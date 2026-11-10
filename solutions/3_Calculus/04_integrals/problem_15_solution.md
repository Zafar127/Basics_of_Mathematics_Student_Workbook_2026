# Problem 15 — Recovering a Function from Its Derivative

## Question

The function $F$ satisfies
$$F'(x)=2xe^{x^2}$$
and
$$F(0)=3.$$

1. Recognize the method needed to find the function $F$.
2. Determine the entire family of functions with the given derivative.
3. Use the condition $F(0)=3$ to determine the correct constant.
4. Verify the final result by differentiation and substitution of $x=0$.

## Solution

Use substitution \(u=x^2\), \(du=2x\,dx\):
\[
F'(x)=2xe^{x^2}\quad\Longrightarrow\quad F(x)=e^{x^2}+C.
\]
The condition \(F(0)=3\) gives \(1+C=3\), hence \(C=2\) and \(F(x)=e^{x^2}+2\). Its derivative is \(2xe^{x^2}\), and \(F(0)=3\), verifying both conditions.