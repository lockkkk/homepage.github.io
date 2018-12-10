# Semiautomatic annotation
In this project, I use CAD models to generate 2D point coordinates on real images in KITTI dataset, and each label has a visible type. I defined 20 key points for each CAD modle. Besides, there are 4 types of visibility:

- Self-occlusion (Yellow &#x1F49B;)
- Other-occlusion (Blue &#x1F499;)
- Truncation (Green &#x1F49A;)
- Visible (Red ❤️)

Here is the system structure:

![system_structure](../src/Annotation_structure.png)


And here is the visualization result:

<img src="../src/aresult_1.png" width="100%" />

<img src="../src/aresult_2.png" width="100%" />

<img src="../src/aresult_3.png" width="100%" />

