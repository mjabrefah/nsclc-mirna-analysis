## Lung Cancer Gene Expression Visualization

This Python project visualizes the gene expression profile of human lung cancer and control samples. It uses data from a study on non-small cell lung cancer (NSCLC) to analyze and compare gene expression patterns between tumor and non-tumor samples.

## Project Overview

The project aims to:
1. Establish gene signatures in primary adenocarcinomas and squamous-cell carcinomas
2. Determine differentially expressed gene sequences at different stages of the disease
3. Identify sequences with biological significance for tumor progression

## Dataset
GEO Series GSE93300

The dataset used in this project comes from a microarray analysis of 91 NSCLC samples:
- 46 tumor samples
- 45 control (non-tumor) samples

An additional independent set of 70 samples was used for validation:
- 48 tumor samples
- 22 non-tumor samples

The study focused on 92 selected genes, validated using qPCR.

## Tools Used

This project utilizes the following Python libraries:
- NumPy: For numerical computations and array operations
- Pandas: For data manipulation and analysis
- Matplotlib: For creating visualizations and plots
