# Margin of Error Distribution

This is the repo for the distribution of the Monte Carlo simulation for margin of error. The github pages website for the 3d plot of the distribution is here.



## **Formula and Parameter Distributions**

**Formula:**

$$me = z^* \frac{s}{\sqrt{n}}$$

s - sample standard deviation

n - sample size

$z^*$ - 1.96 (95% Confidence Interval)

**Parameter Distributions for simulaion:**

- $s \sim U(1, 200)$
- $n \sim U(30, 500)$

_We will do 10,000 MC simulations._
