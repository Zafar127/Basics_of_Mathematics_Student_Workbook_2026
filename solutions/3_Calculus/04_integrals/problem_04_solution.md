# Problem 4 — Substitution and the Chain Rule

## Question

Compute
$$\int 2x(x^2+1)^4\,dx.$$
Before calculating, identify a candidate for the new variable $u$ and show that its derivative appears in the integral. Finally, verify the result by differentiation.

## Solution

Set \(u=x^2+1\), so \(du=2x\,dx\). Then
\[
\int2x(x^2+1)^4\,dx=\int u^4\,du=\frac{u^5}{5}+C
=\frac{(x^2+1)^5}{5}+C.
\]
Differentiating gives \(2x(x^2+1)^4\).