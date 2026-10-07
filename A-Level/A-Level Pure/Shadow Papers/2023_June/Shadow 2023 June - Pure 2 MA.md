@paper P2 Shadow June 2023

@q 1
@topic Second derivative, concave range
@marks 4
@question
(a) Differentiate $f(x) = 2x^{3} + 3x^{2} - 5x + 8$: \\
$f'(x) = 6x^{2} + 6x - 5$ \\
Differentiate again: \\
$f''(x) = 12x + 6$ \\
(b)(i) Set $f''(x) = 0$: \\
$12x + 6 = 0$ \\
Subtract 6: \\
$12x = -6$ \\
Divide by 12: \\
$x = -\frac{1}{2}$ \\
(ii) $f(x)$ is concave where $f''(x) < 0$ \\
$12x + 6 < 0$ \\
Subtract 6: \\
$12x < -6$ \\
Divide by 12: \\
$x < -\frac{1}{2}$ \\
(Check: at $x = -1$, $f''(-1) = -6$, which is negative, so $f$ is concave there)

@q 2
@topic Recurrence with sin and (-1)^n, sum
@marks 6
@question
(a)(i) Put $n = 1$ into $u_{n+1} = u_{n} + 5\sin \left( \frac{n\pi}{2} \right) - 3(-1)^{n}$: \\
$u_{2} = u_{1} + 5\sin \left( \frac{\pi}{2} \right) - 3(-1)^{1}$ \\
$\sin \frac{\pi}{2} = 1$ and $(-1)^{1} = -1$ \\
$u_{2} = 20 + 5(1) - 3(-1)$ \\
$u_{2} = 20 + 5 + 3$ \\
$u_{2} = 28$ as required \\
(ii) Put $n = 2$: \\
$u_{3} = u_{2} + 5\sin \left( \frac{2\pi}{2} \right) - 3(-1)^{2}$ \\
$\sin \pi = 0$ and $(-1)^{2} = 1$ \\
$u_{3} = 28 + 0 - 3$ \\
$u_{3} = 25$ \\
Put $n = 3$: \\
$u_{4} = u_{3} + 5\sin \left( \frac{3\pi}{2} \right) - 3(-1)^{3}$ \\
$\sin \frac{3\pi}{2} = -1$ and $(-1)^{3} = -1$ \\
$u_{4} = 25 + 5(-1) - 3(-1)$ \\
$u_{4} = 25 - 5 + 3$ \\
$u_{4} = 23$ \\
(b)(i) The sequence has order 4, so $u_{5} = u_{1}$ \\
$u_{5} = 20$ \\
(ii) One full cycle: $u_{1} + u_{2} + u_{3} + u_{4} = 20 + 28 + 25 + 23$ \\
$= 96$ \\
$25 = 4 \times 6 + 1$, so there are 6 full cycles (24 terms) and one extra term \\
The extra term is $u_{25} = u_{1} = 20$ \\
$\sum_{r=1}^{25} u_{r} = 6 \times 96 + 20$ \\
$= 576 + 20$ \\
$= 596$

@q 3
@topic Log equation, reject invalid root
@marks 5
@question
(a) Use the log laws to write each side as a single log \\
Left side: $2\log_{2}(x + 2) = \log_{2}(x + 2)^{2}$ \\
Right side: $2 = \log_{2} 4$, since $2^{2} = 4$ \\
$2\log_{2} x = \log_{2} x^{2}$ \\
$2 + 2\log_{2} x = \log_{2} 4 + \log_{2} x^{2}$ \\
$= \log_{2} 4x^{2}$ \\
$\log_{2}(x + 2)^{2} = \log_{2} 4x^{2}$ \\
Logs of the same base are equal when what is inside is equal: \\
$(x + 2)^{2} = 4x^{2}$ \\
Expand the bracket: \\
$x^{2} + 4x + 4 = 4x^{2}$ \\
Subtract $x^{2}$, $4x$ and 4 from both sides, to put everything on the right: \\
$0 = 3x^{2} - 4x - 4$ \\
$3x^{2} - 4x - 4 = 0$ as required \\
(b)(i) Factorise: $(3x + 2)(x - 2) = 0$ \\
$x = -\frac{2}{3}$ or $x = 2$ \\
(ii) The original equation has $\log_{2} x$ in it, and you cannot take the log of a negative number \\
$x = -\frac{2}{3}$ is negative, so $\log_{2}\left( -\frac{2}{3} \right)$ is not real \\
So $x = -\frac{2}{3}$ is not a solution \\
(Check $x = 2$: $2\log_{2} 4 = 4$ and $2 + 2\log_{2} 2 = 4$)

