# Lab11
Biostat1 Lab11


### 1. Create a GitHub repository Lab11

<br><br>

### 2. Submit your code for all problems from **Activity11**.

<br>

#### Question 1
Write a function that generates numbers from $B(n, p)$ distribution using `runif()` function. 

+ Hint: $B(n, p)$ random variable can be defined as a sum of n independent *Bernoulli(p)* random variables.

<br>

#### Question 2
Compare performance of your function with `rbinom()` using `microbenchmark()` function.

<br>

#### Question 3
Suppose we want to simulate data from a linear regression model:

<p align="center">
<img src = 'https://ws1.sinaimg.cn/large/006tNbRwly1fxgcsuhyd6j30jj02faa6.jpg'>
</p>
<br>

Let beta_0=15 and beta_1=0.4 are known coefficients. Generate data (N=50) from this models with given coefficients. Fit a linear regression model and plot fitted values vs. residuals using `ggplot()` function. Please do not forget to use `set.seed()` function for reproductibility.

<br>

#### Question 4
Box-Muller algorithm: generate U_1 and U_2 two independent uniform (0, 1) random variables and set:

<p align="center">
<img src = 'https://ws1.sinaimg.cn/large/006tNbRwly1fxgqt6hpblj309i042t8q.jpg'>
</p>
<br>

are two independent normal variables. Write a function that generates normal variates using Box-Muller
algorithm. Compare simulated data from your function with simulated data from `rnorm()` function using `ggplot()` (histogram?).

<br><br>

### 3. Please make sure your code is formatted according to the style guide.
