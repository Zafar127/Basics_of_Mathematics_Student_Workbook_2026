# Exercise 11 — An \(n\)-th Root

## Question

Compute
$$\lim_{n\to\infty}\sqrt[n]{5^n+2^n}.$$
Explain which term dominates and why the transformation looks different from the case of a quotient of polynomials.

## Solution

Factor out the largest exponential term:
\[
\sqrt[n]{5^n+2^n}
=5\left(1+\left(\frac25\right)^n\right)^{1/n}.
\]
The parenthetical factor is between \(1\) and \(2^{1/n}\), and both bounds tend to \(1\). By squeezing, the limit is \(5\). The term \(5^n\) dominates \(2^n\) because their ratio \((2/5)^n\) tends to zero; factoring a common exponential is the natural analogue of dividing by the highest polynomial power.