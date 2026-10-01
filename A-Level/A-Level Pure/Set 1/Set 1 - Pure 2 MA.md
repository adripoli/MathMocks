@paper P2 Mock Set 1

@q 1
@topic Small angle approximations, validity
@marks 4
@question
(a) Small angle approximations: $\cos \theta \approx 1 - \frac{\theta^{2}}{2}$, $\sin \theta \approx \theta$, $\tan \theta \approx \theta$ \\
Apply them to each term in $\cos \theta - \sin\left( \frac{1}{2}\theta \right) + 2\tan \theta = \frac{11}{10}$: \\
$\cos \theta \approx 1 - \frac{1}{2}\theta^{2}$ \\
$\sin\left( \frac{1}{2}\theta \right) \approx \frac{1}{2}\theta$ \\
$2\tan \theta \approx 2\theta$ \\
$1 - \frac{1}{2}\theta^{2} - \frac{1}{2}\theta + 2\theta \approx \frac{11}{10}$ \\
Collect the $\theta$ terms: $-\frac{1}{2}\theta + 2\theta = \frac{3}{2}\theta$ \\
$1 - \frac{1}{2}\theta^{2} + \frac{3}{2}\theta \approx \frac{11}{10}$ \\
Subtract $\frac{11}{10}$ from both sides: \\
$-\frac{1}{2}\theta^{2} + \frac{3}{2}\theta + 1 - \frac{11}{10} \approx 0$ \\
$-\frac{1}{2}\theta^{2} + \frac{3}{2}\theta - \frac{1}{10} \approx 0$ \\
Multiply every term by $-10$: \\
$5\theta^{2} - 15\theta + 1 \approx 0$ as required \\
(b) $\theta = 0.068$ is small, so the small angle approximations are valid \\
So this is a valid approximate solution to the original equation \\
$\theta = 2.932$ is not small (it is close to $\pi$), so the approximations do not hold \\
So this is not a valid solution to the original equation

@q 2
@topic Parametric to Cartesian equation
@marks 3
@question
$x = 6t + 1$ and $y = 5 - \frac{4}{3t}$ \\
Rearrange the first equation to make $t$ the subject: \\
$x - 1 = 6t$ \\
$t = \frac{x - 1}{6}$ \\
Substitute into $y = 5 - \frac{4}{3t}$: \\
$y = 5 - \frac{4}{3\left( \frac{x - 1}{6} \right)}$ \\
Simplify the denominator: $3 \times \frac{x - 1}{6} = \frac{x - 1}{2}$ \\
$y = 5 - \frac{4}{\frac{x - 1}{2}}$ \\
Dividing by a fraction is the same as multiplying by its reciprocal: \\
$y = 5 - 4 \times \frac{2}{x - 1}$ \\
$y = 5 - \frac{8}{x - 1}$ \\
Write 5 as a fraction with denominator $(x - 1)$: \\
$y = \frac{5(x - 1)}{x - 1} - \frac{8}{x - 1}$ \\
Combine: \\
$y = \frac{5(x - 1) - 8}{x - 1}$ \\
Expand the bracket: \\
$y = \frac{5x - 5 - 8}{x - 1}$ \\
$y = \frac{5x - 13}{x - 1}$ \\
$t \ne 0$, so $x \ne 6(0) + 1 = 1$ \\
So $a = 5$, $b = -13$ and $k = 1$

