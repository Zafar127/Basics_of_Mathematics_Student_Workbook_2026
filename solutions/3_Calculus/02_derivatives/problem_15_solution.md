# Problem 15 — The Difference Quotient

## Question

Choose one function from the problem set and a point $x_0$ at which the derivative exists. Compute $f'(x_0)$ exactly, and then calculate
$$\frac{f(x_0+h)-f(x_0)}h$$
for $h=1$, $0.1$, and $0.01$. Compare the values with $f'(x_0)$ and explain why the difference quotient approaching a single number is consistent with the definition of the derivative, while a few computations do not replace a limit argument.

## Solution

Choose \(f(x)=x^2\) and \(x_0=2\). The derivative is \(f'(x)=2x\), so \(f'(2)=4\). For \(h\ne0\),
\[
\frac{f(2+h)-f(2)}h
=\frac{(2+h)^2-4}{h}=4+h.
\]
For \(h=1,0.1,0.01\), the quotients are \(5,\ 4.1,\ 4.01\), approaching \(4\). This is consistent with the defining limit; finitely many values illustrate but cannot establish that limit.