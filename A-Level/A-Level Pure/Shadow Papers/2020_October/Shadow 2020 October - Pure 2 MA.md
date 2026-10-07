@paper P2 Shadow October 2020

@q 1
@topic Trapezium rule, scaling, accuracy
@marks 5
@question
(a) There are 5 values of $y$, so 4 strips, each of width $h = 0.75$ \\
Trapezium rule: $\frac{h}{2}\left\{ y_{0} + y_{4} + 2(y_{1} + y_{2} + y_{3}) \right\}$ \\
$y_{0} = 0.5108$ and $y_{4} = 0.9258$ \\
Add them: $0.5108 + 0.9258 = 1.4366$ \\
Middle values: $0.6794 + 0.7878 + 0.8660 = 2.3332$ \\
Double them: $2 \times 2.3332 = 4.6664$ \\
$\frac{0.75}{2}\left\{ 1.4366 + 4.6664 \right\}$ \\
$= 0.375 \times 6.1030$ \\
$= 2.2886$ \\
The estimate is 2.29 to 3 significant figures \\
(b) Write the new integrand using $\sqrt{32} = \sqrt{16 \times 2} = 4\sqrt{2}$ \\
$\sqrt{\frac{32x}{5 + x}} = \sqrt{16} \times \sqrt{\frac{2x}{5 + x}}$ \\
$= 4\sqrt{\frac{2x}{5 + x}}$ \\
So the new integral is 4 times the integral in part (a) \\
$\int_{0.75}^{3.75} \sqrt{\frac{32x}{5 + x}} dx = 4 \times \int_{0.75}^{3.75} \sqrt{\frac{2x}{5 + x}} dx$ \\
$\approx 4 \times 2.29$ \\
$\approx 9.16$ \\
(c) The true value is 9.196 and the estimate is 9.16 \\
Difference: $9.196 - 9.16 = 0.036$ \\
As a percentage of the true value: $\frac{0.036}{9.196} \times 100 = 0.39$ percent \\
The estimate is very accurate (less than 1 percent out), though it is a slight underestimate

@q 2
@topic Vectors, point dividing PR, show q
@marks 3
@question
$Q$ lies one fifth of the way from $P$ to $R$, and $P$, $Q$, $R$ are in a line \\
So $\text{PQ}$ is one fifth of $\text{PR}$ \\
$\text{PQ} = \frac{1}{5}\text{PR}$ \\
Write each vector as a difference of position vectors: \\
$\text{PQ} = \mathbf{q} - \mathbf{p}$ \\
$\text{PR} = \mathbf{r} - \mathbf{p}$ \\
$\mathbf{q} - \mathbf{p} = \frac{1}{5}(\mathbf{r} - \mathbf{p})$ \\
Multiply both sides by 5: \\
$5\mathbf{q} - 5\mathbf{p} = \mathbf{r} - \mathbf{p}$ \\
Add $5\mathbf{p}$ to both sides: \\
$5\mathbf{q} = \mathbf{r} - \mathbf{p} + 5\mathbf{p}$ \\
$5\mathbf{q} = \mathbf{r} + 4\mathbf{p}$ \\
Divide by 5: \\
$\mathbf{q} = \frac{1}{5}(\mathbf{r} + 4\mathbf{p})$ as required

@q 3
@topic Log equation, reject invalid root
@marks 5
@question
(a) Use the power law on the left hand side: $2\log (5 - x) = \log (5 - x)^{2}$ \\
$\log (5 - x)^{2} = \log (x + 7)$ \\
Logs of the same base are equal when what is inside is equal: \\
$(5 - x)^{2} = x + 7$ \\
Expand the bracket: $(5 - x)^{2} = 25 - 10x + x^{2}$ \\
$25 - 10x + x^{2} = x + 7$ \\
Subtract $x$ from both sides: \\
$25 - 11x + x^{2} = 7$ \\
Subtract 7 from both sides: \\
$18 - 11x + x^{2} = 0$ \\
$x^{2} - 11x + 18 = 0$ as required \\
(b)(i) Factorise: $(x - 2)(x - 9) = 0$ \\
$x = 2$ or $x = 9$ \\
(ii) Try $x = 9$ in $\log (5 - x)$: $5 - 9 = -4$ \\
You cannot take the log of a negative number, so $\log (5 - 9)$ cannot be found \\
$x = 9$ is not a solution \\
(Check $x = 2$: $2\log 3 = \log 9$ and $\log (2 + 7) = \log 9$)

