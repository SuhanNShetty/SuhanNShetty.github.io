---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a Ph.D. student at the École polytechnique fédérale de Lausanne ([EPFL](https://www.epfl.ch/en/)) and a research assistant at the [Idiap Research Institute](https://www.idiap.ch/en). I am doing my research at Robot Learning and Interaction group (RLI) under the supervision of [Dr.Sylvain Calinon](https://calinon.ch/).  My research lies at the intersection of data-efficient machine learning, control engineering, and robotics. In particular, I am exploring the usage of **low-rank tensor approximation techniques** (aka tensor methods) to develop algorithms for Robot Control, Reinforcement Learning, and Motion Planning that were previously considered to be intractable. 

## What is low-rank tensor approximation?

Low-rank tensor appoximation techniques (aka Tensor factorization techniques or Tensor Networks in applied physics) are extensions of matrix factorization techniques into multidimensional arrays
(i.e., tensors). These techniques approximate a given tensor compactly using a set of lower-dimensional arrays (called factors). In addition to the compact representation, they allow efficient algebraic operations to be performed on them. Popular tensor factorization techniques include CP/PARAFAC
decomposition, Tucker decomposition, Hierarchical Tucker decomposition, and Tensor Train (TT)for applications in machine learning.

In essence, they allow us to represent multi-dimensional functions (or an array) in variable separation form (i.e., sum of product of univariate functions). Such representations yield fast approaches to perform algebraic operations like additions, multiplication, hadamard product and many more in an efficient manner. Many challenges such as multi-variate integration and probailistic analysis can be performed elegantly if we assume such representation. This leads to solving many problems in robotics which were previously considered to be intractable. See my publication list to see some examples of solved problems (and many more to come!).  
 
## Latest News

### 2022
- Our paper "Tensor Train for Global Optimization Problems in Robotics" is out on arXiv 
  - Website: https://sites.google.com/view/ttgo/home

### 2021
- Our paper "Ergodic Exploration using Tensor Train: Applications in Insertion task" won the best paper award of the year (2021) from the institute Idiap Research Institute, Martigny

- Our paper "Trajectory Prediction with Compressed 3D Environment Representation using Tensor Train Decomposition" is accepted at ICAR  

- Our paper "Ergodic Exploration using Tensor Train: Applications in Insertion task" is accepted for publication at IEEE T-RO
  - Website: https://sites.google.com/view/ergodic-exploration/

### 2019
- (June) Started my PhD at EPFL and as a Research Assistent at Idiap Research Institute, Martigny 

- (Feb) Joined Robert Bosch Center for Cyber-Physical systems as a Research Associate
  - I will be applying Reinforcement Learning to generate walking gaits for a quadruped called Stoc which is developed in-house

### 2016
- Started working at The MathWorks Inc, India in the Engineerinf Development Group
  - I will be working with MATLAB, Simulink, Robotics System Toolbox, Automated Driving System Toolbox 

### 2014
- Started a master's degree in Mechanical Engineering at the Indian Institute of Science, Bangalore
  - I will be focusing on Dynamic Systems and Control 
<!-- 

Some useful links
======

My latest research: [`click here`](/publications/)

Resume / CV: [`click here`](/files/cv/cv.pdf)
 -->


<!-- 
## Latest news

### 2022

- The first two papers submitted to [INTERSPEECH 2022](https://interspeech2022.org/) are up in ArXiV! Check them out! 
  - BERTraffic: BERT-based Joint Speaker Role and Speaker Change Detection for Air Traffic Control Communications
  [abstract](https://arxiv.org/abs/2110.05781), [PDF](https://arxiv.org/pdf/2110.05781.pdf){: .notice}
  - How Does Pre-trained Wav2Vec2.0 Perform on Domain-Shifted ASR? An Extensive Benchmark on Air Traffic Control Communications
  [abstract](https://arxiv.org/abs/2203.16822), [PDF](https://arxiv.org/pdf/2203.16822.pdf){: .notice}

- We submitted 5 papers to [INTERSPEECH 2022](https://interspeech2022.org/) with Yulia, Amrutha, Saeed and Petr M., from our lab ([Idiap](https://www.idiap.ch/en)) and some other nice co-authors from DLR (Germany), Brno University of Technology and Uniphore!
  - Two submissions are improved versions of the two rejected papers at ICASSP 2022. We are putting a lot of effort into improving the quality of these two.
  - The third paper is about How pre-trained Wav2Vec2.0 performs on domain-shifted ASR? This is basically an extensive benchmark on air traffic control communications.
  - A new paper is about School of Information and Electronics, Beijing Institute of Technology submission to the [Oriental Language Recognition (OLR) 2021 Challenge](http://cslt.riit.tsinghua.edu.cn/mediawiki/index.php/OLR_Challenge_2021). The team obtained 2nd and 3rd place in task3 and task4 (constrained and unconstrained ASR for 13 oriental languages). 
  - The last paper is about a Kaldi implementation of contextual biasing in GPU decoder for online ASR. Basically, adding some target n-grams after/during ASR decoding.  

- Exciting news! One out of three papers submitted to [**ICASSP 2022**](https://2022.ieeeicassp.org/) were accepted for on-site presentation!
  - Accepted paper: A two-step approach to leverage contextual data: speech recognition in air-traffic communications. 
  [abstract](https://arxiv.org/abs/2202.03725), [PDF](https://arxiv.org/pdf/2202.03725.pdf){: .notice}

- Rebuttal period for our 3 submissions to ICASSP 2022... Loading... Loading. 

### 2021

- More news before the Holiday season - end of 2021! Our paper about cross-lingual speech recognition was accepted for publication in [**Electronics**](https://www.mdpi.com/journal/electronics) (Journal) (December, 10(24))!
  - Domain-Adversarial Based Model with Phonological Knowledge for Cross-Lingual Speech Recognition.
  [abstract](https://www.mdpi.com/2079-9292/10/24/3172), [PDF](https://www.mdpi.com/2079-9292/10/24/3172/htm){: .notice}

- Our paper submitted to [**The 9th OpenSky Symposium**](https://symposium.opensky-network.org/) has been published in MDPI engineering proceedings!
  - Automatic Processing Pipeline for Collecting and Annotating Air-Traffic Voice Communication Data.
  [abstract](https://www.mdpi.com/2673-4591/13/1/8), [PDF](https://www.mdpi.com/2673-4591/13/1/8/htm){: .notice}

- Our team from [Idiap](https://www.idiap.ch/en) and [BUT](https://www.vut.cz/EN/) is traveling to Brussels, Belgium to present our paper at [**The 9th OpenSky Symposium**](https://symposium.opensky-network.org/)

- Out first paper submitted to [ICASSP 2022](https://2022.ieeeicassp.org/) was just released in ArXiV:
  - BERTraffic: A Robust BERT-Based Approach for Speaker Change Detection and Role Identification of Air-Traffic Communications. 
  [abstract](https://arxiv.org/abs/2110.05781), [PDF](https://arxiv.org/pdf/2110.05781.pdf){: .notice}


- We submitted 3 papers to [ICASSP 2022](https://2022.ieeeicassp.org/) with Yulia, Amrutha, Saeed and Petr M., from our lab ([Idiap](https://www.idiap.ch/en)). 

- Exciting news! Our paper submitted to [**The 9th OpenSky Symposium**](https://symposium.opensky-network.org/) was accepted for on-site presentation! (Automatic processing pipeline for collecting and annotating air-traffic voice communication data)

- The two papers presented at [Interspeech 2021](https://www.interspeech2021.org/) are:
  - Contextual Semi-Supervised Learning: An Approach to Leverage Air-Surveillance and Untranscribed ATC Data in ASR Systems.
  [abstract](https://isca-speech.org/archive/interspeech_2021/zuluagagomez21_interspeech.html), [PDF](https://isca-speech.org/archive/pdfs/interspeech_2021/zuluagagomez21_interspeech.pdf){: .notice}
  - Boosting of Contextual Information in ASR for Air-Traffic Call-Sign Recognition. [abstract](https://isca-speech.org/archive/interspeech_2021/kocour21_interspeech.html), [PDF](https://isca-speech.org/archive/pdfs/interspeech_2021/kocour21_interspeech.pdf){: .notice}

- We are releasing in ArXiv the two papers that were rejected:
  - Improving callsign recognition with air-surveillance data in air-traffic communication. [abstract](https://arxiv.org/abs/2108.12156), [PDF](https://arxiv.org/pdf/2108.12156.pdf){: .notice}
  - Grammar Based Identification Of Speaker Role For Improving ATCO And Pilot ASR. [abstract](https://arxiv.org/abs/2108.12175), [PDF](https://arxiv.org/pdf/2108.12175.pdf){: .notice}


- Exciting news! two of the four papers submitted to [Interspeech 2021](https://www.interspeech2021.org/) were accepted. 

- We submitted 4 papers to [Interspeech 2021](https://www.interspeech2021.org/) with Yulia and Amrutha from our lab ([Idiap](https://www.idiap.ch/en)) and [Brno University of Technology](https://www.vut.cz/EN/).


### 2020

- Exciting news! our paper submitted to [**The 8th OpenSky Symposium**](https://symposium.opensky-network.org/) was accepted for virtual presentation! (Automatic Call Sign Detection: Matching Air Surveillance Data with Air Traffic Spoken Communications)

- The full paper presented at [Interspeech 2020](https://www.interspeech2020.org/):
  - Automatic speech recognition benchmark for air-traffic communications.
  [abstract](https://isca-speech.org/archive/interspeech_2020/zuluagagomez20_interspeech.html)[PDF](https://isca-speech.org/archive/pdfs/interspeech_2020/zuluagagomez20_interspeech.pdf){: .notice}


- Exciting news! one paper submitted at [**Interspeech 2020**](http://www.interspeech2020.org/) was accepted for on-site presentation! (Automatic speech recognition benchmark for air-traffic communications)

- Really excited about my first paper about ASR for air traffic control communications (a low-resource task)! It was submitted at [Interspeech 2020](http://www.interspeech2020.org/). Additionally, we submitted another work with Qingran Zhan from our lab ([Idiap](https://www.idiap.ch/en)) about Articularatory features for ASR.


### 2019

- Another paper from our team (led by Jian Ma) got published in the **Vibroengineering PROCEDIA**:
  - A portable breast cancer detection system based on a smartphone with an infrared camera. [abstract](https://www.jvejournals.com/article/20978)[PDF](https://www.jvejournals.com/article/20978/pdf){: .notice}

- Time goes so fast! We just published a second Journal paper related to breast cancer diagnosis with infrared techniques and machine learning (computer vision)! The paper was accepted for publication in the **Computer Methods in Biomechanics and Biomedical Engineering: Imaging & Visualization**. 
[Journal](https://www.tandfonline.com/doi/abs/10.1080/21681163.2020.1824685) and [pre-print](https://arxiv.org/abs/1910.13757){: .notice}

- Excited about my first Journal survey paper related to breast cancer diagnosis techniques! The survey paper was published in the **Journal of Medical Engineering & Technology**. 
[Journal](https://www.tandfonline.com/doi/abs/10.1080/03091902.2019.1664672) and [pre-print](https://hal.archives-ouvertes.fr/hal-02387519/document){: .notice}

- January: Started my Master Thesis at the École nationale supérieure de mécanique et des microtechniques in Besançon, France! I will work on computer vision for breast cancer diagnosis! 

### 2017

- September: Arrived in Gijon, Spain to start a Master's degree in Mechatronics Engineering! Gijon is such a nice coastal town! 

- January: I got the exciting news that I was accepted at the [**The Joint Master Degree in Mechatronic Engineering, EU4M**](https://www.eu4m.eu/inicio). This program allows students to select from 2 to 3 (out of 5) universities where to go for studies. I will start at the University of Oviedo in Spain, then I will go to ISPU (Ivanovo, Russia) and finally to ENSMM in France!

### 2010-2015

- Started and finished a Bachelor's degree in Mechatronics Engineering! I learned tons of things about electronics, mechanical engineering, robotics, and programming languages (C, Python, and Matlab)!

 -->