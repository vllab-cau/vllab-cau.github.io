---
title: "Deep Virtual Networks for Memory Efficient Inference of Multiple Tasks"
collection: publications
permalink: /publication/CVPR19_DVN
excerpt: 'Authors: **Eunwoo Kim**, Chanho Ahn, Philip H.S. Torr, Songhwai Oh'
date: 2019-06-01
venue: 'IEEE Conference on Computer Vision and Pattern Recognition (CVPR)'
---
<img src='/images/cvpr19_deep_virtualnet.png'>

**Eunwoo Kim**, Chanho Ahn, Philip H.S. Torr, and Songhwai Oh, “Deep Virtual Networks for Memory Efficient Inference of Multiple Tasks”, *in Proc. of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, Jun.  2019.  (25.2% Acceptance Rate)

Abstract: Deep networks consume a large amount of memory by their nature. A natural question arises can we reduce that memory requirement whilst maintaining performance. In particular, in this work we address the problem of memory efficient learning for multiple tasks. To this end, we propose a novel network architecture producing multiple networks of different configurations, termed deep virtual networks (DVNs), for different tasks. Each DVN is specialized for a single task and structured hierarchically. The hierarchical structure, which contains multiple levels of hierarchy corresponding to different numbers of parameters, enables multiple inference for different memory budgets. The building block of a deep virtual network is based on a disjoint collection of parameters of a network, which we call a unit. The lowest level of hierarchy in a deep virtual network is a unit, and higher levels of hierarchy contain lower levels' units and other additional units. Given a budget on the number of parameters, a different level of a deep virtual network can be chosen to perform the task. A unit can be shared by different DVNs, allowing multiple DVNs in a single network. In addition, shared units provide assistance to the target task with additional knowledge learned from another tasks. This cooperative configuration of DVNs makes it possible to handle different tasks in a memory-aware manner. Our experiments show that the proposed method outperforms existing approaches for multiple tasks. Notably, ours is more efficient than others as it allows memory-aware inference for all tasks.

[[Paper](https://arxiv.org/abs/1904.04562)] [[Code](https://github.com/niceday15/deep-virtual-network-cifar)]
