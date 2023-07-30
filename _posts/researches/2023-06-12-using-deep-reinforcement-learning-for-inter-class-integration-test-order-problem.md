---
layout: post
title: Using deep reinforcement learning for inter-class integration test order problem
author: Zhicheng Zhang, Yanmei Zhang, Yanru Ding, Guna Yuan, and Wei Dai
date: 2023-06-12 13:17:23 +0800
tags: [Research]
excerpt_separator: <!--excerpt-->
excerpt: The research develops CITO-DRL, a method for applying deep reinforcement learning to the NP problem of the generation of class integration test order. 
sticky: false
---
The research develops CITO-DRL, a method for applying deep reinforcement learning to the NP problem of the generation of class integration test order.<!--excerpt--> Within the framework of the Deep Q-Network algorithm, we devised the state representation, network structures, and environment to make it suitable for the problem. Particularly, we followed the state transition mechanism to convert the state of the agent, extracted inter-class coupling information, and designed a reward function to calculate profits. To evaluate the performance of CITO-DRL, we executed three experiments with seven experimental subjects. The results show that compared with other methods, for the majority of experimental subjects, our method is capable of generating test orders with the lowest complexity and testing important classes as early as possible.

<div><img src="{{"assets/img/posts/2023-06-12-using-deep-reinforcement-learning-for-inter-class-integration-test-order-problem-OCplx.png" | relative_url}}" style="height: 20rem;"></div>

> The paper has been submitted in June 2023 and is presently being given full consideration for publication in Software Testing, Verification and Reliability.

