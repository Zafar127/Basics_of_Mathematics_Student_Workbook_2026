# Problem 11 — Volume of a Solid of Revolution

## Question

The region under the graph
$$
y=\sqrt{x},\qquad x\in[0,4],
$$
is rotated about the $x$-axis.

1. Construct the integral describing the volume using the disk method.
2. Compute the volume.
3. Explain where the factor $\pi y^2$ in the integral comes from.

## Solution

Rotating a vertical slice of height \(y=\sqrt{x}\) about the \(x\)-axis gives a disk of radius \(\sqrt{x}\) and area \(\pi(\sqrt{x})^2=\pi x\). Therefore
\[
V=\pi\int_0^4(\sqrt{x})^2\,dx
=\pi\int_0^4x\,dx
=8\pi.
\]
The factor \(\pi y^2\) is the area of each circular cross-section perpendicular to the axis of rotation.