@paper P1 Specimen

@q 1
@topic Trapezium rule, area estimate
@marks 6
@question
(a) The $x$ values go up in steps of 0.5, so $h = 0.5$ \\
Trapezium rule: area $\approx \frac{h}{2}\{ y_{0} + y_{4} + 2(y_{1} + y_{2} + y_{3}) \}$ \\
$\text{Area}(R) \approx \frac{1}{2} \times 0.5 \times \{ 0.5 + 1.0981 + 2(0.6742 + 0.8284 + 0.9686) \}$ \\
First and last: $0.5 + 1.0981 = 1.5981$ \\
Middle three: $0.6742 + 0.8284 + 0.9686 = 2.4712$ \\
Double the middle three: $2 \times 2.4712 = 4.9424$ \\
$= 0.25 \times \{ 1.5981 + 4.9424 \}$ \\
$= 0.25 \times 6.5405$ \\
$= 1.635125$ \\
$\text{Area}(R) \approx 1.635$ (3 dp) \\
(b) Use more strips (more trapezia) between $x = 1$ and $x = 3$, so that each strip is narrower \\
(c)(i) $\int_{1}^{3} \frac{5x}{1 + \sqrt{x}} \, dx = 5\int_{1}^{3} \frac{x}{1 + \sqrt{x}} \, dx$ \\
The integral on the right is the area of $R$, which is 1.635 from (a) \\
$= 5 \times 1.635$ \\
$= 8.175$ \\
(ii) Split the integral into two parts: \\
$\int_{1}^{3} \left( 6 + \frac{x}{1 + \sqrt{x}} \right) dx = \int_{1}^{3} 6 \, dx + \int_{1}^{3} \frac{x}{1 + \sqrt{x}} \, dx$ \\
$\int_{1}^{3} 6 \, dx = [6x]_{1}^{3} = 6(3) - 6(1) = 12$ \\
The second part is 1.635 from (a) \\
$= 12 + 1.635$ \\
$= 13.635$

@q 2
@topic Binomial expansion, estimate sqrt 2
@marks 8
@question
(a) Take out a factor of 4 from the bracket: \\
$(4 + 5x)^{\frac{1}{2}} = \left( 4\left( 1 + \frac{5x}{4} \right) \right)^{\frac{1}{2}}$ \\
$= 4^{\frac{1}{2}}\left( 1 + \frac{5x}{4} \right)^{\frac{1}{2}}$ \\
$= 2\left( 1 + \frac{5x}{4} \right)^{\frac{1}{2}}$ \\
Binomial expansion: $(1 + X)^{n} = 1 + nX + \frac{n(n-1)}{2!}X^{2} + \ldots$ with $n = \frac{1}{2}$ and $X = \frac{5x}{4}$ \\
Term 2: $nX = \frac{1}{2} \times \frac{5x}{4} = \frac{5x}{8}$ \\
Term 3: $\frac{n(n-1)}{2!}X^{2} = \frac{\frac{1}{2} \times \left( -\frac{1}{2} \right)}{2}\left( \frac{5x}{4} \right)^{2}$ \\
$\frac{1}{2} \times \left( -\frac{1}{2} \right) = -\frac{1}{4}$ \\
$-\frac{1}{4} \div 2 = -\frac{1}{8}$ \\
$\left( \frac{5x}{4} \right)^{2} = \frac{25x^{2}}{16}$ \\
Term 3 $= -\frac{1}{8} \times \frac{25x^{2}}{16} = -\frac{25x^{2}}{128}$ \\
$\left( 1 + \frac{5x}{4} \right)^{\frac{1}{2}} = 1 + \frac{5x}{8} - \frac{25x^{2}}{128} + \ldots$ \\
Multiply by 2: \\
$(4 + 5x)^{\frac{1}{2}} = 2 + \frac{10x}{8} - \frac{50x^{2}}{128} + \ldots$ \\
$= 2 + \frac{5}{4}x - \frac{25}{64}x^{2} + \ldots$ \\
So $k = -\frac{25}{64}$ \\
(b)(i) Substitute $x = \frac{1}{10}$ into $(4 + 5x)^{\frac{1}{2}}$: \\
$\left( 4 + 5 \times \frac{1}{10} \right)^{\frac{1}{2}} = \sqrt{4.5}$ \\
$4.5 = \frac{9}{2}$, so $\sqrt{4.5} = \frac{\sqrt{9}}{\sqrt{2}} = \frac{3}{\sqrt{2}}$ \\
Rationalise: $\frac{3}{\sqrt{2}} = \frac{3\sqrt{2}}{2} = \frac{3}{2}\sqrt{2}$ \\
Substitute $x = \frac{1}{10}$ into the expansion: \\
$2 + \frac{5}{4}\left( \frac{1}{10} \right) - \frac{25}{64}\left( \frac{1}{10} \right)^{2}$ \\
$= 2 + \frac{5}{40} - \frac{25}{6400}$ \\
$= 2 + \frac{1}{8} - \frac{1}{256}$ \\
Write each term over 256: \\
$= \frac{512}{256} + \frac{32}{256} - \frac{1}{256}$ \\
$= \frac{543}{256}$ \\
So $\frac{3}{2}\sqrt{2} \approx \frac{543}{256}$ \\
Multiply both sides by $\frac{2}{3}$: \\
$\sqrt{2} \approx \frac{2 \times 543}{3 \times 256}$ \\
$= \frac{1086}{768}$ \\
Divide the top and the bottom by 6: \\
$\sqrt{2} \approx \frac{181}{128}$ \\
(ii) The expansion of $\left( 1 + \frac{5x}{4} \right)^{\frac{1}{2}}$ is valid when $\left| \frac{5x}{4} \right| < 1$ \\
$|x| < \frac{4}{5}$ \\
$x = \frac{1}{10}$ satisfies $|x| < \frac{4}{5}$, so substituting it into the expansion gives a valid approximation