@q 4
@topic Cooling coffee, exponential model
@marks 4
@question
(a) At $t = 0$, $H = 90$ and $e^{0} = 1$: \\
$90 = Ae^{0} + 25$ \\
$90 = A + 25$ \\
Subtract 25: \\
$A = 65$ \\
(b) Differentiate $H = 65e^{-Bt} + 25$ with respect to $t$: \\
$\frac{dH}{dt} = 65 \times (-B)e^{-Bt}$ \\
$\frac{dH}{dt} = -65Be^{-Bt}$ \\
Initially $t = 0$, and the coffee is cooling at 8 degrees C per minute, so $\frac{dH}{dt} = -8$: \\
$-65Be^{0} = -8$ \\
$-65B = -8$ \\
Divide by $-65$: \\
$B = \frac{8}{65}$ \\
$B = 0.1231$ \\
$B = 0.123$ to 3 decimal places \\
$H = 65e^{-0.123t} + 25$

@q 5
@topic Turning point, find k, integrate
@marks 5
@question
(a) $P(5, 10)$ is a turning point, so $\frac{dy}{dx} = 0$ when $x = 5$ \\
$6(5)^{2} - 38(5) + k = 0$ \\
$6 \times 25 = 150$ and $38 \times 5 = 190$ \\
$150 - 190 + k = 0$ \\
$-40 + k = 0$ \\
Add 40: \\
$k = 40$ as required \\
(b) Integrate $\frac{dy}{dx} = 6x^{2} - 38x + 40$: \\
$y = \frac{6x^{3}}{3} - \frac{38x^{2}}{2} + 40x + c$ \\
$y = 2x^{3} - 19x^{2} + 40x + c$ \\
$P(5, 10)$ is on the curve, so put $x = 5$ and $y = 10$: \\
$10 = 2(5)^{3} - 19(5)^{2} + 40(5) + c$ \\
$2(125) = 250$ and $19(25) = 475$ \\
$10 = 250 - 475 + 200 + c$ \\
$10 = -25 + c$ \\
Add 25: \\
$c = 35$ \\
The curve is $y = 2x^{3} - 19x^{2} + 40x + 35$ \\
It crosses the $y$-axis where $x = 0$, so $y = c = 35$ \\
The point is $(0, 35)$

@q 6
@topic Parallel vectors, track speed
@marks 6
@question
(a) $\text{AD} = \text{OD} - \text{OA}$ \\
$\text{AD} = (26\mathbf{i} + 30\mathbf{j}) - 14\mathbf{i}$ \\
$\text{AD} = 12\mathbf{i} + 30\mathbf{j}$ \\
$\text{BC} = \text{OC} - \text{OB}$ \\
$\text{BC} = (36\mathbf{i} + 110\mathbf{j}) - 20\mathbf{j}$ \\
$\text{BC} = 36\mathbf{i} + 90\mathbf{j}$ \\
$36\mathbf{i} + 90\mathbf{j} = 3(12\mathbf{i} + 30\mathbf{j})$ \\
$\text{BC} = 3\text{AD}$ \\
$\text{AD}$ is a multiple of $\text{BC}$, so $AD$ is parallel to $BC$ \\
(b) Find the length of each side \\
$\text{AB} = \text{OB} - \text{OA} = -14\mathbf{i} + 20\mathbf{j}$ \\
$|\text{AB}| = \sqrt{(-14)^{2} + 20^{2}}$ \\
$= \sqrt{196 + 400}$ \\
$= \sqrt{596}$ \\
$= 2\sqrt{149}$ \\
$= 24.41$ m \\
$|\text{BC}| = \sqrt{36^{2} + 90^{2}}$ \\
$= \sqrt{1296 + 8100}$ \\
$= \sqrt{9396}$ \\
$= 18\sqrt{29}$ \\
$= 96.93$ m \\
$\text{CD} = \text{OD} - \text{OC} = -10\mathbf{i} - 80\mathbf{j}$ \\
$|\text{CD}| = \sqrt{(-10)^{2} + (-80)^{2}}$ \\
$= \sqrt{100 + 6400}$ \\
$= \sqrt{6500}$ \\
$= 10\sqrt{65}$ \\
$= 80.62$ m \\
$|\text{DA}| = \sqrt{12^{2} + 30^{2}}$ \\
$= \sqrt{144 + 900}$ \\
$= \sqrt{1044}$ \\
$= 6\sqrt{29}$ \\
$= 32.31$ m \\
One lap: $24.41 + 96.93 + 80.62 + 32.31 = 234.28$ m \\
3 laps: $3 \times 234.28 = 702.8$ m \\
Change to kilometres: $702.8 \div 1000 = 0.7028$ km \\
8 minutes in hours: $\frac{8}{60} = 0.13333$ hours \\
Speed $= \frac{\text{distance}}{\text{time}}$ \\
Speed $= \frac{0.7028}{0.13333}$ \\
Speed $= 5.27$ km per hour to 3 significant figures

