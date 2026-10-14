# DLPFC Spatial Transcriptomics Analysis

An exploratory spatial transcriptomics analysis of human dorsolateral prefrontal cortex (DLPFC) tissue using **10x Genomics Visium** data. This project investigates cortical layer organization through gene-expression clustering and compares feature-selection strategies across five tissue samples.

## Methods

- **Preprocessing:** Scanpy, AnnData, spatial coordinates
- **Dimensionality Reduction:** PCA, UMAP
- **Feature Selection:** Highly Variable Genes (2,000 and 5,000 HVGs)
- **Clustering:** Leiden clustering
- **Evaluation:** Adjusted Rand Index (ARI), Normalized Mutual Information (NMI)

## Key Findings

Full-gene PCA achieved the highest ARI in three of five samples, while selecting 2,000 highly variable genes performed better in the remaining two, highlighting sample-dependent differences in clustering performance.

## Dataset

**Human DLPFC — 10x Genomics Visium**

[Report Link](https://drive.google.com/file/d/13en8pnvkDfc1i_NuzWA0qza_eqvCAHJz/view?usp=sharing)

## Repository Contents

- `01_DLPFC_Visium_Data_Download.ipynb` — Dataset acquisition.
- `02_DLPFC_Spatial_Transcriptomics_Analysis.ipynb` — Data preprocessing, clustering, feature selection, visualization, and evaluation.

## Technologies

Python · Scanpy · AnnData · Scikit-learn · Leiden · UMAP
