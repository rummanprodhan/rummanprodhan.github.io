---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="display: flex; justify-content: flex-end;">
  <a href="https://rummanprodhan.github.io/files/CV_Rumman_Ahmed_Prodhan.pdf" class="btn btn-primary" download>Download CV (PDF)</a>
</div>

## Objective
Dedicated academic and researcher with expertise in **Artificial Intelligence**, **Machine Learning**, and **Signal Processing**, currently serving as a **Senior Lecturer** at Northern University Bangladesh. Passionate about advancing AI for healthcare and human behavior analysis through ethical, explainable, and collaborative research. Seeking to pursue a **Ph.D.** in Computer Science to contribute to high-impact interdisciplinary research in AI and federated systems.

## Work Experience
<style>
.xp{display:flex;gap:1em;margin:0 0 1.6em}
.xp-logo{flex:0 0 52px;height:52px;border-radius:50%;border:2px solid #e3e3e3;display:flex;align-items:center;justify-content:center;font-weight:700;font-size:.8em;color:#2a6f3e;background:#f6fbf7}
.xp-body{flex:1;min-width:0}
.xp-org{font-weight:700;margin:0}
.xp-meta{color:#777;font-size:.88em;margin:0 0 .6em}
.xp-roles{list-style:none;margin:0;padding:0}
.xp-roles li{position:relative;padding:0 0 1em 1.4em;margin:0}
.xp-roles li::before{content:"";position:absolute;left:3px;top:.45em;width:9px;height:9px;border-radius:50%;background:#aaa}
.xp-roles li:not(:last-child)::after{content:"";position:absolute;left:7px;top:1.35em;bottom:.15em;width:2px;background:#ddd}
.xp-role{font-weight:600;margin:0}
.xp-date{color:#777;font-size:.88em;margin:0}
.xp-desc{margin:.35em 0 0;font-size:.95em}
</style>

<div class="xp">
  <div class="xp-logo">NUB</div>
  <div class="xp-body">
    <p class="xp-org">Northern University Bangladesh</p>
    <p class="xp-meta">Full-time · Sep 2022 – Present · Dhaka, Bangladesh</p>
    <ul class="xp-roles">
      <li>
        <p class="xp-role">Senior Lecturer, Dept. of CSE</p>
        <p class="xp-date">Oct 2026 – Present</p>
      </li>
      <li>
        <p class="xp-role">Lecturer, Dept. of CSE</p>
        <p class="xp-date">Sep 2022 – Sep 2026</p>
        <p class="xp-desc">Taught BSc courses including Database Management Systems, Artificial Intelligence &amp; Expert Systems, Computer Architecture, Operating Systems, and Software Development. Supervised undergraduate theses on deep learning, image processing, and federated learning.</p>
      </li>
    </ul>
  </div>
</div>

* **Volunteer Assistant Researcher (Remote)**  
  Neuro-Analytics Lab, NJIT, USA — *Jul 2022 – Jun 2023*  
  Collaborated on EEG-based emotion recognition research, leading to a publication in **MDPI Sensors** as an equally contributing first author.

* **Intern (Research & Development)**  
  Bondstein Technologies Limited, Dhaka, Bangladesh — *Jan 2022 – Jun 2022*  
  Developed a **real-time conveyor belt fault detection system** for **British American Tobacco (BAT)** using computer vision and embedded AI.

* **SEO Team Lead (Part-time, Remote)**  
  Marketing Doorway, Dhaka, Bangladesh — *Jul 2017 – Sep 2022*  
  Led a team of SEO professionals to improve client visibility and optimize traffic analytics.

* **SEO Specialist (Part-time, Remote)**  
  Lead Technology, Dhaka, Bangladesh — *Jul 2016 – Jul 2017*

## Education
* **M.Sc. in Computer Science & Engineering**  
  BRAC University, Dhaka, Bangladesh — *Coursework Completed, Thesis Ongoing*  
  *CGPA: 3.95/4.00* — Awarded Merit Scholarship  
  Advanced coursework: Neural Networks & Fuzzy Systems, Distributed Computing, Deep Learning for Computer Vision, Symbolic Machine Learning, Pattern Recognition, Parallel Algorithms.  

* **B.Sc. in Computer Science & Engineering**  
  University of Asia Pacific, Dhaka, Bangladesh — *Apr 2018 – Jun 2022*  
  *Cumulative CGPA: 3.79/4.00*  
  *Last 2 Years: 3.96 | Final Semester: 4.00*  

## Publications
<ul>{% for post in site.publications reversed %}  
    {% include archive-single-cv.html %}  
  {% endfor %}</ul>

**Selected Publications:**
- *“M1M2: Deep Learning-Based Real-Time Emotion Recognition from Neural Activity”* — MDPI **Sensors**, 2022. [DOI](https://doi.org/10.3390/s22218467)  
- *“Emotion Recognition from Brain Wave using Multitask Machine Learning Leveraging Residual Connections”* — **MIET 2022**, Bangladesh. [DOI](https://doi.org/10.1007/978-3-031-34622-4_10)  
- *“Evaluating the Effectiveness of Classification Algorithms for EEG Sentiment Analysis”* — **ICSADL 2022**, Nepal. [DOI](https://doi.org/10.1007/978-981-19-5443-6_17)  
- *“Optimal EEG Electrode Set for Emotion Recognition From Brain Signals: An Empirical Quest”* — **ABC 2022**, London. [DOI](https://doi.org/10.1201/9781003371540-5)  
- *“Enhanced Pediatric Dental Segmentation Using a Custom SegUNet with VGG19 Backbone on Panoramic Radiographs”* — **ICCIT 2024**, Bangladesh. [DOI](https://doi.org/10.1109/ICCIT64611.2024.11021764)  
- *“Multimodal Deep Learning for Handwritten Prescription Recognition with Explainable AI”* — **2nd IEEE Quantum-inspired Patient Informatics (Q-PAIN), 2026** (IEEE Xplore). [DOI](https://doi.org/10.1109/QPAIN69676.2026.11546070)  

## Research Focus
* EEG-based emotion recognition and cross-subject generalization  
* Cross-domain federated learning for medical imaging  
* Deep learning for medical and dental image segmentation  
* Explainable AI for healthcare and decision support systems  

## MSc Research Projects
* **Unsupervised Acoustic Disentanglement via Hybrid Beta-VAE** — Fused convolutional spectral audio features with semantic embeddings to resolve cross-cultural genre overlaps; perfect separation (ARI = 1.0) on HBLM-100.
* **Scalable Hybrid Parallelism for Federated Learning** — MPI (inter-node) + CUDA (intra-node) architecture tackling the straggler problem; 9.26× speedup over serial execution on SipakMed.
* **Federated Domain Generalization (FedDG) for Cancer Diagnosis** — FedBN within the Flower framework to handle staining-protocol domain shift; 15% better cross-site robustness than FedAvg.
* **Zero-Shot Cross-Dataset EEG Emotion Recognition** — CORAL regularization and MixStyle to transfer models between DEAP and DREAMER without retraining.

## Projects
* **Cross-Device Skin Disease Classification using Federated Learning** — [Kaggle](https://www.kaggle.com/code/rummanahmedprodhan/cross-domain-federated-learning-skin-disease-poc)  
* **Zero-Shot Cross-Dataset EEG Emotion Recognition** — [Google Colab](https://colab.research.google.com/drive/1v0wxB2InMdmaL5hQtTIutek7pJDzEqAM?usp=sharing)  
* **Real-Time Emotion and Attendance System (Raspberry Pi)**  
* **Conveyor Belt Fault Detection for BAT (Raspberry Pi)**  
* **Bangladeshi Travel Blog using Django** — [Live Demo](http://rumman.pythonanywhere.com/)  
* **Air Tickets Management System (SQL)** — [GitHub](https://github.com/rumman153/Database/tree/master/Airport%20Ticket%20Management)  
* **Employee Management (Java)** — [GitHub](https://github.com/rumman153/Java/tree/)*