@q 3
@topic Periodic sequence and sum
@marks 4
@question
(a) $a_{n+1} = \frac{a_{n} - 3}{a_{n} - 2}$ and $a_{1} = 3$ \\
$a_{2} = \frac{a_{1} - 3}{a_{1} - 2}$ \\
$= \frac{3 - 3}{3 - 2}$ \\
$= \frac{0}{1}$ \\
$= 0$ \\
$a_{3} = \frac{a_{2} - 3}{a_{2} - 2}$ \\
$= \frac{0 - 3}{0 - 2}$ \\
$= \frac{-3}{-2}$ \\
$= 1.5$ \\
$a_{4} = \frac{a_{3} - 3}{a_{3} - 2}$ \\
$= \frac{1.5 - 3}{1.5 - 2}$ \\
$= \frac{-1.5}{-0.5}$ \\
$= 3$ \\
$a_{4} = a_{1}$, so the sequence repeats every 3 terms: $3, 0, 1.5, 3, 0, 1.5, \ldots$ \\
One cycle adds up to $3 + 0 + 1.5 = 4.5$ \\
$100 = 3 \times 33 + 1$, so there are 33 full cycles, plus one more term, which is $a_{100} = a_{1} = 3$ \\
$\sum_{r=1}^{100} a_{r} = 33 \times 4.5 + 3$ \\
$= 148.5 + 3$ \\
$= 151.5$ \\
(b) $\sum_{r=1}^{99} a_{r}$ is 33 full cycles: $33 \times 4.5 = 148.5$ \\
$\sum_{r=1}^{100} a_{r} + \sum_{r=1}^{99} a_{r} = 151.5 + 148.5$ \\
$= 300$