@q 4
@topic Binomial coefficient, find a
@marks 3
@question
The term in $x^{5}$ is $^{9}C_{5} \times a^{9-5} \times (3x)^{5}$ \\
$^{9}C_{5} = \frac{9!}{5!4!}$ \\
$= \frac{9 \times 8 \times 7 \times 6}{4 \times 3 \times 2 \times 1}$ \\
$= 126$ \\
$(3x)^{5} = 3^{5}x^{5} = 243x^{5}$ \\
Term in $x^{5}$: $126 \times a^{4} \times 243x^{5}$ \\
Multiply the numbers: $126 \times 243 = 30618$ \\
The coefficient of $x^{5}$ is $30618a^{4}$ \\
Set this equal to 489 888: \\
$30618a^{4} = 489888$ \\
Divide both sides by 30618: \\
$a^{4} = 16$ \\
Take the fourth root: \\
$a = \pm 2$ \\
(Check: $30618 \times 2^{4} = 30618 \times 16 = 489888$, and $(-2)^{4}$ is also 16)

@q 5
@topic Exponential equation, exact x
@marks 4
@question
At the point $P$ both equations give the same $y$ value, so set them equal: \\
$6 \times 3^{x} = 60 - 3^{x+2}$ \\
Use the index law $3^{x+2} = 3^{x} \times 3^{2}$ \\
$3^{x+2} = 9 \times 3^{x}$ \\
$6 \times 3^{x} = 60 - 9 \times 3^{x}$ \\
Add $9 \times 3^{x}$ to both sides: \\
$15 \times 3^{x} = 60$ \\
Divide both sides by 15: \\
$3^{x} = 4$ \\
Take logs (base 3) of both sides: \\
$x = \log_{3} 4$ \\
(Check: $\log_{3} 4 = \frac{\ln 4}{\ln 3} = 1.2619$, and $3^{1.2619} = 4$)

@q 6
@topic Algebraic division, ln integral
@marks 7
@question
(a) Multiply both sides by $(x + 4)$: \\
$x^{2} + 10x - 5 = (Ax + B)(x + 4) + C$ \\
Expand the bracket: \\
$(Ax + B)(x + 4) = Ax^{2} + 4Ax + Bx + 4B$ \\
$x^{2} + 10x - 5 = Ax^{2} + (4A + B)x + (4B + C)$ \\
Compare the coefficients of $x^{2}$: $A = 1$ \\
Compare the coefficients of $x$: $4A + B = 10$ \\
$4(1) + B = 10$ \\
$B = 6$ \\
Compare the constant terms: $4B + C = -5$ \\
$4(6) + C = -5$ \\
$24 + C = -5$ \\
$C = -29$ \\
So $A = 1$, $B = 6$, $C = -29$ \\
(b) Use the result of part (a): \\
$\frac{x^{2} + 10x - 5}{x + 4} = x + 6 - \frac{29}{x + 4}$ \\
Integrate each term: \\
$\int \left( x + 6 - \frac{29}{x + 4} \right) dx = \frac{1}{2}x^{2} + 6x - 29\ln (x + 4)$ \\
Upper limit $x = 8$: $\frac{1}{2}(8)^{2} + 6(8) - 29\ln 12$ \\
$= 32 + 48 - 29\ln 12$ \\
$= 80 - 29\ln 12$ \\
Lower limit $x = 0$: $0 + 0 - 29\ln 4$ \\
$= -29\ln 4$ \\
Subtract the lower limit from the upper limit: \\
$80 - 29\ln 12 - (-29\ln 4)$ \\
$= 80 - 29\ln 12 + 29\ln 4$ \\
Take out the factor 29: \\
$= 80 - 29(\ln 12 - \ln 4)$ \\
Use $\ln a - \ln b = \ln \frac{a}{b}$: \\
$= 80 - 29\ln \frac{12}{4}$ \\
$= 80 - 29\ln 3$ \\
So $a = 80$ and $b = -29$

