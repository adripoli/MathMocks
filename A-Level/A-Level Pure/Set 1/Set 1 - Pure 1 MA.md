@paper P1 Mock Set 1

@q 1
@topic Trapezium rule, integration estimate
@marks 5
@question
(a) There are 5 y-values, so there are 4 strips, each of width $h = 0.5$ \\
Trapezium rule: area $\approx \frac{1}{2} \times h \times \{ y_0 + 2(y_1 + y_2 + y_3) + y_4 \}$ \\
Substitute the table values: \\
$= \frac{1}{2} \times 0.5 \times \{ 1 + 2(e^{0.05} + e^{0.2} + e^{0.45}) + e^{0.8} \}$ \\
Evaluate each exponential: \\
$e^{0.05} = 1.051271$, $e^{0.2} = 1.221403$, $e^{0.45} = 1.568312$, $e^{0.8} = 2.225541$ \\
Add the three middle y-values: \\
$1.051271 + 1.221403 + 1.568312 = 3.840986$ \\
Double this: $2 \times 3.840986 = 7.681972$ \\
Add the first and last y-values: \\
$1 + 7.681972 + 2.225541 = 10.907513$ \\
The outside factor is $\frac{1}{2} \times 0.5 = \frac{1}{4}$ \\
Area $\approx \frac{1}{4} \times 10.907513 = 2.726878$ \\
Area of R $= 2.73$ (2 dp) \\
(b)(i) Split the integral into two parts: \\
$\int_{0}^{2} \left( 4 + e^{\frac{1}{5}x^{2}} \right) dx = \int_{0}^{2} 4 \, dx + \int_{0}^{2} e^{\frac{1}{5}x^{2}} \, dx$ \\
First part: $\int_{0}^{2} 4 \, dx = [4x]_{0}^{2} = 4(2) - 4(0) = 8$ \\
Second part: this is the area of R (bounded by the curve, both axes and $x = 2$), which is $2.73$ from part (a) \\
So the integral is $8 + 2.73 = 10.73$ (2 dp) \\
(b)(ii) Let $u = x - 1$, so $du = dx$ \\
When $x = 1$, $u = 0$; when $x = 3$, $u = 2$ \\
$\int_{1}^{3} e^{\frac{1}{5}(x-1)^{2}} \, dx = \int_{0}^{2} e^{\frac{1}{5}u^{2}} \, du$ \\
This is the same integral as the area of R, so its value is $2.73$ (2 dp) \\
(Replacing $x$ by $x - 1$ slides the curve 1 unit to the right, so the area under it does not change.)

@q 2
@topic Radians, sector arc and cosine rule
@marks 5
@question
A, O and C lie on a straight line, so angle AOB + angle BOC = $\pi$ \\
Angle BOC $= \pi - 1.2 = 1.9416$ radians (4 dp) \\
$OB = OA = 7.5$ cm, as both are radii of the sector \\
Cosine rule in triangle BOC: \\
$BC^{2} = OB^{2} + OC^{2} - 2(OB)(OC)\cos(\pi - 1.2)$ \\
$= 7.5^{2} + 8.5^{2} - 2(7.5)(8.5)\cos(\pi - 1.2)$ \\
Evaluate the squares and the product: \\
$7.5^{2} = 56.25$, $8.5^{2} = 72.25$, $2(7.5)(8.5) = 127.5$ \\
$\cos(\pi - 1.2) = -\cos 1.2 = -0.3623578$ (calculator in radian mode) \\
$BC^{2} = 56.25 + 72.25 - 127.5 \times (-0.3623578)$ \\
$= 128.5 + 46.2006$ \\
$= 174.7006$ \\
$BC = \sqrt{174.7006} = 13.2174$ cm (4 dp) \\
Arc AB: $s = r\theta = 7.5 \times 1.2 = 9$ cm \\
The perimeter of AOCBA is made of AO, OC, CB and the arc BA: \\
Perimeter $= 7.5 + 8.5 + 13.2174 + 9$ \\
$= 16 + 13.2174 + 9$ \\
$= 38.2174$ \\
Perimeter $= 38.2$ cm (1 dp)

@q 3
@topic Discriminant, quadratic with no real roots
@marks 4
@question
Start with $3x^{2} + k = 5x + 2$ \\
Bring every term to one side (subtract $5x$ and $2$ from both sides): \\
$3x^{2} - 5x + k - 2 = 0$ \\
Compare with $ax^{2} + bx + c = 0$: $a = 3$, $b = -5$, $c = k - 2$ \\
No real roots means the discriminant is negative: $b^{2} - 4ac < 0$ \\
$(-5)^{2} - 4(3)(k - 2) < 0$ \\
$25 - 12(k - 2) < 0$ \\
Expand the bracket: $25 - 12k + 24 < 0$ \\
Collect the numbers: $49 - 12k < 0$ \\
Add $12k$ to both sides: $49 < 12k$ \\
Divide both sides by 12: $\frac{49}{12} < k$ \\
So $k > \frac{49}{12}$

