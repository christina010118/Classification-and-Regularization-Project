# Classification-and-Regularization-Project

## Classification

We conduct classification task to predict the body performance of class A,B,C,D. Conclusion: Based on the model fits, a non-linear is more appropriate since the accuracy generated from QDA has the highest accuracy, though the accuracy are pretty close to each other in all classification methods.

## Regularization
For this portion of the project, we're going to use a data set containing information on the Australian housing market and apply regularization techniques to make predictions on house prices. The data set will have 81 columns of data. 

*Overall procedure*

Numeric pipeline:
- We will impute missing values with medians 
- After that, we will standardize each vector of data to ensure each feature is given equal weighting by our models


Categorical pipeline:
- In each vector of data, we will fill missing values with the most commonly observed sample
- After that, we will transform each vector to numeric representation using label encoding or by making them dummy variables, where appropriate
