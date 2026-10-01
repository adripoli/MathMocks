@paper P2 Mock Set 2

@q 1
@topic Logarithms, quadratic, reject a root
@marks 5
@question
(a) Start with $2\log(3 - x) - \log(21 - 2x) = 0$ \\
Use the power law $n\log a = \log(a^{n})$ on the first term: \\
$2\log(3 - x) = \log\left( (3 - x)^{2} \right)$ \\
$\log\left( (3 - x)^{2} \right) - \log(21 - 2x) = 0$ \\
Use the subtraction law $\log a - \log b = \log\frac{a}{b}$: \\
$\log\left( \frac{(3 - x)^{2}}{21 - 2x} \right) = 0$ \\
Since $\log 1 = 0$: \\
$\frac{(3 - x)^{2}}{21 - 2x} = 1$ \\
Multiply both sides by $(21 - 2x)$: \\
$(3 - x)^{2} = 21 - 2x$ \\
Expand the bracket: $(3 - x)(3 - x) = 9 - 3x - 3x + x^{2} = 9 - 6x + x^{2}$ \\
$9 - 6x + x^{2} = 21 - 2x$ \\
Add $2x$ to both sides: \\
$9 - 4x + x^{2} = 21$ \\
Subtract 21 from both sides: \\
$x^{2} - 4x - 12 = 0$ as required \\
(b)(i) Factorise: the numbers with product $-12$ and sum $-4$ are $-6$ and $2$ \\
$(x - 6)(x + 2) = 0$ \\
$x = 6$ or $x = -2$ \\
(b)(ii) Check each root in the original equation \\
When $x = 6$: $3 - x = -3$, and $\log(-3)$ cannot be found \\
So $x = 6$ is not a solution \\
When $x = -2$: $3 - x = 5$ and $21 - 2x = 25$, both positive \\
$2\log 5 - \log 25 = \log 25 - \log 25 = 0$, so $x = -2$ is a solution

