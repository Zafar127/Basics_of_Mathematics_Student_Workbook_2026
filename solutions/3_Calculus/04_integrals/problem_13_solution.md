# Problem 13 — An Integral Depending on the Upper Limit

## Question

Let
$$F(x)=\int_0^x(t^2+1)\,dt.$$
Determine $F(x)$, compute $F'(x)$, and compare the result with the integrand. Explain in your own words why the height of the function describes the local rate of increase of the accumulated area.

## Solution

\[
F(x)=\int_0^x(t^2+1)\,dt=\frac{x^3}{3}+x.
\]
Thus \(F'(x)=x^2+1\), equal to the integrand evaluated at the upper limit. Over a small increase \(\Delta x\), the accumulated area changes approximately by the current height \((x^2+1)\Delta x\), so that height is the local rate of accumulation.