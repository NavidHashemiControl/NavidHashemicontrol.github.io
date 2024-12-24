---
title: "LB4TL: A Smooth Semantics for Temporal Logic to Train Neural Feedback Controllers."
collection: publications
permalink: /publication/Navid_IFAC2024
excerpt: ''
date: 2024-07-01
venue: 'IFAC-PapersOnline'
paperurl: 'https://doi.org/10.1016/j.ifacol.2024.07.445'
citation: 'Hashemi, Navid, et al. "LB4TL: A smooth semantics for temporal logic to train neural feedback controllers." IFAC-PapersOnLine 58.11 (2024): 183-188.'
---

This paper presents a framework for training neural network (NN)-based feedback controllers for autonomous agents with deterministic nonlinear dynamics to satisfy task objectives and safety constraints expressed in discrete-time Signal Temporal Logic (DT-STL). Control synthesis that uses the robustness semantics of DT-STL poses challenges due to its non-convexity, non-differentiability, and recursive definition, in particular when it is used to train NN-based controllers. We introduce a smooth neuro-symbolic computation graph to encode DT-STL robustness to represent a smooth approximation of the robustness, enabling the use of powerful stochastic gradient descent and backpropagation-based optimization for training. Our approximation guarantees that it lower bounds the robustness value of a given DT-STL formula, and shows orders of magnitude improvement over existing smooth approximations when applied to control synthesis. We demonstrate our approach on planning to satisfy complex spatio-temporal and sequential tasks, and show scalability with formula complexity.
