# churn-modelling
Churn modelling a POC


We are find out customers who are predicted to churn out of a service based organization based on their financial habits. This contains two parts of analysis 
i) EDA: We have done a rigorous EDA in order to find out data insights, columns with high correlation etc. The following data visualisation concepts were employed:
   a) Pie charts for categorical columns 
   b) Correlation of predictor variables with Response variable 
   c) Visualising correlation matrix to find out highly correlated variables thereby removing them from our model

ii) Model building through Logistic regression and prediction 
   a) Performance evaluation through confusion matrix, K fold cross validation and other related performance metrics 
   b) Recursive feature extraction to find out 20 most relevant predictors and compare the accuracy with previous model with 40 predictors
