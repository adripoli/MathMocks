@paper P1 Shadow June 2022

@q 1
@topic Transformations of a point on a curve
@marks 4
@question
(a) $y = f(x) - 4$ moves the curve 4 units down \\
Subtract 4 from the $y$ coordinate and leave $x$ alone: \\
$(-5, -2 - 4)$ \\
$P$ is mapped to $(-5, -6)$ \\
(b) $y = |f(x)|$ turns every negative $y$ value positive \\
$|-2| = 2$ \\
The $x$ coordinate is unchanged \\
$P$ is mapped to $(-5, 2)$ \\
(c) $y = 5f(x + 4) - 4$ \\
Do it in stages. First $f(x + 4)$ moves the curve 4 units to the left, so subtract 4 from $x$: \\
$x = -5 - 4 = -9$ \\
Then multiply the $y$ coordinate by 5: \\
$5 \times (-2) = -10$ \\
Then subtract 4: \\
$-10 - 4 = -14$ \\
$P$ is mapped to $(-9, -14)$ \\
(Check: the new curve at $x = -9$ has $y = 5f(-9 + 4) - 4 = 5f(-5) - 4 = 5(-2) - 4 = -14$)

@q 2
@topic Factor theorem, find k
@marks 3
@question
$(x + 3)$ is a factor of $f(x)$, so by the factor theorem $f(-3) = 0$ \\
$f(x) = (x - 2)(x^{3} + 8x^{2} - 20x + k) - 1225$ \\
First bracket: $-3 - 2 = -5$ \\
Second bracket: evaluate each part at $x = -3$ \\
$(-3)^{3} = -27$ \\
$8(-3)^{2} = 8 \times 9 = 72$ \\
$-20(-3) = 60$ \\
$-27 + 72 + 60 + k = 105 + k$ \\
$f(-3) = -5(105 + k) - 1225$ \\
Set this equal to zero: \\
$-5(105 + k) - 1225 = 0$ \\
Expand the bracket: \\
$-525 - 5k - 1225 = 0$ \\
Collect the numbers: \\
$-1750 - 5k = 0$ \\
Add $5k$ to both sides: \\
$-1750 = 5k$ \\
Divide by 5: \\
$k = -350$

@q 3
@topic Circle centre/radius, nearest point
@marks 5
@question
(a) Complete the square on the $x$ terms and the $y$ terms \\
$x^{2} + 6x = (x + 3)^{2} - 9$ \\
$y^{2} - 14y = (y - 7)^{2} - 49$ \\
$(x + 3)^{2} - 9 + (y - 7)^{2} - 49 = 138$ \\
Add 9 and 49 to both sides: \\
$(x + 3)^{2} + (y - 7)^{2} = 138 + 9 + 49$ \\
$(x + 3)^{2} + (y - 7)^{2} = 196$ \\
(i) The centre is $(-3, 7)$ \\
(ii) $r^{2} = 196$, so the radius is $r = 14$ \\
(b) Find how far the origin is from the centre: \\
$d = \sqrt{(-3)^{2} + 7^{2}}$ \\
$d = \sqrt{9 + 49}$ \\
$d = \sqrt{58}$ \\
$\sqrt{58} = 7.62$, which is less than the radius 14, so $O$ is inside the circle \\
The nearest point $P$ on the circle is on the line from the centre through $O$ \\
Going from the centre to $O$ is a distance $\sqrt{58}$, and the rest of the way to the circle is the radius minus that \\
$OP = 14 - \sqrt{58}$ \\
(That is about 6.38)

@q 4
@topic Sum to integral, ln p
@marks 3
@question
(a) As $\delta x \to 0$ the sum of the thin strips becomes an integral, with the same limits \\
$\lim_{\delta x \to 0} \sum_{x=2.4}^{9.6} \frac{5}{x} \delta x = \int_{2.4}^{9.6} \frac{5}{x} dx$ \\
(b) Integrate: $\int \frac{5}{x} dx = 5\ln x$ \\
$\int_{2.4}^{9.6} \frac{5}{x} dx = \left[ 5\ln x \right]_{2.4}^{9.6}$ \\
Upper limit minus lower limit: \\
$= 5\ln 9.6 - 5\ln 2.4$ \\
Take out the factor 5: \\
$= 5(\ln 9.6 - \ln 2.4)$ \\
Use $\ln a - \ln b = \ln \frac{a}{b}$: \\
$= 5\ln \frac{9.6}{2.4}$ \\
$= 5\ln 4$ \\
Use $n\ln a = \ln a^{n}$: \\
$= \ln 4^{5}$ \\
$= \ln 1024$ \\
So $p = 1024$

