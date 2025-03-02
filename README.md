# Credit Card Fraud Detection and Analysis

This project develops a machine learning model to detect fraudulent credit card transactions using historical transaction data. The model analyzes transaction patterns and classifies them as fraudulent or not, helping reduce risks and improve the security of digital payments.

## Overview

As the volume of digital payments continues to rise, detecting fraudulent transactions has become increasingly challenging. Fraudsters exploit vulnerabilities in payment systems, and machine learning models are used to identify anomalous behaviors to reduce these risks. This project focuses on leveraging machine learning algorithms to detect and classify fraudulent credit card transactions.

## Problem

The rise of digital payments has led to a corresponding increase in fraudulent transactions. Traditional fraud detection systems may not be efficient enough to handle the high volume and complexity of transactions. Machine learning can play a significant role in identifying suspicious activities by analyzing transaction patterns and recognizing anomalies that signal potential fraud.

## Approach

### Dataset
- **Size**: 1,000,000 rows
- **Features**: 7 independent features representing transaction details
- **Target**: 1 dependent feature representing fraud labels (fraud or not fraud)

### Modeling
Five different machine learning algorithms were implemented for detecting fraud:

1. **Logistic Regression**
2. **Decision Trees**
3. **Random Forest**
4. **K-Nearest Neighbors (KNN)**
5. **Support Vector Machine (SVM)**

A data poisoning attack was applied to the SVM classifier, resulting in a slight reduction in accuracy from 95% to 94.33%. The impact of this attack was analyzed to demonstrate the robustness of the models.

### Data Poisoning Attack
- The data poisoning attack was aimed at degrading the performance of the SVM model by injecting misleading data points into the training set, resulting in a slight decrease in accuracy.

## Results

- **Highest Accuracy**: 99.999% achieved with the **Random Forest** model.
- The model can predict whether a transaction is fraudulent with high accuracy, offering significant improvements in fraud detection for credit card transactions.

## Tools and Technologies

- **Python**: Used for implementing machine learning models and data processing.
- **Scikit-learn**: Library used for building machine learning models.
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib/Seaborn**: Used for visualizing the data and model performance.


