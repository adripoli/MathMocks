@paper P2 SAMs

@q 1
@topic Factor theorem, find constant a
@marks 3
@question
$f(x) = 2x^{3} - 5x^{2} + ax + a$ \\
$(x + 2)$ is a factor, so $f(-2) = 0$ \\
$2(-2)^{3} - 5(-2)^{2} + a(-2) + a = 0$ \\
$2(-8) - 5(4) - 2a + a = 0$ \\
$-16 - 20 - 2a + a = 0$ \\
Collect the numbers and the terms in $a$: \\
$-36 - a = 0$ \\
Add $a$ to both sides: \\
$-36 = a$ \\
$a = -36$

@q 2
@topic Find the errors, cos = 2 sin
@marks 3
@question
(a) $\cos \theta = 2\sin \theta$ \\
Divide both sides by $\cos \theta$: \\
$1 = 2 \times \frac{\sin \theta}{\cos \theta}$ \\
$\tan \theta = \frac{\sin \theta}{\cos \theta}$, so this gives $1 = 2\tan \theta$, i.e. $\tan \theta = \frac{1}{2}$ \\
Student A wrote $\tan \theta = 2$, so they used $\tan \theta = \frac{\cos \theta}{\sin \theta}$ \\
That is the error: the correct identity is $\tan \theta = \frac{\sin \theta}{\cos \theta}$ \\
(b)(i) Test $\theta = -26.6$ degrees in $\cos \theta = 2\sin \theta$: \\
$\cos(-26.6) = 0.894$, which is positive \\
$2\sin(-26.6) = 2(-0.448) = -0.896$, which is negative \\
$0.894 \ne -0.896$, so $\theta = -26.6$ degrees does not satisfy the equation \\
(ii) Student B squared both sides, going from $\cos \theta = 2\sin \theta$ to $\cos^{2} \theta = 4\sin^{2} \theta$ \\
Squaring can bring in extra solutions: for example, $x = 5$ squared gives $x^{2} = 25$, which also has the solution $x = -5$ \\
In the same way, $\sin \theta = \pm\frac{1}{\sqrt{5}}$ has the extra value $\sin \theta = -\frac{1}{\sqrt{5}}$, which gives $\theta = -26.6$ degrees, and that value does not satisfy the original equation

@q 3
@topic Product and chain rule, show form
@marks 4
@question
$y = x(2x + 1)^{4}$ \\
Use the product rule with $u = x$ and $v = (2x + 1)^{4}$ \\
$u' = 1$ \\
Chain rule for $v$: $v' = 4(2x + 1)^{3} \times 2 = 8(2x + 1)^{3}$ \\
$\frac{dy}{dx} = u'v + uv'$ \\
$= 1 \times (2x + 1)^{4} + x \times 8(2x + 1)^{3}$ \\
$= (2x + 1)^{4} + 8x(2x + 1)^{3}$ \\
Take out the common factor $(2x + 1)^{3}$: \\
$= (2x + 1)^{3}\left\{ (2x + 1) + 8x \right\}$ \\
Collect the terms in the bracket: \\
$= (2x + 1)^{3}(10x + 1)$ \\
Comparing with $(2x + 1)^{n}(Ax + B)$: \\
$n = 3$, $A = 10$ and $B = 1$

@q 4
@topic Composite functions gf and fg
@marks 5
@question
(a) $gf(x) = g(f(x)) = g(e^{x})$ \\
$= 3\ln(e^{x})$ \\
Use $\ln(e^{x}) = x$: \\
$= 3x$ \\
(b) $fg(x) = f(g(x)) = f(3\ln x)$ \\
$= e^{3\ln x}$ \\
Use $3\ln x = \ln(x^{3})$: \\
$= e^{\ln(x^{3})}$ \\
$= x^{3}$ \\
Set $gf(x) = fg(x)$: \\
$3x = x^{3}$ \\
Subtract $3x$ from both sides: \\
$0 = x^{3} - 3x$ \\
Factorise: \\
$x(x^{2} - 3) = 0$ \\
$x = 0$ or $x^{2} = 3$, so $x = \sqrt{3}$ or $x = -\sqrt{3}$ \\
$g(x) = 3\ln x$ is only defined for $x > 0$ \\
So $x = 0$ and $x = -\sqrt{3}$ are not allowed \\
The only real value is $x = \sqrt{3}$

