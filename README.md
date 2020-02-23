# Cross Validation and Simple Linear Regression
This is the process that gives us the internal and the cross-validation measures of predictive accuracy for a simple linear regression. The data are randomly assigned to a number of "folds", which in our context is the test and training folds. Each fold is removed, in turn, while the remaining data is used to re-fit the regression model and to predict at the deleted observations.

We will predict employee salaries from different employee characteristics (or features).
We are going to use a simple supervised learning technique: linear regression.
We want to build a simple model to determine how well Years Worked predicts an employee’s salary. Years Worked predicts an employee’s salary.