@q 7
@topic Implicit differentiation, normal
@marks 7
@question
(a) Differentiate $x^{3} + 4xy + 5y^{2} = 32$ with respect to $x$ \\
$x^{3} \to 3x^{2}$ \\
$4xy$: product rule gives $4y + 4x\frac{dy}{dx}$ \\
$5y^{2}$: chain rule gives $10y\frac{dy}{dx}$ \\
$32 \to 0$ \\
$3x^{2} + 4y + 4x\frac{dy}{dx} + 10y\frac{dy}{dx} = 0$ \\
Move the terms without $\frac{dy}{dx}$ to the right: \\
$4x\frac{dy}{dx} + 10y\frac{dy}{dx} = -3x^{2} - 4y$ \\
Factorise out $\frac{dy}{dx}$: \\
$(4x + 10y)\frac{dy}{dx} = -3x^{2} - 4y$ \\
Divide by $(4x + 10y)$: \\
$\frac{dy}{dx} = -\frac{3x^{2} + 4y}{4x + 10y}$ \\
(b) At $P(-1, 3)$: \\
Top: $3(-1)^{2} + 4(3) = 3 + 12 = 15$ \\
Bottom: $4(-1) + 10(3) = -4 + 30 = 26$ \\
$\frac{dy}{dx} = -\frac{15}{26}$ \\
The normal is perpendicular to the tangent, so its gradient is the negative reciprocal: \\
Gradient of the normal $= \frac{26}{15}$ \\
$y - 3 = \frac{26}{15}(x - (-1))$ \\
$y - 3 = \frac{26}{15}(x + 1)$ \\
Multiply both sides by 15: \\
$15y - 45 = 26(x + 1)$ \\
Expand the bracket: \\
$15y - 45 = 26x + 26$ \\
Subtract $15y$ from both sides and add 45 to the right: \\
$0 = 26x - 15y + 71$ \\
$26x - 15y + 71 = 0$

@q 8
@topic R cos(t - a) form, arithmetic sum S9
@marks 6
@question
(a) Write $R\cos (\theta - \alpha)$ out using the compound angle formula: \\
$R\cos (\theta - \alpha) = R\cos \theta \cos \alpha + R\sin \theta \sin \alpha$ \\
Compare with $\cos \theta + 8\sin \theta$ \\
Coefficient of $\cos \theta$: $R\cos \alpha = 1$ \\
Coefficient of $\sin \theta$: $R\sin \alpha = 8$ \\
Square both equations and add: \\
$R^{2}\cos^{2} \alpha + R^{2}\sin^{2} \alpha = 1^{2} + 8^{2}$ \\
$R^{2}(\cos^{2} \alpha + \sin^{2} \alpha) = 65$ \\
$\cos^{2} \alpha + \sin^{2} \alpha = 1$, so $R^{2} = 65$ \\
$R = \sqrt{65}$ \\
Divide $R\sin \alpha = 8$ by $R\cos \alpha = 1$: \\
$\tan \alpha = 8$ \\
$\alpha = \tan^{-1} 8$ \\
$\alpha = 1.446$ radians to 3 decimal places \\
$\cos \theta + 8\sin \theta = \sqrt{65}\cos (\theta - 1.446)$ \\
(b)(i) The sequence is arithmetic with first term $a = \cos x$ \\
Common difference: $(\cos x + 2\sin x) - \cos x = 2\sin x$ \\
$d = 2\sin x$ \\
Sum of an arithmetic series: $S_{n} = \frac{n}{2}\{ 2a + (n - 1)d \}$ \\
$S_{9} = \frac{9}{2}\{ 2\cos x + 8 \times 2\sin x \}$ \\
$S_{9} = \frac{9}{2}\{ 2\cos x + 16\sin x \}$ \\
Take out a factor of 2 inside the bracket: \\
$S_{9} = \frac{9}{2} \times 2(\cos x + 8\sin x)$ \\
$S_{9} = 9(\cos x + 8\sin x)$ \\
Use part (a): \\
$S_{9} = 9\sqrt{65}\cos (x - 1.446)$ \\
The largest value of cosine is 1 \\
Maximum $S_{9} = 9\sqrt{65}$ \\
(ii) The maximum happens when $\cos (x - 1.446) = 1$ \\
$x - 1.446 = 0$ \\
$x = 1.446$ \\
The smallest positive value of $x$ is 1.446 radians

