---
title: 'ARES: Adaptive Resource-Aware Split Learning for Internet of Things'
authors:
- Eric Samikwa
- Antonio Di Maio
- Torsten Braun
date: '2022-12-01'
publishDate: '2024-05-25T00:58:24.455903Z'
publication_types:
- article-journal
publication: '*Computer Networks*'
doi: 10.1016/j.comnet.2022.109380
abstract: Distributed training of Machine Learning models in edge Internet of Things
  (IoT) environments is challenging because of three main points. First, resource-constrained
  devices have large training times and limited energy budget. Second, resource heterogeneity
  of IoT devices slows down the training of the global model due to the presence of
  slower devices (stragglers). Finally, varying operational conditions, such as network
  bandwidth, and computing resources, significantly affect training time and energy
  consumption. Recent studies have proposed Split Learning (SL) for distributed model
  training with limited resources but its efficient implementation on the resource-constrained
  and decentralized heterogeneous IoT devices remains minimally explored. We propose
  Adaptive REsource-aware Split-learning (ARES), a scheme for efficient model training
  in IoT systems. ARES accelerates training in resource-constrained devices and minimizes
  the effect of stragglers on the training through device-targeted split points while
  accounting for time-varying network throughput and computing resources. ARES takes
  into account application constraints to mitigate training optimization tradeoffs
  in terms of energy consumption and training time. We evaluate ARES prototype on
  a real testbed comprising heterogeneous IoT devices running a widely-adopted deep
  neural network and dataset. Results show that ARES accelerates model training on
  IoT devices by up to 48% and minimizes the energy consumption by up to 61.4% compared
  to Federated Learning (FL) and classic SL, without sacrificing model convergence
  and accuracy.
tags:
- Edge computing
- Internet of things
- Distributed machine learning
- Federated learning
- Split learning
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1389128622004145
---
