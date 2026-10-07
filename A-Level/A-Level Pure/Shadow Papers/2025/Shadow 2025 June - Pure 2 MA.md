@paper P2 Shadow June 2025

@q 1
@topic Factorise a cubic completely
@marks 3
@question
Take out the common factor $2x$ from every term: \\
$2x^{3} = 2x \times x^{2}$ \\
$-22x^{2} = 2x \times (-11x)$ \\
$60x = 2x \times 30$ \\
$2x^{3} - 22x^{2} + 60x = 2x(x^{2} - 11x + 30)$ \\
Factorise the quadratic. Two numbers that multiply to $+30$ and add to $-11$ are $-5$ and $-6$ \\
(Check: $(-5) \times (-6) = 30$ and $(-5) + (-6) = -11$) \\
$x^{2} - 11x + 30 = (x - 5)(x - 6)$ \\
$2x^{3} - 22x^{2} + 60x = 2x(x - 5)(x - 6)$ \\
(Check by expanding: $(x - 5)(x - 6) = x^{2} - 6x - 5x + 30 = x^{2} - 11x + 30$)

@q 2
@topic Integrate x^3 - 9x^(1/2) + 4
@marks 4
@question
Integrate each term: add 1 to the power and divide by the new power \\
$x^{3}$: the new power is $3 + 1 = 4$, so we get $\frac{x^{4}}{4}$ \\
$-9x^{\frac{1}{2}}$: the new power is $\frac{1}{2} + 1 = \frac{3}{2}$, so we get $-9 \times x^{\frac{3}{2}} \div \frac{3}{2}$ \\
Dividing by $\frac{3}{2}$ is the same as multiplying by $\frac{2}{3}$: \\
$-9 \times \frac{2}{3}x^{\frac{3}{2}}$ \\
$= -\frac{18}{3}x^{\frac{3}{2}}$ \\
$= -6x^{\frac{3}{2}}$ \\
$4$ is $4x^{0}$, so the new power is 1 and we get $4x$ \\
Do not forget the constant of integration: \\
$\int \left( x^{3} - 9x^{\frac{1}{2}} + 4 \right) dx = \frac{x^{4}}{4} - 6x^{\frac{3}{2}} + 4x + c$

@q 3
@topic Logs: 5^x = 2^y, exact x/y
@marks 2
@question
Take natural logs of both sides: \\
$\ln (5^{x}) = \ln (2^{y})$ \\
Use the power law $\ln (a^{n}) = n \ln a$ on each side: \\
$x \ln 5 = y \ln 2$ \\
We want $\frac{x}{y}$, so divide both sides by $y$: \\
$\frac{x \ln 5}{y} = \ln 2$ \\
Then divide both sides by $\ln 5$: \\
$\frac{x}{y} = \frac{\ln 2}{\ln 5}$ \\
(Check: take $y = 1$, then $x = \frac{\ln 2}{\ln 5} = 0.4307$ and $5^{0.4307} = 2$, which equals $2^{1}$)

@q 4
@topic Triangle with sector, angle and area
@marks 5
@question
(a) $C$ lies on $BD$ and $BC = BA$, so angle $ABC$ is the same as angle $ABD$ \\
Let $\phi$ be angle $ABD$, which is also angle $ABC$ \\
Use the cosine rule in triangle $ABD$. The angle $\phi$ is opposite side $AD$: \\
$AD^{2} = BA^{2} + BD^{2} - 2(BA)(BD)\cos \phi$ \\
$8.2^{2} = 11^{2} + 17^{2} - 2(11)(17)\cos \phi$ \\
Evaluate the squares: $8.2^{2} = 67.24$, $11^{2} = 121$ and $17^{2} = 289$ \\
Evaluate $2(11)(17) = 374$ \\
$67.24 = 121 + 289 - 374\cos \phi$ \\
$67.24 = 410 - 374\cos \phi$ \\
Add $374\cos \phi$ to both sides: \\
$374\cos \phi + 67.24 = 410$ \\
Subtract 67.24 from both sides: \\
$374\cos \phi = 342.76$ \\
Divide both sides by 374: \\
$\cos \phi = \frac{342.76}{374}$ \\
$\cos \phi = 0.916470...$ \\
Take the inverse cosine, with the calculator in radian mode: \\
$\phi = \cos^{-1}(0.916470...)$ \\
$\phi = 0.411628...$ \\
$\phi = 0.412$ radians to 3 sf \\
So angle $ABC = 0.412$ radians to 3 significant figures, as required \\
(b) Area of $R$ = area of triangle $ABD$ minus area of sector $ABC$ \\
Triangle $ABD$: use area $= \frac{1}{2}ab\sin C$ with sides $BA$ and $BD$ and the angle $\phi$ between them \\
Area $= \frac{1}{2}(11)(17)\sin (0.411628...)$ \\
$\frac{1}{2} \times 11 \times 17 = 93.5$ \\
$\sin (0.411628...) = 0.400102...$ \\
Area of triangle $= 93.5 \times 0.400102...$ \\
$= 37.4095...$ \\
Sector $ABC$ has radius $BA = 11$ and angle $\phi$. Use sector area $= \frac{1}{2}r^{2}\phi$ \\
Area of sector $= \frac{1}{2}(11)^{2}(0.411628...)$ \\
$= \frac{1}{2}(121)(0.411628...)$ \\
$= 60.5 \times 0.411628...$ \\
$= 24.9035...$ \\
Subtract the sector from the triangle: \\
Area of $R = 37.4095... - 24.9035...$ \\
$= 12.506...$ \\
Area of $R = 12.5$ cm$^{2}$ to 3 sf

