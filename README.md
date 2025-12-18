# -Gene-Expression-Omnibus-GEO-Dataset-GSE68086
Samples: 285 columns (including controls), Features: 57,736 Ensembl gene IDs (rows), Data Type: Intron-spanning read counts

## Project Overview
This project explores gene expression data from the Gene Expression Omnibus (GEO) Dataset: GSE68086.
The goal is to understand the basic workflow of gene expression data analysis, including preprocessing, dimensionality reduction, and classification.

## Dataset
- Source: Gene Expression Omnibus (GEO)
- Accession number: GSE68086
- Accessed via: Kaggle
- Description: Gene expression profiles with disease status labels

The raw data are publicly available and are not included in this repository.

## Methods
The following steps were performed:

1. Data preprocessing
   - Removed samples with unknown disease status
   - Standardized gene expression values using StandardScaler

2. Exploratory analysis
   - Principal Component Analysis (PCA) to visualize sample distribution

3. Modeling
   - Logistic Regression for disease classification
   - Model evaluation using accuracy and ROC-AUC

## Tools
- Python
- pandas, numpy
- scikit-learn
- matplotlib / seaborn

## What I Learned
- How to preprocess high-dimensional gene expression data
- Why feature scaling is necessary before PCA and logistic regression
- How to evaluate classification models using different metrics

## Future Work
- Try additional models such as Random Forest or SVM
- Perform feature selection to identify important genes
