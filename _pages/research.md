---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research combines computational neuroimaging, graph machine learning, and reproducible data engineering to study brain aging and dementia risk.

Predicting Dementia Conversion
======

I am developing a micro-structural and macro-topological MRI framework for predicting conversion from mild cognitive impairment to dementia. The project uses graph neural networks, including GCN, GAT, and GraphSAGE models, with transfer learning across cohorts.

The modeling strategy pretrains on the public ADNI cohort and fine-tunes on the local ILAS cohort to address cross-site domain shift. Model interpretation methods such as GNNExplainer are used to connect predictions back to brain regions and graph features.

Morphological Similarity Networks
======

I build subject-level morphological similarity networks from multimodal MRI features across 100+ brain regions. These graphs support topological analysis, including global efficiency, modularity, small-worldness, and related network metrics.

Large-Scale MRI Pipelines
======

I develop Python and Nipype workflows for multimodal MRI processing, quality control, registration, feature extraction, and statistical modeling. These pipelines have processed more than 500 subjects and approximately 3 TB of imaging data on HPC systems.

Diffusion MRI and White Matter Microstructure
======

My earlier work used diffusion MRI and fixel-based analysis to study white matter alterations in Parkinson's disease, stroke, depression, environmental exposure, and aging-related cohorts.
