# Auto-mpg-dataset-solution

Objectives
Given different features (or explanatory variables), the aim is to predict the fuel consumption in MPG (miles per gallon).

Such a model can be then used during the design process of cars case fuel consumption is a determinant factor to assess different designs and configurations.

Dataset
The data set comes from the UCI Machine Learning Repository and can be downloaded here.

The dataset is small (398 instances and 8 features). Yet, it is rich in terms of features types.

cylinders: numerical discrete
displacement (engine size): continuous
horsepower: continuous
weight: continuous
acceleration: continuous
model year: numerical discrete
origin: numerical discrete
car name: string (unique for each instance)
Approach and Results
After data exploration and cleaning, we preprocessed original features and used them to train a Random Forest model.

We used Random Search Cross-Validation to tune the hyperparameters. The weight of the car and the size of its engine are the most important features to predict the fuel consumption according to the Random Forest model.

The RMSE (Root Mean Squared Error) score for the selected model is 2.27 MPG with a 95% confidence interval [1.82, 2.65].

The Jupyter notebooks will walk you through each step of the process. They are intended to be self-explanatory.
