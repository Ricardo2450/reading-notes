# Linear Regressions

> ## [How to Run Linear Regression in Python]()

* Difference between regression and classification is that the output variable in regression is continuous, while the output for classification is discrete.

* Regression predicts quantity; classification predicts labels. 

* Labeled data is data that has already been classified

* Unlabeled data is data that has not yet been labeled

* Two types of classification:

  * Binary Classification – sorts data on the basis of discrete or non-continuous values (usually two values). For example, a medical test may sort patients into those that have a specific disease versus those that do not.

  * Multi-class Classification – sorts data into three or more classes. For example, medical profiling that sorts patients into those with kidney, liver, lung, or bladder infection symptoms.

* Classification with Scikit-Learn include:
 
  * Decision Tree/Random Forest – the Decision Tree classifier has dataset attributes classed as nodes or branches in a tree. The Random Forest classifier is a meta-estimator that fits a forest of decision trees and uses averages to improve prediction accuracy.

  * K-Nearest Neighbors (KNN) – a simple classification algorithm, where K refers to the square root of the number of training records.

  * Linear Discriminant Analysis – estimates the probability of a new set of inputs for every class.

  * Logistic Regression – a model with an input variable (x) and an output variable (y), which is a discrete value of either 1 (yes) or 0 (no).

  * Naive Bayes – a family of classifiers based on a simple Bayesian model that is comparatively fast and accurate. Bayesian theory explores the relationship between probability and possibility.

  * Support Vector Machines (SVMs) – a model with associated learning algorithms that analyze data for classification. Also known as Support-Vector Networks. 

* linear regression method:

  * Best Fit – the straight line in a plot that minimizes the deviation between related scattered data points.

  * Coefficient – also known as a parameter, is the factor a variable is multiplied by. In linear regression, a coefficient represents changes in a Response Variable (see below).

  * Coefficient of Determination – the correlation coefficient denoted as 𝑅². Used to describe the precision or degree of fit in a regression. 

  * Correlation – the relationship between two variables in terms of quantifiable strength and degree, often referred to as the ‘degree of correlation’.  Values range between -1.0 and 1.0. 

  * Dependent Feature – a variable denoted as y in the slope equation y=ax+b. Also known as an Output, or a Response. 

  * Estimated Regression Line – the straight line that best fits a set of scattered data points.

  * Independent Feature – a variable denoted as x in the slope equation y=ax+b. Also known as an Input, or a predictor. 

  * Intercept – the location where the Slope intercepts the Y-axis denoted b in the slope equation y=ax+b. 

  * Least Squares – a method of estimating a Best Fit to data, by minimizing the sum of the squares of the differences between observed and estimated values.

  * Mean – an average of a set of numbers, but in linear regression, Mean is modeled by a linear function.

  * Ordinary Least Squares Regression (OLS) – more commonly known as Linear Regression. 

  * Residual – vertical distance between a data point and the line of regression (see Residual in Figure 1 below).

  * Regression – estimate of predictive change in a variable in relation to changes in other variables (see Predicted Response in Figure 1 below).

  * Regression Model – the ideal formula for approximating a regression.

  * Response Variables – includes both the Predicted Response (the value predicted by the regression) and the Actual Response, which is the actual value of the data point.

  * Slope – the steepness of a line of regression. Slope and Intercept can be used to define the linear relationship between two variables: y=ax+b.

  * Simple Linear Regression – a linear regression that has a single independent variable

> ## [Linear Regression in Python](https://realpython.com/linear-regression-in-python/)

* Regression searches for relationships among variables

* The dependent features are called the dependent variables, outputs, or responses

* The independent features are called the independent variables, inputs, regressors, or predictors.

* Regression is also useful when you want to forecast a response using a new set of predictors

* Linear regression is the ease of interpreting results.

* Multiple or multivariate linear regression is a case of linear regression with two or more independent variables.

> ## [Introduction to Simple Linear Regressions](https://www.youtube.com/watch?v=KsVBBJRb9TE)

* Regression analysis explores the relationship between a quantitative response variable and one or more explanatory variables

* A linear relationship between x and y is: 𝑦|x = 𝛽₀ + 𝛽₁x or E(y|x)= bo + b1 * x

* smple data to obtain the estimated regression line is : y = 𝑏₀ + 𝑏₁𝑥

> ## Other reads

* [Train & Test Splits](https://towardsdatascience.com/train-test-split-and-cross-validation-in-python-80b61beca4b6)

* [What is Linear Regression](https://www.statisticssolutions.com/what-is-linear-regression/)


[Return Home](../README.md)
