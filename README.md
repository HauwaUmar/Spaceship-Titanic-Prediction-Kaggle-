# Spaceship-Titanic-Prediction-Kaggle-
This project is an implementation of binary classification on ‘Spaceship titanic’ data from Kaggle.(https://www.kaggle.com/competitions/spaceship-titanic/overview).

The aim is to predict which passengers were transported to an alternate dimension by the anomaly using the records provided.

The dataset contained information about each passenger such as:

The name of the passenger.
The age of the passenger.
The home planet of the passenger.
Where the passenger planned to arrive.
To start with, basic data exploration was performed to depict certain relationships and trends in the dataset. There seems to be weak correlations between the predictors.

Both the test and train sets held out by Kaggle were combined to perform data cleaning and preprocessing uniformly on the entire data for ease of modeling. The data-cleaning part includes:

Handling missing/NaN values, which was done by filling the NaN values with appropriate imputations.

The data needs to be pre-processed before being trained by the model, to transform the categorical variables we have used label encoder and generated dummy variables.

Four binary classification methods were implemented based on the nature of the dataset

Gaussian Naive Bayes

Bernoulli Naive Bayes

Linear Discriminant Analysis

Logistic Regression

For understanding the importance of variables and selecting the best set of features, feature selection was performed using forward selection and backward elimination for certain models.

After implementing multiple classification models to perform this binary classification task, logistic regression coupled with backward elimination proved to perform the best out of all the others. This produced the highest kaggle submission score of 0.80.
