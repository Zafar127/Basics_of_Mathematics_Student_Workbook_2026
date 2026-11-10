# Problem 14 — Continuity and Differentiability

## Question

Investigate the behavior at $x=0$ of
$$f(x)=\begin{cases}x^2,&x\ge0,\\ax,&x<0.\end{cases}$$
For which values of $a$ is the function continuous? For which values do the one-sided derivatives exist and agree? For which value of $a$ is the function differentiable? Explain why continuity alone is not sufficient.

## Solution

At zero, \(f(0)=0\). The right-hand limit is \(0\), and the left-hand limit \(ax\to0\) for every real \(a\); thus the function is continuous for every \(a\).

For \(x>0\), \(f'(x)=2x\), so the right derivative at zero is \(0\). For \(x<0\), \(f'(x)=a\), so the left derivative at zero is \(a\). Both one-sided derivatives exist for every \(a\), and agree exactly when \(a=0\). Therefore \(f\) is differentiable at zero only for \(a=0\). Continuity does not ensure that the two one-sided slopes agree.