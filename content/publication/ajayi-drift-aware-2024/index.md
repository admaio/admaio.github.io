---
title: Drift-Aware Policy Selection for Slice Admission Control
authors:
- Jesutofunmi Ajayi
- Antonio Di Maio
- Torsten Braun
date: '2024-05-01'
publishDate: '2024-05-25T00:58:24.558043Z'
publication_types:
- paper-conference
publication: '*IEEE/IFIP Network Operations and Management Symposium*'
doi: 10.13140/RG.2.2.33583.10409
abstract: Fifth-generation (5G) mobile networks are expected to support the dynamic
  provisioning of services with heterogeneous Quality of Service requirements through
  Network Slicing. However, the uncertainty in the resource requirements of the tenant's
  future Network Slice Requests raises the problem of how Network Slices can be admitted
  onto the mobile network infrastructure. To address this, we investigate the Slice
  Admission Control problem in virtualization-enabled mobile networks. Specifically,
  we focus on the scenario in which a controller needs to select an Admission Control
  policy (or algorithm) based on the patterns of previous Network Slice Requests and
  formulate such a problem as a Multi-Armed Bandit problem. By leveraging Online Learning
  (OL), we propose a framework, Drift-AwaRe upper confIdence bOund (DARIO), that adaptively
  selects and learns the performance of online Slice Admission Control (SAC) policies
  by monitoring for changes in the underlying patterns of Network Slice Request (NSR)
  features. We evaluate the performance of our framework in terms of the relative
  gains in average revenue, acceptance ratio, and average resource utilization when
  compared to both static and adaptive baselines and show that we outperform the considered
  baselines for the considered metrics.
---
