---
title: "Enhance the Safety in Reinforcement Learning by ADRC Lagrangian Methods"
collection: publications
type: publication
venue: "Submitted to NeurIPS 2025"
date: 2025-01-01
permalink: /publication/adrc-lagrangian
flag: 1
topics: ["Safe RL", "Control", "RL"]
abstract: >-
  Safe reinforcement learning (Safe RL) aims to maximize rewards while satisfying cost constraints.
  Lagrangian-based methods are widely used to address safety concerns, but existing approaches, including PID and
  classical Lagrangian methods, often suffer from oscillations due to parameter sensitivity and inherent phase lag,
  leading to frequent safety violations during training. Active Disturbance Rejection Control (ADRC), with its adaptive
  and robust control capabilities, provides a compelling alternative by effectively managing parameter uncertainties and
  dynamic system behaviors. Leveraging these advantages, in this paper, we introduces ADRC Lagrangian methods that
  reduce oscillations and enhance parameters robustness, positioning classical and PID Lagrangian methods as special
  cases within our framework. Experiments demonstrate that our method reduces safety violations by up to 74%, constraint
  violation magnitudes by 89%, and average costs by 67%, establishing its effectiveness for Safe RL in complex
  environments.
---

{{ page.abstract }}