@q 9
@topic Parametric to Cartesian, tangent at P
@marks 7
@question
(a) Complete the square for $x$: \\
$x = t^{2} + 8t - 20$ \\
$t^{2} + 8t = (t + 4)^{2} - 16$ \\
$x = (t + 4)^{2} - 16 - 20$ \\
$x = (t + 4)^{2} - 36$ \\
Add 36 to both sides: \\
$x + 36 = (t + 4)^{2}$ \\
Take the square root (as $t > -4$, so $t + 4 > 0$): \\
$t + 4 = (x + 36)^{\frac{1}{2}}$ \\
Substitute into $y = 8\ln (t + 4)$: \\
$y = 8\ln (x + 36)^{\frac{1}{2}}$ \\
Use $\ln a^{n} = n\ln a$: \\
$y = 8 \times \frac{1}{2}\ln (x + 36)$ \\
$y = 4\ln (x + 36)$ \\
So $A = 4$ and $B = 36$ \\
Since $t + 4 > 0$ we have $x + 36 > 0$, so $x > -36$ \\
(b) $C$ cuts the $y$-axis where $x = 0$ \\
$y = 4\ln (0 + 36)$ \\
$y = 4\ln 36$ \\
Use $\ln 36 = \ln 6^{2} = 2\ln 6$: \\
$y = 8\ln 6$ \\
$P = (0, 8\ln 6)$ \\
Differentiate $y = 4\ln (x + 36)$: \\
$\frac{dy}{dx} = \frac{4}{x + 36}$ \\
At $P$, $x = 0$: \\
$\frac{dy}{dx} = \frac{4}{36}$ \\
$\frac{dy}{dx} = \frac{1}{9}$ \\
The tangent has gradient $\frac{1}{9}$ and passes through $(0, 8\ln 6)$: \\
$y - 8\ln 6 = \frac{1}{9}(x - 0)$ \\
Multiply both sides by 9: \\
$9y - 72\ln 6 = x$ \\
Subtract $x$ and add $72\ln 6$: \\
$9y - x = 72\ln 6$ \\
In the form $ax + by = c\ln 6$: $-x + 9y = 72\ln 6$, so $a = -1$, $b = 9$, $c = 72$

