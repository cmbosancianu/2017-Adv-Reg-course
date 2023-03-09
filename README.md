# Advanced Topics in Applied Regression

The course provided a set of tools that can be employed in situations when standard OLS estimation does not produce adequate estimates. Weighted Least Squares and cluster-corrected standard errors were discussed as solutions to the problem of heteroskedasticity, which can severely impact estimates of uncertainty in standard OLS. Interactions can be of help in instances when we have reason to suspect that effects vary across subgroups in the population. Nonlinear regression can handle situations when the relationship between two variables has a more complex form than a simple straight line. Finally, certain types of robust regression serves to produce proper estimates even in situations of data outliers. All these topics were discussed both theoretically, in the lectures, as well as practically, with the use of actual social science data sets and the `R` statistical environment. The topics represent a middle ground between the standard linear regression framework and more advanced GLM procedures, or the multilevel modeling framework.

# Sessions

## OLS assumptions

Topics discussed:

1. Regression assumptions, with particular emphasis on: continuous predictors, normal distribution of errors, homoskedasticity, and linear relationships
2. Diagnostic tools for each of these four assumptions
3. The effect of assumption violations on estimates

## Addressing heteroskedasticity

Topics discussed:

1. The impact of heteroskedasticity on OLS estimates
2. Cluster-corrected SEs (Huber-White) as a solution to heteroscedasticity
3. Where cluster-corrected SEs do not work
4. Weighted Least Squares, in cases of either known or unknown variance structure

## Effect heterogeneity

Topics discussed:

1. Interactions in linear regression: two-way and three-way specifications
2. Overview of interpretation for different types of interaction: continuous $\times$ continuous, dichotomous $\times$ continuous, dichotomous $\times$ dichotomous
3. Graphical methods of presenting marginal effects from interactions
4. Interpreting main effects in linear models with interactions
5. Fixed-effects to model heterogeneity

## Nonlinear regression

Topics discussed:

1. Nonlinear relationships in OLS
2. Data transformations as solution to non-linearity
3. Polynomials
4. Regression splines
5. Semiparametric models


## Robust regression

Topics discussed:

1. The impact of outliers on OLS estimates
2. Diagnostics for outliers
3. *M*-estimation
4. Bounded-influence regression
5. Quantile regression

# Readings

## Day 1

Fox, J. (2008). *Applied Regression Analysis and Generalized Linear Models*. New York: Sage. Chapter 12: "Diagnosing non-normality, nonconstant error variance, and nonlinearity" (pp. 267-306).

## Day 2

Wooldridge, J. M. (2013). *Introductory Econometrics: A Modern Approach*, 5th edition. Mason, OH: Cengage Learning. Chapter 8: "Heteroskedasticity" (pp. 268–302)

## Day 3

Kam, C. D., & Franzese Jr., R. J. (2007). *Modeling and Interpreting Interactive Hypotheses in Regression Analysis*. Ann Arbor, MI: The University of Michigan Press. Chapter 3 ("Theory to practice") and Chapter 4 ("The meaning, use, and abuse of some common general-practice rules"), pp. 13–102.

## Day 4

Fox, J. (2008). *Applied Regression Analysis and Generalized Linear Models*. New York: Sage. Chapter 17: "Nonlinear regression" (pp. 451–475).

Motulsky, H. J., & Ransnas, L. A. (1987). "Fitting curves to data using nonlinear regression: a practical and nonmathematical review." *The FASEB Journal*, **1**(5), 365–374.

## Day 5

Fox, J. (2008). *Applied Regression Analysis and Generalized Linear Models*. New York: Sage. Chapter 11: "Unusual and influential data" (pp. 241–266) and Chapter 19: "Robust regression" (pp. 530-547).