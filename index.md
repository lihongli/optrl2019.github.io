---
title: 'NeurIPS 2019 Optimization Foundations for Reinforcement Learning Workshop'
layout: default
---

<style>thead { display: none; }</style>

# Background

Dynamic programming (DP) based algorithms, which apply various forms of the Bellman operator, dominate the literature on model-free reinforcement learning (RL). While DP is powerful, the value function estimate can oscillate or even diverge when function approximation is introduced with off-policy data, except in special cases. This problem has been well-known for decades (referred to as the deadly triad in the literature), and has remained a critical open fundamental problem in RL.

More recently, the community witnessed a fast-growing trend that frames RL problems as well-posed optimization problems, in which a proper objective function is proposed whose minimization results in the optimal value function. Such an optimization-based approach provides a promising perspective that brings mature mathematical tools to bear on integrating linear/nonlinear function approximation with off-policy data, while avoiding DP's inherent instability. Moreover, the optimization perspective is naturally extensible to incorporating constraints, sparsity regularization, distributed multi-agent scenarios, and other new settings.

In addition to being able to apply powerful optimization techniques to a variety of RL problems, the special recursive structure and restricted exploration sampling in RL also naturally raises the question of whether tailored algorithms can be developed to improve sample efficiency, convergence rates, and asymptotic performance, under the guidance of the established optimization techniques.

The goal of this workshop is to catalyze the collaboration between reinforcement learning and optimization communities, pushing the boundaries from both sides. It will provide a forum for establishing a mutually accessible introduction to current research on this integration, and allow exploration of recent advances in optimization for potential application in reinforcement learning. It will also be a window to identify and discuss existing challenges and forward-looking problems of interest in reinforcement learning to the optimization community. 


# Invited Speakers


- <a href="http://www.columbia.edu/~sa3305/">Shipra Agrawal</a> (Columbia University)
- <a href="https://homes.cs.washington.edu/~sham/">Sham Kakade</a> (University of Washington) 
- <a href="https://web.stanford.edu/~bvr/">Benjamin Van Roy</a> (Stanford University) 
- <a href="https://mwang.princeton.edu/">Mengdi Wang</a> (Princeton University) 
- <a href="https://directory.ualberta.ca/person/huizhen">Huizhen Yu</a> (University of Alberta)



# Call for papers

We will invite submissions on topics such as, but not limited to: 

- Optimization formulations and algorithms for RL
- Optimization correspondences of the components in RL (e.g., on/off-policy, exploration, replay buffer, entropy regularization, target networks, reward shaping, variance reduction, stability, and generalization, etc)
- Theoretical analysis of existing RL algorithms (e.g., temporal difference algorithms);
- Optimization for other RL settings (e.g., distributed/multi-agent RL, robust RL, partial observed RL, and hierarchical RL)
- Empirical comparison of optimization algorithms in RL applications and benchmarks
Other topics at the intersection between reinforcement learning and optimization
- Open problems in optimization raised in RL tasks


A submission is up to 6 pages long in the <a href="https://nips.cc/Conferences/2019/PaperInformation/StyleFiles">NeurIPS style</a>, excluding references and appendices. The submission process will be handled via <a href="https://cmt3.research.microsoft.com/OPTRL2019">CMT</a>. Author names need not be anonymised. Parallel submissions (e.g., AISTATS and ICLR) are permitted.

The submission deadline is **~~September 10th~~ ~~September 17th, 2019, 11:59pm AOE~~** and the acceptance notification will be distributed no later than **October 1st, 2019**. Submissions will be accepted as contributed talks, spotlight or poster presentations based on novelty, technical merit and alignment to the workshop's goals. Final versions will be posted on the workshop website. 

Paper submission portal: <a href="https://cmt3.research.microsoft.com/OPTRL2019"> https://cmt3.research.microsoft.com/OPTRL2019 </a>

# Dates

- Submission deadline: **~~September 10th~~, ~~September 17th, 2019~~** (~~11:59 pm <a href="https://www.timeanddate.com/time/zones/aoe">AOE</a>~~) 
- Notifications: **~~October 1st, 2019~~** 
- Camera ready: **November 15th, 2019** (11:59 pm <a href="https://www.timeanddate.com/time/zones/aoe">AOE</a>) 
<!-- Workshop: **December 13th 2019** 
 -->


# Awards

We are working to find funding to support travel for students, especially those in underrepresented groups.


<!-- # Sponsors

<p style="text-align: left">
We thank our sponsors for making this workshop possible:
</p>