@q 5
@topic Exponential decay, dm/dt = km
@marks 4
@question
(a) Six months is $t = 0.5$ years \\
$m = 25e^{-0.05 \times 0.5}$ \\
$= 25e^{-0.025}$ \\
$= 25 \times 0.97531$ \\
$= 24.38$ \\
$m = 24.4$ g (3 sf) \\
(b) $m = 25e^{-0.05t}$ \\
Differentiate, using $\frac{d}{dt}(e^{kt}) = ke^{kt}$: \\
$\frac{dm}{dt} = 25 \times (-0.05)e^{-0.05t}$ \\
$= -0.05 \times 25e^{-0.05t}$ \\
Replace $25e^{-0.05t}$ by $m$: \\
$\frac{dm}{dt} = -0.05m$ \\
So $k = -0.05$

@q 6
@topic Always, sometimes, never true
@marks 6
@question
(i) Complete the square: \\
$x^{2} - 6x + 10 = (x - 3)^{2} - 9 + 10$ \\
$= (x - 3)^{2} + 1$ \\
$(x - 3)^{2} \ge 0$ for all real $x$ \\
So $(x - 3)^{2} + 1 \ge 1$, which is greater than 0 \\
The statement is always true \\
(ii) If $a > 0$, dividing $ax > b$ by $a$ keeps the inequality: $x > \frac{b}{a}$ \\
If $a < 0$, dividing by a negative number reverses the inequality: $x < \frac{b}{a}$ \\
For example, $a = -3$ and $b = 6$: $-3x > 6$ gives $x < -2$, and $\frac{b}{a} = -2$, so $x > \frac{b}{a}$ is false \\
The statement is sometimes true (when $a > 0$) \\
(iii) Let two consecutive square numbers be $n^{2}$ and $(n + 1)^{2}$ \\
Difference $= (n + 1)^{2} - n^{2}$ \\
$= n^{2} + 2n + 1 - n^{2}$ \\
$= 2n + 1$ \\
$2n$ is even, so $2n + 1$ is odd \\
The statement is always true

@q 7
@topic Binomial expansion, validity
@marks 5
@question
(a) Take out a factor of 4 from inside the root: \\
$\sqrt{4 - x} = \sqrt{4\left( 1 - \frac{x}{4} \right)}$ \\
$= \sqrt{4} \times \left( 1 - \frac{x}{4} \right)^{\frac{1}{2}}$ \\
$= 2\left( 1 - \frac{1}{4}x \right)^{\frac{1}{2}}$ \\
Binomial expansion: $(1 + X)^{n} = 1 + nX + \frac{n(n-1)}{2!}X^{2} + \ldots$ with $n = \frac{1}{2}$ and $X = -\frac{1}{4}x$ \\
Term 2: $nX = \frac{1}{2}\left( -\frac{1}{4}x \right) = -\frac{1}{8}x$ \\
Term 3: $\frac{n(n-1)}{2!}X^{2} = \frac{\frac{1}{2} \times \left( -\frac{1}{2} \right)}{2}\left( -\frac{1}{4}x \right)^{2}$ \\
$\frac{1}{2} \times \left( -\frac{1}{2} \right) = -\frac{1}{4}$ \\
$-\frac{1}{4} \div 2 = -\frac{1}{8}$ \\
$\left( -\frac{1}{4}x \right)^{2} = \frac{1}{16}x^{2}$ \\
Term 3 $= -\frac{1}{8} \times \frac{1}{16}x^{2} = -\frac{1}{128}x^{2}$ \\
$\left( 1 - \frac{1}{4}x \right)^{\frac{1}{2}} = 1 - \frac{1}{8}x - \frac{1}{128}x^{2} + \ldots$ \\
Multiply by 2: \\
$\sqrt{4 - x} = 2 - \frac{2}{8}x - \frac{2}{128}x^{2} + \ldots$ \\
$= 2 - \frac{1}{4}x - \frac{1}{64}x^{2} + \ldots$ \\
So $k = -\frac{1}{64}$ \\
(b) The expansion of $\left( 1 - \frac{1}{4}x \right)^{\frac{1}{2}}$ is valid when $\left| \frac{x}{4} \right| < 1$ \\
$|x| < 4$ \\
$x = 1$ satisfies $|x| < 4$, so the expansion is valid for $x = 1$