@q 5
@topic Mass model m^2 = pt + q, evaluate
@marks 6
@question
(a) The model is $m^{2} = pt + q$ \\
When $t = 3$, $m = 2.13$: \\
$m^{2} = 2.13^{2} = 4.5369$ \\
Equation 1: $3p + q = 4.5369$ \\
When $t = 7$, $m = 3.25$: \\
$m^{2} = 3.25^{2} = 10.5625$ \\
Equation 2: $7p + q = 10.5625$ \\
Subtract equation 1 from equation 2: \\
$4p = 10.5625 - 4.5369$ \\
$4p = 6.0256$ \\
Divide by 4: \\
$p = 1.5064$ \\
Put $p$ into equation 1: \\
$q = 4.5369 - 3 \times 1.5064$ \\
$q = 4.5369 - 4.5192$ \\
$q = 0.0177$ \\
To 2 significant figures $p = 1.5$ and $q = 0.018$ \\
$m^{2} = 1.5t + 0.018$ \\
(b) Eight years is $8 \times 12 = 96$ months, so $t = 96$ \\
$m^{2} = 1.5 \times 96 + 0.018$ \\
$m^{2} = 144 + 0.018$ \\
$m^{2} = 144.018$ \\
$m = \sqrt{144.018}$ \\
$m = 12.0$ kg \\
The real mass was 5 kg, and 12 kg is not close to 5 kg \\
So the model is not a good model for the cat at 8 years

