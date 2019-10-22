---
title: 'NeurIPS 2019 Optimization Foundations of Reinforcement Learning Workshop'
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


# Dates

- Submission deadline: **~~September 10th~~, ~~September 17th, 2019~~** (~~11:59 pm <a href="https://www.timeanddate.com/time/zones/aoe">AOE</a>~~) 
- Notifications: **~~October 1st, 2019~~** 
- Camera ready: **November 15th, 2019** (11:59 pm <a href="https://www.timeanddate.com/time/zones/aoe">AOE</a>) 
<!-- Workshop: **December 13th 2019** 
 -->


# Awards

<!-- We are working to find funding to support travel for students, especially those in underrepresented groups. -->

We will provide student travel awards to the authors of the accepted papers for complimentary workshop registration. 

To apply for the travel awards, please send the following information to <a href="mailto:optrl2019@gmail.com">optrl2019@gmail.com</a> by the application deadline **Oct. 28th**:
- Title with [OptRL 2019 Student Travel Awards Application].
- Your paper ID and title.
- A brief bio, no more than one paragraph.
- Student status certificate, such as photocopies of student ID or university website. 


# Sponsors

<p style="text-align: left">
We thank our sponsor to make this workshop possible:
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
    <li>Alekh Agarwal</li>
    <li>Zafarali Ahmed</li>
    <li>Kavosh Asad</li>
    <li>Marlos C. Machado</li>
    <li>Jianshu Chen</li>
    <li>Yinlam Chow</li>
    <li>Adithya Devraj</li>
    <li>Thinh Doan</li>
    <li>Simon Du</li>  
    <li>Yihao Fen</li> 
    <li>Roy Fox</li>
    <li>Matthieu Geist</li>
    <li>Saeed Ghadimi</li>
  </ul> 
  </div>
  <div class="column">
  <ul>
    <li>Shixiang Gu</li>
    <li>Botao Hao</li> 
    <li>Nan Jiang</li> 
    <li>Ajin Joseph</li> 
    <li>Donghwan Lee</li>
    <li>Alex Lewandowski</li>
    <li>Vincent Liu</li>
    <li>Rupam Mahmood</li> 
    <li>Jincheng Mei</li>
    <li>Ofir Nachum</li>
    <li>Gergely Neu</li>
    <li>Mohammad Norouzi</li>
    <li>Andrew Patterson</li> 
  </ul> 
  </div>
  <div class="column">
  <ul>
    <li>Yash Satsangi</li>
    <li>Matthew Schlegel</li>
    <li>Karan Singh</li>
    <li>Ziyang Tang</li>
    <li>Valentin Thomas</li>
    <li>Sergio Valcarcel Macua</li>
    <li>Junfeng Wen</li>
    <li>Zheng Wen</li>
    <li>Adam White</li>
    <li>Tengyang Xie</li>
    <li>Zhuoran Yang</li>
    <li>Shangtong Zhang</li>
    <li>Tuo Zhao</li>
  </ul> 
  </div>
</div>
</div>



<p style="text-align: left">
For questions, please contact us:
<a href="mailto:optrl2019@gmail.com">optrl2019@gmail.com</a>
</p>