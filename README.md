# credit-risk-classification
## Project Overview

This project aims to evaluate the performance of various machine learning models in predicting the likelihood of loan defaults. The goal is to identify the most effective model for predicting whether a loan will be paid back in full or will default, using financial information related to loans.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Results](#results)


## Dataset

The dataset used in this analysis contains financial information related to loans, including borrower details, loan characteristics, and payment status. The target variable is the loan status, where:
- `0` indicates the loan was paid back in full.
- `1` indicates the loan defaulted.

## Installation

To run this project, ensure you have the following dependencies installed:
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Results

### Model Performance
    Model	                Accuracy	Precision	Recall
    Logistic Regression	    0.85	0.87	    0.83
    Decision Tree	            0.82	0.80	    0.85
    Random Forest	            0.88	0.90	    0.86
    Support Vector Machine	    0.84	0.86	    0.82
    Gradient Boosting	    0.89	0.91	    0.87

## Best Performing Model

- Gradient Boosting: Highest accuracy (0.89), precision (0.91), and recall (0.87).
- Most reliable for predicting loan defaults.

## Conclusion

- The Gradient Boosting model is recommended due to its superior performance across all metrics.
- It provides a balanced approach in predicting both defaults and loans paid back in full.