@q 3
@topic Stationary point, inflection, sign change
@marks 9
@question
(a) $y = x^{2} + kx + 14 - \frac{8}{x - 5}$ \\
Write the fraction as a power: $\frac{8}{x - 5} = 8(x - 5)^{-1}$ \\
$y = x^{2} + kx + 14 - 8(x - 5)^{-1}$ \\
Differentiate each term: \\
$x^{2} \to 2x$ \\
$kx \to k$ \\
$14 \to 0$ \\
$-8(x - 5)^{-1} \to -8(-1)(x - 5)^{-2} = 8(x - 5)^{-2}$ \\
$\frac{dy}{dx} = 2x + k + 8(x - 5)^{-2}$ \\
At the stationary point, $x = 3$ and $\frac{dy}{dx} = 0$: \\
$2(3) + k + \frac{8}{(3 - 5)^{2}} = 0$ \\
$6 + k + \frac{8}{(-2)^{2}} = 0$ \\
$6 + k + \frac{8}{4} = 0$ \\
$6 + k + 2 = 0$ \\
$8 + k = 0$ \\
$k = -8$ as required \\
(b) Differentiate again: \\
$\frac{d^{2}y}{dx^{2}} = 2 + 8(-2)(x - 5)^{-3}$ \\
$= 2 - 16(x - 5)^{-3}$ \\
$= 2 - \frac{16}{(x - 5)^{3}}$ \\
At $x = 3$: \\
$\frac{d^{2}y}{dx^{2}} = 2 - \frac{16}{(3 - 5)^{3}}$ \\
$= 2 - \frac{16}{(-2)^{3}}$ \\
$= 2 - \frac{16}{-8}$ \\
$= 2 + 2$ \\
$= 4$ \\
$\frac{d^{2}y}{dx^{2}} > 0$, so $P$ is a local minimum \\
(c) At $x = 7$: \\
$\frac{d^{2}y}{dx^{2}} = 2 - \frac{16}{(7 - 5)^{3}}$ \\
$= 2 - \frac{16}{8}$ \\
$= 2 - 2$ \\
$= 0$ \\
Check that the second derivative changes sign either side of $x = 7$: \\
At $x = 6$: $\frac{d^{2}y}{dx^{2}} = 2 - \frac{16}{1^{3}} = -14 < 0$ \\
At $x = 8$: $\frac{d^{2}y}{dx^{2}} = 2 - \frac{16}{27} = 1.41 > 0$ \\
Or use the third derivative: $\frac{d^{3}y}{dx^{3}} = 48(x - 5)^{-4} = \frac{48}{(x - 5)^{4}}$ \\
At $x = 7$: $\frac{48}{2^{4}} = 3 \ne 0$ \\
So the curve has a point of inflection at $x = 7$ \\
(d) The curve is not defined at $x = 5$, as $\frac{8}{x - 5}$ would need division by zero \\
So the curve is not continuous on the interval $(4.5, 5.5)$, and it has a vertical asymptote at $x = 5$ \\
A change of sign only shows there is a root if the curve is continuous, so Jane's reasoning is not valid

@q 4
@topic Cubic factorisation, roots, trig solutions
@marks 6
@question
(a) $f(x) = x^{3} - 6x^{2} + 7x + 2$ \\
$Q$ is $(2, 0)$, so $(x - 2)$ is a factor \\
Write $f(x) = (x - 2)(x^{2} + bx - 1)$, as the constant term is $(-2) \times (-1) = 2$ \\
Expand: $(x - 2)(x^{2} + bx - 1) = x^{3} + bx^{2} - x - 2x^{2} - 2bx + 2$ \\
$= x^{3} + (b - 2)x^{2} + (-1 - 2b)x + 2$ \\
Compare the $x^{2}$ terms: $b - 2 = -6$, so $b = -4$ \\
Check the $x$ terms: $-1 - 2(-4) = 7$ \\
$f(x) = (x - 2)(x^{2} - 4x - 1)$ \\
(b) $P$ and $R$ are the other roots, from $x^{2} - 4x - 1 = 0$ \\
Use the quadratic formula with $a = 1$, $b = -4$, $c = -1$: \\
$x = \frac{4 \pm \sqrt{(-4)^{2} - 4(1)(-1)}}{2(1)}$ \\
$= \frac{4 \pm \sqrt{16 + 4}}{2}$ \\
$= \frac{4 \pm \sqrt{20}}{2}$ \\
$\sqrt{20} = \sqrt{4 \times 5} = 2\sqrt{5}$ \\
$= \frac{4 \pm 2\sqrt{5}}{2}$ \\
$= 2 \pm \sqrt{5}$ \\
(i) $P$ has the smaller $x$ value: $x = 2 - \sqrt{5}$ \\
(ii) $R$ has the larger $x$ value: $x = 2 + \sqrt{5}$ \\
(c) $\sin^{3}\theta - 6\sin^{2}\theta + 7\sin\theta + 2 = 0$ is $f(\sin\theta) = 0$ \\
So $\sin\theta = 2$, $\sin\theta = 2 - \sqrt{5}$ or $\sin\theta = 2 + \sqrt{5}$ \\
$\sin\theta = 2$ has no solutions, as $-1 \le \sin\theta \le 1$ \\
$\sin\theta = 2 + \sqrt{5} = 4.236$ has no solutions for the same reason \\
$\sin\theta = 2 - \sqrt{5} = -0.236$ is between $-1$ and 1, so it has solutions \\
In each interval of length $2\pi$ this has 2 solutions \\
$[0, 12\pi]$ is 6 intervals of length $2\pi$, so it has $6 \times 2 = 12$ solutions \\
In $[-\pi, 0]$, $\sin\theta$ is negative, and $\sin\theta = -0.236$ has 2 solutions ($\theta = -0.238$ and $\theta = -\pi + 0.238 = -2.90$) \\
Total number of real solutions $= 12 + 2 = 14$

