@paper P2 Shadow June 2022

@q 1
@topic Modulus equation |5 - 4x| = 2 + x
@marks 4
@question
The modulus means we split into two cases \\
Case 1: $5 - 4x \geq 0$, so $|5 - 4x| = 5 - 4x$ \\
$5 - 4x = 2 + x$ \\
Add $4x$ to both sides: \\
$5 = 2 + 5x$ \\
Subtract 2: \\
$3 = 5x$ \\
$x = \frac{3}{5}$ \\
Check: $5 - 4\left( \frac{3}{5} \right) = 2.6$, which is positive, so the case is valid \\
Case 2: $5 - 4x < 0$, so $|5 - 4x| = -(5 - 4x) = 4x - 5$ \\
$4x - 5 = 2 + x$ \\
Subtract $x$ and add 5: \\
$3x = 7$ \\
$x = \frac{7}{3}$ \\
Check: $4\left( \frac{7}{3} \right) - 5 = \frac{13}{3}$, which is positive, so the case is valid \\
Check both in the original equation: \\
$x = \frac{3}{5}$: left side $|5 - 2.4| = 2.6$ and right side $2 + 0.6 = 2.6$ \\
$x = \frac{7}{3}$: left side $\left| 5 - \frac{28}{3} \right| = \frac{13}{3}$ and right side $2 + \frac{7}{3} = \frac{13}{3}$ \\
$x = \frac{3}{5}$ or $x = \frac{7}{3}$

@q 2
@topic Sketch 6^x, solve 6^x = 200
@marks 4
@question
(a) $y = 6^{x}$ is an exponential growth curve \\
When $x = 0$, $y = 6^{0} = 1$, so it crosses the $y$ axis at $(0, 1)$ \\
$6^{x}$ is always positive, so the curve never meets the $x$ axis \\
As $x$ gets very negative, $y$ gets close to 0 (the $x$ axis is an asymptote) \\
As $x$ increases, $y$ rises more and more steeply \\
(Diagram: a curve rising steeply from close to the $x$ axis on the left, through $(0, 1)$, and up to the right) \\
(b) Take logs of both sides of $6^{x} = 200$: \\
$\ln 6^{x} = \ln 200$ \\
Use the power law: \\
$x\ln 6 = \ln 200$ \\
Divide by $\ln 6$: \\
$x = \frac{\ln 200}{\ln 6}$ \\
$\ln 200 = 5.29832$ \\
$\ln 6 = 1.79176$ \\
$x = \frac{5.29832}{1.79176}$ \\
$x = 2.95705$ \\
$x = 2.957$ to 3 decimal places

@q 3
@topic Periodic sequence order 3, sum
@marks 4
@question
(a) $a_{1} = 3$ \\
$a_{2} = \frac{3 - 3}{3 - 2} = \frac{0}{1} = 0$ \\
$a_{3} = \frac{0 - 3}{0 - 2} = \frac{-3}{-2} = 1.5$ \\
$a_{4} = \frac{1.5 - 3}{1.5 - 2} = \frac{-1.5}{-0.5} = 3$ \\
$a_{4} = a_{1}$, and each term depends only on the one before it \\
So the sequence repeats $3, 0, 1.5, 3, 0, 1.5, \ldots$ \\
The sequence is periodic with order 3 \\
(b) One full cycle adds up to $3 + 0 + 1.5 = 4.5$ \\
$85 = 3 \times 28 + 1$, so there are 28 full cycles (84 terms) and one more term \\
The extra term is $a_{85} = a_{1} = 3$ \\
$\sum_{n=1}^{85} a_{n} = 28 \times 4.5 + 3$ \\
$= 126 + 3$ \\
$= 129$

@q 4
@topic Differentiation from first principles
@marks 3
@question
$f(x) = -5x^{2}$ \\
$f(x + h) = -5(x + h)^{2}$ \\
Expand the bracket: $(x + h)^{2} = x^{2} + 2xh + h^{2}$ \\
$f(x + h) = -5x^{2} - 10xh - 5h^{2}$ \\
Use the definition of the gradient: $\frac{f(x + h) - f(x)}{h}$ \\
$= \frac{-5x^{2} - 10xh - 5h^{2} - (-5x^{2})}{h}$ \\
The $-5x^{2}$ terms cancel: \\
$= \frac{-10xh - 5h^{2}}{h}$ \\
Divide the top by $h$: \\
$= -10x - 5h$ \\
As $h \to 0$ the term $-5h$ goes to 0: \\
$\frac{dy}{dx} = \lim_{h \to 0}(-10x - 5h)$ \\
$\frac{dy}{dx} = -10x$ as required

