# Generalized Linear Models

## What are Linear Models

Kinear models are any models that assumes linearity in a system

Now the assumptions linear models make are

- The y's (observations) are independent

- The observations are drawn from a normal distributions

$$
y \space\text{~}\space \textbf{N}(\mu_i, \sigma^2)
$$

- The means ($\mu_i$) are related to predictor values ($x_i$) by a linear model

so it looks like $\beta_0 + x_1 * \beta_1 + x_2 * \beta_2 ...$

- We use both Least Squares and MLE

Now where do we get this eq?

$\beta_0 + x_1 * \beta_1 + x_2 * \beta_2 ...$

Fir this lets take a look at least squares

not typing it out

Now taking the generic line equations

$y = mx + b$

we get

$$
((mx_1 + b) - y_1)^2 + ((mx_2 + b) - y_2)^2 ...
$$

now my questions is how do i show $\beta_0 + x_1 * \beta_1 + x_2 * \beta_2 ...$?