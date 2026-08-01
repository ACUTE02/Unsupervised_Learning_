# 🔍 Clustering Algorithms using K-Means & DBSCAN

> **An Unsupervised Machine Learning project demonstrating clustering techniques using K-Means, DBSCAN, and the Elbow Method with Scikit-learn.**

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blue?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Unsupervised-Learning-success?style=for-the-badge)

</p>

---

# 📖 Overview

Clustering is one of the most widely used unsupervised machine learning techniques for discovering hidden patterns in unlabeled data.

This project demonstrates two popular clustering algorithms:

- **K-Means Clustering** – A centroid-based clustering algorithm.
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** – A density-based clustering algorithm capable of detecting arbitrarily shaped clusters and identifying noise points.

The project also implements the **Elbow Method** using Within-Cluster Sum of Squares (WCSS) to determine the optimal number of clusters for K-Means.

---

# ✨ Features

- 🔍 K-Means Clustering
- 🌐 DBSCAN Clustering
- 📊 Elbow Method (WCSS)
- 📈 Cluster Visualization
- ⚙️ Feature Scaling using StandardScaler
- 🧪 Synthetic Dataset Generation
- 📉 Performance Comparison of Clustering Algorithms
- 🎨 Seaborn Scatter Plots

---

# 📂 Project Structure

```text
Clustering-Algorithms/
│
├── clustering.py
├── Clustering.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset

The project uses synthetic datasets generated using Scikit-learn.

### Dataset 1

**make_blobs()**

- 500 Samples
- 3 Clusters
- Standard Deviation = 4

Used for demonstrating **K-Means Clustering**.

---

### Dataset 2

**make_moons()**

- 500 Samples
- Non-linear moon-shaped clusters
- Noise = 0.05

Used to compare **K-Means** and **DBSCAN**.

---

# 🧠 Algorithms Used

## 📍 K-Means Clustering

K-Means partitions the dataset into **K clusters** by assigning each data point to the nearest centroid.

### Workflow

```text
Random Centroids
       │
       ▼
Assign Data Points
       │
       ▼
Update Centroids
       │
       ▼
Repeat Until Convergence
```

---

## 📈 Elbow Method

The project calculates the **Within-Cluster Sum of Squares (WCSS)** for different values of **K**.

The optimal number of clusters is selected where the WCSS curve forms an "elbow", indicating diminishing returns from adding more clusters.

---

## 🌐 DBSCAN

DBSCAN groups points based on density instead of predefined centroids.

### Advantages

- Detects arbitrarily shaped clusters.
- Automatically identifies outliers.
- Does not require specifying the number of clusters beforehand.

---

# 🔄 Project Workflow

```text
Generate Dataset
        │
        ▼
Feature Scaling
        │
        ▼
Elbow Method
        │
        ▼
Optimal K Selection
        │
        ▼
K-Means Clustering
        │
        ▼
Cluster Visualization
        │
        ▼
Generate Moon Dataset
        │
        ▼
K-Means vs DBSCAN
        │
        ▼
Performance Comparison
```

---

# 📊 Results

The project demonstrates:

- WCSS curve for selecting the optimal number of clusters.
- K-Means clustering visualization on blob data.
- Comparison of K-Means and DBSCAN on moon-shaped data.
- DBSCAN's ability to identify non-linear clusters and noise.

---

# 🛠 Technologies Used

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Clustering-Algorithms.git
```

```bash
cd Clustering-Algorithms
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Run the Project

```bash
python clustering.py
```

or open:

```text
Clustering.ipynb
```

---

# 📚 Concepts Covered

- Unsupervised Learning
- K-Means Clustering
- DBSCAN
- Elbow Method
- WCSS (Within-Cluster Sum of Squares)
- Feature Scaling
- Cluster Visualization
- Synthetic Data Generation

---

# 🎯 Skills Demonstrated

- Machine Learning
- Unsupervised Learning
- Data Preprocessing
- Feature Scaling
- Clustering Algorithms
- Model Comparison
- Data Visualization
- Python Programming

---

# 📦 requirements.txt

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

# 🚀 Future Improvements

- Hierarchical Clustering
- Agglomerative Clustering
- Gaussian Mixture Models (GMM)
- Silhouette Score Evaluation
- Real-World Dataset Analysis
- Interactive Streamlit Dashboard

---

# 👨‍💻 Author

**Ayushmaan Gupta**

B.Tech CSE (Artificial Intelligence & Machine Learning)

---

# ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork this repository
- 🤝 Contribute with improvements

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

## 🔍 Clustering Algorithms using K-Means & DBSCAN

### Discover Hidden Patterns in Unlabeled Data

**"Unsupervised learning reveals the structure hidden within data."**

</div>
