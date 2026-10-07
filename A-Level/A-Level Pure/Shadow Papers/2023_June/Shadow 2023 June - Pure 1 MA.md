@paper P1 Shadow June 2023

@q 1
@topic Integrate x^(1/2)(3x - 2)/5
@marks 4
@question
Multiply out the top first: \\
$x^{\frac{1}{2}}(3x - 2) = 3x^{\frac{3}{2}} - 2x^{\frac{1}{2}}$ \\
(Add the powers: $x^{\frac{1}{2}} \times x = x^{\frac{3}{2}}$) \\
Divide each term by 5: \\
$\frac{x^{\frac{1}{2}}(3x - 2)}{5} = \frac{3}{5}x^{\frac{3}{2}} - \frac{2}{5}x^{\frac{1}{2}}$ \\
Integrate each term (add 1 to the power, divide by the new power): \\
$\frac{3}{5}x^{\frac{3}{2}} \to \frac{3}{5} \times \frac{x^{\frac{5}{2}}}{\frac{5}{2}}$ \\
$= \frac{3}{5} \times \frac{2}{5}x^{\frac{5}{2}}$ \\
$= \frac{6}{25}x^{\frac{5}{2}}$ \\
$-\frac{2}{5}x^{\frac{1}{2}} \to -\frac{2}{5} \times \frac{x^{\frac{3}{2}}}{\frac{3}{2}}$ \\
$= -\frac{2}{5} \times \frac{2}{3}x^{\frac{3}{2}}$ \\
$= -\frac{4}{15}x^{\frac{3}{2}}$ \\
$\int \frac{x^{\frac{1}{2}}(3x - 2)}{5} dx = \frac{6}{25}x^{\frac{5}{2}} - \frac{4}{15}x^{\frac{3}{2}} + c$

@q 2
@topic Factor theorem with a, cubic equation
@marks 6
@question
(a) $(x - a)$ is a factor, so by the factor theorem $f(a) = 0$ \\
$f(a) = 5a^{3} + 3a^{2} - 7a + 5a$ \\
Collect the $a$ terms: $-7a + 5a = -2a$ \\
$f(a) = 5a^{3} + 3a^{2} - 2a$ \\
Set this equal to zero: \\
$5a^{3} + 3a^{2} - 2a = 0$ \\
Factorise out $a$: \\
$a(5a^{2} + 3a - 2) = 0$ as required \\
(b)(i) $a$ is positive, so $a \ne 0$, which means \\
$5a^{2} + 3a - 2 = 0$ \\
Factorise: \\
$(5a - 2)(a + 1) = 0$ \\
$a = \frac{2}{5}$ or $a = -1$ \\
$a$ is positive, so $a = \frac{2}{5}$ \\
(ii) Put $a = \frac{2}{5}$ into $f(x)$: \\
$5 \times \frac{2}{5} = 2$ \\
$f(x) = 5x^{3} + 3x^{2} - 7x + 2$ \\
Solve $f(x) = 2$: \\
$5x^{3} + 3x^{2} - 7x + 2 = 2$ \\
Subtract 2 from both sides: \\
$5x^{3} + 3x^{2} - 7x = 0$ \\
Factorise out $x$: \\
$x(5x^{2} + 3x - 7) = 0$ \\
Either $x = 0$ or $5x^{2} + 3x - 7 = 0$ \\
Use the quadratic formula on $5x^{2} + 3x - 7 = 0$ with $a = 5$, $b = 3$, $c = -7$: \\
$x = \frac{-3 \pm \sqrt{3^{2} - 4(5)(-7)}}{2(5)}$ \\
$x = \frac{-3 \pm \sqrt{9 + 140}}{10}$ \\
$x = \frac{-3 \pm \sqrt{149}}{10}$ \\
The solutions are $x = 0$ and $x = \frac{-3 \pm \sqrt{149}}{10}$

