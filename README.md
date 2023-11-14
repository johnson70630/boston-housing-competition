# boston-housing-competition
Build a machine learning model to predict Boston house prices for Kaggle competition

[Kaggle competition](https://www.kaggle.com/competitions/sc201-jul-2023)

## Data

[training & validation data](https://github.com/johnson70630/boston-housing-competition/blob/main/boston_housing_competition/boston_housing/train.csv)

60% for trianig, 40% for validation, randomly

[testing data](https://github.com/johnson70630/boston-housing-competition/blob/main/boston_housing_competition/boston_housing/test.csv)

### Housing Price in Boston
The medv variable is the target variable.

### Data Description
The Boston data frame has 506 rows and 14 columns.
This data frame contains the following columns:

- crim: per capita crime rate by town

- zn: proportion of residential land zoned for lots over 25,000 sq.ft

- indus: proportion of non-retail business acres per town

- chas: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

- nox: nitrogen oxides concentration (parts per 10 million)

- rm: average number of rooms per dwelling

- age: proportion of owner-occupied units built prior to 1940

- dis: weighted mean of distances to five Boston employment centres

- rad: index of accessibility to radial highways

- tax: full-value property-tax rate per \$10,000

- ptratio: pupil-teacher ratio by town

- black: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

- lstat: lower status of the population (percent)

- medv: median value of owner-occupied homes in \$1000s


## data preprocessing
- remove 'ID'
- check for missing data
- no 'medv' in testing data

## one-hot encoding
Transform 'chas' into 'chas_0' and 'chas_1', and under each new feature, use 0 and 1 to represent the presence or absence of the category

## standardization

## bagging


## Training
### [Linear Regression](https://github.com/johnson70630/boston-housing-competition/blob/main/boston_housing_competition/boston_housing_competition.py)

### [Random Forest](https://github.com/johnson70630/boston-housing-competition/blob/main/boston_housing_competition/boston_random_forest.py)
