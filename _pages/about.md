---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# Zhou Enyu (周恩宇）
I am a Ph.D student in School of Computer Science at Fudan University, advised by [Prof.Xuanjing Huang](https://scholar.google.com/citations?user=RGsMgZA4H78C). 

I obtained a bachelor's degree from Intelligent Science and Technology (Honors Program) at Fudan University.

My research interests mainly lie in NLP, focusing on LLM alignment and reasoning.


# 📚 Publications 

<div class='paper-box'><div class='paper-box-image'  style="text-align: center;"><div><img src='/images/RMB.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**(ICLR'2025)** [RMB: Comprehensively Benchmarking Reward Models in LLM Alignment](https://arxiv.org/pdf/2410.09893)

**Enyu Zhou**, Guodong Zheng, Binghai Wang, Zhiheng Xi, Shihan Dou, Rong Bao, Wei Shen, Limao Xiong, Jessica Fan, Yurong Mou, Rui Zheng, Tao Gui, Qi Zhang, Xuanjing Huang

- Proposed a fine-grained benchmarking framework for reward models, covering pairwise and Best-of-N paradigms, and demonstrated the strong correlation between reward model evaluation and downstream alignment tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'  style="text-align: center;"><div><img src='/images/loramoe.jpg' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**(ACL'2024)** [LoRAMoE: Alleviating world knowledge forgetting in large language models via MoE-style plugin](https://aclanthology.org/2024.acl-long.106.pdf)

Shihan Dou\*, **Enyu Zhou\***, Yan Liu, Songyang Gao, Wei Shen, Limao Xiong, Yuhao Zhou, Xiao Wang, Zhiheng Xi, Xiaoran Fan, Shiliang Pu, Jiang Zhu, Rui Zheng, Tao Gui, Qi Zhang, Xuan-Jing Huang

- Explored challenges of world knowledge forgetting during large-scale fine-tuning and proposed LoRAMoE, an architecture combining LoRA and MoE to mitigate knowledge conflicts and enhance multitask capabilities of LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'  style="text-align: center;"><div><img src='/images/realbehaviorfull.jpg' alt="sym" width="50%"></div></div>
<div class='paper-box-text' markdown="1">

**(EMNLP'2023)** [RealBehavior: A Framework for Faithfully Characterizing Foundation Models' Human-like Behavior Mechanisms](https://arxiv.org/pdf/2310.11227)

**Enyu Zhou**, Rui Zheng, Zhiheng Xi, Songyang Gao, Xiaoran Fan, Zichu Fei, Jingting Ye, Tao Gui, Qi Zhang, Xuanjing Huang

- Developed a framework for faithfully characterizing LLM human-like behaviors based on psychometric theories, establishing automatic testing processes and investigating the effects of alignment training.
</div>
</div>



  
**(AAAI'2025)** [Alleviating Shifted Distribution in Human Preference Alignment through Meta-Learning](https://arxiv.org/pdf/2405.00438)

Shihan Dou, Yan Liu, **Enyu Zhou**, Tianlong Li, Haoxiang Jia, Limao Xiong, Xin Zhao, Junjie Ye, Rui Zheng, Tao Gui, Qi Zhang, Xuanjing Huang


**(ACL'2024)** [Stepcoder: Improve code generation with reinforcement learning from compiler feedback](https://arxiv.org/pdf/2402.01391)

Shihan Dou, Yan Liu, Haoxiang Jia, Limao Xiong, **Enyu Zhou**, Wei Shen, Junjie Shan, Caishuang Huang, Xiao Wang, Xiaoran Fan, Zhiheng Xi, Yuhao Zhou, Tao Ji, Rui Zheng, Qi Zhang, Xuanjing Huang, Tao Gui



# 🎖 Honors and Awards
- *2024.12* Fudan University Huatai Securities Technology Scholarship
- *2023.06* Shanghai Outstanding Graduate Award
- *2021.12* National Scholarship for Undergraduates (Selected as an Outstanding Example)
- *2021.12* "Top Ten Students", School of Information Science and Engineering, Fudan University

# 📖 Educations
- *2023.06 - Present *, School of Computer Science, Fudan University
- *2019.09 - 2023.06*, School of Information Science and Technology, Fudan University
