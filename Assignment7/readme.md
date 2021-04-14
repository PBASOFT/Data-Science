# Assignment 7 - Linear Regression
## Simple Vs. Multiple Vs. Polynomial Regression


linear regressione =  find the best way to draw a line through the data points.

### Simpel Linear Regression:
  - y = ax+b
  - Models the relationship between two variables (one dependent(y) and one independent(X) variable)
  - Simple linear regression” is the term used to describe the process of finding a “best fit line” that models the relationship between two variables with a straight line.
  - source: https://www.quora.com/What-is-the-difference-between-simple-and-multiple-regression

### Multiple Linear Regression:   
- <img src="https://latex.codecogs.com/gif.latex?y&space;=&space;\beta&space;^{}_{0}&plus;\beta&space;m_{1}&space;\cdot&space;X_{1}&plus;\beta&space;_{2}&space;\cdot&space;X_{2}&space;...&space;\beta&space;_{n}&space;\cdot&space;X_{n}" title="y = \beta ^{}_{0}+\beta m_{1} \cdot X_{1}+\beta _{2} \cdot X_{2} ... \beta _{n} \cdot X_{n}" />
    - “Multiple regression” simply means that there are more X variables (independent variables) used in the prediction of Y


### Polynomial Linear Regression:
  - <img src="https://latex.codecogs.com/gif.latex?y&space;=&space;\beta&space;_{0}&space;&plus;&space;\beta&space;_{1}X_{1}&plus;\beta&space;_{2}X_{1}^{2}&plus;...&plus;\beta&space;_{n}X_{1}^{n}" title="y = \beta _{0} + \beta _{1}X_{1}+\beta _{2}X_{1}^{2}+...+\beta _{n}X_{1}^{n}" />
  - The line bends to follow the points more accurate, when they dont follow a linear form.


![](https://cdn.analyticsvidhya.com/wp-content/uploads/2020/03/pr8.png)



## In which type of projects each of them fits best?

Simpel Linear Regression is suited for projects where you want to learn about the dependency between two variables, i.e. salary and education level, if the data follows a linear progression.

Multiple Linear Regression is suited for projects where you want to learn multiple variabels dependency on a single variable, i.e. salery, education level and age.

Polynomial Linear Regression is suited for projects where you want to learn about the dependency between variabels, when the data doesn't follow a linear progression.

**Note:** Polynomial generelly fits the data better, but has a downside: It will be heavily affected by outliers.

