# Mono 3D Detection 
I focus on monocular 3D object detection. In monocular scenario, the main difficulty in neural network focuses on location regression, which keeps huge variance; thus the network is difficult to converge. 

I combines neural network’s estimates with geometric constraints provided by a 2D object bounding box to produce a complete 3D bounding box. This strategy maintains the consistency between 2D-box estimation and 3D-box estimation. The overdetermined equation was solved through SVD decomposition. And the 3D AP of our result can reach 57% (OVERLAP 0.5). Here is part of the visualization result. 
![Geometry](../src/Geometry.png)

![result1](../src/result_1.png)

![result2](../src/result_2.png)

However in truncation cases, geometry constraint will be unsuccessful, here is an example:

![result3](../src/result_4.png)

![result4](../src/result_3.png)


Specially, geometric constraint method have several limitations:
- [x] None truncation scenario: success 3D box estimation.
- [ ] Truncation scenario: failed, because geometry constraint cannot apply to truncated 2D box.
- [ ] End-to-end training : not support, because it relys on 2D detection result. 

Thus my next part of work focuses on padding image to get out boundary 2D box, which solves truncation problem; I also use re-projection error to realize bundle adjustment in training loss, which realizes end-to-end training in nerual network.

![Multi_task.png](../src/Multi_task.png)