@q 7
@topic Differentiate, turning point, iteration
@marks 10
@question
(a) Split the fraction into separate powers of $x$: \\
$\frac{16x^{2}}{4\sqrt{x}} = 4x^{2 - \frac{1}{2}} = 4x^{\frac{3}{2}}$ \\
$\frac{x}{4\sqrt{x}} = \frac{1}{4}x^{1 - \frac{1}{2}} = \frac{1}{4}x^{\frac{1}{2}}$ \\
$y = 4x^{\frac{3}{2}} + \frac{1}{4}x^{\frac{1}{2}} - 6\ln x$ \\
Differentiate each term: \\
$4x^{\frac{3}{2}} \to 4 \times \frac{3}{2}x^{\frac{1}{2}} = 6x^{\frac{1}{2}}$ \\
$\frac{1}{4}x^{\frac{1}{2}} \to \frac{1}{4} \times \frac{1}{2}x^{-\frac{1}{2}} = \frac{1}{8}x^{-\frac{1}{2}}$ \\
$-6\ln x \to -\frac{6}{x}$ \\
$\frac{dy}{dx} = 6\sqrt{x} + \frac{1}{8\sqrt{x}} - \frac{6}{x}$ \\
Write each term over the common denominator $8x\sqrt{x}$ \\
$6\sqrt{x} = \frac{6\sqrt{x} \times 8x\sqrt{x}}{8x\sqrt{x}}$ \\
$\sqrt{x} \times \sqrt{x} = x$, so $6\sqrt{x} = \frac{48x^{2}}{8x\sqrt{x}}$ \\
$\frac{1}{8\sqrt{x}} = \frac{x}{8x\sqrt{x}}$ \\
$\frac{6}{x} = \frac{48\sqrt{x}}{8x\sqrt{x}}$ \\
$\frac{dy}{dx} = \frac{48x^{2} + x - 48\sqrt{x}}{8x\sqrt{x}}$ as required \\
(b) At the minimum turning point $\frac{dy}{dx} = 0$ \\
The bottom $8x\sqrt{x}$ is never zero for $x > 0$, so the top is zero: \\
$48x^{2} + x - 48\sqrt{x} = 0$ \\
Divide every term by $\sqrt{x}$: \\
$48x^{\frac{3}{2}} + x^{\frac{1}{2}} - 48 = 0$ \\
Add 48 and subtract $\sqrt{x}$ on both sides: \\
$48x^{\frac{3}{2}} = 48 - \sqrt{x}$ \\
Divide by 48: \\
$x^{\frac{3}{2}} = 1 - \frac{\sqrt{x}}{48}$ \\
Raise both sides to the power $\frac{2}{3}$: \\
$x = \left( 1 - \frac{\sqrt{x}}{48} \right)^{\frac{2}{3}}$ as required \\
(c)(i) Put $x_{1} = 3$ into the formula: \\
$x_{2} = \left( 1 - \frac{\sqrt{3}}{48} \right)^{\frac{2}{3}}$ \\
$\sqrt{3} = 1.73205$ \\
$\frac{\sqrt{3}}{48} = 0.036084$ \\
$1 - 0.036084 = 0.963916$ \\
$x_{2} = 0.963916^{\frac{2}{3}}$ \\
$x_{2} = 0.9758$ to 4 decimal places \\
(ii) Keep going with the ANS key: \\
$x_{3} = 0.98623$ \\
$x_{4} = 0.98616$ \\
$x_{5} = 0.98616$ \\
The values have settled at 0.9862 \\
Check with the sign change of $h(x) = 48x^{\frac{3}{2}} + x^{\frac{1}{2}} - 48$: \\
$h(0.98615) = -0.0007$, which is negative \\
$h(0.98625) = 0.0065$, which is positive \\
So the root lies between 0.98615 and 0.98625 \\
The $x$ coordinate of $P$ is 0.9862 to 4 decimal places

