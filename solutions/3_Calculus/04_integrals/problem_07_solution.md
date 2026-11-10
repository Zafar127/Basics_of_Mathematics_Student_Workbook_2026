# Problem 7 — Integration by Parts

## Question

Compute
$$\int xe^x\,dx.$$
First write the product differentiation rule and, on that basis, explain the meaning of the integration-by-parts formula. Verify the result by differentiation.

## Solution

The product rule is \((uv)'=u'v+uv'\). Rearranging and integrating yields
\(\int u\,dv=uv-\int v\,du\). Choose \(u=x\), \(dv=e^x\,dx\); then \(du=dx\), \(v=e^x\):
\[
\int xe^x\,dx=xe^x-\int e^x\,dx=e^x(x-1)+C.
\]
Differentiation gives \(xe^x\).