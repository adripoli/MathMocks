@paper P1 Shadow October 2020

@q 1
@topic Binomial expansion, approximate root 12
@marks 5
@question
(a) Binomial expansion: $(1 + y)^{n} = 1 + ny + \frac{n(n - 1)}{2!}y^{2} + \frac{n(n - 1)(n - 2)}{3!}y^{3} + \ldots$ \\
Here $n = \frac{1}{2}$ and $y = 12x$ \\
Second term: $ny = \frac{1}{2} \times 12x$ \\
$= 6x$ \\
Third term: $\frac{n(n - 1)}{2!} = \frac{\frac{1}{2} \times \left( -\frac{1}{2} \right)}{2}$ \\
$= \frac{-\frac{1}{4}}{2}$ \\
$= -\frac{1}{8}$ \\
$y^{2} = (12x)^{2} = 144x^{2}$ \\
$-\frac{1}{8} \times 144x^{2} = -18x^{2}$ \\
Fourth term: $\frac{n(n - 1)(n - 2)}{3!} = \frac{\frac{1}{2} \times \left( -\frac{1}{2} \right) \times \left( -\frac{3}{2} \right)}{6}$ \\
$= \frac{\frac{3}{8}}{6}$ \\
$= \frac{1}{16}$ \\
$y^{3} = (12x)^{3} = 1728x^{3}$ \\
$\frac{1}{16} \times 1728x^{3} = 108x^{3}$ \\
$(1 + 12x)^{\frac{1}{2}} = 1 + 6x - 18x^{2} + 108x^{3} + \ldots$ \\
(b) Substitute $x = \frac{1}{36}$ into $(1 + 12x)^{\frac{1}{2}}$: \\
$1 + 12 \times \frac{1}{36} = 1 + \frac{1}{3}$ \\
$= \frac{4}{3}$ \\
$\left( \frac{4}{3} \right)^{\frac{1}{2}} = \frac{\sqrt{4}}{\sqrt{3}}$ \\
$= \frac{2}{\sqrt{3}}$ \\
Multiply the top and bottom by $\sqrt{3}$: \\
$= \frac{2\sqrt{3}}{3}$ \\
Since $\sqrt{12} = 2\sqrt{3}$: \\
$(1 + 12x)^{\frac{1}{2}} = \frac{\sqrt{12}}{3}$ when $x = \frac{1}{36}$ \\
So put $x = \frac{1}{36}$ into $1 + 6x - 18x^{2} + 108x^{3}$ to get an approximation for $\frac{\sqrt{12}}{3}$ \\
Then multiply the result by 3 to get an approximation for $\sqrt{12}$ \\
(The expansion is valid as $|12x| = \frac{1}{3} < 1$)

@q 2
@topic Solve exponential equation using logs
@marks 3
@question
Take logs of both sides of $5^{4q - 2} = 7^{160}$: \\
$\log 5^{4q - 2} = \log 7^{160}$ \\
Use $\log a^{n} = n\log a$: \\
$(4q - 2)\log 5 = 160\log 7$ \\
Divide both sides by $\log 5$: \\
$4q - 2 = \frac{160\log 7}{\log 5}$ \\
$\frac{\log 7}{\log 5} = 1.20906$ \\
$4q - 2 = 160 \times 1.20906$ \\
$4q - 2 = 193.450$ \\
Add 2 to both sides: \\
$4q = 195.450$ \\
Divide by 4: \\
$q = 48.862$ \\
$q = 48.9$ to 1 decimal place

@q 3
@topic Position vectors, trapezium
@marks 4
@question
(a) $\text{PQ} = \text{OQ} - \text{OP}$ \\
$\text{PQ} = (5\mathbf{i} - 3\mathbf{j} - 2\mathbf{k}) - (3\mathbf{i} + 2\mathbf{j} - 5\mathbf{k})$ \\
$\mathbf{i}$ terms: $5 - 3 = 2$ \\
$\mathbf{j}$ terms: $-3 - 2 = -5$ \\
$\mathbf{k}$ terms: $-2 - (-5) = 3$ \\
$\text{PQ} = 2\mathbf{i} - 5\mathbf{j} + 3\mathbf{k}$ \\
(b) $\text{OR} = 4\mathbf{i} - 10\mathbf{j} + 6\mathbf{k}$ \\
Take out a factor of 2: \\
$\text{OR} = 2(2\mathbf{i} - 5\mathbf{j} + 3\mathbf{k})$ \\
$\text{OR} = 2\text{PQ}$ \\
So $OR$ is parallel to $PQ$, and twice as long \\
A trapezium has exactly one pair of parallel sides \\
$OP$ and $RQ$ are not parallel: $\text{OP} = 3\mathbf{i} + 2\mathbf{j} - 5\mathbf{k}$ and $\text{RQ} = \mathbf{i} + 7\mathbf{j} - 8\mathbf{k}$, which are not multiples of each other \\
So $OPQR$ has one pair of parallel sides, $OR$ and $PQ$, which are different lengths \\
Therefore $OPQR$ is a trapezium

