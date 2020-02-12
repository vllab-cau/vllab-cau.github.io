---
title: ## "Deep Elastic Networks with Model Selection for Multi-Task Learning"
collection: publications
permalink: /publication/ICCV19_DEN
excerpt: 'Authors: Chanho Ahn\*, **Eunwoo Kim**\*, and Songhwai Oh (\* indicates equal contribution.)'
date: 2019-10-01
font_size: 10pt
venue: IEEE International Conference on Computer Vision (ICCV)

---
<img src='/images/DEN.png' width="500">

Chanho Ahn\*, **Eunwoo Kim**\*, and Songhwai Oh, “Deep Elastic Networks with Model Selection for Multi-Task Learning”, *in Proc. of the IEEE International Conference on Computer Vision (ICCV)*, Oct. 2019. (\* indicates  equal contribution, 25.0% Acceptance Rate)

Abstract: In this work, we consider the problem of instance-wise dynamic network model selection for multi-task learning. To this end, we propose an efficient approach to exploit a compact but accurate model in a backbone architecture for each instance of all tasks. The proposed method consists of an estimator and a selector. The estimator is based on a backbone architecture and structured hierarchically. It can produce multiple different network models of different configurations in a hierarchical structure. The selector chooses a model dynamically from a pool of candidate models given an input instance. The selector is a relatively small-size network consisting of a few layers, which estimates a probability distribution over the candidate models when an input instance of a task is given. Both estimator and selector are jointly trained in a unified learning framework in conjunction with a sampling-based learning strategy, without additional computation steps. We demonstrate the proposed approach for several image classification tasks compared to existing approaches performing model selection or learning multiple tasks. Experimental results show that our approach gives not only outstanding performance compared to other competitors but also the versatility to perform instance-wise model selection for multiple tasks.

[[Paper](https://arxiv.org/abs/1909.04860)] [[Code](https://github.com/rllab-snu/Deep-Elastic-Network)]
