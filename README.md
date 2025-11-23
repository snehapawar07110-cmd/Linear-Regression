# Linear-Regression
Simple Linear Regression [Input-Output Sowing Linear Relation(SLR)]


DEFINITION :  SLR is a type of regression algorithm that models the realtionship between a dependent(TARGET) and "single" independent variable


LINEAR EQUATION : y=mx=+c


WHERE:
y=dependent varibale
x=independent variable
m= slope / coefficient
c= intercept


<img width="256" height="148" alt="image" src="https://github.com/user-attachments/assets/d83cdcd8-4256-4c4c-9704-26c8b7f0c65c" />



#Multiple Linear Regression (MLR)

Definition:

Multiple Linear Regression is a statistical method to predict the value of a dependent variable (target) based on two or more independent variables (features).

It extends Simple Linear Regression to multiple features.

Equation:

Key Points:

Uses two or more independent variables.

Fits a hyperplane instead of a straight line.

Evaluates impact of each feature on the target.

Common metrics for evaluation: R² score, Mean Squared Error (MSE).


<img width="270" height="148" alt="image" src="https://github.com/user-attachments/assets/89043557-a6eb-40eb-9027-63383a7c8317" />

#Lasso Regression (L1 Regularization)


Definition:

Lasso Regression is a linear regression technique with L1 regularization.

It adds a penalty to the regression coefficients to reduce overfitting and can set some coefficients exactly to zero, effectively performing feature selection.

EQUATION :

cost Function: RSS+αj=1∑n​∣bj​∣


Where:

RSS = Residual Sum of Squares

𝑏j= coefficients of features

α = regularization strength (larger 

α → more shrinkage)

Lasso helps when you have many features and want to remove irrelevant ones

KEY POINT:

Penalizes absolute value of coefficients (L1 penalty).

Can shrink some coefficients to zero, useful for feature selection.

Reduces overfitting and improves model generalization.

#Ridge Regression (L2 Regularization)


Definition:

Ridge Regression is a type of linear regression with L2 regularization.

It adds a penalty to the squared magnitude of coefficients to reduce overfitting.

Unlike Lasso, Ridge does not set coefficients to zero, but shrinks them toward zero.

Works for multiple linear regression problems.

Key Points:

Penalizes squared coefficients (L2 penalty).

Reduces overfitting and improves model stability.

Useful when you have many correlated features.

Does not remove features (all coefficients remain >0).

Use Case	   :  When feature selection is needed                                                    When features are highly correlated


Graph/Distribution  :	Sparse coefficients	                                                                 Smooth, small coefficients



# Polynomial-Regrssion


Polynomial Regression — Simple Explanation

Polynomial Regression is an extension of Linear Regression where we model the relationship between variables as an nth-degree polynomial instead of a straight line.

🔹 Why we use Polynomial Regression?

Because real-world data is often non-linear.
Polynomial regression helps in:

Curve fitting

Capturing non-linear patterns

Making better predictions than simple linear regression for curved data
