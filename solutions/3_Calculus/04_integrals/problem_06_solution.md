# Problem 6 — The Logarithmic Antiderivative

## Solution

Set \(u=x^2+5\), so \(du=2x\,dx\). Therefore
\[
\int\frac{2x}{x^2+5}\,dx=\int\frac{du}{u}=\ln|u|+C
=\ln(x^2+5)+C.
\]
The logarithm appears because the integrand is the derivative of its denominator divided by that denominator; \(x^2+5>0\) for all real \(x\).