@q 4
@topic Functions, range, inverse and composite
@marks 10
@question
(a) At $x = 0$: $f(0) = \frac{12(0)}{3(0) + 4} = \frac{0}{4} = 0$ \\
Write $12x$ as $4(3x + 4) - 16$: \\
$f(x) = \frac{4(3x+4) - 16}{3x+4}$ \\
Split into two fractions: \\
$f(x) = \frac{4(3x+4)}{3x+4} - \frac{16}{3x+4}$ \\
Cancel the common factor in the first fraction: \\
$f(x) = 4 - \frac{16}{3x+4}$ \\
For $x \ge 0$: $3x + 4 \ge 4$ \\
So $\frac{16}{3x+4}$ is positive but never more than $\frac{16}{4} = 4$: \\
$0 < \frac{16}{3x+4} \le 4$ \\
Multiply by $-1$ (this reverses the inequalities): \\
$-4 \le -\frac{16}{3x+4} < 0$ \\
Add 4 to every part: \\
$0 \le 4 - \frac{16}{3x+4} < 4$ \\
$f(x)$ gets closer and closer to 4 but never reaches it \\
Range of f: $0 \le f(x) < 4$ \\
(b) Let $y = f(x)$: $y = \frac{12x}{3x+4}$ \\
Multiply both sides by $(3x + 4)$: \\
$y(3x + 4) = 12x$ \\
Expand the bracket: \\
$3xy + 4y = 12x$ \\
Get the $x$ terms together (subtract $3xy$ from both sides): \\
$4y = 12x - 3xy$ \\
Factorise the right-hand side: \\
$4y = x(12 - 3y)$ \\
Divide both sides by $(12 - 3y)$: \\
$x = \frac{4y}{12 - 3y}$ \\
Replace $y$ by $x$: \\
$f^{-1}(x) = \frac{4x}{12 - 3x}$ \\
The domain of $f^{-1}$ is the range of $f$: \\
$f^{-1}(x) = \frac{4x}{12 - 3x}$, $0 \le x < 4$ \\
(c) Put $f(x)$ into itself: $ff(x) = f\left(\frac{12x}{3x+4}\right)$ \\
Replace every $x$ in $\frac{12x}{3x+4}$ by $\frac{12x}{3x+4}$: \\
$ff(x) = \frac{12\left(\frac{12x}{3x+4}\right)}{3\left(\frac{12x}{3x+4}\right) + 4}$ \\
Multiply the top and the bottom by $(3x + 4)$ to clear the small fractions \\
Top: $12 \times \frac{12x}{3x+4} \times (3x+4) = 12 \times 12x = 144x$ \\
Bottom: $\left( 3 \times \frac{12x}{3x+4} + 4 \right)(3x+4) = 3 \times 12x + 4(3x+4)$ \\
$= 36x + 12x + 16$ \\
$= 48x + 16$ \\
So $ff(x) = \frac{144x}{48x + 16}$ \\
Factorise: $144x = 16 \times 9x$ and $48x + 16 = 16(3x + 1)$ \\
$ff(x) = \frac{16 \times 9x}{16(3x + 1)}$ \\
Cancel the common factor of 16: \\
$ff(x) = \frac{9x}{3x + 1}$ as required \\
(d) Set $ff(x) = \frac{7}{2}$: $\frac{9x}{3x+1} = \frac{7}{2}$ \\
Cross-multiply: $2 \times 9x = 7(3x + 1)$ \\
$18x = 21x + 7$ \\
Subtract $21x$ from both sides: $-3x = 7$ \\
Divide both sides by $-3$: $x = -\frac{7}{3}$ \\
But f is only defined for $x \ge 0$, and $-\frac{7}{3} < 0$ \\
So this solution is rejected, and $ff(x) = \frac{7}{2}$ has no solutions \\
Alt: $ff(x) = \frac{9x}{3x+1} = 3 - \frac{3}{3x+1}$, so $0 \le ff(x) < 3$ \\
Since $\frac{7}{2} > 3$, $ff(x)$ can never equal $\frac{7}{2}$

