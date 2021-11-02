---
title: Fault injection on Deep learning models
date: 2021-11-02T19:23:15.713Z
summary: >-
  I studied the robustness of multiple DNN architectures, and designed a new\

  activation function to increase the robustness and reliability of DNNs. I used\

  Python/PyTorch in this project.
draft: false
featured: false
tags:
  - Python
  - Pytorch
  - Deep Learning
image:
  filename: ""
  focal_point: Smart
  preview_only: false
---
With the rise of Deep Neural Networks (DNNs), many safety-critical applications,\
such as self-driving cars and healthcare devices, are using them to improve their\
performance. In these systems, error resilience is a top priority since faults in DNN\
inference could lead to mispredictions and safety hazards. In this work, I developed a\
new method to improve the error resiliency of DNNs called FitAct. The idea is to\
bound the activation function with a post-trained, neuron-wise activation function. I\
tested this method on several DNN architectures and datasets. For this project, I\
used PyTorch, a deep learning framework based on Python, to implement and test\
FitAct.