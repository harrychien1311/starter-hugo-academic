---
title: "AI-based Cyberthreat Detection System for the Republic of Korea Army"
date: 2022-08-01T10:20:13.294Z
summary: Desgin and develop  an AI-based system to detect network attacks in the intranet of the Republic of Korea Army.
draft: false
featured: false
authors: 
  - Chien-Nguyen
tags:
  - Deep learning
categories:
  - Deep learning
image:
  filename: rok.jpg
  focal_point: Smart
  preview_only: false
---
1. Summarize of the project: The intranet of Republic of Korea's Army suffers millions of sessions per day. This could lead to the hight potential of cyber attacks eventhough there is no outside traffics in this intranet. However, just a spam email or unintentionally plugig an external device such as USB could bring a malware to a signle computer in the intranet and then it could become a bot in a botnet attack or DDoS attack,... attack the entire network. With high volume of traffics in the intranet, there is a need for an AI-based cyberattack detections to automatically detect network attacks and support network operators in network analysis.
2. Solutions: We developed a system utilizing 3 AI algorithms to detect multiple types of attacks including XGBoostClassifier, Tabformer-a variant of tranformer based architecture that uitlize narutal language processing technique to process tabbular data. Especially we converted network session data to hiveplot images for visualization and then used a CNN model to classified attacks


3. My position: Team leader

4. Main responsibilities:
    - Conducted big data analysis using Pyspark and built automated pipelines to process data with the Prefect framework.
    - Conducted hypothesis testing to find the feature importance among variables
    - Developed  the Tabformer architecture in Pytorch.
    - Implemented the inference pipeline
    - Designed CI/CD pipeline to boost the productivity when deploying the inference pipeline with different models
    - Conducted coding review

5.  Technologies and Tools used: Python, Pytorch, Apache Spark, Pandas, Scikit-learn, Docker
6. *Note: This is a goverment project. Thus we cannot share the actual architecture image and the source code*

![Overview architecture](overview_architecture.png)

*Note: This overview architecture is not the actual implemented architecture*

![Feature Importance](feature_importance.png)
*Feature importance analyzing using SHAP*