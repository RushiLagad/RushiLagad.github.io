---
title: Cassette2Vec-EC
date: 2026-10-30
summary: Reads the arrangement of genes inside genomic islands to separate pathogenic from commensal poultry-associated Enterococcus cecorum. Published in Frontiers in Microbiology (2026).
links:
  - type: code
    url: https://github.com/RushiLagad/Cassette2Vec
  - type: pdf
    url: https://doi.org/10.3389/fmicb.2026.1882753
    label: Paper
tags:
  - Microbial Genomics
  - Machine Learning
  - AMR
---

Most genome-based classifiers treat a genome as a bag of genes. Cassette2Vec-EC instead encodes the *local gene neighborhoods* (cassettes) anchored inside genomic islands, and asks whether that architecture carries signal about which *Enterococcus cecorum* lineages cause disease in poultry.

**What we found.** On 145 genomes, the model reached an AUROC of 0.918 under genome-grouped cross-validation, and 0.694 when whole studies were held out. The drop is the point: it shows where the signal holds and where it weakens when the model meets data from a study it has never seen.

**Paper.** Lagad RR, Rafi S, Goswami A. Genomic-island cassette architecture provides interpretable signal for exploratory classification of poultry-associated *Enterococcus cecorum* lineages. *Frontiers in Microbiology*. 2026;17:1882753. [doi:10.3389/fmicb.2026.1882753](https://doi.org/10.3389/fmicb.2026.1882753)

**Funding.** Arkansas Research Alliance Impact Grant Program (PI: A. Goswami), with additional support from Cobb-Vantress Genetics LLC.

**Coverage.** [University of Arkansas System Division of Agriculture](https://www.uaex.uada.edu/media-resources/news/2026/august/08-11-2026-ark-genomic-island-cassette-architecture.aspx), [Feedstuffs](https://www.feedstuffs.com/poultry/genetic-neighborhoods-may-reveal-pathogenic-bacteria), [News-Medical](https://www.news-medical.net/news/20260812/Machine-learning-uses-gene-neighborhoods-to-identify-harmful-poultry-bacteria.aspx), [The Microbiologist](https://www.the-microbiologist.com/news/researchers-look-at-genetic-neighborhoods-to-find-pathogenic-bacteria/9750.article).