@q 4
@topic Vectors and parallelogram
@marks 5
@question
(Vectors are given as column vectors.) \\
(a) $\text{OA} = (1, 7, -2)$, $\text{OB} = (4, 3, 3)$, $\text{OC} = (2, 10, 9)$ \\
In the parallelogram $ABCD$, $\text{DC} = \text{AB}$, so $\text{OD} = \text{OC} - \text{AB} = \text{OC} + \text{BA}$ \\
$\text{BA} = \text{OA} - \text{OB}$ \\
$= (1 - 4, 7 - 3, -2 - 3)$ \\
$= (-3, 4, -5)$ \\
$\text{OD} = \text{OC} + \text{BA}$ \\
$= (2, 10, 9) + (-3, 4, -5)$ \\
$= (2 - 3, 10 + 4, 9 - 5)$ \\
$= (-1, 14, 4)$ \\
Check: $\text{AD} = \text{OD} - \text{OA} = (-2, 7, 6)$ and $\text{BC} = \text{OC} - \text{OB} = (-2, 7, 6)$, which are equal \\
(b) $\text{AB} = \text{OB} - \text{OA}$ \\
$= (4 - 1, 3 - 7, 3 - (-2))$ \\
$= (3, -4, 5)$ \\
$|\text{AB}| = \sqrt{3^{2} + (-4)^{2} + 5^{2}}$ \\
$= \sqrt{9 + 16 + 25}$ \\
$= \sqrt{50}$ \\
$= 5\sqrt{2}$ \\
$|\text{AX}| = 10\sqrt{2} = 2 \times 5\sqrt{2} = 2|\text{AB}|$ \\
$AX$ has the same direction as $AB$, so $\text{AX} = 2\text{AB}$ \\
$= (6, -8, 10)$ \\
$\text{OX} = \text{OA} + \text{AX}$ \\
$= (1, 7, -2) + (6, -8, 10)$ \\
$= (7, -1, 8)$

@q 5
@topic Factor theorem, logs, no real roots
@marks 10
@question
(a)(i) $f(x) = x^{3} + ax^{2} - ax + 48$ and $f(-6) = 0$ \\
$(-6)^{3} + a(-6)^{2} - a(-6) + 48 = 0$ \\
$-216 + 36a + 6a + 48 = 0$ \\
Collect the terms in $a$ and the numbers: \\
$42a - 168 = 0$ \\
Add 168 to both sides: \\
$42a = 168$ \\
Divide both sides by 42: \\
$a = 4$ \\
(ii) With $a = 4$: $f(x) = x^{3} + 4x^{2} - 4x + 48$ \\
$f(-6) = 0$, so $(x + 6)$ is a factor \\
Write $f(x) = (x + 6)(x^{2} + bx + 8)$, as the constant term is $6 \times 8 = 48$ \\
Expand: $(x + 6)(x^{2} + bx + 8) = x^{3} + bx^{2} + 8x + 6x^{2} + 6bx + 48$ \\
$= x^{3} + (b + 6)x^{2} + (8 + 6b)x + 48$ \\
Compare the $x^{2}$ terms: $b + 6 = 4$, so $b = -2$ \\
Check the $x$ terms: $8 + 6(-2) = -4$ \\
$f(x) = (x + 6)(x^{2} - 2x + 8)$ \\
(b) $2\log_{2}(x + 2) + \log_{2} x - \log_{2}(x - 6) = 3$ \\
Use the power law: $2\log_{2}(x + 2) = \log_{2}\left( (x + 2)^{2} \right)$ \\
$\log_{2}\left( (x + 2)^{2} \right) + \log_{2} x - \log_{2}(x - 6) = 3$ \\
Use the addition law on the first two terms: \\
$\log_{2}\left( x(x + 2)^{2} \right) - \log_{2}(x - 6) = 3$ \\
Use the subtraction law: \\
$\log_{2}\left( \frac{x(x + 2)^{2}}{x - 6} \right) = 3$ \\
Undo the logarithm: if $\log_{2} y = 3$ then $y = 2^{3} = 8$ \\
$\frac{x(x + 2)^{2}}{x - 6} = 8$ \\
Multiply both sides by $(x - 6)$: \\
$x(x + 2)^{2} = 8(x - 6)$ \\
Expand the brackets: \\
$x(x^{2} + 4x + 4) = 8x - 48$ \\
$x^{3} + 4x^{2} + 4x = 8x - 48$ \\
Subtract $8x$ from both sides and add 48 to both sides: \\
$x^{3} + 4x^{2} + 4x - 8x + 48 = 0$ \\
$x^{3} + 4x^{2} - 4x + 48 = 0$ as required \\
(c) By (a)(ii), $x^{3} + 4x^{2} - 4x + 48 = (x + 6)(x^{2} - 2x + 8)$ \\
$(x + 6)(x^{2} - 2x + 8) = 0$ \\
So $x = -6$ or $x^{2} - 2x + 8 = 0$ \\
For $x^{2} - 2x + 8 = 0$: discriminant $= b^{2} - 4ac = (-2)^{2} - 4(1)(8)$ \\
$= 4 - 32$ \\
$= -28$ \\
The discriminant is negative, so $x^{2} - 2x + 8 = 0$ has no real roots \\
$x = -6$ is not a solution of the log equation, as $\log_{2} x$ and $\log_{2}(x - 6)$ are not defined for negative numbers \\
So $2\log_{2}(x + 2) + \log_{2} x - \log_{2}(x - 6) = 3$ has no real roots

