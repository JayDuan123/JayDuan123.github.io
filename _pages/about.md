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

I am a junior student at the **University of Wisconsin-Madison**. I am working with Professor [Wei Qiu](https://profiles.rice.edu/faculty/wei-qiu) and [Lei Hou](https://scholar.google.com/citations?user=gwHifcYAAAAJ&hl=en). Before that, I worked with Dr. [Chao Wang](https://szbl.ac.cn/research/groups/Chao-Wang.htm). My work focuses on biomedical foundation models, interpretable AI, multi-omics integration, and AI for precision health. I am going to apply for 27 Fall PHD in Computer Science, Computational Biology and Bioinformatics.

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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2027</div><img src='/images/interecgfm-pipeline.png' alt="InterECGFM pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**InterECGFM: What ECG Foundation Model will learn?**

`Yixuan Duan`, Sadeer Al-Kindi, Wei Qiu

Submitting to KDD 2027.

- Investigated what ECG foundation models learn from large-scale ECG data.
- Decomposed hidden representations with sparse autoencoders to identify interpretable ECG concepts.
- Connected learned features to disease discovery, concept control, downstream prediction, and LLM-assisted feature annotation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2026</div><img src='/images/csfm.png' alt="Cardiac SAE pipeline" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Discovering Interpretable Features in Cardiac Multi-Modality Foundation Models via Sparse Autoencoders**

`Yixuan Duan`, Wei Qiu

Manuscript in preparation, 2026.

- Encoded raw ECG and PPG biomedical signals into hidden activations and embeddings using pretrained foundation models.
- Applied sparse autoencoders to decompose internal representations into sparse and interpretable latent features.
- Analyzed top-activating samples and linked SAE features to waveform patterns, clinical reports, ICD phenotypes, and disease-related concepts.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2026</div><img src='/images/bench.png' alt="InterBench benchmark overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**InterBench: An Interpretable Benchmark for Cardiopulmonary Foundation Models**

`Yixuan Duan`, Wei Qiu

Manuscript in preparation, 2026.

- Designed an interpretable benchmark for evaluating cardiopulmonary foundation models.
- Organized ECG, PPG, and related biomedical tasks around clinically meaningful concepts and phenotypes.
- Evaluated model representations with a focus on interpretability, downstream prediction, and concept-level analysis.
</div>
</div>

<span class='anchor' id='-experience'></span>

# 💻 Research Experience

<img class="svg" src="/images/rice.png" width="45pt"> <span style="color: #00205b;">**Rice University**</span>
<br>
**Discovering interpretable features in foundation models via sparse autoencoders**
<br>
*Apr. 2026 - Present*, Advisor: Professor Wei Qiu, Department of Electrical and Computer Engineering, Rice University

<img class="svg" src="/images/rice.png" width="45pt"> <span style="color: #00205b;">**Rice University**</span>
<br>
**Disentangling aging-related signals in foundation model representations**
<br>
*Feb. 2026 - Apr. 2026*, Advisor: Professor Wei Qiu, Department of Electrical and Computer Engineering, Rice University


<img class="svg" src="/images/logo-bu.svg" width="75pt"> <span style="color: #cc0000;">**Boston University**</span>
<br>
**Graph-based integration model of scATAC-seq and DNA methylation**
<br>
*Jan. 2026 - Present*, Advisor: Professor Lei Hou, Department of Medicine, Biomedical Genetics Section, Boston University
<br>
<img class="svg" src="/images/szbl.png" width="85pt"> <span style="color: #1765ad;">**Shenzhen Bay Laboratory**</span>
<br>
**Modeling glycan-protein binding strength**
<br>
*Jun. 2025 - Aug. 2025*, Advisor: Dr. Chao Wang, Institute of Systems and Physical Biology, Shenzhen Bay Laboratory
<span class='anchor' id='-skills'></span>

# 💪 Skills

- Linux, Python, R, Java, SQL
- ECG and PPG analysis, RNA-seq, scRNA-seq, scATAC-seq, DNA methylation

<span class='anchor' id='-award'></span>

# 🏆 Awards

- 2026 UW-Madison Dean's List
- 2026 UW-Madison Undergraduate Summer Award
