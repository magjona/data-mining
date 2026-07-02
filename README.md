# Data Mining — Computing Assignment (Semester 2)

This repository contains a data mining project completed as part of a computing course assignment, applying core data mining techniques — classification, clustering, and outlier detection — across multiple benchmark datasets in R.

## Overview

| Task | Dataset | Techniques |
|---|---|---|
| Income Prediction | Adult Census Income | Decision Tree, Naive Bayes, Logistic Regression, KNN, ANN |
| Clustering | Iris | K-Means, Hierarchical Clustering |
| Outlier Detection | Adult Census Income | IQR, Z-Score, Isolation Forest, LOF (with consensus approach) |
| Rule-Based Learning | Weather | One Rule (1R) |

## Details

### 1. Income Prediction (Classification)
Predicts income category (`<=50K` / `>50K`) from the Adult Census dataset using five classifiers:
- **Decision Tree**
- **Naive Bayes**
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Artificial Neural Network (ANN)**

Models are trained, evaluated, and compared to identify the best-performing approach for this classification task.

### 2. Clustering Analysis
Applies unsupervised learning to the classic Iris dataset:
- **K-Means Clustering**
- **Hierarchical Clustering**

Used to explore natural groupings in the data and compare cluster assignments against known species labels.

### 3. Outlier Detection
Identifies anomalous records in the Adult dataset using four independent methods:
- **IQR (Interquartile Range)**
- **Z-Score**
- **Isolation Forest**
- **LOF (Local Outlier Factor)**

A **consensus approach** combines results across all four methods to flag the most reliably anomalous points.

### 4. One Rule (1R) Demonstration
A simple rule-based classifier applied to a weather dataset, demonstrating how a single-attribute rule can achieve reasonable predictive accuracy — a useful baseline against more complex models.

## Notes
All code is written with efficiency and readability in mind.

## Tech Stack
- **Language:** R (R Markdown)
- **Key packages:** likely includes `caret`, `class`, `e1071`, `rpart`, `nnet`, `cluster`, `isotree`/`solitude`, `dbscan` or similar (update to match your actual `.Rmd` library calls)

## How to Run
1. Clone the repository
2. Open the `.Rmd` file in RStudio
3. Install required packages (see library calls at the top of the file)
4. Knit to HTML/PDF to reproduce the full analysis and results

## Author
Maganda Jonathan — Bachelor of Statistics (Computing Option), Makerere University