@q 5
@topic Trapezium rule on log2 table, scaling
@marks 6
@question
(a) There are 5 values of $y$, so 4 strips, each of width $h = 1.25$ \\
Check: $2.25 - 1 = 1.25$ \\
Trapezium rule: $\frac{h}{2}\left\{ y_{0} + y_{4} + 2(y_{1} + y_{2} + y_{3}) \right\}$ \\
Add the first and last: $1.58 + 4.17 = 5.75$ \\
Add the middle ones: $3.39 + 3.83 + 2.75 = 9.97$ \\
Double them: $2 \times 9.97 = 19.94$ \\
Total in the brackets: $5.75 + 19.94 = 25.69$ \\
$\frac{1.25}{2} \times 25.69$ \\
$= 0.625 \times 25.69$ \\
$= 16.056$ \\
The estimate is 16.1 \\
(b)(i) Use the power law $\log a^{n} = n\log a$: \\
$\log_{2}(3x)^{8} = 8\log_{2} 3x$ \\
$\int_{1}^{6} \log_{2}(3x)^{8} dx = 8\int_{1}^{6} \log_{2} 3x \, dx$ \\
$\approx 8 \times 16.056$ \\
$\approx 128.45$ \\
The estimate is about 128 \\
(ii) Write $48x$ as $16 \times 3x$: \\
$\log_{2} 48x = \log_{2}(16 \times 3x)$ \\
Use $\log (ab) = \log a + \log b$: \\
$= \log_{2} 16 + \log_{2} 3x$ \\
$\log_{2} 16 = 4$, since $2^{4} = 16$ \\
$\log_{2} 48x = 4 + \log_{2} 3x$ \\
$\int_{1}^{6} \log_{2} 48x \, dx = \int_{1}^{6} 4 \, dx + \int_{1}^{6} \log_{2} 3x \, dx$ \\
$\int_{1}^{6} 4 \, dx = \left[ 4x \right]_{1}^{6} = 24 - 4 = 20$ \\
$\approx 20 + 16.056$ \\
$\approx 36.056$ \\
The estimate is about 36.1

