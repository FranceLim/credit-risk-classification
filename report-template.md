# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. 

The purpose of this analysis was to see if the logistic regression model was useful in predicting from the dataset. The specific goal was to see whether a long as a potential high risk loan. The data pertained to financial loans. For the machine learning process, I used train_test_split, created a logistic regression model, fit the data, and then make predictions. 


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

  Machine Learning Model 1:
  Description of Model 1 Accuracy: .9919
  
  Healthy
    Precision: 1.00
    Recall score: .99
    f1-score: 1.00

  High Risk
    Precision: 0.85
    Recall score: 0.91
    f1-score: 0.88


  Machine Learning Model 2:
  Description of Model 2 Accuracy:. 9965
  
  Healthy
    Precision: 1.00
    Recall score: .99
    f1-score: 1.00

  High Risk
    Precision: 0.84
    Recall score: 0.99
    f1-score: 0.91


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. 

The logstic regression model worked very well for the healthy loans (Precision: 1.00). However, it was not as accurate for the high risk loans. That being mentioned, the scores were not horrible, just not as accurate as the healthy loans. Overeall, the model does a good job of predicting outcomes of loans. 
