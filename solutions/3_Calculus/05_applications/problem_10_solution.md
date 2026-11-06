# Problem 10 — A Cable Through Water and Land

## Solution

Let \(x\) be the signed distance along the far bank from the point directly opposite \(A\) to the cable's exit point, positive toward \(B\). The domain is \(x\in\mathbb R\). The underwater length is \(\sqrt{100^2+x^2}\), and the land length to \(B\) is \(|500-x|\). If the land cost per meter is \(c>0\), the total cost is
\[
C(x)=c\left(2\sqrt{10000+x^2}+|500-x|\right).
\]
For \(x<500\), \(C'(x)/c=2x/\sqrt{10000+x^2}-1\); its zero is \(x=100/\sqrt3\). For \(x<0\) this derivative is negative, and for \(100/\sqrt3<x<500\) it is positive. For \(x>500\), \(C'(x)/c=2x/\sqrt{10000+x^2}+1>0\). Therefore the unique global minimum is at
\[
x=\frac{100}{\sqrt3}\text{ m}\approx57.7\text{ m}
\]
toward \(B\) from the point opposite \(A\). The exit point lies between the two perpendicular bank points; the corner at \(x=500\) cannot be a minimum because the cost is increasing there on both sides.