@q 8
@topic Integrate, factor theorem, find f(x)
@marks 6
@question
Integrate $f'(x) = 9x^{2} + ax + 5$ to find $f(x)$: \\
$f(x) = \frac{9x^{3}}{3} + \frac{ax^{2}}{2} + 5x + c$ \\
$f(x) = 3x^{3} + \frac{1}{2}ax^{2} + 5x + c$ \\
The $y$ intercept is $-3$, so $f(0) = -3$ \\
$f(0) = c$, so $c = -3$ \\
$f(x) = 3x^{3} + \frac{1}{2}ax^{2} + 5x - 3$ \\
$(x + 3)$ is a factor, so by the factor theorem $f(-3) = 0$ \\
$f(-3) = 3(-3)^{3} + \frac{1}{2}a(-3)^{2} + 5(-3) - 3$ \\
Evaluate each part: \\
$3(-27) = -81$ \\
$\frac{1}{2}a(9) = 4.5a$ \\
$5(-3) = -15$ \\
$f(-3) = -81 + 4.5a - 15 - 3$ \\
Collect the numbers: $-81 - 15 - 3 = -99$ \\
$f(-3) = 4.5a - 99$ \\
Set this equal to zero: \\
$4.5a - 99 = 0$ \\
Add 99 to both sides: \\
$4.5a = 99$ \\
Divide by 4.5: \\
$a = 22$ \\
Put $a = 22$ back: $\frac{1}{2}a = 11$ \\
$f(x) = 3x^{3} + 11x^{2} + 5x - 3$ \\
(Check: $(x + 3)(3x^{2} + 2x - 1) = 3x^{3} + 2x^{2} - x + 9x^{2} + 6x - 3$) \\
$= 3x^{3} + 11x^{2} + 5x - 3$

@q 9
@topic Exponential heating model, evaluate
@marks 6
@question
(a) At $t = 0$ the temperature is 20: \\
$20 = A - Be^{0}$ \\
$e^{0} = 1$, so $A - B = 20$ \\
Equation 1: $A - B = 20$ \\
At $t = 8$ the temperature is 42: \\
$42 = A - Be^{-0.08 \times 8}$ \\
$-0.08 \times 8 = -0.64$ \\
Equation 2: $A - Be^{-0.64} = 42$ \\
Subtract equation 1 from equation 2: \\
$(A - Be^{-0.64}) - (A - B) = 42 - 20$ \\
$-Be^{-0.64} + B = 22$ \\
Factorise out $B$: \\
$B(1 - e^{-0.64}) = 22$ \\
$e^{-0.64} = 0.52729$ \\
$1 - 0.52729 = 0.47271$ \\
Divide by 0.47271: \\
$B = \frac{22}{0.47271}$ \\
$B = 46.540$ \\
From equation 1: $A = 20 + B$ \\
$A = 66.540$ \\
To 3 significant figures $A = 66.5$ and $B = 46.5$ \\
$\theta = 66.5 - 46.5e^{-0.08t}$ \\
(b) As $t$ gets large, $e^{-0.08t}$ gets close to 0 \\
So $\theta$ gets close to $A = 66.5$ \\
The model says the temperature can never go above 66.5 degrees C \\
But ethanol boils at about 80 degrees C, and the ethanol was heated until it reached boiling point \\
The model's limit of 66.5 is much lower than 80, so it is not a good model