@q 6
@topic Quadratic model, road tunnel
@marks 6
@question
(a) Put the origin $O$ at the middle of the base \\
The base is 6 m wide, so $A = (-3, 0)$ and $B = (3, 0)$, and the top is $C = (0, 5)$ \\
The curve crosses the $x$-axis at $x = -3$ and $x = 3$, so use $y = a(3 - x)(3 + x)$ \\
$y = a(9 - x^{2})$ \\
At $C$, $x = 0$ and $y = 5$: \\
$5 = a(9 - 0)$ \\
$5 = 9a$ \\
$a = \frac{5}{9}$ \\
$y = \frac{5}{9}(9 - x^{2})$, for $-3 \le x \le 3$ \\
(b) The coach is 2.4 m wide, so if it is in the middle of the tunnel, its sides are at $x = \pm 1.2$ \\
Find the height of the tunnel at $x = 1.2$: \\
$y = \frac{5}{9}(9 - 1.2^{2})$ \\
$= \frac{5}{9}(9 - 1.44)$ \\
$= \frac{5}{9}(7.56)$ \\
$= 4.2$ m \\
The coach is 4.1 m high, and $4.2 > 4.1$ \\
So, according to the model, the coach can enter the tunnel \\
(c) The model assumes the coach drives through the middle of the tunnel, which is only possible for a one-way tunnel \\
(Also, the road may be cambered rather than horizontal, or there may be lights that block the path of the coach.)

@q 7
@topic Integration by parts, exponential
@marks 5
@question
$y = 2e^{2x} - xe^{2x}$ \\
Factorise: $y = (2 - x)e^{2x}$ \\
$R$ is bounded by the curve, the $x$-axis and the $y$-axis, so find where the curve meets the $x$-axis: \\
$(2 - x)e^{2x} = 0$ \\
$e^{2x}$ is never zero, so $2 - x = 0$, giving $x = 2$ \\
Area of $R = \int_{0}^{2} (2 - x)e^{2x} \, dx$ \\
Integrate by parts: let $u = 2 - x$ and $\frac{dv}{dx} = e^{2x}$ \\
$\frac{du}{dx} = -1$ and $v = \frac{1}{2}e^{2x}$ \\
$\int (2 - x)e^{2x} \, dx = uv - \int v\frac{du}{dx} \, dx$ \\
$= \frac{1}{2}(2 - x)e^{2x} - \int \frac{1}{2}e^{2x}(-1) \, dx$ \\
$= \frac{1}{2}(2 - x)e^{2x} + \frac{1}{2}\int e^{2x} \, dx$ \\
$= \frac{1}{2}(2 - x)e^{2x} + \frac{1}{2} \times \frac{1}{2}e^{2x}$ \\
$= \frac{1}{2}(2 - x)e^{2x} + \frac{1}{4}e^{2x}$ \\
Apply the limits: \\
$\left[ \frac{1}{2}(2 - x)e^{2x} + \frac{1}{4}e^{2x} \right]_{0}^{2}$ \\
Upper limit $x = 2$: $\frac{1}{2}(0)e^{4} + \frac{1}{4}e^{4} = \frac{1}{4}e^{4}$ \\
Lower limit $x = 0$: $\frac{1}{2}(2)e^{0} + \frac{1}{4}e^{0} = 1 + \frac{1}{4} = \frac{5}{4}$ \\
Subtract: \\
Area of $R = \frac{1}{4}e^{4} - \frac{5}{4}$ \\
So $p = \frac{1}{4}$ and $q = -\frac{5}{4}$

