# Variables Selection with R
Here, we use toys data set available in the VSURF package.

1- We start by performing a linear model and applying a variable selection procedure (LASSO and Ridge).

2- We perform the quality of these models by test error on the test data set.

3- We perform a CART model and a random forest one, and evaluate also their performance

4- We run the VSURF procedure and we evaluate the quality of the final model selected by this procedure.

5- We repeat the VSURF procedure 50 times and we conclude.


# Linear Regression Model
In the Fund.txt data set, the first column is the response variable and the second one is the explanatory one.

We start to estimate the linear model and then plotting the regression curve on the cloud points. After that, we estimate the confidence interval for the prediction and plot it on the same graph.

At the end, we make the fisher test to see if the is an influence or not of the explanatory variable of the response.