<div style="text-align: left;">
{%- for sponsor in site.data.sponsors -%}
<div class="sponsor">
  <a href="{{ sponsor.url }}" target="_blank">
    <img src="{{ sponsor.image }}" />
  </a>
</div>
{%- endfor -%}
</div>
 -->
# Accepted Papers

We have received many high-quality submissions. The order below is random. Some papers will be selected to give an additional oral/spotlight presentation, which will be announced soon.

- **Kalman Optimization for Value Approximation**. Shirli Di-Castro, Shie Mannor
- **Hierarchical model-based policy optimization: from actions to action sequences and back**. Daniel McNamee
- **Representational Limits in Reinforcement Learning**. Simon Du, Sham Kakade, Ruosong Wang, Lin Yang
- **Apprenticeship Learning via Frank-Wolfe**.  Tom Zahavy, Haim Kaplan, Alon Cohen, Yishay Mansour	
- **Improving Evolutionary Strategies With Past Descent Directions**. Asier Mujika, Florian Meier, Marcelo Matheus Gauy, Angelika Steger
- **ALGAE: Policy Gradient from Arbitrary Experience**.	Ofir Nachum, Bo Dai, Ilya  Kostrikov, Dale  Schuurmans
- **A Distributional Analysis of Sampling-Based Reinforcement Learning Algorithms**. Philip Amortila, Doina Precup, Prakash  Panangaden, Marc G. Bellemare	
- **ISL: Optimal Policy Learning With Optimal Exploration-Exploitation Trade-Off**. Lucas C Cassano, Ali H Sayed
- **Learning Reward Machines for Partially Observable Reinforcement Learning**. Rodrigo A Toro Icarte, Ethan Waldie, Toryn  Klassen,  Richard Valenzano, Margarita  Castro, Sheila A.  McIlraith	
- **Provably Convergent Off-Policy Actor-Critic with Function Approximation**. Shangtong Zhang, Bo Liu, Hengshuai Yao, Shimon Whiteson
- **Q-learning with UCB Exploration is Sample Efficient for Infinite-Horizon MDP**.	Kefan Dong, Yuanhao Wang, Xiaoyu Chen, Liwei Wang
- **Adaptive Smoothing Path Integral Control**. Dominik Thalmeier, Bert Kappen, Simone Totaro, Vicenç Gómez
- **Data Efficient Training for Reinforcement Learning with Adaptive Behavior Policy Sharing**. Ge Liu, Heng-Tze Cheng, Rui  Wu, Jing  Wang, Jayiden Ooi, Ang Li, Sibon Li, Lihong Li, Craig Boutilier
- **A Two Time-Scale Update Rule Ensuring Convergence of Episodic Reinforcement Learning Algorithms at the Example of RUDDER**. Markus 	Holzleitner, José Arjona-Medina, Marius-Constantin  Dinu, Sepp  Hochreiter
- **Distributional Reinforcement Learning for Energy-Based Sequential Models**. Tetiana Parshakova, Jean-Marc Andreoli, Marc Dymetman
- **Multi-Task Reinforcement Learning without Interference**. Tianhe Yu, Saurabh Kumar, Abhishek Gupta, Karol Hausman, Sergey Levine, Chelsea Finn
- **Toward Provably Unbiased Temporal-Difference Value Estimation**. Roy Fox
- **Provable Q-Iteration without Concentrability** Ming Yu, Zhuoran Yang, Mengdi Wang, Zhaoran Wang
- **Faster saddle-point optimization for solving large-scale Markov decision processes**. Joan Bas Serrano, Gergely Neu
- **Approximate information state for partially observed systems**. Jayakumar Subramanian, Aditya Mahajan
- **Logarithmic Regret for Online Control**. Naman Agarwal, Elad Hazan, Karan Singh	
- **Solving Discounted Stochastic Two-Player Games with Near-Optimal Time and Sample Complexity**. Aaron Sidford, Mengdi Wang, Lin Yang, Yinyu Ye
- **Improved Upper and Lower Bounds for Policy and Strategy Iteration**. Aaron Sidford, Mengdi Wang, Lin  Yang, Yinyu Ye
- **Reinforcement Learning in Feature Space: Matrix Bandit, Kernels, and Regret Bound**. Lin Yang, Mengdi Wang
- **Deterministic Bellman Residual Minimization**. Ehsan Saleh, Nan Jiang,
- **Empirical Likelihood for Contextual Bandits**. Nikos Karampatziakis, John Langford, Paul Mineiro.
- **Reinforcement Learning with Langevin Dynamics**. Parameswaran Kamalaruban, Doga Tekin, Paul Rolland, Volkan Cevher
- **Provably Efficient Reinforcement Learning with Linear Function Approximation**. Chi Jin, Zhuoran Yang, Zhaoran Wang, Michael Jordan
- **On the Finite-Time Convergence of Actor-Critic Algorithm**.	Shuang Qiu, Zhuoran Yang, Jieping Ye, Zhaoran Wang
- **Approximability Gap between Model-based and Model-free Algorithms in Continuous State Space**. Kefan Dong, Yuping Luo, Tengyu Ma
- **Entropy Regularization with Discounted Future State Distribution in Policy Gradient Methods**. Riashat Islam, Raihan Seraj, Pierre-Luc Bacon, Doina Precup,
- **Batch and Sequential Policy Optimization with Doubly Robust Objectives**. Alex P Lewandowski, Dale Schuurmans
- **A Single Time-scale Stochastic Approximation Method for Nested Stochastic Optimization**. Saeed Ghadimi, Andrzej Ruszczynski, Mengdi Wang
- **CAQL: Continuous Action Q-Learning**. Yinlam Chow, Moonkyung Ryu, Craig Boutilier, Ross Anderson, Christian Tjandraatmadja 
- **Harnessing Infinite-Horizon Off-Policy Evaluation: Double Robustness via Duality**. Ziyang Tang, Yihao Feng, Lihong Li, Denny Zhou, Qiang Liu
- **The Gambler's Problem and Beyond**. Baoxiang Wang, Shuai  Li, Jiajin Li, Siu	On
- **Toward Understanding Catastrophic Interference in Online Reinforcement Learning**. Vincent Liu, Hengshuai Yao, Martha White
- **Optimistic Adaptive Gradient Methods**. Xinyi Chen, Simon Du, Elad Hazan
- **QNTRPO: Including Curvature in TRPO**. Devesh K Jha, Arvind U Raghunathan, Diego Romeres
- **Selectively Planning with Imperfect Models via Learned Error Signals**. Muhammad Zaheer, Samuel Sokota, Erin Talvitie, Martha White
- **A Stochastic Derivative Free Optimization Method with Momentum**. Eduard Gorbunov, Adel Bibi, Ozan Sener, El Houcine Bergou, Peter Richtarik
- **Actor-Critic Provably Finds Nash Equilibria of Linear-Quadratic Mean-Field Games**. Zuyue Fu, Zhuoran Yang, Yongxin Chen, Zhaoran Wang
- **Trajectory-wise Control Variates for Variance Reduction in Policy Gradient Methods**. Xinyan Yan, Ching-An Cheng, Byron Boots
- **Continuous Online Learning and New Insights to Online Imitation Learning**. Jonathan Lee, Ching-An Cheng, Ken Goldberg, Byron Boots
- **Analyzing the Variance of Policy Gradient Estimators for the Linear-Quadratic Regulator**. James Preiss, Chen-Yu Wei, Sébastien Arnold, Marius Kloft
- **Sample Efficient Policy Gradient Methods with Recursive Variance Reduction**. Pan Xu, Xi Gao, Quanquan Gu
- **Adaptive Trust Region Policy Optimization: Convergence and Faster Rates of regularized MDPs**. Lior Shani, Yonathan Efroni, Shie Mannor
- **A Lagrangian Method for Inverse Problems in Reinforcement Learning**. Pierre-Luc Bacon, Florian T Schaefer, Clement Gehring, Animashree Anandkumar, Emma Brunskill
- **Policy Continuation and Policy Evolution with Hindsight Inverse Dynamics**. Hao Sun, Bo  Dai, Zhizhong Li, Xiaotong Liu, Rui  Xu, Dahua Lin, Bolei Zhou
- **Observational Overfitting in Reinforcement Learning**. Xingyou Song, YiDing Jiang, Yilun Du, Behnam Neyshabur
- **Compatible features for Monotonic Policy Improvement**. Marcin B Tomczak, Sergio Valcarcel Macua, Enrique Munoz De Cote, Peter Vrancx
- **Analysis of Q-Learning: Switching System Approach**. Donghwan Lee, Niao He
- **On the Convergence of Approximate and Regularized Policy Iteration Schemes** Elena Smirnova, Elvis Dohmatob
- **An Asynchronous Multi-Agent Actor-Critic Algorithm for Distributed Reinforcement Learning**. Yixuan Lin, Yuehan Luo, Wesley Suttle, Kaiqing Zhang, Zhuoran Yang, Zhaoran  Wang, Tamer Basar, Romeil Sandhu, Ji Liu
- **On the Expected Dynamics of Nonlinear TD Learning**. David Brandfonbrener, Joan Bruna
- **Revisit Policy Optimization in Matrix Form**. Sitao Luan, Xiao-Wen Chang, Doina Precup
- **A Finite Time Analysis of Temporal Difference Learning With Linear Function Approximation**. Jalaj Bhandari, Daniel Russo
- **Global Optimality Guarantees For  Policy Gradient Methods**. Jalaj Bhandari, Daniel Russo
- **On the Sample Complexity of Actor-Critic for Reinforcement Learning**. Harshat Kumar, Alec Koppel, Alejandro Ribeiro
- **Adaptive Discretization for Episodic Reinforcement Learning in Metric Spaces**. Siddhartha Banerjee, Sean Sinclair, Christina Lee Yu
- **Fast distributed temporal-difference learning via homotopy stochastic primal-dual optimization**. Dongsheng Ding, Xiaohan Wei, Zhuoran Yang, Zhaoran Wang, Mihailo Jovanovic
- **Performance of Q-learning with Linear Function Approximation: Stability and Finite Time Analysis**. Zaiwei Chen, Sheng Zhang, Thinh T Doan, Siva Theja Maguluri, John-Paul Clarke
- **Feature-Based Q-Learning for Two-Player Stochastic Games**. Zeyu Jia, Lin Yang, Mengdi Wang
- **A Convergence Result for Regularized Actor-Critic Methods**. Wesley Suttle, Zhuoran  Yang, Kaiqing Zhang, Ji Liu
- **Neural Policy Gradient Methods: Global Optimality and Rates of Convergence**. Lingxiao Wang, Qi Cai, Zhuoran Yang
- **All-Action Policy Gradient Methods: A Numerical Integration Approach**. Benjamin Petit, Loren Amdahl-Culleton, Yao Liu, Jimmy Smith, Pierre-Luc Bacon
- **On Connections between Constrained Optimization and Reinforcement Learning**. Nino Vieillard, Olivier Pietquin, Matthieu Geist
- **Worst-Case Regret Bound for Perturbation Based Exploration in Reinforcement Learning**. Ziping Xu, Ambuj Tewari
- **Generalized Policy Updates for Policy Optimization**. Saurabh Kumar, Robert Dadashi, Zafarali Ahmed, Dale Schuurmans, Marc G. Bellemare
- **Stochastic convex optimization for provably efficient apprenticeship learning**.  Angeliki Kamoutsi
- **Discounted Reinforcement Learning is Not an Optimization Problem**. Abhishek Naik, Roshan Shariff, Niko Yasui, Richard Sutton
- **On Computation and Generalization of Generative Adversarial Imitation Learning**. Minshuo Chen, Yizhou Wang, Tianyi  Liu, Xingguo Li, Zhuoran Yang, Zhaoran Wang, Tuo Zhao




