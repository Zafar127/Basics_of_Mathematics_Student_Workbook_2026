# Exercise 11 — Two Similar Surfaces

## Question

Compare \(x^2+y^2-z^2=1\) and \(x^2+y^2-z^2=-1\). For several sections \(z=c\), determine existence and radius, describe the difference between the surfaces, and make a qualitative sketch of each.

## Solution

At \(z=c\), the first equation gives
\[
x^2+y^2=1+c^2,
\]
a circle of radius \(\sqrt{1+c^2}\) for every real \(c\). Its narrowest section, at \(c=0\), has radius \(1\); the radius increases in both directions along \(z\). It is a connected, one-sheeted hyperboloid.

The second equation gives
\[
x^2+y^2=c^2-1.
\]
It has circular sections of radius \(\sqrt{c^2-1}\) when \(|c|>1\), a single point at \(c=\pm1\), and no real section when \(|c|<1\). For example, \(c=0\) has no section, \(c=1\) gives a point, and \(c=2\) gives radius \(\sqrt3\). The two separated nappes are a two-sheeted hyperboloid.

```text
One-sheeted hyperboloid                 Two-sheeted hyperboloid
 (waist at z=0 has radius 1)             (no points for -1<z<1)

          z                                      z
          ^                                      ^
       \     /                                \     /
        \   /                                  \   /
         \ /                                    \ /
        (---) z=0, r=1                         * z=1
         / \                                   / \
        /   \                                 /   \
       /     \                               (z>1 section)
   sections exist for every z               <--- gap --->
                                              * z=-1
                                             / \
```

The left surface remains connected through its smallest circular section at \(z=0\); the right surface consists of two separated sheets beginning at \(z=\pm1\).