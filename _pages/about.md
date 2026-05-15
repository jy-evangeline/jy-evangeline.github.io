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


My name is Jingyan Shen. I am a first-year CS Ph.D. student at New York University (Courant Institute), advised by Prof. [Matus Telgarsky](https://cims.nyu.edu/~matus/) and Prof. [Pavel Izmailov](https://izmailovpavel.github.io/). Previously, I earned my dual master degree from Tsinghua University and Columbia University. Prior to this, I completed my Bachelor's degree at Wuhan University, majoring in Statistics. 

I am broadly interested in machine learning and statistics, with a current focus on reinforcement learning for reasoning and planning. My current research studies when and why RL-based post-training improves reasoning in large language models. In particular, I am interested in:

- **RL scaling and model priors**: how the benefits and dynamics of RL post-training are shaped by what a model has already learned during pretraining or supervised fine-tuning.
- **Weak-to-strong generalization**: how RL can elicit stronger reasoning from limited, noisy, or weak supervision.
- **Continual self-improvement**: how LLMs can improve beyond fixed human-curated data through self-play, self-generated curricula, and verifier-guided exploration.

I am also fortunate to work with many great scholars and mentors, and I’m deeply grateful for their guidance.

<!-- <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🗞 News
<div class="scroll-box scroll-box--news" markdown="1">
- *2026.06*: &nbsp;🌃 Joining **Microsoft Research (NYC)** as a Research Intern in Summer 2026! Feel free to reach out if you would like to connect or chat about research!
- *2026.05*: &nbsp;🏅 Selected as an **ICML 2026 Gold Reviewer**.
- *2025.11*: &nbsp;🎉 [MiCRo](https://arxiv.org/pdf/2505.24846) received the **EMNLP 2025 Outstanding Paper Award**!
</div>

# 🔬 Preprints & Workshops
(<sup>†</sup>: equal contribution)

<div class="scroll-box scroll-box--pub" markdown="1">

**When Can LLMs Learn to Reason with Weak Supervision?**  
Salman Rahman<sup>†</sup>, **Jingyan Shen**<sup>†</sup>, Anna Mordvina, Hamid Palangi, Saadia Gabriel, Pavel Izmailov  
Preprint. \[[Paper](https://arxiv.org/abs/2604.18574)\] \[[Project Page](https://salmanrahman.net/rlvr-weak-supervision)\]

**When Reasoning Meets Its Laws**

  Junyu Zhang<sup>†</sup>, Yifan Sun<sup>†</sup>, Tianang Leng<sup>†</sup>, **Jingyan Shen**<sup>†</sup>, Ziyin Liu, Paul Pu Liang, Huan Zhang  
  <span style="color:blue;">Efficient Reasoning Workshop at NeurIPS 2025</span> (Oral Presentation, <span style="color:red;">Best Paper Nomination</span>) \[[Paper](https://arxiv.org/pdf/2512.17901)\] \[[Website](https://lore-project.github.io/)\]

</div>

# 🔬 Selected Publications

<div class="scroll-box scroll-box--pub" markdown="1">

**Adversarially Robust Control of Conditional Value-at-Risk via Kelly Conformal Inference**  
Catherine Chen, **Jingyan Shen**, Zhun Deng, Lihua Lei  
<span style="color:blue;">ICML</span> 2026

**MiCRo: Mixture Modeling and Context-aware Routing for Personalized Preference Learning**

  **Jingyan Shen**<sup>†</sup>, Jiarui Yao<sup>†</sup>, Rui Yang<sup>†</sup>, Yifan Sun, Feng Luo, Rui Pan, Tong Zhang, Han Zhao  
  <span style="color:blue;">EMNLP</span> 2025 (Main) <span style="color:red;">Outstanding Paper Award 🏆</span> \[[Paper](https://arxiv.org/pdf/2505.24846)\]

**Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay**

  Yifan Sun<sup>†</sup>, **Jingyan Shen**<sup>†</sup>, Yibin Wang<sup>†</sup>, Tianyu Chen, Zhendong Wang, Mingyuan Zhou, Huan Zhang  
  <span style="color:blue;">NeurIPS</span> 2025 \[[Paper](https://arxiv.org/pdf/2506.05316)\]

**Conformal Tail Risk Control for Large Language Model Alignment**

  Catherine Chen,  **Jingyan Shen**, Zhun Deng, Lihua Lei  
  <span style="color:blue;">ICML</span> 2025 \[[Paper](https://arxiv.org/abs/2502.20285)\]

**Rethinking Diverse Human Preference Learning through Principal Component Analysis**

  Feng Luo, Rui Yang, Hao Sun, Chunyuan Deng, Jiarui Yao, **Jingyan Shen**, Huan Zhang, Hanjie Chen  
  <span style="color:blue;">ACL</span> 2025 (Findings) \[[Paper](https://arxiv.org/pdf/2502.13131)\]

**TimeInf: Time Series Data Contribution via Influence Functions**

  Yizi Zhang<sup>†</sup>, **Jingyan Shen**<sup>†</sup>, Xiaoxue Xiong<sup>†</sup>, Yongchan Kwon  
  <span style="color:blue;">ICLR</span> 2025 \[[Paper](https://arxiv.org/pdf/2407.15247)\] \[[Code](https://github.com/yzhang511/TimeInf)\]

**2D-OOB: Attributing Data Contribution through Joint Valuation Framework**

  Yifan Sun<sup>†</sup>, **Jingyan Shen**<sup>†</sup>, Yongchan Kwon  
  <span style="color:blue;">NeurIPS</span> 2024 \[[Paper](https://arxiv.org/abs/2408.03572)\] \[[Code](https://github.com/yifansun99/2D-OOB-Joint-Valuation)\]

</div>

<!-- 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

Yizi Zhang$^\dag$,  **Jingyan Shen**$^\dag$, Xiaoxue Xiong$^\dag$, and Yongchan Kwon

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- ICML 2026 Gold Reviewer, 2026
- Outstanding Paper Award, EMNLP 2025
- MacCracken Fellowship, New York University, 2025
- Outstanding Graduate Student (Top 1%), Tsinghua University, 2024
- Excellent Graduate Thesis Award, Tsinghua University, 2024
- Graduate Fellowship, Columbia University, 2023
- Outstanding Undergraduate Student, Wuhan University, 2021
- National Scholarship for Undergraduates, Ministry of Education of China, 2018

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)-->

# 👾 Industry Experience
- *2024.02 - 2025.06*, Full-time machine learning engineer at Pinterest

# 🐰 Miscs
I value the diversity and richness of life, and I hold a deep respect for beauty and purity in all their forms. Beyond research, I enjoy playing table tennis and tennis, playing drums, losing myself in a good book, or discovering new places through travel. My recent favorite books include *Flowers for Algernon* and *Why Fish Don't Exist*. I am also a big fan of Stephen Sondheim’s musicals, particularly *Company* and *Sunday in the Park with George*. Born in Guangzhou, I’m picky about food and I particularly enjoy Japanese and Cantonese cuisine for their focus on fresh ingredients and natural flavors.