@q 5
@topic Differentiation from first principles
@marks 5
@question
Check that $P(2, 6)$ is on the curve: $y = 4(2)^{2} - 5(2) = 16 - 10 = 6$ \\
Let Q be a point on the curve with $x$ coordinate $2 + h$ \\
$y_Q = 4(2 + h)^{2} - 5(2 + h)$ \\
Expand $(2 + h)^{2} = 4 + 4h + h^{2}$: \\
$y_Q = 4(4 + 4h + h^{2}) - 5(2 + h)$ \\
Expand both brackets: \\
$y_Q = 16 + 16h + 4h^{2} - 10 - 5h$ \\
Collect like terms: \\
$y_Q = 6 + 11h + 4h^{2}$ \\
Gradient of the chord PQ: \\
$\frac{y_Q - y_P}{x_Q - x_P} = \frac{(6 + 11h + 4h^{2}) - 6}{(2 + h) - 2}$ \\
Simplify the top and the bottom: \\
$= \frac{11h + 4h^{2}}{h}$ \\
Factorise the top: \\
$= \frac{h(11 + 4h)}{h}$ \\
Cancel $h$ (as $h \ne 0$): \\
$= 11 + 4h$ \\
As $h \to 0$, Q moves towards P and the chord becomes the tangent: \\
$\frac{dy}{dx} = \lim_{h \to 0} (11 + 4h) = 11$ \\
The gradient of the curve at P is 11

@q 6
@topic Substitution and partial fractions
@marks 8
@question
(a) $u = e^{\frac{1}{2}x}$ \\
Differentiate: $\frac{du}{dx} = \frac{1}{2}e^{\frac{1}{2}x} = \frac{1}{2}u$ \\
Rearrange: $dx = \frac{2}{u} \, du$ \\
Limits: when $x = 0$, $u = e^{0} = 1$ \\
When $x = 2$, $u = e^{1} = e$ \\
Area of R $= \int_{0}^{2} \frac{6}{e^{\frac{1}{2}x} + 4} \, dx$ \\
Replace $e^{\frac{1}{2}x}$ by $u$ and $dx$ by $\frac{2}{u} \, du$: \\
$= \int_{1}^{e} \frac{6}{u + 4} \times \frac{2}{u} \, du$ \\
Multiply the fractions: \\
$= \int_{1}^{e} \frac{12}{u(u + 4)} \, du$ \\
So $a = 1$ and $b = e$ \\
(b) Write $\frac{12}{u(u+4)}$ in partial fractions: \\
$\frac{12}{u(u+4)} = \frac{A}{u} + \frac{B}{u+4}$ \\
Multiply both sides by $u(u + 4)$: \\
$12 = A(u + 4) + Bu$ \\
Let $u = 0$: $12 = 4A$, so $A = 3$ \\
Let $u = -4$: $12 = -4B$, so $B = -3$ \\
$\frac{12}{u(u+4)} = \frac{3}{u} - \frac{3}{u+4}$ \\
Integrate each term: \\
$\int_{1}^{e} \left( \frac{3}{u} - \frac{3}{u+4} \right) du = \left[ 3\ln u - 3\ln(u + 4) \right]_{1}^{e}$ \\
Substitute the upper limit $u = e$ and subtract the lower limit $u = 1$: \\
$= \left( 3\ln e - 3\ln(e + 4) \right) - \left( 3\ln 1 - 3\ln 5 \right)$ \\
Use $\ln e = 1$ and $\ln 1 = 0$: \\
$= \left( 3 - 3\ln(e + 4) \right) - \left( 0 - 3\ln 5 \right)$ \\
Remove the brackets: \\
$= 3 - 3\ln(e + 4) + 3\ln 5$ \\
Write $3 = 3\ln e$: \\
$= 3\ln e + 3\ln 5 - 3\ln(e + 4)$ \\
Factorise by 3: \\
$= 3 \left( \ln e + \ln 5 - \ln(e + 4) \right)$ \\
Use $\ln a + \ln b = \ln(ab)$: \\
$= 3 \left( \ln(5e) - \ln(e + 4) \right)$ \\
Use $\ln a - \ln b = \ln \frac{a}{b}$: \\
Area of R $= 3\ln\left( \frac{5e}{e + 4} \right)$ as required

