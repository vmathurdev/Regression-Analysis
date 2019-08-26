# Regression-Analysis
Regression Analysis of Wine Quality

This project involves the prediction of the rated overall quality of white wine from 11 chemical properties. The data set consists of 4,898 observations on chemical tests and sensory ratings of the wine by wine experts. The goal of the analysis is to determine whether or not the sensory ratings done by experts can be predicted from the chemical properties of wine.

The data are on Vinho Verde wines produced in northwestern Portugal. The variables in the data set are:
• Target variable:
o sensory quality (score between 0 and 10) based on the median ratings of at least 3
evaluations made by wine experts. Each expert graded the wine quality between 0
(very bad) and 10 (very excellent).
• Predictor variables:
o fixed acidity
o volatile acidity
o citric acid
o residual sugar
o chlorides
o free sulfur dioxide
o total sulfur dioxide
o density
o pH
o sulphates
o alcohol
The results of the analyses and answers to the following questions:
1. Exploratory analysis: Explore the data and discuss any issues or problems that you find.
a. Develop summary statistics on all of the variables. Check for missing values.
b. Produce histograms for each variable. Comment on the distributions.
c. Create a correlation matrix with the data and a correlogram to visualize the
correlations.
2. Regression analysis:

W I N E Q U A L I T Y A N A L Y S I S
2
a. Create training (70%) and test (30%) subsets of the wine dataframe. Set the seed
to 123. Call these wine.train and wine.test, respectively. Print the dimensions of
each of the subsets.
b. Regress sensory quality on the predictors using just the training data; call the
model reg.train.
i. Discuss and summarize the results of the regression.
ii. Which predictors are statistically significant?
iii. Should any predictors be dropped? If so, which ones and why. If you drop
any predictors, rerun the regression.
c. Create predictions using the reg.train model using the training data. Put the
predictions in train.pred.
d. Create predictions using the reg.train model using the test data. Put the
predictions in test.pred.
e. Plot the training data predictions versus the residuals from the training data.
i. Comment on the results.
f. Plot the test predictions of quality (test.pred) versus the actual quality ratings from
the test data.
i. Comment on the results.
g. Create the following performance measures using the training data and the test
data:
i. RMSE (root mean square error) for the predictions for the training data
(RMSE.training) and for the test data (RMSE.test).
ii. MAPE (mean absolute percent error) for the predictions for the training
data (MAPE training) and for the test data (MAPE
iii. Prepare a summary table comparing the results for the training and
validation data in terms of RMSE, and MAPE.
iv. Comment on the performance of the model, comparing the performance
using the training versus the test data.
