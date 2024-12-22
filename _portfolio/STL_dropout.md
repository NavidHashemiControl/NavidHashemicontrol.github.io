---
title: "STL_dropout"
excerpt: "Neural Feedback Policy training for long time horizon tasks and high dimensional systems.<br/><img src='/images/quadapprox_intro.png'>"
collection: portfolio
---

In this repository I provided a toolbox that scales the Neurosymbolic algorithm, for neural controller training for temporal tasks to longer time horizon and higher state dimensions. The toolbox is available from [here](https://github.com/Navidhashemicodes/STL_dropout). The main issue for scalability is the problem of vanish/explode gradient when the taks horizon is long or the system dimension is high. We provided a novel gradient approximation technique specifically for policy optimization via Signal Temporal Logics objectives, that combines the idea of [stochastic depth](https://arxiv.org/abs/1603.09382) and the idea of [critical predicates](https://www.sciencedirect.com/science/article/pii/S0304397509004149) for STL. This provides a scalable algorithm that enables us doing policy optimization to satisfy real-world and complex temporal tasks. 