@q 5
@topic Parametric: point, Cartesian, gradient
@marks 7
@question
(a) The point $P$ has $x = -2$, so use the $x$ equation to find $t$: \\
$\frac{t - 2}{3} = -2$ \\
Multiply both sides by 3: \\
$t - 2 = -6$ \\
Add 2 to both sides: \\
$t = -4$ \\
Substitute $t = -4$ into the $y$ equation: \\
$y = 4(-4 + 2)^{3}$ \\
$y = 4(-2)^{3}$ \\
$(-2)^{3} = -8$ \\
$y = 4 \times (-8)$ \\
$y = -32$ \\
(b) Eliminate $t$. Make $t$ the subject of $x = \frac{t - 2}{3}$ \\
Multiply both sides by 3: \\
$3x = t - 2$ \\
Add 2 to both sides: \\
$t = 3x + 2$ \\
Substitute into $y = 4(t + 2)^{3}$: \\
$y = 4(3x + 2 + 2)^{3}$ \\
$y = 4(3x + 4)^{3}$ \\
(c) Differentiate $y = 4(3x + 4)^{3}$ using the chain rule \\
Let $u = 3x + 4$, so $y = 4u^{3}$ \\
$\frac{du}{dx} = 3$ \\
$\frac{dy}{du} = 12u^{2}$ \\
$\frac{dy}{dx} = \frac{dy}{du} \times \frac{du}{dx}$ \\
$= 12u^{2} \times 3$ \\
$= 36u^{2}$ \\
Replace $u$ by $3x + 4$: \\
$\frac{dy}{dx} = 36(3x + 4)^{2}$ \\
At $P$, $x = -2$: \\
$\frac{dy}{dx} = 36(3(-2) + 4)^{2}$ \\
$= 36(-6 + 4)^{2}$ \\
$= 36(-2)^{2}$ \\
$= 36 \times 4$ \\
$= 144$ \\
The gradient of $C$ at $P$ is 144 \\
(Check using the parametric form: $\frac{dx}{dt} = \frac{1}{3}$ and $\frac{dy}{dt} = 12(t + 2)^{2} = 12(-2)^{2} = 48$ when $t = -4$, so $\frac{dy}{dx} = 48 \div \frac{1}{3} = 144$)

@q 6
@topic Small angle approximations
@marks 6
@question
(a) The small angle approximation is $\cos \theta \approx 1 - \frac{\theta^{2}}{2}$ \\
Replace $\theta$ by $3x$: \\
$\cos (3x) \approx 1 - \frac{(3x)^{2}}{2}$ \\
$(3x)^{2} = 9x^{2}$ \\
$\cos (3x) \approx 1 - \frac{9x^{2}}{2}$ \\
Square both sides: \\
$\cos^{2}(3x) \approx \left( 1 - \frac{9x^{2}}{2} \right)^{2}$ \\
Expand using $(1 - A)^{2} = 1 - 2A + A^{2}$ with $A = \frac{9x^{2}}{2}$ \\
$2A = 2 \times \frac{9x^{2}}{2} = 9x^{2}$ \\
$A^{2} = \frac{81x^{4}}{4}$ \\
$\cos^{2}(3x) \approx 1 - 9x^{2} + \frac{81}{4}x^{4}$ \\
Subtract from 1: \\
$1 - \cos^{2}(3x) \approx 1 - \left( 1 - 9x^{2} + \frac{81}{4}x^{4} \right)$ \\
Remove the bracket, changing every sign: \\
$= 1 - 1 + 9x^{2} - \frac{81}{4}x^{4}$ \\
$= 9x^{2} - \frac{81}{4}x^{4}$ as required \\
(b) The small angle approximation for tan is $\tan \theta \approx \theta$ \\
Replace $\theta$ by $\frac{x}{2}$: \\
$\tan \left( \frac{x}{2} \right) \approx \frac{x}{2}$ \\
Square both sides: \\
$\tan^{2} \left( \frac{x}{2} \right) \approx \frac{x^{2}}{4}$ \\
The top of the fraction, from part (a): \\
$1 - \cos^{2}(3x) \approx 9x^{2} - \frac{81}{4}x^{4}$ \\
The bottom of the fraction: \\
$\tan^{2} \left( \frac{x}{2} \right) \approx \frac{x^{2}}{4}$ \\
Dividing by $\frac{x^{2}}{4}$ is the same as multiplying by $\frac{4}{x^{2}}$: \\
$\frac{1 - \cos^{2}(3x)}{\tan^{2}(\frac{x}{2})} \approx \left( 9x^{2} - \frac{81}{4}x^{4} \right) \times \frac{4}{x^{2}}$ \\
Multiply each term by $\frac{4}{x^{2}}$: \\
$9x^{2} \times \frac{4}{x^{2}} = 36$ \\
$\frac{81}{4}x^{4} \times \frac{4}{x^{2}} = 81x^{2}$ \\
$\approx 36 - 81x^{2}$ \\
This is $a + bx^{2}$ with $a = 36$ and $b = -81$ \\
(c) $x$ is very small, so $x^{2}$ is extremely small and the term $-81x^{2}$ is close to 0 \\
As $x \to 0$ the expression $36 - 81x^{2}$ gets closer and closer to 36 \\
The approximate value is 36 \\
Reason: when $x$ is very small, $x^{2}$ is negligible, so $81x^{2}$ is negligible compared with 36

@q 7
@topic Algebraic division and partial fractions
@marks 4
@question
The top is a cubic and the bottom is a quadratic, so first divide \\
Expand the denominator: \\
$(x - 2)(x + 3) = x^{2} + 3x - 2x - 6$ \\
$= x^{2} + x - 6$ \\
Divide $2x^{3} + 5x^{2} - 12x - 7$ by $x^{2} + x - 6$ \\
First term: $2x^{3} \div x^{2} = 2x$ \\
Multiply the divisor by $2x$: \\
$2x(x^{2} + x - 6) = 2x^{3} + 2x^{2} - 12x$ \\
Subtract this from the cubic: \\
$(2x^{3} + 5x^{2} - 12x - 7) - (2x^{3} + 2x^{2} - 12x)$ \\
$= 3x^{2} + 0x - 7$ \\
Next term: $3x^{2} \div x^{2} = 3$ \\
Multiply the divisor by 3: \\
$3(x^{2} + x - 6) = 3x^{2} + 3x - 18$ \\
Subtract this from the remainder: \\
$(3x^{2} + 0x - 7) - (3x^{2} + 3x - 18)$ \\
$= -3x + 11$ \\
So the quotient is $2x + 3$ and the remainder is $-3x + 11$ \\
$\frac{2x^{3} + 5x^{2} - 12x - 7}{(x - 2)(x + 3)} = 2x + 3 + \frac{-3x + 11}{(x - 2)(x + 3)}$ \\
Compare with $Ax + B$: $A = 2$ and $B = 3$ \\
Now split the remainder fraction into partial fractions: \\
$\frac{-3x + 11}{(x - 2)(x + 3)} \equiv \frac{C}{x - 2} + \frac{D}{x + 3}$ \\
Multiply both sides by $(x - 2)(x + 3)$: \\
$-3x + 11 \equiv C(x + 3) + D(x - 2)$ \\
Let $x = 2$, which makes the $D$ term 0: \\
$-3(2) + 11 = C(2 + 3) + D(0)$ \\
$-6 + 11 = 5C$ \\
$5 = 5C$ \\
$C = 1$ \\
Let $x = -3$, which makes the $C$ term 0: \\
$-3(-3) + 11 = C(0) + D(-3 - 2)$ \\
$9 + 11 = -5D$ \\
$20 = -5D$ \\
Divide both sides by $-5$: \\
$D = -4$ \\
$A = 2$, $B = 3$, $C = 1$, $D = -4$ \\
(Check with $x = 0$: the left side is $\frac{-7}{(-2)(3)} = \frac{7}{6}$) \\
(The right side is $3 + \frac{1}{-2} + \frac{-4}{3} = \frac{18}{6} - \frac{3}{6} - \frac{8}{6} = \frac{7}{6}$)

