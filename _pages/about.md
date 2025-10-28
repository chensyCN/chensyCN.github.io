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

# 🎓 About Me

I am a Postdoc with [Prof. Jiannong CAO](https://www4.comp.polyu.edu.hk/~csjcao/) (since 2024) at the Department of Computing, Hong Kong Polytechnic University. I earned my Ph.D. from the same department under the supervision of [Prof. Xiao HUANG](https://www4.comp.polyu.edu.hk/~xiaohuang/index.html) (2021–2024). Prior to that, I obtained my B.E. from [Fudan University](https://www.fudan.edu.cn/).

My research interests include **graph learning, reasoning**, and **Large Language Models**, with latest research presented at NeurIPS, ICML, TKDE, ACL, CIKM, etc.. Currently, I am working on **Graph-based Retrieval-Augmented Generation for LLMs (graphRAG).** 

# 🎉 News
- [*2025.10*] We release LinearRAG, a lightweight GraphRAG framework that eliminates LLM token cost during graph construction and retrieval -- making GraphRAG faster and more efficient than ever. [[Paper](https://arxiv.org/abs/2510.10114)\|[Code](https://github.com/DEEP-PolyU/LinearRAG)] [![](https://img.shields.io/github/stars/DEEP-PolyU/LinearRAG)](https://github.com/DEEP-PolyU/LinearRAG)
- [*2025.09*] Our work NeuSymEA is accepted to NeurIPS'25. [[Paper](https://arxiv.org/abs/2410.04153)\|[Code](https://github.com/chensyCN/NeuSymEA-NeurIPS25)]
- [*2025.07*] 🔥🔥🔥 Our NeurIPS'24 paper [LLM4EA](https://openreview.net/forum?id=qfCQ54ZTX1) ranks **#1st** in Google Scholar search results for "entity alignment" papers in the past two years (2024-2025)!
- [*2025.06*] Released a GraphRAG benchmark: [[Homepage](https://graphrag-bench.github.io/)\|[Paper](https://arxiv.org/abs/2506.05690)\|[Code](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)\|[Slides](https://docs.google.com/presentation/d/1q8K2RgsDYktkEIDp9Lqpb9WwBCBHT_L5/edit?slide=id.p1#slide=id.p1)] [![](https://img.shields.io/github/stars/GraphRAG-Bench/GraphRAG-Benchmark)](https://github.com/GraphRAG-Bench/GraphRAG-Benchmark)
- [2025.05] Two papers are accepted to [ACL'25 (main)](https://openreview.net/forum?id=WlEJovnbXc) and [ICML'25](https://openreview.net/forum?id=gT8JSEFqaS), respectively. Kudos to my amazing collaborators! 🎉
- [*2025.01*] Our survey on graphRAG is released! [[Paper](https://arxiv.org/abs/2501.13958)\|[Github awesome-list](https://github.com/DEEP-PolyU/Awesome-GraphRAG)] [![](https://img.shields.io/github/stars/DEEP-PolyU/Awesome-GraphRAG)](https://github.com/DEEP-PolyU/Awesome-GraphRAG)
- [*2024.12*] One paper accepted to TKDE.
- [*2024.09*] Our work LLM4EA is accepted to NeurIPS'24. [[Paper](https://openreview.net/forum?id=qfCQ54ZTX1)\|[Code](https://github.com/chensyCN/llm4ea_official)] [![](https://img.shields.io/github/stars/chensyCN/llm4ea_official)](https://github.com/chensyCN/llm4ea_official)


# 📔 Selected Publications ([Full List](https://scholar.google.com/citations?user=9Ro5HtwAAAAJ))
<span style="color: #006400">**[†]: Corresponding Author**</span>, <span style="color: #8B4513">**[‡]: Co-first Author**</span>

### Preprint:
- **[Arxiv'25]** Luyao Zhuang, <span style="color: #8B4513">**Shengyuan Chen‡**</span>, Yilin Xiao, Huachi Zhou, Yujing Zhang, Hao Chen, Qinggang Zhang, Xiao Huang, [LinearRAG: Linear Graph Retrieval Augmented Generation on Large-scale Corpora](https://arxiv.org/abs/2510.10114).
- **[Arxiv'25]** **Shengyuan Chen**, Chuang Zhou, Zheng Yuan, Qinggang Zhang, Zeyang Cui, Hao Chen, Yilin Xiao, Jiannong Cao, Xiao Huang, [You Don't Need Pre-built Graphs for RAG: Retrieval Augmented Generation with Adaptive Reasoning Structures](https://arxiv.org/abs/2508.06105).
- **[Arxiv'25]** Qinggang Zhang, <span style="color: #8B4513">**Shengyuan Chen‡**</span>, Yuanchen Bei, Zheng Yuan, Huachi Zhou, Zijin Hong, Junnan Dong, Hao Chen, Yi Chang, Xiao Huang, [A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models](https://arxiv.org/abs/2501.13958).



### Published:
- **[NeurIPS'25]** **Shengyuan Chen**, Zheng Yuan, Qinggang Zhang, Wen Hua, Jiannong Cao, Xiao Huang, [Neuro-symbolic Entity Alignment via Variational Inference](https://arxiv.org/abs/2410.04153).
- **[ACL'25]** Chuang Zhou, Zhu Wang, <span style="color: #006400">**Shengyuan Chen†**</span>, Jiahe Du, Qiyuan Zheng, Zhaozhuo Xu, Xiao Huang, [Taming Language Models for Text-attributed Graph Learning with Decoupled Aggregation](https://openreview.net/forum?id=WlEJovnbXc).
- **[ICML'25]** Qinggang Zhang, Hao Chen, Junnan Dong,  <span style="color: #006400">**Shengyuan Chen†**</span>, Feiran Huang, Xiao Huang, [Structure-Guided Large Language Models for Text-to-SQL Generation](https://openreview.net/forum?id=gT8JSEFqaS).
- **[NeurIPS'24]** **Shengyuan Chen**, Qinggang Zhang, Junnan Dong, Wen Hua, Qing Li, Xiao Huang, [Entity Alignment with Noisy Annotations from Large Language Models](https://openreview.net/forum?id=qfCQ54ZTX1).
- **[NeurIPS'23]** **Shengyuan Chen**, Yunfeng Cai, Huang Fang, Xiao Huang, Mingming Sun, [Differentiable Neuro-Symbolic Reasoning on Large-Scale Knowledge Graphs](https://openreview.net/forum?id=bETvUctiTR).
- **[ICML'23]** Zirui Liu, **Shengyuan Chen**, Kaixiong Zhou, Daochen Zha, Xiao Huang, Xia Hu, [RSC: Accelerating Graph Neural Networks Training via Randomized Sparse Computation](https://openreview.net/forum?id=GnsqiJwDzN).


# 🏆 Honors and Awards
- [*2025*] Postdoc Matching Fund ~ Two Years
- [*2023*] Departmental Top Conference Grant
- [*2022*] Winner of "Most Appreciated Teaching Assistant" (~$30,000HKD)
- [*2018*] Shanghai 'TI Cup' Undergraduate Electronic Design Contest ~ Second Price
- [*2018*] SCSK Corporation Scholarship
- [*2015-2018*] Fudan University Scholarship for Outstanding Students ~ Three Times
- [*2015-2017*] National Scholarship of Encouragement and Support ~ Twice

# 💼 Academic Service

- **Program Committee:** NeurIPS (2024-2025); ICML (2025); ICLR (2025-2026); AISTATS (2025-2026); AAAI (2026)

- **Reviewer:** TNNLS; TKDD; TNSE 

<!-- - **Teaching Assistant:** Big Data Analytics (2023 Spring/ 2022 Spring); Object-oriented Programming (2022 Fall); Discrete Mathematics (2021 Fall); Human Computer Interaction (2021 Spring); Computer Networking (2020 Spring); Information Systems (2019 Fall) -->