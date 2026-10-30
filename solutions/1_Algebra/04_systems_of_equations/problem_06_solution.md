# Exercise 6 — A System with a Parameter

## Question

Analyze, depending on the parameter $a$, the system
$$\begin{cases}x+y=2,\\ax+ay=4.\end{cases}$$

Among the three possibilities — exactly one solution, infinitely many solutions, no solution — determine which actually occur and for which values of $a$. If one type cannot occur, explain why.

## Solution

The second left-hand side is \(a(x+y)\), while the first equation fixes \(x+y=2\). Thus the second equation is consistent precisely when \(2a=4\), or \(a=2\).

- If \(a=2\), the second equation duplicates the first, so there are infinitely many solutions: \(x+y=2\).
- If \(a=0\), the second equation is \(0=4\), so there is no solution.
- If \(a\ne0,2\), the equations require both \(x+y=2\) and \(x+y=4/a\), which conflict; there is no solution.

Exactly one solution never occurs because the two left-hand sides are always proportional, so the equations cannot determine both unknowns independently.
