## Predicting Boston House Price with the following algorithms using python
  - Polynomial Regression
  - Ridge Regression
  - Lasso Regression
1. Introduction Regularization in Machine Learning:
  Regularization refers to techniques that are used to calibrate machine learning models in order to minimize the adjusted loss function and prevent overfitting or underfitting.
  using regularization, we can fit our machine learning model appropriately on a given test set and hence reduce the errors in it. The commonly used regularization techniques are:
      Lasso Regularization – L1 Regularization
      Ridge Regularization – L2 Regularization
      Elastic Net Regularization – L1 and L2 Regularization
2. Lasso
  A regression model which uses the L1 Regularization technique is called LASSO(Least Absolute Shrinkage and Selection Operator) regression.
  Lasso Regression adds the “absolute value of magnitude” of the coefficient as a penalty term to the loss function(L).
  Lasso regression also helps us achieve feature selection by penalizing the weights to approximately equal to zero if that feature does not serve any purpose in the model.
4. Ridge
  A regression model that uses the L2 regularization technique is called Ridge regression. Ridge regression adds the “squared magnitude” of the coefficient as a penalty term to the loss function(L).
5. Elastic Net Regression
  This model is a combination of L1 as well as L2 regularization. That implies that we add the absolute norm of the weights as well as the squared measure of the weights.
  With the help of an extra hyperparameter that controls the ratio of the L1 and L2 regularization.
  Note that a good choice of list of values for l1_ratio is often to put more values close to 1 (i.e. Lasso) and less close to 0 (i.e. Ridge).
6. Performance comparison of Polynomial regression and Regularization algorithms in prediction house price.
