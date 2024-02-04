#ML--Linear Regression--Advertising Data

# Linear Regression- Advertising data

## Objective- Predicting Sales to increase marketing efficiency by exploring various Advertising channels used for marketing.

## Project Summary

### 1. Data Exploration
### 2. Data Analysis : shape, info, missing values, datatypes
### 3. Checking the Assumptions of Linear Regression
#### Assumption No 1 - There should be no outliers in the data : pd.boxplot()
#### Assumption No 2 - Assumption of Linearity : pairplot() -Create X and Y
#### Assumption No 3 - Assumption of normality of Y : distplot(), log().Handle the skewness in the X: skew(), log1p(), hist()
#### Assumption No 4 - There should be no multicollinearity : corr(), heatmap(), vif()
### 4. Perform EDA
### 5. Split the data : train_test_split() / manual Splitting
### 6. Normalize the Data (Optional): MinMaxScaler(), StandardScaler()
### 7. Build the model:
#### a. Create the model object : model = LinearRegression()
#### b. Train the model : model.fit(X_train, y_train)
#### c. Predict using the model : y_pred=model.predict(X_test)
### 8. Evaluating the Model:
#### a. R-square
#### b. Adjusted R-square
#### c. RMSE