@q 2
@topic Iterative formula, turning point root
@marks 8
@question
(a) $f(x) = 3x^{4} + 2x^{2} - 12x + 8$ \\
Differentiate: $f'(x) = 12x^{3} + 4x - 12$ \\
At a turning point $f'(x) = 0$: \\
$12x^{3} + 4x - 12 = 0$ \\
Move the terms in $x$ to the other side: \\
$12x^{3} = 12 - 4x$ \\
Divide both sides by 12: \\
$x^{3} = \frac{12 - 4x}{12}$ \\
$x^{3} = \frac{12}{12} - \frac{4x}{12}$ \\
$x^{3} = 1 - \frac{x}{3}$ \\
Take the cube root of both sides: \\
$x = \sqrt[3]{1 - \frac{x}{3}}$ as required \\
(b) $x_{1} = 1$ \\
$x_{2} = \sqrt[3]{1 - \frac{x_{1}}{3}} = \sqrt[3]{1 - \frac{1}{3}} = \sqrt[3]{\frac{2}{3}} = 0.8736$ \\
$x_{3} = \sqrt[3]{1 - \frac{x_{2}}{3}} = 0.8916$ \\
$x_{4} = \sqrt[3]{1 - \frac{x_{3}}{3}} = 0.8891$ \\
$x_{5} = \sqrt[3]{1 - \frac{x_{4}}{3}} = 0.8894$ \\
(Use the calculator's ANS key so that rounding errors do not build up.) \\
$x_{2} = 0.8736$ and $x_{5} = 0.8894$ (4 dp) \\
(c) Use the function $f'(x) = 12x^{3} + 4x - 12$, whose root is $\alpha$ \\
To show $\alpha = 0.889$ to 3 dp, look for a sign change between $0.8885$ and $0.8895$ \\
$f'(0.8885) = 12(0.8885)^{3} + 4(0.8885) - 12$ \\
$= 12(0.70141) + 3.554 - 12$ \\
$= 8.41693 + 3.554 - 12$ \\
$= -0.029$ (negative) \\
$f'(0.8895) = 12(0.8895)^{3} + 4(0.8895) - 12$ \\
$= 12(0.70378) + 3.558 - 12$ \\
$= 8.44538 + 3.558 - 12$ \\
$= 0.003$ (positive) \\
There is a change of sign, and $f'(x)$ is continuous on this interval \\
So there is a root $\alpha$ between $0.8885$ and $0.8895$ \\
Every number in this interval rounds to $0.889$, so $\alpha = 0.889$ to 3 decimal places

@q 3
@topic Sector and triangles, perimeter, area
@marks 9
@question
(a) $AFE$ is a straight line, so the angles at $F$ add up to $\pi$: \\
Angle $AFB$ + 1.82 + angle $DFE = \pi$ \\
The triangles are congruent, so angle $AFB$ = angle $DFE$, and call each of them $\phi$ \\
$\phi + 1.82 + \phi = \pi$ \\
$2\phi = \pi - 1.82$ \\
$\phi = \frac{\pi - 1.82}{2} = \frac{1.3216}{2} = 0.6608$ radians \\
Cosine rule in triangle $ABF$ (with $AF = 10.7$, $BF = 9.2$): \\
$AB^{2} = AF^{2} + BF^{2} - 2(AF)(BF)\cos \phi$ \\
$AB^{2} = 10.7^{2} + 9.2^{2} - 2(10.7)(9.2)\cos(0.6608)$ \\
$10.7^{2} = 114.49$, $9.2^{2} = 84.64$, $2(10.7)(9.2) = 196.88$ \\
$\cos(0.6608) = 0.7895$ \\
$AB^{2} = 114.49 + 84.64 - 196.88 \times 0.7895$ \\
$= 199.13 - 155.44$ \\
$= 43.69$ \\
$AB = \sqrt{43.69} = 6.610$ m \\
$DE = AB = 6.610$ m, as the triangles are congruent \\
Arc $BCD$: $s = r\theta = 9.2 \times 1.82 = 16.744$ m \\
$AE = AF + FE = 10.7 + 10.7 = 21.4$ m \\
The perimeter is made of arc $BCD$, $DE$, $EA$ and $AB$: \\
Perimeter $= 16.744 + 6.610 + 21.4 + 6.610$ \\
$= 16.744 + 2(6.610) + 21.4$ \\
$= 16.744 + 13.220 + 21.4$ \\
$= 51.364$ \\
Perimeter $= 51.4$ m (1 dp) \\
(b) Area of the sector $BFDC = \frac{1}{2}r^{2}\theta$ \\
$= \frac{1}{2}(9.2)^{2}(1.82)$ \\
$= \frac{1}{2}(84.64)(1.82)$ \\
$= 77.0224$ \\
Area of triangle $ABF = \frac{1}{2}(AF)(BF)\sin \phi$ \\
$= \frac{1}{2}(10.7)(9.2)\sin(0.6608)$ \\
$= \frac{1}{2}(98.44)(0.6137)$ \\
$= 30.21$ \\
Triangle $DEF$ has the same area \\
Total area $=$ sector $+$ 2 triangles \\
$= 77.0224 + 2(30.21)$ \\
$= 77.0224 + 60.42$ \\
$= 137.44$ \\
Area $= 137.4$ m$^2$ (1 dp)

@q 4
@topic Coordinate geometry, isosceles triangle
@marks 11
@question
(a) $l_{1}$: $y = 2x - 1$ has gradient 2 \\
For perpendicular lines, the gradients multiply to $-1$: $2 \times m = -1$ \\
So the gradient of $l_{2}$ is $m = -\frac{1}{2}$ \\
$l_{2}$ passes through $A(-2, 3)$: \\
$y - y_{1} = m(x - x_{1})$ \\
$y - 3 = -\frac{1}{2}(x - (-2))$ \\
$y - 3 = -\frac{1}{2}(x + 2)$ \\
Expand the bracket: \\
$y - 3 = -\frac{1}{2}x - 1$ \\
Add 3 to both sides: \\
$y = -\frac{1}{2}x - 1 + 3$ \\
$y = -\frac{1}{2}x + 2$ \\
(b) $B$ and $C$ lie on $l_{1}$, so they have the form $(x, 2x - 1)$ \\
They are a distance $2\sqrt{13}$ from $A(-2, 3)$ \\
Distance$^{2}$ $= (x_{2} - x_{1})^{2} + (y_{2} - y_{1})^{2}$: \\
$(x - (-2))^{2} + (2x - 1 - 3)^{2} = (2\sqrt{13})^{2}$ \\
$(x + 2)^{2} + (2x - 4)^{2} = 4 \times 13$ \\
$(x + 2)^{2} + (2x - 4)^{2} = 52$ \\
Expand $(x + 2)^{2} = x^{2} + 4x + 4$ \\
Expand $(2x - 4)^{2} = 4x^{2} - 16x + 16$ \\
$x^{2} + 4x + 4 + 4x^{2} - 16x + 16 = 52$ \\
Collect like terms: \\
$5x^{2} - 12x + 20 = 52$ \\
Subtract 52 from both sides: \\
$5x^{2} - 12x - 32 = 0$ as required \\
(c) Factorise $5x^{2} - 12x - 32 = 0$ \\
Look for two numbers with product $5 \times (-32) = -160$ and sum $-12$: these are $-20$ and $8$ \\
$5x^{2} - 20x + 8x - 32 = 0$ \\
$5x(x - 4) + 8(x - 4) = 0$ \\
$(5x + 8)(x - 4) = 0$ \\
$x = -\frac{8}{5}$ or $x = 4$ \\
$B$ is in the 3rd quadrant, where both $x$ and $y$ are negative \\
When $x = 4$: $y = 2(4) - 1 = 7$, which is in the 1st quadrant, so this is $C$ \\
So $B$ has $x = -\frac{8}{5}$ \\
$y = 2\left( -\frac{8}{5} \right) - 1$ \\
$= -\frac{16}{5} - \frac{5}{5}$ \\
$= -\frac{21}{5}$ \\
$B = \left( -\frac{8}{5}, -\frac{21}{5} \right)$

@q 5
@topic 3D vectors - parallel condition
@marks 5
@question
(Vectors are given as column vectors.) \\
$\text{AB} = (2p, q, 4)$ and $\text{BC} = (9, -3p, 2)$ \\
$\text{AC} = \text{AB} + \text{BC}$ \\
$= (2p + 9, q - 3p, 4 + 2)$ \\
$= (2p + 9, q - 3p, 6)$ \\
$\text{AC}$ is parallel to $(3, -4, 3)$, so it is a multiple of it: \\
$(2p + 9, q - 3p, 6) = k(3, -4, 3)$ \\
Compare the first components: $2p + 9 = 3k$ \\
Compare the second components: $q - 3p = -4k$ \\
Compare the third components: $6 = 3k$ \\
Divide both sides by 3: $k = 2$ \\
Put $k = 2$ into the first equation: \\
$2p + 9 = 3(2)$ \\
$2p + 9 = 6$ \\
Subtract 9 from both sides: $2p = -3$ \\
Divide both sides by 2: $p = -\frac{3}{2}$ \\
Put $k = 2$ into the second equation: \\
$q - 3p = -4(2)$ \\
$q - 3p = -8$ \\
Substitute $p = -\frac{3}{2}$: \\
$q - 3\left( -\frac{3}{2} \right) = -8$ \\
$q + \frac{9}{2} = -8$ \\
Subtract $\frac{9}{2}$ from both sides: \\
$q = -8 - \frac{9}{2}$ \\
$q = -\frac{16}{2} - \frac{9}{2}$ \\
$q = -\frac{25}{2}$ \\
So $p = -\frac{3}{2}$ and $q = -\frac{25}{2}$

@q 6
@topic Arithmetic and geometric models, batteries
@marks 9
@question
(a) Model A is an arithmetic sequence, with first term $a = 2600$ and common difference $d$ \\
Year 10 is the 10th term: $u_{10} = a + 9d$ \\
$12000 = 2600 + 9d$ \\
Subtract 2600 from both sides: \\
$9d = 9400$ \\
Divide both sides by 9: \\
$d = \frac{9400}{9} = 1044.4$ \\
Year 2 is the 2nd term: \\
$u_{2} = a + d = 2600 + 1044.4 = 3644.4$ \\
The company makes 3644 batteries in year 2 \\
(b) Model B is a geometric sequence, with first term $a = 2600$ and common ratio $r$ \\
Year 10 is the 10th term: $u_{10} = ar^{9}$ \\
$12000 = 2600r^{9}$ \\
Divide both sides by 2600: \\
$r^{9} = \frac{12000}{2600} = 4.6154$ \\
Take the 9th root of both sides: \\
$r = 4.6154^{\frac{1}{9}} = 1.1852$ \\
Year 2 is the 2nd term: \\
$u_{2} = ar = 2600 \times 1.1852 = 3081.6$ \\
The company makes 3080 batteries in year 2 (nearest 10) \\
(c) Total for Model A (arithmetic): $S_{n} = \frac{n}{2}(\text{first} + \text{last})$ \\
$S_{10} = \frac{10}{2}(2600 + 12000)$ \\
$= 5 \times 14600$ \\
$= 73000$ \\
Total for Model B (geometric): $S_{n} = \frac{a(r^{n} - 1)}{r - 1}$ \\
$S_{10} = \frac{2600(r^{10} - 1)}{r - 1}$ \\
Use the exact value of $r$ from your calculator, not the rounded value: $r = 1.185225\ldots$ \\
$r^{10} = 5.47027$ \\
$S_{10} = \frac{2600(5.47027 - 1)}{1.185225 - 1}$ \\
$= \frac{2600(4.47027)}{0.185225}$ \\
$= \frac{11622.7}{0.185225}$ \\
$= 62749$ \\
Difference $= 73000 - 62749$ \\
$= 10251$ \\
The difference is 10300 batteries (nearest 100)

@q 7
@topic Cubic factor, point of inflection, no stationary points
@marks 7
@question
(a) $(2x + 1)$ is a factor, so $g\left( -\frac{1}{2} \right) = 0$ \\
$g(x) = 4x^{3} + ax^{2} + 4x + b$ \\
$4\left( -\frac{1}{2} \right)^{3} + a\left( -\frac{1}{2} \right)^{2} + 4\left( -\frac{1}{2} \right) + b = 0$ \\
$4\left( -\frac{1}{8} \right) + a\left( \frac{1}{4} \right) - 2 + b = 0$ \\
$-\frac{1}{2} + \frac{a}{4} - 2 + b = 0$ \\
Collect the numbers: $\frac{a}{4} + b - \frac{5}{2} = 0$ \\
Multiply every term by 4: $a + 4b - 10 = 0$ \\
$a + 4b = 10$ \\
Equation 1: $a + 4b = 10$ \\
Differentiate twice: \\
$g'(x) = 12x^{2} + 2ax + 4$ \\
$g''(x) = 24x + 2a$ \\
A point of inflection at $x = \frac{1}{6}$ means $g''\left( \frac{1}{6} \right) = 0$ \\
$24\left( \frac{1}{6} \right) + 2a = 0$ \\
$4 + 2a = 0$ \\
$2a = -4$ \\
$a = -2$ \\
Substitute $a = -2$ into equation 1: \\
$-2 + 4b = 10$ \\
$4b = 12$ \\
$b = 3$ \\
So $a = -2$ and $b = 3$ \\
(b) Substitute $a = -2$ into $g'(x) = 12x^{2} + 2ax + 4$: \\
$g'(x) = 12x^{2} - 4x + 4$ \\
Complete the square: take out a factor of 12 from the first two terms \\
$g'(x) = 12\left( x^{2} - \frac{1}{3}x \right) + 4$ \\
$x^{2} - \frac{1}{3}x = \left( x - \frac{1}{6} \right)^{2} - \frac{1}{36}$ \\
$g'(x) = 12\left( \left( x - \frac{1}{6} \right)^{2} - \frac{1}{36} \right) + 4$ \\
Expand the outer bracket: \\
$= 12\left( x - \frac{1}{6} \right)^{2} - \frac{12}{36} + 4$ \\
$= 12\left( x - \frac{1}{6} \right)^{2} - \frac{1}{3} + 4$ \\
$= 12\left( x - \frac{1}{6} \right)^{2} + \frac{11}{3}$ \\
$\left( x - \frac{1}{6} \right)^{2} \ge 0$ for all $x$ \\
So $g'(x) \ge \frac{11}{3}$, which is greater than 0 \\
$g'(x)$ is never zero, so there are no stationary points

@q 8
@topic Reciprocal graph, discriminant, k range
@marks 9
@question
(a) $y = k - \frac{1}{2x}$, where $k > 0$ \\
The curve is undefined at $x = 0$, so the $y$-axis is a vertical asymptote and there is no $y$-intercept \\
As $x \to \pm\infty$, $\frac{1}{2x} \to 0$, so $y \to k$ \\
The horizontal asymptote is $y = k$ \\
$x$-intercept: put $y = 0$ \\
$0 = k - \frac{1}{2x}$ \\
$\frac{1}{2x} = k$ \\
$2x = \frac{1}{k}$ \\
$x = \frac{1}{2k}$ \\
The curve crosses the $x$-axis at $\left( \frac{1}{2k}, 0 \right)$ \\
For $x > 0$: the branch rises from far below, crosses the $x$-axis at $x = \frac{1}{2k}$ and approaches $y = k$ from below \\
For $x < 0$: $y = k + \frac{1}{2|x|}$ is above $y = k$, and the branch approaches $y = k$ from above as $x \to -\infty$, and goes up to $+\infty$ as $x \to 0$ \\
(b) Set the curve equal to the line: \\
$k - \frac{1}{2x} = 2x + 3$ \\
Multiply every term by $2x$: \\
$2kx - 1 = 4x^{2} + 6x$ \\
Move everything to one side: \\
$0 = 4x^{2} + 6x - 2kx + 1$ \\
$4x^{2} + (6 - 2k)x + 1 = 0$ \\
Two distinct intersections means two distinct roots, so the discriminant is positive: $b^{2} - 4ac > 0$ \\
$a = 4$, $b = 6 - 2k$, $c = 1$ \\
$(6 - 2k)^{2} - 4(4)(1) > 0$ \\
$(6 - 2k)^{2} - 16 > 0$ \\
Expand $(6 - 2k)^{2} = 36 - 24k + 4k^{2}$: \\
$36 - 24k + 4k^{2} - 16 > 0$ \\
$4k^{2} - 24k + 20 > 0$ \\
Divide every term by 4: \\
$k^{2} - 6k + 5 > 0$ \\
Factorise: \\
$(k - 1)(k - 5) > 0$ \\
The critical values are $k = 1$ and $k = 5$ \\
The quadratic $k^{2} - 6k + 5$ is a U shape, so it is positive outside the critical values: \\
$k < 1$ or $k > 5$ \\
Since $k$ is a positive constant: \\
$\{ k : 0 < k < 1 \}$ or $\{ k : k > 5 \}$ \\
(The mark scheme also accepts $\{ k : k < 1 \}$ or $\{ k : k > 5 \}$.)

@q 9
@topic Turning point, integration by parts, area
@marks 9
@question
(a) $y = xe^{-2x}$ \\
Use the product rule with $u = x$ and $v = e^{-2x}$ \\
$u' = 1$ and $v' = -2e^{-2x}$ \\
$\frac{dy}{dx} = u'v + uv'$ \\
$= 1 \times e^{-2x} + x \times (-2e^{-2x})$ \\
$= e^{-2x} - 2xe^{-2x}$ \\
Factorise: \\
$\frac{dy}{dx} = e^{-2x}(1 - 2x)$ \\
At the turning point $\frac{dy}{dx} = 0$: \\
$e^{-2x}(1 - 2x) = 0$ \\
$e^{-2x}$ is never zero, so $1 - 2x = 0$ \\
$2x = 1$ \\
$x = \frac{1}{2}$ \\
Substitute back into $y = xe^{-2x}$: \\
$y = \frac{1}{2}e^{-2 \times \frac{1}{2}}$ \\
$= \frac{1}{2}e^{-1}$ \\
$= \frac{1}{2e}$ \\
So $a = \frac{1}{2}$ and $b = \frac{1}{2e}$ \\
(b) $R$ lies between the $y$-axis ($x = 0$) and $x = \frac{1}{2}$, above the curve and below the line $y = b$ \\
Area of $R$ = area of the rectangle $-$ area under the curve \\
Rectangle: $\frac{1}{2} \times b = \frac{1}{2} \times \frac{1}{2e} = \frac{1}{4e}$ \\
Area under the curve: $\int_{0}^{\frac{1}{2}} xe^{-2x} \, dx$ \\
Integrate by parts with $u = x$ and $\frac{dv}{dx} = e^{-2x}$ \\
$\frac{du}{dx} = 1$ and $v = -\frac{1}{2}e^{-2x}$ \\
$\int xe^{-2x} \, dx = -\frac{1}{2}xe^{-2x} - \int \left( -\frac{1}{2}e^{-2x} \right)(1) \, dx$ \\
$= -\frac{1}{2}xe^{-2x} + \frac{1}{2}\int e^{-2x} \, dx$ \\
$= -\frac{1}{2}xe^{-2x} + \frac{1}{2}\left( -\frac{1}{2}e^{-2x} \right)$ \\
$= -\frac{1}{2}xe^{-2x} - \frac{1}{4}e^{-2x}$ \\
Apply the limits: \\
At $x = \frac{1}{2}$: $-\frac{1}{2}\left( \frac{1}{2} \right)e^{-1} - \frac{1}{4}e^{-1} = -\frac{1}{4e} - \frac{1}{4e} = -\frac{1}{2e}$ \\
At $x = 0$: $-\frac{1}{2}(0)e^{0} - \frac{1}{4}e^{0} = -\frac{1}{4}$ \\
$\int_{0}^{\frac{1}{2}} xe^{-2x} \, dx = -\frac{1}{2e} - \left( -\frac{1}{4} \right)$ \\
$= \frac{1}{4} - \frac{1}{2e}$ \\
Area of $R = \frac{1}{4e} - \left( \frac{1}{4} - \frac{1}{2e} \right)$ \\
Remove the bracket: \\
$= \frac{1}{4e} - \frac{1}{4} + \frac{1}{2e}$ \\
Write $\frac{1}{2e} = \frac{2}{4e}$: \\
$= \frac{1}{4e} + \frac{2}{4e} - \frac{1}{4}$ \\
$= \frac{3}{4e} - \frac{1}{4}$ \\
Area of $R = \frac{3}{4e} - \frac{1}{4}$, or as a single fraction $\frac{3 - e}{4e}$

@q 10
@topic R sin form, reciprocal model, seabird
@marks 9
@question
(a) $H = \frac{140}{A + 45\sin 2t - 28\cos 2t}$ \\
The nest is at $t = 0$ with $H = 20$: \\
$20 = \frac{140}{A + 45\sin 0 - 28\cos 0}$ \\
Use $\sin 0 = 0$ and $\cos 0 = 1$: \\
$20 = \frac{140}{A + 0 - 28}$ \\
$20 = \frac{140}{A - 28}$ \\
Multiply both sides by $(A - 28)$: \\
$20(A - 28) = 140$ \\
Divide both sides by 20: \\
$A - 28 = 7$ \\
Add 28 to both sides: \\
$A = 35$ \\
$H = \frac{140}{35 + 45\sin 2t - 28\cos 2t}$ \\
(b) Expand the right-hand side using $\sin(A - B) = \sin A \cos B - \cos A \sin B$: \\
$53\sin(2t - \alpha) = 53\sin 2t \cos \alpha - 53\cos 2t \sin \alpha$ \\
Compare the coefficients of $\sin 2t$: $53\cos \alpha = 45$ \\
Compare the coefficients of $\cos 2t$: $53\sin \alpha = 28$ \\
Divide the second equation by the first: \\
$\frac{53\sin \alpha}{53\cos \alpha} = \frac{28}{45}$ \\
$\tan \alpha = \frac{28}{45}$ \\
$\alpha = \tan^{-1}\left( \frac{28}{45} \right)$ \\
$\alpha = 31.9$ degrees (1 dp) \\
(c) $H = \frac{140}{35 + 53\sin(2t - 31.9)}$ \\
$H$ is smallest when the denominator is largest \\
The largest value of $\sin$ is 1: \\
Largest denominator $= 35 + 53(1) = 88$ \\
$H_{min} = \frac{140}{88}$ \\
$= 1.5909$ m \\
$= 159.09$ cm \\
The minimum height is 159 cm (nearest cm) \\
(d) The model fails if the denominator reaches zero, as $H$ cannot then be found \\
$35 + 53\sin(2T - 31.9) = 0$ \\
Subtract 35 from both sides: \\
$53\sin(2T - 31.9) = -35$ \\
Divide both sides by 53: \\
$\sin(2T - 31.9) = -\frac{35}{53} = -0.6604$ \\
Let $X = 2T - 31.9$ \\
$\sin^{-1}(-0.6604) = -41.3$ degrees \\
This is not possible, as $T \ge 0$ gives $X \ge -31.9$ \\
The next solution: $X = 180 + 41.3 = 221.3$ degrees \\
$2T - 31.9 = 221.3$ \\
Add 31.9 to both sides: \\
$2T = 253.2$ \\
Divide both sides by 2: \\
$T = 126.6$ \\
So the model is only valid for $T < 126.6$ seconds

@q 11
@topic Parametric area, trig integral
@marks 7
@question
(a) $x = 3\cos 2t$ \\
Differentiate: $\frac{dx}{dt} = 3 \times (-2\sin 2t) = -6\sin 2t$ \\
Area $= \int y \, dx = \int y\frac{dx}{dt} \, dt$ \\
$y\frac{dx}{dt} = 2\tan t \times (-6\sin 2t)$ \\
$= -12\tan t \sin 2t$ \\
Use $\tan t = \frac{\sin t}{\cos t}$ and $\sin 2t = 2\sin t \cos t$: \\
$= -12 \times \frac{\sin t}{\cos t} \times 2\sin t \cos t$ \\
Cancel $\cos t$: \\
$= -12 \times \sin t \times 2\sin t$ \\
$= -24\sin^{2} t$ \\
Find the limits for $t$: \\
$x = 3$: $3\cos 2t = 3$, so $\cos 2t = 1$, and $t = 0$ \\
$x = 0$: $3\cos 2t = 0$, so $2t = \frac{\pi}{2}$, and $t = \frac{\pi}{4}$ \\
$R$ goes from $x = 0$ to $x = 3$, which is from $t = \frac{\pi}{4}$ to $t = 0$: \\
Area $= \int_{\frac{\pi}{4}}^{0} -24\sin^{2} t \, dt$ \\
Swapping the limits changes the sign: \\
Area $= \int_{0}^{\frac{\pi}{4}} 24\sin^{2} t \, dt$ as required \\
(b) Use $\cos 2t = 1 - 2\sin^{2} t$ \\
Rearrange: $2\sin^{2} t = 1 - \cos 2t$ \\
$\sin^{2} t = \frac{1 - \cos 2t}{2}$ \\
$24\sin^{2} t = 24 \times \frac{1 - \cos 2t}{2}$ \\
$= 12(1 - \cos 2t)$ \\
$= 12 - 12\cos 2t$ \\
$\int_{0}^{\frac{\pi}{4}} (12 - 12\cos 2t) \, dt = \left[ 12t - 12 \times \frac{\sin 2t}{2} \right]_{0}^{\frac{\pi}{4}}$ \\
$= \left[ 12t - 6\sin 2t \right]_{0}^{\frac{\pi}{4}}$ \\
Substitute the upper limit $t = \frac{\pi}{4}$: \\
$12 \times \frac{\pi}{4} - 6\sin\left( \frac{\pi}{2} \right) = 3\pi - 6(1) = 3\pi - 6$ \\
Substitute the lower limit $t = 0$: \\
$12(0) - 6\sin 0 = 0$ \\
Subtract: \\
Area $= (3\pi - 6) - 0$ \\
Area $= 3\pi - 6$

@q 12
@topic Exponential curves, logs, intersection
@marks 8
@question
(a) $P(a, 96\sqrt{2})$ is on $y = 3 \times 2^{2x}$ \\
$3 \times 2^{2a} = 96\sqrt{2}$ \\
Divide both sides by 3: \\
$2^{2a} = 32\sqrt{2}$ \\
Write each part as a power of 2: $32 = 2^{5}$ and $\sqrt{2} = 2^{\frac{1}{2}}$ \\
$2^{2a} = 2^{5} \times 2^{\frac{1}{2}}$ \\
Add the powers: \\
$2^{2a} = 2^{\frac{11}{2}}$ \\
Compare the powers: \\
$2a = \frac{11}{2}$ \\
$a = \frac{11}{4}$ \\
(b) At $Q$ the curves meet: \\
$3 \times 2^{2x} = 6^{3 - x}$ \\
Take $\log_{2}$ of both sides: \\
$\log_{2}(3 \times 2^{2x}) = \log_{2}(6^{3 - x})$ \\
Use $\log(ab) = \log a + \log b$ on the left and $\log(a^{n}) = n\log a$ on both sides: \\
$\log_{2} 3 + 2x\log_{2} 2 = (3 - x)\log_{2} 6$ \\
Use $\log_{2} 2 = 1$: \\
$\log_{2} 3 + 2x = (3 - x)\log_{2} 6$ \\
Write $6 = 2 \times 3$: \\
$\log_{2} 6 = \log_{2} 2 + \log_{2} 3 = 1 + \log_{2} 3$ \\
$\log_{2} 3 + 2x = (3 - x)(1 + \log_{2} 3)$ \\
Expand the bracket: \\
$\log_{2} 3 + 2x = 3 + 3\log_{2} 3 - x - x\log_{2} 3$ \\
Get the terms in $x$ on the left and the rest on the right: \\
Add $x$ and $x\log_{2} 3$ to both sides, and subtract $\log_{2} 3$ from both sides: \\
$2x + x + x\log_{2} 3 = 3 + 3\log_{2} 3 - \log_{2} 3$ \\
$3x + x\log_{2} 3 = 3 + 2\log_{2} 3$ \\
Factorise the left-hand side: \\
$x(3 + \log_{2} 3) = 3 + 2\log_{2} 3$ \\
Divide both sides by $(3 + \log_{2} 3)$: \\
$x = \frac{3 + 2\log_{2} 3}{3 + \log_{2} 3}$ as required

@q 13
@topic Proof by contradiction, integers
@marks 4
@question
Assume the opposite: there are positive integers $a$ and $b$, with $a$ odd, such that $a + 2b = \sqrt{8ab}$ \\
Square both sides: \\
$(a + 2b)^{2} = 8ab$ \\
Expand the bracket: $(a + 2b)(a + 2b) = a^{2} + 2ab + 2ab + 4b^{2} = a^{2} + 4ab + 4b^{2}$ \\
$a^{2} + 4ab + 4b^{2} = 8ab$ \\
Subtract $8ab$ from both sides: \\
$a^{2} - 4ab + 4b^{2} = 0$ \\
Factorise the left-hand side as a perfect square: \\
$(a - 2b)^{2} = 0$ \\
Take the square root of both sides: \\
$a - 2b = 0$ \\
$a = 2b$ \\
Since $b$ is an integer, $2b$ is even, so $a$ is even \\
But we assumed that $a$ is odd, which is a contradiction \\
So the assumption is false \\
Therefore there are no positive integers $a$ and $b$, with $a$ odd, such that $a + 2b = \sqrt{8ab}$
