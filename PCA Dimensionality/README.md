# 📉 Principal Component Analysis (PCA) for Dimensionality Reduction

> **A Machine Learning project demonstrating Principal Component Analysis (PCA) using Scikit-learn for reducing high-dimensional data while preserving the most important information.**

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success?style=for-the-badge)

</p>

---

# 📖 Overview

Principal Component Analysis (PCA) is one of the most important dimensionality reduction techniques used in Machine Learning. It transforms high-dimensional datasets into a lower-dimensional space while preserving the maximum possible variance.

This project demonstrates how PCA can simplify complex datasets by reducing five original features into two principal components. Before applying PCA, the data is standardized using **StandardScaler** to ensure that all features contribute equally to the transformation.

The reduced dataset is then visualized to illustrate how PCA preserves the overall structure of the data while making it easier to analyze and visualize.

---

# ✨ Features

- 📉 Principal Component Analysis (PCA)
- 📊 Dimensionality Reduction
- ⚙️ Feature Scaling using StandardScaler
- 📈 Principal Component Visualization
- 🎨 Scatter Plot Visualization
- 🧪 Synthetic Dataset Generation
- 🚀 Scikit-learn Implementation

---

# 📂 Project Structure

```text
PCA-Dimensionality/
│
├── PCAdimension.ipynb
├── pcadimension.py
└── README.md
```

---

# 📊 Dataset

The project generates a synthetic dataset using **Scikit-learn's `make_blobs()`**.

Dataset Characteristics:

- 500 Samples
- 5 Numerical Features
- 3 Clusters
- Random State = 42

---

# 🔄 Workflow

```text
Generate Dataset
        │
        ▼
StandardScaler
        │
        ▼
Principal Component Analysis
        │
        ▼
Reduce Dimensions
(5 → 2)
        │
        ▼
Visualize Principal Components
```

---

# 🧠 What is PCA?

PCA transforms the original features into a new set of variables called **Principal Components**.

These components:

- Capture maximum variance
- Are mutually independent
- Reduce feature dimensions
- Improve visualization
- Reduce computational complexity

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

## Clone the Repository

```bash
git clone https://github.com/your-username/PCA-Dimensionality.git
```

```bash
cd PCA-Dimensionality
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
```

Activate it

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
python3 -m venv venv
```

Activate it

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

or

```bash
pip install -r requirements.txt
```

---

## Run the Project

### Python Script

```bash
python pcadimension.py
```

### Jupyter Notebook

Open

```text
PCAdimension.ipynb
```

and run all cells.

---

# 📈 Output

The project produces:

- Standardized Dataset
- Reduced Dataset (2 Principal Components)
- Scatter Plot of Principal Components

---

# 📚 Concepts Covered

- Machine Learning
- Unsupervised Learning
- Principal Component Analysis (PCA)
- Dimensionality Reduction
- Feature Scaling
- StandardScaler
- Data Visualization

---

# 🎯 Skills Demonstrated

- Data Preprocessing
- Feature Engineering
- Dimensionality Reduction
- Machine Learning
- Scikit-learn
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

- Explained Variance Ratio Plot
- PCA on Real-world Datasets
- 3D PCA Visualization
- Comparison with t-SNE
- Comparison with UMAP
- Interactive Streamlit Dashboard

---

# 👨‍💻 Author

**Ayushmaan Gupta**

B.Tech CSE (Artificial Intelligence & Machine Learning)

---

# ⭐ Support

If you found this project useful:

⭐ Star this repository

🍴 Fork this repository

🤝 Contribute to improve it

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

## 📉 Principal Component Analysis

### Transform High-Dimensional Data into Meaningful Insights

**Built with ❤️ using Python & Scikit-learn**

</div>
