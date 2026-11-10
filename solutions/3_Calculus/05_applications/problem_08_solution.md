# Problem 8 — Number of Requests Handled by a Server

## Question

The rate at which requests arrive at a server during the first 5 minutes is described by the function
$$
r(t)=100+20t\quad [\text{requests/min}],\qquad 0\le t\le5.
$$

1. Compute the total number of requests that arrived during this time.
2. Compute the average rate of incoming requests over this interval.
3. Compare the average rate with the values $r(0)$ and $r(5)$.

## Solution

The total is the integral of the arrival rate:
\[
\int_0^5(100+20t)\,dt
=\left[100t+10t^2\right]_0^5=750\text{ requests}.
\]
The average rate is \(750/5=150\) requests/min. The endpoint rates are \(r(0)=100\) and \(r(5)=200\) requests/min, so the average lies between them (and is their midpoint because the rate is linear).