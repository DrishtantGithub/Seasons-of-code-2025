# Wine Dataset Classifier

This mini-project is the **first assignment** completed as part of the **Seasons of Code Learning Program**. It uses the classic **Wine dataset** from the `scikit-learn` library to demonstrate multiple classification techniques and analysis tools learned so far.

---

## Project Overview

The **Wine dataset** is a well-known multivariate dataset that contains the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. Each sample includes 13 numerical features (like alcohol, malic acid, flavanoids, etc.) and a target class (cultivar: 0, 1, or 2).

### Objectives

- Understand and explore the dataset
- Determine whether the problem is regression or classification (→ it's **classification**)
- Apply **dimensionality reduction** using PCA
- Compare multiple classification algorithms and evaluate performance

---

## Dataset Details

- **Total samples**: 178
- **Features**: 13 continuous variables
- **Target classes**: 3 wine types (class 0, 1, 2)
- **Source**: `sklearn.datasets.load_wine()`

---

## Algorithms Used

- **Support Vector Machines (SVM)**
- **Naive Bayes (GaussianNB)**
- **Linear Discriminant Analysis (LDA)**
- **Quadratic Discriminant Analysis (QDA)**
- **K-Nearest Neighbors (KNN)**

Dimensionality reduction was done using **Principal Component Analysis (PCA)** to visualize the data and assess linear separability.

---
