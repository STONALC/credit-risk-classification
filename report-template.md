# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to predict the risk level of  contracted by external parties. 
In pstyivulst, the analysis categorizes the loans as either (i) healthy or (ii) high-risk. 
This classification is necessary for the bank not only to assess but also to manage risk and make informed decisions about how much to lend,
whom to lend and when to lend. 


* Explain what financial information the data was on, and what you needed to predict.

The data contained such financial information as the loan amount and interest rate, income levels of borrowers, and other relevant financial 
information needed to predict  whether a particular loan is healthy or high-risk. 


* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

I was working to predict two variables: healthy loans and high-risk loans. For purposes of this exercise,
I represent the healthy loan as variable X and the high-risk loan as variable Y.

* Describe the stages of the machine learning process you went through as part of this analysis.

I went through three basic stages of machine learning to perform the analysis. These stages are:
(i) data processing which included cleaning the data and handling missing values or variables; and
(ii) selecting the relevant parameters for the prediction;
(iii) model training or evaluation which involves the use of standards such as accuracy, precision and recall.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy score is 0.82 or 82%, Precision score is 0.85 or 85% for heallthy loans and 0.78 or 78% for high-risk loans, while 
    Recall scores are 0.90 or 90% for healthy loans or 0.70 or 70% for high-risk loans.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best? The Logistic Regression model seems to perform best. This conclusion is based on the accuracy, precision, recall scores. It presents 
a very good balance in predicting both healthy loans and high-risk loans.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Yes, performance depends on the problem we are trying o solve. Assuming that it is more important to identify high-risk loans with greater accuracy, 
the logistic regression will serve the purpose as it provides a good balance between healthy and high-risk loans.

If you do not recommend any of the models, please justify your reasoning. I recommend these models as either of them will provide the necessary predictions.
