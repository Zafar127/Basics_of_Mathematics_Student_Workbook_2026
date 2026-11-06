# Exercise 10 — Paraboloids

## Question

Compare \(z=x^2+y^2\) and \(z=x^2-y^2\). For each surface describe the sections \(x=0\), \(y=0\), and \(z=c\), then make a qualitative sketch showing its vertical and representative horizontal sections.

## Solution

For \(z=x^2+y^2\):
- \(x=0\) gives \(z=y^2\), an upward-opening parabola in the \(yz\)-plane.
- \(y=0\) gives \(z=x^2\), an upward-opening parabola in the \(xz\)-plane.
- \(z=c\) gives \(x^2+y^2=c\): a point for \(c=0\), circles for \(c>0\), and no real points for \(c<0\).

This is an upward-opening circular bowl (an elliptic paraboloid).

For \(z=x^2-y^2\):
- \(y=0\) gives \(z=x^2\), while \(x=0\) gives \(z=-y^2\), a downward-opening parabola.
- \(z=c\) gives \(x^2-y^2=c\), a hyperbola for \(c\ne0\) and the intersecting lines \(y=\pm x\) for \(c=0\).

The opposite curvatures in perpendicular vertical sections produce a saddle (a hyperbolic paraboloid).

Schematic sketches (vertical side sections are shown; horizontal sections are described by their equations):

**Elliptic paraboloid \(z=x^2+y^2\), with horizontal circles \(x^2+y^2=c\) for \(c>0\):**
```text
             z
             ^
             |         \     /
             |          \   /     vertical sections: upward parabolas
             |           \_/
             |          (---)     z=c>0: circle, radius √c
             |            O
             +------------------> x (y=0 section)
```

**Hyperbolic paraboloid \(z=x^2-y^2\), with horizontal hyperbolas \(x^2-y^2=c\):**
```text
              z
              ^
       x=0    |    y=0
       down   |    up
         \    |    /
          \   |   /
           \__O__/       saddle at the origin
          /       \
         /         \
      horizontal sections are hyperbolas (lines y=±x when c=0)
```

In the first sketch both perpendicular vertical sections open upward; in the saddle one opens upward and the perpendicular one downward.