@q 7
@topic R sin form, trig modelling of temperature
@marks 8
@question
(a) Let $3\sin \theta - 4\cos \theta = R\sin(\theta - \alpha)$ \\
Expand the right-hand side using $\sin(A - B) = \sin A \cos B - \cos A \sin B$: \\
$R\sin(\theta - \alpha) = R\sin \theta \cos \alpha - R\cos \theta \sin \alpha$ \\
Equation 1, from the coefficients of $\sin \theta$: $R\cos \alpha = 3$ \\
Equation 2, from the coefficients of $\cos \theta$: $R\sin \alpha = 4$ \\
Square both equations, then add: \\
$R^{2}\cos^{2}\alpha + R^{2}\sin^{2}\alpha = 3^{2} + 4^{2}$ \\
$R^{2}(\cos^{2}\alpha + \sin^{2}\alpha) = 25$ \\
Use $\cos^{2}\alpha + \sin^{2}\alpha = 1$: $R^{2} = 25$ \\
$R = 5$ (as $R > 0$) \\
Divide equation 2 by equation 1: $\frac{R\sin \alpha}{R\cos \alpha} = \frac{4}{3}$ \\
$\tan \alpha = \frac{4}{3}$ \\
$\alpha = \tan^{-1}\left( \frac{4}{3} \right) = 53.13$ degrees (2 dp) \\
This is in the range $0 < \alpha < 90$ degrees \\
$3\sin \theta - 4\cos \theta = 5\sin(\theta - 53.13)$ \\
(b)(i) $G = 17 + 3\sin(15t) - 4\cos(15t)$ \\
Use (a) with $\theta = 15t$: $G = 17 + 5\sin(15t - 53.13)$ \\
The greatest value of $\sin$ is 1: \\
$G_{max} = 17 + 5(1) = 22$ degrees C \\
(b)(ii) Set $G = 20$: $17 + 5\sin(15t - 53.13) = 20$ \\
Subtract 17 from both sides: $5\sin(15t - 53.13) = 3$ \\
Divide both sides by 5: $\sin(15t - 53.13) = \frac{3}{5} = 0.6$ \\
Let $X = 15t - 53.13$ \\
$0 \le t \le 17$ gives $0 \le 15t \le 255$ \\
So $-53.13 \le X \le 201.87$ \\
Principal value: $X = \sin^{-1}(0.6) = 36.87$ degrees \\
Second solution: $X = 180 - 36.87 = 143.13$ degrees \\
(Adding or subtracting 360 gives values outside the range.) \\
First solution: $15t - 53.13 = 36.87$ \\
$15t = 90$, so $t = 6$ \\
This is 6 hours after 5 a.m., i.e. 11 a.m., which is before midday, so reject \\
Second solution: $15t - 53.13 = 143.13$ \\
$15t = 196.26$ \\
$t = \frac{196.26}{15} = 13.084$ \\
13 hours after 5 a.m. is 6 p.m. \\
$0.084 \times 60 = 5.04$ minutes, which is 5 minutes to the nearest minute \\
The temperature is 20 degrees C at 6:05 p.m. (18:05)

@q 8
@topic Proof, contradiction, counter-example
@marks 8
@question
(i) Complete the square: \\
$y^{2} - 4y + 7 = (y - 2)^{2} - 2^{2} + 7$ \\
$= (y - 2)^{2} - 4 + 7$ \\
$= (y - 2)^{2} + 3$ \\
$(y - 2)^{2} \ge 0$ for all real $y$ \\
So $(y - 2)^{2} + 3 \ge 3$, which is greater than 0 \\
So $y^{2} - 4y + 7$ is positive for all real values of $y$ \\
(ii) Try $x = -1$: $e^{3x} = e^{-3} = 0.0498$ and $e^{2x} = e^{-2} = 0.1353$ \\
$e^{-3} < e^{-2}$, so the claim is false when $x = -1$ \\
Try $x = 1$: $e^{3} = 20.09$ and $e^{2} = 7.389$ \\
$e^{3} \ge e^{2}$, so the claim is true when $x = 1$ \\
In general: $e^{3x} - e^{2x} = e^{2x}(e^{x} - 1)$ \\
$e^{2x} > 0$, so this is $\ge 0$ only when $e^{x} \ge 1$, i.e. $x \ge 0$ \\
The claim is true for some values of $x$ and false for others, so Bobby's claim is sometimes true \\
(iii) Assume the opposite: $n^{2}$ is even but $n$ is odd \\
If $n$ is odd then $n = 2k + 1$, where $k$ is an integer \\
$n^{2} = (2k + 1)^{2}$ \\
Expand the bracket: $n^{2} = 4k^{2} + 4k + 1$ \\
Take out a factor of 2 from the first two terms: $n^{2} = 2(2k^{2} + 2k) + 1$ \\
$2k^{2} + 2k$ is an integer, so $n^{2}$ is 2 $\times$ (an integer) + 1 \\
So $n^{2}$ is odd, which contradicts $n^{2}$ being even \\
So the assumption is wrong: if $n^{2}$ is even then $n$ must be even \\
Elsa's claim is true \\
(iv) Take the irrational numbers $\pi$ and $9 - \pi$ (they are different) \\
$9 - \pi$ is irrational, otherwise $\pi = 9 - (9 - \pi)$ would be rational \\
Their sum: $\pi + (9 - \pi) = 9$, which is rational \\
So Ying's claim fails for this pair \\
Now take the irrational numbers $\pi$ and $9 + \pi$ (they are different) \\
Their sum: $\pi + (9 + \pi) = 2\pi + 9$ \\
Suppose $2\pi + 9 = \frac{p}{q}$, where $p$ and $q$ are integers \\
Subtract 9 and divide by 2: $\pi = \frac{p - 9q}{2q}$, which is rational \\
This is a contradiction, so $2\pi + 9$ is irrational and the claim holds for this pair \\
The claim is true for some pairs and false for others, so Ying's claim is sometimes true

