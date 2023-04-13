# Advanced-Stats5

# Bootstrap Sampling
This repository contains the solution to the bootstrap sampling problem, where we obtain a bootstrap sample B = {b1, . . . , bn} from n observations. We are asked to answer the following questions:

What is the probability that the first bootstrap sample point b1 is not the jth observation?
What is the probability that the jth observation is not a part of the bootstrap sample?
What happens as n → ∞?
Create a plot that displays, for each integer value of n from 1 to 100,000, the probability that the jth observation is in the bootstrap sample. Comment based on the answer to the previous question.
Bootstrap for Regression

This repository contains the solution to the applied problem of bootstrap for regression, where we consider the Auto dataset from the ISLR2 library.

# We perform the following tasks:

First, we run an OLS between mpg ∼ horsepower and obtain the standard errors of the coefficients that is returned by the package.

Next, we use bootstrap to obtain the standard errors of the estimates. We look at the coefficients of linear regression for each bootstrap sample and compute the standard error from these estimates.

We rerun the above two steps for mpg ∼ horsepower + I(horsepower2).

We comment on observations. In which case do we have a closer match? In which case are errors by regression more inflated as compared to bootstrap? In 1-2 sentences, we comment on why this is the case.

We also provide an algorithm for residual bootstrap.

# Hypothesis Testing using Bootstrapping
This repository contains the solution to the hypothesis testing problem using bootstrapping, where we look at the percentage of ethanol in gasoline obtained from two different gas stations. We find the following percentages between the two gas stations: From station A, we found the following percentages (10.2,8.1,9.4, 8.7, 9.2, 7.5,9.9, 8.9, 10.1). From station B we find the following ethanol percentages in the 10 samples of gasoline (9.4, 7.1, 7.9, 8.5, 8.1, 8, 5.7, 7.5, 9).

We perform the following tasks:

We run a t-test to obtain the difference in samples.
We discuss whether the t-test is appropriate here or not and why.
We use the bootstrap to calculate the difference between the means of two samples. We also look at the 95% quantiles (2.5 percentile and 97.5 percentile).

# Robust Linear Regression

This repository contains the solution to the robust linear regression problem, where we consider the dataset fat from the package faraway. We perform the following tasks:

We compare the output of linear regression and robust linear regression for the model. For robust linear regression, we use the rlm package. We also comment on the differences.




