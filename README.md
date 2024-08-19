# Project 09: Bank Customer Churn Prediction

## Overview
Beta Bank is experiencing customer attrition, and they want to predict if a customer will leave soon. The bank has determined that retaining existing customers is more cost-effective than acquiring new ones. The goal is to create a model that predicts customer churn using historical data.

## Objective
- Build a classification model with an F1 score of at least 0.59 to predict whether a customer will leave the bank.
- Measure the AUC-ROC metric to compare with F1 scores.

## Workflow
1. **Preparing the Data:**
   - Import necessary libraries and datasets.
   - Preprocess the data by checking for duplicates, handling null values, and encoding categorical variables.
   
2. **Training a Model:**
   - Split the dataset into training and testing samples.
   - Train multiple classification models (Random Forest, SVM, and Logistic Regression).
   - Implement hyperparameter tuning using GridSearchCV.

3. **Rebalancing the Dataset:**
   - Use SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.
   
4. **Model Evaluation:**
   - Evaluate models using metrics such as F1 score, precision, recall, and AUC-ROC.
   - Compare the performance of the models based on the evaluation metrics.

5. **Conclusions:**
   - Draw insights based on model performance and suggest the best model for predicting customer churn.

## Requirements
This project requires the following Python packages:
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn

## Installation
You can install the necessary packages using the following command:

```bash
pip install -r requirements.txt
```
