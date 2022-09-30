---
title: "Paper Title Number 3"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2022-04-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper3.pdf'
citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

# Wildfire & Flame Project
Wildfire flame detection based on deep learning & image processing

<!-- [Paper link:](http://academicpages.github.io/files/paper3.pdf) -->

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->


## Background
In this project, we propose a drone-based wildfire monitoring system for remote and hard-to-reach areas. This system utilizes autonomous unmanned aerial vehicles (UAVs) with the main advantage of providing on-demand monitoring service faster than the current approaches of using satellite images, manned aircraft and remotely controlled drones.

![Sample of Dataset](../images/flame.jpg)


Avalible datasets for now:
<a href="https://ieee-dataport.org/open-access/flame-dataset-aerial-imagery-pile-burn-detection-using-drones-uavs">THE FLAME DATASET: AERIAL IMAGERY PILE BURN DETECTION USING DRONES (UAVS)</a>


More information, please reference our previous paper:
<a href="https://ieeexplore.ieee.org/abstract/document/8845309">Wildfire Monitoring in Remote Areas using Autonomous Unmanned Aerial Vehicles</a>


## Flame Detection
This module only uses image processing method to detect flame zone on IR pictures, then draw bounding boxes on related RGB images.

For codes, please go to: [Flame_detection](Flame_detection)

![Flame detection](./images/flame.jpg)
<!-- <img src="./images/Figure%202022-06-30%20001211.png" width="500px"> -->




## Flame Images Generating
This module uses GAN-based deep learning method to generate RGB flame images from given IR image. For example, input an arbitrary IR image of wildfire, the model will generate a virtual RGB image to describe the fire situation.

This part is only on experimental stage, but it's good to research the relationship between the wildfire and its smoke.

For codes, please go to: [Flame_GAN](Flame_GAN)

![Flame GAN](./images/flame.jpg)
<!-- <img src="./images/Figure%202022-06-16%20233050.png" width="500px"> -->





## Contributing
This project is contributed by: 
<a href="hao9@g.clemson.edu">hao9@clemson.edu</a>
<a href="xiwenc@g.clemson.edu">xiwenc@clemson.edu</a>
<a href="bryceh@g.clemson.edu">bryceh@clemson.edu</a>

### Please cite our work if you think this project helps your research.







