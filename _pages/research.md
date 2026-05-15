---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Our lab investigates the intersection of AI, optimization, and systems engineering to address real-world challenges in
manufacturing, energy systems, and other engineering applications.
Some examples of our research are shown below.

<style>
.research-item {
  margin-bottom: 40px;
}
.research-img-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 12px;
  margin-bottom: 12px;
}
.research-img-grid img {
  width: 100%;
  height: 240px;
  object-fit: cover;
  border-radius: 6px;
  display: block;
}
.research-title {
  font-size: 1.05em;
  font-weight: bold;
  margin-bottom: 6px;
}
.research-text {
  font-size: 0.95em;
  color: #333;
}
</style>

---

## Advanced Manufacturing System

<div class="research-item">
  <div class="research-title">Explainable multi-agent deep reinforcement learning for manufacturing system scheduling</div>
  <div class="research-img-grid">
    <img src="{{ site.baseurl }}/assets/images/DRL_train.gif" alt="DRL train " style="height: auto; object-fit: contain;"/>
    <img src="{{ site.baseurl }}/assets/images/DRL_goal.png" alt="DRL_goal" style="height: auto; width: auto; object-fit: contain;" />
  </div>
  <div class="research-text">
    We develop deep reinforcement learning frameworks that integrate domain knowledge from manufacturing system modeling
    for dynamic scheduling and process control in manufacturing environments. Our research focuses on
    real-time decision-making under uncertainty, enabling adaptive scheduling and control strategies that not only respond
    to disruptions and changing system conditions, but also ensures critical production constraints such as production order
    fulfillment.
  </div>
</div>

<div class="research-item">
  <div class="research-title">Deep reinforcement learning for adaptive disassembly scheduling</div>
  <div class="research-img-grid">
    <img src="{{ site.baseurl }}/assets/images/disassembly.gif" alt="Disassembly" />
    <img src="{{ site.baseurl }}/assets/images/C-Qmix.png" alt="C-Qmix" />
    <img src="{{ site.baseurl }}/assets/images/schedule.png" alt="schedule" />
  </div>
  <div class="research-text">
    In this study, a constrained multi-agent deep reinforcement learning approach is proposed to maximize the
disassembly profit by dynamically changing the batch mixing ratios of different-sized components in self-
disassembly workstations and adapting real-time scheduling to stochastic product quality, changes in operational
sequences, and self-disassembly failures.
  </div>
</div>

---

## Energy Management

<div class="research-item">
  <div class="research-title">Demand response for fast-charging battery powered material handling equipment</div>
  <div class="research-img-grid">
    <img src="{{ site.baseurl }}/assets/images/framwork.png" alt="framwork" />
    <img src="{{ site.baseurl }}/assets/images/schedule2.png" alt="scheduel" />
    <img src="{{ site.baseurl }}/assets/images/cost.png" alt="cost" />
  </div>
  <div class="research-text">
    In this study, an analytical manufacturing and material handling
system model is proposed to obtain cost-effective production schedules under demand response. The interactions
between machines and MHE, production throughput requirement, battery charging characteristic, and time-
varying electricity pricing are jointly considered in the integrated model to help manufacturers reap substantial
benefits of demand response.
  </div>
</div>