@q 8
@topic Quartic stationary points, f(x) = k
@marks 9
@question
(a) A local maximum is a stationary point, so $f'(x) = 0$ there \\
Differentiate $f(x)$ term by term: \\
$x^{4} \to 4x^{3}$ \\
$-\frac{2}{3}x^{3} \to -\frac{2}{3} \times 3x^{2} = -2x^{2}$ \\
$-18x^{2} \to -36x$ \\
$ax \to a$ \\
$\frac{50}{3} \to 0$ \\
$f'(x) = 4x^{3} - 2x^{2} - 36x + a$ \\
Substitute $x = \frac{1}{2}$ and set $f'(\frac{1}{2}) = 0$: \\
$4 \left( \frac{1}{2} \right)^{3} - 2 \left( \frac{1}{2} \right)^{2} - 36 \left( \frac{1}{2} \right) + a = 0$ \\
Evaluate each term: \\
$4 \times \frac{1}{8} = \frac{1}{2}$ \\
$2 \times \frac{1}{4} = \frac{1}{2}$ \\
$36 \times \frac{1}{2} = 18$ \\
$\frac{1}{2} - \frac{1}{2} - 18 + a = 0$ \\
$-18 + a = 0$ \\
Add 18 to both sides: \\
$a = 18$ as required \\
(b) Substitute $a = 18$ to get $f(x) = x^{4} - \frac{2}{3}x^{3} - 18x^{2} + 18x + \frac{50}{3}$ \\
Now put in $x = \frac{1}{2}$: \\
$f \left( \frac{1}{2} \right) = \left( \frac{1}{2} \right)^{4} - \frac{2}{3} \left( \frac{1}{2} \right)^{3}$ \\
$\quad - 18 \left( \frac{1}{2} \right)^{2} + 18 \left( \frac{1}{2} \right) + \frac{50}{3}$ \\
Evaluate each term: \\
$\left( \frac{1}{2} \right)^{4} = \frac{1}{16}$ \\
$\frac{2}{3} \times \frac{1}{8} = \frac{2}{24} = \frac{1}{12}$ \\
$18 \times \frac{1}{4} = \frac{18}{4} = \frac{9}{2}$ \\
$18 \times \frac{1}{2} = 9$ \\
$f \left( \frac{1}{2} \right) = \frac{1}{16} - \frac{1}{12} - \frac{9}{2} + 9 + \frac{50}{3}$ \\
Write every term over the common denominator 48: \\
$\frac{1}{16} = \frac{3}{48}$ and $\frac{1}{12} = \frac{4}{48}$ and $\frac{9}{2} = \frac{216}{48}$ \\
$9 = \frac{432}{48}$ and $\frac{50}{3} = \frac{800}{48}$ \\
$= \frac{3 - 4 - 216 + 432 + 800}{48}$ \\
Work out the top: $3 - 4 = -1$, then $-1 - 216 = -217$, then $-217 + 432 = 215$, then $215 + 800 = 1015$ \\
$= \frac{1015}{48}$ \\
The local maximum has $y$ coordinate $\frac{1015}{48}$ \\
(c) The line $y = k$ meets $C$ four times when $k$ is above both minima and below the local maximum \\
Find all the stationary points. Set $f'(x) = 0$ with $a = 18$: \\
$4x^{3} - 2x^{2} - 36x + 18 = 0$ \\
Divide every term by 2: \\
$2x^{3} - x^{2} - 18x + 9 = 0$ \\
Group the terms in pairs: \\
$x^{2}(2x - 1) - 9(2x - 1) = 0$ \\
(Check: $-9(2x - 1) = -18x + 9$) \\
Take out the common bracket $(2x - 1)$: \\
$(2x - 1)(x^{2} - 9) = 0$ \\
Factorise the difference of two squares: \\
$(2x - 1)(x - 3)(x + 3) = 0$ \\
$x = \frac{1}{2}$ or $x = 3$ or $x = -3$ \\
Classify them with $f''(x) = 12x^{2} - 4x - 36$ \\
$f''(\frac{1}{2}) = 12(\frac{1}{4}) - 4(\frac{1}{2}) - 36 = 3 - 2 - 36 = -35 < 0$, so a maximum \\
$f''(3) = 12(9) - 4(3) - 36 = 108 - 12 - 36 = 60 > 0$, so a minimum \\
$f''(-3) = 12(9) - 4(-3) - 36 = 108 + 12 - 36 = 84 > 0$, so a minimum \\
Find the $y$ values at the minima: \\
$f(3) = 3^{4} - \frac{2}{3}(3^{3}) - 18(3^{2}) + 18(3) + \frac{50}{3}$ \\
$= 81 - \frac{2}{3}(27) - 18(9) + 54 + \frac{50}{3}$ \\
$= 81 - 18 - 162 + 54 + \frac{50}{3}$ \\
$= -45 + \frac{50}{3}$ \\
$= -\frac{135}{3} + \frac{50}{3}$ \\
$= -\frac{85}{3}$ \\
$f(-3) = (-3)^{4} - \frac{2}{3}(-3)^{3} - 18(-3)^{2} + 18(-3) + \frac{50}{3}$ \\
$= 81 - \frac{2}{3}(-27) - 18(9) - 54 + \frac{50}{3}$ \\
$= 81 + 18 - 162 - 54 + \frac{50}{3}$ \\
$= -117 + \frac{50}{3}$ \\
$= -\frac{351}{3} + \frac{50}{3}$ \\
$= -\frac{301}{3}$ \\
The minimum values are $-\frac{85}{3}$ (about $-28.3$) and $-\frac{301}{3}$ (about $-100.3$) \\
The higher of the two minima is $-\frac{85}{3}$ \\
The line $y = k$ crosses $C$ four times when it is above both minima and below the local maximum: \\
$-\frac{85}{3} < k < \frac{1015}{48}$ \\
(If $k$ equals a turning value the line touches the curve and there are fewer than 4 distinct solutions) \\
In set notation: \\
$\{ k : -\frac{85}{3} < k < \frac{1015}{48} \}$