@q 4
@topic Inverse and composite function
@marks 5
@question
(a) $f^{-1}(9)$ is the value of $x$ for which $f(x) = 9$ \\
$\frac{5x - 9}{x - 3} = 9$ \\
Multiply both sides by $(x - 3)$: \\
$5x - 9 = 9(x - 3)$ \\
Expand the bracket: \\
$5x - 9 = 9x - 27$ \\
Subtract $5x$ from both sides: \\
$-9 = 4x - 27$ \\
Add 27 to both sides: \\
$18 = 4x$ \\
Divide by 4: \\
$x = \frac{9}{2}$ \\
$f^{-1}(9) = \frac{9}{2}$ \\
(Check: $f\left( \frac{9}{2} \right) = \frac{22.5 - 9}{4.5 - 3} = \frac{13.5}{1.5} = 9$) \\
(b) $ff(x) = f\left( \frac{5x - 9}{x - 3} \right)$ \\
Replace $x$ in $f(x)$ by $\frac{5x - 9}{x - 3}$: \\
$ff(x) = \frac{5\left( \frac{5x - 9}{x - 3} \right) - 9}{\left( \frac{5x - 9}{x - 3} \right) - 3}$ \\
Multiply the top and bottom by $(x - 3)$ to clear the small fractions: \\
$ff(x) = \frac{5(5x - 9) - 9(x - 3)}{(5x - 9) - 3(x - 3)}$ \\
Top: $5(5x - 9) = 25x - 45$ \\
Top: $-9(x - 3) = -9x + 27$ \\
Top: $25x - 45 - 9x + 27 = 16x - 18$ \\
Bottom: $-3(x - 3) = -3x + 9$ \\
Bottom: $5x - 9 - 3x + 9 = 2x$ \\
$ff(x) = \frac{16x - 18}{2x}$ \\
Divide each term on the top by $2x$: \\
$ff(x) = \frac{16x}{2x} - \frac{18}{2x}$ \\
$ff(x) = 8 - \frac{9}{x}$ \\
So $a = 8$ and $b = -9$

@q 5
@topic Arithmetic and geometric sequences, gears
@marks 6
@question
(a) Arithmetic sequence: first term $a = 10$, and the 10th term is 73 \\
$n$th term $= a + (n - 1)d$ \\
10th term: $10 + 9d = 73$ \\
Subtract 10 from both sides: \\
$9d = 63$ \\
Divide by 9: \\
$d = 7$ \\
5th term: $10 + 4d$ \\
$= 10 + 4 \times 7$ \\
$= 10 + 28$ \\
$= 38$ \\
The fastest speed in 5th gear is 38 km h$^{-1}$ \\
(b) Geometric sequence: first term $a = 10$, and the 10th term is 73 \\
$n$th term $= ar^{n - 1}$ \\
10th term: $10r^{9} = 73$ \\
Divide by 10: \\
$r^{9} = 7.3$ \\
Take the 9th root: \\
$r = 7.3^{\frac{1}{9}}$ \\
$r = 1.24717$ \\
8th term: $10r^{7}$ \\
$r^{7} = 1.24717^{7}$ \\
$r^{7} = 4.6933$ \\
$10r^{7} = 46.933$ \\
The fastest speed in 8th gear is 46.9 km h$^{-1}$ (3 significant figures)

