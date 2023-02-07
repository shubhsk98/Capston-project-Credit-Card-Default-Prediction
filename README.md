
# Credit-Card-Default-Prediction

This project is aimed at predicting the case of customers’ default payments in Taiwan. From the 
perspective of risk management, the result of predictive accuracy of the estimated probability of 
default will be more valuable than the binary result of classification - credible or not credible 
clients. We can use the K-S chart to evaluate which customers will default on their credit card 
payments.

# Objective

The objective of our project is to predict which customers might default in the upcoming months.

# Dataset descriptions

1) ID: ID of each client
2) LIMIT_BAL: Amount of given credit in NT dollars (includes individual and family/supplementary credit)
3) SEX: Gender (1=male, 2=female)
4) EDUCATION: (1=graduate school, 2 = university, 3 = high school,4=others, 5=unknown, 6=unknown)
5) MARRIAGE: Marital status (1=married, 2=single, 3=others)
6) AGE: Age in years
7) PAY_0-6: History of past payments from April to September 
8) BILL_AMT1-6: Amount of bill statement from April to September 2005 (NT dollar)
9) PAY_AMT1-6: Amount of previous payment from April to September 2005 (NT dollar)
10) default.payment.next.month: Default payment (1=yes, 0=no


# Machine Learning models

Developed a classification model using algorithms such as *Logistic Regression *Decision Tree classifier *Random forest classifier *XG-Boost. All four models have good R2 and Adjusted R2. All of them in, the best accuracy has obtained from the Random Forest Classifier.

# Conclusion

1) By Visualization we have checked the distribution of defaulters vs non-defaulters and we see around 78% 
are non-defaulters and 22% are defaulters.

2) By applying Random Forest Classifier with recall 90.60%, we can predict with 87.47% accuracy whether a customer is likely to default next month.