@q 6
@topic Cubic curve, inequality, equation of C
@marks 6
@question
(a) $f'(x) < 0$ where the curve is going downhill \\
That is between the maximum at $x = -4$ and the minimum at $x = 0$ \\
$-4 < x < 0$ \\
(b) The curve has a maximum value of 2 and a minimum value of 0 \\
If $k > 2$, the line $y = k$ is above the maximum and meets the curve only once, on the right hand branch \\
If $k < 0$, the line is below the minimum and meets the curve only once, on the left hand branch \\
If $k = 2$ the line touches the maximum and also cuts the right hand branch, so there are 2 points \\
If $k = 0$ the line meets the curve at the minimum and at $x = -6$, so there are 2 points \\
$\{ k : k < 0 \} \text{ or } \{ k : k > 2 \}$ \\
(c) The curve is a cubic that touches the $x$ axis at the origin (its minimum is on the axis) \\
So $x = 0$ is a repeated root, and $x = -6$ is the other root \\
$f(x) = ax^{2}(x + 6)$ \\
The maximum is at $(-4, 2)$, so put $x = -4$ and $y = 2$: \\
$2 = a(-4)^{2}(-4 + 6)$ \\
$2 = a(16)(2)$ \\
$2 = 32a$ \\
Divide by 32: \\
$a = \frac{1}{16}$ \\
$y = \frac{1}{16}x^{2}(x + 6)$ \\
(Check: $f'(x) = \frac{1}{16}(3x^{2} + 12x) = \frac{3x}{16}(x + 4)$, which is zero at $x = -4$ and $x = 0$)

@q 7
@topic Proof by contradiction, inequality
@marks 5
@question
(i) Assume the opposite: $p + q$ is a multiple of 3 and one of $p$ and $q$ is a multiple of 3 \\
$p$ and $q$ are consecutive integers, so let $q = p + 1$ \\
Case 1: $p$ is the multiple of 3, so $p = 3k$ and $q = 3k + 1$ \\
$p + q = 3k + 3k + 1$ \\
$p + q = 6k + 1$ \\
$6k + 1 = 3(2k) + 1$ \\
This is one more than a multiple of 3, so it is not a multiple of 3 \\
Case 2: $q$ is the multiple of 3, so $q = 3m$ and $p = 3m - 1$ \\
$p + q = 3m - 1 + 3m$ \\
$p + q = 6m - 1$ \\
$6m - 1 = 3(2m) - 1$ \\
This is one less than a multiple of 3, so it is not a multiple of 3 \\
Both cases contradict the fact that $p + q$ is a multiple of 3 \\
So the assumption is wrong: if $p + q$ is a multiple of 3, then neither $p$ nor $q$ is a multiple of 3 \\
(ii) Start with $(x - y)^{2} < y^{2} - 3x^{2}$ \\
Expand the bracket: \\
$x^{2} - 2xy + y^{2} < y^{2} - 3x^{2}$ \\
Subtract $y^{2}$ from both sides: \\
$x^{2} - 2xy < -3x^{2}$ \\
Add $3x^{2}$ to both sides: \\
$4x^{2} - 2xy < 0$ \\
Add $2xy$ to both sides: \\
$4x^{2} < 2xy$ \\
Divide both sides by 2: \\
$2x^{2} < xy$ \\
$x < 0$, so dividing by $x$ reverses the inequality: \\
$2x > y$ \\
So $y < 2x$ as required

@q 8
@topic Train speed model, iteration
@marks 8
@question
(a) The train stops when $v = 0$ \\
$(1500 - 600T)\ln (T + 1) = 0$ \\
$\ln (T + 1) = 0$ gives $T = 0$, which is the start, not the end \\
So $1500 - 600T = 0$ \\
$600T = 1500$ \\
$T = 2.5$ hours \\
(b) Use the product rule on $v = (1500 - 600t)\ln (t + 1)$ \\
Let $u = 1500 - 600t$ and $w = \ln (t + 1)$ \\
$\frac{du}{dt} = -600$ \\
$\frac{dw}{dt} = \frac{1}{t + 1}$ \\
$\frac{dv}{dt} = \frac{du}{dt}w + u\frac{dw}{dt}$ \\
$\frac{dv}{dt} = -600\ln (t + 1) + \frac{1500 - 600t}{t + 1}$ \\
The maximum speed is when $\frac{dv}{dt} = 0$: \\
$\frac{1500 - 600t}{t + 1} = 600\ln (t + 1)$ \\
Multiply both sides by $(t + 1)$: \\
$1500 - 600t = 600(t + 1)\ln (t + 1)$ \\
Expand the bracket: \\
$1500 - 600t = 600t\ln (t + 1) + 600\ln (t + 1)$ \\
Collect the $t$ terms on one side and the rest on the other: \\
$1500 - 600\ln (t + 1) = 600t + 600t\ln (t + 1)$ \\
Factorise the right hand side: \\
$1500 - 600\ln (t + 1) = 600t(1 + \ln (t + 1))$ \\
Divide by $600(1 + \ln (t + 1))$: \\
$t = \frac{1500 - 600\ln (t + 1)}{600(1 + \ln (t + 1))}$ \\
Divide the top and bottom by 600: \\
$t = \frac{2.5 - \ln (t + 1)}{1 + \ln (t + 1)}$ \\
Multiply the top and bottom by 2: \\
$t = \frac{5 - 2\ln (t + 1)}{2 + 2\ln (t + 1)}$ \\
Write the top as $7 - (2 + 2\ln (t + 1))$: \\
$t = \frac{7 - (2 + 2\ln (t + 1))}{2 + 2\ln (t + 1)}$ \\
Split into two fractions: \\
$t = \frac{7}{2 + 2\ln (t + 1)} - \frac{2 + 2\ln (t + 1)}{2 + 2\ln (t + 1)}$ \\
$t = \frac{7}{2 + 2\ln (t + 1)} - 1$ as required \\
(c)(i) $t_{1} = 1.05$ \\
$t_{2} = \frac{7}{2 + 2\ln (1.05 + 1)} - 1$ \\
$\ln 2.05 = 0.71784$ \\
$t_{2} = \frac{7}{3.43568} - 1$ \\
$t_{2} = 1.03744$ \\
$t_{3} = \frac{7}{2 + 2\ln (1.03744 + 1)} - 1$ \\
$t_{3} = 1.04476$ \\
$t_{3} = 1.045$ to 3 decimal places \\
(ii) Keep iterating with the ANS key: \\
$t_{4} = 1.04048$ \\
$t_{5} = 1.04298$ \\
$t_{6} = 1.04152$ \\
$t_{7} = 1.04237$ \\
$t_{8} = 1.04188$ \\
The values are settling down to 1.042 \\
The time to reach maximum speed is 1.04 hours (to 2 decimal places)

@q 9
@topic Parallelogram vectors, rhombus area
@marks 6
@question
(a) Find the lengths of two adjacent sides $PQ$ and $QR$ \\
$|\text{PQ}| = \sqrt{5^{2} + 3^{2} + (-4)^{2}}$ \\
$= \sqrt{25 + 9 + 16}$ \\
$= \sqrt{50}$ \\
$\text{QR} = 0\mathbf{i} + \mathbf{j} - 7\mathbf{k}$ \\
$|\text{QR}| = \sqrt{0^{2} + 1^{2} + (-7)^{2}}$ \\
$= \sqrt{1 + 49}$ \\
$= \sqrt{50}$ \\
$|\text{PQ}| = |\text{QR}| = \sqrt{50}$ \\
A parallelogram with two adjacent sides equal is a rhombus, so $PQRS$ is a rhombus \\
(b) The area of a rhombus is $\frac{1}{2} \times$ (one diagonal) $\times$ (the other diagonal) \\
First diagonal: $\text{PR} = \text{PQ} + \text{QR}$ \\
$\text{PR} = (5\mathbf{i} + 3\mathbf{j} - 4\mathbf{k}) + (\mathbf{j} - 7\mathbf{k})$ \\
$\text{PR} = 5\mathbf{i} + 4\mathbf{j} - 11\mathbf{k}$ \\
Second diagonal: $\text{QS} = \text{QP} + \text{PS}$ \\
In a parallelogram $\text{PS} = \text{QR}$ and $\text{QP} = -\text{PQ}$ \\
$\text{QS} = -\text{PQ} + \text{QR}$ \\
$\text{QS} = (-5\mathbf{i} - 3\mathbf{j} + 4\mathbf{k}) + (\mathbf{j} - 7\mathbf{k})$ \\
$\text{QS} = -5\mathbf{i} - 2\mathbf{j} - 3\mathbf{k}$ \\
Lengths of the diagonals: \\
$|\text{PR}| = \sqrt{25 + 16 + 121}$ \\
$|\text{PR}| = \sqrt{162}$ \\
$\sqrt{162} = \sqrt{81 \times 2} = 9\sqrt{2}$ \\
$|\text{QS}| = \sqrt{25 + 4 + 9}$ \\
$|\text{QS}| = \sqrt{38}$ \\
Area $= \frac{1}{2} \times 9\sqrt{2} \times \sqrt{38}$ \\
$\sqrt{2} \times \sqrt{38} = \sqrt{76}$ \\
$\sqrt{76} = \sqrt{4 \times 19} = 2\sqrt{19}$ \\
Area $= \frac{1}{2} \times 9 \times 2\sqrt{19}$ \\
Area $= 9\sqrt{19}$ \\
(Check: the diagonals of a rhombus are perpendicular, and $\text{PR} \cdot \text{QS} = -25 - 8 + 33 = 0$)

@q 10
@topic Exponential models, lions and wildebeest
@marks 8
@question
(a) At the start $t = 0$: \\
$L = 1 + 2e^{0}$ \\
$e^{0} = 1$ \\
$L = 3$ \\
$L$ is in hundreds, so there were 300 lions \\
(b) Differentiate $L = 1 + 2e^{0.03t}$ with respect to $t$: \\
$\frac{dL}{dt} = 2 \times 0.03e^{0.03t}$ \\
$\frac{dL}{dt} = 0.06e^{0.03t}$ \\
At $t = 5$: \\
$\frac{dL}{dt} = 0.06e^{0.15}$ \\
$e^{0.15} = 1.16183$ \\
$\frac{dL}{dt} = 0.06 \times 1.16183$ \\
$\frac{dL}{dt} = 0.0697$ hundred lions per year \\
Multiply by 100 to get lions per year: \\
$0.0697 \times 100 = 6.97$ \\
So the number of lions is increasing at about 7 per year \\
(c) The number of lions is $100L$ and the number of wildebeest is $1000W$ \\
10 times as many wildebeest as lions: \\
$1000W = 10 \times 100L$ \\
$1000W = 1000L$ \\
$W = L$ \\
$10 + 4e^{-0.03T} = 1 + 2e^{0.03T}$ \\
Let $y = e^{0.03T}$, so $e^{-0.03T} = \frac{1}{y}$ \\
$10 + \frac{4}{y} = 1 + 2y$ \\
Multiply every term by $y$: \\
$10y + 4 = y + 2y^{2}$ \\
Subtract $10y$ and 4 from both sides: \\
$0 = 2y^{2} - 9y - 4$ \\
Use the quadratic formula with $a = 2$, $b = -9$, $c = -4$: \\
$y = \frac{9 \pm \sqrt{81 + 32}}{4}$ \\
$y = \frac{9 \pm \sqrt{113}}{4}$ \\
$y = 4.9075$ or $y = -0.4075$ \\
$y = e^{0.03T}$ is positive, so reject $-0.4075$ \\
$e^{0.03T} = 4.9075$ \\
Take natural logs of both sides: \\
$0.03T = \ln 4.9075$ \\
$0.03T = 1.5909$ \\
Divide by 0.03: \\
$T = 53.03$ \\
$T = 53.0$ to 1 decimal place

@q 11
@topic Cubic and quadratic intersect, factorise
@marks 7
@question
(a) Put $x = -\frac{1}{3}$ into $y = 3x^{3} + 60$: \\
$x^{3} = \left( -\frac{1}{3} \right)^{3} = -\frac{1}{27}$ \\
$3x^{3} = -\frac{3}{27} = -\frac{1}{9}$ \\
$y = 60 - \frac{1}{9}$ \\
$y = \frac{540}{9} - \frac{1}{9}$ \\
$y = \frac{539}{9}$ \\
Put $x = -\frac{1}{3}$ into $y = 29x^{2} + 100x + 90$: \\
$29x^{2} = 29 \times \frac{1}{9} = \frac{29}{9}$ \\
$100x = -\frac{100}{3} = -\frac{300}{9}$ \\
$90 = \frac{810}{9}$ \\
$y = \frac{29}{9} - \frac{300}{9} + \frac{810}{9}$ \\
$y = \frac{539}{9}$ \\
Both curves give $y = \frac{539}{9}$ at $x = -\frac{1}{3}$ \\
So they intersect at $x = -\frac{1}{3}$ \\
(b) At an intersection the $y$ values are equal: \\
$3x^{3} + 60 = 29x^{2} + 100x + 90$ \\
Subtract $29x^{2}$, $100x$ and 90 from both sides: \\
$3x^{3} - 29x^{2} - 100x - 30 = 0$ \\
$x = -\frac{1}{3}$ is a root, so $(3x + 1)$ is a factor \\
Divide to find the other factor, $3x^{3} - 29x^{2} - 100x - 30 = (3x + 1)(x^{2} + bx - 30)$ \\
Expand: $(3x + 1)(x^{2} + bx - 30) = 3x^{3} + (3b + 1)x^{2} + (b - 90)x - 30$ \\
Compare the $x^{2}$ terms: $3b + 1 = -29$ \\
$3b = -30$ \\
$b = -10$ \\
(Check the $x$ terms: $b - 90 = -100$, which matches) \\
$(3x + 1)(x^{2} - 10x - 30) = 0$ \\
The other intersections come from $x^{2} - 10x - 30 = 0$ \\
Complete the square: $x^{2} - 10x = (x - 5)^{2} - 25$ \\
$(x - 5)^{2} - 25 - 30 = 0$ \\
$(x - 5)^{2} = 55$ \\
Square root both sides: \\
$x - 5 = \pm \sqrt{55}$ \\
$x = 5 \pm \sqrt{55}$ \\
The curves are only drawn for $x < 0$ \\
$5 + \sqrt{55} = 12.4$ is positive, so reject it \\
$x = 5 - \sqrt{55}$ \\
($5 - \sqrt{55} = -2.42$)

@q 12
@topic Integration by parts, x^2 ln x
@marks 5
@question
Use integration by parts with $u = \ln x$ and $\frac{dv}{dx} = x^{2}$ \\
$\frac{du}{dx} = \frac{1}{x}$ \\
$v = \frac{x^{3}}{3}$ \\
$\int x^{2}\ln x \, dx = \frac{x^{3}}{3}\ln x - \int \frac{x^{3}}{3} \times \frac{1}{x} dx$ \\
Cancel an $x$ in the integral: \\
$= \frac{x^{3}}{3}\ln x - \int \frac{x^{2}}{3} dx$ \\
$= \frac{x^{3}}{3}\ln x - \frac{x^{3}}{9}$ \\
Now apply the limits $e^{2}$ and $e$: \\
Upper limit $x = e^{2}$: \\
$x^{3} = e^{6}$ and $\ln e^{2} = 2$ \\
$\frac{e^{6}}{3} \times 2 - \frac{e^{6}}{9}$ \\
$= \frac{2e^{6}}{3} - \frac{e^{6}}{9}$ \\
$= \frac{6e^{6}}{9} - \frac{e^{6}}{9}$ \\
$= \frac{5e^{6}}{9}$ \\
Lower limit $x = e$: \\
$x^{3} = e^{3}$ and $\ln e = 1$ \\
$\frac{e^{3}}{3} \times 1 - \frac{e^{3}}{9}$ \\
$= \frac{3e^{3}}{9} - \frac{e^{3}}{9}$ \\
$= \frac{2e^{3}}{9}$ \\
Subtract the lower limit from the upper limit: \\
$\frac{5e^{6}}{9} - \frac{2e^{3}}{9}$ \\
Take out the factor $\frac{e^{3}}{9}$: \\
$= \frac{e^{3}}{9}\left( 5e^{3} - 2 \right)$ \\
$= \frac{1}{9}e^{3}\left( 5e^{3} - 2 \right)$ \\
So $A = 5$ and $B = -2$

@q 13
@topic Geometric proof, arithmetic savings
@marks 7
@question
(i) Write out the sum: \\
$S_{n} = a + ar + ar^{2} + \ldots + ar^{n-1}$ \\
Multiply every term by $r$: \\
$rS_{n} = ar + ar^{2} + ar^{3} + \ldots + ar^{n}$ \\
Subtract the second line from the first. All the middle terms cancel: \\
$S_{n} - rS_{n} = a - ar^{n}$ \\
Factorise both sides: \\
$(1 - r)S_{n} = a(1 - r^{n})$ \\
Divide by $(1 - r)$ (for $r \ne 1$): \\
$S_{n} = \frac{a(1 - r^{n})}{1 - r}$ as required \\
(ii)(a) The amounts saved are 6.60, 6.00, 5.40, ... \\
They go down by 0.60 each week, so this is arithmetic with $a = 6.6$ and $d = -0.6$ \\
Sum of an arithmetic series: $S_{n} = \frac{n}{2}\{ 2a + (n - 1)d \}$ \\
$36 = \frac{n}{2}\{ 2(6.6) + (n - 1)(-0.6) \}$ \\
$36 = \frac{n}{2}\{ 13.2 - 0.6(n - 1) \}$ \\
Multiply both sides by 2: \\
$72 = n\{ 13.2 - 0.6(n - 1) \}$ \\
Expand the inner bracket: $-0.6(n - 1) = -0.6n + 0.6$ \\
$72 = n(13.2 - 0.6n + 0.6)$ \\
$72 = n(13.8 - 0.6n)$ \\
Expand: \\
$72 = 13.8n - 0.6n^{2}$ \\
Add $0.6n^{2}$ and subtract $13.8n$ from both sides: \\
$0.6n^{2} - 13.8n + 72 = 0$ \\
Divide every term by 0.6: \\
$n^{2} - 23n + 120 = 0$ as required \\
(b) Factorise: find two numbers that multiply to 120 and add to $-23$ \\
$-8$ and $-15$ work \\
$(n - 8)(n - 15) = 0$ \\
$n = 8$ or $n = 15$ \\
(c) The amount saved in week $n$ is $7.2 - 0.6n$ \\
Week 12: $7.2 - 0.6 \times 12 = 0$ \\
Week 13: $7.2 - 0.6 \times 13 = -0.6$ \\
After week 12 the amounts would be negative, which makes no sense for saving \\
So $n = 15$ is not sensible \\
It takes 8 weeks

@q 14
@topic Compound angle, tan x, solve equation
@marks 8
@question
(a) Expand both sides using the compound angle formulae \\
$\sin (x + 30) = \sin x\cos 30 + \cos x\sin 30$ \\
$\cos (x - 30) = \cos x\cos 30 + \sin x\sin 30$ \\
$\cos 30 = \frac{\sqrt{3}}{2}$ and $\sin 30 = \frac{1}{2}$ \\
$5\sin (x + 30) = 5\left( \frac{\sqrt{3}}{2}\sin x + \frac{1}{2}\cos x \right)$ \\
$= \frac{5\sqrt{3}}{2}\sin x + \frac{5}{2}\cos x$ \\
$3\cos (x - 30) = 3\left( \frac{\sqrt{3}}{2}\cos x + \frac{1}{2}\sin x \right)$ \\
$= \frac{3\sqrt{3}}{2}\cos x + \frac{3}{2}\sin x$ \\
Set them equal: \\
$\frac{5\sqrt{3}}{2}\sin x + \frac{5}{2}\cos x = \frac{3\sqrt{3}}{2}\cos x + \frac{3}{2}\sin x$ \\
Multiply every term by 2: \\
$5\sqrt{3}\sin x + 5\cos x = 3\sqrt{3}\cos x + 3\sin x$ \\
Subtract $3\sin x$ and $5\cos x$ from both sides: \\
$5\sqrt{3}\sin x - 3\sin x = 3\sqrt{3}\cos x - 5\cos x$ \\
Factorise each side: \\
$(5\sqrt{3} - 3)\sin x = (3\sqrt{3} - 5)\cos x$ \\
Divide both sides by $\cos x$ and use $\tan x = \frac{\sin x}{\cos x}$: \\
$(5\sqrt{3} - 3)\tan x = 3\sqrt{3} - 5$ \\
Divide by $(5\sqrt{3} - 3)$: \\
$\tan x = \frac{3\sqrt{3} - 5}{5\sqrt{3} - 3}$ as required \\
(b) Let $x = 2\theta + 30$ \\
Then $x + 30 = 2\theta + 60$ and $x - 30 = 2\theta$ \\
So $5\sin (2\theta + 60) = 3\cos 2\theta$ is the same equation as $5\sin (x + 30) = 3\cos (x - 30)$ \\
From part (a): $\tan (2\theta + 30) = \frac{3\sqrt{3} - 5}{5\sqrt{3} - 3}$ \\
$\frac{3\sqrt{3} - 5}{5\sqrt{3} - 3} = 0.034654$ \\
$2\theta + 30 = \tan^{-1}(0.034654)$ \\
$2\theta + 30 = 1.985 \text{ degrees}$ \\
Tangent repeats every 180 degrees, so $2\theta + 30 = 1.985 + 180n$ \\
For $0 \leq \theta < 180$ we need $30 \leq 2\theta + 30 < 390$ \\
$1.985$ is below 30, so reject it \\
$2\theta + 30 = 181.985$ or $2\theta + 30 = 361.985$ \\
Subtract 30: \\
$2\theta = 151.985$ or $2\theta = 331.985$ \\
Divide by 2: \\
$\theta = 75.99$ or $\theta = 165.99$ \\
$\theta = 76$ or $166$ degrees to the nearest integer

@q 15
@topic Cheesecake slice, minimise surface area
@marks 10
@question
(a) Area of the sector $ABC$: $\frac{1}{2}r^{2}\theta = \frac{1}{2}r^{2}(0.5)$ \\
Area of $ABC = \frac{r^{2}}{4}$ \\
Volume $=$ area of $ABC$ $\times$ $h$ \\
$\frac{r^{2}}{4}h = 125$ \\
Multiply both sides by 4: \\
$r^{2}h = 500$ \\
Divide by $r^{2}$: \\
$h = \frac{500}{r^{2}}$ \\
Surface area, face by face: \\
Two sector faces $ABC$ and $DEF$: $2 \times \frac{r^{2}}{4} = \frac{r^{2}}{2}$ \\
Rectangle $ABED$: $r \times h = rh$ \\
Rectangle $ACFD$: $r \times h = rh$ \\
Curved face $BCFE$: arc length $BC = r\theta = 0.5r$, so the area is $0.5r \times h = 0.5rh$ \\
$S = \frac{r^{2}}{2} + rh + rh + 0.5rh$ \\
$S = \frac{r^{2}}{2} + 2.5rh$ \\
Substitute $h = \frac{500}{r^{2}}$: \\
$2.5rh = 2.5r \times \frac{500}{r^{2}}$ \\
$= \frac{1250r}{r^{2}}$ \\
$= \frac{1250}{r}$ \\
$S = \frac{r^{2}}{2} + \frac{1250}{r}$ as required \\
(b) Write $S = \frac{1}{2}r^{2} + 1250r^{-1}$ \\
Differentiate: \\
$\frac{dS}{dr} = r - 1250r^{-2}$ \\
$\frac{dS}{dr} = r - \frac{1250}{r^{2}}$ \\
At a stationary point $\frac{dS}{dr} = 0$: \\
$r - \frac{1250}{r^{2}} = 0$ \\
Add $\frac{1250}{r^{2}}$ to both sides: \\
$r = \frac{1250}{r^{2}}$ \\
Multiply by $r^{2}$: \\
$r^{3} = 1250$ \\
Take the cube root: \\
$r = \sqrt[3]{1250}$ \\
$r = 10.77$ \\
$r = 10.8$ to 3 significant figures \\
(c) Differentiate again: \\
$\frac{d^{2}S}{dr^{2}} = 1 + 2500r^{-3}$ \\
$\frac{d^{2}S}{dr^{2}} = 1 + \frac{2500}{r^{3}}$ \\
At the stationary point $r^{3} = 1250$: \\
$\frac{d^{2}S}{dr^{2}} = 1 + \frac{2500}{1250}$ \\
$= 1 + 2$ \\
$= 3$ \\
$3 > 0$, so the stationary point is a minimum \\
So $r = 10.8$ gives the minimum surface area

@q 16
@topic Parametric area, double angle integral
@marks 9
@question
(a) Area under a curve: $R = \int y \, dx$ \\
$x = \cos^{2} t$ \\
$\frac{dx}{dt} = 2\cos t \times (-\sin t)$ \\
$\frac{dx}{dt} = -2\sin t\cos t$ \\
Use $\sin 2t = 2\sin t\cos t$: \\
$\frac{dx}{dt} = -\sin 2t$ \\
$y\frac{dx}{dt} = -(3\cos 2t + 2\cos t + 3)\sin 2t$ \\
Expand the bracket, one term at a time: \\
$-3\cos 2t\sin 2t$ \\
$-2\cos t\sin 2t$ \\
$-3\sin 2t$ \\
Use $\sin 2t = 2\sin t\cos t$ in the second term: \\
$-2\cos t \times 2\sin t\cos t = -4\cos^{2} t\sin t$ \\
Use $\sin 4t = 2\sin 2t\cos 2t$ in the first term, so $\sin 2t\cos 2t = \frac{1}{2}\sin 4t$: \\
$-3\cos 2t\sin 2t = -\frac{3}{2}\sin 4t$ \\
$y\frac{dx}{dt} = -\frac{3}{2}\sin 4t - 4\cos^{2} t\sin t - 3\sin 2t$ \\
Now the limits. $x = 0$ means $\cos^{2} t = 0$, so $t = \frac{\pi}{2}$ \\
$x = \frac{1}{4}$ means $\cos^{2} t = \frac{1}{4}$ \\
In the range $\frac{\pi}{4} \leq t \leq \frac{\pi}{2}$, $\cos t$ is positive, so $\cos t = \frac{1}{2}$ \\
$t = \frac{\pi}{3}$ \\
$R = \int_{\frac{\pi}{2}}^{a}\left( -\frac{3}{2}\sin 4t - 4\cos^{2} t\sin t - 3\sin 2t \right) dt$ with $a = \frac{\pi}{3}$ \\
(b) Integrate each term: \\
$\int -\frac{3}{2}\sin 4t \, dt = -\frac{3}{2} \times \left( -\frac{\cos 4t}{4} \right) = \frac{3}{8}\cos 4t$ \\
$\int -4\cos^{2} t\sin t \, dt = \frac{4}{3}\cos^{3} t$ \\
(Check: differentiating $\frac{4}{3}\cos^{3} t$ gives $\frac{4}{3} \times 3\cos^{2} t \times (-\sin t) = -4\cos^{2} t\sin t$) \\
$\int -3\sin 2t \, dt = -3 \times \left( -\frac{\cos 2t}{2} \right) = \frac{3}{2}\cos 2t$ \\
$F(t) = \frac{3}{8}\cos 4t + \frac{4}{3}\cos^{3} t + \frac{3}{2}\cos 2t$ \\
Upper limit $t = \frac{\pi}{3}$: \\
$\cos \frac{4\pi}{3} = -\frac{1}{2}$, so $\frac{3}{8} \times \left( -\frac{1}{2} \right) = -\frac{3}{16}$ \\
$\cos \frac{\pi}{3} = \frac{1}{2}$, so $\frac{4}{3} \times \frac{1}{8} = \frac{1}{6}$ \\
$\cos \frac{2\pi}{3} = -\frac{1}{2}$, so $\frac{3}{2} \times \left( -\frac{1}{2} \right) = -\frac{3}{4}$ \\
$F\left( \frac{\pi}{3} \right) = -\frac{3}{16} + \frac{1}{6} - \frac{3}{4}$ \\
Write over the denominator 48: $-\frac{9}{48} + \frac{8}{48} - \frac{36}{48}$ \\
$F\left( \frac{\pi}{3} \right) = -\frac{37}{48}$ \\
Lower limit $t = \frac{\pi}{2}$: \\
$\cos 2\pi = 1$, so $\frac{3}{8} \times 1 = \frac{3}{8}$ \\
$\cos \frac{\pi}{2} = 0$, so the second term is 0 \\
$\cos \pi = -1$, so $\frac{3}{2} \times (-1) = -\frac{3}{2}$ \\
$F\left( \frac{\pi}{2} \right) = \frac{3}{8} - \frac{3}{2}$ \\
$F\left( \frac{\pi}{2} \right) = -\frac{9}{8}$ \\
$F\left( \frac{\pi}{2} \right) = -\frac{54}{48}$ \\
Upper limit minus lower limit, in the order of the integral: \\
Area $= F\left( \frac{\pi}{3} \right) - F\left( \frac{\pi}{2} \right)$ \\
$= -\frac{37}{48} - \left( -\frac{54}{48} \right)$ \\
$= -\frac{37}{48} + \frac{54}{48}$ \\
$= \frac{17}{48}$
