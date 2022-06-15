---
url_pdf: ""
summary: ""
authors:
  - Chien
url_video: ""
date: 2022-06-09T00:00:00.000Z
external_link: ""
url_slides: https://docs.google.com/presentation/d/11etSR-CS0qpMqELd50tTFbj7WJ_iT3BNNl2-WbTfif0/edit?usp=sharing
title: Two-phase Deep Learning-based EDOS Attack Detection System
tags:
  - Deep Learning
links:
  - icon: doi
    icon_pack: ai
    name: DOI
    url: https://www.mdpi.com/2076-3417/11/21/10249
image:
  caption: The conceptual architecture of the two-phase deep leanring-based EDoS
    detection
  focal_point: Smart
  filename: featured.png
url_code: ""
---
Cloud computing is currently considered the most cost-effective platform for offering business and consumer IT services over the Internet. However, it is prone to new vulnerabilities. A new type of attack called an economic denial of sustainability (EDoS) attack exploits the pay-per-use model to scale up the resource usage over time to the extent that the cloud user has to pay for the unexpected usage charge. To prevent EDoS attacks, a few solutions have been proposed, including hard-threshold and machine learning-based solutions. Among them, long short-term memory (LSTM)-based solutions achieve much higher accuracy and false-alarm rates than hard-threshold and other machine learning-based solutions. However, LSTM requires a long sequence length of the input data, leading to a degraded performance owing to increases in the calculations, the detection time, and consuming a large number of computing resources of the defense system. 

We, therefore, propose a two-phase deep learning-based EDoS detection scheme that uses an LSTM model to detect each abnormal flow in network traffic; however, the LSTM model requires only a short sequence length of five of the input data. Thus, the proposed scheme can take advantage of the efficiency of the LSTM algorithm in detecting each abnormal flow in network traffic, while reducing the required sequence length of the input data. A comprehensive performance evaluation shows that our proposed scheme outperforms the existing solutions in terms of accuracy and resource consumption.

Technologies or Tools used: Keras, Apache Spark, Wireshark, Ansible, SplitCap
Programming Languages: Python, shell

My main responsibilies: Idea proposing, data analysis and coding 


The github link of the project: https://github.com/harrychien1311/Two-phase-Deep-learning-based-EDoS-Detection-System
