# Machine Learning Exercise 6

This directory contains the implementation and report for Exercise 6 of the **Machine Learning Laboratory**, focusing on tree-based classification methods.

## 🌳 Binary Classification: Decision Tree & Random Forest

This exercise applies **Decision Tree** and **Random Forest** classifiers on the Wisconsin Diagnostic Breast Cancer Dataset to classify tumors as **Malignant** or **Benign**.

The experiment evaluates how hyperparameters such as tree depth, number of estimators, and feature selection affect performance. Random Forest improves generalization by combining multiple Decision Trees and reducing overfitting.

Cross-validation and evaluation metrics are used to compare both models.

---

## Repository Contents

- **EX6.ipynb** – Jupyter Notebook containing model implementation and evaluation  
- **EXPERIMENT_6_Latex file.tex** – LaTeX source for the experiment report  
- **EXPERIMENT_6.pdf** – Final compiled report  
- **wdbc.data** – Dataset used for training and testing  
- **dt_confusion_matrix.png** – Decision Tree confusion matrix  
- **rf_confusion_matrix.png** – Random Forest confusion matrix  
- **roc_curve.png** – ROC curve comparison  

---

## Workflow Overview

### 1. Data Preparation
- Load and clean dataset  
- Encode target labels  
- Split into training and testing sets  

### 2. Model Training
- Train Decision Tree classifier  
- Train Random Forest classifier  
- Perform hyperparameter tuning using 5-fold cross-validation  

### 3. Evaluation
- Accuracy, Precision, Recall, F1-score  
- Confusion Matrix  
- ROC Curve and AUC  

---

## Conclusion

Random Forest achieved higher accuracy and better generalization compared to Decision Tree, demonstrating the effectiveness of ensemble learning for classification tasks.