@q 10
@topic sin 3A identity, cubic in sin x
@marks 8
@question
(a) Write $3A$ as $2A + A$ and use the addition formula: \\
$\sin 3A = \sin (2A + A)$ \\
$\sin 3A = \sin 2A\cos A + \cos 2A\sin A$ \\
Use $\sin 2A = 2\sin A\cos A$ and $\cos 2A = 1 - 2\sin^{2} A$ \\
$\sin 3A = 2\sin A\cos A \times \cos A + (1 - 2\sin^{2} A)\sin A$ \\
$\sin 3A = 2\sin A\cos^{2} A + (1 - 2\sin^{2} A)\sin A$ \\
Use $\cos^{2} A = 1 - \sin^{2} A$ \\
$\sin 3A = 2\sin A(1 - \sin^{2} A) + (1 - 2\sin^{2} A)\sin A$ \\
Expand the first term: $2\sin A - 2\sin^{3} A$ \\
Expand the second term: $\sin A - 2\sin^{3} A$ \\
$\sin 3A = 2\sin A - 2\sin^{3} A + \sin A - 2\sin^{3} A$ \\
Collect like terms: \\
$\sin 3A = 3\sin A - 4\sin^{3} A$ as required \\
(b) Use part (a) with $A = x$: $\sin 3x = 3\sin x - 4\sin^{3} x$ \\
Use $\cos^{2} x = 1 - \sin^{2} x$ \\
$1 - (3\sin x - 4\sin^{3} x) = 1 - \sin^{2} x$ \\
Expand the bracket: \\
$1 - 3\sin x + 4\sin^{3} x = 1 - \sin^{2} x$ \\
Subtract 1 from both sides: \\
$-3\sin x + 4\sin^{3} x = -\sin^{2} x$ \\
Add $\sin^{2} x$ to both sides: \\
$4\sin^{3} x + \sin^{2} x - 3\sin x = 0$ \\
Factorise out $\sin x$ (do not divide by it): \\
$\sin x(4\sin^{2} x + \sin x - 3) = 0$ \\
Factorise the quadratic in $\sin x$: \\
$4\sin^{2} x + \sin x - 3 = (4\sin x - 3)(\sin x + 1)$ \\
$\sin x(4\sin x - 3)(\sin x + 1) = 0$ \\
Case 1: $\sin x = 0$ \\
$x = 0$ or $x = 180$ degrees \\
Case 2: $4\sin x - 3 = 0$ \\
$\sin x = \frac{3}{4}$ \\
$x = 48.59$ degrees \\
Sine is positive in the second quadrant, so also $x = 180 - 48.59 = 131.41$ degrees \\
Case 3: $\sin x + 1 = 0$ \\
$\sin x = -1$ \\
$x = 270$ degrees, which is outside $0 \leq x \leq 180$, so reject \\
The solutions are $x = 0, 48.6, 131.4, 180$ degrees

@q 11
@topic Modulus graph, vertex, line intersection
@marks 7
@question
(a) The vertex of $y = 4|x + 3| - 7$ is where the modulus is zero \\
$x + 3 = 0$, so $x = -3$ \\
$y = 4(0) - 7 = -7$ \\
$P = (-3, -7)$ \\
(b) Solve $5x + 60 = 4|x + 3| - 7$ by splitting into two cases \\
Case 1: $x + 3 \geq 0$, so $|x + 3| = x + 3$ \\
$5x + 60 = 4(x + 3) - 7$ \\
$5x + 60 = 4x + 12 - 7$ \\
$5x + 60 = 4x + 5$ \\
Subtract $4x$ and 60: \\
$x = -55$ \\
$-55$ is not $\geq -3$, so reject \\
Case 2: $x + 3 < 0$, so $|x + 3| = -(x + 3)$ \\
$5x + 60 = -4(x + 3) - 7$ \\
$5x + 60 = -4x - 12 - 7$ \\
$5x + 60 = -4x - 19$ \\
Add $4x$ to both sides: \\
$9x + 60 = -19$ \\
Subtract 60: \\
$9x = -79$ \\
Divide by 9: \\
$x = -\frac{79}{9}$ \\
$-\frac{79}{9} = -8.78$, which is less than $-3$, so accept \\
$x = -\frac{79}{9}$ \\
(c) The right arm of the V, for $x \geq -3$, is $y = 4x + 5$ \\
The left arm, for $x < -3$, is $y = -4x - 19$ \\
Line $l$: $y = ax$ passes through the origin \\
Meeting the right arm: $ax = 4x + 5$ \\
Subtract $4x$: \\
$(a - 4)x = 5$ \\
If $a = 4$ this says $0 = 5$, so there is no intersection \\
If $a > 4$: $x = \frac{5}{a - 4}$ is positive, so it is on the right arm: an intersection \\
If $a < 4$: $x = \frac{5}{a - 4}$ is negative and must be at least $-3$ \\
$\frac{5}{a - 4} \geq -3$ \\
$a - 4$ is negative, so multiplying by it reverses the inequality: \\
$5 \leq -3(a - 4)$ \\
$5 \leq -3a + 12$ \\
Add $3a$ and subtract 5: \\
$3a \leq 7$ \\
$a \leq \frac{7}{3}$ \\
(When $a = \frac{7}{3}$ the line goes through the vertex $P$, since $\frac{-7}{-3} = \frac{7}{3}$) \\
Meeting the left arm: $ax = -4x - 19$, so $x = -\frac{19}{a + 4}$ \\
For this to be less than $-3$ needs $a < \frac{7}{3}$, which is already included above \\
So $l$ meets the graph for $a \leq \frac{7}{3}$ or $a > 4$ \\
$\{ a : a \leq \frac{7}{3} \} \text{ or } \{ a : a > 4 \}$