@q 9
@topic Book sales model, exponential
@marks 8
@question
(a) The total sold in the first 6 weeks is $N$ when $t = 6$ \\
$N = 3200 - 3200e^{-0.085(6)}$ \\
Evaluate the index: $0.085 \times 6 = 0.51$ \\
$N = 3200 - 3200e^{-0.51}$ \\
$e^{-0.51} = 0.600496...$ \\
$3200 \times 0.600496 = 1921.59$ \\
$N = 3200 - 1921.59$ \\
$N = 1278.41$ \\
The number of books is a whole number, so about 1278 books were sold in the first 6 weeks \\
(b) Set $N = 2000$ and $t = T$: \\
$2000 = 3200 - 3200e^{-0.085T}$ \\
Subtract 3200 from both sides: \\
$2000 - 3200 = -3200e^{-0.085T}$ \\
$-1200 = -3200e^{-0.085T}$ \\
Divide both sides by $-3200$: \\
$e^{-0.085T} = \frac{1200}{3200}$ \\
Divide the top and bottom by 400: \\
$e^{-0.085T} = \frac{3}{8}$ \\
Take natural logs of both sides: \\
$-0.085T = \ln \left( \frac{3}{8} \right)$ \\
$\ln \left( \frac{3}{8} \right) = -0.980829...$ \\
Divide both sides by $-0.085$: \\
$T = \frac{-0.980829...}{-0.085}$ \\
$T = 11.5391...$ \\
$T = 11.54$ to 2 dp \\
(Check: $3200 - 3200e^{-0.085 \times 11.54} = 3200 - 3200(0.37497) = 2000.1$, close to 2000) \\
(c) The rate of increase is $\frac{dN}{dt}$ \\
Differentiate $N = 3200 - 3200e^{-0.085t}$ \\
The constant 3200 differentiates to 0 \\
The derivative of $e^{ax}$ is $ae^{ax}$, so $\frac{d}{dt}(e^{-0.085t}) = -0.085e^{-0.085t}$ \\
$\frac{dN}{dt} = -3200 \times (-0.085)e^{-0.085t}$ \\
$-3200 \times (-0.085) = 272$ \\
$\frac{dN}{dt} = 272e^{-0.085t}$ \\
At $t = 6$: \\
$\frac{dN}{dt} = 272e^{-0.51}$ \\
$= 272 \times 0.600496...$ \\
$= 163.33...$ \\
The rate of increase is 163 books per week to 3 sf \\
(d) In the model $N \to 3200$ as $t \to \infty$, since $e^{-0.085t} \to 0$ \\
So 3200 is the upper limit of the current model \\
To make the upper limit 4000, replace 3200 by 4000 in both places: \\
$N = 4000 - 4000e^{-0.085t}$ \\
(This still gives $N = 0$ when $t = 0$, and $N \to 4000$ as $t \to \infty$)

@q 10
@topic Grain container differential equation
@marks 9
@question
(a) Rate of change of volume = rate in minus rate out \\
$\frac{dV}{dt} = 0.6 - 0.25V$ \\
Multiply every term by 20: \\
$20\frac{dV}{dt} = 20 \times 0.6 - 20 \times 0.25V$ \\
$20 \times 0.6 = 12$ and $20 \times 0.25 = 5$ \\
$20\frac{dV}{dt} = 12 - 5V$ as required \\
(b) Separate the variables: $V$ terms with $dV$ on one side and $t$ terms with $dt$ on the other \\
$20\frac{dV}{dt} = 12 - 5V$ \\
Divide both sides by $(12 - 5V)$ and multiply both sides by $dt$: \\
$\frac{20}{12 - 5V} dV = dt$ \\
Integrate both sides: \\
$\int \frac{20}{12 - 5V} dV = \int 1 \, dt$ \\
Use $\int \frac{1}{aV + b} dV = \frac{1}{a} \ln |aV + b|$. Here $a = -5$: \\
$20 \times \frac{1}{-5} \ln |12 - 5V| = t + c$ \\
$-4 \ln |12 - 5V| = t + c$ \\
Use the starting condition: $V = 0.8$ when $t = 0$ \\
$12 - 5(0.8) = 12 - 4 = 8$ \\
$-4 \ln 8 = 0 + c$ \\
$c = -4 \ln 8$ \\
Substitute $c$ back: \\
$-4 \ln |12 - 5V| = t - 4 \ln 8$ \\
Divide every term by $-4$: \\
$\ln |12 - 5V| = -\frac{t}{4} + \ln 8$ \\
$12 - 5V = 8$ at the start, which is positive, and it stays positive, so drop the modulus: \\
$\ln (12 - 5V) = \ln 8 - \frac{t}{4}$ \\
Take exponentials of both sides, using $e^{\ln a} = a$: \\
$12 - 5V = e^{\ln 8 - \frac{t}{4}}$ \\
Split the index: $e^{a - b} = e^{a} \times e^{-b}$ \\
$12 - 5V = e^{\ln 8} \times e^{-\frac{t}{4}}$ \\
$12 - 5V = 8e^{-\frac{t}{4}}$ \\
Subtract 12 from both sides: \\
$-5V = 8e^{-\frac{t}{4}} - 12$ \\
Divide both sides by $-5$: \\
$V = -\frac{8}{5}e^{-\frac{t}{4}} + \frac{12}{5}$ \\
$V = \frac{12}{5} - \frac{8}{5}e^{-\frac{t}{4}}$ \\
Write as decimals: $\frac{12}{5} = 2.4$ and $\frac{8}{5} = 1.6$ and $\frac{1}{4} = 0.25$ \\
$V = 2.4 - 1.6e^{-0.25t}$ \\
This is $V = P - Qe^{-kt}$ with $P = 2.4$, $Q = 1.6$ and $k = 0.25$ \\
(Check: when $t = 0$, $V = 2.4 - 1.6 = 0.8$) \\
(c) As $t$ increases, $e^{-0.25t}$ gets closer and closer to 0 \\
So $V$ gets closer and closer to 2.4 \\
$1.6e^{-0.25t}$ is always positive, so $V = 2.4 - 1.6e^{-0.25t}$ is always less than 2.4 \\
The volume never gets above 2.4, so it can never reach the capacity of 3 \\
$2.4 < 3$, so the container will never become full

