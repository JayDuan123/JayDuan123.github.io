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

Hi, I am **Jay Yixuan Duan**.

I am a junior student at the **University of Wisconsin-Madison**. I am working with Professor [Wei Qiu](https://profiles.rice.edu/faculty/wei-qiu), [Lei Hou](https://scholar.google.com/citations?user=gwHifcYAAAAJ&hl=en), and [Hanwen Xu](https://scholar.google.com/citations?user=HwO7L5sAAAAJ&hl=zh-CN). Before that, I worked with Dr. [Chao Wang](https://szbl.ac.cn/research/groups/Chao-Wang.htm). My work focuses on biomedical foundation models, interpretable AI, multi-omics integration, and AI for precision health. I am going to apply for 27 Fall PHD in Computer Science, Computational Biology and Bioinformatics.

<span class='anchor' id='-edu'></span>

# 🎓 Education

<img class="svg" src="/images/uw-madison-logo.png" width="45pt"> <span style="color: #c5050c;">**University of Wisconsin-Madison**</span>
<br>
- *Expected to Graduate in May 2027*, Bachelor of Science in Computer Science
- GPA: 3.88 / 4.0
- Relevant Coursework: Data Structures and Algorithms, Deep Learning, Artificial Intelligence, Big Data Systems, Human Computer Interaction, Advanced Natural Language Processing, Molecules to Life and Science
<span class='anchor' id='-research'></span>

# 🚀 Research Interests

- Biological Foundation Model
- AI for Precision Health
- Interpretable AI
- Multi-omics Integration

<span class='anchor' id='-pub'></span>

# 📖 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2027</div><img src='/images/ecg-interpbench.png' alt="ECG-InterpBench overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**ECG-InterpBench: Benchmarking the Interpretability of ECG Foundation Models with Matched-Scale Sparse Autoencoders**

`Yixuan Duan`, Wei Qiu

Submitting to KDD 2027.

- Proposed a capacity-controlled benchmark that compares representation-level interpretability across six frozen ECG foundation models under a matched sparse-autoencoder protocol.
- Built a 450-cell matched-scale interpretability atlas over five encoder depths, five dictionary widths, and three seeds, with leakage-controlled metrics for sparse reconstruction fidelity, single-feature clinical concept accessibility and coverage (49 ECG measurements), and cross-seed reproducibility.
- Provided robust comparisons using patient- and design-level uncertainty, sparsity sensitivity, and an external MIMIC-IV-ECG replication.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2026</div><img src='/images/cadence.png' alt="CADENCE pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**CADENCE: A Cardiac Atom Dictionary for Interpretable Neural Concept Extraction from ECG Foundation Models**

`Yixuan Duan`, Arjun Naik, Sadeer Al-Kindi, Wei Qiu

arXiv preprint, 2026. [[arXiv]](https://arxiv.org/abs/2607.25244)

- Built a dictionary of interpretable "cardiac atoms" to decompose the internal representations of ECG foundation models.
- Extracted human-understandable neural concepts from learned features and linked them to clinically meaningful cardiac patterns.
- Enabled interpretable analysis and concept-level probing of ECG foundation model representations.
</div>
</div>

<span class='anchor' id='-experience'></span>

# 💻 Research Experience

<img class="svg" src="/images/rice.png" width="45pt"> <span style="color: #00205b;">**Rice University**</span>
<br>
*Feb. 2026 - Present*, Advisor: Professor Wei Qiu
<br>
ECG Foundation Models · Sparse Autoencoders · Interpretability

<img class="svg" src="/images/logo-bu.svg" width="75pt"> <span style="color: #cc0000;">**Boston University**</span>
<br>
*Jan. 2026 - Present*, Advisor: Professor Lei Hou
<br>
Multi-omics Integration · scATAC-seq · DNA Methylation

<img class="svg" src="/images/szbl.png" width="85pt"> <span style="color: #1765ad;">**Shenzhen Bay Laboratory**</span>
<br>
*Jun. 2025 - Aug. 2025*, Advisor: Dr. Chao Wang
<br>
Glycan–Protein Binding · Molecular Modeling

<span class='anchor' id='-skills'></span>

# 💪 Skills

- Linux, Python, R, Java, SQL
- ECG and PPG analysis, RNA-seq, scRNA-seq, scATAC-seq, DNA methylation

<span class='anchor' id='-award'></span>

# 🏆 Awards

- 2026 UW-Madison Dean's List
- 2026 UW-Madison Undergraduate Summer Award