@q 9
@topic Trig identity, cosec, no real solutions
@marks 5
@question
(a) Use the common denominator $(1 - \cos x)\sin x$: \\
Multiply the first fraction top and bottom by $\sin x$, and the second top and bottom by $(1 - \cos x)$ \\
$\frac{\sin x}{1 - \cos x} + \frac{1 - \cos x}{\sin x} = \frac{\sin x \times \sin x}{(1 - \cos x)\sin x} + \frac{(1 - \cos x)(1 - \cos x)}{(1 - \cos x)\sin x}$ \\
Add the numerators: \\
$= \frac{\sin^{2} x + (1 - \cos x)^{2}}{(1 - \cos x)\sin x}$ \\
Expand $(1 - \cos x)^{2} = 1 - 2\cos x + \cos^{2} x$: \\
$= \frac{\sin^{2} x + 1 - 2\cos x + \cos^{2} x}{(1 - \cos x)\sin x}$ \\
Group $\sin^{2} x + \cos^{2} x$ together: \\
$= \frac{(\sin^{2} x + \cos^{2} x) + 1 - 2\cos x}{(1 - \cos x)\sin x}$ \\
Use $\sin^{2} x + \cos^{2} x = 1$: \\
$= \frac{1 + 1 - 2\cos x}{(1 - \cos x)\sin x}$ \\
$= \frac{2 - 2\cos x}{(1 - \cos x)\sin x}$ \\
Factorise the numerator: $2 - 2\cos x = 2(1 - \cos x)$ \\
$= \frac{2(1 - \cos x)}{(1 - \cos x)\sin x}$ \\
Cancel $(1 - \cos x)$, which is not zero as $x \ne n\pi$: \\
$= \frac{2}{\sin x}$ \\
Use $\frac{1}{\sin x} = \cosec x$: \\
$= 2\cosec x$ \\
So $k = 2$ \\
(b) Using (a): $2\cosec x = 1.6$ \\
Divide both sides by 2: $\cosec x = 0.8$ \\
Since $\cosec x = \frac{1}{\sin x}$: $\sin x = \frac{1}{0.8} = 1.25$ \\
But $-1 \le \sin x \le 1$, and $1.25 > 1$ \\
So there are no real solutions \\
(Equivalently, $\cosec x$ never takes a value between $-1$ and $1$, so it can never equal $0.8$.)

@q 10
@topic Connected rates of change, filling a bowl
@marks 9
@question
$V = 4\pi h(h + 6)$ and $\frac{dV}{dt} = 80\pi$ (constant) \\
The bowl starts empty, so $V = 0$ when $t = 0$ \\
(a) When $h = 24$: $V = 4\pi(24)(24 + 6)$ \\
$= 4\pi \times 24 \times 30$ \\
$= 2880\pi$ cm$^3$ \\
The water flows in at a constant rate, so time = volume $\div$ rate: \\
Time $= \frac{2880\pi}{80\pi}$ \\
Cancel $\pi$: $= \frac{2880}{80} = 36$ seconds as required \\
(b) At $t = 8$: volume of water = rate $\times$ time $= 80\pi \times 8 = 640\pi$ \\
Put this equal to the model: $4\pi h(h + 6) = 640\pi$ \\
Divide both sides by $4\pi$: $h(h + 6) = 160$ \\
Expand the bracket: $h^{2} + 6h = 160$ \\
Rearrange: $h^{2} + 6h - 160 = 0$ \\
Factorise (numbers with product $-160$ and sum $6$ are $16$ and $-10$): \\
$(h + 16)(h - 10) = 0$ \\
$h = -16$ or $h = 10$ \\
A height cannot be negative, so $h = 10$ cm \\
Expand $V$ before differentiating: $V = 4\pi h^{2} + 24\pi h$ \\
$\frac{dV}{dh} = 8\pi h + 24\pi$ \\
Chain rule: $\frac{dV}{dt} = \frac{dV}{dh} \times \frac{dh}{dt}$ \\
$80\pi = (8\pi h + 24\pi)\frac{dh}{dt}$ \\
$\frac{dh}{dt} = \frac{80\pi}{8\pi h + 24\pi}$ \\
Substitute $h = 10$: $8\pi(10) + 24\pi = 80\pi + 24\pi = 104\pi$ \\
$\frac{dh}{dt} = \frac{80\pi}{104\pi}$ \\
Cancel $\pi$: $= \frac{80}{104}$ \\
Divide top and bottom by 8: $= \frac{10}{13}$ \\
$\frac{dh}{dt} = \frac{10}{13} = 0.769$ cm s$^{-1}$ (3 sf)

