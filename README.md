# Linear-Regression-implementation

Linear regression is a statistical method used for modeling the relationship between a dependent variable and one or more independent variables by fitting a linear equation to observed data. It is a fundamental technique in both statistics and machine learning for understanding and predicting the relationships between variables.

In a simple linear regression, there is one dependent variable (also known as the target or outcome variable) and one independent variable (also known as the predictor variable). The goal is to find the best-fitting straight line (linear equation) that minimizes the difference between the actual observed values and the predicted values based on the linear equation. This line is often referred to as the "regression line" or "best-fit line."

The linear equation for simple linear regression can be represented as:

\[ y = mx + b \]

Where:
- \( y \) is the dependent variable (target).
- \( x \) is the independent variable (predictor).
- \( m \) is the slope of the line, representing the change in \( y \) for a unit change in \( x \).
- \( b \) is the y-intercept, which is the value of \( y \) when \( x \) is 0.

In multiple linear regression, there are more than one independent variables, and the linear equation takes the form:

\[ y = b_0 + b_1x_1 + b_2x_2 + \ldots + b_nx_n \]

Where:
- \( y \) is the dependent variable.
- \( b_0 \) is the y-intercept.
- \( b_1, b_2, \ldots, b_n \) are the coefficients associated with the independent variables \( x_1, x_2, \ldots, x_n \).

The coefficients \( b_0, b_1, \ldots, b_n \) are estimated from the given data using various techniques, with the goal of minimizing the difference between the predicted values and the actual observed values. This minimization is often achieved using methods like the least squares approach.

Linear regression is commonly used for tasks such as predicting future values, understanding the relationships between variables, and making inferences about how changes in independent variables influence the dependent variable. It serves as the foundation for more advanced regression and machine learning techniques.




Here, we use numPy and Pandas to establish a linear relation between the response and regressor variables.
To test the significance of the relation, R-squared is calculated. Also, the relation is compared with the **Linear Regression Model from ScikitLearn**

# Method:
<img width="466" alt="image" src="https://github.com/RonSheoran123/Linear-Regression-implementation/assets/106268100/6cb222ba-5262-4d10-bf64-ee2c2da8b63c">


Represent your dataset in matrix form. Let 
X be the matrix of independent variables (with each row representing an observation and each column representing a different independent variable), and 
Y be the vector of dependent variable values.


<img width="418" alt="image" src="https://github.com/RonSheoran123/Linear-Regression-implementation/assets/106268100/0a35f283-caa6-4a39-85db-491fba4b5c8a">                    


<img width="488" alt="image" src="https://github.com/RonSheoran123/Linear-Regression-implementation/assets/106268100/2ab9e000-3802-4f71-960e-1a469737bb6b">                    


<img width="493" alt="image" src="https://github.com/RonSheoran123/Linear-Regression-implementation/assets/106268100/d139f74d-87ee-455c-8907-d2a21366373d">                    
