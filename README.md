# Visualizing-Hierarchical-Clustering-with-Dendrograms-Iris-Dataset-
Use scipy to perform Agglomerative Hierarchical Clustering. Create a dendrogram to show merging steps. Cut the tree at a selected level and plot the final cluster labels. from scipy.cluster.hierarchy import dendrogram, linkage linkage_matrix = linkage(X, method='ward')

# 🌿 Hierarchical Clustering with Dendrograms – Iris Dataset

## 📘 Project Overview

This project demonstrates **Agglomerative Hierarchical Clustering** using the classic **Iris dataset**. The project includes:

- Data preprocessing (feature selection and scaling)
- Generating a dendrogram to visualize the merge steps
- Cutting the dendrogram to form clusters
- Visualizing the resulting clusters with a scatter plot

---

## 📊 Dataset

- **Name**: Iris Dataset (built-in from `sklearn.datasets`)
- **Samples**: 150 iris flower records
- **Features used**:
  - Sepal length (cm)
  - Petal length (cm)
- **Target**: Not used (unsupervised), but available for comparison

---

## 📌 Objectives

- Apply **Ward’s method** to perform agglomerative clustering
- Visualize the cluster merging process using a **dendrogram**
- Extract **3 clusters** from the tree
- Plot the final clusters using 2D scatter plot

---

## 🧰 Technologies Used

- Python
- pandas
- seaborn
- matplotlib
- scikit-learn
- scipy (for hierarchical clustering and dendrogram)
