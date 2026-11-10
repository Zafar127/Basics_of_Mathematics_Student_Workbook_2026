# Problem 5 — Distance from Velocity

## Question

The velocity of a car during the first five seconds is described by the function
$$
v(t)=4t+2\quad [\mathrm{m/s}].
$$

Compute the distance traveled and explain why the integral of velocity gives the change in position.

Then answer what would have to be changed in the reasoning if the velocity also took negative values.

## Solution

Since \(v(t)=4t+2>0\) for \(0\le t\le5\), distance equals the change in position:
\[
\int_0^5v(t)\,dt=\left[2t^2+2t\right]_0^5=60\text{ m}.
\]
If \(s(t)\) denotes position, then \(v(t)=s'(t)\), so the Fundamental Theorem of Calculus gives
\[
\int_0^5v(t)\,dt=\int_0^5s'(t)\,dt=s(5)-s(0).
\]
Thus the integral accumulates signed displacement. If velocity can be negative, actual distance is instead \(\int_0^5|v(t)|\,dt\), splitting at any sign changes; the signed integral remains net displacement.