@q 6
@topic R sin(x + a) form, room temperature
@marks 7
@question
(a) Write $R\sin (x + \alpha)$ out using the addition formula: \\
$R\sin (x + \alpha) = R\sin x \cos \alpha + R\cos x \sin \alpha$ \\
Compare with $2\sin x + 3\cos x$ \\
Coefficient of $\sin x$: $R\cos \alpha = 2$ \\
Coefficient of $\cos x$: $R\sin \alpha = 3$ \\
Square both equations and add them: \\
$R^{2}\cos^{2} \alpha + R^{2}\sin^{2} \alpha = 2^{2} + 3^{2}$ \\
$R^{2}(\cos^{2} \alpha + \sin^{2} \alpha) = 13$ \\
$\cos^{2} \alpha + \sin^{2} \alpha = 1$, so $R^{2} = 13$ \\
$R = \sqrt{13}$ \\
Divide $R\sin \alpha = 3$ by $R\cos \alpha = 2$: \\
$\tan \alpha = \frac{3}{2}$ \\
$\alpha = \tan^{-1}(1.5)$ \\
$\alpha = 0.9828$ radians to 4 decimal places \\
$2\sin x + 3\cos x = \sqrt{13}\sin (x + 0.9828)$ \\
(b) In the model let $u = \frac{\pi t}{6} - 2$ \\
$\theta = 13 + 2\sin u + 3\cos u$ \\
Use part (a): $2\sin u + 3\cos u = \sqrt{13}\sin (u + 0.9828)$ \\
$\theta = 13 + \sqrt{13}\sin \left( \frac{\pi t}{6} - 2 + 0.9828 \right)$ \\
The largest value of sine is 1 \\
Maximum temperature $= 13 + \sqrt{13}$ \\
$= 16.61$ degrees C \\
(c) The maximum happens when the sine is 1: \\
$\sin \left( \frac{\pi t}{6} - 2 + 0.9828 \right) = 1$ \\
$\frac{\pi t}{6} - 2 + 0.9828 = \frac{\pi}{2}$ \\
Add 2 and subtract 0.9828 on both sides: \\
$\frac{\pi t}{6} = \frac{\pi}{2} + 2 - 0.98279$ \\
$\frac{\pi t}{6} = 1.57080 + 1.01721$ \\
$\frac{\pi t}{6} = 2.58801$ \\
Multiply by $\frac{6}{\pi}$: \\
$t = 2.58801 \times \frac{6}{\pi}$ \\
$t = 4.9427$ hours after midnight \\
Convert the decimal part to minutes: $0.9427 \times 60 = 56.6$ \\
That is 4 hours 57 minutes after midnight, so the time is 04:57 \\
The sine has a period of 12 hours (as $\frac{\pi}{6} \times 12 = 2\pi$), so the maximum also happens at $t = 4.9427 + 12 = 16.9427$ \\
That is 16:57, which is also in the range $0 \leq t < 24$ \\
The maximum temperature occurs at 04:57 and again at 16:57

@q 7
@topic Quadratic and line, inequalities for R
@marks 5
@question
Find the line $l$ first. It passes through $(-3, 7)$ and $(0, 16)$ \\
Gradient: $\frac{16 - 7}{0 - (-3)} = \frac{9}{3}$ \\
$m = 3$ \\
The line crosses the $y$ axis at 16, so $c = 16$ \\
$l$: $y = 3x + 16$ \\
(Check with $(-3, 7)$: $3(-3) + 16 = 7$) \\
Now find the curve $C$. It is a quadratic with minimum point $(-3, 7)$ \\
So $y = a(x + 3)^{2} + 7$ \\
$C$ passes through $(0, 16)$: \\
$16 = a(0 + 3)^{2} + 7$ \\
$16 = 9a + 7$ \\
Subtract 7 from both sides: \\
$9 = 9a$ \\
$a = 1$ \\
$C$: $y = (x + 3)^{2} + 7$ \\
Expand to check: $(x + 3)^{2} + 7 = x^{2} + 6x + 9 + 7$ \\
$C$: $y = x^{2} + 6x + 16$ \\
Region $R$ is above the curve $C$ and below the line $l$ \\
Above the curve: $y > (x + 3)^{2} + 7$ \\
Below the line: $y < 3x + 16$ \\
$R$ is defined by $(x + 3)^{2} + 7 < y < 3x + 16$ \\
(Check: the line meets the curve where $x^{2} + 3x = 0$, that is $x = -3$ and $x = 0$, so $R$ lies between $x = -3$ and $x = 0$ as in the figure)

@q 8
@topic Rate proportional to n, exponential
@marks 2
@question
The rate of increase of $n$ is $\frac{dn}{dm}$ \\
Proportional to $n$ means $\frac{dn}{dm} = kn$ where $k$ is a positive constant \\
Separate the variables: \\
$\frac{1}{n} dn = k \, dm$ \\
Integrate both sides: \\
$\ln n = km + c$ \\
Take exponentials of both sides: \\
$n = e^{km + c}$ \\
Split the power: \\
$n = e^{c} \times e^{km}$ \\
Let $A = e^{c}$, a constant: \\
$n = Ae^{km}$