# Committees

## Organizers

<!-- <div style="text-align: left;">
Bo Dai, Niao He, Nicolas Le Roux, Lihong Li, Dale Schuurmans, Martha White
</div>
 -->

- <a href="https://sites.google.com/site/daibohr/">Bo Dai</a> (Google Brain)
- <a href="http://niaohe.ise.illinois.edu/">Niao He</a> (University of Illinois at Urbana-Champaign)
- <a href="http://nicolas.le-roux.name/">Nicolas Le Roux</a> (Google Brain)
- <a href="https://lihongli.github.io/">Lihong Li</a> (Google Brain) 
- <a href="https://webdocs.cs.ualberta.ca/~dale/">Dale Schuurmans</a> (Google Brain & University of Alberta)
- <a href="https://webdocs.cs.ualberta.ca/~whitem/">Martha White</a> (University of Alberta)


## Program committee

<div style="text-align: left;">
<div class="row">
  <div class="column">
  <ul>
    <li>Bo Dai</li>
    <li>Bo Dai</li>
  </ul> 
  </div>
  <div class="column">
  <ul>
    <li>Bo Dai</li>
    <li>Bo Dai</li>
  </ul> 
  </div>
  <div class="column">
  <ul>
    <li>Bo Dai</li>
    <li>Bo Dai</li>
  </ul> 
  </div>
</div>
</div>



<p style="text-align: left">
For questions, please contact us:
<a href="mailto:optrl2019@gmail.com">optrl2019@gmail.com</a>
</p>