@q 8
@topic Straight lines, area of rectangle
@marks 7
@question
(a) $AB$: $5y + 2x = 10$ \\
$A$ is on the $y$-axis, so put $x = 0$: \\
$5y = 10$ \\
$y = 2$ \\
$A = (0, 2)$ \\
Rearrange to find the gradient of $AB$: \\
$5y = -2x + 10$ \\
$y = -\frac{2}{5}x + 2$ \\
Gradient of $AB = -\frac{2}{5}$ \\
$ABCD$ is a rectangle, so $AD$ is perpendicular to $AB$ \\
Gradient of $AD$: $-\frac{2}{5} \times m = -1$ \\
$m = -1 \div \left( -\frac{2}{5} \right) = \frac{5}{2}$ \\
$AD$ passes through $A(0, 2)$, so the intercept is 2: \\
$y = \frac{5}{2}x + 2$ \\
Multiply every term by 2: \\
$2y = 5x + 4$ \\
Subtract $5x$ from both sides: \\
$2y - 5x = 4$ as required \\
(b) $B$ is on the $x$-axis: put $y = 0$ in $5y + 2x = 10$: \\
$2x = 10$ \\
$x = 5$ \\
$B = (5, 0)$ \\
$D$ is on the $x$-axis: put $y = 0$ in $2y - 5x = 4$: \\
$-5x = 4$ \\
$x = -\frac{4}{5}$ \\
$D = \left( -\frac{4}{5}, 0 \right)$ \\
$AB = \sqrt{(5 - 0)^{2} + (0 - 2)^{2}}$ \\
$= \sqrt{25 + 4}$ \\
$= \sqrt{29}$ \\
$AD = \sqrt{\left( -\frac{4}{5} - 0 \right)^{2} + (0 - 2)^{2}}$ \\
$= \sqrt{\frac{16}{25} + 4}$ \\
$= \sqrt{\frac{16}{25} + \frac{100}{25}}$ \\
$= \sqrt{\frac{116}{25}}$ \\
$= \frac{\sqrt{116}}{5}$ \\
$= \frac{2\sqrt{29}}{5}$ \\
Area of the rectangle $= AB \times AD$ \\
$= \sqrt{29} \times \frac{2\sqrt{29}}{5}$ \\
$= \frac{2 \times 29}{5}$ \\
$= \frac{58}{5}$ \\
$= 11.6$

@q 9
@topic Definite integral, quadratic in A
@marks 5
@question
Write $\sqrt{x} = x^{\frac{1}{2}}$: \\
$\int_{1}^{4} \left( 3x^{\frac{1}{2}} + A \right) dx$ \\
Integrate each term ($A$ is a constant, so $\int A \, dx = Ax$): \\
$\int 3x^{\frac{1}{2}} \, dx = 3 \times \frac{x^{\frac{3}{2}}}{\frac{3}{2}} = 2x^{\frac{3}{2}}$ \\
$= \left[ 2x^{\frac{3}{2}} + Ax \right]_{1}^{4}$ \\
Upper limit $x = 4$: $2 \times 4^{\frac{3}{2}} + 4A = 2 \times 8 + 4A = 16 + 4A$ \\
Lower limit $x = 1$: $2 \times 1^{\frac{3}{2}} + A = 2 + A$ \\
Subtract: \\
$(16 + 4A) - (2 + A) = 16 + 4A - 2 - A$ \\
$= 14 + 3A$ \\
Set equal to $2A^{2}$: \\
$14 + 3A = 2A^{2}$ \\
Rearrange to one side: \\
$0 = 2A^{2} - 3A - 14$ \\
$2A^{2} - 3A - 14 = 0$ \\
Discriminant $= b^{2} - 4ac$ with $a = 2$, $b = -3$, $c = -14$: \\
$= (-3)^{2} - 4(2)(-14)$ \\
$= 9 + 112$ \\
$= 121$ \\
The discriminant is positive, so there are two distinct real roots \\
So there are exactly two possible values for $A$ \\
(Check: $2A^{2} - 3A - 14 = (2A - 7)(A + 2) = 0$ gives $A = \frac{7}{2}$ or $A = -2$.)

