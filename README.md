# Linear-Regression
- Linear Regression tends to establish a relationship between a dependent variable(Y) and one or more independent variable(X) by finding the best fit of the straight line.
- The equation for the Linear model is Y = mX+c, where m is the slope and c is the intercept.

![0_Y_wKuvGOCaoUQKeJ](https://user-images.githubusercontent.com/84494071/132179703-d4c7c819-b03a-4414-971e-fa69f1a9fa24.png)

# Where we can apply linear regression ?
- Linear regression only for regression problem statement where we have continuous output.

# What are the assumptions associated with a linear regression ?
- The relationship between X and Y must be linear.
- Yes to Homoscedasticity, No to Hetroscedasticity.
- No Multicollinearity.
- No Auto Regression.
- Zero residual mean.

# Note:
- If all condition satisfied, then only we can use this linear regression.
- if input features are one we call that, simple linear regression model.
- if input features are more than 1 we call that as multiple linear regression model.
- linear regression is a parametric model, where we are getting M and C values.
- If model is overfitting means low bias high verience, we need to perform regularization like Ridge, Lasso and Elastic Net.
- If model is underfitting, then we need to boost our algorithmns to learn better, for that we go with Optimizers like Gredient Decent.
- This is the scenarios for over fitting and under fitting

![download](https://user-images.githubusercontent.com/84494071/132234266-5872a32f-90d5-40d7-9604-1b33c80db281.png)




# How to check all assumptions are true or not ?
- For Linearity check we can plot scatter plot.
- For multicollinearity, we can check with VIF score.So if values are in range b/w 0 to 5 then there is no multicollinearity, if values are 5 to 10 then there is but we can take those attributes for prediction.If values are more than that, we can't take those input features, better to remove the features which is having multicollinearity.

# Python Implementation of linear regression:
- https://github.com/Jyotiranjan404/Linear-Regression/blob/main/linear%20regression.ipynb



