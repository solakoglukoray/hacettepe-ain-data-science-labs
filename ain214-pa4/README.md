# AIN214 PA4 — Airline Classification + Country Clustering

> AIN214 Data Science Lab · Fall 2025

## Overview

Two-part assignment: classification on airline passenger satisfaction, and K-Means clustering on country socioeconomic data.

## Part 1 — Airline Passenger Satisfaction (Classification)

**Dataset:** Airline Passenger Satisfaction (~130,000 samples)

### Preprocessing
- EDA: class distribution, missing values, feature distributions
- One-hot encoding for categorical variables
- Missing value imputation
- Feature normalization/standardization
- Manual train/validation split (80/20) — no `train_test_split` used

### Models Trained
- Logistic Regression
- kNN Classifier
- Decision Tree

**Evaluation:** Accuracy · Confusion Matrix · Precision / Recall / F1 · Feature importance

## Part 2 — Country Development Clustering

**Dataset:** 167-country socioeconomic & health indicators

- K-Means clustering with elbow method for optimal k
- Feature scaling before clustering
- Cluster profile interpretation (development levels)
- Visualization of cluster distributions

## Run

```bash
jupyter notebook ain214_pa4.ipynb
```

## Topics

`Logistic Regression` `kNN` `Decision Tree` `K-Means` `Feature importance` `Clustering` `Elbow method`