@q 3
@topic Position vectors, magnitude inequality
@marks 3
@question
(a) $\text{OB} = 5\mathbf{i} + 4\mathbf{j} + 2\mathbf{k}$ \\
$|\text{OB}| = \sqrt{5^{2} + 4^{2} + 2^{2}}$ \\
$= \sqrt{25 + 16 + 4}$ \\
$= \sqrt{45}$ as required \\
(b) $|\text{OA}| = \sqrt{2^{2} + 3^{2} + a^{2}}$ \\
$|\text{OA}| = \sqrt{13 + a^{2}}$ \\
We need $|\text{OB}| > |\text{OA}|$ \\
$\sqrt{45} > \sqrt{13 + a^{2}}$ \\
Square both sides (both are positive): \\
$45 > 13 + a^{2}$ \\
Subtract 13: \\
$32 > a^{2}$ \\
$a < \sqrt{32}$ \\
$\sqrt{32} = 5.66$ \\
$a$ is a positive integer, so the largest value is $a = 5$ \\
(Check: for $a = 5$, $|\text{OA}| = \sqrt{38} < \sqrt{45}$; for $a = 6$, $|\text{OA}| = \sqrt{49} > \sqrt{45}$)

@q 4
@topic Small angle estimate, tangent
@marks 5
@question
(a) At the stationary point $f'(\alpha) = 0$ \\
$3\alpha - \frac{1}{3}\cos \alpha = 0$ \\
Small angle approximation: $\cos \alpha \approx 1 - \frac{\alpha^{2}}{2}$ \\
$3\alpha - \frac{1}{3}\left( 1 - \frac{\alpha^{2}}{2} \right) \approx 0$ \\
Expand the bracket: \\
$3\alpha - \frac{1}{3} + \frac{\alpha^{2}}{6} \approx 0$ \\
Multiply every term by 6 to clear the fractions: \\
$18\alpha - 2 + \alpha^{2} \approx 0$ \\
$\alpha^{2} + 18\alpha - 2 = 0$ \\
Use the quadratic formula with $a = 1$, $b = 18$, $c = -2$: \\
$\alpha = \frac{-18 \pm \sqrt{18^{2} - 4(1)(-2)}}{2}$ \\
$\alpha = \frac{-18 \pm \sqrt{332}}{2}$ \\
$\sqrt{332} = 18.2209$ \\
$\alpha = \frac{-18 + 18.2209}{2} = 0.1104$ \\
The other root, $\frac{-18 - 18.2209}{2} = -18.1$, is not small, so reject it \\
$\alpha = 0.110$ to 3 decimal places \\
(b) The gradient of the tangent at $P$ is $f'(0)$: \\
$f'(0) = 3(0) - \frac{1}{3}\cos 0$ \\
$\cos 0 = 1$ \\
$f'(0) = -\frac{1}{3}$ \\
The tangent has gradient $-\frac{1}{3}$ and passes through $P(0, 5)$, so the $y$ intercept is 5 \\
$y = -\frac{1}{3}x + 5$

@q 5
@topic Trapezium rule with unknowns a and b
@marks 6
@question
(a) There are 6 values of $y$, so 5 strips, each of width $h = \frac{6.5 - 5}{5} = 0.3$ \\
Trapezium rule: $\frac{h}{2}\left\{ y_{0} + y_{5} + 2(y_{1} + y_{2} + y_{3} + y_{4}) \right\}$ \\
$y_{0} = 17.6$ and $y_{5} = b$ \\
$y_{1} + y_{2} + y_{3} + y_{4} = a + 21.2 + 20.3 + 17.6$ \\
$\frac{0.3}{2}\left\{ 17.6 + b + 2(a + 21.2 + 20.3 + 17.6) \right\} = 28.425$ \\
Add the numbers inside the double bracket: $21.2 + 20.3 + 17.6 = 59.1$ \\
$0.15\left\{ 17.6 + b + 2(a + 59.1) \right\} = 28.425$ \\
Expand the bracket: $2(a + 59.1) = 2a + 118.2$ \\
$0.15\left\{ 2a + b + 135.8 \right\} = 28.425$ \\
Divide both sides by 0.15: \\
$2a + b + 135.8 = 189.5$ \\
Subtract 135.8: \\
$2a + b = 53.7$ as required \\
(b) Add up all the $y$ values: \\
$17.6 + a + 21.2 + 20.3 + 17.6 + b = 110.1$ \\
$17.6 + 21.2 + 20.3 + 17.6 = 76.7$ \\
$a + b + 76.7 = 110.1$ \\
Subtract 76.7: \\
$a + b = 33.4$ \\
Subtract this from $2a + b = 53.7$: \\
$(2a + b) - (a + b) = 53.7 - 33.4$ \\
$a = 20.3$ \\
Put $a = 20.3$ into $a + b = 33.4$: \\
$b = 33.4 - 20.3$ \\
$b = 13.1$

