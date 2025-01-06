---
title: 'Project: VisionBot'
date: 2020-08-11 12:12:12
tags:
category: gallery
featured_image: gallery_assets/visionbot.png 
---

[Github](https://github.com/gogoalexy/VisionBot)

VisionBot is a collection of several utilities for obstacle detection algorithm path-finding. 
The project contains the following modules:
1. Optical flow calculator: Calculate the optical flow to a given video or a video stream and plot 
the flow vectors on the top of the video.
2. MagicMotion: A video clip generator for optical flow verification. The module applies 
translation, rotation or stretching to a static image.
3. IQIF obstacle avoidance detector: preliminary results to the developed algorithm.

## Tech Stack
* Development: The obstacle avoidance algorithm demo is implemented on a Raspberry Pi.
* Programming languages: The major part of the application is written in Python and Qt, and the IQIF 
neural simulator is written in C++ in consideration of efficiency.
* Algorithms: Most of the image processing algorithms are called from the OpenCV library with 
Python binding.

## Acknowledgements
1. Thanks to my teammate [Cheng-Fu Yeh](https://github.com/twetto)'s algorithmic insights to the 
obstacle avoidance module and he is also the author of the IQIF 
(Integer Quadratic Integrate-and-Fire) neural simulator.
2. Thanks to the team leader Cheng-Te Wang for his precious suggestions for the project.
