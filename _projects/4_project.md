---
layout: page
title: Vehicle Analytics App
description: a video processing application for detecting and tracking 15 classes of vehicles
img: assets/img/vehicle-analytics-app_image.png
importance: 1
category: work
---

This project was what I spent the majority of the summer of 2023 working on. I had obtained an NSERC USRA that allowed me to work under a professor doing research for the summer, and my task was to develop a video processing application for tracking vehicles in CCTV footage and aggregating some data about the vehicles detected. I luckily had the help of some other lab mates during my time, and they are a big reason why this project got finished!

### What Does It Do?

The main purpose of the application is to take some long CCTV footage of a roadway and output vehicle class counts and their direction of travel. These insights are useful for goods-flow analysis and route optimization, amongst other things. We wanted it to be an iterative application, as the scenario was one in which new data was constantly available. This meant that models could be iteratively improved over time, which is why I ended up putting quite an emphasis on building a solid active learning component and creating functionality for alternative model selection.

The entire project was built in Python, but in the future a web-based interface with a proper backend integrated with a database of processing results would increase usability for clients (this was very out of my scope for the summer unfortunately). The code can be found [here](https://github.com/Jquinny/Vehicle-Analytics-App), and a video demonstration of the application can be found [here](https://drive.google.com/file/d/1F5YM1VlahphWRd3eGtMNBK81S-v46Muk/view?usp=sharing).

### The Journey (and Lessons Learned)

I spent the first part of the summer getting my bearings on the basics of deep learning frameworks and MLOps. I learned a valuable lesson here, and that is to avoid tutorial hell and escape the mindset of "I need to understand everything deeply before attempting to create anything". If I'm being honest, I felt like I had wasted a good chunk of time trying to plan out every little detail I could possibly think of. I felt swamped by all of the choices and technologies that I could've chosen to work with.

If I could go back, I would dedicate a small amount of time at the start for framework research and initial knowledge acquisition. Then, I would've spent another small amount of time planning out a high level path to a finished product that was malleable enough to accomodate the inevitable shortcomings I would find along the way.
The project was built with clients in mind, and working with them was a valuable opportunity. It gave me experience dealing with ill-defined dynamic application requirements, and it also showed me how fun it is to work on a project that will positively impact the lives of others!

With that said, I started making real headway in the latter half of the summer. I had a foundational dataset created and began testing some different models on it. In parallel, I began development on the application itself. Some of the major components of the application were vehicle detection and classification, multi-object tracking,
and active learning. My lab mates assisted with data labeling, model training, and building the graphical user interface. It came down to the wire, but we managed to finish everything up in the nick of time, making final repository pushes on the last day of my work term!

Another very valuable experience I got from this was in the form of academic paper writing and presentation of my work. We managed to get a conference paper published in the 2023 IEEE International Symposium on Multimedia (ISM), and even got a best paper nomination! We also got to present our work at the conference (unfortunately only virtually as we all had finals that week), and that was an experience I will remember for a long time!
