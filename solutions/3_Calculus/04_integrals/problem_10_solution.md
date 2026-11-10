# Problem 10 — Definite Integral and Estimation

## Question

Before carrying out the exact calculation, estimate the possible range of values of the integral
$$\int_0^2(x^2+1)\,dx,$$
using
$$1\le x^2+1\le5$$
on $[0,2]$. Only then compute the integral exactly, compare the result with the earlier estimate, and explain what type of computational error such a check can detect.

## Solution

Since \(1\le x^2+1\le5\) on an interval of length \(2\),
\[
2\le\int_0^2(x^2+1)\,dx\le10.
\]
Exactly,
\[
\int_0^2(x^2+1)\,dx=\left[\frac{x^3}{3}+x\right]_0^2
=\frac83+2=\frac{14}{3}.
\]
This lies in the estimated range. Such a bound can expose a result that is implausibly too large or too small, though it does not by itself prove the exact arithmetic.