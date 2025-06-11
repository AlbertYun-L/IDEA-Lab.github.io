---
title: "Transferable Deep Reinforcement Learning for Adaptive Control Across Varying Manufacturing System Configurations"
collection: publications
category: conferences
permalink: /publication/2025-conference-1
excerpt: 'Authors: Esma Birişçi and Lingxiang Yun'
date: 2025-06-01
venue: 'Institute of Industrial and Systems Engineers Annual Conference'
paperurl: ''
---

Deep reinforcement learning (DRL) offers a powerful approach to the adaptive control of manufacturing systems under various uncertainties. Although existing DRL approaches can consider factors such as material supply fluctuations, shifts in production demand, or changes in energy prices, these methods are typically designed for training on a single, fixed manufacturing system configuration. Consequently, these DRL models must be retrained from scratch to accommodate new manufacturing configurations, limiting their adaptability and scalability. To overcome this limitation, this paper proposes a transferable DRL architecture that can be directly applied across diverse discrete manufacturing systems. Specifically, we propose a fully distributed multi-agent framework that categorizes manufacturing resources into distinct classes based on their functions. Each class of resources requires a similar structure of local information for decision-making, allowing each DRL agent to learn control policy for a class of resources rather than an individual resource. A new observation update method ensures that observable local information is sufficient for distributed agents to make collaborative decisions for a class of resources, regardless of their location within the manufacturing system. As manufacturing systems can be viewed as combinations of these resource classes, agents trained under this framework can be combined flexibly and adapt to various manufacturing system configurations. In case studies, agents are trained on randomly generated manufacturing configurations, and their performance is evaluated on new system setups. Results demonstrate the DRL agents' effectiveness in minimizing energy costs under dynamic pricing while satisfying production throughput constraints.
