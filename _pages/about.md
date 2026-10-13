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


My name is Jingyan Shen. I am a second-year CS Ph.D. student at New York University (Courant Institute), advised by Prof. [Matus Telgarsky](https://cims.nyu.edu/~matus/) and Prof. [Pavel Izmailov](https://izmailovpavel.github.io/). Previously, I earned my dual master degree from Tsinghua University and Columbia University. Prior to this, I completed my Bachelor's degree at Wuhan University, majoring in Statistics. 

I am broadly interested in machine learning and statistics. My current research studies when and why RL-based post-training improves reasoning in large language models. In particular, I am interested in:

- Understanding how reasoning capabilities emerge from pretraining to post-training
- Scalable verification and RL environments
- Continual self-improvement

I am also fortunate to work with many great scholars and mentors, and I’m deeply grateful for their guidance.

<!-- <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- # 🗞 News
<div class="scroll-box scroll-box--news" markdown="1">
- *2026.05*: &nbsp;🏅 Selected as an **ICML 2026 Gold Reviewer**.
- *2025.11*: &nbsp;🎉 [MiCRo](https://arxiv.org/pdf/2505.24846) received the **EMNLP 2025 Outstanding Paper Award**!
</div> -->

# 🔬 Publications
(<sup>†</sup>: equal contribution)

<div class="pub-tabs" role="tablist" aria-label="Publication view">
  <button role="tab" id="tab-selected" aria-controls="panel-selected" aria-selected="true">Selected</button>
  <button role="tab" id="tab-all" aria-controls="panel-all" aria-selected="false">All</button>
</div>

<div class="pub-panel" id="panel-selected" role="tabpanel" aria-labelledby="tab-selected" markdown="1">

<div class='paper-box'>
<div class='paper-box-image'><div><img src='images/papers/understanding-reasoning.png' alt="Understanding Reasoning from Pretraining to Post-Training" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Understanding Reasoning from Pretraining to Post-Training**  
**Jingyan Shen**<sup>†</sup>, [Ang Li](https://leonlixyz.github.io/)<sup>†</sup>, [Salman Rahman](https://salmanrahman.net/), [Yifan Sun](https://yifansun99.github.io/), [Micah Goldblum](https://goldblum.github.io/), [Matus Telgarsky](https://cims.nyu.edu/~matus/), [Pavel Izmailov](https://izmailovpavel.github.io/)  
<span style="color:blue;">NeurIPS</span> 2026 \[[Paper](https://arxiv.org/abs/2607.16097)\] \[[Code](https://github.com/pavelslab-nyu/pre2post-chess)\]

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><img src='images/papers/micro.png' alt="MiCRo" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MiCRo: Mixture Modeling and Context-aware Routing for Personalized Preference Learning**  
**Jingyan Shen**<sup>†</sup>, [Jiarui Yao](https://maxwelljryao.github.io/)<sup>†</sup>, [Rui Yang](https://yangrui2015.github.io/)<sup>†</sup>, [Yifan Sun](https://yifansun99.github.io/), Feng Luo, [Rui Pan](https://research4pan.github.io/), [Tong Zhang](https://tongzhang-ml.org/), [Han Zhao](https://hanzhaoml.github.io/)  
<span style="color:blue;">EMNLP</span> 2025 (Main) <span style="color:red;">Outstanding Paper Award 🏆</span> \[[Paper](https://arxiv.org/pdf/2505.24846)\]

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><img src='images/papers/data-efficiency-rft.png' alt="Difficulty-targeted Online Data Selection and Rollout Replay" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay**  
[Yifan Sun](https://yifansun99.github.io/)<sup>†</sup>, **Jingyan Shen**<sup>†</sup>, [Yibin Wang](https://yibinwang.netlify.app/)<sup>†</sup>, [Tianyu Chen](https://tianyucodings.github.io/), [Zhendong Wang](https://zhendong-wang.github.io/), [Mingyuan Zhou](https://mingyuanzhou.github.io/), [Huan Zhang](https://www.huan-zhang.com/)  
<span style="color:blue;">NeurIPS</span> 2025 \[[Paper](https://arxiv.org/pdf/2506.05316)\]

</div>
</div>

</div>

<div class="pub-panel" id="panel-all" role="tabpanel" aria-labelledby="tab-all" hidden>
<h3 class="pc-year">2026</h3>
<ul class="pc-list">
  <li class="pc">
    <span class="pc-venue">NeurIPS 2026</span>
    <div>
      <a class="pc-title" href="https://arxiv.org/abs/2607.16097">Understanding Reasoning from Pretraining to Post-Training</a>
      <span class="pc-authors"><b>Jingyan Shen</b><sup>†</sup>, Ang Li<sup>†</sup>, Salman Rahman, Yifan Sun, Micah Goldblum, Matus Telgarsky, Pavel Izmailov</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">NeurIPS 2026<span class="pc-track">Evaluations and Datasets Track</span></span>
    <div>
      <span class="pc-title">Your Benchmark Is an Empirical Measure Over Difficulty</span>
      <span class="pc-authors">Yifan Sun<sup>†</sup>, Naicheng Yu<sup>†</sup>, Jiawen Gong<sup>†</sup>, <b>Jingyan Shen</b>, Huan Zhang</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">NeurIPS 2026</span>
    <div>
      <a class="pc-title" href="https://arxiv.org/pdf/2512.17901">When Reasoning Meets Its Laws</a>
      <span class="pc-authors">Junyu Zhang<sup>†</sup>, Yifan Sun<sup>†</sup>, Tianang Leng<sup>†</sup>, <b>Jingyan Shen</b><sup>†</sup>, Ziyin Liu, Paul Pu Liang, Huan Zhang</span>
      <span class="pc-note">Efficient Reasoning Workshop at NeurIPS 2025 · Oral, Best Paper Nomination</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">ICML 2026</span>
    <div>
      <a class="pc-title" href="https://arxiv.org/abs/2606.00320">Adversarially Robust Control of Conditional Value-at-Risk via Rockafellar-Uryasev Conformal Inference</a>
      <span class="pc-authors">Catherine Chen, <b>Jingyan Shen</b>, Zhun Deng, Lihua Lei</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">MATH-AI @ NeurIPS 2026</span>
    <div>
      <span class="pc-title">Training Natural-Language Proof Verifiers with Lean-Grounded Synthetic Data</span>
      <span class="pc-authors">Rodney Lafuente-Mercado, Salman Rahman, <b>Jingyan Shen</b>, James Shiffer, Saadia Gabriel, Pavel Izmailov</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">Preprint</span>
    <div>
      <a class="pc-title" href="https://arxiv.org/abs/2604.18574">When Can LLMs Learn to Reason with Weak Supervision?</a>
      <span class="pc-authors">Salman Rahman<sup>†</sup>, <b>Jingyan Shen</b><sup>†</sup>, Anna Mordvina, Hamid Palangi, Saadia Gabriel, Pavel Izmailov</span>
    </div>
  </li>
</ul>
<h3 class="pc-year">2025</h3>
<ul class="pc-list">
  <li class="pc">
    <span class="pc-venue">EMNLP 2025</span>
    <div>
      <a class="pc-title" href="https://arxiv.org/pdf/2505.24846">MiCRo: Mixture Modeling and Context-aware Routing for Personalized Preference Learning</a>
      <span class="pc-authors"><b>Jingyan Shen</b><sup>†</sup>, Jiarui Yao<sup>†</sup>, Rui Yang<sup>†</sup>, Yifan Sun, Feng Luo, Rui Pan, Tong Zhang, Han Zhao</span>
      <span class="pc-note">Outstanding Paper Award 🏆</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">NeurIPS 2025</span>
    <div>
      <a class="pc-title" href="https://arxiv.org/pdf/2506.05316">Improving Data Efficiency for LLM Reinforcement Fine-tuning Through Difficulty-targeted Online Data Selection and Rollout Replay</a>
      <span class="pc-authors">Yifan Sun<sup>†</sup>, <b>Jingyan Shen</b><sup>†</sup>, Yibin Wang<sup>†</sup>, Tianyu Chen, Zhendong Wang, Mingyuan Zhou, Huan Zhang</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">ICML 2025</span>
    <div>
      <span class="pc-title">Conformal Tail Risk Control for Large Language Model Alignment</span>
      <span class="pc-authors">Catherine Chen, <b>Jingyan Shen</b>, Zhun Deng, Lihua Lei</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">ICLR 2025</span>
    <div>
      <span class="pc-title">TimeInf: Time Series Data Contribution via Influence Functions</span>
      <span class="pc-authors">Yizi Zhang<sup>†</sup>, <b>Jingyan Shen</b><sup>†</sup>, Xiaoxue Xiong<sup>†</sup>, Yongchan Kwon</span>
    </div>
  </li>
  <li class="pc">
    <span class="pc-venue">ACL 2025 Findings</span>
    <div>
      <span class="pc-title">Rethinking Diverse Human Preference Learning through Principal Component Analysis</span>
      <span class="pc-authors">Feng Luo<sup>†</sup>, Rui Yang<sup>†</sup>, Hao Sun, Chunyuan Deng, Jiarui Yao, <b>Jingyan Shen</b>, Huan Zhang, Hanjie Chen</span>
    </div>
  </li>
</ul>
<h3 class="pc-year">2024</h3>
<ul class="pc-list">
  <li class="pc">
    <span class="pc-venue">NeurIPS 2024</span>
    <div>
      <span class="pc-title">2D-OOB: Attributing Data Contribution through Joint Valuation Framework</span>
      <span class="pc-authors">Yifan Sun<sup>†</sup>, <b>Jingyan Shen</b><sup>†</sup>, Yongchan Kwon</span>
    </div>
  </li>
</ul>
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

# 🔬 Preprints & Workshops

<div class='paper-box'>
<div class='paper-box-image'><div><img src='images/papers/leanprm.png' alt="Training Natural-Language Proof Verifiers with Lean-Grounded Synthetic Data" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Training Natural-Language Proof Verifiers with Lean-Grounded Synthetic Data**  
Rodney Lafuente-Mercado, [Salman Rahman](https://salmanrahman.net/), **Jingyan Shen**, James Shiffer, [Saadia Gabriel](https://saadiagabriel.com/), [Pavel Izmailov](https://izmailovpavel.github.io/)  
<span style="color:blue;">MATH-AI Workshop at NeurIPS 2026</span>

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><img src='images/papers/weak-supervision.png' alt="When Can LLMs Learn to Reason with Weak Supervision?" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**When Can LLMs Learn to Reason with Weak Supervision?**  
[Salman Rahman](https://salmanrahman.net/)<sup>†</sup>, **Jingyan Shen**<sup>†</sup>, Anna Mordvina, [Hamid Palangi](https://www.hamidpalangi.com/), [Saadia Gabriel](https://saadiagabriel.com/), [Pavel Izmailov](https://izmailovpavel.github.io/)  
Preprint. \[[Paper](https://arxiv.org/abs/2604.18574)\] \[[Project Page](https://salmanrahman.net/rlvr-weak-supervision)\]

</div>
</div>

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
- *2026.05 - 2026.08*, Research Intern at Microsoft Research (NYC)
  - I was very fortunate to work with [Stephanie Milani](https://stephmilani.github.io/), [Akshay Krishnamurthy](https://www.microsoft.com/en-us/research/people/akshaykr/), and [Jordan T. Ash](https://www.jordantash.com/).
- *2024.02 - 2025.06*, Full-time machine learning engineer at Pinterest

# 🐰 Miscs
I value the diversity and richness of life, and I hold a deep respect for beauty and purity in all their forms. Beyond research, I enjoy playing table tennis and tennis, losing myself in a good book, or discovering new places through travel.

I also love music and singing, and I'd love to keep learning the drums whenever I find the time! 🥁