@q 9
@topic Product rule, stationary points, range
@marks 9
@question
(a) Use the product rule with $u = x^{2} - 6$ and $v = e^{-2x}$ \\
$\frac{du}{dx} = 2x$ \\
$\frac{dv}{dx} = -2e^{-2x}$ \\
$f'(x) = 9\left[ \frac{du}{dx}v + u\frac{dv}{dx} \right]$ \\
$f'(x) = 9\left[ 2xe^{-2x} + (x^{2} - 6)(-2e^{-2x}) \right]$ \\
Factorise out $e^{-2x}$: \\
$f'(x) = 9e^{-2x}\left[ 2x - 2(x^{2} - 6) \right]$ \\
Expand the bracket: \\
$f'(x) = 9e^{-2x}(2x - 2x^{2} + 12)$ \\
Factorise out 2: \\
$f'(x) = 18e^{-2x}(x - x^{2} + 6)$ \\
$f'(x) = 18(6 + x - x^{2})e^{-2x}$ as required \\
(b) Stationary points are where $f'(x) = 0$: \\
$18(6 + x - x^{2})e^{-2x} = 0$ \\
$e^{-2x}$ is never zero, so $6 + x - x^{2} = 0$ \\
Multiply by $-1$: \\
$x^{2} - x - 6 = 0$ \\
Factorise: \\
$(x - 3)(x + 2) = 0$ \\
$x = 3$ or $x = -2$ \\
Find the $y$ value for $x = 3$: \\
$f(3) = 9(3^{2} - 6)e^{-6}$ \\
$= 9(9 - 6)e^{-6}$ \\
$= 27e^{-6}$ \\
Find the $y$ value for $x = -2$: \\
$f(-2) = 9((-2)^{2} - 6)e^{4}$ \\
$= 9(4 - 6)e^{4}$ \\
$= -18e^{4}$ \\
The stationary points are $(-2, -18e^{4})$ and $(3, 27e^{-6})$ \\
(c)(i) $g(x) = 2f(x)$ for all real $x$ \\
The lowest point of $C$ is the minimum at $x = -2$, where $f = -18e^{4}$ \\
As $x \to -\infty$, $f(x) \to \infty$ (the curve goes up on the left) \\
So the range of $f$ is $f(x) \geq -18e^{4}$ \\
Multiply by 2: \\
Range of g: $g(x) \geq -36e^{4}$ \\
(ii) Now $x \geq 0$ only \\
$f(0) = 9(0 - 6)e^{0}$ \\
$f(0) = -54$ \\
$f'(x) > 0$ for $-2 < x < 3$, so $f$ rises from $-54$ at $x = 0$ up to the maximum at $x = 3$ \\
Maximum: $f(3) = 27e^{-6}$ \\
For $x > 3$, $f$ falls but stays positive and tends to 0 \\
So for $x \geq 0$ the range of $f$ is $-54 \leq f(x) \leq 27e^{-6}$ \\
$h(x) = 2f(x) - 2$ \\
Lowest value: $2(-54) - 2 = -110$ \\
Highest value: $2(27e^{-6}) - 2 = 54e^{-6} - 2$ \\
Range of h: $-110 \leq h(x) \leq 54e^{-6} - 2$

