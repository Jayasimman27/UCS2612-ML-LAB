# Machine Learning Exercise 3

This directory contains the resources and datasets for the third exercise in the **“Getting Started with Machine Learning”** series.

## 📈 Supervised Learning: Regression & Regularization Techniques

In this repository, we advance into regression-based supervised learning with the goal of predicting continuous target values. Using a housing / real-estate dataset, we build and compare multiple regression models while emphasizing the role of **regularization** methods such as **Ridge**, **Lasso**, and **Elastic Net**.  
The exercise highlights how regularization helps reduce overfitting, manage multicollinearity, and perform feature selection. A strong focus is placed on constructing clean and efficient data pipelines that handle missing values and categorical features automatically.

## Repository Structure

- **EX3.ipynb**: The main Jupyter Notebook containing the complete regression pipeline, model implementations, and comparisons.
- **ML Exercise - 3.pdf**: A detailed report describing the experiments conducted and the results obtained.

## Notebook Overview (Ex-3.ipynb)

The `Ex-3.ipynb` notebook showcases a structured and scalable workflow for regression modeling:

### 1. Data Preprocessing Pipeline
- **Missing Value Treatment**: Applying `SimpleImputer` to fill missing values in both numerical and categorical features.
- **Feature Engineering**: Using `ColumnTransformer` to standardize numerical variables with `StandardScaler` and encode categorical variables using `OneHotEncoder`.
- **Pipeline Design**: Combining preprocessing and modeling steps into Scikit-Learn `Pipeline` objects for better organization and reproducibility.

### 2. Regression Models Used
- **Linear Regression**: Serving as the baseline model for comparison.
- **Ridge Regression (L2 Regularization)**: Reducing model variance and handling multicollinearity through L2 penalties.
- **Lasso Regression (L1 Regularization)**: Performing implicit feature selection by driving less important coefficients to zero.
- **Elastic Net Regression**: Integrating both L1 and L2 regularization for a balanced and flexible modeling approach.

### 3. Hyperparameter Optimization
- **GridSearchCV**: Performing a systematic search to identify optimal values for hyperparameters such as `alpha` and `l1_ratio`.
- **Cross-Validation**: Employing k-fold cross-validation to validate model performance and improve generalization on unseen data.

### 4. Model Evaluation & Analysis
- **Evaluation Metrics**: Assessing model performance using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared ($R^2$).
- **Coefficient Comparison**: Analyzing and visualizing feature coefficients across different models (Linear, Ridge, and Lasso).
- **Runtime Analysis**: Observing and comparing the execution time of various regression algorithms.
