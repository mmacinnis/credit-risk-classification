
## Overview of the Analysis

The purpose of this analysis was to use machine learning to predict loan risk. Training data was taken from previous lending activity, such as: 

* Loan size
* Interest rate
* Borrower income
* Debt to income ratio
* Number of accounts
* Derogatory marks
* Total debt

With the goal of predicting loan default.

 A logistical regression analysis was used, trained on a subset of the data and then compared to a separate testing portion of the data. In this way we could judge how well it predicted the values in the testing subset, and thus how well our model would work on real-world data.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Model: Logistical Regression
* Accuracy: 99%
* Precision: 100% for healthy loans; 87% for high-risk
* Recall: 100% for healthy loans; 89% for high-risk 
* F1 score: 100% for healthy loans; 88% for high-risk 



## Summary

With excellent F1 scores in both categories, I would suggest this model for use. Its accuracy would indicate we aren't leaving money on the table by rejecting too many good applicants, and protecting ourselves from risk with a minimum of work. That saved time could be devoted to human review of "decisions" "made" by the model. This data was a bit lopsided, which is a weakness, so implementation of this model would be subject to review in 90 days from implementation. The model itself can, of course, be continually updated and trained with the latest data available.