@q 10
@topic Geometric series, sum to infinity
@marks 4
@question
$S_{\infty} = \frac{a}{1 - r}$ and $S_{6} = \frac{a(1 - r^{6})}{1 - r}$ \\
Substitute into $S_{\infty} = \frac{8}{7}S_{6}$: \\
$\frac{a}{1 - r} = \frac{8}{7} \times \frac{a(1 - r^{6})}{1 - r}$ \\
Divide both sides by $\frac{a}{1 - r}$: \\
$1 = \frac{8}{7}(1 - r^{6})$ \\
Multiply both sides by $\frac{7}{8}$: \\
$\frac{7}{8} = 1 - r^{6}$ \\
Rearrange: \\
$r^{6} = 1 - \frac{7}{8}$ \\
$r^{6} = \frac{1}{8}$ \\
Take the 6th root of both sides (positive and negative): \\
$r = \pm\left( \frac{1}{8} \right)^{\frac{1}{6}}$ \\
Write $8 = 2^{3}$: \\
$r = \pm\left( \frac{1}{2^{3}} \right)^{\frac{1}{6}}$ \\
$= \pm\frac{1}{2^{\frac{3}{6}}}$ \\
$= \pm\frac{1}{2^{\frac{1}{2}}}$ \\
$= \pm\frac{1}{\sqrt{2}}$ \\
So $r = \pm\frac{1}{\sqrt{k}}$ with $k = 2$

@q 11
@topic Modulus function, range, equation
@marks 6
@question
(a) $f(x) = 2|3 - x| + 5$ \\
$|3 - x| \ge 0$ for all $x$, with the value 0 at $x = 3$ \\
So $2|3 - x| \ge 0$, and $2|3 - x| + 5 \ge 5$ \\
Range of $f$: $f(x) \ge 5$ \\
(b) $f(x) = \frac{1}{2}x + 30$ \\
For $x \ge 3$: $|3 - x| = x - 3$ \\
$f(x) = 2(x - 3) + 5$ \\
$= 2x - 6 + 5$ \\
$= 2x - 1$ \\
$2x - 1 = \frac{1}{2}x + 30$ \\
Subtract $\frac{1}{2}x$ from both sides: \\
$\frac{3}{2}x - 1 = 30$ \\
Add 1 to both sides: \\
$\frac{3}{2}x = 31$ \\
Multiply both sides by $\frac{2}{3}$: \\
$x = \frac{62}{3}$ \\
This satisfies $x \ge 3$ \\
For $0 \le x < 3$: $f(x) = 2(3 - x) + 5 = 11 - 2x$ \\
$11 - 2x = \frac{1}{2}x + 30$ gives $-\frac{5}{2}x = 19$, so $x = -7.6$, which is not in the domain, so it is rejected \\
$x = \frac{62}{3}$ only \\
(c) For $0 \le x \le 3$: $f(x) = 11 - 2x$, which decreases from $f(0) = 11$ down to $f(3) = 5$ \\
For $x \ge 3$: $f(x) = 2x - 1$, which increases from $f(3) = 5$ without limit \\
The line $y = k$ crosses both branches, giving two roots, when $k$ is above the minimum 5 and no more than $f(0) = 11$ \\
At $k = 5$ there is one root (the vertex), and for $k > 11$ there is one root (on the right branch only) \\
$\{ k : k \in \mathbb{R}, 5 < k \le 11 \}$

