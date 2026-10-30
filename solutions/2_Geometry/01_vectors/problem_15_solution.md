# Exercise 15 — Comparing Directions Using the Cosine of the Angle

## Question

Given \(a=(1,2,1)\), \(b=(2,4,2)\), and \(c=(2,0,3)\), compute \(\frac{u\cdot v}{\|u\|\|v\|}\) for each pair and order the pairs by increasing angle. Explain why \(a,b\) give the value \(1\) despite having different lengths.

## Solution

The norms are
\[
\|a\|=\sqrt6,\qquad \|b\|=\sqrt{24}=2\sqrt6,\qquad \|c\|=\sqrt{13}.
\]
For the pair \((a,b)\),
\[
\frac{a\cdot b}{\|a\|\|b\|}
=\frac{12}{\sqrt6(2\sqrt6)}=1.
\]
For the other pairs,
\[
\frac{a\cdot c}{\|a\|\|c\|}
=\frac{5}{\sqrt{78}},\qquad
\frac{b\cdot c}{\|b\|\|c\|}
=\frac{10}{2\sqrt{78}}=\frac{5}{\sqrt{78}}.
\]
Since cosine decreases as the angle increases on \([0,\pi]\), the increasing-angle order is
\[
(a,b)\quad<\quad(a,c)=(b,c).
\]
The value for \(a,b\) is \(1\) because \(b=2a\): the vectors have different lengths but the same direction, so the angle between them is zero.