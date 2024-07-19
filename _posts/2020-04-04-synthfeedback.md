---
title: "New paper: Towards biologically plausible deep learning: learning to solve the credit assigment problem"
categories:
  - deep-learning
tags:
  - "biologically plausible deep learning"
  - "reinforcement learning"
use_math: true
published: true
---

Excited to present this paper in collaboration with Prashanth Prakash and Konrad Kording at ICLR 2020 main meeting:

Backpropagation is driving today's artificial neural networks (ANNs). However, despite extensive research, it remains unclear if the brain implements this algorithm. Among neuroscientists, reinforcement learning (RL) algorithms are often seen as a realistic alternative: neurons can randomly introduce change, and use unspecific feedback signals to observe their effect on the cost and thus approximate their gradient. However, the convergence rate of such learning scales poorly with the number of involved neurons. Here we propose a hybrid learning approach. Each neuron uses an RL-type strategy to learn how to approximate the gradients that backpropagation would provide. We provide proof that our approach converges to the true gradient for certain classes of networks. In both feedforward and convolutional networks, we empirically show that our approach learns to approximate the gradient, and can match the performance of gradient-based learning. Learning feedback weights provides a biologically plausible mechanism of achieving good performance, without the need for precise, pre-specified learning rules. 

<p style="text-align: center"><img src="../../images/fig1_schematic.png" width="35%" align="middle"></p>

**Lansdell B**, Prakash P, Kording K, [arXiv](https://arxiv.org/abs/1906.00889) *ICLR 2020 main meeting*