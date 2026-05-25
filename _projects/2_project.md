---
layout: page
title: CAFA 5 — Bronze Medal
description: Protein function prediction (Kaggle)
importance: 2
category: competitions
---

**Competition:** [CAFA 5 Protein Function Prediction](https://www.kaggle.com/competitions/cafa-5-protein-function-prediction) — Kaggle

**Result:** Bronze Medal

**Task:** Predict Gene Ontology (GO) terms for protein sequences — a large-scale, multi-label classification problem with ~140k proteins and ~31k GO terms across biological process, molecular function, and cellular component ontologies.

**Approach:**
- Protein language model embeddings (ESM-2) as sequence features
- Multi-label classification with threshold-tuned per-GO-term predictions
- Hierarchical GO structure incorporated via ancestor propagation

**Skills:** PyTorch, ESM-2, scikit-learn, Biopython, Python

{% include figure.liquid path="assets/img/projects_imgs/Kaggle_bronze.png" alt="Bronze Medal" %}