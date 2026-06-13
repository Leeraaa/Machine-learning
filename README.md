# Machine-learning

# Medical Mortality Prediction using Machine Learning

## Overview

This project was developed as part of the Machine Learning course at HIT (Holon Institute of Technology).

The goal of the project is to predict 5-year mortality risk based on patient clinical and laboratory data.

## Dataset

The dataset contains demographic, clinical, and laboratory features, including:

* Albumin
* ACR
* Blood pressure
* Smoking status
* Urine test indicators
* Additional medical measurements

Target variable:

* `dead_5y` (5-year mortality prediction)

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Missing Value Analysis and Imputation
3. Feature Engineering
4. Categorical Encoding
5. Class Balancing using RandomOverSampler
6. Model Training and Evaluation

## Models Evaluated

* Logistic Regression
* XGBoost
* Support Vector Machine (SVC)
* Random Forest
* K-Nearest Neighbors
* Gradient Boosting
* Decision Tree
* Perceptron
* Naive Bayes

## Evaluation Metrics

* ROC-AUC
* Classification Report
* Confusion Matrix

## Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Matplotlib
* Seaborn