@q 12
@topic Trig equation, quadratic in sin x
@marks 8
@question
(a) $3\sin^{2} x + \sin x + 8 = 9\cos^{2} x$ \\
Use $\cos^{2} x = 1 - \sin^{2} x$: \\
$3\sin^{2} x + \sin x + 8 = 9(1 - \sin^{2} x)$ \\
Expand the bracket: \\
$3\sin^{2} x + \sin x + 8 = 9 - 9\sin^{2} x$ \\
Add $9\sin^{2} x$ to both sides and subtract 9 from both sides: \\
$3\sin^{2} x + 9\sin^{2} x + \sin x + 8 - 9 = 0$ \\
$12\sin^{2} x + \sin x - 1 = 0$ \\
Factorise: the numbers with product $12 \times (-1) = -12$ and sum 1 are 4 and $-3$ \\
$12\sin^{2} x + 4\sin x - 3\sin x - 1 = 0$ \\
$4\sin x(3\sin x + 1) - 1(3\sin x + 1) = 0$ \\
$(4\sin x - 1)(3\sin x + 1) = 0$ \\
$\sin x = \frac{1}{4}$ or $\sin x = -\frac{1}{3}$ \\
For $\sin x = \frac{1}{4}$: \\
$x = \sin^{-1}\left( \frac{1}{4} \right) = 14.48$ degrees \\
The other solution is $x = 180 - 14.48 = 165.52$ degrees \\
For $\sin x = -\frac{1}{3}$: \\
$x = \sin^{-1}\left( -\frac{1}{3} \right) = -19.47$ degrees \\
The other solution is $x = -180 - (-19.47) = -160.53$ degrees \\
All four are in the range $-180 \le x < 180$ \\
$x = 14.48$, $165.52$, $-19.47$, $-160.53$ degrees (2 dp) \\
(b) Let $\phi = 2\theta - 30$ degrees \\
The equation becomes $3\sin^{2}\phi + \sin\phi + 8 = 9\cos^{2}\phi$, which is the equation from (a) \\
So $\phi = 14.48$, $165.52$, $-19.47$, $-160.53$ degrees, or any of these plus a multiple of 360 degrees \\
$\theta = \frac{\phi + 30}{2}$ \\
For $\theta > 0$ we need $\phi > -30$ degrees \\
The smallest allowed value of $\phi$ is $-19.47$ degrees (as $-160.53$ is too small, and $-160.53 + 360 = 199.47$ is larger) \\
$\theta = \frac{-19.47 + 30}{2}$ \\
$= \frac{10.53}{2}$ \\
$= 5.26$ degrees \\
Smallest positive solution: $\theta = 5.26$ degrees (2 dp)

@q 13
@topic R cos form, Ferris wheel model
@marks 9
@question
(a) Let $10\cos \theta - 3\sin \theta = R\cos(\theta + \alpha)$ \\
Expand the right-hand side using $\cos(A + B) = \cos A \cos B - \sin A \sin B$: \\
$R\cos(\theta + \alpha) = R\cos \theta \cos \alpha - R\sin \theta \sin \alpha$ \\
Compare the coefficients of $\cos \theta$: $R\cos \alpha = 10$ \\
Compare the coefficients of $\sin \theta$: $R\sin \alpha = 3$ \\
Square and add: \\
$R^{2}\cos^{2}\alpha + R^{2}\sin^{2}\alpha = 10^{2} + 3^{2}$ \\
$R^{2} = 109$ \\
$R = \sqrt{109}$ \\
Divide $R\sin \alpha = 3$ by $R\cos \alpha = 10$: \\
$\tan \alpha = \frac{3}{10}$ \\
$\alpha = \tan^{-1}\left( \frac{3}{10} \right) = 16.70$ degrees (2 dp) \\
$10\cos \theta - 3\sin \theta = \sqrt{109}\cos(\theta + 16.70)$ \\
(b)(i) $H = a - 10\cos(80t) + 3\sin(80t)$ \\
Write this as $H = a - (10\cos(80t) - 3\sin(80t))$ \\
Use (a) with $\theta = 80t$: \\
$H = a - \sqrt{109}\cos(80t + 16.70)$ \\
At the start, $t = 0$ and $H = 1$: \\
$1 = a - 10\cos 0 + 3\sin 0$ \\
$1 = a - 10 + 0$ \\
$a = 11$ \\
$H = 11 - 10\cos(80t) + 3\sin(80t)$, or $H = 11 - \sqrt{109}\cos(80t + 16.70)$ \\
(ii) $H$ is greatest when $\cos(80t + 16.70) = -1$ \\
$H_{max} = 11 - \sqrt{109}(-1)$ \\
$= 11 + \sqrt{109}$ \\
$= 11 + 10.440$ \\
$= 21.44$ m \\
(c) The maximum height happens when $80t + 16.70 = 180$ (first cycle) \\
The next maximum is 360 degrees later, so $80t + 16.70 = 540$ (second cycle) \\
Subtract 16.70 from both sides: \\
$80t = 523.3$ \\
Divide both sides by 80: \\
$t = 6.5413$ minutes \\
$0.5413 \times 60 = 32.5$ seconds \\
$t = 6$ minutes 32 seconds (nearest second) \\
(d) To make the wheel turn faster, increase the 80 in the equation, for example to 90, as this makes the angle $80t$ change faster

