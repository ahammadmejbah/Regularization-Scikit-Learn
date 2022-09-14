### L2 and L1 regularization

Regularization is a technique that is used to avoid overfitting of the data, by adding complexity to the weights.

In other words, instead of simply aiming to minimize loss (empirical risk minimization):
```
minimize(loss_function)
```
we'll now minimize loss+complexity, which is called structural risk minimization:

```
minimize(loss_function)+complexity(model)
```

Our training optimization algorithm is now a function of two terms: the loss term, which measures how well the model fits the data, and the regularization term, which measures model complexity.

### Reference:
    
[Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/regularization-for-simplicity/l2-regularization)

[Towards Data Science](https://towardsdatascience.com/ridge-and-lasso-regression-a-complete-guide-with-python-scikit-learn-e20e34bcbf0b)
