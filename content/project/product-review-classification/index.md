---
title: Product review classification
date: 2022-06-25T11:36:31.681Z
summary: ""
draft: false
featured: false
links:
  - url: https://github.com/harrychien1311/Product-review-classification
    name: github
    icon_pack: fab
    icon: github
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: The process scheme of product review classification
---


1. Summary of the project:

   In this project, I build a LSTM-based sentiment classification model to classify custormer's behaviour buying clothes and jewerly in the Amazon website based on their reviews of ordered products leaving on the website. The model's output is a 3-class output which are postivie, negative and neutral. This project uses a pretrained word2vec model which is Google Word2Vec model to embed sentences into word embedding vectors. Then the LSTM model will use these embedding vectors to train the model.
2. The goal of the project:This project will help the producers can control and understand their custormer behavior to improve their products.
3. Desired outputs:

   The customer's behavior: Positive: Really like the product Negative: Really hate the product Neutral: Feel the product not too good but not bad
4. Frameworks used: Keras, NLTK (Natual language processing toolkit )