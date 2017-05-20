# sale-price-prediction
Using Regularized Linear Regression to predict house prices (Ames data set)

Author: David Kradolfer, May 2017

In this notebook, I will use two linear regression methods, the Lasso and Ridge regression, to predict sale prices of properties in Ames, Iowa, between 2006 and 2010. The training and test data can be downloaded from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

A description of the variables of the data set can be found [here](https://ww2.amstat.org/publications/jse/v19n3/decock/DataDocumentation.txt)
, and there is also a [publication](https://ww2.amstat.org/publications/jse/v19n3/decock.pdf) on the data set by Dean De Cock.

Evaluation metric:  Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.
