# Gene Expression Classification Using Machine Learning
Explore the basic workflow of gene expression data analysis, including preprocessing, dimensionality reduction, and classification.

## Project Motivation
Gene expression data is high-dimensional and noisy, making it a challenging yet meaningful application of machine learning in bioinformatics.
This project explores whether expression profiles can distinguish disease and healthy samples using classical machine learning techniques.

## Dataset & Task Definition
The dataset is from the Gene Expression Omnibus (GEO), accession **GSE68086**.

- **Task type:** Binary classification
- **Input:** Gene expression levels
- **Output:** Disease status

## Methodology
The analysis followed a structured bioinformatics workflow:

1. Data cleaning and label verification  
2. Exploratory analysis and dimensionality reduction using PCA  
3. Feature scaling  
4. Baseline classification model training  

PCA was used to visually assess class separability before modeling.

## Models & Evaluation
A baseline logistic regression model was trained.

Evaluation focused on:
- Accuracy
- ROC-AUC
- Conceptual understanding of ranking-based metrics

Special attention was paid to interpreting ROC-AUC in the context of biological data.

## Key Takeaways
This project provided experience with:
- High-dimensional biological datasets
- Dimensionality reduction for exploratory analysis
- Evaluation metrics beyond simple accuracy

## Future Work
- Try additional models such as Random Forest or SVM
- Perform feature selection to identify important genes
