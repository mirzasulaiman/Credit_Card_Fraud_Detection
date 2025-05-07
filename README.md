
# Credit Card Fraud Detection

This project is focused on detecting fraudulent credit card transactions using various machine learning models. Due to the highly imbalanced nature of fraud detection data, the project applies preprocessing, feature selection, and model tuning techniques to improve the accuracy and reliability of the detection system.

## Project Overview

- **Objective**: Build a machine learning model to detect fraudulent transactions from a dataset of credit card activities.
- **Dataset**: [Credit Card Fraud Detection Dataset - Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Tech Stack**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn, XGBoost

## Dataset Information

- Contains transactions made by European cardholders in September 2013.
- 284,807 transactions in total.
- 492 transactions are fraudulent (highly imbalanced).
- Features are numerical and result from a PCA transformation, except for `Time`, `Amount`, and `Class`.

## Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Feature scaling
   - Balancing the dataset using techniques like SMOTE or undersampling

2. **Exploratory Data Analysis**
   - Fraud vs. Non-fraud comparison
   - Correlation matrix

3. **Model Implementation**
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - XGBoost Classifier

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
   - ROC-AUC curve

## 📈 Results

| Model              | Accuracy| ROC AUC    |      R2    | 
|--------------------|----------|-----------|------------|
| Logistic Regression| 0.993715 | 0.902001  |-0.092265   |
| Decision Tree      | 0.996526 | 0.848511  | 0.396239   | 
| Random Forest      | 0.997208 | 0.950644  | 0.5174847  | 
| XGBoost            |0.997548  | 0.988134  | 0.573816   | 




