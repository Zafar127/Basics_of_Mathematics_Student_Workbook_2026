# Exercise 1 — Dominant Terms in a Sequence

## Question

Compute
$$\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.$$
Explain why the highest-degree terms determine the result.

## Solution

Divide the numerator and denominator by \(n^2\):
\[
\frac{4n^2-3n+1}{2n^2+5n-7}
=\frac{4-\frac3n+\frac1{n^2}}{2+\frac5n-\frac7{n^2}}
\longrightarrow \frac42=2.
\]
The terms of lower degree, after division by \(n^2\), tend to zero. Thus the leading terms determine the limit.