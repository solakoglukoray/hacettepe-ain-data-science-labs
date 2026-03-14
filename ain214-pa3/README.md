# AIN214 PA3 — Diamond Price Regression

> AIN214 Data Science Lab · Fall 2025

## Overview

Regression analysis on the Diamonds dataset (~54,000 samples) predicting price from physical and quality features.

## Pipeline

### Part 1 — Data Preprocessing
- EDA: missing values, feature-target visualizations, correlation heatmap
- Outlier detection (chosen method explained in notebook)
- Outlier removal with before/after comparison
- Ordinal encoding for cut, color, clarity
- Manual train/test split (70/30) — no `train_test_split` used

### Part 2 — Regression Models

| Model | Dataset | Metric |
|-------|---------|--------|
| Linear Regression | Original + Outlier-removed | MSE |
| Linear Regression | K-Fold Cross-validation | R², RMSE (mean ± std) |
| kNN Regression | k=1–10, both datasets | MSE vs k curve |
| kNN + StandardScaler | Best k, best dataset | MSE comparison |

## Run

```bash
jupyter notebook ain214_pa3.ipynb
```

## Topics

`Linear Regression` `kNN Regression` `Outlier detection` `Cross-validation` `Feature scaling` `Ordinal encoding`
