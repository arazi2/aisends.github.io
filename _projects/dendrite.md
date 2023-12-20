---
title: "Nano-Resolution Visual Identifiers Enable Secure Monitoring in Next-Generation Cyber-Physical Systems"
collection: projects
permalink: /project/dendrite
# excerpt: 'This paper is proceeding to CSCI 2022.'
date: 2023-08-15
# venue: 'CSCI 2022'
# paperurl: 'https://arxiv.org/abs/2211.08678'
# citation: 'Wang, H., Chen, X. and Razi, A., 2022. Fast Key Points Detection and Matching for Tree-Structured Images. arXiv preprint arXiv:2211.03242.'
redirect_from: 
  - /projects/dendrite
---



# Project Team
## PI: Dr. Abolfazl Razi [arazi@clemson.edu](mailto:arazi@clemson.edu)
- Chriss Mann
- Michael Kozicki

## Graduate Students:
- Xiwen Chen
-	Hao Wang
- Huayu Li (Graduated)
-	Ali Valehi (Graduated)
-	Jiaming Chen(Graduated)


<br><br><br><br>




# Lab Equipments

<img src="../images/Nano/equipments.png" width="80%">


<br><br><br><br>




# Research Products

Valehi, Ali, et al. "A graph matching algorithm for user authentication in data networks using image-based physical unclonable functions." 2017 Computing Conference. IEEE, 2017.
<a href="https://ieeexplore.ieee.org/abstract/document/8252196" target="_blank">Paper Link</a>
<a href="">Code</a>



<br>

Chi, Zaoyi, et al. "Consistency penalized graph matching for image-based identification of dendritic patterns." IEEE Access 8 (2020): 118623-118637.
<a href="https://ieeexplore.ieee.org/abstract/document/9126787" target="_blank">Paper Link</a>
<a href="">Code</a>

<br>

Li, Huayu, et al. "Deep DIH: Statistically inferred reconstruction of digital in-line holography by deep learning." arXiv preprint arXiv:2004.12231 (2020).
<a href="https://arxiv.org/abs/2004.12231" target="_blank">Paper Link</a>
<a href="">Code</a>

<br>

Chen, Xiwen, et al. "DH-GAN: a physics-driven untrained generative adversarial network for holographic imaging." Optics Express 31.6 (2023): 10114-10135.
<a href="https://opg.optica.org/oe/fulltext.cfm?uri=oe-31-6-10114&id=527879" target="_blank">Paper Link</a>
<a href="">Code</a>

<br>

Wang, Hao, et al. "Fast key points detection and matching for tree-structured images." 2022 International Conference on Computational Science and Computational Intelligence (CSCI). IEEE, 2022.
<a href="https://ieeexplore.ieee.org/abstract/document/10216721" target="_blank">Paper Link</a>
<a href="">Code</a>

<br>

H. Wang, X. Chen, A. Razi, M. Kozicki, R. Amin and M. Manfredo, "Nano-Resolution Visual Identifiers Enable Secure Monitoring in Next-Generation Cyber-Physical Systems," 2022 International Conference on Computational Science and Computational Intelligence (CSCI), Las Vegas, NV, USA, 2022, pp. 856-861, doi: 10.1109/CSCI58124.2022.00155.
<a href="https://ieeexplore.ieee.org/document/10216773" target="_blank">Paper Link</a>
<a href="">Code</a>

<br><br><br><br>







