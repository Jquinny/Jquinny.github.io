---
layout: page
title: Autonomous Foosball, With a Twist!
description: an autonomous 1v1 foosball/pong style robotic system
img: assets/img/312-project_image.jpg
importance: 1
category: school
---
This project is an autonomous system where two robots play a foosball/pong like game against each other, attempting to either score on each other, or pass for as long as possible. It was built by a group of three of us taking **CMPUT 312 - Introduction to Robotics and Mechatronics** as our final course project. It makes use of various topics we learned throughout the course and on our own, such as forward and inverse kinematics, thread programming, computer vision, trajectory estimation, and more.

My contributions were on the computer vision side as well as arena assembly (since I was the only one with wood and tools on hand). The construction was a nice breath of fresh air where I got to work with my hands and physically manifest something (I'm so used to doing work purely in the virtual realm, which is weird to think about). On the computer vision side I had to calibrate the camera to get accurate ball position estimates and then implement ball detection and tracking.

During initial project planning I had come up with many ideas for how I wanted to tackle the computer vision aspects. After some thinking and troubleshooting, I quickly realized that complex algorithms that are both slightly inefficient and way more bug-friendly were going to bring more pain than gain. I stuck with simple and efficient image processing techniques and trajectory estimations, which was a nice introduction to realistic engineered environment project settings.

For a more in depth explanation of the project, you can read our [paper](https://drive.google.com/file/d/1D_Xng_zkUOHNvnRvWYmK_6wHN3MmuqtN/view)!
