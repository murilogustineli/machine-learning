# Linear Regression and Gradient Descent
_**Linear Regression**_ is a supervised learning algorithm which goal is to to find a line that minimizes the prediction error of all data points.
<br> In statistics and machine learning, we optimize a lot of stuff. 
<br>Linear Regression predicts continous numerical values based on the given data points. In summary, _**Linear Regression fits a line to data.**_
- Linear Regression tries to find parameters of the line function, so the distance between all points and the line is as small as possible.
- In statistcs, linear regression is a linear approach to modeling the relationship between a _dependent variable_ and one or more _independent variables_.
  - dependent variable = _**y**_
  - independent variable = _**x**_

![Linear Regression](./Linear_Regression.jpg)

<br>

## Hypothesis
We define a linear relationship between x and y by using the equation _Y = mX + b_. <br>In this equation, m is the _**slope**_ of the line and b is the _**y-intercept**_.

<br>

## Loss Function (Cost Function)
The loss function, also called as "cost function", is the _error_ in the predicted value of m and b, given _y = mx + b_

<br>

## Mean Squared Error (MSE)
It tells you how close a regression line is to a set of points. It does this by taking the distances from the points to the regression line (these distances are the “errors”) and squaring them. The squaring is necessary to remove any negative signs. It also gives more weight to larger differences. It’s called the mean squared error as you’re finding the average of a set of errors. The lower the MSE, the better the predicted value.

<br>

## Gradient Descent 
_"A gradient measures how much the output of a function changes if you change the inputs a little bit." — Lex Fridman (MIT)_
<br>
<br>Gradient descent is an optimization algorithm used to find the values of parameters (coefficients) of a function (f) that minimizes a cost function (cost). Here, the cost function is the _MSE_. It minimizes some function (f) by iteratively moving in the direction of steepest descent as defined by the negative of the gradient. In machine learning, we use gradient descent to update the parameters of our model. Parameters refer to coefficients in Linear Regression and weights in neural networks.
<br>
<br>A gradient simply measures the change in all weights with regard to the change in error. You can also think of a gradient as the slope of a function. The higher the gradient, the steeper the slope and the faster a model can learn. But if the slope is zero, the model stops learning. In mathematical terms, a gradient is a partial derivative with respect to its inputs.

<br>
<br>

### Resources:
1. [Linear Regression using Gradient Descent in Python - Machine Learning Basics](https://www.youtube.com/watch?v=4PHI11lX11I&ab_channel=AdarshMenon)
2. [TowardsDataSciene - Linear Regression using Gradient Descent](https://towardsdatascience.com/linear-regression-using-gradient-descent-97a6c8700931)
3. [StatQuest: Gradient Descent - Step-by-Step](https://www.youtube.com/watch?v=sDv4f4s2SB8&ab_channel=StatQuestwithJoshStarmer)