# Project Overview
In recent years, Physically Unclonable Functions (PUFs) have garnered significant attention for enhancing security mechanisms in applications like the Internet of Things (IoT), leveraging the inherent randomness in device-specific characteristics. This approach complements traditional security algorithms, which face increased vulnerabilities due to advances in computational technology and automated hacking systems. In this project, we propose a novel authentication mechanism based on a specific implementation of PUFs using metallic dendrites—nanomaterial devices characterized by unique, complex, and unclonable patterns akin to human DNA. We introduce a method for processing dendrite images, encompassing denoising, skeletonization, pruning, and feature point extraction. These feature points are represented using a tree-based weighted algorithm, transforming the authentication challenge into a graph matching problem. To identify and authenticate users, the test object is compared against a database of valid patterns through a novel algorithm. Our method exhibits high accuracy, low computational complexity with linear growth concerning extracted points and database size, and significantly reduces in-network storage and communication requirements in large-scale networks. Additionally, we explore digital in-line holography for reconstructing 3D images from 2D holograms, addressing challenges in removing twin images caused by phase-conjugate wavefronts. We introduce an autoencoder-based deep learning architecture for single-shot hologram reconstruction, eliminating the need for extensive datasets for training. Furthermore, we propose a generative adversarial network-based DL architecture for hologram reconstruction, offering explainability, transferability, and robustness to noise. Lastly, we present an authentication algorithm for nano-resolution visual identifiers with tree-shaped patterns, particularly focusing on dendrites. Our algorithm includes image-to-tree conversion, graph matching, and features improvements for real-world applications, ensuring accuracy and scalability. In the context of supply chain security, we introduce an end-to-end system employing dendrites as nano-resolution visual identifiers to secure product tracking. The system comprises back-end programming, mobile device applications, and a cloud database, addressing personalization, registration, inspection, 2D graph matching, and 3D image authentication. Our two-step search approach enhances scalability by limiting the search space to samples with high similarity scores. This comprehensive solution fortifies dendrites against adversarial attacks and contributes to the security of modern supply chains relying on cyber-physical systems.

Specifically, we present a solution for secure monitoring in supply chains with nano-resolution visual identifiers-based cyber-physical systems.
In this project, nano-reoslution samples are used for identification and authentication process. 

<p align="center">
  <img src="../images/Nano/sample.png" width="30%">
</p>

The dendritic samples are electro-chemical generated nano-materials and is customizable in terms of scale and morphology complexity. 

Compare to the conventional barcode or QR code-based methods, our solution provide high-level security due to the randomness and high entropy information of dendritic samples. Meanwhile, our computer vision-based algorithm provides a competitive computation cost.

<img src="../images/Nano/2_2.jpg" width="100%">



<br><br><br><br>





## Subproject 1: Top-Down Graph Matching Algorithm 
Recently, Physically Unclonable Functions (PUFs) received considerable attention in order to developing security mechanisms for applications such as Internet of Things (IoT) by exploiting the natural randomness in device-specific characteristics. This approach complements and improves the conventional security algorithms that are vulnerable to security attacks due to recent advances in computational technology and fully automated hacking systems. In this project, we propose a new authentication mechanism based on a specific implementation of PUF using metallic dendrites. Dendrites are nanomaterial devices that contain unique, complex and unclonable patterns (similar to human DNAs). We propose a method to process dendrite images. The proposed framework comprises several steps including denoising, skeletonizing, pruning and feature points extraction. The feature points are represented in terms of a tree-based weighted algorithm that converts the authentication problem to a graph matching problem. The test object is compared against a database of valid patterns using a novel algorithm to perform user identification and authentication. The proposed method demonstrates a high level of accuracy and a low computational complexity that grows linearly with the number of extracted points and database size. It also significantly reduces the required in-network storage capacity and communication rates to maintain database of users in large-scale networks.

<img src="../images/Nano/ali_1.png" width="80%">

Demonstration of the proposed algorithm to find similarity between the test graph and a set of reference graphs. Top row presents sub graph mapping stage. The bottom row, represents identification and recovery of level change by the proposed modified algorithm.

### Research Publication:
Valehi, Ali, et al. "A graph matching algorithm for user authentication in data networks using image-based physical unclonable functions." 2017 Computing Conference. IEEE, 2017.


<br><br><br><br>


