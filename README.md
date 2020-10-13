# CC-Fraud-Detection
Credit Card Fraud Detection from a Bank Simulated Dataset 
(utiilizing only Supervised Learning)

**Fraud Detection**

This is a simulated credit card transaction dataset created by an A.I. that has legitimate and fraudulent transactions during the span of *1st Jan 2019 - 31st Dec 2020.*
It contains the records of credit card purchases of 1000 customers doing transactions spanning from 800 different merchants.

1. trans_date_trans_time
2. cc_num
3. merchant
4. category
5. amt
6. first last (name)
7. gender
8. zip
9. lat(latitude)
10. long(longitude)
11. city_pop
12. job
13. dob(date of birth)
14. trans_num(transaction number)
15. unix_time
16. merch_lat
17. merch_long
18. is_fraud

To analyze this data, this project will employ the following techniques.
Decision Tree -- To provide fraud rules, which can be embedded into the rule engine
Logistic Regression -- Able to provide probability, such as how probable is the transaction is a fraud
XGBoost -- To mine frequent patterns out from the fraud dataset.
Classification using Frequent Patterns -- From all of the fraud and non-fraud frequent patterns, generate Association Rules, which then use it as a rule classifier model to classify fraudulent transaction.
TNSE for clustering methods
KNN clusters
