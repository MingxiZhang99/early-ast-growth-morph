# Early Antibiotic Susceptibility Classification

This repository contains the analysis pipeline and notebooks for early classification of antibiotic susceptibility
from time-lapse microscopy using growth-rate dynamics and morphological features.

---

## Overview

The pipeline:
- Computes growth-rate time series from segmentation masks
- Extracts early area and morphological features
- Detects and down-weights out-of-focus frames
- Trains classifiers to distinguish REF vs RIF10
- Generates interpretable outputs (growth curves, PCA, Mahalanobis deviation, ROC/PR curves)

---

## Files

| File | Description |
|------|-------------|
| `early-ast-analysis.ipynb` | Main analysis notebook |
| `pipeline.py` | Reproducible pipeline implementation |
| `requirements.txt` | Python dependencies |
| `README.md` | This file |

---

## Setup

```bash
pip install -r requirements.txt
