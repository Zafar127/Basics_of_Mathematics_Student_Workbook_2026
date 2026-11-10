# Exercise 9 — One-Sided Limits and an Asymptote

## Question

Analyze the left-hand and right-hand limits of
$$f(x)=\frac1{x-2}$$
as $x\to2$. Does the two-sided limit exist? Interpret the result on a sketch of the graph and identify the vertical asymptote.

## Solution

As \(x\to2^-\), \(x-2\) is negative and approaches zero, so \(1/(x-2)\to-\infty\). As \(x\to2^+\), the denominator is positive and approaches zero, so \(1/(x-2)\to+\infty\). The two-sided limit does not exist (the one-sided limits differ). The graph has vertical asymptote \(x=2\), with the left branch falling and the right branch rising without bound near it.

```text
 y
 ↑                 │       ╭────
 0 ────────────────┼──────╯────────→ x
      ─────╮       │
           ╰──╮    │
              ╰────↓
                  x=2
 ```

The left branch is below the horizontal axis and tends to \(-\infty\) as \(x\to2^-\); the right branch is above it and tends to \(+\infty\) as \(x\to2^+\).