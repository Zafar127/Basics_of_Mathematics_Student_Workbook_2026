# Problem 8 — Choosing Factors in Integration by Parts

## Question

Compute
$$\int x\cos x\,dx.$$
Before calculating, justify why it is convenient to differentiate $x$ and integrate $\cos x$, rather than the other way around.

## Solution

Choose \(u=x\) and \(dv=\cos x\,dx\). Differentiating \(x\) simplifies it to \(1\), while \(\cos x\) has the simple antiderivative \(\sin x\). Thus
\[
\int x\cos x\,dx=x\sin x-\int\sin x\,dx
=x\sin x+\cos x+C.
\]
With the reverse choice \(u=\cos x\), \(dv=x\,dx\), we have \(du=-\sin x\,dx\) and \(v=x^2/2\), so
\[
\int x\cos x\,dx=\frac{x^2}{2}\cos x+\frac12\int x^2\sin x\,dx.
\]
This raises the polynomial degree from \(x\) to \(x^2\), making the remaining integral more complicated rather than simpler.