## Subproject 2: Ad-hoc Consistency Penalized Probabilistic Graph Matching 
Recently, physically unclonable functions (PUFs) have received considerable attention from the research community due to their potential use in security mechanisms for applications such as the Internet of things (IoT). The concept generally employs the fabrication variability and naturally embedded randomness of device characteristics for secure identification. This approach complements and improves upon the conventional cryptographic security algorithms by covering their vulnerability against counterfeiting, cloning attacks, and physical hijacking. In this work, we propose a new identification/authentication mechanism based on a specific implementation of optical PUFs based on electrochemically formed dendritic patterns. Dendritic tags are built by growing unique, complex, and unclonable nano-scaled metallic patterns on highly nonreactive substrates using electrolyte solutions. Dendritic patterns with 3D surfaces are technically impossible to reproduce, hence they can be used as the fingerprints of objects. Current optical PUF-based identification mechanisms rely on image processing methods that require high-complexity computations and massive storage and communication capacity to store and exchange high-resolution image databases in large-scale networks. To address these issues, we propose a light-weight identification algorithm that converts the images of dendritic patterns into representative graphs and uses a graph-matching approach for device identification. More specifically, we develop a probabilistic graph matching algorithm that makes linkages between the similar feature points in the test and reference graphs while considering the consistency of their local subgraphs. The proposed method demonstrates a high level of accuracy in the presence of imaging artifacts, noise, and skew compared to existing image-based algorithms. The computational complexity of the algorithm grows linearly with the number of extracted feature points and is therefore suitable for large-scale networks.

<img src="../images/Nano/zaoyi_1.png" width="80%">

The image processing steps applied to the reference dendrite (top row) and the noisy version of the test dendrite (bottom row). The columns represent: (a) the original image, (b) the Image in YCbCr space, (c) the image after segmentation, (d) the binarized image, (e) the extracted and thinned skeleton, (f) the extracted graph vertices (feature points), and (g) the representative graph.

### Research Publication:
Chi, Zaoyi, et al. "Consistency penalized graph matching for image-based identification of dendritic patterns." IEEE Access 8 (2020): 118623-118637.



<br><br><br><br>



## Subproject 3: Autoencoders with deep Prior for 3D Image Reconstruction  
Digital in-line holography is commonly used to reconstruct 3D images from 2D holograms for microscopic objects. One of the technical challenges that arise in the signal processing stage is removing the twin image that is caused by the phase-conjugate wavefront from the recorded holograms. Twin image removal is typically formulated as a non-linear inverse problem due to the irreversible scattering process when generating the hologram. Recently, end-to-end deep learning-based methods have been utilized to reconstruct the object wavefront (as a surrogate for the 3D structure of the object) directly from a single-shot in-line digital hologram. However, massive data pairs are required to train deep learning models for acceptable reconstruction precision. In contrast to typical image processing problems, well-curated datasets for in-line digital holography does not exist. Also, the trained model highly influenced by the morphological properties of the object and hence can vary for different applications. Therefore, data collection can be prohibitively cumbersome in practice as a major hindrance to using deep learning for digital holography. In this paper, we proposed a novel implementation of autoencoder-based deep learning architecture for single-shot hologram reconstruction solely based on the current sample without the need for massive datasets to train the model. The simulations results demonstrate the superior performance of the proposed method compared to the state of the art single-shot compressive digital in-line hologram reconstruction method.

<img src="../images/Nano/huayu_1.png" width="80%">

For the deep convolutional autoencoder with hourglass architecture used in this paper. We deploy Batch Normalization after each convolution layer except the last three layers to stabilize the training steps.

### Research Publication:
Li, Huayu, et al. "Deep DIH: Statistically inferred reconstruction of digital in-line holography by deep learning." arXiv preprint arXiv:2004.12231 (2020).


<br><br><br><br>


