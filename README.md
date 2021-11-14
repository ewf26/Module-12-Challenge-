# Module-12-Challenge-

## Overview of the Analysis

* The purpose of this analysis is to improve the identification of high risk loans. 
* The analysis is based on loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. 
* We are trying to predict whether a loan is classified as high risk or healthy. 
* First I split the data into training and testing sets. Then I created a logistic regression model with the original data. After assessing the accuracy, I made a new model that oversampled the data. The oversampled data provided more accurate predictions. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Balanced Accuracy: 0.9919521254643004, Macro Precision: .93, Macro Recall: .95



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Balanced Accuracy: 0.9946255663142933, Macro Precision: .99, Macro Recall: .99

## Summary


The second model with oversampled data performs best. In the first model, there was not enough data to accurately predict high risk loans. With the oversampled data, the model is much better at predicting riskier loans which is the goal of the project. 
