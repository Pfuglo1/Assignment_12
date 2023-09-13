# Module 12 Report Template

## Overview of the Analysis


The primary objective of this analysis was to leverage customer information for determining the health status of loans within a peer-to-peer lending company.

The dataset used included loan and borrower information, encompassing loan size, interest rate, income, debt-to-income ratio, account count, presence of derogatory marks, and loan status, represented as binary values (0 for healthy loans and 1 for unhealthy loans).

The dataset contained 75,036 instances of healthy loans (0) and 2,500 instances of unhealthy loans (1). To facilitate analysis, we split the customer data into variable X and the binary loan status into variable y. Subsequently, we used the test_train_split function to prepare the data for linear regression analysis using the sklearn library.

After fitting the model and utilizing the predict function, we successfully developed a classification model with commendable performance.

In an effort to enhance model performance, we addressed the class imbalance issue by oversampling the data and repeated the same analytical procedures.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
  * Accuracy  0.9218124642767772

  * Precision 
      - 0 1.00 
      - 1 0.85
  * Recall 
      - 0 0.99
      - 1 0.91



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
  * Accuracy 0.9205494133884273
  
  * Precision 
      - 0 0.99
      - 1 0.99
  * Recall 
      - 0 1.00
      - 1 0.84


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* In summary, both machine learning models have demonstrated strong performance in classifying healthy (0) and unhealthy (1) loans. While Model 1 achieved a slightly higher balanced accuracy score, Model 2 exhibited more balanced precision and recall scores across both classes.
* It is definitely more important to properly identify the 1 as they represent the unhealthy loans

If you do not recommend any of the models, please justify your reasoning.