@q 10
@topic Partial fractions with k, integral
@marks 7
@question
(a) Write $\frac{3kx - 12}{(x + 2)(x - 1)} = \frac{A}{x + 2} + \frac{B}{x - 1}$ \\
Multiply both sides by $(x + 2)(x - 1)$: \\
$3kx - 12 = A(x - 1) + B(x + 2)$ \\
Put $x = 1$ (this removes the $A$ term): \\
$3k - 12 = B(3)$ \\
$B = \frac{3k - 12}{3}$ \\
$B = k - 4$ \\
Put $x = -2$ (this removes the $B$ term): \\
$-6k - 12 = A(-3)$ \\
$A = \frac{-6k - 12}{-3}$ \\
$A = 2k + 4$ \\
$f(x) = \frac{2k + 4}{x + 2} + \frac{k - 4}{x - 1}$ \\
(b) Integrate each term: \\
$\int \frac{2k + 4}{x + 2} dx = (2k + 4)\ln |x + 2|$ \\
$\int \frac{k - 4}{x - 1} dx = (k - 4)\ln |x - 1|$ \\
$\int_{-1}^{0} f(x) dx = \left[ (2k + 4)\ln |x + 2| + (k - 4)\ln |x - 1| \right]_{-1}^{0}$ \\
Upper limit $x = 0$: \\
$(2k + 4)\ln 2 + (k - 4)\ln 1$ \\
$\ln 1 = 0$ \\
$= (2k + 4)\ln 2$ \\
Lower limit $x = -1$: \\
$(2k + 4)\ln 1 + (k - 4)\ln 2$ \\
$= (k - 4)\ln 2$ \\
Subtract the lower limit from the upper limit: \\
$(2k + 4)\ln 2 - (k - 4)\ln 2$ \\
Take out the factor $\ln 2$: \\
$= (2k + 4 - k + 4)\ln 2$ \\
$= (k + 8)\ln 2$ \\
Set this equal to 15: \\
$(k + 8)\ln 2 = 15$ \\
Divide by $\ln 2$: \\
$k + 8 = \frac{15}{\ln 2}$ \\
Subtract 8: \\
$k = \frac{15}{\ln 2} - 8$ \\
(That is about 13.64, which is positive, as required)

@q 11
@topic Tank filling, rate inverse to root h
@marks 10
@question
(a) Volume of water: $V = 16 \times 8 \times h$ \\
$V = 128h$ \\
$\frac{dV}{dh} = 128$ \\
The rate of change of $V$ is inversely proportional to $\sqrt{h}$: \\
$\frac{dV}{dt} = \frac{k}{\sqrt{h}}$ for a constant $k$ \\
Use the chain rule: $\frac{dh}{dt} = \frac{dh}{dV} \times \frac{dV}{dt}$ \\
$\frac{dh}{dV} = \frac{1}{128}$ \\
$\frac{dh}{dt} = \frac{1}{128} \times \frac{k}{\sqrt{h}}$ \\
$\frac{dh}{dt} = \frac{k}{128\sqrt{h}}$ \\
Let $\lambda = \frac{k}{128}$, which is a constant: \\
$\frac{dh}{dt} = \frac{\lambda}{\sqrt{h}}$ as required \\
(b) Separate the variables: multiply by $\sqrt{h}$ and by $dt$ \\
$\sqrt{h} \, dh = \lambda \, dt$ \\
$h^{\frac{1}{2}} dh = \lambda \, dt$ \\
Integrate both sides: \\
$\frac{h^{\frac{3}{2}}}{\frac{3}{2}} = \lambda t + c$ \\
$\frac{2}{3}h^{\frac{3}{2}} = \lambda t + c$ \\
Initially $t = 0$ and $h = 1.21$: \\
$\frac{2}{3}(1.21)^{\frac{3}{2}} = \lambda(0) + c$ \\
$1.21^{\frac{3}{2}} = (\sqrt{1.21})^{3} = 1.1^{3} = 1.331$ \\
$c = \frac{2}{3} \times 1.331$ \\
$c = 0.88733$ \\
At $t = 6$, $h = 2.56$: \\
$\frac{2}{3}(2.56)^{\frac{3}{2}} = 6\lambda + 0.88733$ \\
$2.56^{\frac{3}{2}} = (\sqrt{2.56})^{3} = 1.6^{3} = 4.096$ \\
$\frac{2}{3} \times 4.096 = 2.73067$ \\
$2.73067 = 6\lambda + 0.88733$ \\
Subtract 0.88733: \\
$6\lambda = 1.84333$ \\
Divide by 6: \\
$\lambda = 0.30722$ \\
Put $\lambda$ and $c$ back: \\
$\frac{2}{3}h^{\frac{3}{2}} = 0.30722t + 0.88733$ \\
Multiply both sides by $\frac{3}{2}$: \\
$h^{\frac{3}{2}} = 0.46083t + 1.331$ \\
$h^{\frac{3}{2}} = 0.461t + 1.331$ \\
(c) The tank is full when $h = 4$ \\
$4^{\frac{3}{2}} = (\sqrt{4})^{3} = 2^{3} = 8$ \\
$8 = 0.46083t + 1.331$ \\
Subtract 1.331: \\
$6.669 = 0.46083t$ \\
Divide by 0.46083: \\
$t = 14.47$ \\
It took about 14.5 minutes to be completely full