@q 5
@topic Modulus graph, area, range of k
@marks 5
@question
(a) $f(x) = 7 - |3x - 5|$ \\
The graph is an upside-down V, with its vertex where $3x - 5 = 0$, i.e. $x = \frac{5}{3}$, at height $y = 7$ \\
It meets the $x$-axis where $f(x) = 0$: \\
$7 - |3x - 5| = 0$ \\
$|3x - 5| = 7$ \\
$3x - 5 = 7$ or $3x - 5 = -7$ \\
$3x = 12$, so $x = 4$ \\
$3x = -2$, so $x = -\frac{2}{3}$ \\
Region $R$ is a triangle with base from $x = -\frac{2}{3}$ to $x = 4$, and height 7 \\
Base $= 4 - \left( -\frac{2}{3} \right) = 4 + \frac{2}{3} = \frac{14}{3}$ \\
Area $= \frac{1}{2} \times \text{base} \times \text{height}$ \\
$= \frac{1}{2} \times \frac{14}{3} \times 7$ \\
$= \frac{7}{3} \times 7$ \\
$= \frac{49}{3}$ \\
(b) The greatest value of $f(x)$ is 7 \\
The horizontal line $y = k$ cuts the upside-down V twice when it is below the vertex \\
$k < 7$

@q 6
@topic Binomial expansion, (2+kx)^-4, validity
@marks 6
@question
(a) Take out a factor of 2 from the bracket: \\
$(2 + kx)^{-4} = \left( 2\left( 1 + \frac{kx}{2} \right) \right)^{-4}$ \\
$= 2^{-4}\left( 1 + \frac{kx}{2} \right)^{-4}$ \\
$= \frac{1}{16}\left( 1 + \frac{kx}{2} \right)^{-4}$ \\
Binomial expansion: $(1 + X)^{n} = 1 + nX + \frac{n(n-1)}{2!}X^{2} + \ldots$ with $n = -4$ and $X = \frac{kx}{2}$ \\
$\left( 1 + \frac{kx}{2} \right)^{-4} = 1 + (-4)\left( \frac{kx}{2} \right) + \frac{(-4)(-5)}{2}\left( \frac{kx}{2} \right)^{2} + \ldots$ \\
$= 1 - 2kx + 10 \times \frac{k^{2}x^{2}}{4} + \ldots$ \\
$= 1 - 2kx + \frac{5k^{2}}{2}x^{2} + \ldots$ \\
Multiply by $\frac{1}{16}$: \\
$(2 + kx)^{-4} = \frac{1}{16} - \frac{2k}{16}x + \frac{5k^{2}}{32}x^{2} + \ldots$ \\
$= \frac{1}{16} - \frac{k}{8}x + \frac{5k^{2}}{32}x^{2} + \ldots$ \\
Compare the $x^{2}$ terms with $\frac{125}{32}x^{2}$: \\
$\frac{5k^{2}}{32} = \frac{125}{32}$ \\
$5k^{2} = 125$ \\
$k^{2} = 25$ \\
$k = 5$ (as $k > 0$) \\
$A = -\frac{k}{8} = -\frac{5}{8}$ \\
(b) The expansion is valid when $\left| \frac{kx}{2} \right| < 1$ \\
$\left| \frac{5x}{2} \right| < 1$ \\
$|x| < \frac{2}{5}$ \\
$x = \frac{1}{10} = 0.1$, and $0.1 < \frac{2}{5} = 0.4$ \\
So the expansion is valid when $x = \frac{1}{10}$