@q 11
@topic Linear model, profit quadratic
@marks 11
@question
(a) A linear model has the form $y = mx + c$ \\
Two points on the line are $(25, 1600)$ and $(45, 600)$ \\
Gradient: $m = \frac{y_{2} - y_{1}}{x_{2} - x_{1}}$ \\
$m = \frac{600 - 1600}{45 - 25}$ \\
$m = \frac{-1000}{20}$ \\
$m = -50$ \\
Use $y - y_{1} = m(x - x_{1})$ with the point $(25, 1600)$: \\
$y - 1600 = -50(x - 25)$ \\
Expand the bracket: \\
$y - 1600 = -50x + 1250$ \\
Add 1600 to both sides: \\
$y = -50x + 1250 + 1600$ \\
$y = -50x + 2850$ \\
(Check with $(45, 600)$: $-50(45) + 2850 = -2250 + 2850 = 600$) \\
(b) Profit = money from sales minus cost of making minus extra costs \\
Money from sales = price $\times$ number sold $= xy$ \\
Cost of making = $8y$ \\
Extra costs = 10000 \\
Profit in pounds $= xy - 8y - 10000$ \\
Factorise the first two terms: \\
$= y(x - 8) - 10000$ \\
Substitute $y = 2850 - 50x$: \\
$= (2850 - 50x)(x - 8) - 10000$ \\
Multiply each term of the first bracket by $x$ and then by $-8$: \\
$2850x - 50x^{2} - 22800 + 400x$ \\
(Here $2850 \times 8 = 22800$ and $-50x \times (-8) = 400x$) \\
Collect like terms: $2850x + 400x = 3250x$ \\
$= -50x^{2} + 3250x - 22800 - 10000$ \\
$= -50x^{2} + 3250x - 32800$ \\
This is the profit in pounds. For thousands of pounds, divide by 1000: \\
$P = \frac{-50x^{2} + 3250x - 32800}{1000}$ \\
$P = -0.05x^{2} + 3.25x - 32.8$ as required \\
(c) The company makes a profit when $P > 0$ \\
$-0.05x^{2} + 3.25x - 32.8 > 0$ \\
Multiply every term by $-20$. This turns $-0.05$ into 1, $3.25$ into $-65$ and $-32.8$ into 656, and it reverses the inequality sign: \\
$x^{2} - 65x + 656 < 0$ \\
Find where $x^{2} - 65x + 656 = 0$ using the quadratic formula: \\
$x = \frac{65 \pm \sqrt{65^{2} - 4(1)(656)}}{2(1)}$ \\
$65^{2} = 4225$ and $4(656) = 2624$ \\
$x = \frac{65 \pm \sqrt{4225 - 2624}}{2}$ \\
$x = \frac{65 \pm \sqrt{1601}}{2}$ \\
$\sqrt{1601} = 40.0125...$ \\
$x = \frac{65 - 40.0125...}{2}$ or $x = \frac{65 + 40.0125...}{2}$ \\
$x = 12.4937...$ or $x = 52.5062...$ \\
The quadratic $x^{2} - 65x + 656$ is a U shape, so it is below zero between the roots: \\
$\frac{65 - \sqrt{1601}}{2} < x < \frac{65 + \sqrt{1601}}{2}$ \\
$12.49 < x < 52.51$ to 2 dp \\
The selling price must be between GBP 12.49 and GBP 52.51 \\
(d) $P$ is a downward-facing parabola, so it is symmetrical and its maximum is halfway between the two roots \\
The two roots add up to 65, as $\frac{65 - \sqrt{1601}}{2} + \frac{65 + \sqrt{1601}}{2} = \frac{130}{2} = 65$ \\
Halfway is half of this sum: \\
$x = \frac{65}{2}$ \\
$x = 32.5$ \\
The profit is greatest when the selling price is GBP 32.50 \\
(Check with calculus: $\frac{dP}{dx} = -0.1x + 3.25 = 0$ gives $x = 32.5$) \\
(e) Put $x = 30$ into the model for the profit in thousands of pounds: \\
$P = -0.05(30)^{2} + 3.25(30) - 32.8$ \\
$30^{2} = 900$ and $0.05 \times 900 = 45$ \\
$3.25 \times 30 = 97.5$ \\
$P = -45 + 97.5 - 32.8$ \\
$P = 19.7$ \\
The model predicts a profit of 19.7 thousand pounds, which is GBP 19 700 \\
The actual profit was GBP 19 850 \\
Difference: $19850 - 19700 = 150$ \\
As a percentage of the actual profit: $\frac{150}{19850} \times 100 = 0.76$ percent \\
The model slightly underestimates the profit, but it is only GBP 150 (less than 1 percent) out, so the model is a good fit here and is suitable

