@paper P2 Mock Set 4

@q 1
@topic Inequalities, linear and quadratic
@marks 5
@question
(a)(i) $2x - 10 < 3(5 - x)$ \\
Expand the bracket: \\
$2x - 10 < 15 - 3x$ \\
Add $3x$ to both sides: \\
$5x - 10 < 15$ \\
Add 10 to both sides: \\
$5x < 25$ \\
Divide both sides by 5: \\
$x < 5$ \\
(ii) $x^{2} - 11x + 24 \le 0$ \\
Solve $x^{2} - 11x + 24 = 0$: the numbers with product 24 and sum $-11$ are $-3$ and $-8$ \\
$(x - 3)(x - 8) = 0$ \\
$x = 3$ or $x = 8$ \\
The graph of $y = x^{2} - 11x + 24$ is a U shape, so it is below or on the $x$-axis between the roots: \\
$3 \le x \le 8$ \\
(b) Both inequalities must be true, so take the overlap of $x < 5$ and $3 \le x \le 8$: \\
$3 \le x < 5$

@q 2
@topic Differentiation, root, Newton-Raphson
@marks 5
@question
(a) Write the fraction as a power: $\frac{3}{x} = 3x^{-1}$ \\
$f(x) = x^{3} - 5x^{2} + 3x^{-1} - 4$ \\
Differentiate each term using $x^{n} \to nx^{n-1}$: \\
$x^{3} \to 3x^{2}$ \\
$-5x^{2} \to -10x$ \\
$3x^{-1} \to -3x^{-2}$ \\
$-4 \to 0$ \\
$f'(x) = 3x^{2} - 10x - 3x^{-2}$ \\
$f'(x) = 3x^{2} - 10x - \frac{3}{x^{2}}$ \\
(b) $f(0.5) = 0.875$ is positive and $f(0.6) = -0.584$ is negative \\
$f(x)$ is continuous for $x > 0$ \\
So $f$ changes sign between 0.5 and 0.6, and there is a root $\alpha$ in the interval $[0.5, 0.6]$ \\
(c) Newton-Raphson: $x_{n+1} = x_{n} - \frac{f(x_{n})}{f'(x_{n})}$ \\
$f'(0.5) = 3(0.5)^{2} - 10(0.5) - \frac{3}{(0.5)^{2}}$ \\
$= 3(0.25) - 5 - \frac{3}{0.25}$ \\
$= 0.75 - 5 - 12$ \\
$= -16.25$ \\
$x_{1} = 0.5 - \frac{f(0.5)}{f'(0.5)}$ \\
$= 0.5 - \frac{0.875}{-16.25}$ \\
$= 0.5 + 0.05385$ \\
$= 0.55385$ \\
$x_{1} = 0.554$ (3 dp)

@q 3
@topic Trapezium rule, over/underestimate, table
@marks 7
@question
(a) The $x$ values go up in steps of 0.3, so $h = 0.3$ \\
Trapezium rule: area $\approx \frac{h}{2}\{ y_{0} + y_{5} + 2(y_{1} + y_{2} + y_{3} + y_{4}) \}$ \\
$\int_{-0.6}^{0.9} f(x) \, dx \approx \frac{0.3}{2}\{ 1.811 + 2.944 + 2(2.342 + 2.718 + 2.941 + 3.011) \}$ \\
First and last: $1.811 + 2.944 = 4.755$ \\
Middle four: $2.342 + 2.718 + 2.941 + 3.011 = 11.012$ \\
Double the middle four: $2 \times 11.012 = 22.024$ \\
$= 0.15 \times \{ 4.755 + 22.024 \}$ \\
$= 0.15 \times 26.779$ \\
$= 4.01685$ \\
$= 4.02$ (3 sf) \\
(b) The curve is concave (it bends downwards) \\
So the straight tops of the trapezia lie below the curve \\
The trapezia have less area than the region under the curve, so the answer to (a) is an underestimate \\
(c) Split the integral into two parts: \\
$\int_{-0.6}^{0.9} (8 - 2f(x)) \, dx = \int_{-0.6}^{0.9} 8 \, dx - 2\int_{-0.6}^{0.9} f(x) \, dx$ \\
First part: $\int_{-0.6}^{0.9} 8 \, dx = [8x]_{-0.6}^{0.9}$ \\
$= 8(0.9) - 8(-0.6)$ \\
$= 7.2 + 4.8$ \\
$= 12$ \\
Second part: $2 \times 4.02 = 8.04$, from (a) \\
$= 12 - 8.04$ \\
$= 3.96$

@q 4
@topic Factor theorem, unknown coefficients
@marks 4
@question
(a) $(2x + 1)$ is a factor, so $f\left( -\frac{1}{2} \right) = 0$ \\
$f(x) = px^{3} - 7x^{2} - x + q$ \\
$p\left( -\frac{1}{2} \right)^{3} - 7\left( -\frac{1}{2} \right)^{2} - \left( -\frac{1}{2} \right) + q = 0$ \\
$p\left( -\frac{1}{8} \right) - 7\left( \frac{1}{4} \right) + \frac{1}{2} + q = 0$ \\
$-\frac{p}{8} - \frac{7}{4} + \frac{1}{2} + q = 0$ \\
Multiply every term by 8: \\
$-p - 14 + 4 + 8q = 0$ \\
$-p - 10 + 8q = 0$ \\
Add 10 to both sides: \\
$8q - p = 10$ as required \\
(b) $(x - 1)$ is a factor, so $f(1) = 0$ \\
$p(1)^{3} - 7(1)^{2} - 1 + q = 0$ \\
$p - 7 - 1 + q = 0$ \\
$p + q = 8$ \\
Equation 1: $8q - p = 10$ \\
Equation 2: $p + q = 8$ \\
Add the two equations: \\
$8q - p + p + q = 10 + 8$ \\
$9q = 18$ \\
$q = 2$ \\
Substitute $q = 2$ into equation 2: \\
$p + 2 = 8$ \\
$p = 6$ \\
So $p = 6$ and $q = 2$

@q 5
@topic Small angle approximations
@marks 3
@question
Small angle approximations: $\cos x \approx 1 - \frac{x^{2}}{2}$ and $\sin x \approx x$ \\
Numerator: $\cos 9\theta \approx 1 - \frac{(9\theta)^{2}}{2}$ \\
$(9\theta)^{2} = 81\theta^{2}$ \\
$\cos 9\theta \approx 1 - \frac{81\theta^{2}}{2}$ \\
$\cos 9\theta - 1 \approx 1 - \frac{81\theta^{2}}{2} - 1 = -\frac{81\theta^{2}}{2}$ \\
Denominator: $\theta\sin\theta \approx \theta \times \theta = \theta^{2}$ \\
$\frac{\cos 9\theta - 1}{\theta\sin\theta} \approx \frac{-\frac{81\theta^{2}}{2}}{\theta^{2}}$ \\
Cancel $\theta^{2}$: \\
$= -\frac{81}{2}$

@q 6
@topic Differentiation, cubic, inflection
@marks 7
@question
(a)(i) $y = ax^{3} + bx^{2} + 12x + 2$ \\
Differentiate each term: \\
$\frac{dy}{dx} = 3ax^{2} + 2bx + 12$ \\
(ii) Differentiate again: \\
$\frac{d^{2}y}{dx^{2}} = 6ax + 2b$ \\
(b) $P\left( \frac{3}{2}, \frac{13}{2} \right)$ lies on $C$, so substitute $x = \frac{3}{2}$ and $y = \frac{13}{2}$: \\
$\frac{13}{2} = a\left( \frac{3}{2} \right)^{3} + b\left( \frac{3}{2} \right)^{2} + 12\left( \frac{3}{2} \right) + 2$ \\
$\frac{13}{2} = \frac{27a}{8} + \frac{9b}{4} + 18 + 2$ \\
$\frac{13}{2} = \frac{27a}{8} + \frac{9b}{4} + 20$ \\
Subtract 20 from both sides: \\
$\frac{27a}{8} + \frac{9b}{4} = \frac{13}{2} - 20$ \\
$\frac{27a}{8} + \frac{9b}{4} = -\frac{27}{2}$ \\
Equation 1: $\frac{27a}{8} + \frac{9b}{4} = -\frac{27}{2}$ \\
$\frac{d^{2}y}{dx^{2}} = 0$ at $P$, so substitute $x = \frac{3}{2}$ into $6ax + 2b = 0$: \\
$6a\left( \frac{3}{2} \right) + 2b = 0$ \\
$9a + 2b = 0$ \\
$b = -\frac{9a}{2}$ \\
Substitute this into equation 1: \\
$\frac{27a}{8} + \frac{9}{4}\left( -\frac{9a}{2} \right) = -\frac{27}{2}$ \\
$\frac{27a}{8} - \frac{81a}{8} = -\frac{27}{2}$ \\
$-\frac{54a}{8} = -\frac{27}{2}$ \\
$-\frac{27a}{4} = -\frac{27}{2}$ \\
Multiply both sides by $-\frac{4}{27}$: \\
$a = \frac{27}{2} \times \frac{4}{27} = 2$ \\
$b = -\frac{9(2)}{2} = -9$ \\
So $a = 2$ and $b = -9$ \\
(c) With $a = 2$ and $b = -9$: \\
$\frac{d^{2}y}{dx^{2}} = 6(2)x + 2(-9) = 12x - 18$ \\
Check $\frac{d^{2}y}{dx^{2}} = 0$ at $x = \frac{3}{2}$: $12\left( \frac{3}{2} \right) - 18 = 18 - 18 = 0$ \\
Now look at the sign either side of $x = \frac{3}{2}$ \\
At $x = 1$: $\frac{d^{2}y}{dx^{2}} = 12(1) - 18 = -6 < 0$ \\
At $x = 2$: $\frac{d^{2}y}{dx^{2}} = 12(2) - 18 = 6 > 0$ \\
The second derivative changes sign either side of $P$ \\
So $P$ is a point of inflection

@q 7
@topic Integral as limit of a sum, exact value
@marks 5
@question
The limit of the sum is an integral: \\
$\lim_{\delta x \to 0} \sum_{x=2}^{3} \frac{(x - 3)^{2}}{x^{\frac{3}{2}}} \, \delta x = \int_{2}^{3} \frac{(x - 3)^{2}}{x^{\frac{3}{2}}} \, dx$ \\
Expand the numerator: $(x - 3)^{2} = x^{2} - 6x + 9$ \\
Divide each term by $x^{\frac{3}{2}}$: \\
$\frac{x^{2}}{x^{\frac{3}{2}}} = x^{2 - \frac{3}{2}} = x^{\frac{1}{2}}$ \\
$\frac{6x}{x^{\frac{3}{2}}} = 6x^{1 - \frac{3}{2}} = 6x^{-\frac{1}{2}}$ \\
$\frac{9}{x^{\frac{3}{2}}} = 9x^{-\frac{3}{2}}$ \\
$\frac{(x - 3)^{2}}{x^{\frac{3}{2}}} = x^{\frac{1}{2}} - 6x^{-\frac{1}{2}} + 9x^{-\frac{3}{2}}$ \\
Integrate each term, adding 1 to the power and dividing by the new power: \\
$\int x^{\frac{1}{2}} \, dx = \frac{x^{\frac{3}{2}}}{\frac{3}{2}} = \frac{2}{3}x^{\frac{3}{2}}$ \\
$\int -6x^{-\frac{1}{2}} \, dx = -6 \times \frac{x^{\frac{1}{2}}}{\frac{1}{2}} = -12x^{\frac{1}{2}}$ \\
$\int 9x^{-\frac{3}{2}} \, dx = 9 \times \frac{x^{-\frac{1}{2}}}{-\frac{1}{2}} = -18x^{-\frac{1}{2}}$ \\
$\int_{2}^{3} \left( x^{\frac{1}{2}} - 6x^{-\frac{1}{2}} + 9x^{-\frac{3}{2}} \right) dx = \left[ \frac{2}{3}x^{\frac{3}{2}} - 12x^{\frac{1}{2}} - 18x^{-\frac{1}{2}} \right]_{2}^{3}$ \\
Upper limit $x = 3$: $x^{\frac{3}{2}} = 3\sqrt{3}$, $x^{\frac{1}{2}} = \sqrt{3}$, $x^{-\frac{1}{2}} = \frac{1}{\sqrt{3}}$ \\
$\frac{2}{3}(3\sqrt{3}) - 12\sqrt{3} - \frac{18}{\sqrt{3}}$ \\
$\frac{18}{\sqrt{3}} = \frac{18\sqrt{3}}{3} = 6\sqrt{3}$ \\
$= 2\sqrt{3} - 12\sqrt{3} - 6\sqrt{3}$ \\
$= -16\sqrt{3}$ \\
Lower limit $x = 2$: $x^{\frac{3}{2}} = 2\sqrt{2}$, $x^{\frac{1}{2}} = \sqrt{2}$, $x^{-\frac{1}{2}} = \frac{1}{\sqrt{2}}$ \\
$\frac{2}{3}(2\sqrt{2}) - 12\sqrt{2} - \frac{18}{\sqrt{2}}$ \\
$\frac{18}{\sqrt{2}} = \frac{18\sqrt{2}}{2} = 9\sqrt{2}$ \\
$= \frac{4}{3}\sqrt{2} - 12\sqrt{2} - 9\sqrt{2}$ \\
$= \frac{4}{3}\sqrt{2} - 21\sqrt{2}$ \\
$= \frac{4}{3}\sqrt{2} - \frac{63}{3}\sqrt{2}$ \\
$= -\frac{59}{3}\sqrt{2}$ \\
Subtract the lower limit from the upper limit: \\
$= -16\sqrt{3} - \left( -\frac{59}{3}\sqrt{2} \right)$ \\
$= \frac{59}{3}\sqrt{2} - 16\sqrt{3}$ \\
So $p = \frac{59}{3}$ and $q = -16$

@q 8
@topic Arithmetic series, candle sales model
@marks 7
@question
(a)(i) The sales form an arithmetic sequence with $a = 150$ and $d = 10$ \\
$u_{n} = a + (n - 1)d$ \\
$u_{30} = 150 + 29(10)$ \\
$= 150 + 290$ \\
$= 440$ candles \\
(ii) $S_{n} = \frac{n}{2}(2a + (n - 1)d)$ \\
$S_{30} = \frac{30}{2}(2(150) + 29(10))$ \\
$= 15(300 + 290)$ \\
$= 15(590)$ \\
$= 8850$ candles \\
Check with $\frac{n}{2}(\text{first} + \text{last}) = 15(150 + 440) = 15(590) = 8850$ \\
(b) There are 52 weeks in a year: \\
$S_{52} = \frac{52}{2}(2(150) + 51d)$ \\
$= 26(300 + 51d)$ \\
At least 15 000 candles must be sold: \\
$26(300 + 51d) \ge 15000$ \\
Divide both sides by 26: \\
$300 + 51d \ge 576.92$ \\
Subtract 300 from both sides: \\
$51d \ge 276.92$ \\
Divide both sides by 51: \\
$d \ge 5.43$ \\
The increase $d$ must be a whole number of candles, so the smallest possible value is $d = 6$ \\
Check: $d = 5$ gives $26(300 + 255) = 14430$, which is too small, and $d = 6$ gives $26(300 + 306) = 15756$ \\
(c) The number of extra candles sold each week is unlikely to be exactly the same every week, as the model assumes

@q 9
@topic Modulus curve and parabola, area between
@marks 10
@question
(a) $D$ is where $C_{1}$ meets the $x$-axis: $y = 0$ \\
$|7 - 3x| = 0$ \\
$7 - 3x = 0$ \\
$3x = 7$ \\
$x = \frac{7}{3}$ \\
(b) Substitute $x = 2$ into both equations \\
$C_{1}$: $y = |7 - 3(2)| = |7 - 6| = 1$ \\
$C_{2}$: $y = -2(2)^{2} + 14(2) - 19 = -8 + 28 - 19 = 1$ \\
Both give $y = 1$ at $x = 2$, so $A = (2, 1)$ and the $x$ coordinate of $A$ is 2 \\
(c) $B$ is to the right of $D$, where $7 - 3x < 0$, so $|7 - 3x| = 3x - 7$ \\
Set the curves equal: \\
$3x - 7 = -2x^{2} + 14x - 19$ \\
Move everything to the left-hand side: \\
$2x^{2} + 3x - 14x - 7 + 19 = 0$ \\
$2x^{2} - 11x + 12 = 0$ \\
Factorise: the numbers with product $2 \times 12 = 24$ and sum $-11$ are $-3$ and $-8$ \\
$2x^{2} - 3x - 8x + 12 = 0$ \\
$x(2x - 3) - 4(2x - 3) = 0$ \\
$(2x - 3)(x - 4) = 0$ \\
$x = \frac{3}{2}$ or $x = 4$ \\
$x = \frac{3}{2}$ is less than $\frac{7}{3}$, so it is not on this branch, and it is rejected \\
$x = 4$ \\
$y = 3(4) - 7 = 5$ \\
$B = (4, 5)$ \\
(d) $R$ is between the curve $C_{2}$ (above) and the graph $C_{1}$ (below), from $x = 2$ to $x = 4$ \\
Area of $R$ = area under $C_{2}$ $-$ area under $C_{1}$ \\
Area under $C_{2}$: $\int_{2}^{4} (-2x^{2} + 14x - 19) \, dx$ \\
$= \left[ -\frac{2x^{3}}{3} + 7x^{2} - 19x \right]_{2}^{4}$ \\
Upper limit $x = 4$: $-\frac{2(64)}{3} + 7(16) - 19(4) = -\frac{128}{3} + 112 - 76$ \\
$= -\frac{128}{3} + 36$ \\
$= -\frac{128}{3} + \frac{108}{3}$ \\
$= -\frac{20}{3}$ \\
Lower limit $x = 2$: $-\frac{2(8)}{3} + 7(4) - 19(2) = -\frac{16}{3} + 28 - 38$ \\
$= -\frac{16}{3} - 10$ \\
$= -\frac{16}{3} - \frac{30}{3}$ \\
$= -\frac{46}{3}$ \\
Subtract: $-\frac{20}{3} - \left( -\frac{46}{3} \right) = \frac{26}{3}$ \\
Area under $C_{1}$ from $x = 2$ to $x = 4$ is two triangles with their bases on the $x$-axis: \\
Triangle 1, from $x = 2$ to $D\left( \frac{7}{3}, 0 \right)$: base $\frac{7}{3} - 2 = \frac{1}{3}$, height 1 \\
Area $= \frac{1}{2} \times \frac{1}{3} \times 1 = \frac{1}{6}$ \\
Triangle 2, from $D$ to $x = 4$: base $4 - \frac{7}{3} = \frac{5}{3}$, height 5 \\
Area $= \frac{1}{2} \times \frac{5}{3} \times 5 = \frac{25}{6}$ \\
Total: $\frac{1}{6} + \frac{25}{6} = \frac{26}{6} = \frac{13}{3}$ \\
Area of $R = \frac{26}{3} - \frac{13}{3}$ \\
$= \frac{13}{3}$

@q 10
@topic Circle meets parabola, range of k
@marks 6
@question
The circle is $x^{2} + y^{2} = 10x + k$ and the curve is $x = t^{2}$, $y = 2t$ \\
Substitute $x = t^{2}$ and $y = 2t$ into the circle: \\
$(t^{2})^{2} + (2t)^{2} = 10t^{2} + k$ \\
$t^{4} + 4t^{2} = 10t^{2} + k$ \\
Subtract $10t^{2}$ and $k$ from both sides: \\
$t^{4} + 4t^{2} - 10t^{2} - k = 0$ \\
$t^{4} - 6t^{2} - k = 0$ \\
Let $u = t^{2}$: \\
$u^{2} - 6u - k = 0$ \\
Each positive value of $u$ gives two values of $t$ ($t = \pm\sqrt{u}$), and so two different points on the curve \\
$u = 0$ gives one point and a negative $u$ gives none \\
So for 4 distinct intersections, the quadratic in $u$ needs two distinct positive roots \\
Two distinct real roots: discriminant $> 0$ \\
$(-6)^{2} - 4(1)(-k) > 0$ \\
$36 + 4k > 0$ \\
$4k > -36$ \\
$k > -9$ \\
Both roots positive: the product of the roots is $\frac{c}{a} = -k$, and it must be positive \\
$-k > 0$ \\
$k < 0$ \\
(The sum of the roots is 6, which is positive, as needed.) \\
Combine: $-9 < k < 0$ \\
In set notation: $\{ k : -9 < k < 0 \}$

@q 11
@topic Proof by algebra, divisible by 3
@marks 4
@question
Any integer not divisible by 3 leaves a remainder of 1 or 2 when divided by 3 \\
So $n = 3k + 1$ or $n = 3k + 2$, where $k$ is an integer \\
Case 1: $n = 3k + 1$ \\
$n^{2} - 1 = (3k + 1)^{2} - 1$ \\
Expand the bracket: \\
$= 9k^{2} + 6k + 1 - 1$ \\
$= 9k^{2} + 6k$ \\
Factorise: \\
$= 3(3k^{2} + 2k)$ \\
$3k^{2} + 2k$ is an integer, so this is a multiple of 3 \\
Case 2: $n = 3k + 2$ \\
$n^{2} - 1 = (3k + 2)^{2} - 1$ \\
Expand the bracket: \\
$= 9k^{2} + 12k + 4 - 1$ \\
$= 9k^{2} + 12k + 3$ \\
Factorise: \\
$= 3(3k^{2} + 4k + 1)$ \\
$3k^{2} + 4k + 1$ is an integer, so this is a multiple of 3 \\
In both cases $n^{2} - 1$ is a multiple of 3 \\
So for all positive integers $n$ not divisible by 3, $n^{2} - 1$ is divisible by 3

@q 12
@topic Parametric curve, horizontal tangent
@marks 7
@question
(a) $x = t^{2} + t + 4$ and $y = t^{3} - 12t + 5$ \\
$\frac{dx}{dt} = 2t + 1$ \\
$\frac{dy}{dt} = 3t^{2} - 12$ \\
$\frac{dy}{dx} = \frac{dy}{dt} \div \frac{dx}{dt}$ \\
$\frac{dy}{dx} = \frac{3t^{2} - 12}{2t + 1}$ \\
(b) The tangent is parallel to the $x$-axis, so $\frac{dy}{dx} = 0$ \\
A fraction is zero when its numerator is zero: \\
$3t^{2} - 12 = 0$ \\
$3t^{2} = 12$ \\
$t^{2} = 4$ \\
$t = 2$ or $t = -2$ \\
When $t = 2$: $x = 4 + 2 + 4 = 10$ and $y = 8 - 24 + 5 = -11$ \\
When $t = -2$: $x = 4 - 2 + 4 = 6$ and $y = -8 + 24 + 5 = 21$ \\
$P$ is the turning point above the $x$-axis in the first quadrant (see Figure 3), so $t = -2$ \\
$P = (6, 21)$ \\
(c) $Q$ is on the tangent $y = 21$ \\
$t^{3} - 12t + 5 = 21$ \\
Subtract 21 from both sides: \\
$t^{3} - 12t - 16 = 0$ \\
The tangent touches $C$ at $P$, so $t = -2$ is a repeated root \\
Check: $(-2)^{3} - 12(-2) - 16 = -8 + 24 - 16 = 0$ \\
Divide by $(t + 2)$: \\
$t^{3} - 12t - 16 = (t + 2)(t^{2} - 2t - 8)$ \\
Factorise $t^{2} - 2t - 8 = (t - 4)(t + 2)$ \\
$(t + 2)^{2}(t - 4) = 0$ \\
$t = -2$ (this is $P$) or $t = 4$ \\
At $t = 4$: $x = 4^{2} + 4 + 4 = 16 + 4 + 4 = 24$ \\
$y = 4^{3} - 12(4) + 5 = 64 - 48 + 5 = 21$ \\
$Q = (24, 21)$

@q 13
@topic R sin form, fish tank temperature
@marks 8
@question
(a) Let $\sin x + \frac{1}{2}\cos x = R\sin(x + \alpha)$ \\
Expand the right-hand side using $\sin(A + B) = \sin A \cos B + \cos A \sin B$: \\
$R\sin(x + \alpha) = R\sin x \cos \alpha + R\cos x \sin \alpha$ \\
Compare the coefficients of $\sin x$: $R\cos \alpha = 1$ \\
Compare the coefficients of $\cos x$: $R\sin \alpha = \frac{1}{2}$ \\
Square and add: \\
$R^{2}\cos^{2}\alpha + R^{2}\sin^{2}\alpha = 1^{2} + \left( \frac{1}{2} \right)^{2}$ \\
$R^{2}(\cos^{2}\alpha + \sin^{2}\alpha) = 1 + \frac{1}{4}$ \\
$R^{2} = \frac{5}{4}$ \\
$R = \frac{\sqrt{5}}{2}$ \\
Divide $R\sin \alpha = \frac{1}{2}$ by $R\cos \alpha = 1$: \\
$\tan \alpha = \frac{1}{2}$ \\
$\alpha = \tan^{-1}\left( \frac{1}{2} \right) = 0.464$ radians (3 dp) \\
$\sin x + \frac{1}{2}\cos x = \frac{\sqrt{5}}{2}\sin(x + 0.464)$ \\
(b) Use (a) with $x = \frac{\pi t}{3} - 8$: \\
$\theta = 26 + \frac{\sqrt{5}}{2}\sin\left( \frac{\pi t}{3} - 8 + 0.464 \right)$ \\
The smallest value of $\sin$ is $-1$: \\
$\theta_{min} = 26 - \frac{\sqrt{5}}{2}$ \\
$= 26 - 1.118$ \\
$= 24.9$ degrees C \\
(c) The minimum occurs when $\sin\left( \frac{\pi t}{3} - 8 + 0.464 \right) = -1$ \\
Let $X = \frac{\pi t}{3} - 7.536$ \\
$0 \le t \le 24$ gives $-7.536 \le X \le 17.6$ \\
$\sin X = -1$ when $X = -\frac{\pi}{2}, \frac{3\pi}{2}, \frac{7\pi}{2}, \frac{11\pi}{2}, \ldots$ \\
($-\frac{5\pi}{2} = -7.85$ is below $-7.536$, so it is out of range, and $\frac{15\pi}{2} = 23.6$ is above 17.6.) \\
The 1st minimum is at $X = -\frac{\pi}{2}$, the 2nd at $X = \frac{3\pi}{2}$, and the 3rd at $X = \frac{7\pi}{2}$ \\
3rd time: $\frac{\pi t}{3} - 8 + 0.464 = \frac{7\pi}{2}$ \\
Add $8 - 0.464$ to both sides: \\
$\frac{\pi t}{3} = \frac{7\pi}{2} + 7.536$ \\
$\frac{\pi t}{3} = 10.9956 + 7.536 = 18.5316$ \\
Multiply both sides by $\frac{3}{\pi}$: \\
$t = \frac{3 \times 18.5316}{\pi}$ \\
$= 17.696$ \\
$0.696 \times 60 = 41.8$ minutes \\
The 3rd minimum is at 17 hours 42 minutes after midnight, which is 17:42 (5:42 pm) \\
(d) Increase the constant 26 in the model \\
This raises the mean temperature but does not change the amplitude of the variation

@q 14
@topic Quotient rule, tangent, iteration
@marks 10
@question
(a) $y = \frac{e^{2x}}{x^{3} + 4}$ \\
Use the quotient rule with $u = e^{2x}$ and $v = x^{3} + 4$ \\
$u' = 2e^{2x}$ and $v' = 3x^{2}$ \\
$\frac{dy}{dx} = \frac{u'v - uv'}{v^{2}}$ \\
$= \frac{2e^{2x}(x^{3} + 4) - e^{2x}(3x^{2})}{(x^{3} + 4)^{2}}$ \\
$\frac{dy}{dx} = \frac{2e^{2x}(x^{3} + 4) - 3x^{2}e^{2x}}{(x^{3} + 4)^{2}}$ \\
(b) At $P$, $x = p$, and $y_{P} = \frac{e^{2p}}{p^{3} + 4}$ \\
The gradient of $l$ is $m = \frac{2e^{2p}(p^{3} + 4) - 3p^{2}e^{2p}}{(p^{3} + 4)^{2}}$ \\
The tangent is $y - y_{P} = m(x - p)$ \\
It passes through the origin, so substitute $x = 0$ and $y = 0$: \\
$0 - y_{P} = m(0 - p)$ \\
$-y_{P} = -mp$ \\
$y_{P} = mp$ \\
$\frac{e^{2p}}{p^{3} + 4} = p \times \frac{2e^{2p}(p^{3} + 4) - 3p^{2}e^{2p}}{(p^{3} + 4)^{2}}$ \\
Multiply both sides by $\frac{(p^{3} + 4)^{2}}{e^{2p}}$: \\
$p^{3} + 4 = p\left[ 2(p^{3} + 4) - 3p^{2} \right]$ \\
Expand the bracket: \\
$p^{3} + 4 = p\left[ 2p^{3} + 8 - 3p^{2} \right]$ \\
$p^{3} + 4 = 2p^{4} + 8p - 3p^{3}$ \\
Move everything to the right-hand side: \\
$0 = 2p^{4} - 3p^{3} - p^{3} + 8p - 4$ \\
$0 = 2p^{4} - 4p^{3} + 8p - 4$ \\
Divide every term by 2: \\
$0 = p^{4} - 2p^{3} + 4p - 2$ \\
So $x = p$ is a solution of $x^{4} - 2x^{3} + 4x - 2 = 0$ \\
(c)(i) $x_{n+1} = \frac{2x_{n}^{3} + 2}{x_{n}^{3} + 4}$ and $x_{1} = 0.5$ \\
$x_{2} = \frac{2(0.5)^{3} + 2}{(0.5)^{3} + 4}$ \\
$= \frac{2(0.125) + 2}{0.125 + 4}$ \\
$= \frac{2.25}{4.125}$ \\
$= 0.5455$ (4 dp) \\
(ii) Keep iterating (using the ANS key): \\
$x_{3} = 0.5585$, $x_{4} = 0.5626$, $x_{5} = 0.5639$, $x_{6} = 0.5644$, $x_{7} = 0.5645$, $x_{8} = 0.5646$ \\
The values settle at $0.5646$ \\
Check with a sign change of $g(x) = x^{4} - 2x^{3} + 4x - 2$: \\
$g(0.56455) = -0.00008$ (negative) \\
$g(0.56465) = 0.0002$ (positive) \\
So $p$ is between $0.56455$ and $0.56465$ \\
$p = 0.5646$ (4 dp) \\
(d) The gradient of $l$ is $m = \frac{2e^{2p}(p^{3} + 4) - 3p^{2}e^{2p}}{(p^{3} + 4)^{2}}$ with $p = 0.5646$ \\
$m = 1.31$ (2 dp)

@q 15
@topic Partial fractions, substitution, integral
@marks 12
@question
(a) $\frac{u^{2}}{u^{2} - 1} = A + \frac{B}{u + 1} + \frac{C}{u - 1}$ \\
Multiply both sides by $(u^{2} - 1) = (u + 1)(u - 1)$: \\
$u^{2} = A(u^{2} - 1) + B(u - 1) + C(u + 1)$ \\
Compare the coefficients of $u^{2}$: $A = 1$ \\
Let $u = 1$: $1 = 0 + 0 + 2C$, so $C = \frac{1}{2}$ \\
Let $u = -1$: $1 = 0 - 2B + 0$, so $B = -\frac{1}{2}$ \\
Check the constant terms: $-A - B + C = -1 + \frac{1}{2} + \frac{1}{2} = 0$, which matches $u^{2}$ having no constant term \\
$\frac{u^{2}}{u^{2} - 1} = 1 - \frac{1}{2(u + 1)} + \frac{1}{2(u - 1)}$ \\
So $A = 1$, $B = -\frac{1}{2}$, $C = \frac{1}{2}$ \\
(b) $u = \sqrt{1 + e^{3x}}$ \\
Square both sides: \\
$u^{2} = 1 + e^{3x}$ \\
Differentiate with respect to $x$: \\
$2u\frac{du}{dx} = 3e^{3x}$ \\
From $u^{2} = 1 + e^{3x}$: $e^{3x} = u^{2} - 1$ \\
$2u\frac{du}{dx} = 3(u^{2} - 1)$ \\
$dx = \frac{2u}{3(u^{2} - 1)} \, du$ \\
Limits: when $x = \frac{1}{3}\ln 3$, $3x = \ln 3$, $e^{3x} = 3$, so $u = \sqrt{1 + 3} = 2$ \\
When $x = \frac{1}{3}\ln 8$, $3x = \ln 8$, $e^{3x} = 8$, so $u = \sqrt{1 + 8} = 3$ \\
$\int \sqrt{1 + e^{3x}} \, dx = \int u \times \frac{2u}{3(u^{2} - 1)} \, du$ \\
$= \int \frac{2u^{2}}{3(u^{2} - 1)} \, du$ \\
$= \frac{2}{3}\int \frac{u^{2}}{u^{2} - 1} \, du$ \\
$\int_{\frac{1}{3}\ln 3}^{\frac{1}{3}\ln 8} \sqrt{1 + e^{3x}} \, dx = \frac{2}{3}\int_{2}^{3} \frac{u^{2}}{u^{2} - 1} \, du$ \\
So $k = \frac{2}{3}$, $\alpha = 2$, $\beta = 3$ \\
(c) Use (a): \\
$\int \frac{u^{2}}{u^{2} - 1} \, du = \int \left( 1 - \frac{1}{2(u + 1)} + \frac{1}{2(u - 1)} \right) du$ \\
$= u - \frac{1}{2}\ln(u + 1) + \frac{1}{2}\ln(u - 1) + c$ \\
Apply the limits 2 and 3: \\
$\left[ u - \frac{1}{2}\ln(u + 1) + \frac{1}{2}\ln(u - 1) \right]_{2}^{3}$ \\
Upper limit $u = 3$: $3 - \frac{1}{2}\ln 4 + \frac{1}{2}\ln 2$ \\
Lower limit $u = 2$: $2 - \frac{1}{2}\ln 3 + \frac{1}{2}\ln 1 = 2 - \frac{1}{2}\ln 3$ \\
Subtract: \\
$= 3 - \frac{1}{2}\ln 4 + \frac{1}{2}\ln 2 - 2 + \frac{1}{2}\ln 3$ \\
$= 1 - \frac{1}{2}\ln 4 + \frac{1}{2}\ln 2 + \frac{1}{2}\ln 3$ \\
Use $\ln 4 = 2\ln 2$: \\
$= 1 - \ln 2 + \frac{1}{2}\ln 2 + \frac{1}{2}\ln 3$ \\
$= 1 - \frac{1}{2}\ln 2 + \frac{1}{2}\ln 3$ \\
$= 1 + \frac{1}{2}(\ln 3 - \ln 2)$ \\
$= 1 + \frac{1}{2}\ln\frac{3}{2}$ \\
Multiply by $\frac{2}{3}$: \\
$\int_{\frac{1}{3}\ln 3}^{\frac{1}{3}\ln 8} \sqrt{1 + e^{3x}} \, dx = \frac{2}{3}\left( 1 + \frac{1}{2}\ln\frac{3}{2} \right)$ \\
$= \frac{2}{3} + \frac{1}{3}\ln\frac{3}{2}$ \\
So $p = \frac{2}{3}$, $q = \frac{1}{3}$, $r = \frac{3}{2}$