@q 12
@topic Modulus models, two companies
@marks 10
@question
(a) Initially $t = 0$ \\
$N_{A} = |0 - 4| + 3 = 4 + 3 = 7$ \\
$N_{B} = 10 - |0 - 9| = 10 - 9 = 1$ \\
Difference: $N_{A} - N_{B} = 7 - 1 = 6$ \\
The numbers are in thousands, so the difference is 6000 subscribers \\
(b) The graph of $N_{A}$ has its lowest point (the vertex) at $t = 4$ \\
$|t - 4| = 0$ when $t = 4$, so $N_{A}$ is smallest there, 3 thousand \\
A company would reduce its prices when it has the fewest subscribers, to win more \\
$T = 4$, because that is the point when company A had the lowest number of subscribers \\
(c) First find where the graphs meet: $N_{A} = N_{B}$ \\
From the sketch the first crossing is before $t = 4$ and the second is after $t = 4.5$ \\
For $t < 4$: $|t - 4| = 4 - t$, so $N_{A} = 4 - t + 3 = 7 - t$ \\
For $t < 4.5$: $|2t - 9| = 9 - 2t$, so $N_{B} = 10 - (9 - 2t) = 1 + 2t$ \\
First crossing: $7 - t = 1 + 2t$ \\
Add $t$ and subtract 1: \\
$6 = 3t$ \\
$t = 2$ \\
For $t > 4$: $|t - 4| = t - 4$, so $N_{A} = t - 4 + 3 = t - 1$ \\
For $t > 4.5$: $|2t - 9| = 2t - 9$, so $N_{B} = 10 - (2t - 9) = 19 - 2t$ \\
Second crossing: $t - 1 = 19 - 2t$ \\
Add $2t$ and add 1: \\
$3t = 20$ \\
$t = \frac{20}{3}$ \\
(Check $t = \frac{20}{3} = 6.67$ is greater than 4.5, so the pieces used are valid) \\
$N_{A}$ is above $N_{B}$ outside the two crossing points: before the first and after the second \\
(Check: at $t = 0$, $N_{A} = 7 > N_{B} = 1$; at $t = 3$, $N_{A} = 4 < N_{B} = 7$; at $t = 7$, $N_{A} = 6 > N_{B} = 5$) \\
$\{ t : 0 \leq t < 2 \} \text{ or } \left\{ t : t > \frac{20}{3} \right\}$ \\
(d) $N_{B} = 10 - |2t - 9|$ becomes negative once $|2t - 9| > 10$, which is when $t > 9.5$ \\
A number of subscribers cannot be negative \\
So the model for company B is not valid after $t = 9.5$ years

