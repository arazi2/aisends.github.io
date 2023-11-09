---
title: "Proactive Inverse Learning of Network Topology for Predictive Communication among Unmanned Vehicles"
collection: projects
permalink: /project/UAV
# excerpt: 'TBD'
date: 2023-10-31
# venue: 'TBD'
# paperurl: 'TBD'
# citation: 'TBD'
---

<br>

# Project Synopsis

This project aims to implement an inverse learning framework for Autonomous Vehicles (AVs) for motion-based anomaly detection by modeling and discovering the target decision-making process. We consider the mobility of AVs as a key example of AI-based action planning and aim to identify suspicious activities taken by intruding nodes.

# NSF Project Number #2204721

**Abstract:** The use of unmanned aerial vehicles (UAVs) has become commonplace in many applications nowadays. Like many other technologies, UAVs bring comfort and efficiency to the current practice in many applications while posing threats and safety issues. This project will advance the frontier of science in developing safer and more reliable aerial monitoring platforms while offering privacy and safety. Towards this goal, this project aims to make accurate predictions in UAV networks, by using ** Inverse Learning** techniques, so as to enable safer and more efficient operations.

A smart observation system will be developed to constantly monitor the behavior of autonomous agents to identify suspicious activities by measuring their deviation from the most rational behavior under given conditions. The proposed research includes several steps: (i) to develop mechanisms to simulate the target node's perception of its surrounding environment (i.e., seeing the word from the target's eyes) using deep learning methods, (ii) to predict its rational behavior(s) under given conditions and available resources by modeling the target's decision-making procedure through inverse learning (reading the target's brain), and (iii) to measure the level of trust by detecting rare but critical episodes of deviating from its expected rational behavior. In particular, the mobility of UAVs and their networking activities will be investigated as two important scenarios of malicious activities. This project is expected to result in the development of new tools and algorithms for the action analysis of smart nodes that will be shared with the research community.

The following are some Activities/Products of this Research.

## Research Tasks 1: Mobility Prediction and Profiling
  Develop a unified framework for mobility prediction while offering sufficient flexibility to consider class-specific properties for both aerial and ground unmanned vehicles (UAV/UGV). Our approach integrates model-based kinematics equations with a learning-based data-driven generative mode to enable online learning of class-specific motion capabilities with adaptive processing. Our method addresses the three largely overlooked properties of current methods, including (i) considering class-specific motion properties, (ii) addressing mixed traffic in the presence of human-controlled and Al-based autonomous vehicles, and (iii) addressing rare but informative events.


  <img src="../images/UAV/uav_1.png" width = "80%">
  <img src="../images/UAV/uav_2.png" width = "80%">
<br>

For more information read this [Article] (https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8533579) 



## Research Tasks 2: Perception and Collective Learning Under Imperfect Communication
We develop optimal data aggregation methods for Autonomous Vehicles (AVs) under dynamic environments, by predicting the motion of surrounding vehicles. This project involved developing AI-based scheduling and cooperative perception algorithms for autonomous vehicles and supporting infrastructure. The AI-based scheduling aims to collect data from roadside units (RSUs) to develop learning-based models while accommodating the requirements of dynamic network topology and networking constraints. Our approach to this problem is imposing fairness on class labels (instead of node resources) that enhance the quality of developed models by enhancing the diversity of collected data. We use game theoretic optimization to solve the resulting non-linear non-convex problem. The work opens a new avenue to develop federated learning applications among drones and AVs while meticulously addressing the networking constraints in terms of available channel bandwidth and affordable delay. The preliminary results of this research are published in the 48th IEEE Conference on Local Computer Networks (LCN). 
<img src="../images/UAV/AV_1.jpg" width = "80%">
For more information read this [Article] (https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10223373)



## Research Tasks 3: Cooperative Perception
To enable a better perception of the environment, we are working to develop an algorithm for cooperative perception, where different agents (AVs, or UAVs) share their cameras to extend their visual range. 

 <img src="../images/UAV/AV_cop.jpg" width = "80%">
