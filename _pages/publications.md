---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<small>(The asterisk * indicates equal contributions)</small>

- [Why Does Sharpness-Aware Minimization Generalize Better Than SGD?](https://arxiv.org/abs/2310.07269)  
  *Authors: Zixiang Chen\*, __Junkai Zhang\*__, Yiwen Kou, Xiangning Chen, Cho-Jui Hsieh, Quanquan Gu*  
  in *Advances in Neural Information Processing Systems (__NeurIPS__), 2023* 

  - Characterized the conditions under which benign overfitting can occur in training two-layer convolutional ReLU networks with SGD.

  - Established a rigorous theoretical distinction between SAM and SGD, demonstrating that SAM strictly outperforms SGD in terms of generalization error.

  - Showed that SAM effectively mitigates noise learning in the early stages of training, enabling neural networks to learn features more efficiently.

- [Optimal Horizon-Free Reward-Free Exploration for Linear Mixture MDPs](https://arxiv.org/abs/2303.10165)  
  *Authors: __Junkai Zhang__, Weitong Zhang, Quanquan Gu*   
  in *International Conference on Machine Learning (__ICML__), 2023*
  - Proposed an algorithm for reward-free exploration in the linear mixture MDP setting. The algorithm guided the agent to collect samples using a exploration-driven pseudo-reward function.
  - Rigorously proved that our algorithm can achieve a horizon-free sample complexity based on high-order moment estimation that precisely controls the aleatoric and epistemic uncertainty.
  - Established the theoretical lower bound for reward-free algorithm in linear mixture MDP, which matches our upper bound and further proved the optimality of our algorithm.

- Continuous Treatment Effect Modeling in Multi-agent Dynamical Systems  
  *Authors: Zijie Huang\*, Jeehyun Hwang\*, __Junkai Zhang\*__, Jinwoo Baik, Weitong Zhang, Quanquan Gu, Dominik Wodarz, Yizhou Sun, Wei Wang*  
  in *__NeurIPS 2023__ The Symbiosis of Deep Learning and Differential Equations*
  - Utilized graph-structured neural ODEs to capture the coupled evolution of vertices and edges in multi-agent dynamic systems. Incorporated treatments into the ODE by learning a time-dependent representations using attention mechanism.
  - Proposed domain adversarial training objectives to mitigate confounding bias and improve predictions, outperforming all baselines in COVID-19 dataset and tumor growth simulation dataset.

- Fast Sampling Via De-randomization for Discrete Diffusion Models  
  *Authors: Zixiang Chen, Huizhuo Yuan, Yongqian Li, Yiwen Kou, __Junkai Zhang__, Quanquan Gu*  
  in *__NeurIPS 2023__ Workshop on Diffusion Models*
  - Proposed a novel non-markov discrete diffusion process by introducing transition time set. Significantly reduced the number of function evaluations required during the reverse process, achieving up to a $30\times$ speedup in sampling while maintaining or improving generation quality.
  - Developed a continuous-time (infinite-step) sampling algorithm capable of generating even higher-quality samples compared to its discrete-time (finite-step) counterpart.