## Subproject 4: Transferrable Generative Models for 3D Image Reconstruction  
Digital holography is a 3D imaging technique by emitting a laser beam with a plane wavefront to an object and measuring the intensity of the diffracted waveform, called holograms. The object’s 3D shape can be obtained by numerical analysis of the captured holograms and recovering the incurred phase. Recently, deep learning (DL) methods have been used for more accurate holographic processing. However, most supervised methods require large datasets to train the model, which is rarely available in most DH applications due to the scarcity of samples or privacy concerns. A few one-shot DL-based recovery methods exist with no reliance on large datasets of paired images. Still, most of these methods often neglect the underlying physics law that governs wave propagation. These methods offer a black-box operation, which is not explainable, generalizable, and transferrable to other samples and applications. In this work, we propose a new DL architecture based on generative adversarial networks that uses a discriminative network for realizing a semantic measure for reconstruction quality while using a generative network as a function approximator to model the inverse of hologram formation. We impose smoothness on the background part of the recovered image using a progressive masking module powered by simulated annealing to enhance the reconstruction quality. The proposed method exhibits high transferability to similar samples, which facilitates its fast deployment in time-sensitive applications without the need for retraining the network from scratch. The results show a considerable improvement to competitor methods in reconstruction quality (about 5 dB PSNR gain) and robustness to noise (about 50% reduction in PSNR vs noise increase rate).


While the key points information can be extracted from the 2D images, richer information such as depth and phase can be retrival from another advanced optical photography method, which is Digital Holograph (DH). 

<img src="../images/Nano/DH_lab_1.png" width="80%">

Digital Holograph is used to recover the phase information of samples. In order to generate the phase information, we apply Digital In-line Holography (DIH) to the real samples, and obtain the generated hologram from a regular CMOS. 

<img src="../images/Nano/dendrite_to_3D.png" width="80%">

Through deep learning-based methods, the phase information can successfully been reconstructed from the hologram. 


### Research Publication:
Chen, Xiwen, et al. "DH-GAN: a physics-driven untrained generative adversarial network for holographic imaging." Optics Express 31.6 (2023): 10114-10135.



<br><br><br><br>



## Subproject 5-1: Fast Key Points Detection and Matching
This paper offers a new authentication algorithm based on image matching of nano-resolution visual identifiers with tree-shaped patterns. The algorithm includes image-to-tree conversion by greedy extraction of the fractal pattern skeleton along with a custom-built graph matching algorithm that is robust against imaging artifacts such as scaling, rotation, scratch, and illumination change. The proposed algorithm is applicable to a variety of tree-structured image matching, but our focus is on dendrites, recently-developed visual identifiers. Dendrites are entropy rich and unclonable with existing 2D and 3D printers due to their natural randomness, nano-resolution granularity, and 3D facets, making them an appropriate choice for security applications such as supply chain trace and tracking. The proposed algorithm improves upon graph matching with standard image descriptors. It also improves, which faces various problems when deploying in real-world applications. For instance, image inconsistency due to the camera sensor noise may cause unexpected feature extraction leading to inaccurate tree conversion and authentication failure. Also, previous tree extraction algorithms are prohibitively slow hindering their scalability to large systems. In this paper, we fix the current issues of and accelerate the key points extraction up to 10-times faster by implementing a new skeleton extraction method, a new key points searching algorithm, as well as an optimized key point matching algorithm. Using minimum enclosing circle and center points, make the algorithm robust to the choice of pattern shape. We show that our algorithms outperform standard key descriptors such as SIFT, FAST, and ORB in terms of accuracy (with a margin of 6% to 10%), while utilizing much fewer key points (about 20% to 80% reduction). In contrast to our algorithm handles general graphs with loop connections, therefore is applicable to a wider range of applications such as transportation map analysis, fingerprints, and retina vessel imaging. 1

To extract the information from dendritic samples, we apply a sequence of feature extraction process that using spatial filters and frequency filters to obtain low-frequency information.

<img src="../images/Nano/FKPS.png" width="80%">

Then we apply our proposed fast key points extraction algorithm to get the feature points that can represent the original graph.

<img src="../images/Nano/5.png" width="80%">

Specifically, we apply multiple sliding windows to traverse the graph and store the key points information. 

<img src="../images/Nano/keypoints.gif" width="80%">


The implementation of multiple-sliding window can greatly boost the searching efficiency.


<img src="../images/Nano/7.jpg" width="80%">


### Research Publication:
Wang, Hao, et al. "Fast key points detection and matching for tree-structured images." 2022 International Conference on Computational Science and Computational Intelligence (CSCI). IEEE, 2022.



<br><br><br><br>



