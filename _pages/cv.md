---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)](/files/Zehua_Zhang_CV.pdf){: .btn .btn--primary}

Education
======
* **Ph.D. in Computer Science**, Arizona State University, 2024 -- Present
  * Co-advised by Prof. Chitta Baral and Prof. Ruoyu Wang
  * Expected completion: Fall 2028
* **M.S. in AI Engineering -- Information Security**, Carnegie Mellon University, 2024
  * GPA: 3.7 / 4.0
  * Advised by Prof. Amir Barati Farimani and Prof. David Varodayan
* **B.A. in Computer Science and Economics**, Boston College, 2022
  * GPA: 3.65 / 4.0
  * Dean's List (First Honor): 2020--2022

Research Experience
======
* **Graduate Research Assistant**, Arizona State University (Aug 2024 -- Present)
  * Constructed benchmark dataset for evaluating agentic open-source software compilation methods
  * Designed a multi-agent compilation method enhanced with LLM-assisted retrieval, surpassing the strongest rule-based baseline by ~50%
  * Proposed a jailbreaking technique using layered novel ciphers, increasing success rates from 40% to 78%

* **Graduate Research Assistant**, Carnegie Mellon University (May 2023 -- May 2024)
  * Proposed a new masking pretraining method for Force and Energy-Centric Graph Neural Networks
  * Pretrained and finetuned GNNs on water molecule and organic molecule datasets, reducing RMSE by up to 38%

* **Research Assistant**, Peking University (May 2021 -- June 2021)
  * Evaluated blockchain protocols and smart contract codes
  * Constructed test nets to reproduce attacks targeting smart contracts
  * Analyzed the effect of regulations on cryptocurrency transactions using on-chain data

Professional Experience
======
* **Algorithm Development Intern**, Sohu Inc., Beijing (June 2021 -- Sept 2021)
  * Designed and deployed a real-time feed deduplication system for social media
  * Leveraged Kafka, Spark, simhash, and Bloom filters for large-scale data streaming
  * Reduced repetitive text exposure by ~90% and duplicate video content by ~30%

Technical Skills
======
* **Programming:** Python, C, Scala, Java, R, Swift, JavaScript
* **ML/DL Frameworks:** PyTorch, TensorFlow, PyG, Verl, vLLM
* **Data & Distributed Systems:** Spark, Kafka, Kubernetes
* **Databases:** MySQL, MongoDB, Hive, HBase
* **Cloud:** GCP, AWS

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
