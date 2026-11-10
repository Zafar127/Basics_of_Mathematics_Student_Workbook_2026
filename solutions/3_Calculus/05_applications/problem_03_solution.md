# Problem 3 — A Box Made from Cardboard

## Question

From a $30\text{ cm}\times40\text{ cm}$ sheet, squares of side length $x$ are cut from the corners and the edges are folded up to form an open box.

Write the volume as a function of $x$, determine the physically meaningful domain, and find the value of $x$ for which the volume is greatest.

## Solution

After cutting squares of side \(x\), the box has height \(x\) and base sides \(30-2x\) and \(40-2x\). Thus
\[
V(x)=x(30-2x)(40-2x),\qquad 0<x<15.
\]
Differentiating the expanded expression \(1200x-140x^2+4x^3\) gives
\[
V'(x)=12x^2-280x+1200.
\]
Its roots are \(x=(35\pm5\sqrt{13})/3\); only the smaller root lies in the domain. The derivative is positive before and negative after this root, and the volume is zero at the domain boundaries, so the maximum occurs at
\[
x=\frac{35-5\sqrt{13}}3\ \text{cm}\approx5.66\ \text{cm}.
\]