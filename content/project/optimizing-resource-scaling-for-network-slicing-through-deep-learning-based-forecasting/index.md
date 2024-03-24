---
title: Dynamic Network Slice Scaling Assisted by Attention-Based Prediction in 5G Core Network
date: 2022-06-15T10:07:43.874Z
summary: Network slicing is a key technology in 5G and beyond networks to meet
  the diverse requirements of various applications. The resource usage
  forecasting in network slicing plays an important role in helping network
  operators scale network slices up and down accurately and timely to avoid
  Service Level Agreement (SLA) violations signed with network tenants.
draft: false
featured: false
authors:
  - Chien-Nguyen
url_slides: https://docs.google.com/presentation/d/17_NSrkEV_906OlD0cKVPDi2CAdifElnOV1yqNHtBiQY/edit?usp=sharing
tags:
  - Deep Learning
categories:
  - Deep Learning
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
1. Summary of the project: Network slicing is a key technology in 5G and beyond networks to meet the diverse requirements of various applications. The resource usage forecasting in network slicing plays an important role in helping network operators scale network slices up and down accurately and timely to avoid Service Level Agreement (SLA) violations signed with network tenants. 

Therefore, we propose some modern forecasting algorithms utilizing multivariate time series data to predict the future resource usage of virtual machines (VMs) in network slices. 

We also designed an automated resource configuration system whose main core is the proposed forecasting algorithms. The proposed automated resource configuration system will monitor the resources of VNF instances in the slices, predict the future resource usage and automatically scale in or out the number of VNF instances. The system is deployed on top of the ETSI NFV architecture

Through comprehensive experiments, our proposed algorithm outperforms other state-of-the-arts forecasting algorithms only processing univariate time series data in both short-term prediction and long-term prediction to help network operator reduce the costs of SLA violation and resource overprovisioning.

2. Solution: Please read the link of PPT file to read the detail of the solution

3. My position: Researcher

4. My main responsibilies:
      - Exploratory data analyzing by using Pandas and Matplotlib libraries
      - Researching to design the time series forecasting algorithm
      - Implementing the algorithm and the inference pipeline by using scikit-learnand pytorch
      - Writing the paper to publish the research results


5. Technologies and Tools used:  Python, Pytorch, Pandas, Scikit-learn, Scipy
