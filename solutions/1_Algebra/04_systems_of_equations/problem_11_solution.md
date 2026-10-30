# Exercise 11 — A Parameter in a System of Three Equations

## Question

Analyze the number of solutions depending on $t$:
$$\begin{cases}x+y+z=1,\\x+ty+z=2,\\x+y+tz=3.\end{cases}$$
Use elimination and separately analyze the parameter values for which a standard calculation step ceases to be valid.

## Solution

Subtract the first equation from the second and third:
\[
(t-1)y=1,\qquad (t-1)z=2.
\]
If \(t\ne1\), then \(y=1/(t-1)\), \(z=2/(t-1)\), and
\[
x=1-y-z=1-\frac{3}{t-1}.
\]
There is exactly one solution for each \(t\ne1\). For \(t=1\), the second equation has the same left-hand side as the first but right-hand side \(2\) instead of \(1\); elimination gives \(0=1\), so there is no solution. Dividing by \(t-1\) is invalid at this exceptional value, which must be checked separately.
