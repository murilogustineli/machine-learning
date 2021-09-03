# Linear Regression and Gradient Descent
_**Linear Regression**_ is a supervised learning algorithm which goal is to predict continuous numerical values based on the given data points.
- Linear Regression tries to find parameters of the line function, so the distance between all points and the line is as small as possible.
- In statistcs, linear regression is a linear approach to modeling the relationship between a _dependent variable_ and one or more _independent variables_.
  - dependent variable = _**y**_
  - independent variable = _**x**_



<br>
<br>
<br>
_**Hypothesis**_
<br>We define a linear relationship between x and y by using the equation _Y = mX + b_. <br>In this equation, m is the _**slope**_ of the line and b is the _**y-intercept**_.


_**Loss Function (Cost Function)**_
<br>The loss function, also called as "cost function", is the _error_ in the predicted value of m and b, given _y = mx + b_


_**Mean Squared Error (MSE)**_ tells you how close a regression line is to a set of points. It does this by taking the distances from the points to the regression line (these distances are the “errors”) and squaring them. The squaring is necessary to remove any negative signs. It also gives more weight to larger differences. It’s called the mean squared error as you’re finding the average of a set of errors. The lower the MSE, the better the predicted value.


_**Gradient Descent**_ 
<br>_"A gradient measures how much the output of a function changes if you change the inputs a little bit." — Lex Fridman (MIT)_
<br>Gradient Descent is an iterative optimization algorithm to find the minimum value of a function. In this case, that loss function is our _MSE_.
