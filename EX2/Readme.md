# Machine Learning Exercise 2

This directory contains the resources and datasets for the second exercise in the **“Getting Started with Machine Learning”** series.

## 📊 Supervised Learning: Classification & Model Assessment

In this repository, we move beyond exploratory analysis and step into the process of building and evaluating predictive models. Leveraging the **Spambase** dataset, we develop a **Bernoulli Naive Bayes** classifier to detect spam emails.  
This exercise emphasizes the end-to-end supervised learning workflow, including data preprocessing, feature normalization, model training, and thorough evaluation using standard classification metrics such as Precision, Recall, and F1-Score.

## Repository Contents

- **EX2.ipynb**: The primary Jupyter Notebook containing the complete implementation and analysis for this exercise.
- **ML_EX2**: A report document summarizing the experiment and results obtained.

## Dataset Description

The `datasets` directory includes the main dataset used for spam classification:

- **spambase_csv_Kaggle.csv**:  
  A dataset with **4,601 samples** and **57 input features**, where each feature represents word or character frequency information from emails. Each instance is labeled as either spam (`1`) or non-spam (`0`).

## Notebook Overview (Ex-2.ipynb)

The `Ex-2.ipynb` notebook walks through a complete classification pipeline focused on email spam detection:

### 1. Data Exploration & Validation
- **Dataset Loading**: Importing the data and checking its shape (4601 rows × 58 columns).
- **Data Integrity Check**: Ensuring the dataset contains no missing or null values.
- **Statistical Summary**: Reviewing descriptive statistics such as mean, standard deviation, and value ranges for frequency-based features.

### 2. Preprocessing & Feature Preparation
- **Normalization**: Applying `StandardScaler` to standardize numerical features for improved model performance.
- **Train-Target Split**: Dividing the dataset into input features (`X`) and output labels (`y`) in preparation for training.

### 3. Model Development
- **Bernoulli Naive Bayes Classifier**: Using the `BernoulliNB` algorithm from Scikit-Learn, well-suited for binary classification problems involving discrete or frequency-based data.

### 4. Model Evaluation & Visualization
- **Performance Metrics**: Calculating Accuracy, Precision, Recall, and F1-Score to assess classification effectiveness.
- **Confusion Matrix**: Visual representation of True Positives, True Negatives, False Positives, and False Negatives.
- **Learning Curves**: Plotting training and validation accuracy against varying training set sizes to study generalization behavior and detect overfitting or underfitting.

