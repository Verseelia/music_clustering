# Music Clustering

This project applies **unsupervised machine learning techniques** to analyze and cluster songs based on their audio features.

## 📌 Project Overview

The goal of this project is to identify groups of songs with similar musical characteristics using different clustering algorithms.

The dataset contains approximately **95,000 songs** with features such as:

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Duration

## 🛠️ Techniques Used

- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Correlation Analysis
- K-Means Clustering
- Gaussian Mixture Model (GMM)
- DBSCAN Clustering
- Agglomerative Clustering
- PCA for Visualization
- Silhouette Score for Cluster Evaluation

## 📊 Clustering Algorithms

### K-Means

Used to divide songs into distinct clusters based on their audio features.

### Gaussian Mixture Model (GMM)

Used to identify probabilistic clusters and capture overlapping groups of songs.

### DBSCAN

Used to identify density-based clusters and detect potential noise or outlier observations.

### Agglomerative Clustering

Used to explore hierarchical relationships between songs and compare different numbers of clusters.

## 📈 Model Evaluation

The clustering approaches were evaluated using metrics such as:

- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index
- Cluster size and distribution
- Cluster feature profiles

## 💻 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

