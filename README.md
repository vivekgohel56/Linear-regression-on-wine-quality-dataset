# Linear-regression-on-wine-quality-dataset
I had taken this project from https://machinelearningmastery.com/implement-linear-regression-stochastic-gradient-descent-scratch-python/

In this we will train a linear regression model using stochastic gradient descent on the wine quality dataset.

A k value of 5 was used for cross-validation, giving each fold 4,898/5 = 979.6 or just under 1000 records to be evaluated upon each iteration. A learning rate of 0.01 and 50 training epochs were chosen with a little experimentation.
you can try your own configuration and see the score.

We can see that the RMSE (on the normalized dataset) is 0.126, lower than the baseline value of 0.148 if we just predicted the mean (using the Zero Rule Algorithm).
