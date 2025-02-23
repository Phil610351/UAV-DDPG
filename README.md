# UAV-DDPG

This is the source code for our paper: **Computation Offloading Optimization for UAV-assisted Mobile Edge Computing: A Deep Deterministic Policy Gradient Approach**. A brief introduction of this work is as follows:

> Unmanned Aerial Vehicle (UAV) can play an important role in wireless systems as it can be deployed flexibly to help improve coverage and quality of communication. In this paper, we consider a UAV-assisted Mobile Edge Computing (MEC) system, in which a UAV equipped with computing resources can provide offloading services to nearby user equipments (UEs). The UE offloads a portion of the computing tasks to the UAV, while the remaining tasks are locally executed at this UE. Subject to constraints on discrete variables and energy consumption, we aim to minimize the maximum processing delay by jointly optimizing user scheduling, task offloading ratio, UAV flight angle and flight speed. Considering the non-convexity of this problem, the high-dimensional state space and the continuous action space, we propose a computation offloading algorithm based on Deep Deterministic Policy Gradient (DDPG) in Reinforcement Learning (RL). With this algorithm, we can obtain the optimal computation offloading policy in an uncontrollable dynamic environment. Extensive experiments have been conducted, and the results show that the proposed DDPG-based algorithm can quickly converge to the optimum. Meanwhile, our algorithm can achieve a significant improvement in processing delay as compared with baseline algorithms, e.g., Deep Q Network (DQN).

This work will be published by Wireless Networks. Click [here](https://link.springer.com/article/10.1007/s11276-021-02632-z) for our paper.

## Required software

TensorFlow 1.X

## Contact

Yunpeng Wang (18120421@bjtu.edu.cn)

Weiwei Fang (fangvv@qq.com)
