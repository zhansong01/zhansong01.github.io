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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DAC 2025</div><img src='images/DAC_62_Square.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BoolE: Exact Symbolic Reasoning via Boolean Equality Saturation](https://scholar.google.com/citations?user=DdVCoawAAAAJ)

**Jiaqi Yin\***, **Zhan Song\*** (co-first), Chen Chen, Qihao Hu, Cunxi Yu

**Best Paper Nomination**

- Introducing a novel approach for symbolic reasoning using Boolean Equality Saturation
</div>
</div>

- [HEC: Equivalence Verification Checking for Code Transformation via Equality Saturation](https://scholar.google.com/citations?user=DdVCoawAAAAJ), Jiaqi Yin, **Zhan Song**, Nicolas Bohm Agostini, Antonino Tumeo, Cunxi Yu, **USENIX ATC 2025**

- [e-boost: Boosted E-Graph Extraction with Adaptive Heuristics and Exact Solving](https://scholar.google.com/citations?user=DdVCoawAAAAJ), Jiaqi Yin, **Zhan Song**, Chen Chen, Yaohui Cai, Zhiru Zhang, Cunxi Yu, **ICCAD 2025** [Under Review]

- [Noise-Aware Circuit Clustering based on Analytical Placement Evolution](https://scholar.google.com/citations?user=DdVCoawAAAAJ), Zhiyuan Chen, Chung-Kuan Cheng, **Zhan Song** (corresponding), Yucheng Wang, **SLIP 2024**

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
- [BoolE](https://github.com/Yu-Maryland/BoolE): Exact Symbolic Reasoning via Boolean Equality Saturation
- [Noise-Aware Circuit Clustering](https://github.com/Hikipeko/noise-aware-circuit-clustering): Noise-Aware Circuit Clustering based on Analytical Placement Evolution
