# Machine Learning Exercise 5

This directory contains the implementation and report for Exercise 5 of the **Machine Learning Laboratory**, focusing on neural network–based classification.

## 🔤 Handwritten Character Recognition: PLA vs MLP

This experiment compares the performance of the **Perceptron Learning Algorithm (PLA)** and a **Multilayer Perceptron (MLP)** on the English Handwritten Characters Dataset.

PLA is implemented from scratch using the One-vs-Rest strategy, while MLP is implemented using TensorFlow with hidden layers and nonlinear activation functions. The goal is to show the limitation of linear classifiers and the advantage of neural networks in solving nonlinear classification problems.

---

## Repository Contents

- **EX5.ipynb** – Implementation and evaluation code  
- **EXPERIMENT_5.pdf** – Final experiment report  
- **english.csv** – Dataset file  
- **Img/** – Handwritten character images  

---

## Workflow Overview

### 1. Data Preparation
- Load and preprocess images  
- Normalize and flatten images  
- Encode labels and split dataset  

### 2. Model Training
- Implement PLA using One-vs-Rest  
- Train MLP using TensorFlow  
- Tune hyperparameters  

### 3. Evaluation
- Accuracy, Precision, Recall, F1-score  
- Performance comparison between PLA and MLP  

---

## Conclusion

MLP achieved significantly higher accuracy than PLA, showing that neural networks are more effective than linear classifiers for handwritten character recognition.