@q 6
@topic Log laws in terms of a and b
@marks 6
@question
(a) Write the cube root as a power: $\sqrt[3]{x} = x^{\frac{1}{3}}$ \\
$\frac{1}{\sqrt[3]{x}} = x^{-\frac{1}{3}}$ \\
Use the power law $\log y^{n} = n\log y$: \\
$\log_{2} x^{-\frac{1}{3}} = -\frac{1}{3}\log_{2} x$ \\
$= -\frac{1}{3}a$ \\
(b) Factorise: $2x^{2} + 8x = 2x(x + 4)$ \\
$\log_{2}\left( 2x(x + 4) \right)$ \\
Use $\log (pq) = \log p + \log q$ on the three factors: \\
$= \log_{2} 2 + \log_{2} x + \log_{2}(x + 4)$ \\
$\log_{2} 2 = 1$ \\
$= 1 + a + b$ \\
(c) Write over a common denominator: $\frac{16}{x} + 4 = \frac{16}{x} + \frac{4x}{x}$ \\
$\frac{16}{x} + 4 = \frac{16 + 4x}{x}$ \\
Factorise the top: $16 + 4x = 4(4 + x)$ \\
$\frac{16}{x} + 4 = \frac{4(x + 4)}{x}$ \\
$\log_{2}\frac{4(x + 4)}{x}$ \\
Use $\log \frac{p}{q} = \log p - \log q$ and $\log (pq) = \log p + \log q$: \\
$= \log_{2} 4 + \log_{2}(x + 4) - \log_{2} x$ \\
$\log_{2} 4 = 2$ \\
$= 2 + b - a$

@q 7
@topic Function range, inverse, composite
@marks 8
@question
(a) $\sqrt{x - 3}$ is greater than 0 when $x > 3$ \\
So $2 + \sqrt{x - 3}$ is greater than 2 \\
Range of f: $f(x) > 2$ \\
(b) Let $y = 2 + \sqrt{x - 3}$ \\
Subtract 2: $y - 2 = \sqrt{x - 3}$ \\
Square both sides: \\
$(y - 2)^{2} = x - 3$ \\
Add 3: \\
$x = (y - 2)^{2} + 3$ \\
Swap the letters: \\
$f^{-1}(x) = (x - 2)^{2} + 3$ \\
The domain of $f^{-1}$ is the range of $f$, so $x > 2$ \\
(c) $gf(4)$ means $g(f(4))$ \\
$f(4) = 2 + \sqrt{4 - 3}$ \\
$= 2 + 1$ \\
$= 3$ \\
$g(3) = \frac{10}{3 - 2}$ \\
$gf(4) = 10$ \\
(d) $f(a^{2} + 3) = 2 + \sqrt{a^{2} + 3 - 3}$ \\
$= 2 + \sqrt{a^{2}}$ \\
Take $a > 0$, so $\sqrt{a^{2}} = a$ \\
$f(a^{2} + 3) = 2 + a$ \\
Set equal to $g(a)$: \\
$2 + a = \frac{10}{a - 2}$ \\
Multiply both sides by $(a - 2)$: \\
$(2 + a)(a - 2) = 10$ \\
Expand the bracket (difference of two squares): \\
$a^{2} - 4 = 10$ \\
Add 4: \\
$a^{2} = 14$ \\
$a = \sqrt{14}$ \\
(If $a < 0$ then $\sqrt{a^{2}} = -a$ and the equation becomes $(2 - a)(a - 2) = 10$, that is $-(a - 2)^{2} = 10$, which has no real solution)

