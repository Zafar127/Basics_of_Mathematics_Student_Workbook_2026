# Problem 15 — Correcting a Monotonicity Analysis

## Question

For the function
$$f(x)=x^3-3x$$
the derivative was correctly computed as
$$f'(x)=3(x-1)(x+1).$$

However, a student wrote the following conclusion:

> The derivative is positive between its zeros and negative outside them. Therefore, the function is decreasing on $(-\infty,-1)\cup(1,\infty)$, increasing on $(-1,1)$, has a local minimum at $x=-1$, and a local maximum at $x=1$.

1. Without differentiating again, explain why merely identifying the zeros of the derivative does not justify the stated sign chart, and find the error in the student's reasoning.
2. Construct the correct sign chart for $f'(x)$.
3. Give the correct intervals of monotonicity and the character of the extrema.
4. In each of the three intervals, choose one simple test point and show that the sign of the derivative confirms your classification.

## Solution

Knowing only the zeros of a derivative does not determine its signs; the sign must be checked on the intervals separated by the zeros. Here
\[
f'(x)=3(x-1)(x+1).
\]
Its sign chart is positive on \((-\infty,-1)\), negative on \((-1,1)\), and positive on \((1,\infty)\). The student's claim reversed the signs inside and outside the roots.

Therefore \(f\) increases on \((-\infty,-1)\), decreases on \((-1,1)\), and increases on \((1,\infty)\). There is a local maximum at \(x=-1\) and a local minimum at \(x=1\). Test points confirm the signs: \(f'(-2)=9>0\), \(f'(0)=-3<0\), and \(f'(2)=9>0\).