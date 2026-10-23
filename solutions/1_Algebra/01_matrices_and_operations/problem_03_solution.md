# Exercise 3: When Can Matrices Be Multiplied?

## Problem Statement

For matrices with sizes $A_{2\times3}$, $B_{3\times4}$, $C_{4\times2}$, and $D_{2\times2}$, determine whether each listed product is defined and give the result size when it is.

## Theoretical Background and Concepts

A product $(m\times n)(p\times q)$ is defined exactly when the inner dimensions agree ($n=p$). Its result has the outer dimensions $m\times q$.

## Detailed Step-by-Step Solution

| Product | Dimension check | Defined? | Result size |
|---|---|---|---|
| $AB$ | $(2\times3)(3\times4)$ | Yes | $2\times4$ |
| $BA$ | $(3\times4)(2\times3)$; $4\ne2$ | No | -- |
| $BC$ | $(3\times4)(4\times2)$ | Yes | $3\times2$ |
| $CB$ | $(4\times2)(3\times4)$; $2\ne3$ | No | -- |
| $AC$ | $(2\times3)(4\times2)$; $3\ne4$ | No | -- |
| $CA$ | $(4\times2)(2\times3)$ | Yes | $4\times3$ |
| $AD$ | $(2\times3)(2\times2)$; $3\ne2$ | No | -- |
| $DA$ | $(2\times2)(2\times3)$ | Yes | $2\times3$ |

## Verification and Consistency Checks

For every defined product, the shared inner dimension cancels and the remaining outer dimensions give the stated result size. The undefined products each have unequal inner dimensions.