@q 12
@topic Modulus function, composite, no solutions
@marks 8
@question
(a) $|a| = 3$ means $a = 3$ or $a = -3$ \\
For $a = 3$: \\
$f(3) = 3|3 - 2| + 7$ \\
$|3 - 2| = |1| = 1$ \\
$f(3) = 3(1) + 7$ \\
$f(3) = 10$ \\
For $a = -3$: \\
$f(-3) = 3|-3 - 2| + 7$ \\
$|-3 - 2| = |-5| = 5$ \\
$f(-3) = 3(5) + 7$ \\
$f(-3) = 22$ \\
The possible values of $f(a)$ are 10 and 22 \\
(b) $gf(x)$ means apply $f$ first and then $g$ \\
$gf(x) = g(f(x))$ \\
Replace $x$ in $g(x) = \frac{x - 9}{2}$ by $f(x) = 3|x - 2| + 7$: \\
$gf(x) = \frac{3|x - 2| + 7 - 9}{2}$ \\
$gf(x) = \frac{3|x - 2| - 2}{2}$ \\
The smallest value of $|x - 2|$ is 0 (when $x = 2$), so $|x - 2| \geq 0$ \\
Multiply by 3: $3|x - 2| \geq 0$ \\
Subtract 2: $3|x - 2| - 2 \geq -2$ \\
Divide by 2: \\
$\frac{3|x - 2| - 2}{2} \geq -1$ \\
The range of $gf(x)$ is $gf(x) \geq -1$ \\
(Check: $gf(2) = \frac{3(0) - 2}{2} = -1$) \\
(c) The graph of $y = f(x)$ is a V shape with its vertex at $(2, 7)$ \\
For $x < 2$, $|x - 2| = 2 - x$, so $f(x) = 3(2 - x) + 7$ \\
$f(x) = 6 - 3x + 7$ \\
$f(x) = 13 - 3x$, a line with gradient $-3$ \\
For $x \geq 2$, $|x - 2| = x - 2$, so $f(x) = 3(x - 2) + 7$ \\
$f(x) = 3x - 6 + 7$ \\
$f(x) = 3x + 1$, a line with gradient 3 \\
The line $y = 10 + kx$ passes through $(0, 10)$ with gradient $k$ \\
At $x = 0$ the V is at $f(0) = 13$, which is above 10, so $(0, 10)$ is below the V \\
For no solutions the line must stay below the V everywhere \\
Condition 1: the line must pass below the vertex $(2, 7)$ \\
At $x = 2$ the line has $y = 10 + 2k$ \\
We need $10 + 2k < 7$ \\
Subtract 10 from both sides: \\
$2k < -3$ \\
Divide both sides by 2: \\
$k < -\frac{3}{2}$ \\
(If $k = -\frac{3}{2}$ the line goes through the vertex and meets the graph there) \\
Condition 2: the line must not meet the left arm $y = 13 - 3x$ \\
Set $10 + kx = 13 - 3x$: \\
Add $3x$ to both sides and subtract 10 from both sides: \\
$kx + 3x = 13 - 10$ \\
$(k + 3)x = 3$ \\
If $k = -3$ this says $0 = 3$, which is impossible, so the lines are parallel and never meet \\
If $k \neq -3$ then $x = \frac{3}{k + 3}$, and it only counts if $x < 2$ \\
If $k < -3$, then $k + 3$ is negative, so $x$ is negative, which is less than 2, so they do meet \\
So $k < -3$ is not allowed \\
If $-3 < k < -\frac{3}{2}$, then $0 < k + 3 < \frac{3}{2}$ \\
Taking reciprocals reverses the inequalities: $\frac{1}{k + 3} > \frac{2}{3}$ \\
Multiply both sides by 3: $x = \frac{3}{k + 3} > 2$ \\
$x > 2$ is not on the left arm, so there is no meeting point there \\
Condition 3: the line must not meet the right arm $y = 3x + 1$ for $x \geq 2$ \\
Set $10 + kx = 3x + 1$: \\
Subtract $3x$ and 10 from both sides: \\
$kx - 3x = 1 - 10$ \\
$(k - 3)x = -9$ \\
$x = \frac{9}{3 - k}$ \\
For $k < -\frac{3}{2}$: $3 - k > \frac{9}{2}$ \\
So $x = \frac{9}{3 - k} < \frac{9}{\frac{9}{2}} = 2$ \\
The meeting point has $x < 2$, but the right arm needs $x \geq 2$, so there is no meeting point there \\
Combining the conditions: $k < -\frac{3}{2}$ and $k \geq -3$ \\
$-3 \leq k < -\frac{3}{2}$ \\
(Check with $k = -2$: the line $y = 10 - 2x$ is below the vertex, since $10 - 4 = 6 < 7$, and it does not meet either arm for a valid $x$)

@q 13
@topic sin(nx) = k solutions, sin^2
@marks 3
@question
(i) The graph of $y = \sin (nx)$ has period $\frac{2\pi}{n}$ \\
In $0 \leq x < 2\pi$ there are $2\pi \div \frac{2\pi}{n} = n$ complete periods \\
When $0 < |k| < 1$ the horizontal line $y = k$ cuts each complete period exactly twice \\
Number of solutions $= 2 \times n = 2n$ \\
We are told there are 10 solutions: \\
$2n = 10$ \\
Divide both sides by 2: \\
$n = 5$ \\
(ii) The equation is now $\sin^{2} (5x) = k^{2}$ \\
$\sin^{2}$ repeats every $\pi$, so $\sin^{2} (5x)$ repeats every $\frac{\pi}{5}$ \\
Number of periods in $0 \leq x < 7\pi$: \\
$7\pi \div \frac{\pi}{5}$ \\
$= 7\pi \times \frac{5}{\pi}$ \\
$= 35$ \\
In each period $\sin^{2} (5x)$ rises from 0 to 1 and then falls back to 0 \\
Since $0 < k^{2} < 1$, the line $y = k^{2}$ cuts this once going up and once coming down \\
That is 2 solutions in each period \\
Number of solutions $= 35 \times 2 = 70$ \\
(Check: for $0 < k < 1$, $\sin (5x) = k$ has 36 solutions and $\sin (5x) = -k$ has 34, and $36 + 34 = 70$)