@q 6
@topic Local min, sign change, Newton-Raphson
@marks 7
@question
(a) Differentiate $f(x) = 4\cos (2x - 3) - 5x + 15$ \\
$4\cos (2x - 3) \to 4 \times (-\sin (2x - 3)) \times 2 = -8\sin (2x - 3)$ \\
$-5x \to -5$ \\
$f'(x) = -8\sin (2x - 3) - 5$ \\
Stationary points are where $f'(x) = 0$: \\
$-8\sin (2x - 3) - 5 = 0$ \\
Add 5 and divide by $-8$: \\
$\sin (2x - 3) = -\frac{5}{8}$ \\
$\sin^{-1}(-0.625) = -0.67513$ \\
Sine is also negative in the third quadrant: $2x - 3 = \pi + 0.67513 = 3.81672$ \\
Taking $2x - 3 = 3.81672$ and adding 3: \\
$2x = 6.81672$ \\
$x = 3.40836$ \\
Check that this is a minimum: $f''(x) = -16\cos (2x - 3)$ \\
At $x = 3.408$, $\cos (3.8167) = -0.7806$, so $f''(x) = 12.5$, which is positive \\
So it is a minimum, and $f(3.408) = -5.16$, which is below the $x$ axis, as $P$ is in the sketch \\
(The other minimum, at $x = 0.267$, is above the $x$ axis near the $y$ axis. $P$ is the minimum after the curve has crossed the $x$ axis at $x = a$) \\
The $x$ coordinate of $P$ is 3.41 \\
(b) $f(2) = 7.161$, which is positive \\
$f(3) = -3.960$, which is negative \\
$f(x)$ is continuous (it is made of a cosine and a straight line) \\
So there is a change of sign between $x = 2$ and $x = 3$, and $a$ lies in the interval $[2, 3]$ \\
(c) Newton-Raphson: $x_{1} = x_{0} - \frac{f(x_{0})}{f'(x_{0})}$ with $x_{0} = 2$ \\
$f(2) = 4\cos (4 - 3) - 5(2) + 15$ \\
$= 4\cos 1 + 5$ \\
$= 7.1612$ \\
$f'(2) = -8\sin (4 - 3) - 5$ \\
$= -8\sin 1 - 5$ \\
$= -11.7318$ \\
$x_{1} = 2 - \frac{7.1612}{-11.7318}$ \\
$x_{1} = 2 + 0.6104$ \\
$x_{1} = 2.6104$ \\
$x_{1} = 2.61$ to 3 significant figures

@q 7
@topic Binomial expansion of root, over/under
@marks 5
@question
(a) Write the root as a power and take 9 out of the bracket: \\
$\sqrt{9 - 4x} = (9 - 4x)^{\frac{1}{2}}$ \\
$9 - 4x = 9\left( 1 - \frac{4x}{9} \right)$ \\
$(9 - 4x)^{\frac{1}{2}} = 9^{\frac{1}{2}}\left( 1 - \frac{4x}{9} \right)^{\frac{1}{2}}$ \\
$9^{\frac{1}{2}} = 3$ \\
Binomial expansion: $(1 + y)^{n} = 1 + ny + \frac{n(n - 1)}{2!}y^{2} + \frac{n(n - 1)(n - 2)}{3!}y^{3} + \ldots$ \\
Here $n = \frac{1}{2}$ and $y = -\frac{4x}{9}$ \\
Second term: $\frac{1}{2} \times \left( -\frac{4x}{9} \right) = -\frac{2x}{9}$ \\
Third term: $\frac{n(n - 1)}{2!} = \frac{\frac{1}{2} \times \left( -\frac{1}{2} \right)}{2} = -\frac{1}{8}$ \\
$y^{2} = \frac{16x^{2}}{81}$ \\
$-\frac{1}{8} \times \frac{16x^{2}}{81} = -\frac{2x^{2}}{81}$ \\
Fourth term: $\frac{n(n - 1)(n - 2)}{3!} = \frac{\frac{1}{2} \times \left( -\frac{1}{2} \right) \times \left( -\frac{3}{2} \right)}{6} = \frac{\frac{3}{8}}{6} = \frac{1}{16}$ \\
$y^{3} = -\frac{64x^{3}}{729}$ \\
$\frac{1}{16} \times \left( -\frac{64x^{3}}{729} \right) = -\frac{4x^{3}}{729}$ \\
$\left( 1 - \frac{4x}{9} \right)^{\frac{1}{2}} = 1 - \frac{2x}{9} - \frac{2x^{2}}{81} - \frac{4x^{3}}{729} + \ldots$ \\
Multiply every term by 3: \\
$\sqrt{9 - 4x} = 3 - \frac{6x}{9} - \frac{6x^{2}}{81} - \frac{12x^{3}}{729} + \ldots$ \\
Simplify each fraction: \\
$\sqrt{9 - 4x} = 3 - \frac{2x}{3} - \frac{2x^{2}}{27} - \frac{4x^{3}}{243} + \ldots$ \\
(b) At $x = 1.5$: $9 - 4(1.5) = 3$, so the expansion is giving $\sqrt{3}$ \\
After the first term, every term of the expansion is negative when $x > 0$ \\
The student's four terms leave out the further terms, which are also negative \\
So the approximation is bigger than the true value: it is an overestimate

@q 8
@topic Exact area under curve with root x
@marks 6
@question
Expand the numerator: $(x - 2)(x - 9) = x^{2} - 11x + 18$ \\
$y = \frac{4(x^{2} - 11x + 18)}{9\sqrt{x}}$ \\
Divide each term by $x^{\frac{1}{2}}$: \\
$y = \frac{4}{9}\left( x^{\frac{3}{2}} - 11x^{\frac{1}{2}} + 18x^{-\frac{1}{2}} \right)$ \\
Multiply out the $\frac{4}{9}$: \\
$y = \frac{4}{9}x^{\frac{3}{2}} - \frac{44}{9}x^{\frac{1}{2}} + 8x^{-\frac{1}{2}}$ \\
The curve meets the $x$ axis at $x = 2$ and $x = 9$, and $R$ is between them, below the axis \\
Integrate each term (add 1 to the power, divide by the new power): \\
$\frac{4}{9}x^{\frac{3}{2}} \to \frac{4}{9} \times \frac{2}{5}x^{\frac{5}{2}} = \frac{8}{45}x^{\frac{5}{2}}$ \\
$-\frac{44}{9}x^{\frac{1}{2}} \to -\frac{44}{9} \times \frac{2}{3}x^{\frac{3}{2}} = -\frac{88}{27}x^{\frac{3}{2}}$ \\
$8x^{-\frac{1}{2}} \to 8 \times 2x^{\frac{1}{2}} = 16x^{\frac{1}{2}}$ \\
$F(x) = \frac{8}{45}x^{\frac{5}{2}} - \frac{88}{27}x^{\frac{3}{2}} + 16x^{\frac{1}{2}}$ \\
Upper limit $x = 9$: $9^{\frac{5}{2}} = 243$, $9^{\frac{3}{2}} = 27$, $9^{\frac{1}{2}} = 3$ \\
$F(9) = \frac{8}{45} \times 243 - \frac{88}{27} \times 27 + 16 \times 3$ \\
$= \frac{1944}{45} - 88 + 48$ \\
$= \frac{216}{5} - 40$ \\
$= \frac{216}{5} - \frac{200}{5}$ \\
$F(9) = \frac{16}{5}$ \\
Lower limit $x = 2$: $2^{\frac{5}{2}} = 4\sqrt{2}$, $2^{\frac{3}{2}} = 2\sqrt{2}$, $2^{\frac{1}{2}} = \sqrt{2}$ \\
$F(2) = \frac{8}{45} \times 4\sqrt{2} - \frac{88}{27} \times 2\sqrt{2} + 16\sqrt{2}$ \\
$= \frac{32}{45}\sqrt{2} - \frac{176}{27}\sqrt{2} + 16\sqrt{2}$ \\
Write over the denominator 135: \\
$= \frac{96}{135}\sqrt{2} - \frac{880}{135}\sqrt{2} + \frac{2160}{135}\sqrt{2}$ \\
$F(2) = \frac{1376}{135}\sqrt{2}$ \\
$\int_{2}^{9} y \, dx = F(9) - F(2)$ \\
$= \frac{16}{5} - \frac{1376}{135}\sqrt{2}$ \\
$= -11.21$ \\
$R$ is below the $x$ axis, so the integral is negative and the area is the opposite: \\
Area of $R = \frac{1376}{135}\sqrt{2} - \frac{16}{5}$ \\
So $a = \frac{1376}{135}$ and $b = -\frac{16}{5}$

@q 9
@topic Wheel arrow height model, cos form
@marks 5
@question
(a) The wheel has diameter 40 cm, so the arrow tip is between 0 cm (touching the floor) and 40 cm (at the top) \\
The largest value of $h$ is 40, so $A = 40$ \\
One revolution takes 2 seconds and gives one arch of the graph \\
$\left| \cos (bt) \right|$ repeats every $\frac{180}{b}$ seconds \\
$\frac{180}{b} = 2$ \\
$b = 90$ \\
$h = \left| 40\cos \left( (90t + \alpha) \text{ degrees} \right) \right|$ \\
At $t = 0$ the arrow tip is 35 cm above the floor: \\
$35 = 40\cos \alpha$ \\
Divide by 40: \\
$\cos \alpha = \frac{35}{40} = 0.875$ \\
$\alpha = \cos^{-1}(0.875)$ \\
$\alpha = 28.955$ \\
$\alpha = 29.0$ to 3 significant figures \\
$h = \left| 40\cos \left( (90t + 29.0) \text{ degrees} \right) \right|$ \\
(Check: at $t = 2$, $90 \times 2 + 29 = 209$ and $40\cos 209 = -35$, so $h = 35$ again after one revolution) \\
(b) The arrow points straight down at $t = 0$, so the tip is on the floor and $h = 0$ \\
$0 = 40\cos \alpha$, so $\cos \alpha = 0$ \\
$\alpha = 90$ is one choice \\
$h = \left| 40\cos \left( (90t + 90) \text{ degrees} \right) \right|$ \\
So $A = 40$, $b = 90$, $\alpha = 90$ (or any odd multiple of 90)

@q 10
@topic Inverse, partial fraction form, ranges
@marks 8
@question
(a) $f^{-1}\left( \frac{5}{3} \right)$ is the value of $x$ with $f(x) = \frac{5}{3}$ \\
$\frac{9x + 8}{3x + 5} = \frac{5}{3}$ \\
Cross multiply: \\
$3(9x + 8) = 5(3x + 5)$ \\
Expand both brackets: \\
$27x + 24 = 15x + 25$ \\
Subtract $15x$ and 24 from both sides: \\
$12x = 1$ \\
$x = \frac{1}{12}$ \\
$f^{-1}\left( \frac{5}{3} \right) = \frac{1}{12}$ \\
(b) Write the top in terms of $3(3x + 5)$: \\
$3(3x + 5) = 9x + 15$ \\
$9x + 8 = 9x + 15 - 7$ \\
$9x + 8 = 3(3x + 5) - 7$ \\
$f(x) = \frac{3(3x + 5) - 7}{3x + 5}$ \\
Split into two fractions: \\
$f(x) = \frac{3(3x + 5)}{3x + 5} - \frac{7}{3x + 5}$ \\
$f(x) = 3 - \frac{7}{3x + 5}$ \\
So $A = 3$ and $B = -7$ \\
(c) $g(x) = 9 - x^{2}$ for $0 \leq x \leq 3$ \\
$g(0) = 9$ and $g(3) = 9 - 9 = 0$ \\
$g$ decreases from 9 to 0, so its range is $0 \leq g(x) \leq 9$ \\
The domain of $g^{-1}$ is the range of $g$, and the range of $g^{-1}$ is the domain of $g$ \\
Range of $g^{-1}$: $0 \leq g^{-1}(x) \leq 3$ \\
(d) $fg^{-1}$ means do $g^{-1}$ first, then $f$ \\
$g^{-1}$ gives outputs between 0 and 3, which are the inputs to $f$ \\
$f(x) = 3 - \frac{7}{3x + 5}$ is increasing, because as $x$ increases $\frac{7}{3x + 5}$ decreases \\
So the smallest value is at $x = 0$ and the largest at $x = 3$ \\
$f(0) = \frac{9(0) + 8}{3(0) + 5} = \frac{8}{5}$ \\
$f(3) = \frac{9(3) + 8}{3(3) + 5} = \frac{35}{14}$ \\
$\frac{35}{14} = \frac{5}{2}$ \\
Range of $fg^{-1}$: $\frac{8}{5} \leq fg^{-1}(x) \leq \frac{5}{2}$

@q 11
@topic Proof n(n^2 + 7) is even
@marks 4
@question
Every natural number is either even or odd, so deal with both cases \\
Case 1: $n$ is even, so $n = 2k$ for an integer $k$ \\
$n(n^{2} + 7) = 2k\left( (2k)^{2} + 7 \right)$ \\
$(2k)^{2} = 4k^{2}$ \\
$n(n^{2} + 7) = 2k(4k^{2} + 7)$ \\
This has a factor of 2, so it is even \\
Case 2: $n$ is odd, so $n = 2k + 1$ for an integer $k$ \\
$n^{2} = (2k + 1)^{2} = 4k^{2} + 4k + 1$ \\
$n^{2} + 7 = 4k^{2} + 4k + 8$ \\
Take out a factor of 2: $4k^{2} + 4k + 8 = 2(2k^{2} + 2k + 4)$ \\
$n(n^{2} + 7) = (2k + 1) \times 2(2k^{2} + 2k + 4)$ \\
$= 2(2k + 1)(2k^{2} + 2k + 4)$ \\
This has a factor of 2, so it is even \\
Both cases give an even number \\
So $n(n^{2} + 7)$ is even for all $n \in \mathbb{N}$

@q 12
@topic Quotient rule, no stationary point
@marks 6
@question
(a) Use the quotient rule with $u = -e^{5x}$ and $v = 3x^{2} + k$ \\
$\frac{du}{dx} = -5e^{5x}$ \\
$\frac{dv}{dx} = 6x$ \\
$f'(x) = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^{2}}$ \\
$f'(x) = \frac{(3x^{2} + k)(-5e^{5x}) - (-e^{5x})(6x)}{(3x^{2} + k)^{2}}$ \\
$f'(x) = \frac{-5e^{5x}(3x^{2} + k) + 6xe^{5x}}{(3x^{2} + k)^{2}}$ \\
Take out the factor $-e^{5x}$ on the top: \\
$f'(x) = \frac{-e^{5x}\left[ 5(3x^{2} + k) - 6x \right]}{(3x^{2} + k)^{2}}$ \\
Expand the inner bracket: $5(3x^{2} + k) - 6x = 15x^{2} + 5k - 6x$ \\
$f'(x) = \frac{-e^{5x}(15x^{2} - 6x + 5k)}{(3x^{2} + k)^{2}}$ \\
Write this as the quadratic times a function of $x$: \\
$f'(x) = (15x^{2} - 6x + 5k) \times \left( \frac{-e^{5x}}{(3x^{2} + k)^{2}} \right)$ \\
So $g(x) = -\frac{e^{5x}}{(3x^{2} + k)^{2}}$ \\
(b) A stationary point needs $f'(x) = 0$ \\
$g(x)$ is never zero, because $e^{5x}$ is never zero \\
So stationary points come from $15x^{2} - 6x + 5k = 0$ \\
No stationary point means this quadratic has no real roots, so the discriminant is negative: \\
$b^{2} - 4ac < 0$ with $a = 15$, $b = -6$, $c = 5k$ \\
$(-6)^{2} - 4(15)(5k) < 0$ \\
$36 - 300k < 0$ \\
Add $300k$ to both sides: \\
$36 < 300k$ \\
Divide by 300: \\
$k > \frac{36}{300}$ \\
$k > \frac{3}{25}$

@q 13
@topic Collinear points, parallel vectors, length
@marks 6
@question
(a) $\text{PQ} = \text{OQ} - \text{OP}$ \\
$\text{PQ} = (2\mathbf{i} - 3\mathbf{j} + 6\mathbf{k}) - (3\mathbf{i} + 4\mathbf{k})$ \\
$\text{PQ} = -\mathbf{i} - 3\mathbf{j} + 2\mathbf{k}$ \\
$\text{PR} = \text{OR} - \text{OP}$ \\
$\text{PR} = (-3\mathbf{i} - 18\mathbf{j} + a\mathbf{k}) - (3\mathbf{i} + 4\mathbf{k})$ \\
$\text{PR} = -6\mathbf{i} - 18\mathbf{j} + (a - 4)\mathbf{k}$ \\
$P$, $Q$, $R$ are collinear, so $\text{PR}$ is a multiple of $\text{PQ}$: $\text{PR} = \lambda\text{PQ}$ \\
Compare the $\mathbf{i}$ components: $-6 = -\lambda$, so $\lambda = 6$ \\
Check the $\mathbf{j}$ components: $-18 = 6 \times (-3)$, which is true \\
Compare the $\mathbf{k}$ components: $a - 4 = 6 \times 2$ \\
$a - 4 = 12$ \\
$a = 16$ \\
(b) $S$ is on the line $OP$, so $\text{OS} = \mu\text{OP}$ \\
$\text{OS} = \mu(3\mathbf{i} + 4\mathbf{k})$ \\
$\text{OS} = 3\mu\mathbf{i} + 4\mu\mathbf{k}$ \\
$\text{OR} = -3\mathbf{i} - 18\mathbf{j} + 16\mathbf{k}$ \\
$\text{RS} = \text{OS} - \text{OR}$ \\
$\text{RS} = (3\mu + 3)\mathbf{i} + 18\mathbf{j} + (4\mu - 16)\mathbf{k}$ \\
$\text{RS}$ is parallel to $\text{OQ} = 2\mathbf{i} - 3\mathbf{j} + 6\mathbf{k}$, so $\text{RS} = \lambda\text{OQ}$ \\
Compare the $\mathbf{j}$ components: $18 = -3\lambda$ \\
$\lambda = -6$ \\
Compare the $\mathbf{i}$ components: $3\mu + 3 = 2\lambda = -12$ \\
$3\mu = -15$ \\
$\mu = -5$ \\
Check the $\mathbf{k}$ components: $4\mu - 16 = 6\lambda = -36$, so $4\mu = -20$ and $\mu = -5$, which agrees \\
$\text{OS} = -5\text{OP}$ \\
$\text{OS} = -15\mathbf{i} - 20\mathbf{k}$ \\
$|\text{OS}| = \sqrt{(-15)^{2} + (-20)^{2}}$ \\
$= \sqrt{225 + 400}$ \\
$= \sqrt{625}$ \\
$= 25$

@q 14
@topic Partial fractions, differential equation
@marks 10
@question
(a) Write $\frac{11}{(3x - 2)(x + 3)} = \frac{A}{3x - 2} + \frac{B}{x + 3}$ \\
Multiply both sides by $(3x - 2)(x + 3)$: \\
$11 = A(x + 3) + B(3x - 2)$ \\
Put $x = \frac{2}{3}$ (this removes the $B$ term): \\
$11 = A\left( \frac{2}{3} + 3 \right)$ \\
$11 = \frac{11}{3}A$ \\
$A = 3$ \\
Put $x = -3$ (this removes the $A$ term): \\
$11 = B(-9 - 2)$ \\
$11 = -11B$ \\
$B = -1$ \\
$\frac{11}{(3x - 2)(x + 3)} = \frac{3}{3x - 2} - \frac{1}{x + 3}$ \\
(b) Separate the variables: \\
$\frac{1}{M} dM = \frac{11}{(3t - 2)(t + 3)} dt$ \\
Use part (a) on the right hand side: \\
$\frac{1}{M} dM = \left( \frac{3}{3t - 2} - \frac{1}{t + 3} \right) dt$ \\
Integrate both sides: \\
$\int \frac{1}{M} dM = \ln M$ \\
$\int \frac{3}{3t - 2} dt = \ln (3t - 2)$ \\
$\int \frac{1}{t + 3} dt = \ln (t + 3)$ \\
$\ln M = \ln (3t - 2) - \ln (t + 3) + c$ \\
At $t = 2.5$, $M = 5.5$: \\
$3t - 2 = 5.5$ and $t + 3 = 5.5$ \\
$\ln 5.5 = \ln 5.5 - \ln 5.5 + c$ \\
$c = \ln 5.5$ \\
$\ln M = \ln (3t - 2) - \ln (t + 3) + \ln 5.5$ \\
Use the log laws to combine the right hand side: \\
$\ln M = \ln \frac{5.5(3t - 2)}{t + 3}$ \\
Take exponentials: \\
$M = \frac{5.5(3t - 2)}{t + 3}$ \\
$5.5 = \frac{11}{2}$ \\
$M = \frac{11(3t - 2)}{2(t + 3)}$ as required \\
(c)(i) The new protein starts when $M$ first becomes positive, which is when $M = 0$ \\
$3t - 2 = 0$ \\
$t = \frac{2}{3}$ minutes \\
$\frac{2}{3} \times 60 = 40$ \\
The time delay is 40 seconds \\
(ii) As $t$ gets very large, divide the top and bottom of $M$ by $t$: \\
$M = \frac{11\left( 3 - \frac{2}{t} \right)}{2\left( 1 + \frac{3}{t} \right)}$ \\
$\frac{2}{t} \to 0$ and $\frac{3}{t} \to 0$: \\
$M \to \frac{11 \times 3}{2 \times 1}$ \\
$M \to 16.5$ \\
The limit is 16.5 mg

@q 15
@topic Geometric series, trig, sum to infinity
@marks 10
@question
(a) In a geometric series the common ratio is the same for each pair of neighbouring terms: \\
$\frac{\text{second}}{\text{first}} = \frac{\text{third}}{\text{second}}$ \\
$\frac{5 + 2\sin \theta}{8\cos \theta} = \frac{9\tan \theta}{5 + 2\sin \theta}$ \\
Cross multiply: \\
$(5 + 2\sin \theta)^{2} = 9\tan \theta \times 8\cos \theta$ \\
$(5 + 2\sin \theta)^{2} = 72\tan \theta \cos \theta$ \\
Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$, so $\tan \theta \cos \theta = \sin \theta$: \\
$(5 + 2\sin \theta)^{2} = 72\sin \theta$ \\
Expand the bracket: \\
$25 + 20\sin \theta + 4\sin^{2} \theta = 72\sin \theta$ \\
Subtract $72\sin \theta$ from both sides: \\
$4\sin^{2} \theta - 52\sin \theta + 25 = 0$ as required \\
(b) Factorise the quadratic in $\sin \theta$: \\
$4\sin^{2} \theta - 52\sin \theta + 25 = (2\sin \theta - 1)(2\sin \theta - 25)$ \\
$\sin \theta = \frac{1}{2}$ or $\sin \theta = \frac{25}{2}$ \\
$\sin \theta$ cannot be bigger than 1, so $\sin \theta = \frac{1}{2}$ \\
The acute solution is $\frac{\pi}{6}$ \\
$\theta$ is obtuse, so $\theta = \pi - \frac{\pi}{6}$ \\
$\theta = \frac{5\pi}{6}$ \\
(c) First term: $a = 8\cos \theta = 8\cos \frac{5\pi}{6}$ \\
$\cos \frac{5\pi}{6} = -\frac{\sqrt{3}}{2}$ \\
$a = 8 \times \left( -\frac{\sqrt{3}}{2} \right) = -4\sqrt{3}$ \\
Common ratio: $r = \frac{5 + 2\sin \theta}{8\cos \theta}$ \\
$r = \frac{5 + 2 \times \frac{1}{2}}{-4\sqrt{3}}$ \\
$r = \frac{6}{-4\sqrt{3}}$ \\
$r = -\frac{3}{2\sqrt{3}}$ \\
Multiply the top and bottom by $\sqrt{3}$: \\
$r = -\frac{3\sqrt{3}}{6} = -\frac{\sqrt{3}}{2}$ \\
(Check the third term: $ar^{2} = -4\sqrt{3} \times \frac{3}{4} = -3\sqrt{3}$ and $9\tan \frac{5\pi}{6} = 9 \times \left( -\frac{1}{\sqrt{3}} \right) = -3\sqrt{3}$) \\
$|r| = 0.866 < 1$, so the series converges \\
$S_{\infty} = \frac{a}{1 - r}$ \\
$S_{\infty} = \frac{-4\sqrt{3}}{1 + \frac{\sqrt{3}}{2}}$ \\
Write the denominator as one fraction: $1 + \frac{\sqrt{3}}{2} = \frac{2 + \sqrt{3}}{2}$ \\
$S_{\infty} = -4\sqrt{3} \times \frac{2}{2 + \sqrt{3}}$ \\
$S_{\infty} = \frac{-8\sqrt{3}}{2 + \sqrt{3}}$ \\
Rationalise the denominator: multiply the top and bottom by $(2 - \sqrt{3})$ \\
$(2 + \sqrt{3})(2 - \sqrt{3}) = 4 - 3 = 1$ \\
$S_{\infty} = -8\sqrt{3}(2 - \sqrt{3})$ \\
Expand the bracket: \\
$S_{\infty} = -16\sqrt{3} + 8 \times 3$ \\
$S_{\infty} = 24 - 16\sqrt{3}$ \\
Take out the factor 8: \\
$S_{\infty} = 8(3 - 2\sqrt{3})$ \\
So $k = 8$

@q 16
@topic Parametric normal, Cartesian, line meets C
@marks 12
@question
(a) $x = 3\cot t - 1$ \\
$\frac{dx}{dt} = -3\text{cosec}^{2} t$ \\
$y = 3\text{cosec}^{2} t + 2 = 3(\text{cosec } t)^{2} + 2$ \\
$\frac{dy}{dt} = 3 \times 2\text{cosec } t \times (-\text{cosec } t\cot t)$ \\
$\frac{dy}{dt} = -6\text{cosec}^{2} t\cot t$ \\
$\frac{dy}{dx} = \frac{dy}{dt} \div \frac{dx}{dt}$ \\
$\frac{dy}{dx} = \frac{-6\text{cosec}^{2} t\cot t}{-3\text{cosec}^{2} t}$ \\
Cancel $-3\text{cosec}^{2} t$: \\
$\frac{dy}{dx} = 2\cot t$ \\
At $t = \frac{3\pi}{4}$: $\cot \frac{3\pi}{4} = -1$ \\
$\frac{dy}{dx} = -2$ \\
The coordinates of $P$: $x = 3(-1) - 1 = -4$ \\
$\sin \frac{3\pi}{4} = \frac{\sqrt{2}}{2}$, so $\sin^{2} \frac{3\pi}{4} = \frac{1}{2}$ and $\text{cosec}^{2} \frac{3\pi}{4} = 2$ \\
$y = 3 \times 2 + 2 = 8$ \\
$P = (-4, 8)$ \\
The normal is perpendicular to the tangent, so its gradient is the negative reciprocal of $-2$ \\
Gradient of the normal $= \frac{1}{2}$ \\
$y - 8 = \frac{1}{2}(x - (-4))$ \\
$y - 8 = \frac{1}{2}(x + 4)$ \\
$y - 8 = \frac{1}{2}x + 2$ \\
Add 8: \\
$y = \frac{1}{2}x + 10$ as required \\
(b) Use the identity $\text{cosec}^{2} t = 1 + \cot^{2} t$ \\
From $x = 3\cot t - 1$: $\cot t = \frac{x + 1}{3}$ \\
From $y = 3\text{cosec}^{2} t + 2$: $\text{cosec}^{2} t = \frac{y - 2}{3}$ \\
$\frac{y - 2}{3} = 1 + \left( \frac{x + 1}{3} \right)^{2}$ \\
$\frac{y - 2}{3} = 1 + \frac{(x + 1)^{2}}{9}$ \\
Multiply both sides by 3: \\
$y - 2 = 3 + \frac{(x + 1)^{2}}{3}$ \\
Add 2: \\
$y = \frac{1}{3}(x + 1)^{2} + 5$ as required \\
(c) For $\frac{\pi}{4} \leq t < \pi$, $\cot t$ goes from 1 down to very negative values \\
So $x = 3\cot t - 1$ goes from $x = 2$ (at $t = \frac{\pi}{4}$) down to very negative values \\
$C$ is the part of the parabola with $x \leq 2$, including the end point $(2, 8)$ \\
Where the line meets the parabola: \\
$\frac{1}{3}(x + 1)^{2} + 5 = \frac{1}{2}x + k$ \\
Multiply every term by 6: \\
$2(x + 1)^{2} + 30 = 3x + 6k$ \\
Expand the bracket: \\
$2x^{2} + 4x + 2 + 30 = 3x + 6k$ \\
Subtract $3x$ and $6k$ from both sides: \\
$2x^{2} + x + (32 - 6k) = 0$ \\
Two distinct points need two different real roots: $b^{2} - 4ac > 0$ \\
$1^{2} - 4(2)(32 - 6k) > 0$ \\
$1 - 8(32 - 6k) > 0$ \\
Expand: \\
$1 - 256 + 48k > 0$ \\
$48k > 255$ \\
$k > \frac{255}{48}$ \\
$k > \frac{85}{16}$ \\
Both roots must also have $x \leq 2$ \\
The roots are $x = \frac{-1 \pm \sqrt{48k - 255}}{4}$, and the larger root gets bigger as $k$ gets bigger \\
The largest allowed $k$ is when the line goes through the end point $(2, 8)$: \\
$8 = \frac{1}{2}(2) + k$ \\
$8 = 1 + k$ \\
$k = 7$ \\
(Check: for $k = 7$, $2x^{2} + x - 10 = (2x + 5)(x - 2) = 0$, so $x = -2.5$ and $x = 2$, both on $C$) \\
For $k > 7$ the larger root is greater than 2, so it is not on $C$ \\
$\frac{85}{16} < k \leq 7$
