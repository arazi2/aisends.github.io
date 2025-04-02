---
title: "Assistive Visual Navigation"
collection: projects
permalink: /project/VisionGPT
# excerpt: 'TBD'
date: 2025-3-20
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



# VIA-LLM: Visually Impaired Assistive Tool with LLM Reasoning (under developing) 
Globally, over two billion people suffer from vision impairment, with approximately 43 million classified as legally blind \cite{who_blindness}. Some eye diseases, such as Retinitis Pigmentosa (RP), lead to gradual vision loss and currently have no cure. Most treatments for such genetics-driven diseases – including gene therapy (e.g., Luxturna for specific mutations), stem cells, artificial retinal implants, and vitamin A supplementation – have shown only minor effects in restoring lost vision and remain in exploratory stages for decades. For such conditions, developing assistive tools arises as a promising alternative to enable patients to manage their daily tasks and live more independently. 



## Computer Vision

### Object detection/segmentation
<div align="center">
    <img src="../images/VisionGPT/JP_Shinjuku_1.gif" alt="" style="width: 100%;">
</div>

### Motion-based analysis
<div align="center">
    <img src="../images/VisionGPT/JP_Shinjuku_4.gif" alt="" style="width: 100%;">
</div>

### Simulated visual impairment-sensing
"Less is better." 
<div align="center">
    <img src="../images/VisionGPT/JP_Shinjuku_3.gif" alt="" style="width: 100%;">
</div>



## Assistive agent
### Early detection & feedback
<div align="center">
    <img src="../images/VisionGPT/JP_Shinjuku_4.gif" alt="" style="width: 100%;">
</div>


### Voice boardcast & alert
<div align="center">
    <img src="../images/VisionGPT/JP_1.gif" alt="" style="width: 100%;">
</div>











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

