# Exercise 12 — Exponential Function Limit

## Question

Compute
$$\lim_{x\to0}(1+3x)^{1/x}.$$
Connect the result with the limit from Exercise 5 and show the appropriate transformation.

## Solution

Set \(u=3x\). Then \(x=u/3\), and
\[
(1+3x)^{1/x}=\left((1+u)^{1/u}\right)^3\longrightarrow e^3
\]
as \(u\to0\), using \(\lim_{u\to0}(1+u)^{1/u}=e\), the real-variable form of the classical limit.