---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi welcome to my homepage! I am a second year CS PhD student at The University of Texas, Austin. I work with Prof. [Qiang Liu](https://www.cs.utexas.edu/~lqiang/index.html). I got my bachelor's degree in Mathematics at Zhejiang University in 2017 and I got my master's degree in Statistics at Purdue University in 2019. During the summer of 2020, I was a Machine Learning research intern at Facebook.

Selected Research Projects
======

I have board research interests including efficient deep learning model, certified adversarial robustness, feature selection and Monte Carlo method.
    
Learning Efficient Neural Network
------

Network pruning is a successful technique to learn a compact network model. I work on strong theory-oriented pruning algorithm based on greedy optimization. We are able to show that
* Small network learned by our algorithm is guaranteed to be better than small network learned by direct training.
* Theoretically, it is importance to fine-tune the pruned network instead of retrain it.

**Mao Ye**<sup> * </sup>, Lemeng Wu<sup> * </sup> and Qiang Liu. [Greedy Optimization Provably Wins the Lottery:
Logarithmic Number of Winning Tickets is Enough](https://arxiv.org/pdf/2010.15969.pdf) *NeurIPS 2020*

**Mao Ye**, Chengyue Gong<sup> * </sup>, Lizhen Nie<sup> * </sup>, Denny Zhou, Adam Klivans and Qiang Liu. [Good Subnetworks Provably Exists: Pruning via Greedy Forward Selection.](https://proceedings.icml.cc/static/paper_files/icml/2020/1781-Paper.pdf). *ICML 2020*


Certified Robustness
-----
We propose a functional constraint optimization framework for cerfified adversarial defense using random smoothing. A general class of smoothing distribution is proposed for image classification task. And a special discrete smoothing distribution is proposed for text classification.

Dinghuai Zhang<sup> * </sup>, **Mao Ye**<sup> * </sup>, Chengyue Gong<sup> * </sup> and Qiang Liu. [Black-Box Certification with Randomized Smoothing: A Functional Optimization Based Framework.](https://arxiv.org/pdf/2002.09169.pdf) *Neurips 2020*

**Mao Ye**<sup> * </sup>, Chengyue Gong<sup> * </sup> and Qiang Liu. [SAFER: A Structure-free Approach for Certified Robustness to Adversarial Word Substitutions.](https://www.aclweb.org/anthology/2020.acl-main.317.pdf) *ACL 2020*

Feature Selection
-----
Selecting useful feature is important for ML system. We develop a new drop-out-one loss that accurately detects useful features for difficult task with highly correlated features. Our approach is very easy to implement and is guaranteed to select all useful features and discard all useless features when there is enough data.

**Mao Ye**<sup> * </sup> and Yan Sun<sup> * </sup>. [Variable Selection via Penalized Neural Network: a Drop-Out-One Loss Approac.](http://proceedings.mlr.press/v80/ye18b/ye18b.pdf) *ICML 2018*

Sampling Method
------
Sampling method is important for Bayesian inference and RL. We develop a special samping dynamics that utilizes the collected samples to guide the sampler to explore the unexplored region and thus improve the sampling quality.

**Mao Ye**<sup> * </sup>, Tongzheng Ren<sup> * </sup> and Qiang Liu. [Stein Self-Repulsive Dynamics: Benefits from Past Samples.](https://arxiv.org/pdf/2002.09070.pdf) *Neurips 2020*

Services
======
Conference reviewer: ICML, NeurIPS, ICLR

Journal reviewer: JMLR, Canadian journal of statistics