@q 10
@topic Substitution, partial fractions, ln p
@marks 10
@question
(a) $x = u^{2} - 1$ \\
Differentiate: $\frac{dx}{du} = 2u$ \\
$dx = 2u \, du$ \\
Also $x + 1 = u^{2}$ \\
So $\sqrt{x + 1} = u$ \\
Limits: when $x = 8$, $u^{2} = 9$, so $u = 3$ \\
Limits: when $x = 15$, $u^{2} = 16$, so $u = 4$ \\
$\int_{8}^{15} \frac{5 \, dx}{(x + 1)\left( 5 + 2\sqrt{x + 1} \right)} = \int_{3}^{4} \frac{5 \times 2u \, du}{u^{2}(5 + 2u)}$ \\
$= \int_{3}^{4} \frac{10u \, du}{u^{2}(5 + 2u)}$ \\
Cancel one factor of $u$: \\
$= \int_{3}^{4} \frac{10 \, du}{u(5 + 2u)}$ \\
So $a = 3$ and $b = 4$ \\
(b) Write the fraction in partial fractions: \\
$\frac{10}{u(5 + 2u)} = \frac{A}{u} + \frac{B}{5 + 2u}$ \\
Multiply both sides by $u(5 + 2u)$: \\
$10 = A(5 + 2u) + Bu$ \\
Put $u = 0$: $10 = 5A$ \\
$A = 2$ \\
Put $u = -\frac{5}{2}$: $10 = B\left( -\frac{5}{2} \right)$ \\
$B = -4$ \\
$\frac{10}{u(5 + 2u)} = \frac{2}{u} - \frac{4}{5 + 2u}$ \\
Integrate each term: \\
$\int \frac{2}{u} du = 2\ln u$ \\
$\int \frac{4}{5 + 2u} du = 4 \times \frac{1}{2}\ln (5 + 2u)$ \\
$= 2\ln (5 + 2u)$ \\
$\int \frac{10 \, du}{u(5 + 2u)} = 2\ln u - 2\ln (5 + 2u)$ \\
Apply the limits $u = 4$ and $u = 3$: \\
Upper limit: $2\ln 4 - 2\ln (5 + 8) = 2\ln 4 - 2\ln 13$ \\
Lower limit: $2\ln 3 - 2\ln (5 + 6) = 2\ln 3 - 2\ln 11$ \\
Subtract the lower from the upper: \\
$(2\ln 4 - 2\ln 13) - (2\ln 3 - 2\ln 11)$ \\
$= 2\ln 4 - 2\ln 13 - 2\ln 3 + 2\ln 11$ \\
Take out the factor 2: \\
$= 2(\ln 4 + \ln 11 - \ln 3 - \ln 13)$ \\
Use the log laws to combine: \\
$= 2\ln \frac{4 \times 11}{3 \times 13}$ \\
$= 2\ln \frac{44}{39}$ \\
Use $n\ln a = \ln a^{n}$: \\
$= \ln \left( \frac{44}{39} \right)^{2}$ \\
$= \ln \frac{1936}{1521}$ \\
So $p = \frac{1936}{1521}$ \\
(Check: $\ln \frac{1936}{1521} = 0.24126$, which matches a numerical integration of the original integral)

@q 11
@topic Two circles, arcs and perimeter
@marks 8
@question
(a) The circles meet where both equations are true \\
$x^{2} + y^{2} = 144$ \\
$(x - 16)^{2} + y^{2} = 80$ \\
Expand the second equation: \\
$x^{2} - 32x + 256 + y^{2} = 80$ \\
Replace $x^{2} + y^{2}$ by 144: \\
$144 - 32x + 256 = 80$ \\
$400 - 32x = 80$ \\
Subtract 400 from both sides: \\
$-32x = -320$ \\
Divide by $-32$: \\
$x = 10$ \\
Find $y$ from $x^{2} + y^{2} = 144$: \\
$y^{2} = 144 - 100$ \\
$y^{2} = 44$ \\
$y = \pm 2\sqrt{11}$ \\
$y = \pm 6.633$ \\
So $A = (10, 6.633)$ and $B = (10, -6.633)$ \\
Triangle: $O$, the point $(10, 0)$ and $A$. It has a right angle at $(10, 0)$ \\
The hypotenuse $OA$ is the radius of $C_{1}$, which is 12 \\
The side along the $x$ axis is 10 \\
Let the angle at $O$ be $\frac{1}{2}AOB$ \\
$\cos \left( \frac{1}{2}AOB \right) = \frac{10}{12}$ \\
$\frac{1}{2}AOB = \cos^{-1}\left( \frac{10}{12} \right)$ \\
$\frac{1}{2}AOB = 0.58569$ \\
Double it: \\
$AOB = 1.17137$ \\
$AOB = 1.171$ radians to 4 significant figures as required \\
(b) The perimeter is the outside of the shape: part of $C_{1}$ plus part of $C_{2}$ \\
Part of $C_{1}$: the circle without the bit inside $C_{2}$ \\
That arc has angle $2\pi - 1.17137 = 5.11181$ \\
Arc length $= r\theta = 12 \times 5.11181$ \\
$= 61.342$ \\
Let $X$ be the centre of $C_{2}$, which is $(16, 0)$, with radius $\sqrt{80}$ \\
Triangle: $X$, the point $(10, 0)$ and $A$, with a right angle at $(10, 0)$ \\
The side from $X$ to $(10, 0)$ is $16 - 10 = 6$ \\
The hypotenuse $XA$ is the radius $\sqrt{80}$ \\
Let $\beta$ be the angle at $X$ \\
$\cos \beta = \frac{6}{\sqrt{80}}$ \\
$\beta = \cos^{-1}\left( \frac{6}{\sqrt{80}} \right)$ \\
$\beta = 0.83548$ \\
The angle $AXB = 2\beta = 1.67096$ is the part of $C_{2}$ inside $C_{1}$ \\
The outside arc of $C_{2}$ has angle $2\pi - 1.67096 = 4.61222$ \\
Arc length $= \sqrt{80} \times 4.61222$ \\
$= 8.94427 \times 4.61222$ \\
$= 41.252$ \\
Perimeter $= 61.342 + 41.252$ \\
$= 102.594$ \\
The perimeter is 102.6 to 1 decimal place