@q 13
@topic Binomial (2+x)^-2, integrate, exact
@marks 13
@question
(a) Take out the factor 2 from the bracket: \\
$(2 + x)^{-2} = \left[ 2\left( 1 + \frac{x}{2} \right) \right]^{-2}$ \\
$= 2^{-2}\left( 1 + \frac{x}{2} \right)^{-2}$ \\
$2^{-2} = \frac{1}{4}$ \\
Binomial expansion: $(1 + y)^{n} = 1 + ny + \frac{n(n - 1)}{2!}y^{2} + \ldots$ \\
Here $n = -2$ and $y = \frac{x}{2}$ \\
Second term: $(-2)\left( \frac{x}{2} \right) = -x$ \\
Third term: $\frac{(-2)(-3)}{2!}\left( \frac{x}{2} \right)^{2}$ \\
$\frac{(-2)(-3)}{2} = 3$ \\
$\left( \frac{x}{2} \right)^{2} = \frac{x^{2}}{4}$ \\
$3 \times \frac{x^{2}}{4} = \frac{3x^{2}}{4}$ \\
$\left( 1 + \frac{x}{2} \right)^{-2} = 1 - x + \frac{3x^{2}}{4} + \ldots$ \\
Multiply by $\frac{1}{4}$: \\
$\frac{1}{4} \times 1 = \frac{1}{4}$ \\
$\frac{1}{4} \times (-x) = -\frac{x}{4}$ \\
$\frac{1}{4} \times \frac{3x^{2}}{4} = \frac{3x^{2}}{16}$ \\
$(2 + x)^{-2} = \frac{1}{4} - \frac{x}{4} + \frac{3x^{2}}{16} + \ldots$ \\
(b) $\frac{8x}{(2 + x)^{2}} = 8x(2 + x)^{-2}$ \\
Use the expansion from part (a): \\
$8x\left( \frac{1}{4} - \frac{x}{4} + \frac{3x^{2}}{16} \right)$ \\
Multiply out: \\
$8x \times \frac{1}{4} = 2x$ \\
$8x \times \left( -\frac{x}{4} \right) = -2x^{2}$ \\
$8x \times \frac{3x^{2}}{16} = \frac{3x^{3}}{2}$ \\
$\frac{8x}{(2 + x)^{2}} \approx 2x - 2x^{2} + \frac{3x^{3}}{2}$ \\
Integrate each term: \\
$\int \left( 2x - 2x^{2} + \frac{3x^{3}}{2} \right) dx = x^{2} - \frac{2x^{3}}{3} + \frac{3x^{4}}{8}$ \\
Upper limit $x = 0.3$: \\
$0.3^{2} = 0.09$ \\
$\frac{2(0.3)^{3}}{3} = \frac{2(0.027)}{3} = 0.018$ \\
$\frac{3(0.3)^{4}}{8} = \frac{3(0.0081)}{8} = 0.0030375$ \\
$0.09 - 0.018 + 0.0030375 = 0.0750375$ \\
Lower limit $x = 0.1$: \\
$0.1^{2} = 0.01$ \\
$\frac{2(0.1)^{3}}{3} = \frac{2(0.001)}{3} = 0.00066667$ \\
$\frac{3(0.1)^{4}}{8} = \frac{3(0.0001)}{8} = 0.0000375$ \\
$0.01 - 0.00066667 + 0.0000375 = 0.0093708$ \\
Subtract: $0.0750375 - 0.0093708 = 0.0656667$ \\
The estimate is 0.06567 to 4 significant figures \\
(c) Use the substitution $u = 2 + x$, so $x = u - 2$ and $dx = du$ \\
Limits: when $x = 0.1$, $u = 2.1$; when $x = 0.3$, $u = 2.3$ \\
$\int_{0.1}^{0.3} \frac{8x}{(2 + x)^{2}} dx = \int_{2.1}^{2.3} \frac{8(u - 2)}{u^{2}} du$ \\
Expand the top: \\
$\frac{8(u - 2)}{u^{2}} = \frac{8u - 16}{u^{2}}$ \\
Split into two fractions: \\
$= \frac{8u}{u^{2}} - \frac{16}{u^{2}}$ \\
$= \frac{8}{u} - 16u^{-2}$ \\
Integrate each term: \\
$\int \frac{8}{u} du = 8\ln u$ \\
$\int -16u^{-2} du = -16 \times \frac{u^{-1}}{-1} = 16u^{-1}$ \\
$\int \left( \frac{8}{u} - \frac{16}{u^{2}} \right) du = 8\ln u + \frac{16}{u}$ \\
Upper limit $u = 2.3$: $8\ln 2.3 + \frac{16}{2.3}$ \\
Lower limit $u = 2.1$: $8\ln 2.1 + \frac{16}{2.1}$ \\
Subtract the lower limit from the upper limit: \\
$8\ln 2.3 + \frac{16}{2.3} - 8\ln 2.1 - \frac{16}{2.1}$ \\
Combine the logs: $8\ln 2.3 - 8\ln 2.1 = 8\ln \frac{2.3}{2.1}$ \\
$\frac{2.3}{2.1} = \frac{23}{21}$ \\
Combine the fractions: $\frac{16}{2.3} - \frac{16}{2.1} = 16\left( \frac{2.1 - 2.3}{2.3 \times 2.1} \right)$ \\
$= 16 \times \frac{-0.2}{4.83}$ \\
$= \frac{-3.2}{4.83}$ \\
$= -\frac{320}{483}$ \\
The exact value is $8\ln \frac{23}{21} - \frac{320}{483}$ \\
So $a = 8$, $b = \frac{23}{21}$, $c = -\frac{320}{483}$ \\
(Check: $8\ln \frac{23}{21} - \frac{320}{483} = 0.7278 - 0.6625 = 0.0652$, close to the estimate in part (b))

