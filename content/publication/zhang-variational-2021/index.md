---
title: Variational Continual Bayesian Meta-Learning
authors:
- Qiang Zhang
- Jinyuan Fang
- Zaiqiao Meng
- Shangsong Liang
- Emine Yilmaz
date: '2021-01-01'
publishDate: '2023-11-11T21:38:10.908931Z'
publication_types:
- paper-conference
publication: '*Advances in Neural Information Processing Systems*'
abstract: Conventional meta-learning considers a set of tasks from a stationary distribution.
  In contrast, this paper focuses on a more complex online setting, where tasks arrive
  sequentially and follow a non-stationary distribution. Accordingly, we propose a
  Variational Continual Bayesian Meta-Learning (VC-BML) algorithm. VC-BML maintains
  a Dynamic Gaussian Mixture Model for meta-parameters, with the number of component
  distributions determined by a Chinese Restaurant Process. Dynamic mixtures at the
  meta-parameter level increase the capability to adapt to diverse tasks due to a
  larger parameter space, alleviating the negative knowledge transfer problem. To
  infer posteriors of model parameters, compared to the previously used point estimation
  method, we develop a more robust posterior approximation method -- structured variational
  inference for the sake of avoiding forgetting knowledge. Experiments on tasks from
  non-stationary distributions show that VC-BML is superior in transferring knowledge
  among diverse tasks and alleviating catastrophic forgetting in an online setting.
links:
- name: URL
  url: 
    https://proceedings.neurips.cc/paper/2021/hash/cdd0500dc0ef6682fa6ec6d2e6b577c4-Abstract.html
---