@q 12
@topic Parametric area, dam walkway width
@marks 11
@question
(a)(i) Area under a curve is $\int y \, dx$ \\
$x = 5\sin t$, so $\frac{dx}{dt} = 5\cos t$ \\
$dx = 5\cos t \, dt$ \\
$y = 9\sin 2t$ \\
Use $\sin 2t = 2\sin t\cos t$: $y = 18\sin t\cos t$ \\
$y \, dx = 18\sin t\cos t \times 5\cos t \, dt$ \\
Multiply the numbers: $18 \times 5 = 90$ \\
$y \, dx = 90\sin t\cos^{2} t \, dt$ \\
Limits: when $t = 0$, $x = 0$ \\
Limits: when $t = \frac{\pi}{2}$, $x = 5\sin \frac{\pi}{2} = 5$ \\
Area $= \int_{0}^{\frac{\pi}{2}} 90\sin t\cos^{2} t \, dt$ as required \\
(ii) Let $u = \cos t$, so $\frac{du}{dt} = -\sin t$ \\
$\sin t \, dt = -du$ \\
$\int 90\sin t\cos^{2} t \, dt = \int 90u^{2}(-du)$ \\
$= -90\int u^{2} du$ \\
$= -90 \times \frac{u^{3}}{3}$ \\
$= -30u^{3}$ \\
Replace $u$ by $\cos t$: $-30\cos^{3} t$ \\
Area $= \left[ -30\cos^{3} t \right]_{0}^{\frac{\pi}{2}}$ \\
Upper limit: $-30\cos^{3} \frac{\pi}{2} = -30 \times 0 = 0$ \\
Lower limit: $-30\cos^{3} 0 = -30 \times 1 = -30$ \\
Subtract: $0 - (-30)$ \\
Area $= 30$ exactly \\
(b) The wall is 5.3 m high, so the top of the dam is at $y = 5.3$ \\
$9\sin 2t = 5.3$ \\
Divide by 9: \\
$\sin 2t = \frac{5.3}{9}$ \\
$\sin 2t = 0.58889$ \\
$2t = \sin^{-1}(0.58889)$ \\
$2t = 0.62968$ \\
$t = 0.31484$ \\
Sine is also positive in the second quadrant: \\
$2t = \pi - 0.62968$ \\
$2t = 2.51191$ \\
$t = 1.25595$ \\
The smaller $t$ is the point $M$ on the rising part, and the larger $t$ is the point $N$ on the falling part \\
Find $x$ at $M$: $x = 5\sin 0.31484$ \\
$x_{M} = 5 \times 0.30966$ \\
$x_{M} = 1.5483$ \\
Find $x$ at $N$: $x = 5\sin 1.25595$ \\
$x_{N} = 5 \times 0.95084$ \\
$x_{N} = 4.7542$ \\
Width of the walkway $= x_{N} - x_{M}$ \\
$= 4.7542 - 1.5483$ \\
$= 3.2059$ \\
The walkway is 3.21 m wide

