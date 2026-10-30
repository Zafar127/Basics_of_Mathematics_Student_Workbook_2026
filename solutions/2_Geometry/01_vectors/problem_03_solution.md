# Exercise 3 — Vector Normalization

## Question

For \(v=(3,4)\), find a unit vector \(e\) with the same direction and orientation. Check that \(\|e\|=1\), reconstruct \(v=\|v\|e\), and explain what changes during normalization and what remains unchanged.

## Solution

The length is \(\|v\|=\sqrt{3^2+4^2}=5\). Divide by this positive length:
\[
e=\frac{v}{\|v\|}=\left(\frac35,\frac45\right).
\]
Indeed,
\[
\|e\|=\sqrt{\frac9{25}+\frac{16}{25}}=1,\qquad
\|v\|e=5\left(\frac35,\frac45\right)=(3,4)=v.
\]
Normalization changes the length to \(1\), while preserving the original direction and orientation.