@q 8
@topic Stage plan, sector and triangles
@marks 10
@question
(a) Arc length $= r\theta$ \\
$CDE = OC \times 2.8$ \\
$30.8 = OC \times 2.8$ \\
Divide by 2.8: \\
$OC = \frac{30.8}{2.8}$ \\
$OC = 11$ m as required \\
(b) The angles on the straight line $AOG$ add up to $\pi$ \\
$AOB + COE + GOF = \pi$ \\
The triangles are congruent, so $AOB = GOF$ \\
$2 \times AOB + 2.8 = \pi$ \\
Subtract 2.8: \\
$2 \times AOB = \pi - 2.8$ \\
$2 \times AOB = 0.3416$ \\
Divide by 2: \\
$AOB = 0.1708$ \\
$AOB = 0.171$ radians to 3 decimal places as required \\
(c) The front of the stage $BCDEF$ is made of $BC$, the arc $CDE$, and $EF$ \\
$BC = EF$, since the triangles are congruent \\
$BC + 30.8 + EF = 50$ \\
$2BC = 50 - 30.8$ \\
$2BC = 19.2$ \\
$BC = 9.6$ m \\
$B$ is on the line $OC$ extended, so $OB = OC + CB$ \\
$OB = 11 + 9.6$ \\
$OB = 20.6$ m \\
$AOG$ is 20 m long with $O$ in the middle, so $OA = 10$ m \\
Area of the sector $OCDE = \frac{1}{2}r^{2}\theta$ \\
$= \frac{1}{2} \times 11^{2} \times 2.8$ \\
$= \frac{1}{2} \times 121 \times 2.8$ \\
$= 169.4$ m$^{2}$ \\
Area of triangle $OAB = \frac{1}{2} \times OA \times OB \times \sin AOB$ \\
$= \frac{1}{2} \times 10 \times 20.6 \times \sin 0.1708$ \\
$\sin 0.1708 = 0.16997$ \\
$= 103 \times 0.16997$ \\
$= 17.51$ m$^{2}$ \\
The other triangle $OFG$ has the same area \\
Total area $= 169.4 + 2 \times 17.51$ \\
$= 169.4 + 35.01$ \\
$= 204.4$ \\
The total area of the stage is 204 m$^{2}$ to the nearest square metre

@q 9
@topic Geometric sequence, converges, sum
@marks 7
@question
(a) In a geometric sequence the common ratio is the same between each pair of terms: \\
$\frac{\text{second}}{\text{first}} = \frac{\text{third}}{\text{second}}$ \\
$\frac{2k - 8}{3k - 5} = \frac{\frac{5k + 1}{5}}{2k - 8}$ \\
$\frac{2k - 8}{3k - 5} = \frac{5k + 1}{5(2k - 8)}$ \\
Cross multiply: \\
$5(2k - 8)^{2} = (3k - 5)(5k + 1)$ \\
Expand the left side: $(2k - 8)^{2} = 4k^{2} - 32k + 64$ \\
$5(4k^{2} - 32k + 64) = 20k^{2} - 160k + 320$ \\
Expand the right side: $(3k - 5)(5k + 1) = 15k^{2} + 3k - 25k - 5$ \\
$= 15k^{2} - 22k - 5$ \\
$20k^{2} - 160k + 320 = 15k^{2} - 22k - 5$ \\
Subtract the right side from both sides: \\
$5k^{2} - 138k + 325 = 0$ as required \\
(b)(i) Use the quadratic formula with $a = 5$, $b = -138$, $c = 325$: \\
$k = \frac{138 \pm \sqrt{138^{2} - 4(5)(325)}}{10}$ \\
$138^{2} = 19044$ and $4 \times 5 \times 325 = 6500$ \\
$k = \frac{138 \pm \sqrt{12544}}{10}$ \\
$\sqrt{12544} = 112$ \\
$k = \frac{138 \pm 112}{10}$ \\
$k = 25$ or $k = 2.6$ \\
Test $k = 25$: the terms are $70$, $42$, $25.2$ \\
The ratio is $r = \frac{42}{70} = 0.6$ \\
$|r| < 1$, so the sequence converges \\
Test $k = 2.6$: the terms are $2.8$, $-2.8$, $2.8$ \\
The ratio is $r = -1$, so the terms keep swapping sign and the sequence does not converge \\
So $k = 25$ \\
(ii) $a = 3(25) - 5 = 70$ and $r = \frac{3}{5}$ \\
$S_{\infty} = \frac{a}{1 - r}$ \\
$S_{\infty} = \frac{70}{1 - \frac{3}{5}}$ \\
$S_{\infty} = \frac{70}{\frac{2}{5}}$ \\
Dividing by $\frac{2}{5}$ is multiplying by $\frac{5}{2}$: \\
$S_{\infty} = 70 \times \frac{5}{2}$ \\
$S_{\infty} = 175$

