# Problem 5 — Distance from Velocity

## Solution

Since \(v(t)=4t+2>0\) for \(0\le t\le5\), distance equals the change in position:
\[
\int_0^5v(t)\,dt=\left[2t^2+2t\right]_0^5=60\text{ m}.
\]
The integral of velocity accumulates signed displacement. If velocity can be negative, actual distance is instead \(\int_0^5|v(t)|\,dt\), splitting at any sign changes; the signed integral remains net displacement.