---
title: Rumen Metatranscriptomics Pipeline
date: 2023-11-01
summary: End-to-end pipeline for rumen metatranscriptomic analysis using HUMAnN3, MetaPhlAn, and DESeq2 for differential pathway abundance testing.
links:
  - type: code
    url: https://github.com/RushiLagad
tags:
  - Metatranscriptomics
  - Bioinformatics
  - R
  - HUMAnN3
  - Microbiome
---

## Rumen Metatranscriptomics Pipeline

An end-to-end bioinformatics pipeline for analyzing rumen metatranscriptomic data from livestock. This pipeline integrates quality control, taxonomic profiling, functional annotation, and differential abundance testing to characterize active microbial communities and their metabolic functions.

### Pipeline Steps
1. Quality control with Trimmomatic and FastQC
2. Host read removal via Bowtie2
3. Taxonomic profiling with MetaPhlAn4
4. Functional profiling with HUMAnN3
5. Differential pathway analysis with DESeq2 and ALDEx2
6. Visualization with R (ggplot2, phyloseq)

### Applications
Used to characterize active microbial metabolism in dairy and beef cattle rumen, identifying pathways associated with feed efficiency and methane production.
