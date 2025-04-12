# 🔍 Breast Cancer Data Clustering with K-Means Algorithm

![](https://github.com/Jamestown34/Breast-Cancer-Unsupervised-learning-Prediction/blob/main/BreastCancer/Screenshot%20(46).png) <!-- Image: optional cover image showing clustered data -->

## 🧠 Project Overview

In this project, we explore the power of **unsupervised machine learning** to uncover hidden patterns within breast cancer patient data. By applying the **K-means clustering algorithm**, we aimed to group patient records based on similarities in tumor and diagnostic features — **without any prior labels**.

This approach helps in identifying **natural groupings or clusters** in the data that may align with the likelihood of a breast cancer diagnosis. It offers a fresh perspective on the data, supporting doctors and researchers in early diagnosis, pattern recognition, and potential treatment strategies.

---

## 🎯 Problem Statement

Breast cancer remains one of the most prevalent and life-threatening diseases affecting women globally. While supervised models are commonly used to predict diagnoses, our goal was to take an **unsupervised approach** to gain a **different layer of insights**.

### Objective:
- Cluster patient data using **K-means** to detect underlying patterns
- Identify two primary clusters (likely: malignant vs benign)
- Evaluate clustering effectiveness using **inertia** and **silhouette scores**
- Visualize results for easy interpretation

---

## 📚 Dataset

- Source: [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- Total records: 569
- Features: 30 numeric features (e.g., mean radius, texture, perimeter, area, smoothness)
- Target: Diagnosis (used *only for evaluation*)

![](https://github.com/Jamestown34/Breast-Cancer-Unsupervised-learning-Prediction/blob/main/BreastCancer/Screenshot%20(48).png) <!-- Optional image showing correlation heatmap or data sample -->

---

## 🛠 Tools & Technologies

- **Python**
- **Scikit-learn** (KMeans, preprocessing, evaluation metrics)
- **Matplotlib & Seaborn** (visualizations)
- **Pandas & NumPy** (data manipulation)
- **Jupyter Notebook**

---

## 🔬 Methodology

### ✅ Step-by-step:

1. **Data Preprocessing**
   - Removed non-numeric/identifier columns
   - Standardized feature values using `StandardScaler`

2. **K-means Clustering**
   - Defined 2 clusters (K = 2) to match the possible benign/malignant grouping
   - Trained the model on the normalized feature set

3. **Evaluation**
   - **Inertia Score**: `9.53` — measures within-cluster sum of squares
   - **Silhouette Score**: `0.39` — indicates moderate separation between clusters

4. **Visualization**
   - Plotted PCA-reduced clusters to see separation
   - Used cluster centroids to understand feature influence

![](https://github.com/Jamestown34/Breast-Cancer-Unsupervised-learning-Prediction/blob/main/BreastCancer/Screenshot%20(51).png) <!-- Cluster visualization plot -->

---

## 📊 Results & Interpretation

- The model successfully **segmented the data into two distinguishable clusters**.
- The **silhouette score of 0.39** suggests meaningful separation between patient types, even without label guidance.
- Upon comparing with actual labels post-clustering, a high level of overlap was found between the clusters and the original diagnoses (benign/malignant).
- Visualizations revealed that features like **mean area**, **perimeter**, and **radius** played a strong role in cluster distinction.

---

## 💡 Insights & Implications

This project highlights how **unsupervised techniques like K-means can be used to identify meaningful groupings in medical datasets**, even when labeled data is unavailable or incomplete.

Such insights could:
- Help in **early patient screening**
- Guide **further analysis or treatment pathways**
- Assist in **pattern discovery** in other medical conditions

---

## 🚀 Next Steps

- 🧪 Try other clustering methods: **DBSCAN**, **Hierarchical Clustering**
- 📐 Use **dimensionality reduction techniques** like t-SNE or UMAP for deeper visual insights
- 🧠 Combine clustering with **supervised learning** for hybrid models
- 📈 Deploy findings in a medical data dashboard or visualization tool

- ![](https://github.com/Jamestown34/Breast-Cancer-Unsupervised-learning-Prediction/blob/main/BreastCancer/Screenshot%20(53).png) <!-- Cluster visualization plot -->

---


## 🤝 Let's Connect

This project is a small step in a much larger journey to make data science useful in **real-world healthcare applications**. Feel free to fork the repo, explore the code, or connect with me for collaboration!

