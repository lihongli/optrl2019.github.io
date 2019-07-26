---
title: 'NeurIPS 2019 Optimization Foundations for Reinforcement Learning Workshop'
layout: default
---

<style>thead { display: none; }</style>

# Background

Dynamic programming (DP) based algorithms, which apply various forms of the Bellman operator, dominate the literature on model-free reinforcement learning (RL). While DP is powerful, the value function estimate can oscillate or even diverge when function approximation is introduced with off-policy data, except in special cases [1-8]. This problem has been well-known for decades (referred to as the deadly triad in the literature), and has remained a critical open fundamental problem in RL.

More recently, the community witnessed a fast-growing trend that frames RL problems as well-posed optimization problems, in which a proper objective function is proposed whose minimization results in the optimal value function [9-28]. Such an optimization-based approach provides a promising perspective that brings mature mathematical tools to bear on integrating linear/nonlinear function approximation with off-policy data, while avoiding DP's inherent instability. Moreover, the optimization perspective is naturally extensible to incorporating constraints, sparsity regularization, distributed multi-agent scenarios, and other new settings.

In addition to being able to apply powerful optimization techniques to a variety of RL problems, the special recursive structure and restricted exploration sampling in RL also naturally raises the question of whether tailored algorithms can be developed to improve sample efficiency, convergence rates, and asymptotic performance, under the guidance of the established optimization techniques.

The goal of this workshop is to catalyze the collaboration between reinforcement learning and optimization communities, pushing the boundaries from both sides. It will provide a forum for establishing a mutually accessible introduction to current research on this integration, and allow exploration of recent advances in optimization for potential application in reinforcement learning. It will also be a window to identify and discuss existing challenges and forward-looking problems of interest in reinforcement learning to the optimization community. 


# Speakers


- Shipra Agrawal
- Sham Kakade
- Ben Van Roy
- Mengdi Wang
- Huizhen Yu

# Call for papers

We will invite submissions on topics such as, but not limited to: 

- Optimization formulations and algorithms for RL
- Optimization correspondences of the components in RL (e.g., on/off-policy, exploration, replay buffer, entropy regularization, target networks, reward shaping, variance reduction, stability, and generalization, etc)
- Theoretical analysis of existing RL algorithms (e.g., temporal difference algorithms);
- Optimization for other RL settings (e.g., distributed/multi-agent RL, robust RL, partial observed RL, and hierarchical RL)
- Empirical comparison of optimization algorithms in RL applications and benchmarks
Other topics at the intersection between reinforcement learning and optimization
- Open problems in optimization raised in RL tasks


A submission is up to 6 pages long in the NeurIPS style, excluding references and appendices. The submission process will be handled via CMT. Author names need not be anonymised. Submission may extend beyond the page limit, but reviewers are not expected to read beyond the first 6 pages. If the work has been previously published in a machine learning journal or conference, including NeurIPS 2019, the workshop submission should be accompanied with a cover letter clearly indicating the venue where it has been published and the extensions beyond the previous work. Parallel submissions (e.g., AISTATS and ICLR) are permitted.

The submission deadline is **September 10th, 2019, 11:59pm PST** and the acceptance notification will be distributed no later than October 1st, 2019. Submissions will be accepted as contributed talks, spotlight or poster presentations based on novelty, technical merit and alignment to the workshop's goals. Final versions will be posted on the workshop website. 


# Dates

- Submission deadline: **September 10th, 2019** (11:59 pm <a href="https://www.timeanddate.com/time/zones/aoe">AOE</a>) 
- Notifications: **Octorber 1st, 2019** 
- Camera ready: **November 15th, 2019** (11:59 pm <a href="https://www.timeanddate.com/time/zones/aoe">AOE</a>) 
<!-- Workshop: **December 13th 2019** 
 -->


# Committees

## Organizers

<div style="text-align: left;">
Bo Dai, Niao He, Nicolas Le Roux, Lihong Li, Dale Schuurmans, Martha White
</div>

<p style="text-align: left">
For questions, please contact us at:
<a href="mailto:optrl2019@gmail.com">optrl2019@gmail.com</a>
</p>


## Program committee

<div style="text-align: left;">
TBD
</div>