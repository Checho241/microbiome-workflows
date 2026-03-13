# Microbiome Bioinformatics Workflows

Reproducible workflows for microbiome community analysis using 16S rRNA and ITS amplicon sequencing data.

Developed by Sergio Pardo-Diaz, M.Sc.  
Agricultural and Veterinary Microbiologist  
Bogota, Colombia

---

## Overview

This repository contains reproducible R-based workflows for microbiome data analysis using QIIME2-derived datasets.  
The pipelines are designed for microbial ecology studies involving soil, plant-associated, or environmental microbiomes.

The workflows integrate data preprocessing, ecological statistics, and publication-ready visualization for microbial community studies.

---

## Workflow Components

The analysis pipelines include:

- Import of QIIME2-derived feature tables, taxonomy, trees, and metadata
- Construction of phyloseq objects
- ASV filtering and preprocessing
- Alpha diversity analysis
- Beta diversity analysis
- PERMANOVA and dispersion testing
- Relative abundance profiling
- Differential abundance analysis
- Generation of publication-quality figures

---

## Tools and Packages

Main tools used in the workflows:

### Microbiome analysis
- QIIME2
- phyloseq
- vegan
- microbiome

### Statistical analysis
- ANCOMBC2
- rstatix

### Data manipulation
- tidyverse
- dplyr
- tidyr

### Visualization
- ggplot2
- patchwork
- cowplot

---

## Repository Structure

```text
microbiome-workflows/
├── workflows/
│   ├── microbiome_amplicon_pipeline.R
│   ├── alpha_diversity_analysis.R
│   ├── beta_diversity_analysis.R
│   ├── relative_abundance_analysis.R
│   └── differential_abundance_ANCOMBC2.R
├── templates/
│   └── metadata_template.tsv
├── docs/
│   └── workflow_description.md
└── figures/
    └── example_outputs.png

