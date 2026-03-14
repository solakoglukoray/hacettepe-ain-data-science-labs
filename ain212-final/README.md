# AIN212 Final — Water Potability Prediction

> AIN212 Elements of Data Science · Fall 2024

## Overview

An end-to-end data science project predicting water potability from physicochemical features. Covers the full data science lifecycle on an environmental dataset.

## Pipeline

1. **Data Collection** — Environmental dataset (5000+ samples, 12 features)
2. **Preprocessing & Cleaning** — Missing value handling, noise removal
3. **EDA** — Feature distributions, correlation heatmap, statistical summaries
4. **Clustering** — K-Means clustering with elbow method for optimal k
5. **Predictive Modeling** — 3+ classification algorithms compared
6. **Evaluation** — Confusion matrix, ROC curves, PR curves, F1-score

## Models Compared

- Random Forest ← best performer
- + 2 additional classifiers

**Techniques:** SMOTE oversampling (class imbalance), hyperparameter tuning via cross-validation

## Run

```bash
jupyter notebook ain212_final.ipynb
```

## Topics

`Classification` `EDA` `Clustering` `SMOTE` `Cross-validation` `ROC/PR curves`
