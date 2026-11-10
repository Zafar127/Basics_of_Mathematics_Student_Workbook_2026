# Problem 3 — A Rational Function

## Question

Analyze the domain, zeros, asymptotes, and monotonicity of
$$f(x)=\frac{x+1}{x-2}.$$
Finally, sketch a graph consistent with all the information obtained.

## Solution

\[
f(x)=\frac{x+1}{x-2}=1+\frac3{x-2}.
\]
The domain excludes \(2\). The only zero is \(x=-1\); the vertical asymptote is \(x=2\), and the horizontal asymptote is \(y=1\). Also
\[
f'(x)=-\frac3{(x-2)^2}<0,
\]
so \(f\) decreases on each of \((-\infty,2)\) and \((2,\infty)\). On the left it approaches \(1\) from below at \(-\infty\) and \(-\infty\) at \(2^-\); on the right it decreases from \(+\infty\) at \(2^+\) toward \(1\) from above.

```text
 y
 ↑                   │  ╲
 1 ··················│···╲······  y=1
 0 ───────●──────────│─────╲────→ x
         (-1,0)      2
 |          ╲        │
 |            ╲      │
 |              ╲    ↓
 ```

The two branches are decreasing, with vertical asymptote \(x=2\); the left branch crosses at \((-1,0)\), and both approach the horizontal asymptote \(y=1\) at their respective infinite ends.