## Subproject 5-2: Nano CPS pilot Platform
Today's supply chains heavily rely on cyber-physical systems such as intelligent transportation, online shopping, and E-commerce. It is advantageous to track goods in real-time by web-based registration and authentication of products after any substantial change or relocation. Despite recent advantages in technology-based tracking systems, most supply chains still rely on plainly printed tags such as barcodes and Quick Response (QR) codes for tracking purposes. Although affordable and efficient, these tags convey no security against counterfeit and cloning attacks, raising privacy concerns. It is a critical matter since a few security breaches in merchandise databases in recent years has caused crucial social and economic impacts such as identity loss, social panic, and loss of trust in the community. This paper considers an end-to-end system using dendrites as nano-resolution visual identifiers to secure supply chains. Dendrites are formed by generating fractal metallic patterns on transparent substrates through an electrochemical process, which can be used as secure identifiers due to their natural randomness, high entropy, and unclonable features. The proposed framework compromises the back-end program for identification and authentication, a web-based application for mobile devices, and a cloud database. We review architectural design, dendrite operational phases (personalization, registration, inspection), a lightweight identification method based on 2D graph-matching, and a deep 3D image authentication method based on Digital Holography (DH). A two-step search is proposed to make the system scalable by limiting the search space to samples with high similarity scores in a lower-dimensional space. We conclude by presenting our solution to make dendrites secure against adversarial attacks.

Similar to the facial recognition, each dendritic pattern have a unique ID, and different patterns tend to have different location in feature space. This non-inverse process can accelerate the searching speed, while prevent the hard-decoding from external cyber-attacks.

<img src="../images/Nano/CPS_1.png" width="80%">

To apply the implemented methods into the supply systems, we developed our cloud-based management interface, which can be accessed from multiple platforms such as mobile phone, tablet, and desktop.

<img src="../images/Nano/8_2.jpg" width="80%">

To further integrate with supplyers and vendors, we initiated massive production according to the requirements of different products and delivery purposes. 

We are also working on the security improvement using adversarial learning methods to reduce the risks of cyber-attack from different dimensions. 

For the demonstration of this project, please see <a href="">this link</a>


### Research Publication:
H. Wang, X. Chen, A. Razi, M. Kozicki, R. Amin and M. Manfredo, "Nano-Resolution Visual Identifiers Enable Secure Monitoring in Next-Generation Cyber-Physical Systems," 2022 International Conference on Computational Science and Computational Intelligence (CSCI), Las Vegas, NV, USA, 2022, pp. 856-861, doi: 10.1109/CSCI58124.2022.00155.

<br><br><br><br>


## Subproject #6: Diffusion-based Dendrite Generator [In progress work]





<br><br><br><br>







# Research Products

Valehi, Ali, et al. "A graph matching algorithm for user authentication in data networks using image-based physical unclonable functions." 2017 Computing Conference. IEEE, 2017.

<br>

Chi, Zaoyi, et al. "Consistency penalized graph matching for image-based identification of dendritic patterns." IEEE Access 8 (2020): 118623-118637.

<br>

Li, Huayu, et al. "Deep DIH: Statistically inferred reconstruction of digital in-line holography by deep learning." arXiv preprint arXiv:2004.12231 (2020).

<br>

Chen, Xiwen, et al. "DH-GAN: a physics-driven untrained generative adversarial network for holographic imaging." Optics Express 31.6 (2023): 10114-10135.

<br>

Wang, Hao, et al. "Fast key points detection and matching for tree-structured images." 2022 International Conference on Computational Science and Computational Intelligence (CSCI). IEEE, 2022.

<br>

H. Wang, X. Chen, A. Razi, M. Kozicki, R. Amin and M. Manfredo, "Nano-Resolution Visual Identifiers Enable Secure Monitoring in Next-Generation Cyber-Physical Systems," 2022 International Conference on Computational Science and Computational Intelligence (CSCI), Las Vegas, NV, USA, 2022, pp. 856-861, doi: 10.1109/CSCI58124.2022.00155.



<br><br><br><br>