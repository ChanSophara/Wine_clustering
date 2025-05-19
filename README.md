# 🍷 Wine Clustering Project

> A mini machine learning project using unsupervised learning to group wines based on their chemical properties.

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-orange.svg)
![Status](https://img.shields.io/badge/Project-Finished-brightgreen.svg)

---

## 📌 Project Overview

This project explores the **Wine dataset** from scikit-learn and applies clustering algorithms to uncover natural groupings within the data. It includes:

- 📊 Exploratory Data Analysis (EDA)
- 📉 Dimensionality Reduction (PCA)
- 🤖 Clustering with K-Means and Agglomerative Clustering
- 📈 Evaluation with Silhouette Score
- 🎯 2D visualization of clusters using PCA

---

## 🔍 Objective

The goal is to segment wines into distinct clusters **without knowing the actual wine classes**, and compare the clustering performance using different methods.
## 📊 Dataset Info

- 📦 Source: `sklearn.datasets.load_wine()`
- 🧪 178 wine samples
- 🔬 13 chemical features (e.g., alcohol, malic acid, flavanoids)
- 🎯 True labels (for reference): 3 wine classes

---

## ⚙️ Techniques Used

| Technique           | Purpose                              |
|---------------------|--------------------------------------|
| PCA                 | Reduce dimensionality for plotting   |
| KMeans Clustering   | Group wines based on feature similarity |
| Agglomerative Clustering | Compare with hierarchical approach |
| Silhouette Score    | Evaluate clustering performance      |

---

## 📈 Results

- ✅ **Best number of clusters**: 3  
- 📊 **KMeans Silhouette Score**: ~0.29  
- 🔍 PCA reveals a clear separation of clusters  
- 🧩 Clusters partially align with true wine classes

---

## 📷 Visual Output

> Clusters visualized using PCA:
![Clustering PCA](https://upload.wikimedia.org/wikipedia/commons/4/42/Wine_Data_PCA.png)

---

## 🧠 Learnings

- PCA is a powerful tool to visualize high-dimensional data.
- Even without labels, clustering can discover meaningful structure.
- Comparing different algorithms helps validate findings.

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/wine-clustering-project.git