@q 14
@topic Vectors in a trapezium, ratio
@marks 8
@question
(a) $\text{AD}$ is the journey from $A$ to $B$ and then from $B$ to $D$: \\
$\text{AD} = \text{AB} + \text{BD}$ \\
$\text{AB}$ is the reverse of $\text{BA}$, so $\text{AB} = -\text{BA}$ \\
$\text{AB} = -(\mathbf{a} + 5\mathbf{b})$ \\
$\text{AB} = -\mathbf{a} - 5\mathbf{b}$ \\
$\text{AD} = -\mathbf{a} - 5\mathbf{b} + 5\mathbf{a} + k\mathbf{b}$ \\
Collect the $\mathbf{a}$ terms: $-\mathbf{a} + 5\mathbf{a} = 4\mathbf{a}$ \\
Collect the $\mathbf{b}$ terms: $-5\mathbf{b} + k\mathbf{b} = (k - 5)\mathbf{b}$ \\
$\text{AD} = 4\mathbf{a} + (k - 5)\mathbf{b}$ \\
$AD$ is parallel to $BC$, so $\text{AD}$ is a multiple of $\text{BC}$: \\
$\text{AD} = \lambda \text{BC}$ where $\lambda$ is a constant \\
$4\mathbf{a} + (k - 5)\mathbf{b} = \lambda (20\mathbf{a} + 5\mathbf{b})$ \\
Expand the bracket: \\
$4\mathbf{a} + (k - 5)\mathbf{b} = 20\lambda \mathbf{a} + 5\lambda \mathbf{b}$ \\
$\mathbf{a}$ and $\mathbf{b}$ are not parallel, so compare the coefficients of $\mathbf{a}$ and of $\mathbf{b}$ \\
Coefficients of $\mathbf{a}$: $4 = 20\lambda$ \\
Divide both sides by 20: \\
$\lambda = \frac{4}{20}$ \\
$\lambda = \frac{1}{5}$ \\
Coefficients of $\mathbf{b}$: $k - 5 = 5\lambda$ \\
Substitute $\lambda = \frac{1}{5}$: \\
$k - 5 = 5 \times \frac{1}{5}$ \\
$k - 5 = 1$ \\
Add 5 to both sides: \\
$k = 6$ as required \\
(b) $N$ is on $BC$ with $BN : NC = 3 : 2$, so $BN$ is $\frac{3}{5}$ of $BC$ \\
$\text{BN} = \frac{3}{5}\text{BC}$ \\
$\text{BN} = \frac{3}{5}(20\mathbf{a} + 5\mathbf{b})$ \\
$\text{BN} = 12\mathbf{a} + 3\mathbf{b}$ \\
Find $\text{AN}$ by going from $A$ to $B$ and then from $B$ to $N$: \\
$\text{AN} = \text{AB} + \text{BN}$ \\
$\text{AN} = (-\mathbf{a} - 5\mathbf{b}) + (12\mathbf{a} + 3\mathbf{b})$ \\
$\text{AN} = 11\mathbf{a} - 2\mathbf{b}$ \\
$X$ is on $BD$, so $\text{BX}$ is a multiple of $\text{BD}$. Let $\text{BX} = \lambda \text{BD}$ \\
Now $k = 6$, so $\text{BD} = 5\mathbf{a} + 6\mathbf{b}$ \\
$\text{BX} = \lambda (5\mathbf{a} + 6\mathbf{b})$ \\
$\text{BX} = 5\lambda \mathbf{a} + 6\lambda \mathbf{b}$ \\
$X$ is also on $AN$, so $\text{AX} = \mu \text{AN}$ for some constant $\mu$ \\
$\text{AX} = \mu (11\mathbf{a} - 2\mathbf{b})$ \\
$\text{AX} = 11\mu \mathbf{a} - 2\mu \mathbf{b}$ \\
Find $\text{BX}$ a second way, going from $B$ to $A$ and then from $A$ to $X$: \\
$\text{BX} = \text{BA} + \text{AX}$ \\
$\text{BX} = (\mathbf{a} + 5\mathbf{b}) + 11\mu \mathbf{a} - 2\mu \mathbf{b}$ \\
$\text{BX} = (1 + 11\mu)\mathbf{a} + (5 - 2\mu)\mathbf{b}$ \\
The two expressions for $\text{BX}$ are equal. Compare the coefficients of $\mathbf{a}$ and $\mathbf{b}$: \\
Equation 1, from $\mathbf{a}$: $5\lambda = 1 + 11\mu$ \\
Equation 2, from $\mathbf{b}$: $6\lambda = 5 - 2\mu$ \\
Divide equation 2 by 6 to make $\lambda$ the subject: \\
$\lambda = \frac{5 - 2\mu}{6}$ \\
Substitute into equation 1: \\
$5 \times \frac{5 - 2\mu}{6} = 1 + 11\mu$ \\
Multiply both sides by 6: \\
$5(5 - 2\mu) = 6(1 + 11\mu)$ \\
Expand both brackets: \\
$25 - 10\mu = 6 + 66\mu$ \\
Add $10\mu$ to both sides and subtract 6 from both sides: \\
$25 - 6 = 66\mu + 10\mu$ \\
$19 = 76\mu$ \\
Divide both sides by 76: \\
$\mu = \frac{19}{76}$ \\
$\mu = \frac{1}{4}$ \\
Substitute $\mu = \frac{1}{4}$ into $\lambda = \frac{5 - 2\mu}{6}$: \\
$2\mu = 2 \times \frac{1}{4} = \frac{1}{2}$ \\
$5 - \frac{1}{2} = \frac{9}{2}$ \\
$\lambda = \frac{9}{2} \div 6$ \\
$\lambda = \frac{9}{12}$ \\
$\lambda = \frac{3}{4}$ \\
So $\text{BX} = \frac{3}{4}\text{BD}$ \\
$X$ is $\frac{3}{4}$ of the way from $B$ to $D$, so $BX$ is 3 parts and $XD$ is 1 part \\
$BX : XD = 3 : 1$ \\
(Check: $\frac{3}{4}(5\mathbf{a} + 6\mathbf{b}) = \frac{15}{4}\mathbf{a} + \frac{9}{2}\mathbf{b}$, and $(1 + \frac{11}{4})\mathbf{a} + (5 - \frac{1}{2})\mathbf{b} = \frac{15}{4}\mathbf{a} + \frac{9}{2}\mathbf{b}$)

