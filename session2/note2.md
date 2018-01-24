# Reflaction 2

## Different Data Set

1. ### Traning Set
    - The set is used to train the model
2. ### Validation Set
    - Validation data set is used to tune the model, it has effect to the hyperparameters or weight of each factors
4. ### Test set
    - Used for checking and verfying the performane of the trained model

**Remember to suffle the data before spliting** 

## Split percentage

1. 70% training, 30% validation
2. 60% training, 20% validation, 10% test
3. 98% training, 1% validation, 1% test

## Logistic regression

Does the object fit into certain category. eg. Is this a picture of a cat.

## Lose of logistic regression

MSE cannot be work well since it leads to non-convex result. Use **binary_crossentropy**. Looks at the [link](https://rdipietro.github.io/friendly-intro-to-cross-entropy-loss/)

