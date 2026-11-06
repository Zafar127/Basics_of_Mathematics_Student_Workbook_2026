# Problem 8 — Number of Requests Handled by a Server

## Solution

The total is the integral of the arrival rate:
\[
\int_0^5(100+20t)\,dt
=\left[100t+10t^2\right]_0^5=750\text{ requests}.
\]
The average rate is \(750/5=150\) requests/min. The endpoint rates are \(r(0)=100\) and \(r(5)=200\) requests/min, so the average lies between them (and is their midpoint because the rate is linear).