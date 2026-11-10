# Problem 13 — A Logarithm and an Asymptote

## Question

Perform a complete analysis of
$$f(x)=\frac{\ln x}{x},\qquad x>0.$$
Find the maximum and the behavior at the ends of the domain. Explain which information is necessary for a correct sketch.

## Solution

The domain is \(x>0\). Differentiating,
\[
f'(x)=\frac{x(1/x)-\ln x}{x^2}
=\frac{1-\ln x}{x^2}.
\]
Since \(1-\ln x>0\) for \(0<x<e\), equals zero at \(e\), and is negative for \(x>e\), \(f\) increases on \((0,e)\), decreases on \((e,\infty)\), and has global maximum \(f(e)=1/e\). As \(x\to0^+\), \(\ln x/x\to-\infty\); as \(x\to\infty\), \(\ln x/x\to0^+\). Therefore \(x=0\) is a vertical boundary asymptote, and \(y=0\) is a horizontal asymptote at \(+\infty\). These limits, the domain, and the maximum are key to a correct sketch.

The zero is \(x=1\); hence \(f<0\) on \((0,1)\) and \(f>0\) on \((1,\infty)\). The second derivative is
\[
f''(x)=\frac{(1-\ln x)'x^2-2x(1-\ln x)}{x^4}
=\frac{2\ln x-3}{x^3}.
\]
Since \(x^3>0\), \(f''<0\) for \(0<x<e^{3/2}\) and \(f''>0\) for \(x>e^{3/2}\), giving an inflection at
\[
\left(e^{3/2},\frac{3}{2e^{3/2}}\right).
\]
The limit at zero follows because \(\ln x\to-\infty\) while \(x\to0^+\). At infinity, \(\ln x\) grows more slowly than \(x\), so their ratio tends to zero. This also establishes the horizontal asymptote.