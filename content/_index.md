---
title: ''
summary: ''
date: 2026-11-05
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
        about: 'About'
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
    id: research
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        I am a second-year PhD student in Genomics and Bioinformatics at the University of Arkansas, working with Dr. Aranyak Goswami in the Department of Animal Science. My work asks which signals in microbial and microbiome data still hold up after careful testing, and which only appear to.

        My first-author paper in *Frontiers in Microbiology* showed that the way genes are arranged inside genomic islands helps separate disease-causing *Enterococcus cecorum* from harmless poultry strains. I now bring the same approach to gut microbiome studies in livestock and human disease: **interpretable models**, **validation across independent cohorts**, and **causal inference**.

        Before Arkansas I worked in cancer bioinformatics at Moffitt Cancer Center. I trained first as a pharmacist, which keeps me focused on results that people outside the lab can use.

        I am always happy to talk about collaborations in microbial genomics, microbiome research, and computational biology. Email me at [rlagad@uark.edu](mailto:rlagad@uark.edu).
    design:
      columns: '1'

  - block: markdown
    id: news
    content:
      title: 'News'
      subtitle: ''
      text: |-
        - **Oct 2026.** Gave a selected abstract talk on PDAC-EcoMap at the Dr. Robert Gillies Machine Learning Workshop in Cancer, Moffitt Cancer Center.
        - **Sep 2026.** Co-led the Hypothesis2Omics team at the NIAID-BRC AI Codeathon 2.0, Argonne National Laboratory.
        - **Aug 2026.** Our *Enterococcus cecorum* work was covered by the [University of Arkansas System Division of Agriculture](https://www.uaex.uada.edu/media-resources/news/2026/august/08-11-2026-ark-genomic-island-cassette-architecture.aspx), [Feedstuffs](https://www.feedstuffs.com/poultry/genetic-neighborhoods-may-reveal-pathogenic-bacteria), [News-Medical](https://www.news-medical.net/news/20260812/Machine-learning-uses-gene-neighborhoods-to-identify-harmful-poultry-bacteria.aspx), and [The Microbiologist](https://www.the-microbiologist.com/news/researchers-look-at-genetic-neighborhoods-to-find-pathogenic-bacteria/9750.article).
        - **Jul 2026.** Cassette2Vec-EC published in [*Frontiers in Microbiology*](https://doi.org/10.3389/fmicb.2026.1882753), and our review of omics and AI in neuronal gene expression published in [*Brain Informatics*](https://doi.org/10.1186/s40708-026-00323-z).
        - **2026.** Received the Omni Endowed International Student Scholarship, University of Arkansas.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: citation

  - block: markdown
    id: manuscripts
    content:
      title: ''
      subtitle: ''
      text: |-
        #### Submitted and in preparation

        - **Lagad RR**, Tsai TC, Goswami A. From WGS to actionable insight: making pathogen bioinformatics more interpretable for clinical and public-health audiences. Invited clinical review, *Infectious Disease Special Edition*. Submitted.
        - **Lagad RR**, Goswami A. From association to causal prioritization in rumen microbiome research: multi-omics reanalysis and translational frameworks for feed efficiency and methane mitigation in beef cattle. *Animal Microbiome*. Under review.
        - **Lagad RR**, et al. Moving from taxonomy to function does not sharpen microbiome inference: paired multi-omics evidence from beef cattle rumen and Arctic tundra soil. In preparation.
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Projects
      count: 4
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
      fill_image: true
      show_date: false
      show_read_time: false

  - block: markdown
    id: talks
    content:
      title: 'Talks and Posters'
      subtitle: ''
      text: |-
        #### Talks

        - **Lagad RR**, Modha N, Pathak D, Goswami A. *PDAC-EcoMap: contamination-aware evidence gating for leakage-robust, interpretable machine learning on the intratumoral microbiome in pancreatic ductal adenocarcinoma.* Selected abstract talk, Session V (AI in Biology), Dr. Robert Gillies Machine Learning Workshop in Cancer, Moffitt Cancer Center, Tampa, FL. October 15 to 16, 2026.

        #### Posters

        - Modha N, **Lagad RR**, Goswami A, Tsai TC, Howe S, Watson A, Patel S. *Modeling gut microbiome-immune co-development using multi-omics and machine learning in swine.* Arkansas Biosciences Institute Annual Research Symposium, Fayetteville, AR. October 16, 2026.
        - **Lagad RR**, Goswami A. Poster presentation. ASM Microbe 2026, American Society for Microbiology, Washington, DC. June 4 to 7, 2026.
        - **Lagad RR**, Rafi S, Goswami A. *Cassette2Vec-EC: genomic-island cassette architecture for interpretable prediction of pathogenic poultry-associated Enterococcus cecorum.* AR-BIC 2026, Arkansas Bioinformatics Consortium, North Little Rock, AR. May 18 to 19, 2026.
        - **Lagad RR**, Goswami A. *Cassette2Vec-EC: island-aware, explainable machine learning for early prediction of pathogenic Enterococcus cecorum from NGS genomes.* Abstract 252P, Student Competition, International Poultry Scientific Forum, Atlanta, GA. January 26 to 27, 2026.

        #### Earlier presentations

        - *ML for pathogenicity prediction in poultry microbiomes.* AI in Agriculture Symposium, Fayetteville, AR. 2025.
        - *Cassette2Vec: AI-based AMR cassette prediction.* AR-BIC 2025, Arkansas Bioinformatics Consortium. 2025.
        - Oral and poster presentations at an Indo-German conference (2019) and Indo-African scientific meetings (2018), Pune, India.
    design:
      columns: '1'
---
