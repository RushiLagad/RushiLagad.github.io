---
title: ''
summary: ''
date: 2024-08-01
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        I am a PhD student in Genomics & Bioinformatics at the University of Arkansas, working in the **Goswami Lab**. My research focuses on causal inference and machine learning for host-microbiome interactions in livestock systems.

        I develop computational tools for **microbial genomics**, **Mendelian Randomization**, and **ML-based pathogen surveillance**. My work spans whole-genome sequencing, metagenomics, and transcription factor binding site analysis.

        I am always open to collaborations in bioinformatics, microbiome research, and computational biology.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: citation

  - block: collection
    id: projects-section
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: card
      columns: 2
---