@q 11
@topic Differentiating a^x and inverse tan
@marks 6
@question
(i) $y = a^{x}$ \\
Take natural logs of both sides: $\ln y = \ln(a^{x})$ \\
Use the power law of logs: $\ln y = x\ln a$ \\
Differentiate both sides with respect to $x$ ($\ln a$ is a constant): \\
$\frac{1}{y}\frac{dy}{dx} = \ln a$ \\
Multiply both sides by $y$: \\
$\frac{dy}{dx} = y\ln a$ \\
Replace $y$ by $a^{x}$: \\
$\frac{dy}{dx} = a^{x}\ln a$ as required \\
Alt: $a^{x} = e^{x\ln a}$, so $\frac{dy}{dx} = (\ln a)e^{x\ln a} = a^{x}\ln a$ \\
(ii) $x = 2\tan y$ \\
Differentiate with respect to $y$: $\frac{dx}{dy} = 2\sec^{2} y$ \\
Use $\sec^{2} y = 1 + \tan^{2} y$: \\
$\frac{dx}{dy} = 2(1 + \tan^{2} y)$ \\
From $x = 2\tan y$: $\tan y = \frac{x}{2}$ \\
$\frac{dx}{dy} = 2\left( 1 + \frac{x^{2}}{4} \right)$ \\
Expand the bracket: \\
$= 2 + \frac{2x^{2}}{4}$ \\
$= 2 + \frac{x^{2}}{2}$ \\
Write 2 as $\frac{4}{2}$: \\
$= \frac{4}{2} + \frac{x^{2}}{2}$ \\
$= \frac{4 + x^{2}}{2}$ \\
Now $\frac{dy}{dx} = 1 \div \frac{dx}{dy}$: \\
$\frac{dy}{dx} = 1 \div \frac{4 + x^{2}}{2}$ \\
Dividing by a fraction is the same as multiplying by its reciprocal: \\
$= 1 \times \frac{2}{4 + x^{2}}$ \\
$= \frac{2}{4 + x^{2}}$ \\
So $k = 2$

@q 12
@topic Quadratic modelling, bridge cable
@marks 6
@question
(a) Put the origin at O, with the $x$-axis along the walkway \\
The curve is symmetric about the $y$-axis, so it has the form $y = ax^{2} + c$ (no $x$ term) \\
At O the cable is 4 m high, so the curve passes through $(0, 4)$: \\
$4 = a(0)^{2} + c$, so $c = 4$ \\
The towers are 100 m apart with O midway, so they are at $x = -50$ and $x = 50$ \\
Each tower is 24 m high, so the curve passes through $(50, 24)$ \\
Substitute $(50, 24)$ into $y = ax^{2} + 4$: \\
$24 = a(50)^{2} + 4$ \\
$24 = 2500a + 4$ \\
Subtract 4 from both sides: $20 = 2500a$ \\
Divide both sides by 2500: \\
$a = \frac{20}{2500} = \frac{1}{125}$ (or 0.008) \\
$y = \frac{1}{125}x^{2} + 4$, $-50 \le x \le 50$ \\
(b) The defect is 19 m horizontally from a tower (the towers are at $x = \pm 50$) \\
Its $x$ coordinate is $50 - 19 = 31$ (or $-31$ by symmetry) \\
$y = \frac{1}{125}(31)^{2} + 4$ \\
$= \frac{961}{125} + 4$ \\
$= 7.688 + 4$ \\
$= 11.688$ m \\
$11.688 < 12$, so, according to the model, Lee can safely inspect the defect \\
Alt: set $y = 12$: $12 = \frac{1}{125}x^{2} + 4$, so $\frac{1}{125}x^{2} = 8$ and $x^{2} = 1000$ \\
$x = \sqrt{1000} = 31.62$, so the cable reaches 12 m at $50 - 31.62 = 18.38$ m from a tower \\
The defect is 19 m from the tower, which is further along, so it is below 12 m \\
(c) The model treats the cable as a thin curve, ignoring its thickness (diameter) \\
A real hanging cable is not exactly a parabola, and wind can change its shape \\
The model gives 11.69 m, which is very close to the 12 m limit, so a small error in the model could change the conclusion