@q 12
@topic sec - cos identity, tan equation
@marks 8
@question
(a) Start with the left hand side: $\sec \theta - \cos \theta$ \\
Use $\sec \theta = \frac{1}{\cos \theta}$ \\
$= \frac{1}{\cos \theta} - \cos \theta$ \\
Write $\cos \theta$ with the denominator $\cos \theta$: $\cos \theta = \frac{\cos^{2} \theta}{\cos \theta}$ \\
$= \frac{1}{\cos \theta} - \frac{\cos^{2} \theta}{\cos \theta}$ \\
$= \frac{1 - \cos^{2} \theta}{\cos \theta}$ \\
Use $\sin^{2} \theta + \cos^{2} \theta = 1$, so $1 - \cos^{2} \theta = \sin^{2} \theta$ \\
$= \frac{\sin^{2} \theta}{\cos \theta}$ \\
Split $\sin^{2} \theta$ into $\sin \theta \times \sin \theta$: \\
$= \sin \theta \times \frac{\sin \theta}{\cos \theta}$ \\
Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$ \\
$= \sin \theta \tan \theta$ as required \\
(b) By part (a) with $\theta = x$, $\sec x - \cos x = \sin x \tan x$ \\
The equation $\sec x - \cos x = \sin x \tan (2x - 30)$ becomes \\
$\sin x \tan x = \sin x \tan (2x - 30)$ \\
Subtract the right hand side from both sides: \\
$\sin x \tan x - \sin x \tan (2x - 30) = 0$ \\
Factorise out $\sin x$ (do not divide by it, or solutions are lost): \\
$\sin x \left[ \tan x - \tan (2x - 30) \right] = 0$ \\
Either $\sin x = 0$ or $\tan x = \tan (2x - 30)$ \\
Case 1: $\sin x = 0$ with $0 < x \leq 360$ degrees \\
$x = 180$ degrees or $x = 360$ degrees \\
Case 2: $\tan x = \tan (2x - 30)$ \\
Tangent repeats every 180 degrees, so $x = 2x - 30 + 180n$ \\
Subtract $2x$ from both sides: \\
$-x = -30 + 180n$ \\
Multiply by $-1$: \\
$x = 30 - 180n$ \\
$n = 0$ gives $x = 30$ degrees \\
$n = -1$ gives $x = 30 + 180 = 210$ degrees \\
$n = -2$ gives $x = 390$ degrees, which is too big \\
$n = 1$ gives $x = -150$ degrees, which is too small \\
(Check $x = 210$ degrees: $\tan 210 = 0.5774$ and $\tan (2 \times 210 - 30) = \tan 390 = 0.5774$) \\
All solutions: $x = 30, 180, 210, 360$ degrees

@q 13
@topic Periodic sequence of order 3
@marks 7
@question
(a) Use $a_{n+1} = \frac{k(a_{n} - 2)}{a_{n}}$ starting with $a_{1} = 4$ \\
$a_{2} = \frac{k(4 - 2)}{4}$ \\
$a_{2} = \frac{2k}{4}$ \\
$a_{2} = \frac{k}{2}$ \\
$a_{3} = \frac{k\left( \frac{k}{2} - 2 \right)}{\frac{k}{2}}$ \\
Top: $k\left( \frac{k}{2} - 2 \right) = \frac{k(k - 4)}{2}$ \\
Divide by $\frac{k}{2}$, which is multiplying by $\frac{2}{k}$: \\
$a_{3} = \frac{k(k - 4)}{2} \times \frac{2}{k}$ \\
$a_{3} = k - 4$ \\
$a_{4} = \frac{k(k - 4 - 2)}{k - 4}$ \\
$a_{4} = \frac{k(k - 6)}{k - 4}$ \\
Period 3 means the terms repeat every 3, so $a_{4} = a_{1} = 4$ \\
$\frac{k(k - 6)}{k - 4} = 4$ \\
Multiply both sides by $(k - 4)$: \\
$k(k - 6) = 4(k - 4)$ \\
Expand both sides: \\
$k^{2} - 6k = 4k - 16$ \\
Subtract $4k$ from both sides: \\
$k^{2} - 10k = -16$ \\
Add 16 to both sides: \\
$k^{2} - 10k + 16 = 0$ as required \\
(b) Factorise: $(k - 2)(k - 8) = 0$ \\
$k = 2$ or $k = 8$ \\
Try $k = 8$: $a_{2} = \frac{8}{2} = 4$ \\
$a_{3} = 8 - 4 = 4$ \\
Every term is 4, so the sequence repeats every 1 term, not every 3 \\
So it does not have order 3, and $k \ne 8$ \\
(c) So $k = 2$ \\
$a_{1} = 4$ \\
$a_{2} = \frac{2}{2} = 1$ \\
$a_{3} = 2 - 4 = -2$ \\
$a_{4} = \frac{2(2 - 6)}{2 - 4} = \frac{-8}{-2} = 4$ \\
The sequence repeats $4, 1, -2$ \\
One full cycle adds up to $4 + 1 + (-2) = 3$ \\
$58 = 3 \times 19 + 1$, so there are 19 full cycles and one extra term \\
The extra term is $a_{58} = a_{1} = 4$ \\
$\sum_{r=1}^{58} a_{r} = 19 \times 3 + 4$ \\
$= 57 + 4$ \\
$= 61$