@q 15
@topic Turning point, x = tan(theta), area
@marks 13
@question
(a) The maximum turning points are where $f'(x) = 0$ \\
Use the quotient rule $f'(x) = \frac{vu' - uv'}{v^{2}}$ with $u = x^{2}$ and $v = (1 + x^{2})^{2}$ \\
$u' = 2x$ \\
Differentiate $v$ with the chain rule: \\
$v' = 2(1 + x^{2}) \times 2x = 4x(1 + x^{2})$ \\
Numerator: $(1 + x^{2})^{2}(2x) - x^{2}(4x)(1 + x^{2})$ \\
Denominator: $\left( (1 + x^{2})^{2} \right)^{2} = (1 + x^{2})^{4}$ \\
Take out the common factor $2x(1 + x^{2})$ from the numerator: \\
$(1 + x^{2})^{2}(2x) = 2x(1 + x^{2})(1 + x^{2})$ \\
$x^{2}(4x)(1 + x^{2}) = 2x(1 + x^{2})(2x^{2})$ \\
Numerator $= 2x(1 + x^{2})(1 + x^{2} - 2x^{2})$ \\
$= 2x(1 + x^{2})(1 - x^{2})$ \\
$f'(x) = \frac{2x(1 + x^{2})(1 - x^{2})}{(1 + x^{2})^{4}}$ \\
Cancel one factor of $(1 + x^{2})$, which is never zero: \\
$f'(x) = \frac{2x(1 - x^{2})}{(1 + x^{2})^{3}}$ \\
Set $f'(x) = 0$. A fraction is zero when its top is zero: \\
$2x(1 - x^{2}) = 0$ \\
$x = 0$ or $1 - x^{2} = 0$ \\
$1 - x^{2} = 0$ gives $x^{2} = 1$, so $x = 1$ or $x = -1$ \\
$x = 0$ is the minimum at the origin, so the maximum points are at $x = \pm 1$ \\
$P$ is the maximum on the left of the $y$-axis, so $x = -1$ \\
Find the $y$ coordinate: \\
$f(-1) = \frac{(-1)^{2}}{(1 + (-1)^{2})^{2}}$ \\
$= \frac{1}{(1 + 1)^{2}}$ \\
$= \frac{1}{2^{2}}$ \\
$= \frac{1}{4}$ \\
$P$ is the point $\left( -1, \frac{1}{4} \right)$ \\
(By symmetry $Q$ is $\left( 1, \frac{1}{4} \right)$) \\
(b) Let $x = \tan \theta$ \\
Differentiate: $\frac{dx}{d\theta} = \sec^{2} \theta$ \\
So $dx = \sec^{2} \theta \, d\theta$ \\
Use the identity $1 + \tan^{2} \theta = \sec^{2} \theta$ to simplify $1 + x^{2}$: \\
$1 + x^{2} = 1 + \tan^{2} \theta = \sec^{2} \theta$ \\
Replace $x$ and $dx$ in $f(x) \, dx$: \\
$f(x) \, dx = \frac{\tan^{2} \theta}{(\sec^{2} \theta)^{2}} \times \sec^{2} \theta \, d\theta$ \\
$(\sec^{2} \theta)^{2} = \sec^{4} \theta$ \\
$= \frac{\tan^{2} \theta \sec^{2} \theta}{\sec^{4} \theta} \, d\theta$ \\
Cancel $\sec^{2} \theta$ from the top and bottom: \\
$= \frac{\tan^{2} \theta}{\sec^{2} \theta} \, d\theta$ \\
Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$ and $\sec \theta = \frac{1}{\cos \theta}$: \\
$\tan^{2} \theta = \frac{\sin^{2} \theta}{\cos^{2} \theta}$ and $\sec^{2} \theta = \frac{1}{\cos^{2} \theta}$ \\
$\frac{\tan^{2} \theta}{\sec^{2} \theta} = \frac{\sin^{2} \theta}{\cos^{2} \theta} \times \cos^{2} \theta$ \\
$= \sin^{2} \theta$ \\
Use the double angle formula $\cos 2\theta = 1 - 2\sin^{2} \theta$ \\
Add $2\sin^{2} \theta$ to both sides and subtract $\cos 2\theta$ from both sides: \\
$2\sin^{2} \theta = 1 - \cos 2\theta$ \\
Divide both sides by 2: \\
$\sin^{2} \theta = \frac{1}{2}(1 - \cos 2\theta)$ \\
So $f(x) \, dx = \frac{1}{2}(1 - \cos 2\theta) \, d\theta$ \\
Change the limits. When $x = -\sqrt{3}$: \\
$\tan \theta = -\sqrt{3}$ \\
$\theta = -\frac{\pi}{3}$ \\
When $x = \sqrt{3}$: \\
$\tan \theta = \sqrt{3}$ \\
$\theta = \frac{\pi}{3}$ \\
$\int_{-\sqrt{3}}^{\sqrt{3}} f(x) dx = \int_{-\frac{\pi}{3}}^{\frac{\pi}{3}} \frac{1}{2}(1 - \cos 2\theta) \, d\theta$ \\
So $\alpha = -\frac{\pi}{3}$ and $\beta = \frac{\pi}{3}$ \\
(c) The curve is above the $x$-axis, so the area is the integral of $f(x)$ from $-\sqrt{3}$ to $\sqrt{3}$ \\
Use part (b): \\
$\text{Area} = \int_{-\frac{\pi}{3}}^{\frac{\pi}{3}} \frac{1}{2}(1 - \cos 2\theta) \, d\theta$ \\
Take out the factor $\frac{1}{2}$ and integrate, using $\int \cos 2\theta \, d\theta = \frac{1}{2}\sin 2\theta$: \\
$= \frac{1}{2} \left[ \theta - \frac{1}{2}\sin 2\theta \right]_{-\frac{\pi}{3}}^{\frac{\pi}{3}}$ \\
Upper limit $\theta = \frac{\pi}{3}$: \\
$\frac{\pi}{3} - \frac{1}{2}\sin \frac{2\pi}{3}$ \\
$\sin \frac{2\pi}{3} = \frac{\sqrt{3}}{2}$ \\
$= \frac{\pi}{3} - \frac{1}{2} \times \frac{\sqrt{3}}{2}$ \\
$= \frac{\pi}{3} - \frac{\sqrt{3}}{4}$ \\
Lower limit $\theta = -\frac{\pi}{3}$: \\
$-\frac{\pi}{3} - \frac{1}{2}\sin \left( -\frac{2\pi}{3} \right)$ \\
$\sin \left( -\frac{2\pi}{3} \right) = -\frac{\sqrt{3}}{2}$ \\
$= -\frac{\pi}{3} - \frac{1}{2} \times \left( -\frac{\sqrt{3}}{2} \right)$ \\
$= -\frac{\pi}{3} + \frac{\sqrt{3}}{4}$ \\
Subtract the lower limit from the upper limit: \\
$\left( \frac{\pi}{3} - \frac{\sqrt{3}}{4} \right) - \left( -\frac{\pi}{3} + \frac{\sqrt{3}}{4} \right)$ \\
Remove the second bracket, changing every sign: \\
$= \frac{\pi}{3} - \frac{\sqrt{3}}{4} + \frac{\pi}{3} - \frac{\sqrt{3}}{4}$ \\
$= \frac{2\pi}{3} - \frac{2\sqrt{3}}{4}$ \\
$= \frac{2\pi}{3} - \frac{\sqrt{3}}{2}$ \\
Multiply by the $\frac{1}{2}$ at the front: \\
$\text{Area} = \frac{1}{2} \left( \frac{2\pi}{3} - \frac{\sqrt{3}}{2} \right)$ \\
$= \frac{\pi}{3} - \frac{\sqrt{3}}{4}$ \\
(Check: $\frac{\pi}{3} - \frac{\sqrt{3}}{4} = 1.0472 - 0.4330 = 0.6142$)
