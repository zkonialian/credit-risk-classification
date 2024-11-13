# credit-risk-classification

## Overview of the Analysis


In this analysis, I completed a review of various machine learning models to assess their effectiveness in predicting credit risk based on financial data. The purpose of the analysis was to determine which model could best predict whether a customer would default on a loan, thus allowing the financial institution to make informed lending decisions.

The data consisted of various financial attributes, including credit history, income, and existing debt levels. The primary prediction target was the binary outcome indicating whether a customer defaulted (1) or did not default (0).

The variables included in the analysis were:

* Loan amount (borrow is applying for)
* Annual income
* Existing debts (total debt outstanding)
* Interest rate
* Debt to income ratio
* number of accounts 

I utilized the following stages in the machine learning process:

Data preprocessing: Cleaning and preparing the data for analysis, including handling  scaling features.
Model selection: Choosing appropriate algorithms for classification, such as Logistic Regression from the skearn library.
Model training: Fitting the selected models to the training data.
Model evaluation: Assessing model performance using accuracy, precision, and recall metrics.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.



Machine Learning Model 1 - Logistic Regression:


              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.94      0.89       619

    accuracy                           0.99     19384
   macro avg       0.92      0.97      0.94     19384
weighted avg       0.99      0.99      0.99     19384


## Summary


According to this classification report, the model has a higher accuracy, however the model has .94 recall or lower recall for higher risk applicants. 
This means that the an incorrect decision could be made in approving a high risk loan, that would not be normally approved. 
The model is partially doing wnat it is supposed to do due to the slightly lower recall.
