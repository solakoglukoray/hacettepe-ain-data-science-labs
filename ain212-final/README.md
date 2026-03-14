# AIN212 Final — Water Potability Prediction

> AIN212 Elements of Data Science · Fall 2024

## Overview

An end-to-end data science project predicting water potability from physicochemical features. Covers the full data science lifecycle on an environmental dataset.

## Pipeline

1. **Data Collection** — Water quality dataset (7,996 samples, 20 features)
2. **Preprocessing & Cleaning** — `#NUM!` error handling, negative value correction, outlier removal via IQR
3. **EDA** — Feature distributions, correlation heatmap, skewness analysis, statistical summaries
4. **Clustering** — K-Means and Agglomerative Clustering with silhouette score comparison
5. **Predictive Modeling** — Logistic Regression, Decision Tree, Random Forest compared with GridSearchCV
6. **Evaluation** — Confusion matrix, ROC curves, PR curves, classification report

## Models Compared

| Model | Tuning |
|-------|--------|
| Logistic Regression | GridSearchCV |
| Decision Tree | GridSearchCV |
| Random Forest | GridSearchCV ← best performer |

## Run

```bash
jupyter notebook ain212_final.ipynb
```

## Topics

`Classification` `EDA` `Clustering` `GridSearchCV` `ROC/PR curves` `Silhouette score`
