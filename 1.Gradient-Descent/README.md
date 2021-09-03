# Linear Regression and Gradient Descent
_**Linear Regression**_ is a supervised learning algorithm which goal is to predict continuous numerical values based on the given data points.
- Linear Regression tries to find parameters of the line function, so the distance between all points and the line is as small as possible.
- In statistcs, linear regression is a linear approach to modeling the relationship between a _dependent variable_ and one or more _independent variables_.
  - dependent variable = _**y**_
  - independent variable = _**x**_

![Linear Regression](./Linear_Regression.jpg)

<br>

_**Hypothesis**_
<br>We define a linear relationship between x and y by using the equation _Y = mX + b_. <br>In this equation, m is the _**slope**_ of the line and b is the _**y-intercept**_.


_**Loss Function (Cost Function)**_
<br>The loss function, also called as "cost function", is the _error_ in the predicted value of m and b, given _y = mx + b_


_**Mean Squared Error (MSE)**_ tells you how close a regression line is to a set of points. It does this by taking the distances from the points to the regression line (these distances are the “errors”) and squaring them. The squaring is necessary to remove any negative signs. It also gives more weight to larger differences. It’s called the mean squared error as you’re finding the average of a set of errors. The lower the MSE, the better the predicted value.


_**Gradient Descent**_ 
<br>_"A gradient measures how much the output of a function changes if you change the inputs a little bit." — Lex Fridman (MIT)_
<br>
<br>Gradient descent is an optimization algorithm used to find the values of parameters (coefficients) of a function (f) that minimizes a cost function (cost). Here, the cost function is the _MSE_. It minimizes some function (f) by iteratively moving in the direction of steepest descent as defined by the negative of the gradient. In machine learning, we use gradient descent to update the parameters of our model. Parameters refer to coefficients in Linear Regression and weights in neural networks.
<br>
<br>A gradient simply measures the change in all weights with regard to the change in error. You can also think of a gradient as the slope of a function. The higher the gradient, the steeper the slope and the faster a model can learn. But if the slope is zero, the model stops learning. In mathematical terms, a gradient is a partial derivative with respect to its inputs.
