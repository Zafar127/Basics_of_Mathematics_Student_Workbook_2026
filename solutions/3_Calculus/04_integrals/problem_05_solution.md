# Problem 5 — Substitution with an Exponential

## Question

Compute
$$\int xe^{x^2}\,dx.$$
First compare the structure with Problem 4 and explain what is common despite the different appearance of the function.

## Solution

Set \(u=x^2\), so \(du=2x\,dx\). As in the preceding problem, the derivative of the inner expression is present up to a constant factor:
\[
\int xe^{x^2}\,dx=\frac12\int e^u\,du=\frac12e^{x^2}+C.
\]