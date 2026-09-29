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

I am a Ph.D. student at Central South University. My research approaches a single question from two directions: **when a visual model is wrong, how would we know?**

During my master's I worked on **palm-vein recognition**, a contactless biometric modality whose images are low-contrast and easily degraded by illumination and occlusion. I designed wavelet-based and neural-architecture-search-based networks for discriminative vein feature extraction, and a multiscale memory GAN that purifies adversarial samples before they reach the classifier. This work appeared in IEEE TIFS (2025, 2026) and IEEE TCYB (2026), and I am a co-first author on both TIFS papers. I also contributed to self-supervised Parkinson's disease detection from handwriting dynamics.

I am now working on **situated instructional video generation** for laboratory procedures. My first doctoral project, [LabInstruct](https://csu-jpg.github.io/LabInstruct.github.io/), asks whether image-to-video models can communicate real experimental procedures: 204 tasks across 5 scientific disciplines, each anchored to a real reference execution and annotated with objects, actions, contacts, and state transitions. Evaluating eight frontier models shows that visually plausible generations are frequently *procedurally* incorrect — a gap that matters because these videos are meant to be acted on, not merely watched.

My research interests include video generation and evaluation, multimodal benchmarks, biometric recognition, and adversarial robustness. I am always glad to hear from people working on related problems.

My publication record is on <a href='https://scholar.google.com/citations?user=cJk7eIUAAAAJ'>Google Scholar</a> — total citations <strong><span id='total_cit'>—</span></strong>.

# 🔥 News
- *2026.09*: &nbsp;Started my Ph.D. at Central South University.
- *2026.05*: &nbsp;"MsMemoryGAN: A Multiscale Memory GAN for Palm-Vein Adversarial Purification" published in IEEE Transactions on Cybernetics.
- *2026*: &nbsp;"Neural Architecture Search-Based Global–Local Vision Mamba for Palm-Vein Recognition" published in IEEE Transactions on Information Forensics and Security.
- *2025.10*: &nbsp;Awarded the National Scholarship for Graduate Students.
- *2025*: &nbsp;"WTxGRN: Wavelet Transform-Based Extended Gated Recurrent Network for Palm Vein Recognition" published in IEEE Transactions on Information Forensics and Security.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2026</div><img src='images/labinstruct.jpg' alt="LabInstruct benchmark overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LabInstruct: Benchmarking Situated Instructional Video Generation for Lab Procedures](https://csu-jpg.github.io/LabInstruct.github.io/)

**Yuming Fu**, Weijia Wu, Jing Chen, Jiahao Tang, Feifei Chen, Hongyu Zhu, Xin Jin, Alex Jinpeng Wang

[**Project Page**](https://csu-jpg.github.io/LabInstruct.github.io/)

- The first benchmark for situated instructional video generation in real laboratories: 204 tasks across 5 scientific disciplines, with real reference executions and structured annotations of objects, actions, contacts, and state transitions.
- Evaluating 8 frontier image-to-video models shows that visually plausible generations frequently remain procedurally incorrect, exposing a gap between visual realism and the reliability required for experimental instruction.
</div>
</div>

- [WTxGRN: Wavelet Transform-Based Extended Gated Recurrent Network for Palm Vein Recognition](https://doi.org/10.1109/TIFS.2025.3592561), H. Qin\*, **Yuming Fu**\*, J. Chen, Q. Song, Y. Li, M. A. El-Yacoubi, D. Zhong, **IEEE TIFS 2025**
- [Neural Architecture Search-Based Global–Local Vision Mamba for Palm-Vein Recognition](https://doi.org/10.1109/TIFS.2026.3679936), H. Qin\*, **Yuming Fu**\*, J. Chen, M. A. El-Yacoubi, X. Gao, F. Xi, **IEEE TIFS 2026**
- [MsMemoryGAN: A Multiscale Memory GAN for Palm-Vein Adversarial Purification](https://doi.org/10.1109/TCYB.2026.3668829), H. Qin, **Yuming Fu**, H. Zhang, M. A. El-Yacoubi, X. Gao, Q. Song, J. Wang, **IEEE TCYB 2026**
- WTGMT: A Wavelet-Enhanced Group Memory-augmented Transformer for Self-supervised Parkinson's Disease Detection from Handwriting, Q. Song, J. Chen, **Yuming Fu**, et al., **Neural Networks** (under review)

<small>\* Equal contribution.</small>

# 🎖 Honors and Awards
- *2025.10* National Scholarship for Graduate Students, Ministry of Education of China.
- *2024.12* National Silver Award, the 14th "Challenge Cup" Qinchuangyuan China College Students' Entrepreneurship Competition.
- *2025.10* First-Class Graduate Academic Scholarship, Chongqing Technology and Business University.
- *2024.11* Second-Class Graduate Academic Scholarship, Chongqing Technology and Business University.
- *2023.11* Third-Class Graduate Academic Scholarship, Chongqing Technology and Business University.
- *2024 - 2025* Principal Investigator, Chongqing Graduate Student Research Innovation Project, "Robust Vein Recognition System Based on Deep Adversarial Defense" (completed).

# 📜 Patents
- **A Palm-Vein Image Anti-Spoofing Method Based on Multi-Scale Memory-Enhanced Generative Adversarial Networks**, Chinese Invention Patent, Application No. 2024108644551 (preliminary examination passed).
- **A Transformer-Based Memory Autoencoder Anomaly Detection Algorithm**, Chinese Invention Patent, Application No. 2024109661268 (preliminary examination passed).

# 📖 Educations
- *2026.09 - now*, Ph.D. student, Central South University, Changsha, China.
- *2023.09 - 2026.06*, M.S. in Electronic Information, Chongqing Technology and Business University, Chongqing, China.
- *2018.09 - 2022.06*, B.Eng. in Internet of Things Engineering, Zhejiang University of Technology, Hangzhou, China.
