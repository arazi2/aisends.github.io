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
See our project page for the practical implementation and testing:
<a href="https://github.com/AIS-Clemson/VisionGPT" target="_blank">AIS-Clemson/VisionGPT</a>
<a href="https://github.com/JiayouQin/H-Splitter/tree/main" target="_blank">AIS-Clemson/MotorFocus</a>



# Ego-Motion Prediction with All-Pixel Matching <br> Enhanced Navigation for Blind Guidance
This project introduces an advanced anomaly detection system designed to improve navigation safety for visually impaired individuals and robotic navigation systems. At the heart of this system is an innovative image processing technique analyzing real-time imagery to accurately identify and categorize potential hazards.

<div align="center">
    <img src="../images/VisionGPT/HsplitterV2.gif" alt="" style="width: 100%;">
</div>


## Video Stabilization: 
We used SVD and optical flow to estimate the affine transformation matrix from Feature points extracted in two consecutive frames to counteract camera shake, denoising vector extracted.
- **Vanishing Point Estimation**: Using different techniques to estimate the vanishing point as a reference for segmentation
- **Vanishing Point track analysis** We used a low pass filter over consecutive frames for further smoothening.
<div align="center">
    <img src="../images/VisionGPT/frame_3.png" alt="" style="width: 100%;">
</div>


## Anomaly Detection and Alerts
Anomalies trigger alerts for objects detected in the 'Ground' area or those occupying significant space in the 'Left' or 'Right' regions. By focusing on these critical areas, the system efficiently identifies potential navigation hazards. Alert generation is based on object characteristics such as size (objects occupying >10% of the region), position, and movement patterns, providing users with actionable information.






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

