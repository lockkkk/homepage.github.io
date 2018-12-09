## About me

Hi, I'm Jiaxin. I'm currently a undergraduate student in BeiJing. I am interest in computer vision, image undersatnding. Specifically, I am interested in high-level, symbolic processes of image recognition and interpretation that accurately model the way people interact with the world.

Besides, I also dive into the field of networking and system, now I am a research intern in the Network Research group of Microsoft Research Asia (MSRA). My CV is available on the right side (updated Dec 2018).

## My Project

### Free Virtual Piano System
1. General goal:
- translate hand movement on paper with printed piano keys to music. 

2. Demo:
![Magic Piano](src/piano.mp4)

3.Detail:
[Link](url)

### Mono 3D Detection -part 1-
1. General goal:
- Combining neural network’s estimates with geometric constraints provided by a 2D object bounding box to produce a complete 3D bounding box. 

2. Structure:
![Geometry](src/Geometry.png)

3.Detail:
[Link](url)

### Mono 3D Detection -part 2-
1. General goal:
- Padding image to get out boundary 2D box, to solve truncation problem.
- Using re-projection error to realize bundle adjustment in training loss. Realize end-to-end training.

2. Structure:
![Re-projection](src/Multi_task.png)

### Semiautomatic annotation work
1. General goal:
- Use CAD models to generate key-point label on real images in KITTI dataset for future network training.
- Generate visible type for each labeled point.

2. Sample:
![Semiautomatic_annotation](src/Annotation.png)

3.Detail:
[Link](url)

### Bird-view lane detection
1. General goal:
- Using vanishing point to adaptively transform image into bird view.
- Detecting lane lines in bird view using FCN-based neural network architecture.
- Tracking the lane lines by semi-dense direct visual odometry and Kalman Filter.


2. Demo:
![Lane_detection&tracking](src/Annotation.png)


