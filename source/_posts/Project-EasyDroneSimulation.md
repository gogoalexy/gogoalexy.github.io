---
title: 'Project: EasyDroneSimulation'
date: 2020-08-07 11:03:03
tags:
category: gallery
featured_image: gallery_assets/easydronesimulation.jpg
---

[Github](https://github.com/gogoalexy/EasyDroneSimulation)

While [DroneView](https://gogoalexy.github.io/2020/07/10/Project-DroneView/) already provides a full
 set of tools for flying drone dataset generation, the real flights face challenges from vibration 
interferences and government regulations. It is always great to have a simulation solution for 
backup. Like DoneView, EasyDroneSimulation also collects videos, timestamps, and position 
information.

## Tech Stack
* Simulation: The simulation environment is built with a customized drone model, PX4 SITL(Software-
In-The-Loop), and Gazebo simulator. The position records are stored in rosbag format.
* Container: The project is built with Docker.

## Results

### Recorded video
A simulation flight video.
{% youtube zMvZyrI52jE %}

## Acknowledgements
* This project was funded by [CCLo Lab](https://life.nthu.edu.tw/~lablcc/).
