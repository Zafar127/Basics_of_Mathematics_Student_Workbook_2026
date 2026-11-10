# Problem 9 — Minimizing Material for a Can

## Question

A closed cylinder has fixed volume $V$.

1. Write the volume constraint.
2. Eliminate one of the variables.
3. Express the surface area as a function of the radius $r$.
4. Find the relation between the height $h$ and the radius $r$ for which the material usage is minimal.

Interpret the obtained relation geometrically.

## Solution

For radius \(r>0\) and height \(h>0\), the fixed-volume condition is \(V=\pi r^2h\), so \(h=V/(\pi r^2)\). The closed cylinder's surface area becomes
\[
S(r)=2\pi r^2+2\pi rh=2\pi r^2+\frac{2V}{r}.
\]
Then \(S'(r)=4\pi r-2V/r^2\), which vanishes when \(2\pi r^3=V\). At this point
\[
h=\frac{V}{\pi r^2}=2r.
\]
Also \(S''(r)=4\pi+4V/r^3>0\), so this is a minimum (and the area tends to infinity at both ends of \(r>0\)). The optimal height equals the cylinder's diameter.