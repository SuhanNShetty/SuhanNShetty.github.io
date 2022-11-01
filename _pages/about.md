---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Ph.D. student at the École polytechnique fédérale de Lausanne ([EPFL](https://www.epfl.ch/en/)) and a research assistant at the [Idiap Research Institute](https://www.idiap.ch/en). I am doing my research at Robot Learning and Interaction group (RLI) under the supervision of [Dr.Sylvain Calinon](https://calinon.ch/).  My research lies at the intersection of data-efficient machine learning, control engineering, and robotics. In particular, I am exploring the usage of **low-rank tensor approximation techniques** to develop algorithms for Robot Control, Reinforcement Learning, and Motion Planning that were previously considered to be intractable.

In the Robot Learning and Interaction group, I am developing algorithms for robotic exploration as used in the project CoLLaboratE for industrial assembly tasks, reinforcement learning, and fast optimization algorithms as used in projects Learn-Real and MEMMO for robot control and motion planning. For example, I have developed fast algorithms to find the Fourier series coefficients for higher dimensional functions which lead to a scalable ergodic exploration algorithm ([paper](https://sites.google.com/view/ergodic-exploration/)). In another recent work, I have come up with a new methodology for global optimization of non-convex functions which were applied to inverse kinematics and motion planning of manipulators [(paper)]((https://sites.google.com/view/ttgo/home)). Currently, I am trying to scale up well-known reinforcement learning algorithms that were previously considered to suffer from the curse of dimensionality. 

## What is low-rank tensor approximation?

Low-rank tensor appoximation techniques (aka Tensor factorization techniques or Tensor Networks in applied physics) are extensions of matrix factorization techniques into multidimensional arrays
(i.e., tensors). These techniques approximate a given tensor compactly using a set of lower-dimensional arrays (called factors). In addition to the compact representation and existence of powerful algorithms to find such representation, they allow efficient algebraic operations to be performed on them. Popular tensor factorization techniques include CP/PARAFAC
decomposition, Tucker decomposition, Hierarchical Tucker decomposition, and Tensor Train (TT).

In essence, they allow us to represent multi-dimensional functions (or arrays) in a variable separation form (i.e., sum of product of univariate functions). Such representations yield fast approaches to perform algebraic operations like additions, multiplication, hadamard product and many more in an efficient manner. Many challenges such as multi-variate integration and probailistic analysis can be performed elegantly if we assume such representation. This leads to solving many problems in robotics which were previously considered to be intractable. See my publication list to see some examples of solved problems (and many more to come!).  
 
## Latest News

### 2022
- Our paper "Tensor Train for Global Optimization Problems in Robotics" is out on arXiv 
  - [Website](https://sites.google.com/view/ttgo/home)

### 2021
- Our paper "Ergodic Exploration using Tensor Train: Applications in Insertion task" won the **best paper award** of the year (2021) from the institute Idiap Research Institute, Martigny

- Our paper "Trajectory Prediction with Compressed 3D Environment Representation using Tensor Train Decomposition" is accepted at ICAR  

- Our paper "Ergodic Exploration using Tensor Train: Applications in Insertion task" is accepted for publication at **IEEE Transactions on Robotics**
  - [Website](https://sites.google.com/view/ergodic-exploration/)

### 2019
- (June) Started my **PhD at EPFL** and as a Research Assistent at **Idiap Research Institute, Martigny** 

- (Feb) Joined Robert Bosch Center for Cyber-Physical systems as a Research Associate
  - I will be applying **Reinforcement Learning** to generate walking gaits for a quadruped called Stoc which is developed in-house

### 2016
- Started working at **The MathWorks Inc, India** in the Engineering Development Group
  - I will be working with MATLAB, Simulink, Robotics System Toolbox, Automated Driving System Toolbox 

### 2014
- Started a master's degree in Mechanical Engineering at the **Indian Institute of Science, Bangalore**
  - I will be focusing on **Dynamic Systems and Control**