@q 10
@topic Circle with k, line meets at two points
@marks 9
@question
(a) Complete the square on the $x$ terms and the $y$ terms: \\
$x^{2} - 2kx = (x - k)^{2} - k^{2}$ \\
$y^{2} + 4ky = (y + 2k)^{2} - 4k^{2}$ \\
$(x - k)^{2} - k^{2} + (y + 2k)^{2} - 4k^{2} + 5 = 0$ \\
Collect the $k^{2}$ terms and move them across: \\
$(x - k)^{2} + (y + 2k)^{2} = 5k^{2} - 5$ \\
(i) The centre is $(k, -2k)$ \\
(ii) The radius is $\sqrt{5k^{2} - 5}$ \\
(b) Substitute $y = x - 2$ into $x^{2} + y^{2} - 2kx + 4ky + 5 = 0$: \\
$x^{2} + (x - 2)^{2} - 2kx + 4k(x - 2) + 5 = 0$ \\
Expand the bracket: $(x - 2)^{2} = x^{2} - 4x + 4$ \\
Expand the other: $4k(x - 2) = 4kx - 8k$ \\
$x^{2} + x^{2} - 4x + 4 - 2kx + 4kx - 8k + 5 = 0$ \\
Collect the $x^{2}$ terms: $x^{2} + x^{2} = 2x^{2}$ \\
Collect the $x$ terms: $-4x - 2kx + 4kx = (2k - 4)x$ \\
Collect the rest: $4 - 8k + 5 = 9 - 8k$ \\
$2x^{2} + (2k - 4)x + (9 - 8k) = 0$ \\
Two distinct intersection points need two different real roots: $b^{2} - 4ac > 0$ \\
$(2k - 4)^{2} - 4(2)(9 - 8k) > 0$ \\
Expand the first term: $(2k - 4)^{2} = 4k^{2} - 16k + 16$ \\
Expand the second term: $8(9 - 8k) = 72 - 64k$ \\
$4k^{2} - 16k + 16 - 72 + 64k > 0$ \\
Collect like terms: \\
$4k^{2} + 48k - 56 > 0$ \\
Divide by 4: \\
$k^{2} + 12k - 14 > 0$ \\
Find where $k^{2} + 12k - 14 = 0$, using the quadratic formula: \\
$k = \frac{-12 \pm \sqrt{144 + 56}}{2}$ \\
$k = \frac{-12 \pm \sqrt{200}}{2}$ \\
$\sqrt{200} = 10\sqrt{2}$ \\
$k = -6 \pm 5\sqrt{2}$ \\
The graph of $k^{2} + 12k - 14$ is a U shape, so it is positive outside the roots: \\
$k < -6 - 5\sqrt{2}$ or $k > -6 + 5\sqrt{2}$ \\
(Check the circle is real: $5k^{2} - 5 > 0$ needs $|k| > 1$, and $-6 + 5\sqrt{2} = 1.07$ and $-6 - 5\sqrt{2} = -13.07$ both satisfy this)

