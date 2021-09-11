# Multiple Linear Regression (MLR)

_**Regression models**_ are used to describe relationships between variables by fitting a line to the observed data. Regression allows you to estimate how a dependent variable (_y_) changes as the independent variable(s) (_x_) change.

_**Multiple linear regression**_ is used to estimate the relationship between _**two or more independent variables**_ and _**one dependent variable**_. You can use multiple linear regression when you want to know:
1. How strong the relationship is between two or more independent variables and one dependent variable (e.g. how rainfall, temperature, and amount of fertilizer added affect crop growth).
2. The value of the dependent variable at a certain value of the independent variables (e.g. the expected yield of a crop at certain levels of rainfall, temperature, and fertilizer addition).

In Machine Learning, we treat the independent variables (_x<sub>i</sub>_) as _**features**_. Where, for _**i = 1, 2, ... , n**_ features.

<br>

## Formula of multiple linear regression
The model for multiple linear regression, given _n_ observations, is:
### _y = β<sub>0</sub> + β<sub>1</sub>x<sub>1</sub> + β<sub>2</sub>x<sub>2</sub> + ... + β<sub>n</sub>x<sub>n</sub> + ϵ_
where, for _**i = 1, 2, ... , n**_ observations:
- _y_ = the predicted value of the dependent variable
- _β<sub>0</sub>_ = the y-intercept (value of _y_ when all other parameters are set to 0)
- _β<sub>1</sub>x<sub>1</sub>_ = the regression coefficient (_β<sub>1</sub>_) of the first independent variable (_x<sub>1</sub>_) (a.k.a. the effect that increasing the value of the independent variable has on the predicted _y_ value)
- _β<sub>2</sub>x<sub>2</sub>_ = the regression coefficient (_β<sub>2</sub>_) of the second independent variable (_x<sub>2</sub>_)
- … = do the same for however many independent variables you are testing
- _β<sub>n</sub>x<sub>n</sub>_ = the regression coefficient of the last independent variable
- _ϵ_ = model error (a.k.a. how much variation there is in our estimate of _y_)

<br>

In simple words, the model is expressed as _**DATA = FIT + RESIDUAL**_, where the _"FIT"_ term represents the expression _β<sub>0</sub> + β<sub>1</sub>x<sub>1</sub> + β<sub>2</sub>x<sub>2</sub> + ... + β<sub>n</sub>x<sub>n</sub>_. The _"RESIDUAL"_ term represents the deviations of the observed values _y_ from their means, which are normally distributed with mean 0 and variance. The notation for the model deviations is ϵ.

<br>

## Example of using Multiple Regression for predicting house prices
We want to predict house prices and gathered a few features, such as, size of the house (sqr. feet), number of bedrooms, and age of the house.

In this example, our formula can be written as:
<br>_**price = β<sub>0</sub> + m<sub>1</sub> * size + m<sub>2</sub> * bedrooms + m<sub>3</sub> * age**_

- The price is our dependent variable (_y_), also known as the _**target variable**_ in Machine Learning lingo
- The features are our independent variables (_size, bedrooms, age_)
- _β<sub>0</sub>_ = y-intercept
- _m_ = regression coefficients
- Every value of the independent variable _x_ is associated with a value of the dependent variable _y_

<!---
### _y<sub>i</sub> = β<sub>0</sub> + β<sub>1</sub>x<sub>i1</sub> + β<sub>2</sub>x<sub>i2</sub> + ... + β<sub>p</sub>x<sub>ip</sub> + ϵ<sub>i</sub>_
- _y<sub>i</sub>_ = dependent variable
- _x<sub>i</sub>_ = explanatory variables (independent variables)
- _β<sub>0</sub>_ = y-intercept
- _β<sub>p</sub>_ = slope coeficient for each explanatory variable
- ϵ = the model's error term (also known as the residuals)
--->
<br>

## Simple Regression vs Multiple Regression
Simple regression is just fitting a line to data where you have one dependent variable (_y_) and one independent variable (_x_).

_**Multiple linear regression (MLR)**_, also known simply as _**multiple regression**_, is a statistical technique that uses several explanatory variables to predict the outcome of a response variable.
- The goal of multiple linear regression is to model the linear relationship between the _**explanatory (independent)**_ variables and _**response (dependent)**_ variable. 
- Multiple regression is an extension of ordinary least-squares (OLS) regression because it involves more than one explanatory variable.

<br>

## Multiple Regression vs Multivariate Regression
Multiple Linear Regression differs from Multivariate Regression. Multivariate Regression is a method used to measure the degree at which more than one independent variable (predictors) and more than one dependent variable (responses), are linearly related. The method is broadly used to predict the behavior of the response variables associated to changes in the predictor variables, once a desired degree of relation has been established.

<br>

## What does it mean for a multiple regression to be linear?
In multiple linear regression, the model calculates the _**line of best fit**_ that minimizes the variances of each of the variables included as it relates to the dependent variable. Because it fits a line, it is a linear model. There are also non-linear regression models involving multiple variables, such as logistic regression, quadratic regression, and probit models.

<br>

### Resources
1. [Scribbr - An introduction to multiple linear regression](https://www.scribbr.com/statistics/multiple-linear-regression/)
2. [Yale Stats](http://www.stat.yale.edu/Courses/1997-98/101/linmult.htm)
3. [Investopedia - Multiple Linear Regression (MLR)](https://www.investopedia.com/terms/m/mlr.asp)
4. [codebasics - Machine Learning Tutorial: Linear Regression Multiple Variables](https://www.youtube.com/watch?v=J_LnPL3Qg70&ab_channel=codebasics)
