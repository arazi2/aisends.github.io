---
title: "Assistive Visual Navigation"
collection: projects
permalink: /project/VisionGPT
# excerpt: 'TBD'
date: 2024-5-20
# venue: 'TBD'
# paperurl: 'TBD'
# citation: 'TBD'
---


## Project Overview
Assistive visual navigation systems for visually impaired individuals have become increasingly popular thanks to the rise of mobile computing. Most of these devices work by translating visual information into voice commands. In complex scenarios where multiple objects are present, it is imperative to prioritize object detection and provide immediate notifications for key entities in specific directions. This brings the need for identifying the observer’s motion direction (ego-motion) by merely processing visual information, which is the key contribution of this project.
<a href="https://arxiv.org/pdf/2404.17031" target="_blank">Paper</a>

<br> 
See our poster at the BSN 2024: 
<a href="../files/MotorFocus_poster_2.pdf" target="_blank">BSN 2024 Poster</a>

<br>
See our project page for the practical implementation and testing:
<a href="https://github.com/AIS-Clemson/VisionGPT" target="_blank">AIS-Clemson/VisionGPT</a>
<a href="https://github.com/JiayouQin/H-Splitter/tree/main" target="_blank">AIS-Clemson/MotorFocus</a>


# Ego-Motion Prediction with All-Pixel Matching 
This project introduces Motor Focus -- a lightweight, image-based framework designed to predict ego-motion, i.e., the movement intentions of humans (or humanoid machines), using visual input while filtering out camera motion without the need for camera calibration. The framework implements an optical flow-based pixel-wise temporal analysis to account for camera movement, enhanced by a Gaussian aggregation to smooth the predicted movement area.

<div align="center">
    <img src="../images/VisionGPT/HsplitterV2.gif" alt="" style="width: 100%;">
</div>


## Features
Our framework mainly predicts ego-motion by identifying how users physically orient themselves in space through pixel-wise temporal analysis. 

- **Video Stabilization**: To counteract camera shake, we used SVD and optical flow to estimate the affine transformation matrix from feature points extracted in two consecutive frames.
- **Camera Motion Compensation**: The fusion of two consecutive frames filters the camera motion, which highlights the object that moves relatively with the observer.

<div align="center">
    <img src="../images/VisionGPT/frame_3.png" alt="" style="width: 100%;">
</div>



<br>
<br>
<br>


# Project Team
## PI: Dr. Abolfazl Razi [arazi@clemson.edu](mailto:arazi@clemson.edu)

## Graduate Students:
-	Hao Wang
- Xiwen Chen
-	Ashish Bastola

## Undergraduate Students:
-	John Suchanek


## Acknowledgements:
-	Jiayou Qin (Stevens Institute of Technology)
-	Zihao Gong (Tokai University)



# Outcomes

## Conference Proceedings:
  -  Motor Focus: Fast Ego-Motion Prediction for Assistive Visual Navigation (BSN 2024)


# Codes
[VisionGPT](https://github.com/AIS-Clemson/VisionGPT)
<br>
[Motor Focus](https://github.com/JiayouQin/H-Splitter/tree/main)



<br>
<br>
<br>

