# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis was to create a machine learning algorithm that could identify if a loan will be healthy or high risk. 
* The financial inofrmation used contained many features such as loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, total debt, and loan status. Loan status had all healthy loans denoted as a 0 and all high risk loans were denoted with a 1.
* The first step was to read the csv file containing the financial information into a dataframe on jupyter notebooks. After that, I seperated the loan_status collumn and then dropped it from the rest of the dataframe. I saved the loan_status collumn as y, and the remaining data set as X.
* I then did a train_test_split method which sperates 80% of the data into training data and 20% for testing.
* After this we used a logisticregression model to work with our split data. We then fit the dats, and predicted the data.
* Finally, I used a confusion matrix to review the accuracy of the model. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
* the model had an accuracy score of 99%
* the model had a precision of 100 for the healthy loan and 86 for high risk loans. This means that of the ones it thought were healthy loans, 100% were, and of the ones it thought were high risk, 84% of them were true positives.
* The recall was also high at 99% for healthy loans and 94% for high risk loans. This means 99% of all true positives were found by the model in regards to healthy loans. And for high risk, 94% of all true positives were found by the model. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* I recomend using the model to predict if a loan will be healthy because the precision and recall were both extremely high. I still think that it would be a good idea to use the part of the model that predicted the 1s as a supplementry tool in determining if a loan will be high risk. 

If you do not recommend any of the models, please justify your reasoning.
