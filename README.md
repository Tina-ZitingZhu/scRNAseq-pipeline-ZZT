
## Overview
This repository contains scripts for preprocessing, clustering, and visualization of single-cell RNA-seq data using Seurat in R.

## Features
- Quality control and filtering
- Normalization and scaling
- Dimensionality reduction (PCA, UMAP)
- Clustering and marker gene identification
- Visualization of cell types

## Usage
1. Clone the repo:
   ```bash
   git clone https://github.com/Tina-ZitingZhu/scRNAseq-pipeline-ZZT.git
   cd scRNAseq-pipeline-ZZT

---

2. Install dependencies in R:
   ```R
   install.packages("Seurat")
   install.packages("tidyverse")

3. Run the example script:

source("scripts/run_pipeline.R")

---

## Example result

Below is an example UMAP plot generated from the demo pipeline:

## Data

Demo dataset can be downloaded from:

10x Genomics PBMC 3k

## Repository structure
```
scRNAseq-pipeline-ZZT/
├── README.md
├── scripts/
│   └── run_pipeline.R
├── figures/
│   └── umap_example.png
└── LICENSE
```

## Contact

Maintainer: Ziting Zhu

Email: 2023311133@stu.gzhmu.edu.cn


ORCID: [https://orcid.org/0000-0002-0662-205X]
