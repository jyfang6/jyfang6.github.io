---
title: Gaussian Process with Graph Convolutional Kernel for Relational Learning
authors:
- Jinyuan Fang
- Shangsong Liang
- Zaiqiao Meng
- Qiang Zhang
date: '2021-08-01'
publishDate: '2023-11-11T21:38:10.927386Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery
  & Data Mining*'
doi: 10.1145/3447548.3467327
abstract: Gaussian Process (GP) offers a principled non-parametric framework for learning
  stochastic functions. The generalization capability of GPs depends heavily on the
  kernel function, which implicitly imposes the smoothness assumptions of the data.
  However, common feature-based kernel functions are inefficient to model the relational
  data, where the smoothness assumptions implied by the kernels are violated. To model
  the complex and non-differentiable functions over relational data, we propose a
  novel Graph Convolutional Kernel, which enables to incorporate relational structures
  to feature-based kernels to capture the statistical structure of data. To validate
  the effectiveness of proposed kernel function in modeling relational data, we introduce
  GP models with Graph Convolutional Kernel in two relational learning settings, i.e.,
  unsupervised settings of link prediction and semi-supervised settings of object
  classification. The parameters of our GP models are optimized through the scalable
  variational inducing point method. However, the highly structured likelihood objective
  requires densely sampling from variational distributions, which is costly and makes
  its optimization challenging in the unsupervised settings. To tackle this challenge,
  we propose a Local Neighbor Sampling technique with a provable more efficient computational
  complexity. Experimental results on real-world datasets demonstrate that our model
  achieves state-of-the-art performance in two relational learning tasks.
tags:
- gaussian process
- graph convolutional kernel
- relational learning
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3447548.3467327
---
