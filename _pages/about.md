---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![Neurosymbolic AI introduction](/images/quadrotor.png){: .align-right width="500px"}

I have a PhD degree in Computer Science from the school of Engineering in the Univervisty of Southern California (USC-Viterbi) and a M.Sc degree in Mechanical Engineering from the University of Texas at Dallas, with a focus on autonomous systems and control theory.

My focus area is control theory and autonomy. Over the course of my M.Sc degree, I was working on the safety analysis of cyber pgysical systems and networked control systems against sensor noise and anomalies and also control synthesis to satisfy safety properties. During my Ph.D degree I integrated Signal Temporal Logics (STL) and Machine Learning (a combination that is called Neurosymbolic AI) in my study and provided scaling and novel techniques for safety verification of autonomous systems with respect to temporal tasks and also learning based control synthesis for autonomous mobile systems to satisfy temporal specifications.   


# Selected Experience

## Selected Open Source Contributions
We generated the first deterministic formal verification framework for temporal specifications in collaboration with research scientists of Toyota Research Institute North of America (TRINA) [STLVerNN](https://github.com/Navidhashemicontrol/STLVerNN) that verifies general Temporal specifications for Learning enabled autonomous control systems. STL2NN provided to important contributions to field of Signal Temporal Logics. 1- It is a ReLU neural network and maps the previously unsolved problem of verification of STL to the famous and well studied problem of neural network reachability analysis. 2- It is an End-to-End vectorized computation graph which eliminstes the challenging requirement of robustness computation through recursive algorithms or dynamic programming. Our results shows, its computation speed for the value and gradient of robustness is at least 10 times faster than the existing tools in the literature.

We noticeably scaled the computational process of neural feedback control learning for agents to satisfy real-world scaled temporal specification [STL_dropout](https://github.com/Navidhashemicontrol/STL_dropout). This was achieved by combination of a regularization techniaue called stochastic depth (firstly proposed for ResNet) via neurosymbolic control synthesis, enabling us to train controllers for real-world scaled problems in autonomy.

We extended one of the most popular recent techniques for Lipschitz constant analysis of neural networks, [LipSDP](https://proceedings.neurips.cc/paper/2019/hash/95e1533eb1b20a97777749fb94fdb944-Abstract.html), by reformulating it to provide tight and computationally efficient guarantees for local Lipschitz constants. We called this open source contribution [Local-LipSDP](https://github.com/NavidHashemiControl/Local_LipSDP_L4DC_2021). This technique significantly enhances the accuracy and scalability of robustness analysis for neural networks. Furthermore, we demonstrated the substantial contribution of this technique to the verification of autonomous systems operated by neural network controllers.

We presented an End-to-End Semidefinite programming (Convex optimization) for designing the control gains for a networked control system to perform a task (specified via H_2 constraint) while maintaining safety against sensor noise and anomalies. This open source contribution is avalable [here](https://github.com/NavidHashemiControl/Codesign_TCNS_2022).

Please feel free to visit my [github](https://github.com/Navidhashemicontrol) repository for my other open source contributions.

## Research Outcomes
I have published 4 jouranal papers and 17 conference papers focusing on learning based neurosymbolic control synthesis and and its formal verification, safety analysis and safe design of autonomous cyber physical systsems and control theory in the most reputable IEEE and ACM journals and conferences. Feel free to see my [publication entry](https://navidhashemicontrol.github.io/publications/)   
