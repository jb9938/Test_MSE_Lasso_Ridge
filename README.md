# Test_MSE_Lasso_Ridge

# Topic
This repository demonstrates the difference bewteen test MSE and training MSE. It proves a best performing model built on training does not always guarantee equivalent performance in testing, resulting in overfitting. It also demonstrates the difference between lasso and ridge regression using test MSE. Lasso regression is a regualrization rule following L1 norm while ridge follows L2. Lasso regression are ideal in estimation when true reponse vector are sparse (some betas are 0s). 


# File
test and training MSE.Rmd: Demonstrates & Compares the difference bewteen train and test MSE using 3 different subset selection method (Best, forward stepwise, backward stepwise)

Lasso & Ridge Comparison.Rmd: Demonstrates cases where lasso outperforms ridge and vice versa. 
