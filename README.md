# Prob-Stats-Fundamentals-Linear-Regression

Welcome to **Prob-Stats-Fundamentals-Height-Weight**! This repository is part of my fundamentals series, where I explore core concepts in **probability**, **statistics**, and **data analysis** through practical examples. This project focuses on **simple linear regression** to estimate weight as a function of height using the ANSUR II dataset.

---

## Problem Statement

The table in `ANSUR II MALE Public.csv` reports physical measurements of members of the US army. In this problem, we will work with **simple linear regression** to estimate weight (`Weightlbs`) as a function of height (`Heightin`). Let \( h \) represent height (in inches) and \( w \) represent weight (in pounds).

---

## Tasks

### (a) OLS Estimator
- Compute the OLS estimator of weight given height.
- Add the regression line to a scatterplot (with \( h \) on the x-axis and \( w \) on the y-axis).
- Provide the OLS estimator in equation form:  
  \[
  \hat{w} = \hat{\beta_0} + \hat{\beta_1} h
  \]

### (b) Covariance Between Height and Residuals
- Compute the sample covariance between height and the residuals of the OLS estimator.
- Are they correlated? Interpret the result.

### (c) Interpretation of Slope Coefficient
- Interpret the slope coefficient \( \hat{\beta_1} \).

### (d) Variance of Weight, OLS Estimator, and Residuals
- Compute the sample variance of the weight, the OLS estimator of the weight, and the residual.
- What relationship do you find among these three values?

### (e) Coefficient of Determination
- Compute the sample coefficient of determination (fraction of variance explained by the linear estimator).
- Compare it to the squared sample correlation coefficient.

### (f) Reverse OLS Estimator
- Compute the OLS estimator of \( h \) given \( w \).
- Rearrange this formula to express \( w \) as a function of \( h \):  
  \[
  \tilde{w} = \tilde{\beta_0} + \tilde{\beta_1} h
  \]
- Add this line to the scatterplot (in a different color) and compare it with the initial OLS line.


