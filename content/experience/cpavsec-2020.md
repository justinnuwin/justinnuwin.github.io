+++
title = "Cal Poly Autonomous Vehicle Security Group"
date = "2020-06-14"
daterange = "Jan 2017 - Jun 2020"
author = "Undergraduate Researcher"
cover = ""
tags = ["c/c++", "autonomous vehicles", "image processing", "OpenCV", "python", "machine learning", "object detection"]
keywords = ["unreal engine", "simulation", "keras"]
description = "I developed image processing pipelines for autonomous vehicles (AVs) and architected an extensible simulator for AVs using Microsoft AirSim and Unreal Engine."
showFullContent = false
+++

The Cal Poly Autonomous Vehicle Security Group is headed by Dr. Bruce DeBruhl who is involved in security research for autonomous vehicles, IOT devices, and all things networked.
The projects I have worked on in this group have been primarily focused towards the security of platoons of autonomous vehicles.
Vehicle platoons require extensive communication to stay cohesive and ensure that no collisions occur. 
The two paradigms that vehicles communicate are vehicle-to-vehicle (V2V) using a protocol like DSRC or vehicle-to-infrastructure (V2I) usually using cellular infrastructure like 4G-LTE and 5G.

### Scale Platoon Project

The first year I joined the group, I provided assistance on a [master's thesis](https://digitalcommons.calpoly.edu/theses/2057) and [senior project](https://digitalcommons.calpoly.edu/cpesp/249) both utilizing the same scale platoon platform using RC cars.
On these projects I developed real-time image processing pipelines to detect the other RC cars in the platoon and follow them.
This was done in C++ using the OpenCV library.
Due to the lack of imagery for "RC cars with electronics mounted on top", pure image processing algorithms had to be used over machine learning or data-driven methods.
Some techniques used were distinct optical tracking markers, SIFT Features, optical flow, and sensor fusion were used to detect then track the movement of vehicles.
Since this had to run in real-time CUDA accelerated implementations were used along with the Nvidia Jetson platform.
In addition to the computer vision work, I also helped design the power distribution system for these vehicles and some of the microcontroller code to communicate with sensors like LiDAR, ultrasonic sensors, and IMUs.

### Autonomous Vehicle Simulator

At the end of my third-year at Cal Poly, I started working on a new project in the group which was an autonomous vehicle simulator following the same line of thought for the scale platoon project, but not focusing on simulating life-sized vehicles on simulated roads.

- Develop vision-based lane following pipeline using OpenCV to allow simulated AV to drive on roads
- Develop autonomous perception and sensor fusion module for autonomous driving
- Design self-driving control architecture of simulated vehicle in residential environment using Microsoft Airsim and Unreal Engine
- Implement occupancy grid based local navigation system to navigate autonomous vehicle on residential streets
- Implement cascaded PID controller to drive autonomous vehicle
