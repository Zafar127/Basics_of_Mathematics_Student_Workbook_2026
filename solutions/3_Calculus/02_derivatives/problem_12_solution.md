# Problem 12 — Several Rules at Once

## Question

For
$$f(x)=(x^2+1)^3e^x$$
compute the derivative. Before calculating, write down a plan: which rule applies to the whole expression and which rule applies to one of its factors. Finally, organize the result by factoring out common factors.

## Solution

Apply the product rule to \((x^2+1)^3e^x\), then the chain rule to the first factor:
\[
f'(x)=3(x^2+1)^2(2x)e^x+(x^2+1)^3e^x.
\]
Factoring common terms,
\[
f'(x)=e^x(x^2+1)^2\bigl(6x+x^2+1\bigr).
\]