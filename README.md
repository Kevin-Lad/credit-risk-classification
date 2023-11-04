# credit-risk-classification
* This is the module 20 assignment for bootcamp, which focuses on training a model based on loan risk. The dataset is made up historical data of lending activity from a lending services company. 

## Credit Risk Analysis


* The purpose of this analysis is to determine the credit worthiness of borrowers. I have been provided with financial information on the borrowers and built a model based off of that information to see if the borrower is a credit risk.

* The financial information that was provided is as follows: the size of the loan, the interest rate, the borrowers income, the debt to income ratio, the number of accounts the borrower has, the number of derogatory remarks on their credit report, and the borrowers total debt. I am analyzing this information to predict the borrowers loan status, this is divided into 2 categories, 0 and 1. 0 means a good loan, 1 is at a high risk for defaulting on the loan.  

* The dataset has information on a total of 77,536 loans. 2,500 of those loans are high risk, and 75,036 are healthy loans. 

* The steps in the machine learning process that I used here are the following: preprocess the data, train the model, validate the model and finally predict the outcome. 

* For this problem, I used a logistic regression model, which is a statistical method for predicting a binary outcome from the data.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model:
  *  Accuracy: This model is 99 percent accurate.
  *  Precision: The model predicts healthy loans 100 percent of the time and high-risk loans 87 percent of the time.
  *  Recall : Thej recall for healthy loans is also 100 percent and high-risk loans is 89 percent.


## Summary

Summarize the results of the machine learning model. For example.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) Here we are trying to analyze the credit worthiness of a borrower. This model predicts 100 percent of the time when a borrower will repay a healthy loan. This model is outstanding for healthy loans, you can't get better than 100 percent, so I recommend this for a healthy loan. On the other hand, 87 percent of the time, this model predicts when a high-risk loan would be paid back. 87 percent seems pretty good for most real life situations. In this case though, that means the model is wrong 13 percent of the time. When it comes to lending out money, I don't think that being wrong 13 percent of the time is good enough, so I do not recommend this model.