@q 11
@topic Exponential model from log graph, car
@marks 7
@question
(a) The initial value is at $t = 0$ \\
From the graph, when $t = 0$, $\log_{10} V = 4$ \\
$V = 10^{4}$ \\
The initial value of the car is GBP 10 000 \\
(b) Take logs (base 10) of $V = ab^{t}$: \\
$\log_{10} V = \log_{10}(ab^{t})$ \\
$\log_{10} V = \log_{10} a + \log_{10} b^{t}$ \\
$\log_{10} V = \log_{10} a + t\log_{10} b$ \\
This is a straight line against $t$ with intercept $\log_{10} a$ and gradient $\log_{10} b$ \\
Intercept: $\log_{10} a = 4$, so $a = 10^{4} = 10000$ \\
Gradient from the points $(0, 4)$ and $(8, 3.84)$: \\
$\log_{10} b = \frac{3.84 - 4}{8 - 0}$ \\
$\log_{10} b = \frac{-0.16}{8}$ \\
$\log_{10} b = -0.02$ \\
Raise 10 to the power of each side: \\
$b = 10^{-0.02}$ \\
$b = 0.95499$ \\
$b = 0.955$ to 3 significant figures \\
$V = 10000 \times 0.955^{t}$ \\
(c) Exactly 2 years is 24 months, so $t = 24$ \\
$V = 10000 \times 0.955^{24}$ \\
$0.955^{24} = 0.33119$ \\
$V = 3311.9$ \\
The model gives about GBP 3312 and the car was sold for GBP 3300 \\
The difference is only about GBP 12, which is under 0.5 percent of the sale price \\
So the model is very reliable

@q 12
@topic Differentiate cos x from first principles
@marks 5
@question
$y = f(x) = \cos x$ \\
Gradient from first principles: $\frac{dy}{dx} = \lim_{h \to 0}\frac{f(x + h) - f(x)}{h}$ \\
$\frac{f(x + h) - f(x)}{h} = \frac{\cos (x + h) - \cos x}{h}$ \\
Use $\cos (A + B) = \cos A\cos B - \sin A\sin B$ with $A = x$ and $B = h$: \\
$\cos (x + h) = \cos x\cos h - \sin x\sin h$ \\
$\frac{\cos (x + h) - \cos x}{h} = \frac{\cos x\cos h - \sin x\sin h - \cos x}{h}$ \\
Group the two $\cos x$ terms: \\
$= \frac{\cos x(\cos h - 1) - \sin x\sin h}{h}$ \\
Split into two fractions: \\
$= \cos x\left( \frac{\cos h - 1}{h} \right) - \sin x\left( \frac{\sin h}{h} \right)$ \\
As $h \to 0$ we are told $\frac{\cos h - 1}{h} \to 0$ and $\frac{\sin h}{h} \to 1$ \\
$\to \cos x \times 0 - \sin x \times 1$ \\
$\to -\sin x$ \\
So $\frac{dy}{dx} = -\sin x$ as required

@q 13
@topic Roller coaster, quadratic vs cosine
@marks 7
@question
(a) $H = a - b(t - 15)^{2}$ \\
$(t - 15)^{2}$ is never negative, and $b$ is positive, so $H$ is biggest when $t = 15$ \\
At $t = 15$, $H = a$, and the maximum height is 42, so $a = 42$ \\
$H = 42 - b(t - 15)^{2}$ \\
At the start $t = 0$ and $H = 1.5$: \\
$1.5 = 42 - b(0 - 15)^{2}$ \\
$(0 - 15)^{2} = 225$ \\
$1.5 = 42 - 225b$ \\
Add $225b$ and subtract 1.5 on both sides: \\
$225b = 42 - 1.5$ \\
$225b = 40.5$ \\
Divide by 225: \\
$b = 0.18$ \\
$H = 42 - 0.18(t - 15)^{2}$ \\
(b) Put $t = 25$ into the model: \\
$H = 42 - 0.18(25 - 15)^{2}$ \\
$(25 - 15)^{2} = 100$ \\
$0.18 \times 100 = 18$ \\
$H = 42 - 18$ \\
$H = 24$ m \\
(c) The cosine part goes between $-20.25$ and $20.25$ \\
So $H$ goes between $\beta - 20.25$ and $\beta + 20.25$ \\
The maximum is 42: \\
$\beta + 20.25 = 42$ \\
$\beta = 21.75$ \\
The minimum is $21.75 - 20.25 = 1.5$, which is the starting height \\
So at $t = 0$, $H$ is at its minimum, which means the cosine is $-1$ \\
$\cos \alpha = -1$ \\
$\alpha = 180$ degrees \\
$H = 20.25\cos (12t + 180) \text{ degrees} + 21.75$ \\
(d) The cosine model repeats every $\frac{360}{12} = 30$ seconds, which is one circuit \\
2 minutes is 120 seconds, which is 4 circuits \\
The quadratic model goes up and down only once, and it would give a negative height after $t = 30.3$, which is impossible \\
So the alternative model is more appropriate as it keeps repeating the circuits

