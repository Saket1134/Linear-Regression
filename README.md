# This repository contains Python implementations of Simple Linear Regression (SLR) and Multiple Linear Regression (MLR) for predictive modeling and exploring relationships between variables.
**Linear Regression (LR)**

Linear regression is a foundational statistical and machine learning technique used to model the linear relationship between a dependent variable (the target) and one or more independent variables (the features). Its primary goal is to find the "best-fit" line or hyperplane that minimizes the prediction errors.
Linear regression is a foundational statistical and machine learning technique used to model the linear relationship between a dependent variable (the target) and one or more independent variables (the features). Its primary goal is to find the "best-fit" line or hyperplane that minimizes the prediction errors.

The model posits that the expected value of the dependent variable (Y) is a straight-line function of the independent variables (X 
i) plus an error term (ϵ).

The general form of the linear regression equation is:
Y=β0+β1X1+β2X2+⋯+βnXn+ϵ


**Simple Linear Regression (SLR)**

SLR is the most basic form of linear regression, involving only one independent variable.

Model Equation: Y=β0+β1X+ϵ

Interpretation: The model finds the Line of Best Fit on a 2D scatter plot. The coefficient β1 represents the change in Y for every one-unit change in X.

Application: Ideal for exploring a direct, fundamental relationship between two variables (e.g., height vs. weight).

**Multiple Linear Regression (MLR)**

MLR extends SLR by using two or more independent variables.

Model Equation: Y=β0+β1X1+β2X2+⋯+βnXn+ϵ

Interpretation: The model finds a Hyperplane of Best Fit in a multi-dimensional space. The interpretation of each coefficient (β 
i) is a ceteris paribus (all else being equal) effect—it is the change in Y when Xi
​	
  changes by one unit, assuming all other predictor variables remain constant.

Application: Necessary for modeling complex, real-world phenomena where the outcome is influenced by multiple factors (e.g., predicting house price based on size, location, and number of rooms).

***Key Assumptions (OLS Assumptions)***

For the OLS estimates to be the Best Linear Unbiased Estimators (BLUE) (Guaranteed by the Gauss-Markov Theorem), the following assumptions about the error term (ϵ) must hold:

Linearity: The relationship between X and Y must be linear in the parameters.

No Multicollinearity: The independent variables (X 
i
​	
 ) should not be highly correlated with each other. High correlation makes the individual coefficient estimates unreliable.

Homoscedasticity: The variance of the residuals must be constant across all levels of the predictor variables. (The spread of the errors is the same everywhere).

Independence of Errors: The residuals must be independent of each other (especially relevant for time-series data).

Normality of Errors (for Inference): The residuals should be approximately normally distributed (required for reliable hypothesis testing and confidence intervals, but not for OLS estimation itself).
