# Credit Risk Classification

## Overview of the Analysis

The analysis aimed to develop a machine learning model to predict regular loans and high-risk loans. The purpose was to assist financial institutions in identifying loans that pose a higher risk of default or non-repayment, thus enabling better risk management practices.

The dataset used contained various financial attributes related to loan applicants, such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks,total debt, and loan status. The target variable was a binary classification indicating whether a loan was regular (low risk) or a high-risk loan.

In the machine learning process, the dataset was split into training and testing sets, and a Linear Regression model was trained on the training data. Evaluation metrics such as precision, recall, and accuracy were calculated to assess the performance of the model.

## Results
**Logistic Regression Model:**
- Precision: 
    - Class 0 (Regular loans): 1.00
    - Class 1 (High-risk loans): 0.86
    
- Recall:
    - Class 0 (Regular loans): 0.99
    - Class 1 (High-risk loans): 0.93
    
- F1-score: 
    - Class 0 (Regular loans): 1.00
    - Class 1 (High-risk loans): 0.90
    
- Accuracy: 0.99

## Summary

The Linear Regression model achieved high precision and recall scores for both regular loans and high-risk loans, indicating its effectiveness in distinguishing between the two classes. The model's high accuracy suggests that it performs well overall in classifying loans.

## Technologies Used
- [Python 3.10 or higher](https://www.python.org/)
- [NumPy](https://www.numpy.org)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/stable/index.html)