@q 14
@topic Proof (n-1)^3 - n^3 is odd
@marks 4
@question
Every natural number is even or odd, so deal with both cases \\
Case 1: $n$ is even, so $n = 2k$ for an integer $k$ \\
$(n - 1)^{3} - n^{3} = (2k - 1)^{3} - (2k)^{3}$ \\
Expand $(2k - 1)^{3} = (2k)^{3} - 3(2k)^{2}(1) + 3(2k)(1)^{2} - 1$ \\
$(2k - 1)^{3} = 8k^{3} - 12k^{2} + 6k - 1$ \\
Subtract $(2k)^{3} = 8k^{3}$: \\
$8k^{3} - 12k^{2} + 6k - 1 - 8k^{3}$ \\
The $8k^{3}$ terms cancel: \\
$= -12k^{2} + 6k - 1$ \\
Take out a factor of $-6k$ from the first two terms: \\
$= -6k(2k - 1) - 1$ \\
$-6k(2k - 1)$ has a factor of 2, so it is even \\
Even minus 1 is odd \\
Case 2: $n$ is odd, so $n = 2k + 1$ for an integer $k$ \\
$(n - 1)^{3} - n^{3} = (2k)^{3} - (2k + 1)^{3}$ \\
Expand $(2k + 1)^{3} = 8k^{3} + 12k^{2} + 6k + 1$ \\
$8k^{3} - (8k^{3} + 12k^{2} + 6k + 1)$ \\
Remove the bracket: \\
$= 8k^{3} - 8k^{3} - 12k^{2} - 6k - 1$ \\
$= -12k^{2} - 6k - 1$ \\
Take out a factor of $-6k$ from the first two terms: \\
$= -6k(2k + 1) - 1$ \\
$-6k(2k + 1)$ is even \\
Even minus 1 is odd \\
Both cases give an odd number \\
So $(n - 1)^{3} - n^{3}$ is odd for all $n \in \mathbb{N}$

