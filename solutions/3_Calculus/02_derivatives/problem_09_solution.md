# Problem 9 — A Logarithm and the Chain Rule

## Question

For
$$f(x)=\ln(x^2+1)$$
compute the derivative. Then determine the sign of $f'(x)$ for $x<0$, $x=0$, and $x>0$, and describe qualitatively how the function behaves around zero.

## Solution

\[
u=x^2+1,\qquad u'=2x,\qquad (\ln u)'=\frac{u'}u.
\]
Therefore,
\[
f'(x)=\frac{u'}u=\frac{2x}{x^2+1}.
\]
Since the denominator is positive, \(f'<0\) for \(x<0\), \(f'(0)=0\), and \(f'>0\) for \(x>0\). The function decreases toward \(f(0)=0\) from the left and increases from zero on the right, so it has a minimum at \(0\).