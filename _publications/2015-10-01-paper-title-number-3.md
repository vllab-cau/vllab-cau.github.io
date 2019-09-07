---
title: "NestedNet: Learning Nested Sparse Structures in Deep Neural Networks"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'Authors: **Eunwoo Kim**, Chanho Ahn, and Songhwai Oh'
date: 2018-06-01
venue: 'IEEE Conference on Computer Vision and Patter Recognition (CVPR)'
---
Abstract: Recently, there have been increasing demands to construct compact deep architectures to remove unnecessary redundancy and to improve the inference speed. While many recent works focus on reducing the redundancy by eliminating unneeded weight parameters, it is not possible to apply a single deep architecture for multiple devices with different resources. When a new device or circumstantial condition requires a new deep architecture, it is necessary to construct and train a new network from scratch. In this work, we propose a novel deep learning framework, called a nested sparse network, which exploits an n-in-1-type nested structure in a neural network. A nested sparse network consists of multiple levels of networks with a different sparsity ratio associated with each level, and higher level networks share parameters with lower level networks to enable stable nested learning. The proposed framework realizes a resource-aware versatile architecture as the same network can meet diverse resource requirements. Moreover, the proposed nested network can learn different forms of knowledge in its internal networks at different levels, enabling multiple tasks using a single network, such as coarse-to-fine hierarchical classification. In order to train the proposed nested sparse network, we propose efficient weight connection learning and channel and layer scheduling strategies. We evaluate our network in multiple tasks, including adaptive deep compression, knowledge distillation, and learning class hierarchy, and demonstrate that nested sparse networks perform competitively, but more efficiently, compared to existing methods.

Authors: **Eunwoo Kim**, Chanho Ahn, and Songhwai Oh (Spotlight Presentation, 8.7% Acceptance Rate)

[Paper] [Code]
