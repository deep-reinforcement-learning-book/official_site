---
layout: default
title: Chap 12. Parallel Computing
nav_order: 12
---

## Authors

- Huaqing Zhang* - Google (markasjunior[at]gmail.com)
- Tianyang Yu - Nanchang University

## Abstract

Due to the low sample efficiency of reinforcement learning, parallel computing is an efficient solution to speed up the training process and improve the performance. In this chapter, we introduce the framework applying parallel computation in reinforcement learning. Based on different scenarios, we firstly analyze the synchronous and asynchronous communication and elaborate parallel communication in different network typologies. Taking the advantage of parallel computing, classic distributed reinforcement learning algorithms are depicted and compared, followed by summaries of fundamental components in the distributed computing architecture.

**Keywords**: distributed computing, Asynchronous Advantage Actor-Critic, Hybrid GPU/CPU A3C, Importance Weighted Actor-Learner Architecture (IMPALA), Scalable Efficient Deep-RL (SEED), Distributed Proximal Policy Optimization (DPPO), Ape-X, Retrace-Actor (Reactor), Recurrent Replay Distributed DQN (R2D2)

## Content
[中文版PDF](/assets/pdfs/ch12.pdf){: .btn .btn-purple  .fs-3 .mb-4 .mb-md-0 .mr-2 }

## Citation

To cite this book, please use this bibtex entry:

```
@incollection{deepRL-chapter12-2020,
 title={Parallel Computing},
 chapter={12},
 author={Huaqing Zhang, Tianyang Yu},
 editor={Hao Dong, Zihan Ding, Shanghang Zhang},
 booktitle={Deep Reinforcement Learning: Fundamentals, Research, and Applications},
 publisher={Springer Nature},
 pages={347-366},
 note={\url{http://www.deepreinforcementlearningbook.org}},
 year={2020}
}
```



If you find any typos or have suggestions for improving the book, do not hesitate to contact with the corresponding author (name with *).