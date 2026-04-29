# cancer-classification-ml-dl
Comparison of machine learning and deep learning models for multiclass cancer classification.

# Cancer Classification using Machine Learning & Deep Learning

## Overview

This project focuses on multiclass cancer classification using anonymized biological markers.

The objective is to predict the type of cancer from several clinical and biological features, and to compare classical machine learning models with a neural network approach.

---

## Objectives

- Train and compare multiple supervised machine learning models
- Perform hyperparameter tuning for each model
- Select the best model based on appropriate evaluation metrics
- Implement a neural network and compare its performance with classical methods

---

## Dataset

The dataset contains anonymized medical data including:

- patient age
- biological markers
- cancer type (target variable)

This is a multiclass classification problem.

⚠️ The original dataset is not shared publicly due to confidentiality and health data protection concerns.

---

## Preprocessing

A full preprocessing pipeline was implemented using:

- missing value imputation
- feature scaling
- categorical encoding
- train/test split with stratification

---

## Models Used

### Machine Learning

- Logistic Regression
- k-Nearest Neighbors (kNN)
- Random Forest
- Support Vector Machine (SVM)
- XGBoost

### Deep Learning

- Multi-Layer Perceptron (MLP) implemented with PyTorch

---

## Methods

- GridSearchCV and RandomizedSearchCV for hyperparameter tuning
- Stratified cross-validation
- Pipeline and ColumnTransformer for clean preprocessing

---

## Evaluation Metrics

- Accuracy
- Balanced Accuracy
- F1-score (macro)
- ROC-AUC (one-vs-rest)
- Confusion matrix

---

## Results

Classical machine learning models outperformed deep learning models on this dataset.

This is likely due to:
- small dataset size
- structured/tabular data

Tree-based models and SVM showed strong performance.

---

---

## Technologies

- Python
- pandas
- numpy
- scikit-learn
- XGBoost
- PyTorch
- matplotlib
- seaborn
- Jupyter Notebook

---

## Important Note

The original dataset is not shared publicly due to confidentiality and health data protection concerns.

Only code, documentation and non-sensitive outputs are included.

---

## Author

Yohaldère DURIMEL Cornelius NKRUMAH-BUADII
Master 1 Intelligence en données de santé  
Université de Strasbourg  

GitHub: https://github.com/DurimelY  
LinkedIn: https://www.linkedin.com/in/yohaldère-durimel-a78003386

## Repository Structure

cancer-classification-ml-dl/
│
├── README.md
├── requirements.txt
├── data/
├── notebooks/
├── scripts/
└── results/
