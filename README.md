# Car-Price-Prediction      
In the regression model, for any fixed value of X, Y is distributed in this problem data-target value (Price ) not normally distributed, it is right skewed.
To solve this problem, the log transformation on the target variable is applied when it has skewed distribution and we need to apply an inverse function on the predicted values to get the actual predicted target value.
Due to this, for evaluating the model, the RMSLE is calculated to check the error and the R2 Score is also calculated to evaluate the accuracy of the model.
