# Boston-Housing-Predictions
This program aims to predict the median value of owner-occupied homes in Boston using various machine learning models. The dataset contains information collected by the U.S Census Service, and our goal is to select the variables that best predict the target variable (MEDV) and suggest a machine learning model for prediction.

# Dataset Description
The dataset includes 14 attributes for each case:

CRIM: Per capita crime rate by town
ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS: Proportion of non-retail business acres per town.
CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
NOX: Nitric oxides concentration (parts per 10 million)
RM: Average number of rooms per dwelling
AGE: Proportion of owner-occupied units built prior to 1940
DIS: Weighted distances to five Boston employment centers
RAD: Index of accessibility to radial highways
TAX: Full-value property-tax rate per $10,000
PTRATIO: Pupil-teacher ratio by town
B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
LSTAT: % lower status of the population
MEDV: Median value of owner-occupied homes in $1000's

# Feature Selection and Data Preprocessing
The program performs feature selection using backward elimination based on p-values. Outliers are identified and handled, and multicollinearity is addressed. The dataset is then split into training and test sets.

# Machine Learning Models
The program utilizes various regression models for prediction:
Linear Regression
Polynomial Regression
Support Vector Regression (SVR)
Random Forest Regression
K-Nearest Neighbors (KNN) Regression

# Results
The R squared scores for each model are displayed, providing an evaluation of their predictive performance.

# Visualizations
Bar plots are generated to compare actual and predicted values for the first ten observations in each regression model.
