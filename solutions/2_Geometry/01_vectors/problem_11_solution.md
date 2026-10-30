# Exercise 11 — Decomposition into Parallel and Perpendicular Components

## Question

Decompose \(u=(3,4)\) into components parallel and perpendicular to \(v=(1,2)\). Check \(u=u_{\parallel}+u_{\perp}\) and \(u_{\perp}\cdot v=0\), and explain why these are two independent checks.

## Solution

Since \(u\cdot v=11\) and \(v\cdot v=5\), the parallel component is
\[
u_{\parallel}=\operatorname{proj}_v u=\frac{11}{5}(1,2)=\left(\frac{11}{5},\frac{22}{5}\right).
\]
The perpendicular component is
\[
u_{\perp}=u-u_{\parallel}
=\left(\frac45,-\frac25\right).
\]
Their sum reconstructs \(u\), and
\[
u_{\parallel}+u_{\perp}=(3,4),\qquad
u_{\perp}\cdot v=\frac45-\frac45=0.
\]
The sum check confirms reconstruction, while the dot-product check confirms the perpendicular component has the required orientation; neither condition alone guarantees both properties.