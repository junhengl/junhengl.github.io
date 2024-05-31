---
title: "Dynamic Loco-manipulation on HECTOR: Humanoid for Enhanced ConTrol and Open-source Research"
collection: publications
permalink: /publication/2023HECTOR
date: 2023-12-01
excerpt: "Authors: Junheng Li, Junchao Ma, Omar Kolt, Manas Shah, and Quan Nguyen<br/><img src='/images/locomanipulation.gif'>"
paperurl: 'https://arxiv.org/abs/2312.11868'
venue: 'arXiv.org'
---

Abstract: Despite their remarkable advancement in locomotion and manipulation, humanoid robots remain challenged by a lack of synchronized loco-manipulation control, hindering their full dynamic potential. In this work, we introduce a versatile and effective approach to controlling and generalizing dynamic locomotion and loco-manipulation on humanoid robots via a Force-and-moment-based Model Predictive Control (MPC). Specifically, we proposed a simplified rigid body dynamics (SRBD) model to take into account both humanoid and object dynamics for humanoid loco-manipulation. This linear dynamics model allows us to directly solve for ground reaction forces and moments via an MPC problem to achieve highly dynamic real-time control. Our proposed framework is highly versatile and generalizable. We introduce HECTOR (Humanoid for Enhanced ConTrol and Open-source Research) platform to demonstrate its effectiveness in hardware experiments. With the proposed framework, HECTOR can maintain exceptional balance during double-leg stance mode, even when subjected to external force disturbances to the body or foot location. In addition, it can execute 3-D dynamic walking on a variety of uneven terrains, including wet grassy surfaces, slopes, randomly placed wood slats, and stacked wood slats up to 6 cm high with the speed of 0.6 m/s. In addition, we have demonstrated dynamic humanoid loco-manipulation over uneven terrain, carrying 2.5 kg load. HECTOR simulations, along with the proposed control framework, are made available as an open-source project. (https://github.com/DRCL-USC/Hector_Simulation).