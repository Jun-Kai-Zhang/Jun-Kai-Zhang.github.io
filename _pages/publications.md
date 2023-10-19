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
  *Authors: Zixiang Chen\*, Junkai Zhang\*, Yiwen Kou, Xiangning Chen, Cho-Jui Hsieh, Quanquan Gu*, in *Advances in Neural Information Processing Systems, 2023* 

  - Characterized the conditions under which benign overfitting can occur in training two-layer convolutional ReLU networks with SGD.

  - Established a rigorous theoretical distinction between SAM and SGD, demonstrating that SAM strictly outperforms SGD in terms of generalization error.

  - Showed that SAM effectively mitigates noise learning in the early stages of training, enabling neural networks to learn features more efficiently.

- [Optimal Horizon-Free Reward-Free Exploration for Linear Mixture MDPs](https://arxiv.org/abs/2303.10165)  
  *Authors: Junkai Zhang, Weitong Zhang, Quanquan Gu*, in *International Conference on Machine Learning, 2023*
  - Proposed an algorithm for reward-free exploration in the linear mixture MDP setting. The algorithm guided the agent to collect samples using a exploration-driven pseudo-reward function.
  - Rigorously proved that our algorithm can achieve a horizon-free sample complexity based on high-order moment estimation that precisely controls the aleatoric and epistemic uncertainty.
  - Established the theoretical lower bound for reward-free algorithm in linear mixture MDP, which matches our upper bound and further proved the optimality of our algorithm.



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
