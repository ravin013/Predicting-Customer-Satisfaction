## Project Code: 
H1G8PadUW1U6dGUn

# Project Name: 
Predicting Customer Satisfaction

## Project Overview: 
To predict what makes customers happy with their delivery based on their answers to a survey after receiving their order. The data is tabular with 126 records, and 7 columns, 1 column being the target Y with values indicating 0 (unhappy) and 1 (happy) customers. The other 6 columns are for the survey questions with 1 being less satisfied and 5 being more satisfied.

# Exploratory Data analysis Findings: 
Classes are mostly balanced, slightly skewed towards class 1 or the positive class, about 60 to 40 ratio. X5 and X6 are skewed to the right so might be good predictors for the 1 class, X2 skewed more to the left to might be a good predictor for the 0 class. All correlations under 0.5 so no strong relationships between any of these variables

# Machine Learning model used: 
Model was logistic regression with an accuracy of 76.9 %, with perfect prediction of all of the positive classes and correctly classifying over half of the negative class, which is reasonable with less samples and only the X2 variable being a good predictor of the negative class.

# Conclusion: 
A bigger sample size is needed to create a more robust model that can classify both the negative and positive class with high accuracy. With a small sample size, a simpler model works well along with picking features that skew towards 1 or more towards 5 as those will be a better indicator if a customer is satisfied.