@q 13
@topic Sum of logs, series, set notation
@marks 6
@question
(a) Write out the terms: \\
$\sum_{n=1}^{11} \ln(p^{n}) = \ln p + \ln p^{2} + \ln p^{3} + \ldots + \ln p^{11}$ \\
Use the power law $\ln p^{n} = n\ln p$ on each term: \\
$= 1\ln p + 2\ln p + 3\ln p + \ldots + 11\ln p$ \\
Factorise by $\ln p$: \\
$= (1 + 2 + 3 + \ldots + 11)\ln p$ \\
This is an arithmetic series, first term 1, last term 11, with 11 terms: \\
$S_{11} = \frac{11}{2}(1 + 11) = \frac{11}{2} \times 12 = 66$ \\
$\sum_{n=1}^{11} \ln(p^{n}) = 66\ln p$ \\
So $k = 66$ \\
(b) Use the product law on each term: $\ln(8p^{n}) = \ln 8 + \ln(p^{n})$ \\
$\sum_{n=1}^{11} \ln(8p^{n}) = \sum_{n=1}^{11} \ln 8 + \sum_{n=1}^{11} \ln(p^{n})$ \\
$\ln 8$ is added 11 times, and the second sum is $66\ln p$ from (a): \\
$= 11\ln 8 + 66\ln p$ \\
Write $8 = 2^{3}$: $\ln 8 = \ln 2^{3} = 3\ln 2$ \\
$= 11 \times 3\ln 2 + 66\ln p$ \\
$= 33\ln 2 + 66\ln p$ \\
Factorise by 33: \\
$= 33(\ln 2 + 2\ln p)$ \\
Use the power law backwards: $2\ln p = \ln p^{2}$ \\
$= 33(\ln 2 + \ln p^{2})$ \\
Use the product law: \\
$= 33\ln(2p^{2})$ as required \\
(c) $33\ln(2p^{2}) < 0$ \\
Divide both sides by 33: $\ln(2p^{2}) < 0$ \\
Raise $e$ to the power of each side ($e^{x}$ is an increasing function): \\
$2p^{2} < e^{0}$ \\
$2p^{2} < 1$ \\
Divide both sides by 2: $p^{2} < \frac{1}{2}$ \\
$p$ is positive, so take the square root: $p < \frac{1}{\sqrt{2}}$ \\
Together with $p > 0$: $0 < p < \frac{1}{\sqrt{2}}$ \\
In set notation: $\{ p : 0 < p < \frac{1}{\sqrt{2}} \}$

