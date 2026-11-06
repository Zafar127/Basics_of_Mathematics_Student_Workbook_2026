# Exercise 12 — Recognizing a Surface from Cross-Sections

## Question

A surface has a point as its section at \(z=0\), circular sections of increasing radius for \(z>0\), and parabolic vertical sections through the \(Oz\) axis. Propose a simple equation and justify it.

## Solution

The simplest choice is the circular paraboloid
\[
z=x^2+y^2.
\]
Its section at \(z=0\) is the origin; at \(z>0\), \(x^2+y^2=z\) is a circle of radius \(\sqrt z\); and the vertical sections \(x=0\) or \(y=0\) are parabolas.

More generally, any vertical plane through the \(Oz\) axis contains a radial direction \((\cos\theta,\sin\theta)\). Parameterize points in it by \(x=r\cos\theta,\ y=r\sin\theta\). On the surface,
\[
z=x^2+y^2=r^2(\cos^2\theta+\sin^2\theta)=r^2,
\]
so every such vertical section is a parabola, not only the two coordinate-plane sections.