@q 14
@topic Optimisation, minimum surface area
@marks 9
@question
(a) The volume is 500 ml $= 500$ cm$^3$ \\
Volume of a cylinder $= \pi r^{2}h$ \\
$\pi r^{2}h = 500$ \\
Divide both sides by $\pi r^{2}$: \\
$h = \frac{500}{\pi r^{2}}$ \\
Surface area = two circular ends + the curved surface: \\
$S = 2\pi r^{2} + 2\pi rh$ \\
Substitute for $h$: \\
$S = 2\pi r^{2} + 2\pi r \times \frac{500}{\pi r^{2}}$ \\
Cancel $\pi$ and one $r$: \\
$S = 2\pi r^{2} + \frac{2 \times 500}{r}$ \\
$S = 2\pi r^{2} + \frac{1000}{r}$ as required \\
(b) Write $\frac{1000}{r} = 1000r^{-1}$: \\
$S = 2\pi r^{2} + 1000r^{-1}$ \\
Differentiate: \\
$\frac{dS}{dr} = 4\pi r - 1000r^{-2}$ \\
$\frac{dS}{dr} = 4\pi r - \frac{1000}{r^{2}}$ \\
Set equal to zero: \\
$4\pi r - \frac{1000}{r^{2}} = 0$ \\
$4\pi r = \frac{1000}{r^{2}}$ \\
Multiply both sides by $r^{2}$: \\
$4\pi r^{3} = 1000$ \\
Divide both sides by $4\pi$: \\
$r^{3} = \frac{1000}{4\pi} = \frac{250}{\pi} = 79.577$ \\
Take the cube root: \\
$r = 4.30$ cm (3 sf) \\
Check it is a minimum: $\frac{d^{2}S}{dr^{2}} = 4\pi + \frac{2000}{r^{3}} > 0$ \\
Find $h$: \\
$h = \frac{500}{\pi r^{2}}$ \\
$= \frac{500}{\pi \times 18.50}$ \\
$= \frac{500}{58.12}$ \\
$= 8.60$ cm (3 sf) \\
(The height is twice the radius: $h = 2r$.) \\
(c) With $r = 4.30$ and $h = 8.60$, the height equals the width (diameter) of the can, so it would be a squat, wide can \\
Real drinks cans are taller than they are wide, so it would be awkward to hold and drink from, and hard to stack with other cans

@q 15
@topic Area between curve and tangent
@marks 10
@question
$y = 5x^{\frac{3}{2}} - 9x + 11$ \\
Differentiate each term: \\
$5x^{\frac{3}{2}} \to 5 \times \frac{3}{2}x^{\frac{1}{2}} = \frac{15}{2}x^{\frac{1}{2}}$ \\
$-9x \to -9$ \\
$11 \to 0$ \\
$\frac{dy}{dx} = \frac{15}{2}x^{\frac{1}{2}} - 9$ \\
The gradient at $P$ is the value at $x = 4$: \\
$\frac{dy}{dx} = \frac{15}{2}\sqrt{4} - 9$ \\
$= \frac{15}{2} \times 2 - 9$ \\
$= 15 - 9$ \\
$= 6$ \\
The tangent $l$ passes through $P(4, 15)$ with gradient 6: \\
$y - 15 = 6(x - 4)$ \\
Expand the bracket: \\
$y - 15 = 6x - 24$ \\
Add 15 to both sides: \\
$y = 6x - 9$ \\
The region $R$ is between the curve (above) and the line (below), from the $y$-axis ($x = 0$) to $P$ ($x = 4$) \\
Area of $R = \int_{0}^{4} \left[ \left( 5x^{\frac{3}{2}} - 9x + 11 \right) - (6x - 9) \right] dx$ \\
Subtract the line: $-9x - 6x = -15x$ and $11 + 9 = 20$ \\
$= \int_{0}^{4} \left( 5x^{\frac{3}{2}} - 15x + 20 \right) dx$ \\
Integrate each term: \\
$\int 5x^{\frac{3}{2}} \, dx = 5 \times \frac{x^{\frac{5}{2}}}{\frac{5}{2}} = 2x^{\frac{5}{2}}$ \\
$\int -15x \, dx = -\frac{15}{2}x^{2}$ \\
$\int 20 \, dx = 20x$ \\
$= \left[ 2x^{\frac{5}{2}} - \frac{15}{2}x^{2} + 20x \right]_{0}^{4}$ \\
Upper limit $x = 4$: $4^{\frac{5}{2}} = (\sqrt{4})^{5} = 2^{5} = 32$ \\
$2 \times 32 - \frac{15}{2} \times 16 + 20 \times 4$ \\
$= 64 - 120 + 80$ \\
$= 24$ \\
Lower limit $x = 0$: every term is 0 \\
Area of $R = 24 - 0$ \\
$= 24$ as required