@q 15
@topic Quotient rule, turning points, iteration
@marks 13
@question
(a) Use the quotient rule with $u = 5xe^{x}$ and $v = (e^{3x} - 3)^{\frac{1}{2}}$ \\
Differentiate $u$ with the product rule: \\
$\frac{du}{dx} = 5e^{x} + 5xe^{x}$ \\
$\frac{du}{dx} = 5e^{x}(x + 1)$ \\
Differentiate $v$ with the chain rule: \\
$\frac{dv}{dx} = \frac{1}{2}(e^{3x} - 3)^{-\frac{1}{2}} \times 3e^{3x}$ \\
$\frac{dv}{dx} = \frac{3}{2}e^{3x}(e^{3x} - 3)^{-\frac{1}{2}}$ \\
$f'(x) = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^{2}}$ \\
$v^{2} = e^{3x} - 3$ \\
$f'(x) = \frac{(e^{3x} - 3)^{\frac{1}{2}} \times 5e^{x}(x + 1) - 5xe^{x} \times \frac{3}{2}e^{3x}(e^{3x} - 3)^{-\frac{1}{2}}}{e^{3x} - 3}$ \\
Multiply the top and bottom by $(e^{3x} - 3)^{\frac{1}{2}}$ to remove the negative power: \\
$f'(x) = \frac{(e^{3x} - 3) \times 5e^{x}(x + 1) - \frac{3}{2} \times 5xe^{x}e^{3x}}{(e^{3x} - 3)^{\frac{3}{2}}}$ \\
Take out the common factor $5e^{x}$ on the top: \\
Top $= 5e^{x}\left[ (x + 1)(e^{3x} - 3) - \frac{3}{2}xe^{3x} \right]$ \\
Expand $(x + 1)(e^{3x} - 3) = xe^{3x} - 3x + e^{3x} - 3$ \\
Inside the bracket: $xe^{3x} - 3x + e^{3x} - 3 - \frac{3}{2}xe^{3x}$ \\
Collect the $xe^{3x}$ terms: $xe^{3x} - \frac{3}{2}xe^{3x} = -\frac{1}{2}xe^{3x}$ \\
Inside the bracket: $e^{3x} - \frac{1}{2}xe^{3x} - 3x - 3$ \\
Take out a factor $\frac{1}{2}$: \\
$= \frac{1}{2}\left[ 2e^{3x} - xe^{3x} - 6x - 6 \right]$ \\
$= \frac{1}{2}\left[ e^{3x}(2 - x) - 6x - 6 \right]$ \\
$f'(x) = \frac{5e^{x} \times \frac{1}{2}\left[ e^{3x}(2 - x) - 6x - 6 \right]}{(e^{3x} - 3)^{\frac{3}{2}}}$ \\
$f'(x) = \frac{5e^{x}\left( e^{3x}(2 - x) - 6x - 6 \right)}{2(e^{3x} - 3)^{\frac{3}{2}}}$ \\
So $A = -6$ and $B = -6$ \\
(b) At a turning point $f'(x) = 0$ \\
$5e^{x}$ is never zero and the bottom is never zero, so the bracket on the top is zero: \\
$e^{3x}(2 - x) - 6x - 6 = 0$ \\
Expand: \\
$2e^{3x} - xe^{3x} - 6x - 6 = 0$ \\
Move the terms without $x$ as a factor to the right: \\
$2e^{3x} - 6 = xe^{3x} + 6x$ \\
Factorise out $x$ on the right: \\
$2e^{3x} - 6 = x(e^{3x} + 6)$ \\
Divide by $(e^{3x} + 6)$: \\
$x = \frac{2e^{3x} - 6}{e^{3x} + 6}$ as required \\
(c) Staircase diagram: start at $x = 1$ on the $x$ axis, go up to the curve \\
Then go across to the line $y = x$ \\
Then go up to the curve again, then across to the line again \\
The steps move to the right, away from $x = 1$, and towards the root $\beta$ \\
(Diagram: vertical line from $x = 1$ up to the curve, horizontal to $y = x$, vertical to the curve, and so on, climbing towards the intersection at $\beta$) \\
(d)(i) $x_{2} = \frac{2e^{3x_{1}} - 6}{e^{3x_{1}} + 6}$ with $x_{1} = 1$ \\
$e^{3} = 20.0855$ \\
$2e^{3} - 6 = 34.1711$ \\
$e^{3} + 6 = 26.0855$ \\
$x_{2} = \frac{34.1711}{26.0855}$ \\
$x_{2} = 1.30996$ \\
$x_{2} = 1.310$ to 3 decimal places \\
(ii) Keep iterating with the ANS key: \\
$x_{3} = 1.68366$ \\
$x_{4} = 1.88901$ \\
$x_{5} = 1.93902$ \\
$x_{6} = 1.94737$ \\
$x_{7} = 1.94864$ \\
$x_{8} = 1.94884$ \\
The values settle at 1.949 \\
$\beta = 1.949$ to 3 decimal places \\
(e) Let $h(x) = \frac{2e^{3x} - 6}{e^{3x} + 6} - x$ \\
A root of $h(x) = 0$ is a solution of the equation \\
To show $\alpha = 0.676$ to 3 decimal places, use the interval $[0.6755, 0.6765]$ \\
At $x = 0.6755$: $e^{3x} = 7.58748$ \\
$\frac{2(7.58748) - 6}{7.58748 + 6} = \frac{9.17497}{13.58748} = 0.67525$ \\
$h(0.6755) = 0.67525 - 0.6755 = -0.00025$, which is negative \\
At $x = 0.6765$: $e^{3x} = 7.61028$ \\
$\frac{2(7.61028) - 6}{7.61028 + 6} = \frac{9.22056}{13.61028} = 0.67747$ \\
$h(0.6765) = 0.67747 - 0.6765 = 0.00097$, which is positive \\
$h(x)$ is continuous and changes sign on the interval \\
So there is a root between 0.6755 and 0.6765 \\
So $\alpha = 0.676$ to 3 decimal places
