---
layout: post
title: Brief Paper Review - ImageNet Classification with Deep Convolutional Neural Networks
excerpt: "2012 NIPS Spotlight, Classification"
categories: [2012 NIPS, Spotlight, Classification, Paper Review, Brief Paper Review]
comments: true
---


# 1. Intro

This paper review is brief review of the paper, so it does not contain all the contents of the paper.

Check-out more details and contents from original paper or [`github`](https://github.com/Jasonlee1995/AI_Papers/issues/1).

Comments are welcomed for typos, suggestions and other inquiries on [`github`](https://github.com/Jasonlee1995/AI_Papers/issues/1).


# 2. About Paper

AlexNet was able to be created cause of large dataset like ImageNet and evolution of GPUs.

Combinations of conv, pool, and fc layer produce the best performance at that time, and check AlexNet architecture below.

![AlexNet Architecture](../../../../img/210310_AlexNet/Figure_01.png)

The following 3 contents were conceptually difficult while reading the paper.

1. LRN
2. Data augmentation using PCA
3. Upper-bound of CNN and fully-connected network

I understood this 3 contents as follow.

1. LRN == brightness normalization
2. PCA data augmentation == statistic-based RGB intensity augmentation, not heuristic
3. Upper-bound of CNN and full-connected network: I googled a lot, but can't find the exact matches. VC-dimension may be the rough upper bound measurement.


# 3. Reference
- [ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