@q 16
@topic Partial fractions, DE, meerkats
@marks 12
@question
(a) $\frac{1}{P(11 - 2P)} = \frac{A}{P} + \frac{B}{11 - 2P}$ \\
Multiply both sides by $P(11 - 2P)$: \\
$1 = A(11 - 2P) + BP$ \\
Let $P = 0$: $1 = 11A$, so $A = \frac{1}{11}$ \\
Let $P = \frac{11}{2}$: $1 = \frac{11}{2}B$, so $B = \frac{2}{11}$ \\
$\frac{1}{P(11 - 2P)} = \frac{\frac{1}{11}}{P} + \frac{\frac{2}{11}}{11 - 2P}$ \\
(b) $\frac{dP}{dt} = \frac{1}{22}P(11 - 2P)$ \\
Separate the variables: \\
$\frac{22}{P(11 - 2P)} \, dP = dt$ \\
Use (a): \\
$22 \times \frac{1}{P(11 - 2P)} = 22 \times \frac{\frac{1}{11}}{P} + 22 \times \frac{\frac{2}{11}}{11 - 2P}$ \\
$= \frac{2}{P} + \frac{4}{11 - 2P}$ \\
Integrate both sides: \\
$\int \left( \frac{2}{P} + \frac{4}{11 - 2P} \right) dP = \int 1 \, dt$ \\
$\int \frac{2}{P} \, dP = 2\ln P$ \\
$\int \frac{4}{11 - 2P} \, dP = -2\ln(11 - 2P)$ \\
$2\ln P - 2\ln(11 - 2P) = t + c$ \\
At the start, $t = 0$ and $P = 1$ (1000 meerkats is 1 thousand): \\
$2\ln 1 - 2\ln(11 - 2) = 0 + c$ \\
$0 - 2\ln 9 = c$ \\
$c = -2\ln 9$ \\
$2\ln P - 2\ln(11 - 2P) = t - 2\ln 9$ \\
The population doubles when $P = 2$: \\
$2\ln 2 - 2\ln(11 - 4) = t - 2\ln 9$ \\
$2\ln 2 - 2\ln 7 = t - 2\ln 9$ \\
Add $2\ln 9$ to both sides: \\
$t = 2\ln 2 - 2\ln 7 + 2\ln 9$ \\
Factorise by 2 and use the log laws: \\
$= 2(\ln 2 + \ln 9 - \ln 7)$ \\
$= 2\ln\left( \frac{2 \times 9}{7} \right)$ \\
$= 2\ln\frac{18}{7}$ \\
$= 2 \times 0.9445$ \\
$= 1.89$ years (3 sf) \\
(c) Start from $2\ln P - 2\ln(11 - 2P) = t - 2\ln 9$ \\
Divide every term by 2: \\
$\ln P - \ln(11 - 2P) = \frac{t}{2} - \ln 9$ \\
Add $\ln 9$ to both sides: \\
$\ln P + \ln 9 - \ln(11 - 2P) = \frac{t}{2}$ \\
Combine the logs: \\
$\ln\left( \frac{9P}{11 - 2P} \right) = \frac{t}{2}$ \\
Raise $e$ to the power of both sides: \\
$\frac{9P}{11 - 2P} = e^{\frac{t}{2}}$ \\
Multiply both sides by $(11 - 2P)$: \\
$9P = (11 - 2P)e^{\frac{t}{2}}$ \\
Expand the bracket: \\
$9P = 11e^{\frac{t}{2}} - 2Pe^{\frac{t}{2}}$ \\
Get the terms in $P$ together: \\
$9P + 2Pe^{\frac{t}{2}} = 11e^{\frac{t}{2}}$ \\
Factorise: \\
$P\left( 9 + 2e^{\frac{t}{2}} \right) = 11e^{\frac{t}{2}}$ \\
$P = \frac{11e^{\frac{t}{2}}}{9 + 2e^{\frac{t}{2}}}$ \\
Divide the top and the bottom by $e^{\frac{t}{2}}$: \\
$P = \frac{11}{9e^{-\frac{t}{2}} + 2}$ \\
$P = \frac{11}{2 + 9e^{-\frac{1}{2}t}}$ \\
So $A = 11$, $B = 2$ and $C = 9$
