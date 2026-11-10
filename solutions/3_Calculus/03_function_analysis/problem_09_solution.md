# Problem 9 — An Oblique Asymptote

## Question

Analyze the asymptotes of
$$f(x)=\frac{x^2+1}{x-1}.$$
Perform polynomial division and explain why the remainder term vanishes for large $|x|$.

## Solution

Subtracting \(x(x-1)=x^2-x\) from \(x^2+1\) leaves \(x+1\); subtracting \(x-1\) from that leaves the remainder \(2\). Thus
\[
\frac{x^2+1}{x-1}=x+1+\frac2{x-1}.
\]
Because \(2\) is fixed while \(|x-1|\) grows without bound, \(2/(x-1)\to0\) as \(x\to\pm\infty\). The oblique asymptote is \(y=x+1\). The denominator vanishes at \(x=1\), where the numerator is nonzero, giving vertical asymptote \(x=1\). There is no horizontal asymptote.