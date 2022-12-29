# Credit-Fraud-Detection
The Credit Card Fraud Detection Dataset in Kaggle could be amongst the most complex Dataset available.
One, owing to the fact that the class has an imbalance ratio between the fraudlent transactions which are only
0.172% of all the trasnactions and the transaction classfied as Valid.
Out of 284,807 transactions only 492 transactions are flagged as fraudulent.

In this notebook I have used two algotrithm to solve this classification Problem
in orderto perform anomaly detection on the Dataset:
1. Isolation Forest Algorithm
2. Local Outlier Factor Algorithm

In the notebook, I have only used 10% as the sample dataset, reason for this is that,
the whole dataset would require high processing capability and also require more time to
generate results.
The Support Vector Machine (SVM) Algorithm would also be ideal for this problem, however,
it would taks a considerable amount if time to compute the outliers, 
especially given the enormorse size of the Dataset.

To improve the results, one would also increase the sample size from maybe 10% used here
to say 30%, that would improve the prediction results.

As it is,the Isolation Forest Algorithm has outperformed the Local Outlier Factor Algorithm,
given that the latter has a precision rate of 0.02%, while,IFA has a precision rate of 0.28%.
