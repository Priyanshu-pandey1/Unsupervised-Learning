# 🔍 Unsupervised Learning: Clustering & Pattern Discovery

This repository documents my deep dive into **Unsupervised Learning**, focusing on identifying hidden structures and groupings within unlabeled data.

---

## 📅 Day 16: K-Means Clustering & Iris Analysis
I kicked off the Unsupervised chapter by mastering centroid-based clustering.

* **K-Means Implementation**: Partitioned data into $K$ distinct clusters where points belong to the nearest mean.
* **The Elbow Method**: Used WCSS (Within-Cluster Sum of Squares) visualization to mathematically determine the optimal cluster count.
* **Iris Dataset**: Validated unsupervised clusters against known species labels to measure model performance.

---

## 📅 Day 17: Hierarchical Clustering & DBSCAN
Today, I explored density and connectivity-based algorithms to handle complex data shapes.

### 1. Hierarchical (Agglomerative) Clustering
* **Concept**: A "bottom-up" approach where data points are merged into a tree-like structure based on proximity.
* **Dendrogram Analysis**: Used hierarchical trees to visualize merges and decide where to "cut" the tree for optimal clusters.

### 2. DBSCAN (Density-Based Spatial Clustering)
* **Concept**: Groups points based on high-density regions, making it robust to non-spherical shapes.
* **Noise Detection**: Unlike K-Means, DBSCAN effectively identifies and labels outliers (noise) that don't fit into any cluster.

---

## 📅 Day 18: SmartCart – Customer Segmentation Project 🚀
I applied my unsupervised learning knowledge to a real-world business case: transforming raw customer data into actionable insights.

* **Data Engineering**: Conducted rigorous cleaning, handled missing values, and engineered features like `Total_Spending`, `Total_Children`, and `Customer_Tenure_Days`.
* **Exploratory Data Analysis (EDA)**: Generated Heatmaps to identify correlations and visualized data distributions for better feature selection.
* **Dimensionality Reduction**: Applied **PCA (Principal Component Analysis)** before clustering to improve performance and remove redundant noise.
* **Model Selection**: Used the **Elbow Method** and **Silhouette Score** to determine that $k=4$ provides the most cohesive clusters.
* **Implementation**: Utilized **Agglomerative Clustering** with a "ward" linkage approach to profile distinct customer segments.

---

## 📂 Repository Structure
* **Clustering/**
    * `KMeans.ipynb`: Centroid-based clustering and Elbow Method implementation.
    * `KMeansFor_iris.ipynb`: Application of K-Means on biological Iris data.
    * `hierarchical_clustering.ipynb`: Connectivity-based clustering with Dendrograms.
    * `DBSCAN.ipynb`: Density-based clustering for noise-heavy datasets.
* **Projects/**
    * `SmartCart_Segmentation.ipynb`: **(New)** End-to-end customer profiling using PCA and Agglomerative Clustering.

---

## 👤 Author
**Priyanshu Pandey** [LinkedIn](https://www.linkedin.com/in/priyanshu-pandey-6a200a28b/) | [GitHub Profile](https://github.com/Priyanshu-pandey1)
