# computerVision A
This repo contains some crucial computer vision tasks including: <br>
•	Homography which warps an image took by phone into an image similar to the one obtained through a scanner - hw2 <br>
•	Photometric Stereo, Specularity Removal and Surface Rendering - hw2 & hw3 <br>
•	Edge Detection with Non-Maximum Suppression - hw3 <br>
•	Implementing multiple sparse stereo matching methods - hw4 <br>
•	Implement Optical Flow with Multi-resolution Lucas-Kanade - hw5 <br>

## Homework Results Demonstration

### HW2 - Homography warpping

Original Image
<img src="./Results_demo/photo.jpg" alt="photo" style="zoom:20%;" />
Homography Warpped Image
<img src="./Results_demo/warp2.png" alt="warp2" style="zoom:22%;" />

UCSD Logo and wrapped version:

![logo_and_wrap](./Results_demo/logo_and_wrap.png)

### Hw3: Photometric Stereo, Specularity Removal and Surface Rendering

Table:

<img src="./Results_demo/hw2_table.png" alt="hw2_table" style="zoom:0%;" />

__Surface Rendering Results__:

(1) Lambertian model:

<img src="./Results_demo/lambertian_pear.png" alt="lambertian" style="zoom:65%;">               <img src="Results_demo/Lambertian_sphere.png" alt="Lambertian_sphere" style="zoom:72%;">

(2) Phong model:

(A) For Sphere

![phong_shpher_1](./Results_demo/phong_sphere_1.png)

![phong_sphere_1](./Results_demo/phong_sphere_2.png)

(B) For Pear:

![phong_pear_1](./Results_demo/phong_pear_1.png)

![phong_pear_2](./Results_demo/phong_pear_2.png)

 __Specularity Removal__:

<img src="./Results_demo/Specularity Removal.png" alt="__Specularity Removal__" style="zoom:90%;">

__Robust Photometric Stereo__:

(A) For Sphere:

![photo_stereo_sphere_1](./Results_demo/photo_stereo_sphere_1.png)

![photo_stereo_sphere_2](./Results_demo/photo_stereo_sphere_2.png)

![photo_stereo_sphere_3](./Results_demo/photo_stereo_sphere_3.png)

![photo_stereo_sphere_4](./Results_demo/photo_stereo_sphere_4.png)

(B) For Sphere

![photo_stereo_pear_1](./Results_demo/photo_stereo_pear_1.png)



![photo_stereo_pear_2](./Results_demo/photo_stereo_pear_2.png)

![photo_stereo_pear_3](./Results_demo/photo_stereo_pear_3.png)

![photo_stereo_pear_4](./Results_demo/photo_stereo_pear_4.png)

### Hw3: Edge Detection with Non-Maximum Suppression

Original Image:

<img src="./Results_demo/original_edge_detection.png" alt="original_edge_detection" style="zoom:50%;" />

Gradient Magnitude:

<img src="./Results_demo/gradient_edge_detection.png" alt="gradient_edge_detection" style="zoom:50%;" />

NMS with 5x5 window:

<img src="./Results_demo/nms_edge_detection.png" alt="nms_edge_detection" style="zoom:50%;" />



### HW4: multiple sparse stereo matching

(1) Corner Detection

![corner_detection_1](./Results_demo/corner_detection_1.png)

![corner_detection_2](./Results_demo/corner_detection_2.png)



(2) An exmaple of Naive Matching

![naive_Matching](./Results_demo/naive_Matching.png)

(3) Epipolar Line plotting:

![epipolar_line](./Results_demo/epipolar_line.png)

(4) Image Rectification

![image_rectification](./Results_demo/image_rectification.png)

(5) Matching Using epipolar geometry

![matching_epipolar](./Results_demo/matching_epipolar.png)

### HW5: Optical Flow with Multi-resolution Lucas-Kanade 

(1) Moving left and up

![opticalFlow_leftup](./Results_demo/opticalFlow_leftup.png)

(2) Rotate

![opticalFlow_rotate](./Results_demo/opticalFlow_rotate.png)

(3) Zoom In

![opticalFlow_zoomIn](./Results_demo/opticalFlow_zoomIn.png)

