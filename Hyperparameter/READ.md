# 🔍 Machine Learning Model Selection using GridSearchCV & RandomizedSearchCV

> **Hyperparameter Tuning • Cross Validation • Scikit-learn Pipelines • Model Selection**

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success?style=for-the-badge)

</p>

---

# 📖 Overview

Choosing the right machine learning model is only part of building an effective predictive system. Selecting the optimal hyperparameters is equally important for achieving the best performance.

This project demonstrates **model evaluation** and **hyperparameter optimization** using the Iris dataset. It compares **Support Vector Machine (SVM)** and **K-Nearest Neighbors (KNN)** classifiers through **5-Fold Cross Validation**, **GridSearchCV**, and **RandomizedSearchCV**.

To prevent data leakage and ensure fair evaluation, feature scaling is integrated into Scikit-learn **Pipelines** before performing cross-validation and hyperparameter tuning.

---

# ✨ Features

- 🌸 Iris Dataset Classification
- 🔄 5-Fold Cross Validation
- ⚙️ GridSearchCV
- 🎲 RandomizedSearchCV
- 🚀 Scikit-learn Pipelines
- 📊 Hyperparameter Optimization
- 📈 Model Comparison
- 🔍 Performance Evaluation
- 🛡️ Data Leakage Prevention

---

# 📂 Project Structure

```text
GridSearchCV-Model-Selection/
│
├── grid_search_cv.py
├── grid_search_cv.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset

The project uses the **Iris dataset**, a popular benchmark dataset available in Seaborn.

### Target Classes

- Setosa
- Versicolor
- Virginica

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

# 🧠 Machine Learning Workflow

```text
Load Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Pipeline Creation
      │
      ▼
Cross Validation
      │
      ▼
GridSearchCV
      │
      ▼
RandomizedSearchCV
      │
      ▼
Best Hyperparameters
      │
      ▼
Optimized Model
```

---

# 🤖 Models Used

## Support Vector Machine (SVM)

Hyperparameters tuned:

- C
- Kernel
- Gamma

---

## K-Nearest Neighbors (KNN)

Hyperparameters tuned:

- Number of Neighbors
- Distance Metric
- Weight Function

---

# 🔄 Cross Validation

The project evaluates models using **5-Fold Cross Validation**.

Each model is trained five times using different train-validation splits, and the average accuracy is reported for a more reliable estimate of model performance.

---

# ⚙️ GridSearchCV

GridSearchCV performs an exhaustive search over all specified hyperparameter combinations.

Example:

```text
Kernel:
- Linear
- RBF

C:
- 1
- 10
- 20
- 30

Gamma:
- scale
- auto
```

Every possible combination is evaluated, and the configuration with the highest cross-validation accuracy is selected.

---

# 🎲 RandomizedSearchCV

RandomizedSearchCV samples a fixed number of random hyperparameter combinations instead of evaluating every possible one.

Benefits:

- Faster execution
- Reduced computational cost
- Efficient for large search spaces

---

# 🚀 Pipeline

Feature scaling is automatically applied before model training using Scikit-learn Pipelines.

Algorithms requiring scaling:

- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Pipeline ensures that scaling occurs **inside each cross-validation fold**, preventing data leakage.

---

# 📈 Results

The project reports:

- Mean Cross Validation Accuracy
- Best Hyperparameters
- Best Model Accuracy
- Training Scores
- Testing Scores
- Complete Search Results

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
git clone https://github.com/your-username/GridSearchCV-Model-Selection.git
```

```bash
cd GridSearchCV-Model-Selection
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

---

## Run the Project

```bash
python grid_search_cv.py
```

or

Run the notebook:

```text
grid_search_cv.ipynb
```

---

# 📚 Concepts Covered

- Machine Learning
- Classification
- Cross Validation
- Pipeline
- Feature Scaling
- Hyperparameter Tuning
- GridSearchCV
- RandomizedSearchCV
- Model Selection

---

# 🎯 Skills Demonstrated

- Machine Learning
- Model Evaluation
- Hyperparameter Optimization
- Scikit-learn Pipelines
- Classification Algorithms
- Data Preprocessing
- Cross Validation
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

- Add Decision Tree & Random Forest
- Bayesian Hyperparameter Optimization
- Optuna Integration
- XGBoost Comparison
- Interactive Streamlit Dashboard
- Performance Visualization

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

This project is licensed under the **MIT License**.

---

<div align="center">

### 🚀 Machine Learning Model Selection & Hyperparameter Tuning

**Built with Python & Scikit-learn**

*"Better hyperparameters lead to better models."*

</div>
