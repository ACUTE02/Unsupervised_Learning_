# 📉 Principal Component Analysis (PCA) for Dimensionality Reduction

> **A Machine Learning project demonstrating Principal Component Analysis (PCA) using Scikit-learn for reducing high-dimensional data while preserving essential information.**

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success?style=for-the-badge)

</p>

---

# 📖 Overview

Principal Component Analysis (PCA) is one of the most widely used dimensionality reduction techniques in Machine Learning. It transforms high-dimensional datasets into a smaller set of uncorrelated features called **Principal Components**, preserving most of the important information while reducing computational complexity.

In this project, a synthetic dataset with **5 numerical features** is generated using Scikit-learn. The data is standardized using **StandardScaler**, reduced to **2 principal components**, and visualized to demonstrate how PCA captures the essential structure of the data.

---

# ✨ Features

- 📉 Principal Component Analysis (PCA)
- 📊 Dimensionality Reduction
- ⚙️ Feature Scaling using StandardScaler
- 🧪 Synthetic Dataset Generation
- 📈 Two-Dimensional Data Visualization
- 🎨 Cluster Visualization using Seaborn
- 🚀 Scikit-learn Implementation

---

# 📂 Project Structure

```text
PCA-Dimensionality-Reduction/
│
├── PCAdimension.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset

The project uses a synthetic dataset generated with Scikit-learn.

### Dataset Characteristics

- 500 Samples
- 5 Features
- 3 Clusters
- Generated using `make_blobs()`

---

# 🧠 What is PCA?

Principal Component Analysis transforms the original dataset into a new coordinate system.

Instead of using the original features, PCA creates new variables called **Principal Components**.

These components:

- Capture maximum variance
- Are uncorrelated
- Reduce dimensionality
- Improve visualization
- Reduce computational cost

---

# 🔄 Workflow

```text
Generate Dataset
        │
        ▼
Feature Scaling
        │
        ▼
StandardScaler
        │
        ▼
Principal Component Analysis
        │
        ▼
Reduce Dimensions
(5 Features → 2 Components)
        │
        ▼
Scatter Plot Visualization
```

---

# ⚙️ Implementation Steps

1. Generate synthetic dataset using `make_blobs()`
2. Standardize the features using `StandardScaler`
3. Apply PCA with `n_components=2`
4. Transform the dataset into principal components
5. Create a DataFrame containing PC1 and PC2
6. Visualize the transformed dataset using Seaborn

---

# 📈 Results

The transformed dataset is represented using:

- **PC1 (Principal Component 1)**
- **PC2 (Principal Component 2)**

These two components retain most of the important information from the original five-dimensional dataset while making visualization much easier.

---

# 🛠 Technologies Used

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/PCA-Dimensionality-Reduction.git
```

```bash
cd PCA-Dimensionality-Reduction
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

Open the notebook:

```text
PCAdimension.ipynb
```

Run all cells to generate the PCA visualization.

---

# 📚 Concepts Covered

- Machine Learning
- Unsupervised Learning
- Principal Component Analysis (PCA)
- Feature Scaling
- StandardScaler
- Dimensionality Reduction
- Data Visualization
- Variance Preservation

---

# 🎯 Skills Demonstrated

- Machine Learning
- Data Preprocessing
- Feature Engineering
- Dimensionality Reduction
- Data Visualization
- Scikit-learn
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

- Explained Variance Ratio Analysis
- PCA on Real-World Datasets
- Compare PCA with t-SNE
- Compare PCA with UMAP
- 3D PCA Visualization
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

## 📉 Principal Component Analysis (PCA)

### Reducing Dimensions, Preserving Information

**"Simplify complex data while keeping what matters most."**

</div>
