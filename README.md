Project code: H1G8PadUW1U6dGUn

Business Objective: To predict what makes customers happy with their delivery based on their answers to a survey after receiving their order.

Data Overview: Tabular dataset with 126 records, and 7 columns, 1 column being the target Y with values indicating 0 (unhappy) and 1 (happy) customers. The other 6 columns are for the survey questions with 1 being less satisfied and 5 being more satisfied.

EDA: Classes are mostly balanced, slightly skewed towards class 1 or the positive class, about 60 to 40 ratio. X5 and X6 are skewed to the right so might be good predictors for the 1 class, X2 skewed more to the left to might be a good predictor for the 0 class. All correlations under 0.5 so no strong relationships between any of these variables

Model Results: Overall model accuracy was 76.9 %, with perfect prediction of all of the positive classes and correctly classifying over half of the negative class, which is reasonable with less samples and only the X2 variable being a good predictor of the negative class.


