# ML Foundations Notebook

This repository is a structured collection of Jupyter notebooks designed to help reinforce foundational machine learning concepts. It is ideal for  practical review and structured self-study.

Each section focuses on a key area in data science and machine learning, from statistical fundamentals to deployment basics.

---

## Topics Covered

### 1. Statistical and Probability Fundamentals

**Purpose**: Understand data distributions, hypothesis testing, and statistical reasoning.

**Key Topics**:
- Mean, variance, standard deviation, median, outliers
- Normal distribution, binomial distribution, Bayes’ theorem
- p-values, significance levels, t-tests, chi-square tests
- Correlation vs. causation

---

### 2. Data Preprocessing (Cleaning)

**Purpose**: Prepare data in a format suitable for model training.

**Key Topics**:
- Missing value imputation (MICE, KNN, mean/median)
- Outlier detection (IQR, Z-score)
- Data type conversion, label encoding, one-hot encoding
- Normalization and standardization (MinMaxScaler, StandardScaler)

---

### 3. Supervised Learning (Regression & Classification)

**Purpose**: Understand and compare prediction models.

**Key Topics**:
- Linear and logistic regression
- Decision trees, random forests, XGBoost
- SVM, KNN, Naive Bayes
- Overfitting vs. generalization

---

### 4. Model Evaluation Metrics

**Purpose**: Evaluate model performance effectively.

**Key Topics**:
- Regression: MAE, MSE, RMSE, R²
- Classification: Accuracy, precision, recall, F1-score, ROC-AUC
- Confusion matrix, cross-validation
- Improving scores with better techniques

---

### 5. Feature Engineering

**Purpose**: Improve predictive power and model interpretability.

**Key Topics**:
- Feature selection (correlation, variance, L1/L2 regularization)
- Feature creation (e.g., date → weekday, feature combinations)
- Principal Component Analysis (PCA)
- Category grouping, frequency encoding

---

### 6. Hyperparameter Tuning

**Purpose**: Optimize models and improve generalization.

**Key Topics**:
- Grid search, random search, Bayesian optimization
- Cross-validation strategies
- Early stopping, learning rate tuning

---

### 7. Model Deployment Basics

**Purpose**: Prepare models for real-world usage.

**Key Topics**:
- Model saving and loading with Pickle / joblib
- Inference via API (Flask, FastAPI)
- Model versioning and maintenance
- Input validation and error handling

---

### 8. Glossary

**Key Topics**:
- Bias-variance tradeoff
- Class imbalance and mitigation techniques
- Model interpretability (SHAP, LIME)
- Why high accuracy ≠ useful model?

---

## Setup

Install required packages:

```bash
pip install -r requirements.txt
