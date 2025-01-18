---
title: 'TENET: Adaptive Service Chain Orchestrator for MEC-Enabled Low-Latency 6DoF
  Virtual Reality'
authors:
- Alisson Medeiros
- Antonio Di Maio
- Torsten Braun
- Augusto Neto
date: '2024-04-01'
publishDate: '2025-01-18T12:42:48.703686Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Network and Service Management*'
doi: 10.1109/TNSM.2023.3331755
abstract: The next generation of Virtual Reality (VR) applications is expected to
  provide advanced experiences through Six Degrees of Freedom (6DoF) content, which
  requires higher data rates and ultra-low latency. In this article, we refactor 6DoF
  VR applications into atomic services to increase the computing capacity of VR systems
  aiming to reduce the end-to-end (E2E) of 6DoF VR applications. Those services are
  chained and deployed across Head-Mounted Displays (HMDs) and Multi-access Edge Computing
  (MEC) servers in high mobility scenarios over real-edge network topologies. We investigate
  the Distributed Service Chain Problem (DSCP) to find the optimal service placement
  of services from a service chain such that its E2E latency does not exceed 5 ms.
  The DSCP problem is mathcal NP -hard. We provide an integer linear program to model
  the system, along with a heuristic, namely disTributed sErvice chaiN orchEstraTor
  (TENET), which is one order of magnitude faster than optimally solving the DSCP
  problem. We compare TENET to DSCP implementation and well-known service migration
  algorithms in terms of E2E latency, power consumption, video resolution selection
  based on E2E latency, context migrations, and execution time. We observe a significant
  reduction of E2E latency and gains in more advanced video resolution selection and
  accepted context service migrations when using TENET’s deployment strategy on VR
  services.
tags:
- Computational modeling
- Energy consumption
- Quality of service
- Servers
- quality of service
- Streaming media
- Resists
- multi-access edge computing
- Low latency communication
- end-to-end latency
- Mobile virtual reality
- service function chaining
- service migration
- service offloading
- six degrees of freedom videos
links:
- name: URL
  url: https://ieeexplore.ieee.org/abstract/document/10314807
---