@q 14
@topic Balloon deflating, differential equation
@marks 10
@question
(a) The volume decreases at a constant rate: \\
$\frac{dV}{dt} = -c$ where $c$ is a positive constant \\
The balloon is a sphere: $V = \frac{4}{3}\pi r^{3}$ \\
Differentiate with respect to $r$: \\
$\frac{dV}{dr} = 4\pi r^{2}$ \\
Use the chain rule: $\frac{dV}{dt} = \frac{dV}{dr} \times \frac{dr}{dt}$ \\
$-c = 4\pi r^{2} \times \frac{dr}{dt}$ \\
Divide by $4\pi r^{2}$: \\
$\frac{dr}{dt} = -\frac{c}{4\pi r^{2}}$ \\
Let $k = \frac{c}{4\pi}$, which is a positive constant \\
$\frac{dr}{dt} = -\frac{k}{r^{2}}$ as required \\
(b) Separate the variables: multiply both sides by $r^{2}$ and by $dt$ \\
$r^{2} \, dr = -k \, dt$ \\
Integrate both sides: \\
$\frac{r^{3}}{3} = -kt + \alpha$ \\
Initially $t = 0$ and $r = 80$: \\
$\frac{80^{3}}{3} = 0 + \alpha$ \\
$80^{3} = 512000$ \\
$\alpha = \frac{512000}{3}$ \\
After 5 seconds $t = 5$ and $r = 30$: \\
$\frac{30^{3}}{3} = -5k + \frac{512000}{3}$ \\
$30^{3} = 27000$, so $\frac{27000}{3} = 9000$ \\
$9000 = -5k + \frac{512000}{3}$ \\
Add $5k$ and subtract 9000 on both sides: \\
$5k = \frac{512000}{3} - 9000$ \\
Write 9000 as thirds: $9000 = \frac{27000}{3}$ \\
$5k = \frac{512000 - 27000}{3}$ \\
$5k = \frac{485000}{3}$ \\
Divide by 5: \\
$k = \frac{97000}{3}$ \\
Put $k$ and $\alpha$ back in: \\
$\frac{r^{3}}{3} = -\frac{97000}{3}t + \frac{512000}{3}$ \\
Multiply every term by 3: \\
$r^{3} = 512000 - 97000t$ \\
(Check: at $t = 5$, $r^{3} = 512000 - 485000 = 27000$, so $r = 30$) \\
(c) The radius cannot be negative, and the balloon is empty when $r = 0$ \\
$512000 - 97000t \geq 0$ \\
Add $97000t$ to both sides: \\
$512000 \geq 97000t$ \\
Divide by 97000: \\
$t \leq \frac{512}{97}$ \\
$\frac{512}{97} = 5.28$ \\
The equation is valid for $0 \leq t \leq \frac{512}{97}$ seconds (about 5.28 seconds)

