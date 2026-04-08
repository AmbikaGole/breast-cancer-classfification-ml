# Breast Cancer Classification & Predictive Analysis 

## Overview
This project utilizes the Wisconsin (Diagnostic) Dataset to develop a binary classification framework for identifying tumor malignancy. By applying machine learning techniques, the study aims to assist in clinical decision-making through high-precision diagnostics.

## Objectives

- Perform exploratory data analysis (EDA) to isolate key physiological features influencing diagnosis.
- Evaluate the comparative performance of Logistic Regression and K-Nearest Neighbors (KNN) in a medical context.
- Identify the most significant predictive indicators to streamline future diagnostic workflows.

## Dataset
Breast Cancer Wisconsin (Diagnostic) dataset  
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data

## Methodology

- Data Processing: Feature scaling and correlation analysis were utilized to address multicollinearity and improve model convergence.
- Modeling: Implementation of Logistic Regression and KNN via Scikit-learn.
- Optimization: Feature selection focused on minimizing false negatives, which is critical in healthcare applications.

## Key Results

- KNN Accuracy: 89%
- Logistic Regression Accuracy: 86%
- Primary Indicator: 'Concave points (worst)' was identified as the most significant feature for distinguishing malignant cases.

## Key Insights

- Clinical Application: The high correlation between 'concave points' and malignancy suggests that prioritizing these measurements can lead to faster, more reliable early-stage diagnoses.
- Feature Engineering: Model performance significantly improved through targeted feature selection, highlighting the importance of data quality over quantity in high-stakes environments like healthcare. 

## Tools Used
- Language: Python
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- Environment: Jupyter Notebook
