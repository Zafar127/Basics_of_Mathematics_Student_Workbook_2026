# Problem 7 — Exponential Growth

## Question

Assume the model
$$
N(t)=N_0e^{kt},\qquad k>0.
$$

1. Verify by differentiation that the model satisfies the relation $N'(t)=kN(t)$.
2. Find the population doubling time.
3. Explain why the doubling time does not depend on $N_0$.

## Solution

\[
N'(t)=kN_0e^{kt}=kN(t),
\]
so the model satisfies the stated growth relation. The doubling time \(T\) obeys \(N_0e^{kT}=2N_0\), hence
\[
T=\frac{\ln2}{k}.
\]
The initial value cancels from the doubling equation, so the time depends on the proportional growth rate \(k\), not on \(N_0\).