@q 15
@topic Implicit differentiation, inflection point
@marks 7
@question
(a) Differentiate $x^{3}\tan y = 9$ with respect to $x$ \\
Product rule on $x^{3}\tan y$, with the chain rule for $\tan y$: \\
$3x^{2}\tan y + x^{3}\sec^{2} y \frac{dy}{dx} = 0$ \\
Subtract $3x^{2}\tan y$ from both sides: \\
$x^{3}\sec^{2} y \frac{dy}{dx} = -3x^{2}\tan y$ \\
Divide by $x^{3}\sec^{2} y$: \\
$\frac{dy}{dx} = \frac{-3x^{2}\tan y}{x^{3}\sec^{2} y}$ \\
From the equation of $C$: $\tan y = \frac{9}{x^{3}}$ \\
Use $\sec^{2} y = 1 + \tan^{2} y$ \\
$\sec^{2} y = 1 + \frac{81}{x^{6}}$ \\
Top: $-3x^{2} \times \frac{9}{x^{3}} = -\frac{27}{x}$ \\
Bottom: $x^{3}\left( 1 + \frac{81}{x^{6}} \right) = x^{3} + \frac{81}{x^{3}}$ \\
Bottom as one fraction: $\frac{x^{6} + 81}{x^{3}}$ \\
$\frac{dy}{dx} = \frac{-\frac{27}{x}}{\frac{x^{6} + 81}{x^{3}}}$ \\
Dividing by a fraction is multiplying by its reciprocal: \\
$\frac{dy}{dx} = -\frac{27}{x} \times \frac{x^{3}}{x^{6} + 81}$ \\
Cancel one $x$: \\
$\frac{dy}{dx} = \frac{-27x^{2}}{x^{6} + 81}$ as required \\
(b) Quotient rule with $u = -27x^{2}$ and $v = x^{6} + 81$ \\
$\frac{du}{dx} = -54x$ \\
$\frac{dv}{dx} = 6x^{5}$ \\
$\frac{d^{2}y}{dx^{2}} = \frac{\frac{du}{dx}v - u\frac{dv}{dx}}{v^{2}}$ \\
$\frac{d^{2}y}{dx^{2}} = \frac{-54x(x^{6} + 81) - (-27x^{2})(6x^{5})}{(x^{6} + 81)^{2}}$ \\
Expand the top: $-54x(x^{6} + 81) = -54x^{7} - 4374x$ \\
Expand the top: $-(-27x^{2})(6x^{5}) = 162x^{7}$ \\
Add: $-54x^{7} - 4374x + 162x^{7} = 108x^{7} - 4374x$ \\
Factorise: $108x^{7} - 4374x = 54x(2x^{6} - 81)$ \\
$\frac{d^{2}y}{dx^{2}} = \frac{54x(2x^{6} - 81)}{(x^{6} + 81)^{2}}$ \\
Since $x^{3}\tan y = 9$ and $\tan y > 0$, we have $x > 0$ \\
So $54x > 0$ and $(x^{6} + 81)^{2} > 0$ \\
The sign of $\frac{d^{2}y}{dx^{2}}$ is the sign of $2x^{6} - 81$ \\
Set $2x^{6} - 81 = 0$: \\
$x^{6} = \frac{81}{2}$ \\
$x = \sqrt[6]{\frac{81}{2}}$ \\
For $x < \sqrt[6]{\frac{81}{2}}$: $2x^{6} < 81$, so $\frac{d^{2}y}{dx^{2}} < 0$ \\
For $x > \sqrt[6]{\frac{81}{2}}$: $2x^{6} > 81$, so $\frac{d^{2}y}{dx^{2}} > 0$ \\
$\frac{d^{2}y}{dx^{2}}$ is zero and changes sign at $x = \sqrt[6]{\frac{81}{2}}$ \\
So $C$ has a point of inflection at $x = \sqrt[6]{\frac{81}{2}}$

@q 16
@topic Proof by contradiction, 4a^2 - b^2 = 49
@marks 4
@question
Assume the opposite: there are positive integers $a$ and $b$ with $4a^{2} - b^{2} = 49$ \\
Write $4a^{2}$ as $(2a)^{2}$ and use the difference of two squares: \\
$(2a)^{2} - b^{2} = (2a - b)(2a + b)$ \\
$(2a - b)(2a + b) = 49$ \\
$a$ and $b$ are integers, so both brackets are integers \\
$2a + b$ is positive, and the product is positive, so $2a - b$ is positive too \\
Also $2a + b > 2a - b$ since $b > 0$ \\
The ways to write 49 as a product of two positive integers are $49 \times 1$ and $7 \times 7$ \\
Case 1: $2a + b = 49$ and $2a - b = 1$ \\
Add the two equations: \\
$4a = 50$ \\
$a = 12.5$, which is not an integer \\
Case 2: $2a + b = 7$ and $2a - b = 7$ \\
Add the two equations: \\
$4a = 14$ \\
$a = 3.5$, which is not an integer \\
(Also subtracting gives $2b = 0$, so $b = 0$, which is not positive) \\
Both cases give a contradiction \\
So there are no positive integers $a$ and $b$ such that $4a^{2} - b^{2} = 49$
