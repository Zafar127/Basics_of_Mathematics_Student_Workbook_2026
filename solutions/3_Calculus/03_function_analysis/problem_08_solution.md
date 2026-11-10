# Problem 8 — The Second Derivative

## Question

For
$$f(x)=x^4-4x^2$$
find the local extrema, intervals of convexity and concavity, and inflection points. Sketch the graph and mark all the identified features on it.

## Solution

\[
f'(x)=4x(x^2-2),\qquad f''(x)=12x^2-8.
\]
The sign of \(f'\) is \(-,+,-,+\) on the successive intervals split by \(-\sqrt2,0,\sqrt2\). Thus \(f\) decreases, increases, decreases, then increases; the sign changes give local minima \((\pm\sqrt2,-4)\) and a local maximum \((0,0)\).

Since \(f''=4(3x^2-2)\), it is positive for \(|x|>\sqrt{2/3}\) and negative for \(|x|<\sqrt{2/3}\). The graph is therefore convex outside and concave inside these points, with inflection points \(\left(\pm\sqrt{2/3},-20/9\right)\). The sign changes of \(f'\) classify the extrema, and the sign changes of \(f''\) classify the inflection points.

```text
 y
 ↑     ╲                         ╱
 0 ─────╲───────• (0,0)────────╱────→ x
          ╲ I╱       ╲I      ╱
           ╲╱         ╲╲    ╱
            •         •
       (-√2,-4)    (√2,-4)
 ```

The marked inflection points are \(I_\pm=(\pm\sqrt{2/3},-20/9)\). The function is even, so the two sides are mirror images, and it tends to \(+\infty\) at both ends.