@q 14
@topic Trig identity with tan, sec, solve
@marks 7
@question
(a) Use $1 + \tan^{2} \theta = \sec^{2} \theta$ on the left side and $1 - 2\sin^{2} \theta = \cos 2\theta$ on the right side: \\
$3\cos 2\theta \sec^{2} \theta = \cos 2\theta (2 + 3\tan \theta \sec \theta)$ \\
Write in terms of sine and cosine: $\sec^{2} \theta = \frac{1}{\cos^{2} \theta}$ \\
$\tan \theta \sec \theta = \frac{\sin \theta}{\cos \theta} \times \frac{1}{\cos \theta} = \frac{\sin \theta}{\cos^{2} \theta}$ \\
$\frac{3\cos 2\theta}{\cos^{2} \theta} = \cos 2\theta \left( 2 + \frac{3\sin \theta}{\cos^{2} \theta} \right)$ \\
Write the bracket over $\cos^{2} \theta$: \\
$\frac{3\cos 2\theta}{\cos^{2} \theta} = \cos 2\theta \left( \frac{2\cos^{2} \theta + 3\sin \theta}{\cos^{2} \theta} \right)$ \\
Multiply both sides by $\cos^{2} \theta$: \\
$3\cos 2\theta = \cos 2\theta (2\cos^{2} \theta + 3\sin \theta)$ \\
Subtract the right side from both sides: \\
$\cos 2\theta (3 - 2\cos^{2} \theta - 3\sin \theta) = 0$ \\
Use $\cos^{2} \theta = 1 - \sin^{2} \theta$: \\
$\cos 2\theta (3 - 2(1 - \sin^{2} \theta) - 3\sin \theta) = 0$ \\
Expand the bracket: \\
$\cos 2\theta (3 - 2 + 2\sin^{2} \theta - 3\sin \theta) = 0$ \\
$\cos 2\theta (2\sin^{2} \theta - 3\sin \theta + 1) = 0$ \\
So $A = 2$, $B = -3$, $C = 1$ \\
(b) Using part (a) with $\theta = x$: \\
$\cos 2x (2\sin^{2} x - 3\sin x + 1) = 0$ \\
Either $\cos 2x = 0$ or $2\sin^{2} x - 3\sin x + 1 = 0$ \\
Case 1: $\cos 2x = 0$ \\
$2x = 90 + 180n$ \\
$x = 45 + 90n$ \\
For $360 \leq x \leq 540$: $n = 4$ gives $x = 405$ and $n = 5$ gives $x = 495$ \\
($n = 3$ gives 315 and $n = 6$ gives 585, which are out of range) \\
Case 2: $2\sin^{2} x - 3\sin x + 1 = 0$ \\
Factorise: $(2\sin x - 1)(\sin x - 1) = 0$ \\
$\sin x = \frac{1}{2}$ or $\sin x = 1$ \\
$\sin x = \frac{1}{2}$: $x = 30 + 360 = 390$ or $x = 150 + 360 = 510$ \\
$\sin x = 1$: $x = 90 + 360 = 450$ \\
But at $x = 450$, $\cos x = 0$, so $\tan x$ and $\sec x$ are not defined, and 450 is not allowed \\
$x = 390, 405, 495, 510$ degrees

@q 15
@topic Proof by contradiction, 1/a + 1/b
@marks 3
@question
Start from the student's assumption: \\
$\frac{1}{a} + \frac{1}{b} = \frac{2}{a + b}$ \\
Add the fractions on the left over a common denominator $ab$: \\
$\frac{b}{ab} + \frac{a}{ab} = \frac{a + b}{ab}$ \\
$\frac{a + b}{ab} = \frac{2}{a + b}$ \\
Cross multiply: \\
$(a + b)(a + b) = 2ab$ \\
$(a + b)^{2} = 2ab$ \\
Expand the bracket: \\
$a^{2} + 2ab + b^{2} = 2ab$ \\
Subtract $2ab$ from both sides: \\
$a^{2} + b^{2} = 0$ \\
Subtract $b^{2}$ from both sides: \\
$a^{2} = -b^{2}$ \\
$b^{2}$ is positive, so $-b^{2}$ is negative \\
A real number squared cannot be negative, so there is no real $a$ with $a^{2} = -b^{2}$ \\
That is a contradiction, so the assumption is wrong \\
Therefore $\frac{1}{a} + \frac{1}{b} \ne \frac{2}{a + b}$
