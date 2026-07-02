# Fraud Detection Clustering using K-Means

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Silhouette](https://img.shields.io/badge/Silhouette-0.572-28A745?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-2EA44F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-00C853?style=for-the-badge)

An Unsupervised Machine Learning project for customer transaction clustering using K-Means and Principal Component Analysis (PCA) to identify transaction patterns related to fraud detection.

---

## Overview

This project performs customer segmentation based on transaction behavior using K-Means Clustering.

The workflow covers the complete clustering pipeline, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Correlation analysis
- K-Means clustering
- Cluster evaluation
- PCA visualization

---

## Dataset

The dataset contains synthetic customer transaction information.

Features:

- Transaction Amount
- Customer Age
- Transaction Duration
- Login Attempts
- Account Balance
- Customer Occupation

---

## Features

- Data preprocessing
- Correlation Matrix
- Feature Distribution Analysis
- Transaction Boxplot Analysis
- K-Means Clustering
- Silhouette Score Evaluation
- PCA Dimensionality Reduction
- Cluster Visualization
- Saved K-Means Model
- Saved PCA Model

---

## Project Structure

```text
clustering-project/
├── assets/
│   ├── correlation-matrix.png
│   ├── feature-distributions.png
│   ├── transaction-boxplot.png
│   ├── silhouette-score.png
│   └── cluster-visualization.png
├── dataset/
│   ├── data_clustering.csv
│   └── data_clustering_inverse.csv
├── models/
│   ├── model_clustering.h5
│   └── PCA_model_clustering.h5
├── fraud_detection_clustering.ipynb
├── requirements.txt
└── README.md
```

---

## Clustering Performance

| Metric | Value |
|--------|-------:|
| Optimal Clusters | **2** |
| Silhouette Score | **0.572** |

### Silhouette Score

![Silhouette Score](assets/silhouette-score.png)

---

## Cluster Visualization

### PCA Cluster Visualization

![Cluster Visualization](assets/cluster-visualization.png)

---

## Exploratory Data Analysis

### Correlation Matrix

![Correlation Matrix](assets/correlation-matrix.png)

### Feature Distributions

![Feature Distributions](assets/feature-distributions.png)

### Transaction Distribution by Customer Occupation

![Transaction Boxplot](assets/transaction-boxplot.png)

---

## Technologies

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Joblib

---

## Future Improvements

- Experiment with DBSCAN clustering
- Compare with Hierarchical Clustering
- Optimize feature engineering
- Deploy clustering pipeline using Streamlit
- Apply clustering on real-world financial datasets

---

## Author

**Miqdad Badjuber**

GitHub: https://github.com/miqdadbadjuber
