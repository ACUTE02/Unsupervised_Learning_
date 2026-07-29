# 🚀 Ensemble Learning using Stacking Classifier

> **A Machine Learning project demonstrating Stacking Ensemble Learning using Decision Tree, Support Vector Machine (SVM), Logistic Regression, and K-Nearest Neighbors (KNN).**

<p align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success?style=for-the-badge)

</p>

---

# 📖 Overview

Ensemble learning improves prediction performance by combining multiple machine learning models instead of relying on a single classifier.

This project implements a **Stacking Classifier**, where three different machine learning algorithms are trained as **base learners**, and their predictions are combined using a **meta-learner** to produce the final prediction.

The project uses the Iris dataset and demonstrates how stacking can leverage the strengths of different algorithms to improve classification performance.

---

# ✨ Features

- 🌸 Iris Dataset Classification
- 🧠 Ensemble Learning
- 🔄 Stacking Classifier
- 🌳 Decision Tree Classifier
- 📈 Logistic Regression
- ⚡ Support Vector Machine (SVM)
- 🎯 K-Nearest Neighbors Meta-Learner
- 📊 Model Evaluation
- 🔄 5-Fold Cross Validation inside Stacking
- 📈 Accuracy Measurement

---

# 📂 Project Structure

```text
Stacking-Ensemble-Learning/
│
├── stacking.py
├── Stacking.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 📊 Dataset

The project uses the **Iris Dataset**, one of the most widely used benchmark datasets for multi-class classification.

### Target Classes

- Setosa
- Versicolor
- Virginica

### Input Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

# 🤖 Models Used

## Base Learners

- 🌳 Decision Tree Classifier
- ⚡ Support Vector Machine (RBF Kernel)
- 📈 Logistic Regression

Each model learns different patterns from the data.

---

## Meta Learner

The predictions from all base learners are used as input features for a **K-Nearest Neighbors (KNN)** classifier.

This second-level model learns how to combine the predictions of the base models to improve overall accuracy.

---

# 🔄 Stacking Workflow

```text
                 Dataset
                    │
                    ▼
             Train/Test Split
                    │
                    ▼
        ┌───────────┼────────────┐
        ▼           ▼            ▼
 Decision Tree     SVM     Logistic Regression
        │           │            │
        └───────────┼────────────┘
                    ▼
        Predictions from Base Models
                    │
                    ▼
          KNN Meta-Learner
                    │
                    ▼
           Final Prediction
```

---

# 📈 Cross Validation

The Stacking Classifier internally performs **5-Fold Cross Validation** (`cv=5`) while training the meta-learner.

This ensures that the meta-model learns from out-of-fold predictions rather than predictions on the same data used to train the base learners, reducing overfitting and improving generalization.

---

# 📊 Model Evaluation

The trained stacking model is evaluated using:

- Accuracy Score
- Test Set Prediction
- Model Score

---

# 🛠 Technologies Used

- Python
- Scikit-learn
- NumPy
- Pandas
- Seaborn

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Stacking-Ensemble-Learning.git
```

```bash
cd Stacking-Ensemble-Learning
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
python stacking.py
```

or open and execute:

```text
Stacking.ipynb
```

---

# 📚 Concepts Covered

- Ensemble Learning
- Stacking Classifier
- Decision Tree
- Support Vector Machine
- Logistic Regression
- K-Nearest Neighbors
- Multi-Class Classification
- Cross Validation
- Model Evaluation

---

# 🎯 Skills Demonstrated

- Machine Learning
- Ensemble Learning
- Scikit-learn
- Model Stacking
- Classification Algorithms
- Cross Validation
- Data Preprocessing
- Python Programming

---

# 📦 requirements.txt

```text
numpy
pandas
scikit-learn
seaborn
```

---

# 🚀 Future Improvements

- Add Random Forest as a base learner
- Compare with Voting Classifier
- Hyperparameter tuning using GridSearchCV
- Visualize decision boundaries
- Add confusion matrix and classification report
- Compare multiple meta-learners

---

# 👨‍💻 Author

**Ayushmaan Gupta**

B.Tech CSE (Artificial Intelligence & Machine Learning)

---

# ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork this repository
- 🤝 Contribute to improve it

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

## 🚀 Ensemble Learning using Stacking Classifier

### Combining Multiple Models for Better Predictions

**"One model is good, but a team of models is often better."**

</div>
