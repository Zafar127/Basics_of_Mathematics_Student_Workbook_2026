# Problem 5 — An Exponential Function with a Maximum

## Question

Analyze the monotonicity and extrema of
$$f(x)=xe^{-x}.$$
Also examine the behavior as $x\to\infty$ and explain how the limit affects the shape of the graph on the right-hand side.

## Solution

\[
f'(x)=\frac{d}{dx}(x)e^{-x}+x\frac{d}{dx}(e^{-x})
=e^{-x}-xe^{-x}=e^{-x}(1-x).
\]
Because \(e^{-x}>0\), \(f\) increases for \(x<1\) and decreases for \(x>1\), giving a maximum at \(x=1\) with value \(1/e\). As \(x\to\infty\), \(xe^{-x}\to0^+\). The right-hand branch therefore falls toward the horizontal asymptote \(y=0\), without crossing it for \(x>0\).

Indeed, \(xe^{-x}=x/e^x\to0\) because the exponential \(e^x\) grows faster than the linear numerator \(x\). Thus the graph approaches \(y=0\) from above on the right.