@q 14
@topic Normal, integration by parts, exact area
@marks 10
@question
Plan: find where the normal $l$ meets the $x$-axis, find the area under the curve from $x = 0$ to $x = 1$, then subtract the triangle between the normal and the curve \\
Differentiate $y = 4xe^{-2x}$ with the product rule, with $u = 4x$ and $v = e^{-2x}$ \\
$u' = 4$ and $v' = -2e^{-2x}$ \\
$\frac{dy}{dx} = u'v + uv' = 4e^{-2x} + 4x(-2e^{-2x})$ \\
$\frac{dy}{dx} = 4e^{-2x} - 8xe^{-2x}$ \\
At $P(1, 4e^{-2})$: $m_T = 4e^{-2} - 8(1)e^{-2}$ \\
$m_T = -4e^{-2}$ \\
The normal is perpendicular to the tangent: \\
$m_N = \frac{-1}{m_T} = \frac{-1}{-4e^{-2}} = \frac{1}{4e^{-2}}$ \\
Use $\frac{1}{e^{-2}} = e^{2}$: \\
$m_N = \frac{e^{2}}{4}$ \\
Equation of the normal $l$: \\
$y - 4e^{-2} = \frac{e^{2}}{4}(x - 1)$ \\
It meets the $x$-axis when $y = 0$: \\
$-4e^{-2} = \frac{e^{2}}{4}(x - 1)$ \\
Multiply both sides by $\frac{4}{e^{2}} = 4e^{-2}$: \\
$x - 1 = 4e^{-2} \times (-4e^{-2})$ \\
$x - 1 = -16e^{-4}$ \\
$x = 1 - 16e^{-4}$ \\
Call this point Q: $Q(1 - 16e^{-4}, 0)$ \\
R is the area under the curve from $x = 0$ to $x = 1$, minus the triangle Q, $(1, 0)$, P \\
Area under the curve: $\int_{0}^{1} 4xe^{-2x} \, dx$ \\
Integrate by parts with $u = 4x$ and $\frac{dv}{dx} = e^{-2x}$ \\
$\frac{du}{dx} = 4$ and $v = -\frac{1}{2}e^{-2x}$ \\
$\int 4xe^{-2x} \, dx = 4x\left( -\frac{1}{2}e^{-2x} \right) - \int 4\left( -\frac{1}{2}e^{-2x} \right) dx$ \\
$= -2xe^{-2x} + \int 2e^{-2x} \, dx$ \\
$= -2xe^{-2x} + 2\left( -\frac{1}{2}e^{-2x} \right)$ \\
$= -2xe^{-2x} - e^{-2x}$ \\
Apply the limits $x = 1$ and $x = 0$: \\
$\left[ -2xe^{-2x} - e^{-2x} \right]_{0}^{1} = \left( -2e^{-2} - e^{-2} \right) - \left( -2(0)e^{0} - e^{0} \right)$ \\
$= -3e^{-2} - (0 - 1)$ \\
$= -3e^{-2} + 1$ \\
$= 1 - 3e^{-2}$ \\
The triangle has vertices Q, $(1, 0)$ and P \\
Base $= 1 - (1 - 16e^{-4}) = 16e^{-4}$ \\
Height $= 4e^{-2}$ \\
Area of triangle $= \frac{1}{2} \times 16e^{-4} \times 4e^{-2}$ \\
$= 32e^{-4}e^{-2}$ \\
$= 32e^{-6}$ \\
Area of R $= (1 - 3e^{-2}) - 32e^{-6}$ \\
$= 1 - 3e^{-2} - 32e^{-6}$ \\
As a single fraction (multiply top and bottom by $e^{6}$): \\
$= \frac{e^{6} - 3e^{4} - 32}{e^{6}}$

@q 15
@topic Vectors, trapezium, position vectors
@marks 5
@question
(Vectors are written in the form $(x, y, z)$, as column vectors.) \\
(a) $\text{OD} = \text{OA} + \text{AD}$ \\
$= (-3, 2, 7) + (2, 5, -4)$ \\
$= (-3 + 2, 2 + 5, 7 - 4)$ \\
$\text{OD} = (-1, 7, 3)$ \\
(b) Find $\text{OC}$ first: $\text{OC} = \text{OB} + \text{BC}$ \\
$= (3, -1, p) + (0, 6, -7)$ \\
$\text{OC} = (3, 5, p - 7)$ \\
$\text{DC} = \text{OC} - \text{OD}$ \\
$= (3, 5, p - 7) - (-1, 7, 3)$ \\
$= (3 + 1, 5 - 7, p - 7 - 3)$ \\
$\text{DC} = (4, -2, p - 10)$ \\
$\text{AB} = \text{OB} - \text{OA}$ \\
$= (3, -1, p) - (-3, 2, 7)$ \\
$= (3 + 3, -1 - 2, p - 7)$ \\
$\text{AB} = (6, -3, p - 7)$ \\
A trapezium has one pair of parallel sides \\
$\text{BC} = (0, 6, -7)$ and $\text{AD} = (2, 5, -4)$ are not parallel (one has a zero $x$ component, the other does not) \\
So $\text{AB}$ is parallel to $\text{DC}$: $\text{AB} = \lambda \text{DC}$ \\
$(6, -3, p - 7) = \lambda(4, -2, p - 10)$ \\
$x$ components: $6 = 4\lambda$, so $\lambda = \frac{3}{2}$ \\
Check the $y$ components: $-3 = -2\lambda = -2 \times \frac{3}{2} = -3$ \\
$z$ components: $p - 7 = \frac{3}{2}(p - 10)$ \\
Multiply both sides by 2: $2(p - 7) = 3(p - 10)$ \\
Expand both brackets: $2p - 14 = 3p - 30$ \\
Subtract $2p$ from both sides: $-14 = p - 30$ \\
Add 30 to both sides: $16 = p$ \\
So $p = 16$ \\
Check: $\text{DC} = (4, -2, 6)$ and $\text{AB} = (6, -3, 9) = \frac{3}{2}(4, -2, 6)$
