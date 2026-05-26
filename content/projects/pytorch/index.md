---
title: ML-Based Pathogen Surveillance
date: 2024-05-01
summary: Machine learning pipeline for pathogen detection and antimicrobial resistance prediction from whole-genome sequencing data in livestock.
links:
  - type: code
    url: https://github.com/RushiLagad
tags:
  - Machine Learning
  - Genomics
  - AMR
  - Python
  - Random Forest
---

## ML-Based Pathogen Surveillance

A machine learning pipeline for pathogen detection and antimicrobial resistance (AMR) gene prediction from whole-genome sequencing (WGS) data. This pipeline processes raw sequencing reads through quality control, assembly, and annotation, then applies ensemble ML models to predict AMR profiles and virulence factors.

### Methods
- Random Forest and XGBoost classifiers for AMR gene prediction
- Elastic Net regularization for feature selection across thousands of genomic loci
- K-mer based feature extraction from assembled contigs
- Integration with CARD and VFDB databases

### Performance
Achieves >90% accuracy in predicting resistance phenotypes from genotype data, enabling rapid surveillance without culture-based testing.
