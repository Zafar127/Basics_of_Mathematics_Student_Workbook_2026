# Exercise 13 — Fundamental Trigonometric Limit

## Question

Using
$$\lim_{x\to0}\frac{\sin x}{x}=1,$$
compute
$$\lim_{x\to0}\frac{\sin5x}{x},\qquad \lim_{x\to0}\frac{\sin2x}{\sin3x}.$$
In each case, show how you reduce the expression to the fundamental limit.

## Solution

Using \(\lim_{u\to0}\sin u/u=1\),
\[
\frac{\sin5x}{x}=5\frac{\sin5x}{5x}\longrightarrow5.
\]
For the second limit,
\[
\frac{\sin2x}{\sin3x}
=\frac23\frac{\sin2x}{2x}\frac{3x}{\sin3x}
\longrightarrow\frac23\cdot1\cdot1=\frac23.
\]
Both arguments \(2x,3x,5x\) approach zero.