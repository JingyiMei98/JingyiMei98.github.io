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

I am a PhD candidate at Leiden University working at the intersection of Formal Methods and Quantum Computing. My research develops SAT/\#SAT-based techniques for quantum program compilation and verification, including simulation, equivalence checking, model checking, and synthesis. I am broadly interested in strengthening quantum software tooling through automated reasoning and formal methods.

# ⭐ Research Interests

* Automated reasoning for quantum computing
* SAT / #SAT and weighted model counting
* Quantum circuit simulation, equivalence checking, and synthesis
* Model checking and verification of quantum systems

# 🔥 News
- *12/2025* 🎉 I was awarded the [Grzegorz Rozenberg Research Award](https://www.universiteitleiden.nl/en/science/computer-science/about-us/g.-rosenberg-research-award) in LIACS at Leiden University.



# 📝 Publications 

* Dekel Zak, **Jingyi Mei**, Jean-Marie Lagniez, and Alfons Laarman (2025). *Reducing Quantum Circuit Synthesis to #SAT*. In: **31st International Conference on Principles and Practice of Constraint Programming (CP 2025)**. LIPIcs 340, 38:1–38:21. Dagstuhl, Germany. doi: 10.4230/LIPIcs.CP.2025.38.  
  *We reduce quantum circuit synthesis to a #SAT problem.* 

* **Jingyi Mei**, Tim Coopmans, Marcello Bonsangue, and Alfons Laarman (2024). *Equivalence Checking of Quantum Circuits by Model Counting*. In: **International Joint Conference on Automated Reasoning (IJCAR 2024)**. Springer, pp. 401–421.  
  *We pioneer quantum circuit equivalence checking via #SAT using the Pauli basis.* 

* **Jingyi Mei**, Marcello Bonsangue, and Alfons Laarman (2024). *Simulating Quantum Circuits by Model Counting*. In: **Computer Aided Verification (CAV 2024)**. Springer, pp. 555–578.  
  *We introduce #SAT-based simulation using an extended stabilizer formalism.*

* **Jingyi Mei**, Jan Martens, and Alfons Laarman (2024). *Disentangling the Gap Between Quantum and #SAT*. In: **ICTAC 2024**. Springer, pp. 17–40.  
  *We reduce quantum circuit semantics to weighted model counting over various algebraic domains.* 

* Arend-Jan Quist, **Jingyi Mei**, Tim Coopmans, and Alfons Laarman (2024). *Advancing Quantum Computing with Formal Methods*. In: **International Symposium on Formal Methods (FM 2024)**. Springer, pp. 420–446.  
  *Tutorial-style introduction to quantum computing for the formal methods community.* 

* Jianling Fu, Cheng-Chao Huang, Yong Li, **Jingyi Mei**, Ming Xu, and Lijun Zhang (2023). *Quantitative Controller Synthesis for Consumption Markov Decision Processes*. In: **Information Processing Letters 180**, 106342.

* Ming Xu, Jianling Fu, **Jingyi Mei**, and Yuxin Deng (2022). *Model Checking QCTL+ on Quantum Markov Chains*. In: **Theoretical Computer Science 913**, pp. 43–72.

* Ming Xu, Jianling Fu, **Jingyi Mei**, and Yuxin Deng (2022). *An Algebraic Method to Fidelity-Based Model Checking over Quantum Markov Chains*. In: **Theoretical Computer Science 935**, pp. 61–81.

* Ming Xu, **Jingyi Mei**, Ji Guan, and Nengkun Yu (2021). *Model Checking Quantum Continuous-Time Markov Chains*. In: **CONCUR 2021**. LIPIcs 203, 13:1–13:17. 



# 📖 Educations

- *07/2023 - present* PhD in Computer Science, Leiden University, The Netherlands
Advisors: Alfons Laarman, Marcello Bonsangue

- *09/2020 – 06/2023* MSc in Software Engineering, East China Normal University, China
Thesis: Model-checking Linear-time Logic and Branching-time Logic on Quantum Continuous-time Markov Chains

- *10/2022 – 03/2023* Exchange Student, Saarland University, Germany
<!-- Visiting the Dependable Systems and Software group (Holger Hermanns) -->

- *09/2016 – 06/2020* BSc in Computer Science and Technology, East China Normal University, China
Thesis: Safety Analysis of Quantum Markov Chains

# 💬 Talks and Presentation
- *9/2025*, *Quantum Circuit Compilation with #SAT*, **Highlight 2025**, Saarbrücken, Germany.
- *6/2025*, *Quantum Circuit Compilation with #SAT*, **2nd Workshop on Quantum Software (WQS 2025)**, Seoul, Korea.
- *11/2024*, *Simulating Quantum Circuits with Weighted Model Counting*, **Kuldeep Meel Group Seminar**, online.
- *7/2024*, *Equivalence Checking of Quantum Circuits by Model Counting*, **IJCAR 2024**, Nancy, France.
- *6/2021*, *An Optimal Quantum Error-Correcting Procedure Using Quantifier Elimination*, **12th Computer Science and Mathematics Conference of the Chinese Mathematical Society**, Guilin, China.
- *8/2021*, *Model Checking Quantum Continuous-Time Markov Chains*, **CONCUR 2021**, Paris, France (online).


# Research Visit

- *9/2024* — Institute of Information Science, Academia Sinica.

- *10/2024* — Institute of Software, Chinese Academy of Sciences.

- *5/2024* — European Space Agency (ESA): Research visit.

- *10/2025* — Institute of Information Science, Academia Sinica

# 💻 Academic Service
- Member of Artifact Evaluation Committee:
- International Conference on Verification, Model Checking, and Abstract Interpretation (VMCAI 2026)
- ACM SIGPLAN Symposium on Principles of Programming Languages (POPL 2026)


<!-- 
# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Service -->


