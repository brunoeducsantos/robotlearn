---
layout: page
title: Projects
permalink: /projects/
---


---
## 3D Vehicle Tracking
In [this project](https://github.com/brunoeducsantos/3D-Vehicle-Tracking) the following keys concepts were developed:
* Keypoint detectors and descriptors
* Object detection using the pre-trained YOLO deep-learning framework
* Methods to track objects by matching keypoints and bounding boxes across successive images
* Associating regions in a camera image with lidar points in 3D space
* Estimate TTC (aka Time-To-Collision) using LiDAR and camera key point matching

![]({{ site.url }}{{ site.baseurl }}/images/ttc_estimation.png)

---
## Follow Me 

 In [this project](https://github.com/brunoeducsantos/Follow-Me), a deep neural network was used to identify and track a target in simulation. 
 
 So-called “follow me” applications like this are key to many fields of robotics and the very same techniques you apply here could be extended to scenarios like advanced cruise control in autonomous vehicles or human-robot collaboration in industry. 

 ![]({{ site.url }}{{ site.baseurl }}/images/followme.png)

---
## LiDAR Vehicle Detection

The goal of [project](https://github.com/brunoeducsantos/Lidar-Obstacle-Detection) is apply segmentation of objects around the ego motion car and as a result detect obstacles around it using LiDAR data. In this project, the following tasks were completed:

* Implementation of customized [3D Ransac](https://github.com/brunoeducsantos/Lidar-Obstacle-Detection/blob/master/src/processPointClouds.cpp)
* Implementation of [KDTree](https://github.com/brunoeducsantos/Lidar-Obstacle-Detection/blob/master/src/kdtree.h)
* Implementation of [pre-processing cloud pipeline](https://github.com/brunoeducsantos/Lidar-Obstacle-Detection/blob/master/src/processPointClouds.cpp)


 ![]({{ site.url }}{{ site.baseurl }}/images/lidar.gif)
