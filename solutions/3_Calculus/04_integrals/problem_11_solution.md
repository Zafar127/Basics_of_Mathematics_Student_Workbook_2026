# Problem 11 — Choosing an Integration Method

## Question

For each integral, first write which method you choose and how you recognize it, and then compute:
1. $\int\sin(3x)\,dx$,
2. $\int x\ln x\,dx$,
3. $\int\frac{x}{\sqrt{x^2+1}}\,dx$.

## Solution

1. Use substitution because the angle \(3x\) is a linear inner function. With \(u=3x\), \(du=3dx\), and \(dx=du/3\),
\[
\int\sin(3x)\,dx
=\frac13\int\sin u\,du
=-\frac13\cos(3x)+C.
\]
2. Use integration by parts: differentiating \(\ln x\) gives \(1/x\), so take \(u=\ln x\), \(dv=x\,dx\) (for \(x>0\)). Then \(du=dx/x\), \(v=x^2/2\), and the remaining integral is
\[
\int v\,du=\frac12\int x\,dx.
\]
Therefore,
\[
\int x\ln x\,dx=\frac{x^2}{2}\ln x-\frac{x^2}{4}+C.
\]
3. Use substitution because the numerator contains the derivative of the expression under the square root. With \(u=x^2+1\), \(du=2x\,dx\), and \(x\,dx=du/2\),
\[
\int\frac{x}{\sqrt{x^2+1}}\,dx
=\frac12\int u^{-1/2}\,du
=\sqrt{x^2+1}+C.
\]