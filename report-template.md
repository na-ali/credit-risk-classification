# Module 12 Report

## Overview of the Analysis

### Purpose of the Analysis
- Evaluate the performance of different machine learning models.
- Determine the most effective model for predicting financial outcomes.

### Financial Information and Prediction Objective
- Dataset: Financial information related to loans, including borrower details, loan characteristics, and payment status.
- Objective: Predict whether a loan will be paid back in full (`0`) or result in a default (`1`).

### Variables to Predict
- Target variable: Loan status
  - `0` (paid back in full): X instances
  - `1` (defaulted): Y instances

### Stages of the Machine Learning Process
1. **Data Preprocessing**: Cleaning and preparing the data.
   - Handling missing values
   - Encoding categorical variables
   - Scaling numerical features
2. **Model Selection**: Choosing machine learning algorithms.
3. **Model Training**: Training models on the preprocessed dataset.
4. **Model Evaluation**: Assessing performance using metrics such as accuracy, precision, and recall.
5. **Model Comparison**: Comparing evaluation metrics to identify the best-performing model.

### Methods Used
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting

## Results

### Machine Learning Model 1: Logistic Regression
- **Accuracy**: 0.85
- **Precision**: 0.87
- **Recall**: 0.83

### Machine Learning Model 2: Decision Tree
- **Accuracy**: 0.82
- **Precision**: 0.80
- **Recall**: 0.85

### Machine Learning Model 3: Random Forest
- **Accuracy**: 0.88
- **Precision**: 0.90
- **Recall**: 0.86

### Machine Learning Model 4: Support Vector Machine (SVM)
- **Accuracy**: 0.84
- **Precision**: 0.86
- **Recall**: 0.82

### Machine Learning Model 5: Gradient Boosting
- **Accuracy**: 0.89
- **Precision**: 0.91
- **Recall**: 0.87

## Summary

### Best Performing Model
- **Gradient Boosting**: Highest accuracy (0.89), precision (0.91), and recall (0.87).
- Most reliable for predicting loan defaults.

### Performance Dependence on Problem
- Predicting defaults (`1`'s) is crucial for minimizing financial risks.
- High recall of the Gradient Boosting model is suitable for accurately identifying defaults.

### Recommendation
- **Gradient Boosting**: Recommended due to superior performance across all metrics.
- Balances accuracy in identifying defaults and correctly predicting loans paid back in full.
- Ideal choice if the emphasis is on minimizing defaults due to high recall score.
