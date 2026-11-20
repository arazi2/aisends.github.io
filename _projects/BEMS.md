---
title: "Building Energy Management System for Multi-VAV HVAC in Open Offices"
collection: projects
permalink: /project/bems
# excerpt: 'This paper is proceeding to CSCI 2022.'
date: 2023-10-31
# venue: 'CSCI 2022'
# paperurl: 'https://arxiv.org/abs/2211.08678'
# citation: 'Wang, H., Chen, X. and Razi, A., 2022. Fast Key Points Detection and Matching for Tree-Structured Images. arXiv preprint arXiv:2211.03242.'
---
<br>


### For the code of this project, please see <a href="https://github.com/AIS-Clemson/DRL-BEMS">this link</a>

<br>


# Citation

Recommended citation: 

Wang H, Chen X, Vital N, et al. Energy Optimization for HVAC Systems in Multi-VAV Open Offices: A Deep Reinforcement Learning Approach[J]. arXiv preprint arXiv:2306.13333, 2023.

@article{wang2023energy,
  title={Energy Optimization for HVAC Systems in Multi-VAV Open Offices: A Deep Reinforcement Learning Approach},
  author={Wang, Hao and Chen, Xiwen and Vital, Natan and Duffy, Edward and Razi, Abolfazl},
  journal={arXiv preprint arXiv:2306.13333},
  year={2023}
}

<br>
<br>
<br>
<br>


# Project Overview
we present a DRL-based HVAC control method to optimize building energy consumption in such floor plans. Our specifically designed open office model consists of multiple interconnected spaces, and the DRL algorithm is applied to control multiple VAV units jointly.



The global energy outlook is witnessing a continuous surge in the demand for energy resources, alongside a growing concern for environmental sustainability. With the world's population reaching 8 billion people, our consumption of energy has reached unprecedented levels. The excessive use of energy sources like coal, oil, and natural gas has resulted in the release of harmful greenhouse gases, contributing significantly to the critical issue of global warming. These emissions not only deplete our planet's limited resources but also exacerbate conflicts related to resource availability. This highlights the importance of more informed energy consumption, worldwide.

<br>
<img src="../images/BEMS/commercial_hvac_all.jpg" width="80%">


<br>
<br>


Despite the popularity of open-plan offices in commercial buildings, limited research has been conducted to address the importance of energy optimization in these types of spaces. For instance, VAV units in such offices often operate independently, without considering the interconnectivity of these spaces, which can result in a disparity in heating and cooling, with areas located close to vents receiving more ventilation-based heating/cooling, while spaces near windows receive more heat from solar radiation.

<br>
<img src="../images/BEMS/multi_VAV_2.jpg" width="80%">

<br>
<br>
<br>
<br>


## In short, the contributions of this paper can be summarized as follows:

### We analyze the heat transfer features of connected spaces in open-plan offices and compare their energy consumption to offices with traditional closed floor plans. We offer a formulation for thermal energy exchange that suits open offices.

### We propose a DRL-based control algorithm that simultaneously optimizes thermal comfort and energy efficiency using a multiple-input and multiple-output architecture. It resulted in a 37% reduction in HVAC energy consumption with less than 1% violation of the temperature comfort level and 2.5% violation of humidity comfort level. Note that our model is flexible and can trade off energy efficiency with comfort violation by controlling the tuning parameters.  

### The proposed model requires only minimal input variables, including the outdoor temperature, indoor temperature, time, and control signals. The action space is a binary vector to activate/inactivate enforcing temperature range, instead of using explicit set points. These two approaches make the framework concise and easily generalizable to other buildings. %easily employable.

### We apply a heuristic reward policy to accelerate the training process and reduce the model complexity.

### We introduce a penalty term in the cost function that penalizes frequent inconvenient on/off transitions to avoid discomfort and damage to the HVAC system. 

### Our model is computationally efficient and takes only about 7.75 minutes per epoch (about 40 minutes for 5 epochs) to train. It can be easily adapted to other open-plan offices, making it a universal solution for building energy optimization.

<br>

<img src="../images/BEMS/framework_2.jpg" width="80%">


<br>
<br>
<br>
<br>


For the demonstration of this project, please see <a href="https://github.com/AIS-Clemson/DRL-BEMS">this link</a>

<br>

<img src="../images/BEMS/HVAC_2.0.gif" alt="Training process monitoring" width='100%'>


<br>
<br>
<br>
<br>


# Citation

Recommended citation: 

Wang H, Chen X, Vital N, et al. Energy Optimization for HVAC Systems in Multi-VAV Open Offices: A Deep Reinforcement Learning Approach[J]. arXiv preprint arXiv:2306.13333, 2023.

@article{wang2023energy,
  title={Energy Optimization for HVAC Systems in Multi-VAV Open Offices: A Deep Reinforcement Learning Approach},
  author={Wang, Hao and Chen, Xiwen and Vital, Natan and Duffy, Edward and Razi, Abolfazl},
  journal={arXiv preprint arXiv:2306.13333},
  year={2023}
}