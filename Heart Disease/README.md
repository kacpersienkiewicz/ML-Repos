# Heart Disease
I will use the heart disease dataset (just the Cleveland one since it is the only one that is properly processed) to try to create a model to predict the heart disease diagnosis based on the 13 given features.

## Outline
Exploratory Data Analysis revealed the distributions of the data which revealed a few skewed distributions and a power law distribution. Skewed distrbutions can be transformed using a Box Cox Transformations followed by Z-Score Scaling, while the power law distribution can be transformed using log scaling. It also revealed that a few features needed to be encoded, with one of them having an order to them and so it can be label encoded but the other features needed to be one hot encoded. Logistic Regression, K-Nearest Neighbors and a Random Forest was tested and ultimately the Logistic Regression was optimized to get an overall ROC AUC score of 0.88.

## Source
Uses [Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) found on the UCI Machine Learning Repository.