@q 8
@topic Geometric series, wheat harvest
@marks 5
@question
(a) The yearly amounts form a geometric sequence with $a = 2100$ and $r = 1.012$ (an increase of 1.2 percent is a multiplier of 1.012) \\
2017 to 2030 inclusive is $2030 - 2017 + 1 = 14$ years \\
$S_{n} = \frac{a(r^{n} - 1)}{r - 1}$ \\
$S_{14} = \frac{2100(1.012^{14} - 1)}{1.012 - 1}$ \\
$1.012^{14} = 1.18175$ \\
$= \frac{2100(1.18175 - 1)}{0.012}$ \\
$= \frac{2100 \times 0.18175}{0.012}$ \\
$= 31806.99$ \\
Total mass $= 31800$ tonnes (3 sf) \\
(b) Every year at least 2000 tonnes are harvested (the smallest yearly amount is 2100 tonnes) \\
So each year the first 2000 tonnes cost GBP 5.15 per tonne, and the rest cost GBP 6.45 per tonne \\
Over 14 years, the tonnes charged at GBP 5.15 are $2000 \times 14 = 28000$ \\
Cost of these: $5.15 \times 28000 = 144200$ \\
The remaining tonnes are $31806.99 - 28000 = 3806.99$ \\
Cost of these: $6.45 \times 3806.99 = 24555.12$ \\
Total cost $= 144200 + 24555.12$ \\
$= 168755.12$ \\
The expected cost is GBP 169000 (nearest GBP 1000)

@q 9
@topic First principles, cubic gradient
@marks 5
@question
$y = 2x^{3} + 5$ and $P$ is $(1, 7)$ \\
Let $Q$ be a point on the curve with $x$ coordinate $1 + h$ \\
$y_{Q} = 2(1 + h)^{3} + 5$ \\
Expand $(1 + h)^{3} = 1 + 3h + 3h^{2} + h^{3}$ \\
$y_{Q} = 2(1 + 3h + 3h^{2} + h^{3}) + 5$ \\
Expand the bracket: \\
$y_{Q} = 2 + 6h + 6h^{2} + 2h^{3} + 5$ \\
$y_{Q} = 7 + 6h + 6h^{2} + 2h^{3}$ \\
Gradient of the chord $PQ = \frac{y_{Q} - y_{P}}{x_{Q} - x_{P}}$ \\
$= \frac{(7 + 6h + 6h^{2} + 2h^{3}) - 7}{(1 + h) - 1}$ \\
$= \frac{6h + 6h^{2} + 2h^{3}}{h}$ \\
Factorise the top: \\
$= \frac{h(6 + 6h + 2h^{2})}{h}$ \\
Cancel $h$ (as $h \ne 0$): \\
$= 6 + 6h + 2h^{2}$ \\
As $h \to 0$, $Q$ moves towards $P$ and the chord becomes the tangent: \\
$\frac{dy}{dx} = \lim_{h \to 0} (6 + 6h + 2h^{2}) = 6$ \\
The gradient of the tangent at $P$ is 6

