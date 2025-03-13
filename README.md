This collection of tutorials covers key econometric concepts and their practical implementation using Python. Each tutorial focuses on different aspects of estimation, hypothesis testing, and model evaluation through simulations and real-world data.

Tutorial 1: Estimation and Properties of Estimators
Objective: Estimate the mean and variance of an unknown distribution using data drawn from a uniform distribution.
Topics Covered:
Estimation of mean and variance
Checking for bias and consistency of estimators
Central Limit Theorem (CLT) verification
Methods: Repeated sampling and plotting to assess estimator properties.



Tutorial 2: Unbiased Estimation and Hypothesis Testing
Objective: Understand and apply unbiased estimators and confidence intervals.
Topics Covered:
Estimation of population parameters (mean and variance)
Hypothesis testing for known and unknown variance
Building 95% confidence intervals for different distributions (Normal, Uniform)



Tutorial 3: Ordinary Least Squares (OLS) Estimation
Objective: Perform OLS regression on production data and evaluate model performance.
Topics Covered:
Log transformation of Cobb-Douglas production function data
Estimation of coefficients using OLS
Variance estimation and hypothesis testing (t-statistics, Wald tests)
Confidence interval calculation for estimated parameters



Tutorial 4: Advanced OLS and Hypothesis Testing
Objective: Extend OLS methods and conduct comprehensive hypothesis testing.
Topics Covered:
Estimation of parameters and variance using matrix algebra
Calculation of t-statistics for individual coefficients
Construction of confidence intervals
Wald tests for multiple linear restrictions and joint hypotheses



Tutorial 5: Simple Linear Regression and Statistical Inference
Objective: Simulate and analyze simple linear regression with two regressors.
Topics Covered:
Data generation and visualization
Estimation of regression coefficients using the plug-in method
Distribution of estimators and hypothesis testing
Calculation of t-statistics, confidence intervals, and Wald tests


6.  
Instrumental Variables and Endogeneity Analysis
This project focuses on addressing endogeneity issues in wage determination by using instrumental variables and a two-stage least squares (2SLS) approach. The analysis is based on the MROZ.csv dataset and involves performing manual calculations for standard errors, hypothesis testing, and regression analysis.

Objectives
OLS Regression: Estimate the relationship between log wages and various explanatory variables like education, experience, and family structure.
Endogeneity Detection: Identify potential endogeneity in the education variable.
Two-Stage Least Squares (2SLS): Correct for endogeneity by using parents’ education as instrumental variables.


Methodology
Stage I Regression: Regress education on exogenous variables (like parental education and experience) to obtain fitted values.
Stage II Regression: Use the fitted education values to estimate the effect on log wages, addressing endogeneity.
Standard Errors: Manually calculate standard errors of coefficients in both stages.


Hypothesis Testing:
Joint hypothesis on the significance of instrumental variables.
Test for exogeneity of the education variable using a formal statistical test.
Key Tests and Statistics
Wald Test: For joint hypothesis on the significance of instruments.
Exogeneity Test: Based on the difference in variance between OLS and 2SLS estimates.c
