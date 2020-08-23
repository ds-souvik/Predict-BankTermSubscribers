# Predict-BankTermSubscribers
This is a supervised classification problem to predict if the client would subscribe to a term deposit based on a marketing campaign.

## Problem Statement

### Business Use Case

There has been a revenue decline for a Portuguese bank and they would like to know what actions to take. After investigation, they found out that the root cause is that their clients are not depositing as frequently as before. Knowing that term deposits allow banks to hold onto a deposit for a specific amount of time, so banks can invest in higher gain financial products to make a profit. In addition, banks also hold better chance to persuade term deposit clients into buying other products such as funds or insurance to further increase their revenues. As a result, the Portuguese bank would like to identify existing clients that have higher chance to subscribe for a term deposit and focus marketing efforts on such clients.

### Data Science Problem Statement

Predict if the client will subscribe to a term deposit based on the analysis of the marketing campaigns the bank performed.

### Evaluation Metric
We will be using AUC - Probability to discriminate between subscriber and non-subscriber. 

### Objective of this template notebook

The main objective of this template is to take you through the entire working pipeline that was followed while appraoching a Machine Learning problem.

## The execution is divided into 2 notebooks:
1. Analysis and data processing of Bank Term Subscription past data
2. Training & testing from Past data and prediction on new data.

### Steps followed for solving the problem.
1. Understand business object.
2. Translate business objectives to Data Science problem.
3. Load the data and check the dimensions.
4. Create a data dictionary.
5. Look for null value identification.
6. Null values treatment.
7. Outlier detection.
8. EDA- Univariate.
9. EDA- Bivariate
10. Outlier treatment(Optional).
11. Convert categories to numbers:
    Label encoding/one-hot encoding.
12. Split data into train and validation sets(20:80 ratio)
13. Treat class imbalance only on training data.
14. Train ML model on training dataset.
15. Make predictions on validation dataset.
16. Compare predictions with actual values (AUC score)
17. Test points 13,14 and 15 with multiple algorithms.
18. Select the algorithm with best result for deployment.
19. Evaluate results on blind data/ future data and retrain the model if needed.
20. Present findings to stake holders 
21. Improvements.
