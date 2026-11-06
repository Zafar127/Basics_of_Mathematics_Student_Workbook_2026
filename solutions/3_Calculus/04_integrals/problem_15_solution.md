# Problem 15 — Recovering a Function from Its Derivative

## Solution

Use substitution \(u=x^2\), \(du=2x\,dx\):
\[
F'(x)=2xe^{x^2}\quad\Longrightarrow\quad F(x)=e^{x^2}+C.
\]
The condition \(F(0)=3\) gives \(1+C=3\), hence \(C=2\) and \(F(x)=e^{x^2}+2\). Its derivative is \(2xe^{x^2}\), and \(F(0)=3\), verifying both conditions.