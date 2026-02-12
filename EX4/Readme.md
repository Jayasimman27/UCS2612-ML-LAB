# Machine Learning Exercise 4

This directory contains the resources and datasets for the fourth exercise in the **“Getting Started with Machine Learning”** series.

## 📧 Binary Classification: Logistic Regression & Support Vector Machines

In this repository, we concentrate on binary classification methods for identifying spam emails using **Logistic Regression** and **Support Vector Machines (SVM)**.  
The exercise explores how choices such as feature scaling, kernel functions, and hyperparameter optimization affect model performance. Multiple SVM kernels are evaluated to understand both linear and non-linear decision boundaries, while cross-validation is used to measure how well models generalize to unseen data.

## Repository Contents

- **Ex-4.ipynb**: The primary Jupyter Notebook containing implementations of Logistic Regression and SVM-based classifiers.
- **ML_EX4.pdf**: A report documenting the experimental setup, observations, and results.

## Notebook Overview (Ex-4.ipynb)

The `EX4.ipynb` notebook presents an end-to-end workflow for building and evaluating binary classification models:

### 1. Data Preparation
- **Missing Value Checks**: Identifying and handling incomplete or inconsistent entries.
- **Feature Normalization**: Applying `StandardScaler` to standardize numerical features.
- **Dataset Splitting**: Creating training, validation, and test sets to enable tuning and unbiased evaluation.

### 2. Classification Models
- **Baseline Logistic Regression**: Serving as a reference model for comparison.
- **Optimized Logistic Regression**: Enhancing performance using regularization and hyperparameter tuning.
- **Support Vector Machines**: Training SVM models with linear, polynomial, RBF, and sigmoid kernels.

### 3. Hyperparameter Optimization
- **RandomizedSearchCV**: Efficiently sampling hyperparameter combinations for both Logistic Regression and SVM.
- **Cross-Validation**: Using 5-fold cross-validation to evaluate model stability and robustness.

### 4. Evaluation & Analysis
- **Performance Metrics**: Assessing Accuracy, Precision, Recall, and F1-score.
- **Confusion Matrix Visualization**: Analyzing misclassifications for each model.
- **ROC Curves & AUC Scores**: Comparing the discriminative power of different classifiers and kernels.
- **Learning Curves**: Examining bias–variance trade-offs as training data size increases.
- **Runtime Comparison**: Observing the computational cost of each model.