@q 13
@topic Domain, g'(x) positive, inequality
@marks 6
@question
(a) $g(x)$ is not defined when the denominator is zero \\
$\ln x - 1 = 0$ \\
$\ln x = 1$ \\
$x = e$ \\
So $k = e$ \\
(b) Use the quotient rule with $u = 5\ln x - 6$ and $v = \ln x - 1$ \\
$\frac{du}{dx} = \frac{5}{x}$ \\
$\frac{dv}{dx} = \frac{1}{x}$ \\
$g'(x) = \frac{\frac{du}{dx}v - u\frac{dv}{dx}}{v^{2}}$ \\
$g'(x) = \frac{\frac{5}{x}(\ln x - 1) - (5\ln x - 6)\frac{1}{x}}{(\ln x - 1)^{2}}$ \\
Take out the factor $\frac{1}{x}$ on the top: \\
$g'(x) = \frac{\frac{1}{x}\left[ 5(\ln x - 1) - (5\ln x - 6) \right]}{(\ln x - 1)^{2}}$ \\
Expand the brackets: $5\ln x - 5 - 5\ln x + 6$ \\
The $5\ln x$ terms cancel: $-5 + 6 = 1$ \\
$g'(x) = \frac{\frac{1}{x} \times 1}{(\ln x - 1)^{2}}$ \\
$g'(x) = \frac{1}{x(\ln x - 1)^{2}}$ \\
In the domain $x > 0$, so $x$ is positive \\
Also $x \ne e$, so $\ln x - 1 \ne 0$, and the square $(\ln x - 1)^{2}$ is positive \\
A positive number divided by a positive number is positive \\
So $g'(x) > 0$ for all $x$ in the domain \\
(c) Set $L = \ln a$, so $g(a) = \frac{5L - 6}{L - 1}$ \\
A fraction is positive when top and bottom have the same sign \\
Both positive: $5L - 6 > 0$ gives $L > \frac{6}{5}$, and $L - 1 > 0$ gives $L > 1$ \\
Both are true when $L > \frac{6}{5}$ \\
Both negative: $5L - 6 < 0$ gives $L < \frac{6}{5}$, and $L - 1 < 0$ gives $L < 1$ \\
Both are true when $L < 1$ \\
So $\ln a < 1$ or $\ln a > \frac{6}{5}$ \\
Take exponentials of each inequality: \\
$a < e$ (and $a > 0$ so that $\ln a$ exists) \\
$a > e^{\frac{6}{5}}$ \\
$0 < a < e$ or $a > e^{\frac{6}{5}}$

@q 14
@topic Circle in first quadrant, tangent line
@marks 7
@question
(a) The circle is in the 1st quadrant and touches both axes \\
So its centre is $(r, r)$ and its radius is $r$ \\
$(x - r)^{2} + (y - r)^{2} = r^{2}$ \\
The line is $y + 2x = 8$, so $y = 8 - 2x$ \\
Substitute for $y$: \\
$(x - r)^{2} + (8 - 2x - r)^{2} = r^{2}$ \\
Expand the first bracket: $(x - r)^{2} = x^{2} - 2rx + r^{2}$ \\
Expand the second bracket, treating it as $\left[ (8 - r) - 2x \right]^{2}$: \\
$(8 - r)^{2} - 4x(8 - r) + 4x^{2}$ \\
$(8 - r)^{2} = 64 - 16r + r^{2}$ \\
$-4x(8 - r) = -32x + 4rx$ \\
Second bracket $= 4x^{2} + 4rx - 32x + r^{2} - 16r + 64$ \\
Add the two brackets: \\
$x^{2} - 2rx + r^{2} + 4x^{2} + 4rx - 32x + r^{2} - 16r + 64 = r^{2}$ \\
Subtract $r^{2}$ from both sides: \\
$x^{2} - 2rx + r^{2} + 4x^{2} + 4rx - 32x - 16r + 64 = 0$ \\
Collect the $x^{2}$ terms: $x^{2} + 4x^{2} = 5x^{2}$ \\
Collect the $x$ terms: $-2rx + 4rx - 32x = (2r - 32)x$ \\
Collect the rest: $r^{2} - 16r + 64$ \\
$5x^{2} + (2r - 32)x + (r^{2} - 16r + 64) = 0$ as required \\
(b) A tangent meets the circle at one point, so the quadratic has equal roots \\
The discriminant is zero: $b^{2} - 4ac = 0$ \\
Here $a = 5$, $b = 2r - 32$, $c = r^{2} - 16r + 64$ \\
$(2r - 32)^{2} - 4(5)(r^{2} - 16r + 64) = 0$ \\
Expand the first term: $(2r - 32)^{2} = 4r^{2} - 128r + 1024$ \\
Expand the second term: $20(r^{2} - 16r + 64) = 20r^{2} - 320r + 1280$ \\
$4r^{2} - 128r + 1024 - 20r^{2} + 320r - 1280 = 0$ \\
Collect like terms: \\
$-16r^{2} + 192r - 256 = 0$ \\
Divide by $-16$: \\
$r^{2} - 12r + 16 = 0$ \\
Complete the square: $r^{2} - 12r = (r - 6)^{2} - 36$ \\
$(r - 6)^{2} - 36 + 16 = 0$ \\
$(r - 6)^{2} = 20$ \\
Square root both sides: \\
$r - 6 = \pm \sqrt{20}$ \\
Simplify the surd: $\sqrt{20} = \sqrt{4 \times 5} = 2\sqrt{5}$ \\
$r = 6 \pm 2\sqrt{5}$ \\
Both values are positive ($10.47$ and $1.53$), so both are possible \\
$r = 6 + 2\sqrt{5}$ or $r = 6 - 2\sqrt{5}$

