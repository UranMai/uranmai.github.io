---
layout: page
title: NeurIPS 2024 BELKA — Silver Medal
description: Molecular binding prediction for drug discovery (top 2%, Kaggle)
importance: 1
category: competitions
---

**Competition:** [Predict New Medicines with BELKA](https://www.kaggle.com/competitions/leash-BELKA) — NeurIPS 2024, Kaggle

**Result:** Silver Medal (top 2% of participants)

**Task:** Predict the binding affinity of small molecules to three protein targets relevant to drug discovery. The dataset contained ~100 million molecule-protein pairs described by SMILES strings.

**Approach:**
- Graph neural networks (GNN) on molecular graphs derived from SMILES
- Ensemble of GNN and gradient boosting models
- Feature engineering on molecular fingerprints (Morgan, ECFP)
- Cross-validation strategy to handle protein-target leakage

**Skills:** PyTorch, PyTorch Geometric, RDKit, XGBoost, Python

{% include figure.liquid path="assets/img/projects_imgs/Kaggle_silver.png" alt="Silver Medal" %}