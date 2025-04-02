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



# (2025) VIA-LLM: Visually Impaired Assistive Tool with LLM Reasoning (under developing) 
Globally, over two billion people suffer from vision impairment, with approximately 43 million classified as legally blind \cite{who_blindness}. Some eye diseases, such as Retinitis Pigmentosa (RP), lead to gradual vision loss and currently have no cure. Most treatments for such genetics-driven diseases – including gene therapy (e.g., Luxturna for specific mutations), stem cells, artificial retinal implants, and vitamin A supplementation – have shown only minor effects in restoring lost vision and remain in exploratory stages for decades. For such conditions, developing assistive tools arises as a promising alternative to enable patients to manage their daily tasks and live more independently. 


<!-- 
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

 -->









# (2024) Ego-Motion Prediction with All-Pixel Matching 
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









<!-- 
# (2024) VisionGPT: LLM-Assisted Real-Time Anomaly Detection for Safe Visual Navigation

## Use
Copy/Download the repository, replace the API key in OPENAI_API_KEY.yaml, and run the demo.py.


## Demonstration
<div align="center">
    <img src="../images/VisionGPT/JP_1.gif" alt="Framework" style="width: 60%;">
</div>

See our another project for the movement prediction: <a href="https://github.com/JiayouQin/H-Splitter" target="_blank">H-Splitter</a>


## Overview
This project explores the potential of Large Language Models(LLMs) in zero-shot anomaly detection for safe visual navigation. 

<br>

With the assistance of state-of-the-art real-time open-world
object detection model Yolo-World and specialized prompts, the proposed framework can identify anomalies within camera-captured frames that include any possible obstacles, then generate
concise, audio-delivered descriptions emphasizing abnormalities, assist in safe visual navigation
in complex circumstances. 


<div align="center">
    <img src="../images/VisionGPT/frame.png" alt="Framework" style="width: 70%;">
</div>

Moreover, our proposed framework leverages the advantages of LLMs
and the open-vocabulary object detection model to achieve the dynamic scenario switch, which
allows users to transition smoothly from scene to scene, which addresses the limitation of traditional
visual navigation. 

Furthermore, this project explored the performance contribution of different prompt
components provided the vision for future improvement in visual accessibility and paved the way
for LLMs in video anomaly detection and vision-language understanding.


## Method

### Yolo-World
We apply the latest Yolo-world for the open-world object detection task to adapt the system in any scenario any situation. The detection classes are generated by GPT-4 and can be replaced dynamically.

<div align="center">
    <img src="../images/VisionGPT/dt_classes.png" alt="Detection classes" style="width: 60%;">
</div>

### GPT-3.5
We apply GPT-3.5 for fast response and low cost. We have tested GPT-4 and GPT-4V but found them not financial-friendly.

<div align="center">
    <img src="../images/VisionGPT/prompt.png" alt="Sample results" style="width: 60%;">
</div>


### H-splitter
We implemented an H-splitter to assist object detection and categorize the objects into 3 different types based on the priority. 

<div align="center">
    <img src="../images/VisionGPT/H_2.jpg" alt="H-splitter" style="width: 60%;">
</div>

See our another project for more info: <a href="https://github.com/JiayouQin/H-Splitter" target="_blank">H-Splitter</a>




## Experiments
We use Yolo-World with the H-splitter for universal object detection. For any object that falls (a)in Area 3 or (b)in Area 1/2 with 15% of window size, we record the corresponding frame as anomalies. We set this Yolo-World-H setting as the ground truth for the benchmark.

### System Sensitivity
We pre-set the system with 3 different sensitivities to report the emergency: low, normal, and high. We find that the low system sensitivity is good for daily use due to the low false alarm rate.

<div align="center">
    <img src="../images/VisionGPT/Figure_8.png" alt="System Test" style="width: 50%;">
</div>

### Detection accuracy
We compare the VisionGPT with low system sensitivity with the ground truth to evaluate its performance. We find that VisionGPT has high Accuracy and prefers less False Positive (unnecessary reports).

<div align="center">
    <img src="../images/VisionGPT/Figure_9.png" alt="Performance Test" style="width: 60%;">
</div>

### System Performance & Compatibility
<div align="center">
    <img src="../images/VisionGPT/fps.png" alt="System performance" style="width: 80%;">
</div>

### Cost Evaluation
<div align="center">
    <img src="../images/VisionGPT/cost.png" alt="Financial cost test" style="width: 70%;">
</div>



### Acknowledgements:

Please cite our work if you find this project helpful.
```bibtex
@article{wang2024visiongpt,
  title={VisionGPT: LLM-Assisted Real-Time Anomaly Detection for Safe Visual Navigation},
  author={Wang, Hao and Qin, Jiayou and Bastola, Ashish and Chen, Xiwen and Suchanek, John and Gong, Zihao and Razi, Abolfazl},
  journal={arXiv preprint arXiv:2403.12415},
  year={2024}
}
```



 -->








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

