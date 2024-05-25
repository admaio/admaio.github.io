---
title: 'TENET: Adaptive Service Chain Orchestrator for MEC-enabled Low-latency 6DoF
  Virtual Reality'
authors:
- Alisson Medeiros
- Antonio Di Maio
- Torsten Braun
- Augusto Neto
date: '2023-01-01'
publishDate: '2024-05-25T00:58:24.477874Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Network and Service Management*'
abstract: The next generation of Virtual Reality (VR) applications is expected to
  provide advanced experiences through Six Degrees of Freedom (6DoF) content, which
  requires higher data rates and ultra-low latency. In this article, we refactor 6DoF
  VR applications into atomic services to increase the computing capacity of VR systems
  aiming to reduce the end-to-end (E2E) of 6DoF VR applications. Those services are
  chained and deployed across Head-Mounted Displays (HMDs) and Multi-access Edge Computing
  (MEC) servers in high mobility scenarios over realedge network topologies. We investigate
  the Distributed Service Chain Problem (DSCP) to find the optimal service placement
  of services from a service chain such that its E2E latency does not exceed 5 ms.
  DSCP problem is NP-hard. We provide an integer linear program to model the system,
  along with a heuristic, namely disTributed sErvice chaiN orchEstraTor (TENET), which
  is one order of magnitude faster than optimally solving the DSCP problem.We compare
  TENET to DSCP implementation and wellknown service migration algorithms in terms
  of E2E latency, power consumption, video resolution selection based on E2E latency,
  context migrations, and execution time. We observe a significant reduction of E2E
  latency and gains in more advanced video resolution selection and accepted context
  service migrations when using TENET’s deployment strategy on VR services.
links:
- name: URL
  url: https://boris.unibe.ch/185670/
---
