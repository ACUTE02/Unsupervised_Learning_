## 🔄 Cross Validation

To obtain a more reliable estimate of model performance, the project uses **5-Fold Cross Validation**.

Cross Validation divides the dataset into five equal parts. During each iteration:

- Four folds are used for training.
- One fold is used for validation.
- The process repeats five times so every sample is tested exactly once.

The average accuracy across all folds provides a more robust performance metric compared to relying on a single train-test split.

### Models Evaluated

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Gaussian Naive Bayes
- Support Vector Machine (SVM)

### Pipeline

Feature scaling is required for algorithms such as:

- KNN
- SVM

To prevent **data leakage**, the project uses Scikit-learn's **Pipeline**, ensuring that the `StandardScaler` is fitted only on the training fold during each cross-validation iteration.

```python
svm_pipeline = Pipeline([
    ('scaler', StandardScaler()),
    ('SVM', model_SVM)
])

score = cross_val_score(
    svm_pipeline,
    X,
    y,
    cv=5,
    scoring='accuracy'
)
```

This approach produces more reliable and unbiased model evaluation.
