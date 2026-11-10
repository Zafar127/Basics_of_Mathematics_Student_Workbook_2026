# Exercise 7 — Limit at a Point and Canceling a Factor

## Question

Compute
$$\lim_{x\to3}\frac{x^2-4x+3}{x-3}.$$
Explain why the value of the function at $x=3$ is not needed to compute the limit.

## Solution

Factor the numerator and cancel for \(x\ne3\):
\[
\frac{x^2-4x+3}{x-3}
=\frac{(x-1)(x-3)}{x-3}=x-1.
\]
Therefore the limit is \(3-1=2\). A limit depends on values arbitrarily near \(3\), not necessarily the value at \(3\); indeed the original quotient is undefined there, but its nearby values still approach \(2\).