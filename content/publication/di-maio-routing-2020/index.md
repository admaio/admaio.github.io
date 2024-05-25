---
title: Routing Strategies and Content Dissemination Techniques for Software-Defined
  Vehicular Networks
authors:
- Antonio Di Maio
date: '2020-06-01'
publishDate: '2024-05-25T00:58:24.402403Z'
publication_types:
- thesis
abstract: Over the past years, vehicular networking has enabled a wide range of new
  applications that improve vehicular safety, efficiency, comfort, and environmental
  impact. Vehicular networks, however, normally operate in communication-hostile environments
  and are characterized by dynamic topologies and volatile links, making it challenging
  to guarantee Quality of Service (QoS) and reliability of vehicular applications.
  To this end, the present work explores how the centralized coordination offered
  by Software-Defined Networking can improve the Quality of Service in vehicular networks,
  particularly for Vehicle-to-Vehicle (V2V) unicast routing and content dissemination.
  With regard to V2V routing, this work motivates the case for centralized network
  coordination by studying the performance of traditional MANET routing protocols
  when applied to urban VANETs, showing that they cannot provide satisfactory performance
  for modern vehicular applications because of their limited global network awareness,
  slow convergence, and high signaling. Hence, this work proposes and validates a
  centralized Multi-Flow Congestion-Aware Routing (MFCAR) algorithm to allocate multiple
  data flows on V2V routes. The first novelty of MFCAR is the SDN-based node-busyness
  estimation technique. The second novelty is the enhancement of the path-cost formulation
  as a linear combination of path length and path congestion, allowing the user application
  to fine-tune its QoS requirements between throughput and delay. Concerning content
  dissemination, this work proposes a Fairness- and Throughput-Enhanced Scheduling
  for Content Dissemination in VANETs (ROADNET), a centralized strategy to improve
  the tradeoff between data throughput and user fairness in deterministic vehicular
  content dissemination. ROADNET’s main novelties are the design of a graph-based
  multi-channel transmission scheduler and the enforcement of a transmission-priority
  policy that prevents user starvation. As additional contributions, the present work
  proposes a heuristic for the centralized selection of opportunistic content dissemination
  parameters and discusses the main security issues in Software-Defined Vehicular
  Networking (SDVN) along with possible countermeasures. The proposed techniques are
  evaluated in realistic scenarios (LuST), using discrete-event network simulators
  (OMNeT++) and microscopic vehicular-mobility simulators (SUMO). It is shown that
  MFCAR can improve PDR, throughput and delay for unicast V2V routing up to a five-fold
  gain over traditional algorithms. ROADNET can increase content dissemination throughput
  by 36% and user fairness by 6% compared to state-of-the-art techniques, balancing
  the load over multiple channels with a variance below 1%.
links:
- name: URL
  url: https://orbilu.uni.lu/handle/10993/43560
---
