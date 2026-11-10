# Problem 13 — A Multi-Layer Composition

## Question

For
$$f(x)=e^{\sin(x^2)}$$
compute the derivative. First write the layers
$$x\longrightarrow x^2\longrightarrow \sin(x^2)\longrightarrow e^{\sin(x^2)}$$
and explain why differentiation moves through them in the reverse order.

## Solution

The layers are \(x\to x^2\to\sin(x^2)\to e^{\sin(x^2)}\). Applying the chain rule from the outside inward,
\[
f'(x)=e^{\sin(x^2)}\cos(x^2)\cdot2x
=2xe^{\sin(x^2)}\cos(x^2).
\]
The order reverses because the outer output changes first in response to a change in its input, after which we multiply by the rate at which that input changes. The factors, with their arguments, are
\[
\underbrace{e^u}_{\text{derivative of }e^u}
\quad\text{at }u=\sin(x^2),\qquad
\underbrace{\cos v}_{\text{derivative of }\sin v}
\quad\text{at }v=x^2,\qquad
\underbrace{2x}_{\text{derivative of }x^2}.
\]
Thus the product is \(e^{\sin(x^2)}\cos(x^2)(2x)\).