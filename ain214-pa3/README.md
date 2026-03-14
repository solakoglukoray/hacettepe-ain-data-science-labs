# AIN214 PA3 — Diamond Price Regression

> AIN214 Data Science Lab · Fall 2025

## Overview

Regression analysis on the Diamonds dataset (~54,000 samples) predicting price from physical and quality features.

## Pipeline

### Part 1 — Data Preprocessing
- EDA: missing values, price distribution, correlation heatmap, feature-target visualizations
- Outlier detection: **IQR method** (zero-dimension rows removed first, then statistical outliers)
- Outlier removal with before/after boxplot comparison
- Ordinal encoding for cut, color, clarity (custom order mappings)
- Manual train/test split (70/30) implemented from scratch — no `train_test_split` used

### Part 2 — Regression Models

| Model | Dataset | Metric |
|-------|---------|--------|
| Linear Regression | Original + Outlier-removed | MSE comparison |
| Linear Regression | 5-Fold Cross-Validation | R², RMSE (mean ± std) |
| kNN Regression | k=1–10, both datasets | MSE vs k curve, optimal k |
| kNN + StandardScaler | Best k, cleaned dataset | Scaled vs unscaled comparison |

**Key finding:** Cleaned dataset + StandardScaler gives lowest MSE for kNN.

## Run

```bash
jupyter notebook ain214_pa3.ipynb
```

## Topics

`Linear Regression` `kNN Regression` `Outlier detection` `Cross-validation` `Feature scaling` `Ordinal encoding`