@q 7
@topic Roots, iteration, Newton-Raphson method
@marks 8
@question
(a) $f(x) = \frac{2}{x} - e^{x} + 2x^{2}$ \\
$f(-1.5) = \frac{2}{-1.5} - e^{-1.5} + 2(-1.5)^{2}$ \\
$= -1.3333 - 0.2231 + 2(2.25)$ \\
$= -1.3333 - 0.2231 + 4.5$ \\
$= 2.9435$ \\
$f(-1) = \frac{2}{-1} - e^{-1} + 2(-1)^{2}$ \\
$= -2 - 0.3679 + 2$ \\
$= -0.3679$ \\
$f(-1.5)$ is positive and $f(-1)$ is negative, and $f$ is continuous on $[-1.5, -1]$ \\
So there is a sign change, and $\alpha$ lies between $-1.5$ and $-1$ \\
(b)(i) $x_{n+1} = -\sqrt{\frac{1}{2}e^{x_{n}} - \frac{1}{x_{n}}}$ and $x_{1} = -1$ \\
$x_{2} = -\sqrt{\frac{1}{2}e^{-1} - \frac{1}{-1}}$ \\
$= -\sqrt{0.18394 + 1}$ \\
$= -\sqrt{1.18394}$ \\
$= -1.0881$ \\
$x_{3} = -\sqrt{\frac{1}{2}e^{-1.0881} - \frac{1}{-1.0881}}$ \\
$= -\sqrt{0.16843 + 0.91902}$ \\
$= -\sqrt{1.08745}$ \\
$= -1.0428$ (4 dp) \\
(ii) Keep iterating (using the ANS key): \\
$x_{4} = -1.0654$, $x_{5} = -1.0540$, $x_{6} = -1.0597$, $x_{7} = -1.0568$, $x_{8} = -1.0583$ \\
The values go either side of about $-1.058$ \\
Check with a sign change of $f$: \\
$f(-1.055) = -0.018$ (negative) \\
$f(-1.065) = 0.046$ (positive) \\
So $\alpha$ is between $-1.065$ and $-1.055$, and every number in this interval rounds to $-1.06$ \\
$\alpha = -1.06$ (2 dp) \\
(c) Newton-Raphson: $x_{2} = x_{1} - \frac{f(x_{1})}{f'(x_{1})}$, with $x_{1} = 3$ \\
$x_{2} = 3 - \frac{-1.4189}{-8.3078}$ \\
$= 3 - 0.1708$ \\
$= 2.8292$ \\
$x_{2} = 2.83$ (2 dp) \\
(d) With $x_{1} = 1.5$, the gradient of the curve is very small: $f'(1.5) = 0.63$ \\
$f(1.5) = 1.35$ \\
Draw the tangent at $x = 1.5$: it is almost flat, so it meets the $x$-axis a long way away, at $x_{2} = 1.5 - \frac{1.35}{0.63} = -0.65$ \\
This is on the wrong side of the $y$-axis, far from $\beta$, which is between 1.5 and 3 \\
So the second approximation is not a good one

@q 8
@topic Circle equation, chord length
@marks 7
@question
(a) The circle touches the $x$-axis, so the radius is the distance from the centre to the $x$-axis \\
The centre is $(9, -6)$, which is 6 units below the $x$-axis, so $r = 6$ \\
Equation of a circle: $(x - a)^{2} + (y - b)^{2} = r^{2}$ \\
$(x - 9)^{2} + (y + 6)^{2} = 36$ \\
(b) $PQ = 8$, and the line through the centre perpendicular to the chord bisects it, so half the chord is 4 \\
Let $d$ be the perpendicular distance from the centre to the line $l$ \\
Form a right-angled triangle with sides $d$ and 4, and hypotenuse 6 (the radius): \\
$d^{2} + 4^{2} = 6^{2}$ \\
$d^{2} + 16 = 36$ \\
$d^{2} = 20$ \\
$d = \sqrt{20} = 2\sqrt{5}$ \\
$l$ is parallel to the $x$-axis, so it is a horizontal line $y = c$, at a distance $2\sqrt{5}$ above or below the centre, which has $y$ coordinate $-6$ \\
$y = -6 + 2\sqrt{5}$ or $y = -6 - 2\sqrt{5}$

@q 9
@topic Log form of y = ab^t, antibiotic dose
@marks 9
@question
(a) $y = ab^{t}$ \\
Take $\log_{10}$ of both sides: \\
$\log_{10} y = \log_{10}(ab^{t})$ \\
Use $\log(xy) = \log x + \log y$: \\
$\log_{10} y = \log_{10} a + \log_{10}(b^{t})$ \\
Use $\log(x^{n}) = n\log x$: \\
$\log_{10} y = \log_{10} a + t\log_{10} b$ \\
$\log_{10} y = t\log_{10} b + c$, where $c = \log_{10} a$ \\
(b) The line passes through $(0, 2.23)$, so the intercept is $c = 2.23$ \\
$\log_{10} a = 2.23$ \\
$a = 10^{2.23}$ \\
$= 169.8$ \\
$= 170$ (2 sf) \\
The gradient is $\log_{10} b = -0.076$ \\
$b = 10^{-0.076}$ \\
$= 0.8395$ \\
$= 0.84$ (2 sf) \\
(c)(i) When $t = 0$, $y = ab^{0} = a$ \\
So $a = 170$ is the initial amount of antibiotic, in mg, in the patient's bloodstream \\
(ii) Each hour the amount is multiplied by $b = 0.84$ \\
So the amount of antibiotic falls by 16 percent each hour \\
(d) Set $y = 30$: \\
$30 = 170(0.84)^{t}$ \\
Divide both sides by 170: \\
$(0.84)^{t} = \frac{30}{170}$ \\
Take natural logs of both sides: \\
$\ln\left( (0.84)^{t} \right) = \ln\left( \frac{30}{170} \right)$ \\
Use the power law: \\
$t\ln(0.84) = \ln\left( \frac{30}{170} \right)$ \\
Divide both sides by $\ln(0.84)$: \\
$t = \frac{\ln\left( \frac{30}{170} \right)}{\ln(0.84)}$ \\
$= \frac{-1.7346}{-0.17435}$ \\
$= 9.95$ \\
$t = 9.9$ hours (1 dp) \\
(e) The measurements were only taken for the first 5 hours \\
$t = 9.9$ is outside this range, so the estimate is an extrapolation, and it may not be reliable

@q 10
@topic Differential equation, mould growth model
@marks 9
@question
(a) The rate of increase is proportional to the square root of the area: \\
$\frac{dA}{dt} = k\sqrt{A}$ \\
Separate the variables: \\
$\frac{1}{\sqrt{A}} \, dA = k \, dt$ \\
$A^{-\frac{1}{2}} \, dA = k \, dt$ \\
Integrate both sides: \\
$\int A^{-\frac{1}{2}} \, dA = \int k \, dt$ \\
$\frac{A^{\frac{1}{2}}}{\frac{1}{2}} = kt + c$ \\
$2A^{\frac{1}{2}} = kt + c$ \\
At the start, $t = 0$ and $A = 9$: \\
$2\sqrt{9} = k(0) + c$ \\
$6 = c$ \\
After 6 days, $t = 6$ and $A = 56.25$: \\
$2\sqrt{56.25} = 6k + 6$ \\
$\sqrt{56.25} = 7.5$, so $2 \times 7.5 = 15$ \\
$15 = 6k + 6$ \\
Subtract 6 from both sides: \\
$9 = 6k$ \\
$k = \frac{9}{6} = \frac{3}{2}$ \\
$2\sqrt{A} = \frac{3}{2}t + 6$ \\
Divide both sides by 2: \\
$\sqrt{A} = \frac{3}{4}t + 3$ \\
Square both sides: \\
$A = \left( \frac{3}{4}t + 3 \right)^{2}$ as required \\
(b)(i) Use the model for each time: \\
$t = 12$: $A = \left( \frac{3}{4}(12) + 3 \right)^{2} = (9 + 3)^{2} = 144$ \\
$t = 18$: $A = \left( \frac{3}{4}(18) + 3 \right)^{2} = (13.5 + 3)^{2} = 272.25$ \\
$t = 24$: $A = \left( \frac{3}{4}(24) + 3 \right)^{2} = (18 + 3)^{2} = 441$ \\
$t = 30$: $A = \left( \frac{3}{4}(30) + 3 \right)^{2} = (22.5 + 3)^{2} = 650.25$ \\
Compare with the measurements $143.78$, $271.19$, $334.81$, $337.33$: \\
At $t = 12$ and $t = 18$ the model is very close (within about 1) \\
At $t = 24$ the model gives 441 but the measurement is 334.81, and at $t = 30$ it gives 650.25 but the measurement is 337.33 \\
So the model is good for $t = 12$ and $t = 18$, but overestimates badly at $t = 24$ and $t = 30$ \\
(ii) The measured area levels off, at about 337 cm$^2$ \\
The slice of bread has a limited area and a limited amount of food, so the mould cannot keep growing at an ever faster rate as the model says

@q 11
@topic Quotient rule, turning points, trig curve
@marks 8
@question
(a) $f(x) = \frac{\sin 2x}{-3 + \cos 2x}$ \\
Use the quotient rule with $u = \sin 2x$ and $v = -3 + \cos 2x$ \\
$u' = 2\cos 2x$ \\
$v' = -2\sin 2x$ \\
$f'(x) = \frac{u'v - uv'}{v^{2}}$ \\
$= \frac{(2\cos 2x)(-3 + \cos 2x) - (\sin 2x)(-2\sin 2x)}{(-3 + \cos 2x)^{2}}$ \\
Expand the numerator: \\
$= \frac{-6\cos 2x + 2\cos^{2} 2x + 2\sin^{2} 2x}{(-3 + \cos 2x)^{2}}$ \\
Use $\cos^{2} 2x + \sin^{2} 2x = 1$: \\
$2\cos^{2} 2x + 2\sin^{2} 2x = 2$ \\
$f'(x) = \frac{-6\cos 2x + 2}{(-3 + \cos 2x)^{2}}$ \\
At a turning point, $f'(x) = 0$, so the numerator is zero: \\
$-6\cos 2x + 2 = 0$ \\
$2 = 6\cos 2x$ \\
$\cos 2x = \frac{1}{3}$ as required \\
(b) The turning points of $f$ in $0 \le x \le \pi$ have $\cos 2x = \frac{1}{3}$, so $0 \le 2x \le 2\pi$ \\
$2x = \cos^{-1}\left( \frac{1}{3} \right) = 1.231$ or $2x = 2\pi - 1.231 = 5.052$ \\
At $2x = 1.231$: $\sin 2x$ is positive, so $f(x) = \frac{0.943}{-3 + \frac{1}{3}} = -0.354$, which is the minimum $P$ \\
At $2x = 5.052$: $\sin 2x$ is negative, so $f(x) = \frac{-0.943}{-2.667} = 0.354$, which is the maximum $Q$ \\
(i) $y = f(3x) + 5$ is $f$ with $x$ replaced by $3x$, and shifted up by 5 \\
Its maximum is where $2(3x) = 2\pi - 1.231$ \\
$6x = 5.052$ \\
$x = \frac{5.052}{6}$ \\
$= 0.84$ (2 dp) \\
(ii) $y = -f\left( \frac{1}{4}x \right)$ is $f$ with $x$ replaced by $\frac{x}{4}$, and turned upside down \\
Its maximum is where $f\left( \frac{1}{4}x \right)$ has its minimum \\
$2\left( \frac{x}{4} \right) = 1.231$ \\
$\frac{x}{2} = 1.231$ \\
$x = 2 \times 1.231$ \\
$= 2.46$ (2 dp)

@q 12
@topic Geometric series, mineral extraction
@marks 7
@question
(a) The yearly amounts form a geometric sequence with $a = 4500$ and $r = 0.98$ (a decrease of 2 percent is a multiplier of 0.98) \\
2018 to 2040 inclusive is $2040 - 2018 + 1 = 23$ years \\
$S_{n} = \frac{a(1 - r^{n})}{1 - r}$ \\
$S_{23} = \frac{4500(1 - 0.98^{23})}{1 - 0.98}$ \\
$0.98^{23} = 0.62835$ \\
$= \frac{4500(1 - 0.62835)}{0.02}$ \\
$= \frac{4500 \times 0.37165}{0.02}$ \\
$= 83621.86$ \\
$= 83600$ tonnes (3 sf) \\
(b) The mass extracted in 2040 is the 23rd term: \\
$u_{n} = ar^{n-1}$ \\
$u_{23} = 4500(0.98)^{22}$ \\
$= 4500 \times 0.64117$ \\
$= 2885.27$ \\
$= 2890$ tonnes (3 sf) \\
(c) Every year at least 1500 tonnes are extracted (the smallest yearly amount is 2885 tonnes) \\
So each year the first 1500 tonnes cost GBP 800 per tonne, and the rest cost GBP 600 per tonne \\
Over 23 years, the tonnes charged at GBP 800 are $1500 \times 23 = 34500$ \\
The remaining tonnes are $83621.86 - 34500 = 49121.86$, charged at GBP 600 per tonne \\
Cost of the first part: $800 \times 34500 = 27600000$ \\
Cost of the second part: $600 \times 49121.86 = 29473116.91$ \\
Total cost $= 27600000 + 29473116.91$ \\
$= 57073116.91$ \\
In millions: $x = 57.1$ (3 sf)

@q 13
@topic Parametric equations, area under curve
@marks 7
@question
$x = 6\cos t$ and $y = 5\sin 2t$ \\
$\frac{dx}{dt} = -6\sin t$ \\
$R$ is under the curve from $x = 0$ to $x = 3$ \\
Area $= \int y \, dx = \int y\frac{dx}{dt} \, dt$ \\
$y\frac{dx}{dt} = 5\sin 2t \times (-6\sin t)$ \\
$= -30\sin 2t \sin t$ \\
Use $\sin 2t = 2\sin t \cos t$: \\
$= -30 \times 2\sin t \cos t \times \sin t$ \\
$= -60\sin^{2} t \cos t$ \\
Integrate: use $\frac{d}{dt}(\sin^{3} t) = 3\sin^{2} t \cos t$, so $\int \sin^{2} t \cos t \, dt = \frac{1}{3}\sin^{3} t$ \\
$\int -60\sin^{2} t \cos t \, dt = -60 \times \frac{1}{3}\sin^{3} t = -20\sin^{3} t$ \\
Find the limits for $t$: \\
$x = 0$: $6\cos t = 0$, so $\cos t = 0$ and $t = \frac{\pi}{2}$ \\
$x = 3$: $6\cos t = 3$, so $\cos t = \frac{1}{2}$ and $t = \frac{\pi}{3}$ \\
Area $= \left[ -20\sin^{3} t \right]_{t=\frac{\pi}{2}}^{t=\frac{\pi}{3}}$ \\
Upper limit $t = \frac{\pi}{3}$: $-20\left( \frac{\sqrt{3}}{2} \right)^{3} = -20 \times \frac{3\sqrt{3}}{8} = -\frac{60\sqrt{3}}{8} = -\frac{15\sqrt{3}}{2}$ \\
Lower limit $t = \frac{\pi}{2}$: $-20(1)^{3} = -20$ \\
Subtract: \\
Area $= -\frac{15\sqrt{3}}{2} - (-20)$ \\
$= -\frac{15\sqrt{3}}{2} + 20$ \\
$= 20 - \frac{15}{2}\sqrt{3}$ as required

@q 14
@topic Area between two curves, exact area
@marks 5
@question
Find where the curves meet: \\
$kx^{2} = \sqrt{kx}$ \\
Square both sides: \\
$k^{2}x^{4} = kx$ \\
Subtract $kx$ from both sides: \\
$k^{2}x^{4} - kx = 0$ \\
Factorise: \\
$kx(kx^{3} - 1) = 0$ \\
$k > 0$, so $x = 0$ or $kx^{3} = 1$ \\
$x^{3} = \frac{1}{k}$ \\
$x = k^{-\frac{1}{3}}$ \\
For $0 < x < k^{-\frac{1}{3}}$ the curve $y = \sqrt{kx}$ is above $y = kx^{2}$ \\
Area of $R = \int_{0}^{k^{-\frac{1}{3}}} \left( \sqrt{kx} - kx^{2} \right) dx$ \\
Write $\sqrt{kx} = \sqrt{k}x^{\frac{1}{2}}$: \\
$= \int_{0}^{k^{-\frac{1}{3}}} \left( \sqrt{k}x^{\frac{1}{2}} - kx^{2} \right) dx$ \\
Integrate each term: \\
$\int \sqrt{k}x^{\frac{1}{2}} \, dx = \sqrt{k} \times \frac{x^{\frac{3}{2}}}{\frac{3}{2}} = \frac{2\sqrt{k}}{3}x^{\frac{3}{2}}$ \\
$\int kx^{2} \, dx = \frac{kx^{3}}{3}$ \\
$= \left[ \frac{2\sqrt{k}}{3}x^{\frac{3}{2}} - \frac{k}{3}x^{3} \right]_{0}^{k^{-\frac{1}{3}}}$ \\
At $x = 0$ both terms are 0 \\
At $x = k^{-\frac{1}{3}}$: \\
$x^{\frac{3}{2}} = \left( k^{-\frac{1}{3}} \right)^{\frac{3}{2}} = k^{-\frac{1}{2}}$ \\
$x^{3} = \left( k^{-\frac{1}{3}} \right)^{3} = k^{-1}$ \\
$\frac{2\sqrt{k}}{3} \times k^{-\frac{1}{2}} = \frac{2}{3} \times k^{\frac{1}{2}} \times k^{-\frac{1}{2}} = \frac{2}{3}$ \\
$\frac{k}{3} \times k^{-1} = \frac{1}{3}$ \\
Area of $R = \frac{2}{3} - \frac{1}{3}$ \\
$= \frac{1}{3}$ \\
This does not depend on $k$, so the area is $\frac{1}{3}$ for all values of $k$

@q 15
@topic Periodic sequence, recurrence relation
@marks 7
@question
(a) $a_{n+1} = k - \frac{3k}{a_{n}}$ and $a_{2} = 2$ \\
$a_{3} = k - \frac{3k}{a_{2}}$ \\
$= k - \frac{3k}{2}$ \\
$= -\frac{k}{2}$ \\
$a_{4} = k - \frac{3k}{a_{3}}$ \\
$= k - \frac{3k}{-\frac{k}{2}}$ \\
$\frac{3k}{-\frac{k}{2}} = 3k \times \left( -\frac{2}{k} \right) = -6$ \\
$= k - (-6)$ \\
$= k + 6$ \\
The sequence has order 3, so it repeats every 3 terms and $a_{5} = a_{2} = 2$ \\
$a_{5} = k - \frac{3k}{a_{4}} = k - \frac{3k}{k + 6}$ \\
$k - \frac{3k}{k + 6} = 2$ \\
Multiply every term by $(k + 6)$: \\
$k(k + 6) - 3k = 2(k + 6)$ \\
Expand both brackets: \\
$k^{2} + 6k - 3k = 2k + 12$ \\
$k^{2} + 3k = 2k + 12$ \\
Subtract $2k$ and 12 from both sides: \\
$k^{2} + k - 12 = 0$ as required \\
(b) Factorise: the numbers with product $-12$ and sum $1$ are $4$ and $-3$ \\
$(k + 4)(k - 3) = 0$ \\
$k = -4$ or $k = 3$ \\
If $k = -4$: $a_{2} = -4 - \frac{-12}{a_{1}} = 2$ gives $\frac{12}{a_{1}} = 6$, so $a_{1} = 2$ \\
This has $a_{1} = a_{2}$, which is not allowed, so reject $k = -4$ \\
So $k = 3$ \\
$a_{3} = -\frac{k}{2} = -1.5$ \\
$a_{4} = k + 6 = 9$ \\
The order is 3, so $a_{1} = a_{4} = 9$ \\
Check: $a_{2} = 3 - \frac{9}{9} = 2$, and $a_{1} = 9 \ne a_{2}$ \\
The sequence is $9, 2, -1.5, 9, 2, -1.5, \ldots$ \\
Sum of one cycle: $9 + 2 - 1.5 = 9.5$ \\
$121 = 3 \times 40 + 1$, so there are 40 full cycles plus one more term, $a_{121} = a_{1} = 9$ \\
$\sum_{r=1}^{121} a_{r} = 40 \times 9.5 + 9$ \\
$= 380 + 9$ \\
$= 389$
