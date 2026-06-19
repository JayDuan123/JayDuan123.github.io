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

I am an undergraduate student at the **University of Wisconsin-Madison**. I am currently a Junior student. I am working with Professor [Wei Qiu](https://profiles.rice.edu/faculty/wei-qiu) and [Lei Hou](https://www.bumc.bu.edu/genetics/genetics-people/faculty/lei-hou-ph-d/). Before that, I worked with Dr. [Chao Wang](https://szbl.ac.cn/research/groups/Chao-Wang.htm). My work focuses on biomedical foundation models, interpretable AI, multi-omics integration, and AI for precision health.

<span class='anchor' id='-edu'></span>

# 🎓 Education

<img class="svg" src="/images/uw-madison-logo.png" width="140pt"> <span style="color: #c5050c;">**University of Wisconsin-Madison**</span>
<br>
- *Expected May 2027*, Bachelor of Science in Computer Science
- GPA: 3.83 / 4.0
- Relevant Coursework: Data Structures and Algorithms, Deep Learning, Artificial Intelligence, Molecules to Life and Science

<span class='anchor' id='-research'></span>

# Research Interests

- Biological Foundation Model
- AI for Precision Health
- Interpretable AI
- Multi-omics Integration
- Sparse Autoencoders for Biomedical Representation Analysis

<span class='anchor' id='-pub'></span>

# Publications

**Discovering Interpretable Features in Cardiac Multi-Modality Foundation Models via Sparse Autoencoders**
<br>
Yixuan Duan, Wei Qiu. Manuscript in preparation, 2026.

**InterBench: An Interpretable Benchmark for Cardiopulmonary Foundation Models**
<br>
Yixuan Duan, Wei Qiu. Manuscript in preparation, 2026.

<span class='anchor' id='-experience'></span>

# Research Experience

**Discovering interpretable features in foundation models via sparse autoencoders**
<br>
*Apr. 2026 - Present*, Advisor: Professor Wei Qiu, Department of Electrical and Computer Engineering, Rice University
- Encoded raw ECG and PPG biomedical signals into hidden activations and embeddings using pretrained foundation models.
- Applied sparse autoencoders to decompose internal representations into sparse and interpretable latent features.
- Analyzed top-activating samples and linked SAE features to waveform patterns, clinical reports, ICD phenotypes, and disease-related concepts.

**Disentangling aging-related signals in foundation model representations**
<br>
*Feb. 2026 - Apr. 2026*, Advisor: Professor Wei Qiu, Department of Electrical and Computer Engineering, Rice University
- Used bulk RNA-seq and scRNA-seq foundation model backbones as encoders.
- Designed an ACE-style disentanglement strategy to separate aging-related transcriptomic variation from tissue, sex, batch, and other background factors.
- Developed evaluation strategies for transcriptomic aging embeddings, epigenetic age prediction, age acceleration prediction, cross-tissue generalization, and biological interpretation of aging-related genes.

**Graph-based integration model of scATAC-seq and DNA methylation**
<br>
*Jan. 2026 - Present*, Advisor: Professor Lei Hou, Department of Medicine, Biomedical Genetics Section, Boston University
- Constructed a microglia multi-omics dataset from scATAC-seq and snm3C-seq data.
- Generated cell-by-peak and cell-by-CpG methylation matrices across 40 donors.
- Designed a TF-CRE-CpG graph framework to use DNA methylation embeddings for predicting differentially methylated CpGs and inferring dysregulated CRE modules and transcription factor regulatory programs.

**Modeling glycan-protein binding strength**
<br>
*Jun. 2025 - Aug. 2025*, Advisor: Dr. Chao Wang, Institute of Systems and Physical Biology, Shenzhen Bay Laboratory
- Constructed a queryable database for glycan-protein binding strengths and binding sites.
- Encoded structural and sequence information from glycans and proteins for deep learning model comparison.
- Trained models to predict glycan-protein binding strength and binding sites from molecular structure and sequence information.

<span class='anchor' id='-skills'></span>

# Skills

- Linux, Python, R, Java, SQL
- ECG and PPG analysis, RNA-seq, scRNA-seq, scATAC-seq, DNA methylation

<span class='anchor' id='-award'></span>

# Awards

- 2026 UW-Madison Dean's List
- 2026 UW-Madison Undergraduate Summer Award
