---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ site.baseurl }}/files/Shi-Ming-Wang-CV.pdf">Download PDF CV</a></p>

Education
======

* PhD in Computer Science, National Yang Ming Chiao Tung University, 2023 - present. Expected graduation: December 2026.
  * Dissertation: Micro-structural and Macro-topological MRI Framework for Predicting Conversion from MCI to Dementia using Graph Neural Networks and Morphological Similarity Networks.
  * Research areas: graph neural networks, transfer learning, cross-dataset generalization, model interpretability, and large-scale neuroimaging pipelines.
* MSc in Medical Imaging and Radiological Science, Chang Gung University, 2017 - 2019.
* BSc in Biomedical Imaging and Radiological Science, China Medical University, 2013 - 2017.

Work experience
======

* May 2020 - present: Brain and Cognitive Sciences Lab, National Yang Ming Chiao Tung University
  * Supervisors: Prof. Chih-Mao Huang and Prof. Liwei Chan.
  * Designed PyTorch-based graph neural network models for MCI-to-dementia conversion prediction.
  * Built multiparametric morphological similarity networks and graph-theoretic feature pipelines.
  * Developed reproducible MRI processing workflows for more than 500 subjects and approximately 3 TB of data.
* September 2020 - January 2022: Computational Imaging Group, UCL Centre for Medical Image Computing
  * Supervisors: Prof. Gary Hui Zhang and Prof. Marco Palombo.
  * Built longitudinal diffusion MRI analysis workflows for subacute and chronic stroke cohorts.
* August 2017 - August 2019: Laboratory of Magnetic Resonance Research, Chang Gung University
  * Supervisor: Prof. Jiun-Jie Wang.
  * Developed fixel-based analysis and deep learning approaches for Parkinson's disease neuroimaging.
* February 2018 - January 2019: Teaching Assistant, Chang Gung University.

Skills
======

* Programming: Python, C, C#, MATLAB.
* Machine learning: PyTorch, CUDA/GPU training, graph neural networks, CNNs, transfer learning, model interpretability.
* Neuroimaging: FSL, SPM, MRtrix, Nipype, DTI-TK, DTIstudio, NiftyReg.
* Data and statistics: NumPy, pandas, scikit-learn, XGBoost, R, SPSS.
* Information retrieval and NLP: DistilBERT, CodeBERT, TF-IDF, BM25, dense retrieval.
* Tools and infrastructure: Git, Linux/Unix, Bash, shell scripting, HPC batch processing.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Languages and Certificates
======
* English: TOEFL iBT 102, November 2022.
* Mandarin Chinese: Native.
* Certificate of Medical Radiation Technologist, Ministry of Health and Welfare, Taiwan, 2017.
* Certificate of Completion for Academic Research Ethics Education Courses, Taiwan, 2018.
