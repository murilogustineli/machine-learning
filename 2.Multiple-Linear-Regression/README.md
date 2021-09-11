# Multiple Linear Regression (MLR)

_**Regression models**_ are used to describe relationships between variables by fitting a line to the observed data. Regression allows you to estimate how a dependent variable (_y_) changes as the independent variable(s) (_x_) change.

_**Multiple linear regression**_ is used to estimate the relationship between _**two or more independent variables**_ and _**one dependent variable**_. You can use multiple linear regression when you want to know:
1. How strong the relationship is between two or more independent variables and one dependent variable (e.g. how rainfall, temperature, and amount of fertilizer added affect crop growth).
2. The value of the dependent variable at a certain value of the independent variables (e.g. the expected yield of a crop at certain levels of rainfall, temperature, and fertilizer addition).

<br>

## How to perform a multiple linear regression
### Formula and Calculation of Multiple Linear Regression
The formula for a multiple linear regression is:
### _y<sub>i</sub> = β<sub>0</sub> + β<sub>1</sub>x<sub>i1</sub> + β<sub>2</sub>x<sub>i2</sub> + β<sub>3</sub>x<sub>i3</sub> + ... + β<sub>p</sub>x<sub>ip</sub> + ϵ_

where, for _i=n_ observations:
- _y<sub>i</sub>_ = dependent variable
- _x<sub>i</sub>_ = explanatory variables (independent variables)
- _β<sub>0</sub>_ = y-intercept
- _β<sub>p</sub>_ = slope coeficient for each explanatory variable
- ϵ = the model's error term (also known as the residuals)

<br>

- y = the predicted value of the dependent variable
- B0 = the y-intercept (value of y when all other parameters are set to 0)
- B1X1= the regression coefficient (B1) of the first independent variable (X1) (a.k.a. the effect that increasing the value of the independent variable has on the predicted y value)
- … = do the same for however many independent variables you are testing
- BnXn = the regression coefficient of the last independent variable
- e = model error (a.k.a. how much variation there is in our estimate of y)

<br>

## Simple Regression vs Multiple Regression
Simple regression is just fitting a line to data. 

_**Multiple linear regression (MLR)**_, also known simply as _**multiple regression**_, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable.
- The goal of multiple linear regression is to model the linear relationship between the _**explanatory (independent)**_ variables and _**response (dependent)**_ variable. 
- Multiple regression is an extension of ordinary least-squares (OLS) regression because it involves more than one explanatory variable.

<br>

## Multiple Regression vs Multivariate Regression
Multiple Linear Regression differs from Multivariate Regression. Multivariate Regression is a method used to measure the degree at which more than one independent variable (predictors) and more than one dependent variable (responses), are linearly related. The method is broadly used to predict the behavior of the response variables associated to changes in the predictor variables, once a desired degree of relation has been established.

<br>

## What does it mean for a multiple regression to be linear?
In multiple linear regression, the model calculates the line of best fit that minimizes the variances of each of the variables included as it relates to the dependent variable. Because it fits a line, it is a linear model. There are also non-linear regression models involving multiple variables, such as logistic regression, quadratic regression, and probit models.

<br>

### Resources
1. [Scribbr - An introduction to multiple linear regression](https://www.scribbr.com/statistics/multiple-linear-regression/)
2. [Investopedia - Multiple Linear Regression (MLR)](https://www.investopedia.com/terms/m/mlr.asp)
