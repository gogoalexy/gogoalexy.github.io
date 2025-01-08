---
title: 'Project: DroneView'
date: 2020-07-10 11:46:46
tags:
category: gallery
featured_image: gallery_assets/droneview.png
---

[Github](https://github.com/gogoalexy/DroneView)

In order to evaluate obstacle avoidance algorithms for drones, DroneView is a toolkit for recording 
benchmarking data on an in-house design drone. DoneView collects the following data:
* Video captured by a downward-facing camera
* Timestamps
* 3-dimentional positions in local coordinates

There is also a visualization module in the project that makes those data easy to perceive (shown 
in the **Results** section).

## Tech Stack
* Programming languages: The program is written in Python on a Raspberry Pi, and a shell script 
invokes the recording program on start-up.
* Drone technology: The drone was assembled in-house using open-source flight control software 
[PX4](https://px4.io/).
* 3D printing: The Raspberry Pi board and camera were attached to the drone in a 3D printed payload 
box.

## Results
### In-house built drone
![quadcoptor](drone.png)

### Recorded video
A selected flight video.
{% youtube 87Wy3IQlrzA %}

### Position records
The recorded flight data from the same mission as the video above.
![flight data](velocity_path_position.png)

## Acknowledgements
* This project was funded by [CCLo Lab](https://life.nthu.edu.tw/~lablcc/).
