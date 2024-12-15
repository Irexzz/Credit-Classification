# Credit-Classification
A machine learning project to predict the likelihood of customers defaulting on their payments next month.
# Description
This project focuses on building and evaluating classification models to predict whether a customer will default on their payment in the next month. The dataset includes financial and demographic information about customers, and the target variable is binary:

  0: Customer will not default.
  
  1: Customer will default.
  
The goal is to help financial institutions assess credit risk more effectively and make informed decisions about lending and credit limit adjustments.
# Features
Implementation of multiple classification algorithms, including:
  1. Logistic Regression
  2. K Neighbors
  3. Random Forest
  4. SVC
  
Data preprocessing: Handling missing values, feature scaling, and encoding categorical variables.

Model evaluation using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

Feature importance analysis to identify key factors influencing credit scores.
# Dataset 
Features:
 1. Age
 2. Marriage Status
 3. Education
 4. Gender
 5. Credit Limit
 6. Bill Amt 1-3
 7. Pay Amt 1-3
    
Target Variable:
  1. Default payment next month: Binary (0, 1)
# Results
Tested with every algorithm used. Explaination can be found in notebook

Overall, best model is KNN as it can predict 1s unlike logistic regression. It's accuracy was also able to increase after tuning.
