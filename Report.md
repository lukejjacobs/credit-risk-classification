## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis was to determine if we were able to make a ML algorithm to predict loan status.
* Explain what financial information the data was on, and what you needed to predict.
The data had a few things for example: loan size, interest rate, borrower income, debt to income, # of account, derogatory marks and total debt.
* Describe the stages of the machine learning process you went through as part of this analysis.
I split the data into target and label to make sure we can try and predict loan status. Then we split both the X and y in training and test data so we can test how good our model is. Then we created and fitted our logistic regression model with the training data. After we predicted to determine how accurate our data is.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Our accuracy is nearly perfect with a 99% score.
    * Our weighted precision is very high with 99% but it was 84% with high risk cases which is good but not as accurate as healthy cases.
    * Our recall is really high for both cases with 99% for healthy and then 94% with high risk cases.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
The model did very good and I would recommended to use it.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
I would say it is more important to predict the high risk cases becauses we would not want risky cases to get approved. The reason for this is we don't want to have too manyrisky cases to go through and have the market crash like it did in 2008.