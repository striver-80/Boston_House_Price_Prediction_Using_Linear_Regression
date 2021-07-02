# House_Price_Prediction_Using_Linear_Regression
Predicting Boston house prices using Linear regression.
## Brief about Boston dataset:
This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. This dataset contains 506 examples with 14 attributes. The attributes are the following:
There are 14 attributes in each case of the dataset. They are:
              CRIM - per capita crime rate by town
              ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
              INDUS - proportion of non-retail business acres per town.
              CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
              NOX - nitric oxides concentration (parts per 10 million)
              RM - average number of rooms per dwelling
              AGE - proportion of owner-occupied units built prior to 1940
              DIS - weighted distances to five Boston employment centres
              RAD - index of accessibility to radial highways
              TAX - full-value property-tax rate per $10,000
              PTRATIO - pupil-teacher ratio by town
              B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
              LSTAT - % lower status of the population
              MEDV - Median value of owner-occupied homes in $1000's
The MEDV attributes are the prices of the houses in $1000.
Missing values = 0

## Data Visualization:
For data visualization in this project I've used three types of plots :
                1. Scatter plot to know the relation between features
                2. Heatmap with correlation of features
                3. Bar graph for the relation between features and the target variables.
                
## Model Training:
For training the model I've used the LinearRegression() from sklearn module. And for training purpose 70% of the actual dataset is used and the rest for testing purpose.

## Model Evaluation:
For model evaluation the R^2 score, MAE, MSE and RMSE values have been used.

## Performance:
The output for training data and for test data have been saved in train.csv and test.csv files respectively.
              
