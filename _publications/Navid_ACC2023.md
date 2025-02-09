---
title: "Risk-awareness in learning neural controllers for temporal logic objectives"
collection: publications
permalink: /publication/Navid_ACC2023
excerpt: ''
date: 2023-05-01
venue: '2023 American Control Conference (ACC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10156345'
citation: 'Hashemi, Navid, Xin Qin, Jyotirmoy V. Deshmukh, Georgios Fainekos, Bardh Hoxha, Danil Prokhorov, and Tomoya Yamaguchi. "Risk-awareness in learning neural controllers for temporal logic objectives." In 2023 American Control Conference (ACC), pp. 4096-4103. IEEE, 2023.'
---

In this paper, we consider the problem of synthesizing a controller in the presence of uncertainty such that the resulting closed-loop system satisfies certain hard constraints while optimizing certain (soft) performance objectives. We assume that the hard constraints encoding safety or mission-critical specifications are expressed using Signal Temporal Logic (STL), while performance is quantified using standard cost functions on system trajectories. To ensure satisfaction of the STL constraints, we algorithmically obtain control barrier functions (CBFs) from the STL specifications. We model controllers as neural networks (NNs) and provide an algorithm to train the NN parameters to simultaneously optimize the performance objectives while satisfying the CBF conditions (with a user-specified robustness margin). We evaluate the risk incurred by the trade-off between the robustness margin of the system and its performance using the formalism of risk measures. We demonstrate our approach on challenging nonlinear control examples such as quadcopter motion planning and a unicycle.
