# Problem 13 — A Multi-Layer Composition

## Solution

The layers are \(x\to x^2\to\sin(x^2)\to e^{\sin(x^2)}\). Applying the chain rule from the outside inward,
\[
f'(x)=e^{\sin(x^2)}\cos(x^2)\cdot2x
=2xe^{\sin(x^2)}\cos(x^2).
\]
Each factor is the derivative of one layer, evaluated at the output of the preceding layer.