@q 15
@topic Geometric series proof, S12 = 8 S6
@marks 8
@question
(a) Write out the sum: \\
$S_{n} = a + ar + ar^{2} + \ldots + ar^{n-1}$ \\
Multiply every term by $r$: \\
$rS_{n} = ar + ar^{2} + ar^{3} + \ldots + ar^{n}$ \\
Subtract the second line from the first: \\
$S_{n} - rS_{n} = a - ar^{n}$ \\
(all the middle terms cancel in pairs) \\
Factorise both sides: \\
$S_{n}(1 - r) = a(1 - r^{n})$ \\
Divide by $(1 - r)$, which is not zero since $r \ne 1$: \\
$S_{n} = \frac{a(1 - r^{n})}{1 - r}$ as required \\
(b) Use the formula for $S_{12}$ and $S_{6}$: \\
$\frac{a(1 - r^{12})}{1 - r} = 8 \times \frac{a(1 - r^{6})}{1 - r}$ \\
Multiply both sides by $\frac{1 - r}{a}$ (allowed as $a \ne 0$ and $r \ne 1$): \\
$1 - r^{12} = 8(1 - r^{6})$ \\
Expand the bracket: \\
$1 - r^{12} = 8 - 8r^{6}$ \\
Add $r^{12}$ and subtract 1 from both sides: \\
$0 = r^{12} - 8r^{6} + 7$ \\
Let $u = r^{6}$, so $r^{12} = u^{2}$ \\
$u^{2} - 8u + 7 = 0$ \\
Factorise: \\
$(u - 7)(u - 1) = 0$ \\
$u = 7$ or $u = 1$ \\
$u = 1$ means $r^{6} = 1$, so $r = \pm 1$ \\
$r = 1$ is not allowed, and $r = -1$ makes $S_{6} = S_{12} = 0$, which is not a useful case \\
$u = 7$ means $r^{6} = 7$ \\
Take the sixth root: \\
$r = \sqrt[6]{7}$ \\
(The negative root $-\sqrt[6]{7}$ also satisfies the equation)

@q 16
@topic Proof, squares mod 5
@marks 4
@question
When any natural number is divided by 5, the remainder is 0, 1, 2, 3 or 4 \\
So every natural number can be written as $5k$, $5k + 1$, $5k + 2$, $5k + 3$ or $5k + 4$, where $k$ is a whole number \\
Square each case \\
Case $5k$: \\
$(5k)^{2} = 25k^{2}$ \\
$= 5(5k^{2})$ \\
This is a multiple of 5 \\
Case $5k + 1$: \\
$(5k + 1)^{2} = 25k^{2} + 10k + 1$ \\
$= 5(5k^{2} + 2k) + 1$ \\
This is one more than a multiple of 5 \\
Case $5k + 2$: \\
$(5k + 2)^{2} = 25k^{2} + 20k + 4$ \\
$= 5(5k^{2} + 4k) + 4$ \\
This is four more than a multiple of 5 \\
Case $5k + 3$: \\
$(5k + 3)^{2} = 25k^{2} + 30k + 9$ \\
Write $9 = 5 + 4$ \\
$= 5(5k^{2} + 6k + 1) + 4$ \\
This is four more than a multiple of 5 \\
Case $5k + 4$: \\
$(5k + 4)^{2} = 25k^{2} + 40k + 16$ \\
Write $16 = 15 + 1$ \\
$= 5(5k^{2} + 8k + 3) + 1$ \\
This is one more than a multiple of 5 \\
All five cases give a multiple of 5, or one more, or four more than a multiple of 5 \\
So the square of any natural number is either a multiple of 5 or one or four more than a multiple of 5 as required
