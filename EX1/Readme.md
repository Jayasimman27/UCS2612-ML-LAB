# Machine Learning Exercise 1

This directory contains resources and datasets for the first hands-on exercise in the **“Getting Started with Machine Learning”** series.

## 📈 Introduction to Machine Learning Basics

In this repository, we dive into the foundational concepts of Machine Learning through practical experimentation using core Python libraries such as **NumPy**, **Pandas**, and **Matplotlib**. The primary emphasis is on understanding data before modeling—covering tasks like data cleaning, transformation, and visualization. These steps are essential for gaining insights into datasets and building intuition about patterns, trends, and relationships that Machine Learning models rely on.  
This repository is intended as a sandbox environment where learners can practice, explore, and gradually progress toward more advanced ML techniques.

## Repository Structure

- **[Ex-1.ipynb](EX1.ipynb)**: The main Jupyter Notebook that contains all code implementations and analysis for this exercise.
- **[ML Exercise-1.pdf](ML_EX1.pdf)**: A reference document explaining the problem statements, guidelines, and theoretical concepts related to the exercise.


## Datasets Overview

The `datasets` directory includes multiple CSV files utilized for exploratory analysis.

**Note on the Handwritten Characters Dataset:**  
The complete *English Handwritten Characters Dataset* can be downloaded from the following link:  
[Download English Handwritten Characters Dataset](https://www.kaggle.com/api/v1/datasets/download/dhruvildave/english-handwritten-characters-dataset)

Additional datasets provided:
- `Iris.csv` – A well-known dataset for flower classification.
- `loan_train.csv` – Training data used for loan approval analysis.
- `english.csv` – Metadata related to handwritten character images.
- `diabetes.csv` – Medical dataset for diabetes-related analysis.
- `email.csv` – Dataset used for spam vs non-spam email classification.

## Notebook Overview (Ex-1.ipynb)

The notebook focuses on **Exploratory Data Analysis (EDA)** across multiple real-world datasets:

1. **Loan Amount Analysis**
   - **Initial Exploration**: Loading `loan_train.csv`, examining dataset dimensions, data types, and missing values.
   - **Descriptive Statistics**: Summary statistics for numerical attributes.
   - **Visual Analysis**: Histograms, boxplots, scatter plots, categorical bar charts, and correlation heatmaps.

2. **Iris Dataset Exploration**
   - **Dataset Inspection**: Loading `Iris.csv` and reviewing its structure and statistics.
   - **Visualization**: Feature-wise histograms, species-based boxplots, pairwise plots, and correlation heatmaps.

3. **Handwritten Character Analysis**
   - **Dataset Loading**: Using `english.csv` which maps image paths to character labels.
   - **Visualization**: Studying label frequency distribution and displaying sample character images.

4. **Diabetes Data Exploration**
   - **Data Understanding**: Loading `diabetes.csv` and analyzing health-related features.
   - **Feature Analysis**: Examining attributes relevant to diabetes prediction.

5. **Email Spam Classification**
   - **Data Inspection**: Loading `email.csv` containing labeled email text.
   - **Preliminary Analysis**: Exploring the dataset for spam detection tasks.

## How to Begin

1. Open `Ex-1.ipynb` using a Jupyter-compatible environment such as **JupyterLab**, **Google Colab**, or **VS Code**.
2. Make sure the required Python libraries are installed: `numpy`, `pandas`, `matplotlib`, and `seaborn`.
3. Execute the notebook cells sequentially and follow the instructions provided to complete the analyses.
