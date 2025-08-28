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

# About Me

I am a first-year Computer Engineering Ph.D. student at the University of Maryland, College Park, advised by Prof. Cunxi Yu. My research interests include Logic Synthesis, Formal Verification, and AI/LLM for EDA. I welcome collaboration on any research projects in these areas - feel free to contact me at zhansong@umd.edu if you're interested in working together.

You can find my CV [here](/files/cv.pdf).

<span class='anchor' id='education'></span>

# 📖 Education
- *Aug. 2024 - present*, Ph.D. in Electrical and Computer Engineering, University of Maryland, College Park, USA
 
  Advisor: Prof. [Cunxi Yu](https://ycunxi.github.io/cunxiyu/)

- *Sep. 2023 - June 2024*, M.S. in Computer Science and Engineering (Artificial Intelligence), University of California, San Diego, USA

  Advisor: Prof. [Chung-Kuan Cheng](https://cseweb.ucsd.edu/~kuan/)

- *Sep. 2019 - June 2023*, B.S. in Computer Science and Technology, Fudan University, Shanghai, China

  Advisor: Prof. [Li Shang](https://cscw.fudan.edu.cn/lishang/list.htm)

<span class='anchor' id='research-interests'></span>

# 🔬 Research Interests
- Logic Synthesis
- Formal Verification
- AI/LLM for EDA

<span class='anchor' id='publications'></span>

# 📝 Publications

- [e-boost: Boosted E-Graph Extraction with Adaptive Heuristics and Exact Solving](https://arxiv.org/pdf/2508.13020), Jiaqi Yin, **Zhan Song**, Chen Chen, Yaohui Cai, Zhiru Zhang, Cunxi Yu, **ICCAD 2025**


- [BoolE: Exact Symbolic Reasoning via Boolean Equality Saturation](https://arxiv.org/pdf/2504.05577), **Jiaqi Yin\***, **Zhan Song\*** (co-first), Chen Chen, Qihao Hu, Cunxi Yu, **Best Paper Nomination**, **DAC 2025**


- [HEC: Equivalence Verification Checking for Code Transformation via Equality Saturation](https://arxiv.org/pdf/2506.02290), Jiaqi Yin, **Zhan Song**, Nicolas Bohm Agostini, Antonino Tumeo, Cunxi Yu, **USENIX ATC 2025**

- [Noise-Aware Circuit Clustering based on Analytical Placement Evolution](https://dl.acm.org/doi/pdf/10.1145/3708358.3709348), Zhiyuan Chen, Chung-Kuan Cheng, **Zhan Song** (corresponding), Yucheng Wang, **SLIP 2024**

<span class='anchor' id='awards-and-honors'></span>

# 🏆 Awards and Honors
- *June 2025* Best Paper Nomination, Design Automation Conference (DAC 2025)
- *Aug. 2022* Second Prize, Invent Week Landing Awards, eBay China Center of Excellence (CCOE) (Top 5%)
- *2020, 2022, 2023* Fudan University Scholarship

<span class='anchor' id='work-experience'></span>

# 💻 Work Experience
- *Jan. 2022 - Sep. 2022*, Software Engineer Intern, Payments & Risk Team, eBay, Shanghai, China

<span class='anchor' id='open-source-frameworks'></span>

# 🛠️ Open-Source Frameworks
- [e-boost](https://github.com/Yu-Maryland/e-boost): Boosted E-Graph Extraction with Adaptive Heuristics and Exact Solving
- [BoolE](https://github.com/Yu-Maryland/BoolE): Exact Symbolic Reasoning via Boolean Equality Saturation
- [Noise-Aware Circuit Clustering](https://github.com/Hikipeko/noise-aware-circuit-clustering): Noise-Aware Circuit Clustering based on Analytical Placement Evolution