@q 10
@topic Functions, inverse, composite
@marks 13
@question
(a) Let $y = \frac{3x - 5}{x + 1}$ \\
Multiply both sides by $(x + 1)$: \\
$y(x + 1) = 3x - 5$ \\
Expand the bracket: \\
$xy + y = 3x - 5$ \\
Get the $x$ terms on one side and the rest on the other: \\
$y + 5 = 3x - xy$ \\
Factorise the right-hand side: \\
$y + 5 = x(3 - y)$ \\
Divide both sides by $(3 - y)$: \\
$x = \frac{y + 5}{3 - y}$ \\
Replace $y$ by $x$: \\
$f^{-1}(x) = \frac{x + 5}{3 - x}$, $x \in \mathbb{R}$, $x \ne 3$ \\
(b) $\text{ff}(x) = f\left( \frac{3x - 5}{x + 1} \right)$ \\
Replace $x$ in $f(x) = \frac{3x - 5}{x + 1}$ by $\frac{3x - 5}{x + 1}$: \\
$\text{ff}(x) = \frac{3\left( \frac{3x - 5}{x + 1} \right) - 5}{\frac{3x - 5}{x + 1} + 1}$ \\
Write the top as a single fraction: \\
$3\left( \frac{3x - 5}{x + 1} \right) - 5 = \frac{3(3x - 5) - 5(x + 1)}{x + 1}$ \\
Write the bottom as a single fraction: \\
$\frac{3x - 5}{x + 1} + 1 = \frac{(3x - 5) + (x + 1)}{x + 1}$ \\
$\text{ff}(x) = \frac{\frac{3(3x - 5) - 5(x + 1)}{x + 1}}{\frac{(3x - 5) + (x + 1)}{x + 1}}$ \\
Cancel the common denominator $(x + 1)$: \\
$= \frac{3(3x - 5) - 5(x + 1)}{(3x - 5) + (x + 1)}$ \\
Expand the brackets on the top: $9x - 15 - 5x - 5 = 4x - 20$ \\
Collect the terms on the bottom: $3x - 5 + x + 1 = 4x - 4$ \\
$= \frac{4x - 20}{4x - 4}$ \\
Divide the top and the bottom by 4: \\
$= \frac{x - 5}{x - 1}$ \\
So $a = -5$ \\
(c) $g(2) = 2^{2} - 3(2) = 4 - 6 = -2$ \\
$\text{fg}(2) = f(-2)$ \\
$= \frac{3(-2) - 5}{-2 + 1}$ \\
$= \frac{-6 - 5}{-1}$ \\
$= \frac{-11}{-1}$ \\
$= 11$ \\
(d) $g(x) = x^{2} - 3x$ for $0 \le x \le 5$ \\
Complete the square: \\
$g(x) = \left( x - \frac{3}{2} \right)^{2} - \frac{9}{4}$ \\
$g(x) = (x - 1.5)^{2} - 2.25$ \\
The minimum is $-2.25$, at $x = 1.5$, which is in the domain \\
Check the ends of the domain: \\
$g(0) = 0$ \\
$g(5) = 25 - 15 = 10$ \\
The largest value is 10 \\
Range of $g$: $-2.25 \le g(x) \le 10$ \\
(e) $g(0) = 0$ and $g(3) = 9 - 9 = 0$ \\
Two different $x$ values give the same $y$ value, so $g$ is a many-to-one function \\
A many-to-one function does not have an inverse

