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
