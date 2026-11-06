# Exercise 1 — Recognizing Curves from Canonical Form

## Question

Recognize \(x^2+y^2=9\), \(\frac{x^2}{16}+\frac{y^2}{9}=1\), \(y^2=8x\), and \(\frac{x^2}{9}-\frac{y^2}{4}=1\). Identify the important features of each curve and make a labelled sketch of each, using the equation to explain how its type and shape are recognized.

## Solution

1. \(x^2+y^2=9\) is a circle centered at \((0,0)\) with radius \(3\). Its coordinate intercepts are \((\pm3,0)\) and \((0,\pm3)\).
2. \(\frac{x^2}{16}+\frac{y^2}{9}=1\) is an ellipse centered at the origin, with semiaxes \(4\) along \(x\) and \(3\) along \(y\). Its vertices are \((\pm4,0)\) and \((0,\pm3)\), so its longer axis is horizontal.
3. \(y^2=8x=4px\) with \(p=2\), so it is a right-opening parabola with vertex \((0,0)\) and focus \((2,0)\). It is symmetric about the \(x\)-axis.
4. \(\frac{x^2}{9}-\frac{y^2}{4}=1\) is a hyperbola centered at the origin, opening left and right with vertices \((\pm3,0)\) and asymptotes \(y=\pm\frac23x\).

The sketches below are schematic; marked coordinates and lines identify the required features.

**Circle, radius \(3\):**
```text
                  y
                  ^
               (0,3) *
                  .-|-.
(-3,0) *--------- O ---------* (3,0)  -> x
                  | r=3
                  '-|-'
               (0,-3)*
```

**Ellipse, horizontal semiaxis \(4\), vertical semiaxis \(3\):**
```text
                  y
                  ^
               (0,3) *
             .-------.
(-4,0) *---- O -------* (4,0)  -> x
          <--- a=4 --->|
                      b=3
             '-------'
               (0,-3)*
```

**Right-opening parabola, vertex \((0,0)\), focus \((2,0)\):**
```text
                 y
                 ^
                 |       .-'
                 |   .-'
              V(0,0)*----F(2,0)-----> x
                 |   '-.
                 |       '-.
```

**Hyperbola, vertices \((\pm3,0)\), asymptotes \(y=\pm2x/3\):**
```text
                    y
                    ^
       \       )    |    (       /
        \     )     |     (     /
(-3,0)   *---)------O------(---* (3,0)  -> x
        /     )     |     (     \
       /       )    |    (       \
         asymptotes y = ±2x/3
```

The sum of two positive squared terms equal to \(1\) identifies a circle or ellipse; a single squared variable equal to a linear term identifies a parabola; and the difference of squared terms identifies a hyperbola.