@q 11
@topic Inflection point, cubic, find k
@marks 10
@question
(a) $f'(x) = k - 4x - 3x^{2}$ \\
Differentiate again: \\
$f''(x) = -4 - 6x$ \\
Set $f''(x) = 0$: \\
$-4 - 6x = 0$ \\
$-6x = 4$ \\
$x = -\frac{2}{3}$ \\
Check that $f''(x)$ changes sign either side of $x = -\frac{2}{3}$: \\
$f''(-0.7) = -4 - 6(-0.7) = -4 + 4.2 = 0.2 > 0$ \\
$f''(-0.6) = -4 - 6(-0.6) = -4 + 3.6 = -0.4 < 0$ \\
Or use the third derivative: $f'''(x) = -6$, which is not zero \\
So $C$ has a point of inflection at $x = -\frac{2}{3}$ \\
(b) Integrate $f'(x) = k - 4x - 3x^{2}$: \\
$f(x) = kx - \frac{4x^{2}}{2} - \frac{3x^{3}}{3} + c$ \\
$f(x) = kx - 2x^{2} - x^{3} + c$ \\
$C$ passes through the origin, so $f(0) = 0$: \\
$0 = 0 - 0 - 0 + c$ \\
$c = 0$ \\
$f(x) = kx - 2x^{2} - x^{3}$ \\
Factorise: \\
$f(x) = x(k - 2x - x^{2})$ \\
$C$ crosses the $x$-axis where $f(x) = 0$: \\
$x = 0$ (the origin) or $k - 2x - x^{2} = 0$ \\
Rearrange the second equation: \\
$x^{2} + 2x - k = 0$ \\
Complete the square: \\
$(x + 1)^{2} - 1 - k = 0$ \\
$(x + 1)^{2} = k + 1$ \\
$x + 1 = \pm\sqrt{k + 1}$ \\
$x = -1 \pm \sqrt{k + 1}$ \\
$A$ has the smaller $x$ value: $x_{A} = -1 - \sqrt{k + 1}$ \\
$B$ has the larger $x$ value: $x_{B} = -1 + \sqrt{k + 1}$ \\
$AB = x_{B} - x_{A}$ \\
$= (-1 + \sqrt{k + 1}) - (-1 - \sqrt{k + 1})$ \\
$= 2\sqrt{k + 1}$ \\
Given $AB = 4\sqrt{2}$: \\
$2\sqrt{k + 1} = 4\sqrt{2}$ \\
Divide both sides by 2: \\
$\sqrt{k + 1} = 2\sqrt{2}$ \\
Square both sides: \\
$k + 1 = 8$ \\
$k = 7$

@q 12
@topic Substitution, trig integral, ln
@marks 7
@question
Let $u = 1 + \cos \theta$ \\
Differentiate: $\frac{du}{d\theta} = -\sin \theta$ \\
So $\sin \theta \, d\theta = -du$ \\
From the substitution, $\cos \theta = u - 1$ \\
Use $\sin 2\theta = 2\sin \theta \cos \theta$: \\
$\frac{\sin 2\theta}{1 + \cos \theta} \, d\theta = \frac{2\sin \theta \cos \theta}{1 + \cos \theta} \, d\theta$ \\
$= \frac{2\cos \theta}{1 + \cos \theta} \times \sin \theta \, d\theta$ \\
$= \frac{2(u - 1)}{u} \times (-du)$ \\
$= -\frac{2(u - 1)}{u} \, du$ \\
Limits: when $\theta = 0$, $u = 1 + \cos 0 = 2$ \\
When $\theta = \frac{\pi}{2}$, $u = 1 + \cos\frac{\pi}{2} = 1$ \\
$\int_{0}^{\frac{\pi}{2}} \frac{\sin 2\theta}{1 + \cos \theta} \, d\theta = \int_{2}^{1} -\frac{2(u - 1)}{u} \, du$ \\
Swap the limits, which changes the sign: \\
$= \int_{1}^{2} \frac{2(u - 1)}{u} \, du$ \\
Divide each term of the numerator by $u$: \\
$\frac{2(u - 1)}{u} = \frac{2u - 2}{u} = 2 - \frac{2}{u}$ \\
$= \int_{1}^{2} \left( 2 - \frac{2}{u} \right) du$ \\
Integrate each term: \\
$= \left[ 2u - 2\ln u \right]_{1}^{2}$ \\
Upper limit $u = 2$: $2(2) - 2\ln 2 = 4 - 2\ln 2$ \\
Lower limit $u = 1$: $2(1) - 2\ln 1 = 2 - 0 = 2$ \\
Subtract: \\
$= (4 - 2\ln 2) - 2$ \\
$= 2 - 2\ln 2$ as required

@q 13
@topic R sin form, tide depth model
@marks 11
@question
(a) Let $2\sin \theta - 1.5\cos \theta = R\sin(\theta - \alpha)$ \\
Expand the right-hand side using $\sin(A - B) = \sin A \cos B - \cos A \sin B$: \\
$R\sin(\theta - \alpha) = R\sin \theta \cos \alpha - R\cos \theta \sin \alpha$ \\
Compare the coefficients of $\sin \theta$: $R\cos \alpha = 2$ \\
Compare the coefficients of $\cos \theta$: $R\sin \alpha = 1.5$ \\
Square and add: \\
$R^{2}\cos^{2}\alpha + R^{2}\sin^{2}\alpha = 2^{2} + 1.5^{2}$ \\
$R^{2} = 4 + 2.25$ \\
$R^{2} = 6.25$ \\
$R = 2.5$ \\
Divide $R\sin \alpha = 1.5$ by $R\cos \alpha = 2$: \\
$\tan \alpha = \frac{1.5}{2} = 0.75$ \\
$\alpha = \tan^{-1}(0.75) = 0.6435$ radians (4 dp) \\
$2\sin \theta - 1.5\cos \theta = 2.5\sin(\theta - 0.6435)$ \\
(b) At 00:00, $t = 0$: \\
$D = 6 + 2\sin 0 - 1.5\cos 0$ \\
$= 6 + 0 - 1.5(1)$ \\
$= 4.5$ m \\
(c) Use (a): $D = 6 + 2.5\sin\left( \frac{4\pi t}{25} - 0.6435 \right)$ \\
The greatest value of $\sin$ is 1: \\
$D_{max} = 6 + 2.5$ \\
$= 8.5$ m \\
(d) The maximum depth occurs when $\sin\left( \frac{4\pi t}{25} - 0.6435 \right) = 1$ \\
$\frac{4\pi t}{25} - 0.6435 = \frac{\pi}{2}$ or $\frac{5\pi}{2}$ (adding $2\pi$ each time) \\
The first, $\frac{\pi}{2}$, gives a time in the morning: $t = \frac{25}{4\pi}\left( \frac{\pi}{2} + 0.6435 \right) = 4.41$, which is 04:24 \\
The afternoon solution is the next one: \\
$\frac{4\pi t}{25} - 0.6435 = \frac{5\pi}{2}$ \\
Add $0.6435$ to both sides: \\
$\frac{4\pi t}{25} = \frac{5\pi}{2} + 0.6435$ \\
$= 7.8540 + 0.6435$ \\
$= 8.4975$ \\
Multiply both sides by $\frac{25}{4\pi}$: \\
$t = \frac{25 \times 8.4975}{4\pi}$ \\
$= 16.905$ \\
$0.905 \times 60 = 54.3$ minutes \\
The maximum depth in the afternoon is at 16:54 (4:54 pm) \\
(e)(i) At 00:00 on 19th October, Tom's model has $t = 24$: \\
$D = 6 + 2\sin\left( \frac{4\pi \times 24}{25} \right) - 1.5\cos\left( \frac{4\pi \times 24}{25} \right)$ \\
$= 6 + 2(-0.4818) - 1.5(0.8763)$ \\
$= 6 - 0.9635 - 1.3145$ \\
$= 3.72$ m \\
Jolene's model has $x = 0$: \\
$H = 6 + 2\sin 0 - 1.5\cos 0 = 4.5$ m \\
$4.5 \ne 3.72$, so the two models give different depths at the same moment \\
Jolene's model does not carry on from where Tom's model ends, so it is not correct \\
(ii) Jolene's model should continue Tom's model, so replace $t$ by $x + 24$: \\
$H = 6 + 2\sin\left( \frac{4\pi(x + 24)}{25} \right) - 1.5\cos\left( \frac{4\pi(x + 24)}{25} \right)$, $0 \le x < 24$ \\
(Or shift the model down by $4.5 - 3.72 = 0.78$: $H = 5.22 + 2\sin\left( \frac{4\pi x}{25} \right) - 1.5\cos\left( \frac{4\pi x}{25} \right)$.)

@q 14
@topic Parametric to Cartesian equation
@marks 5
@question
$x = 4\cos\left( t + \frac{\pi}{6} \right)$ and $y = 2\sin t$ \\
Expand $\cos\left( t + \frac{\pi}{6} \right)$ using $\cos(A + B) = \cos A \cos B - \sin A \sin B$: \\
$x = 4\left( \cos t \cos\frac{\pi}{6} - \sin t \sin\frac{\pi}{6} \right)$ \\
Use $\cos\frac{\pi}{6} = \frac{\sqrt{3}}{2}$ and $\sin\frac{\pi}{6} = \frac{1}{2}$: \\
$x = 4\left( \frac{\sqrt{3}}{2}\cos t - \frac{1}{2}\sin t \right)$ \\
$x = 2\sqrt{3}\cos t - 2\sin t$ \\
Add $y = 2\sin t$: \\
$x + y = 2\sqrt{3}\cos t - 2\sin t + 2\sin t$ \\
$x + y = 2\sqrt{3}\cos t$ \\
So $\cos t = \frac{x + y}{2\sqrt{3}}$ \\
From $y = 2\sin t$: $\sin t = \frac{y}{2}$ \\
Use $\cos^{2} t + \sin^{2} t = 1$: \\
$\left( \frac{x + y}{2\sqrt{3}} \right)^{2} + \left( \frac{y}{2} \right)^{2} = 1$ \\
$\frac{(x + y)^{2}}{12} + \frac{y^{2}}{4} = 1$ \\
Multiply every term by 12: \\
$(x + y)^{2} + \frac{12y^{2}}{4} = 12$ \\
$(x + y)^{2} + 3y^{2} = 12$ \\
So $a = 3$ and $b = 12$
