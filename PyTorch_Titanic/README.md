# Titanic Classification with PyTorch

A simple machine learning project using PyTorch to predict Titanic survival based on passenger data such as age, gender, and class. See the [dataset folder](../Titanic_dataset/) for more information.  
We tested three optimizers, each with multiple hyperparameter, to find the best combination.

## Results
The optimizer with the best score on Kaggle was [SGD](train_SGD.ipynb), achieving an accuracy of `0.78`, followed closely by [Adam](train_Adam.ipynb) and [RMSprop](train_RMS.ipynb), both with `0.76` accuracy.