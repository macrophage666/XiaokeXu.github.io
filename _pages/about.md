---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======
Hi, I'm Xiaoke, a PhD candidate in Department of pharmaceutical science, University of Nebraska Medical Center. I have both wet lab and dry lab experience and skills. My thesis project focused on using scRNA-seq and scATAC-seq to understand HIV-associated neurological disorders (HANDs). I am also involved in several other collaborated studies using bulk RNA-seq and proteomics data to understand other neuropathologies. I am skilled in R and Python programming languages, Linux bash, and varied bioinformatic/analytical tools.

Education
======

China Pharmaceutical University (09/2016-06/2020)
------
* Bachelor of Science in Pharmaceutical Science (GPA 3.6/4.0)
* Award: Chinese government scholarship; University scholarship(3 years)

University of Nebraska Medical Center (08/2021-08/2025 (expected))
------
* PhD in Pharmaceutical Science (GPA 3.9/4.0)
* Selected courses: Biostatistical Computing (A+), Intro to Biostatistics, Machine Learning (A+), Biostatistics (A), Fundamentals of Biomolecules(A-), Intro (A+) and Advanced (A) Immunology
* Leadership position: resident of China Students and Scholars Association

Research
======
1. Unveiling the transcriptomic landscape of brain immunity in acute SIV infection via single-cell RNA sequencing (scRNA-seq). 

  In this project, the scRNA-seq was used. My work includes preprocessing the scRNA-seq data using [cellranger pipelines](https://www.10xgenomics.com/support/software/cell-ranger/latest), data mining and result interpretation. In data mining, I used the [Seurat R pacakge](https://satijalab.org/seurat/). Additionally, other scRNA-seq analysis, data manipulation, and visualization tools were also used, which includes [clusterProfiler](https://github.com/YuLab-SMU/clusterProfiler), [ComplexHeatmap](https://github.com/jokergoo/ComplexHeatmap), [Monocle3](https://cole-trapnell-lab.github.io/monocle3/), [dplyr](https://github.com/tidyverse/dplyr), and [ggplot2](https://ggplot2.tidyverse.org/), etc. Given the advancement of scRNA-seq in studying the disease mechanism, I had serveral interesting findings. In the study of [Microglia and macrophages alterations in the CNS during acute SIV infection](https://doi.org/10.1371/journal.ppat.1012168), I identified signature genes associated with different phenotypes and mapping them to various biological and pathological pathways. I also discovered two myeloid cell clusters strongly linked to neurodegenerative disorders. In the study of Lymphocyte alternations in the CNS during acute SIV infection (paper in preparation), I did a comprehensive transcriptomic characterization of brain lymphocytes and blood CD4+ T cells during acute SIV infection, identifying a candidate lymphocyte phenotype that may contribute to the initiation of CNS infection. These findings might shed light on the immunological and pathological effects of different myeloid and lymphoid phenotypes in the brain during acute SIV infection, providing valuable insights for future therapeutic strategies targeting this critical stage and aiming to eliminate the viral reservoir.

2. Transformation of brain myeloid cell populations by SIV in rhesus macaques revealed by multiomics (snRNA-seq and snATAC-seq).

In this project, the 10X Genomics multiomics platform (snRNA-seq and snATAC-seq) was used. My work includes processing the multiomic data using [cellranger arc pipelines](https://www.10xgenomics.com/support/software/cell-ranger-arc/latest), data mining and result interpretation. In data mining, I used the [ArchR R pacakage](https://www.archrproject.com/). Additionally, other scRNA-seq analysis, data manipulation, and visualization tools were also used, which includes [CellChat](https://github.com/sqjin/CellChat), [epiVIA] (https://github.com/wangwl/epiVIA), [ComplexHeatmap](https://github.com/jokergoo/ComplexHeatmap), etc. [In this study](https://doi.org/10.21203/rs.3.rs-4916594/v1), I identified an unique population of microglia-like cells which the chromatin accessibility of genes diverges from their RNA expression. By combining the SIV and rhesus macaque genomes for genome mapping, many SIV DNA fragments and RNA transcripts could be found. The SIV DNA fragments provided a way for us to study the SIV integration site and virus-host gene regulatory interactions.  We identified several potential integration sites and found the integration preference near the FSTL5 gene. Also, we further confirmed that the virus could use the transcription factors (TFs) from human for its own gene regulatory events. Those findings might further deepen the understanding the SIV/HIV and host regulatory events in the brain myeloid cells. 

3. Transcriptomic and epigenetic assessment of the morphine effect on brain myeloid cells in cART-suppressed SIV infection.

In this project, the 10X Genomics multiomics platform (snRNA-seq and snATAC-seq) was used again for studying. My work includes processing the multiomic data using [cellranger arc pipelines](https://www.10xgenomics.com/support/software/cell-ranger-arc/latest), data mining and result interpretation. I first compared the capability of [snapatac2](https://github.com/kaizhang/SnapATAC2) and [ArchR R pacakage](https://www.archrproject.com/) in processing multiomic data, and decided to use ArchR given its better performance in conducting motif analysis. In addition to ArchR, the other pacakages including [clusterProfiler](https://github.com/YuLab-SMU/clusterProfiler), [ComplexHeatmap](https://github.com/jokergoo/ComplexHeatmap), [Monocle3](https://cole-trapnell-lab.github.io/monocle3/) were also used for analysis. By integrating scRNA-seq data for difference species (human and rhesus monkey), I first found that the combination antiretroviral therapy (cART) could greatly restore microglia homeostasis in infected animals. Then, I further studied the morphine's effects in cART-treated SIV infection. Based on both transcriptomic and epigenetic assessment, I found the extensive immunosuppressive effect of morphine on brain myeloid cells during the SIV infection. In this study, I also identified an inflammatory mediator (ADORA2B) that was specifically upregulated in cART-treated SIV infection but not in those cART-treated SIV-infected animals with morphine injection. This project is still going on fpr the wet lab validation and more promising findings.