This is an in-progress work and the early results will appear in the proceedings of the Asilomar Conference on Signals Systems and Computers, 2023.


## Research Task 4: Daviesity-Maximizing Data Accumulation
To broaden the impact of this project to a more general setup of federated learning among autonomous vehicles, the second student is tasked to develop a theoretical foundation for diversity-maximizing data aggregation from autonomous nodes under uncertain networking environments. To this end, we developed a new framework that integrates rate-distortion (RD) theory with determinantal point processes (DPP) to develop a diversity-enhancing data aggregation policy for unmanned ground and aerial vehicles (UGV/UAV) that enhances the quality of deep learning algorithms under federate learning paradigm.  The core idea is to gather imagery from distributed data sets among UAV/UGV nodes that collectively best represent the geometrical features of the entire data set. 

<img src="../images/UAV/DPP1.jpg" width = "80%">
<img src="../images/UAV/DPP2.jpg" width = "80%">

This is an in-progress work and the early results will be presented in this [Preprint] (https://arxiv.org/pdf/2306.02497.pdf) and [Preprint] (https://arxiv.org/pdf/2306.02497.pdf). 

## Research Task 5: Networking Under Predicted Topology
A Key objective of this project is utilizing the predicted network topology and channel conditions to enhance networking efficiency (Al-based networking). To this end, we implemented an application-oriented data-centric communication framework for drones to operate using WiFi and LTE communications in collaboration with MIT-Lincoln Lab.

<img src="../images/UAV/AppSys.png" width = "80%">
For more details, read [this paper] (https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10060823)


## Research Task 6: Actuator Trajectory Planning
We made some initial tests on extending the trajectory planning for actuator UAVs that include overhead manipulators. The goal is to develop RL algorithms to achieve a desired tip trajectory for a given base trajectory.

<img src="../images/UAV/Actuator.png" width = "100%">
<img src="../images/UAV/Actuator1.gif" width = "100%">
![]("../images/UAV/Actuator2.gif")

Preliminary results can be found in [this paper presented in SwarmNet 2023 Workshop] (https://arxiv.org/pdf/2308.12843.pdf)

## Research Task 7: Anomaly Detection and Safety Monitoring
The ultimate goal of this project is Anomaly Detection, or identifying Agents' actions that are not fully aligned with the expected rational behavior obtained by Inverse Learning.  This Aspect includes (i) developing a reverse engineering framework that monitors the environment and target's actions to discover its decision-making strategy, as a baseline, and (ii)  identifying deviations from predicted behavior. The challenges include projecting the observer's perception of the environment to the target's perspective (seeing the world from the target's eyes), determining the target's ultimate goal and reward-generation process (reading the agent's brain), and including potentially unknown factors in the decision-making strategy. To this end, we develop a set of Network-Level Safety Metrics (NSM) to gauge the overall safety of traffic highways with mixt traffic of regular and self-driving vehicles. 

<img src="../images/UAV/TSafety.png" width = "100%">

For more information, please read this [article] (https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9954361)

## Other Research Tasks
Other tasks include developing a learning-based framework for channel error recovery that utilizes sequential learning for exploiting long-term relations among video frames at a bit level.  We also developed algorithms for small object tracking with UAVs as part of this project. 

<br>
<br>
<br>


## Undergraduate Research
Three undergraduate students (Michael Elrod, Rayid Masoo, and John Suchanek)  are recruited to simulate the testing scenarios in simulation environments such as Microsoft AirSIM or ROS/Gazebo (for drones). These two students are also working on developing collective path-planning algorithms for UAV swarms to collectively accomplish a designated task under imperfect observations. Another student is working to develop a practical platform for actuator drones.



<br>
<br>
<br>


# Project Team
## PI: Dr. Abolfazl Razi [arazi@clemson.edu](mailto:arazi@clemson.edu)

## Graduate Students:
- Xiwen Chen
-	Hao Wang
-	Ahmad Sarlak
-	Niloufar Mehrabi
-	Arnau Rovira Sugranes (Graduated)

## Undergraduate Students:
-	William Bain (Graduated)
-	Michel Elrod
-	Rayid Alimasoo
-	John Suchanek

<img src="../images/Lab/RaziTeam2.jpeg" width = "80%">
<img src="../images/Lab/RaziUndergrads.jpg" width = "80%">

<br>
<br>
<br>




# Outcomes
The following papers are the outcome of completing this project. 4 accepted, 1 under review, and 1 in preparation.

## A PhD dissertation titled "Predictive Communications for UAVs" by Arnau Rovira-Sugranes, who was supported by this project. Here is the [Link] (https://www.proquest.com/docview/2572567413?pq-origsite=gscholar&fromopenview=true)

## Journal articles:
  - Razi, A., Chen, X., Li, H., Wang, H., Russo, B., Chen, Y., & Yu, H. (2022). Deep learning serves traffic safety analysis: A forward‐looking review. IET Intelligent Transport Systems.

  - Qu, J., Tang, C., Zhang, Y., Zhou, K., & Razi, A. (2022). Long‐time target tracking algorithm based on re‐detection multi‐feature fusion. IET Cyber‐Systems and Robotics, 4(1), 38-50.

  - Rovira-Sugranes, A., Razi, A., Afghah, F., & Chakareski, J. (2022). A review of AI-enabled routing protocols for UAV networks: Trends, challenges, and future outlook. Ad Hoc Networks, 130, 102790.

  - Chen, X., Wang, H., Razi, A., Russo, B., Pacheco, J., Roberts, J., ... & Head, L. (2022). Network-level Safety Metrics for Overall Traffic Safety Assessment: A Case Study. Submitted to IEEE Access, 2022

  -  Rovira-Sugranes, A., Afghah, F., Qu, J., & Razi, A. (2021). Fully-echoed q-routing with simulated annealing inference for flying Ad Hoc networks. IEEE Transactions on Network Science and Engineering, 8(3), 2223-2234.

## Conference Proceedings:
  - Li, H., Wu, H., Chen, X., Wang, H., & Razi, A. (2021, August). Towards boosting channel attention for real image denoising: Sub-band pyramid attention. In International Conference on Image and Graphics (pp. 303-314). Springer, Cham, 2021.

  -  Qu, J., Zhang, Y., Zhou, K., & Razi, A. (2021, September). Long-Time Target Tracking Algorithm Based on Multi-Feature Fusion and Correlation Filtering. In 2021 4th International Conference on Artificial Intelligence and Pattern Recognition (pp. 29-35), 2021.

  - Chen, X., Li, H., Qu, J., & Razi, A. (2021, January). Boosting Belief Propagation for LDPC Codes with Deep Convolutional Neural Network Predictors. In 2021 IEEE 18th Annual Consumer Communications & Networking Conference (CCNC) (pp. 1-6). IEEE.
  
  -	Sarlak, Ahmad, Abolfazl Razi, Xiwen Chen, and Rahul Amin. "Diversity Maximized Scheduling in RoadSide Units for Traffic Monitoring Applications." In 2023 IEEE 48th Conference on Local Computer Networks (LCN), 1-4. IEEE, 2023.

  -	Wang, Hao, Xiwen Chen, Abolfazl Razi, Michael Kozicki, Rahul Amin, and Mark Manfredo. "Nano-Resolution Visual Identifiers Enable Secure Monitoring in Next-Generation Cyber-Physical Systems." In 2022 International Conference on Computational Science and Computational Intelligence (CSCI). DOI 10.1109/CSCI58124.2022.00227, 2022.

  -	Alzorgan, Hazim, Abolfazl Razi, and Ata Jahangir Moshayedi. "Actuator Trajectory Planning for UAVs with Overhead Manipulator using Reinforcement Learning." arXiv preprint arXiv:2308.12843 (2023), Accepted in SwarmNet Workshop, IEEE International Symposium on Personal, Indoor and Mobile Radio Communications (PiMRC), Toronto, Canada, 2023.

  -	Kaur, Manveen, Abolfazl Razi, Long Cheng, Rahul Amin, and Jim Martin. "Design and Evaluation of an Application-Oriented Data-Centric Communication Framework for Emerging Cyber-Physical Systems." In 2023 IEEE 20th Consumer Communications & Networking Conference (CCNC), 875-878. IEEE, 2023.

  -	Sarlak, Ahmad; Alzorgan, Hazim; Haeri Boroujeni, Sayed Pedram; Amin, Rahul; Razi, Abolfazl, “Cooperative Perception for Connected Autonomous Vehicles under Constrained V2V Networking”, Accepted in Asilomar Conference on Signals Systems and Computers 2023

  -	Chen, Xiwen, Huayu Li, Rahul Amin, and Abolfazl Razi. "RD-DPP: Rate-Distortion Theory Meets Determinantal Point Process to Diversify Learning Data Samples." arXiv preprint arXiv:2304.04137 (2023). Under review for AAAI

  -	Chen, Xiwen, Huayu Li, Rahul Amin, and Abolfazl Razi. "Learning on Bandwidth Constrained Multi-Source Data with MIMO-inspired DPP MAP Inference." arXiv preprint arXiv:2306.02497 (2023). Under Preparation [potentially for IEEE Transactions on Machine Learning in Communications and Networking].


<br>
<br>
<br>


# Training Opportunities
This project provides content for CPSC 4820/6820 titled "AI for Autonomous Vehicles", especially developing several hands-on projects, training modules, and simulation scenarios in virtual environments (SUMO, Webots, Carla).
Here is the syllabus for this [course] (<a href="file:///files/file.pdf">link</a>).

# Capstone Projects
EduPlatCommPro-S19. The Educational Platform for Communication Protocols: AY2018-19
Team Members: Christopher Thompson, Tyler Halperin, Tyler Criss, Huayu Li
[Link:] (https://ceias.nau.edu/capstone/projects/EE/2019/EduPlatCommPro-S19/)


Ground Robotic Design for Predictive Communications
Team Members: Fahad Almaraghi, Yuting Zhang, Qiyuan Huang, Chaoju Wang, Hanxiao Lu
<img src="../images/Undergrads/robot1.png" width = "100%">
([Link:] (https://ceias.nau.edu/capstone/projects/EE/2018/OrdnanceDisposal1/))


Explosive Ordnance Disposal Robot Design
Team Members: Cody Warner, Sixian Zhang, Yazhou Li, Zening Wen, Huiwen Chu
<img src="../images/Undergrads/EOD.png" width = "100%">
[Link:] (https://ceias.nau.edu/capstone/projects/EE/2018/OrdnanceDisposal2/home.html)


<br>
<br>
<br>



# Codes

[Network Level Safety Metrics] (https://github.com/XiwenChen-Clemson/Network-level-safety-metrics)
[Subband Pyramid Network: A new Attention Mechanism for DL] (https://github.com/HuayuLiNAU/Subband-Pyramid-Network)



<br>
<br>
<br>


# Broader Impacts
This project will produce new methods, algorithms, tools, software packages, and product prototypes usable by the CISE research community. This project is expected to advance the frontier of knowledge in the intersection of AI and wireless networking by developing learning algorithms for networking protocols. Our plan will impact the US economy by reducing the networking cost by lubricating the information flow machinery by incorporating the perception of the surrounding environment into networking protocols. The developed knowledge will be incorporated as project topics into related courses in both networking and AI fields taught by the PI and other faculty that impact the large population of female and underrepresented students, especially from Native American and Hispanic origins at NAU. The PI’s several years of industrial experience will help him to translate the developed technology into proof-of-concept products, demos, and patents. The PI plans to apply for the supplement NSF REU grant to translate the research results into projects appropriate for undergraduate students.



