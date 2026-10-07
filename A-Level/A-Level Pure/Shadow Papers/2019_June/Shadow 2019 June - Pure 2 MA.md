@paper P2 Shadow June 2019

@q 1
@topic Indices, y as a function of x
@marks 3
@question
Write every number as a power of 2 \\
$32 = 2^{5}$, so $32^{x} = (2^{5})^{x}$ \\
Multiply the powers: $(2^{5})^{x} = 2^{5x}$ \\
$8 = 2^{3}$ and $\sqrt{2} = 2^{\frac{1}{2}}$ \\
$8\sqrt{2} = 2^{3} \times 2^{\frac{1}{2}}$ \\
Add the powers: $8\sqrt{2} = 2^{\frac{7}{2}}$ \\
$\frac{1}{8\sqrt{2}} = \frac{1}{2^{\frac{7}{2}}} = 2^{-\frac{7}{2}}$ \\
Left hand side: $2^{5x} \times 2^{y} = 2^{5x + y}$ \\
The equation is $2^{5x + y} = 2^{-\frac{7}{2}}$ \\
The bases are equal, so the powers are equal: \\
$5x + y = -\frac{7}{2}$ \\
Subtract $5x$ from both sides: \\
$y = -5x - \frac{7}{2}$

@q 2
@topic Trapezium rule, over/underestimate
@marks 4
@question
(a) Distance is the area under the speed-time graph \\
There are 6 readings, so 5 strips of width $h = 2$ \\
Trapezium rule: $\frac{h}{2}\left\{ y_{0} + y_{5} + 2(y_{1} + y_{2} + y_{3} + y_{4}) \right\}$ \\
First and last speeds: $y_{0} = 2$ and $y_{5} = 26$ \\
Middle speeds: $7, 9, 13, 22$ \\
$\frac{2}{2}\left\{ 2 + 26 + 2(7 + 9 + 13 + 22) \right\}$ \\
Add the middle speeds: $7 + 9 + 13 + 22 = 51$ \\
Double them: $2 \times 51 = 102$ \\
Add the first and last: $2 + 26 = 28$ \\
$1 \times (28 + 102)$ \\
Distance $= 130$ m \\
(b) The tops of the trapezia are straight chords joining points of the speed-time curve \\
The jet speeds up, so the curve bends upwards \\
Chords of an upward bending curve lie above it \\
So the five trapezia have more area than the area under the curve \\
130 m is an overestimate

@q 3
@topic Sector area, radians error
@marks 3
@question
(a) The formula $\text{Area} = \frac{1}{2}r^{2}\theta$ only works when $\theta$ is in radians \\
The student put in $\theta = 36$, which is in degrees \\
(b) Change 36 degrees to radians by multiplying by $\frac{\pi}{180}$ \\
$\theta = 36 \times \frac{\pi}{180}$ \\
$\theta = \frac{\pi}{5}$ \\
$\text{Area} = \frac{1}{2}r^{2}\theta$ \\
$= \frac{1}{2} \times 7^{2} \times \frac{\pi}{5}$ \\
$7^{2} = 49$ \\
$= \frac{1}{2} \times 49 \times \frac{\pi}{5}$ \\
$= \frac{49\pi}{10}$ \\
$= 15.39 \text{ cm}^{2}$ \\
(Check: 36 degrees is $\frac{36}{360} = \frac{1}{10}$ of a full turn, and $\frac{1}{10} \times \pi \times 49 = 4.9\pi = 15.39$)

@q 4
@topic Parametric ellipse meets circle
@marks 6
@question
The curves meet where the points on $C_{1}$ also satisfy the equation of $C_{2}$ \\
Substitute $x = 22\cos t$ and $y = 2\sqrt{5}\sin t$ into $x^{2} + y^{2} = 130$: \\
$(22\cos t)^{2} + (2\sqrt{5}\sin t)^{2} = 130$ \\
Square each bracket: $22^{2} = 484$ and $(2\sqrt{5})^{2} = 4 \times 5 = 20$ \\
$484\cos^{2} t + 20\sin^{2} t = 130$ \\
Use $\sin^{2} t = 1 - \cos^{2} t$ \\
$484\cos^{2} t + 20(1 - \cos^{2} t) = 130$ \\
Expand the bracket: \\
$484\cos^{2} t + 20 - 20\cos^{2} t = 130$ \\
Collect the $\cos^{2} t$ terms: \\
$464\cos^{2} t + 20 = 130$ \\
Subtract 20 from both sides: \\
$464\cos^{2} t = 110$ \\
Divide by 464: \\
$\cos^{2} t = \frac{110}{464}$ \\
$\cos^{2} t = \frac{55}{232}$ \\
Square root both sides: \\
$\cos t = \pm \sqrt{\frac{55}{232}}$ \\
$\cos t = \pm 0.48690$ \\
$S$ is in the 4th quadrant, so $x > 0$ and $y < 0$ \\
$x > 0$ means $\cos t > 0$, so $\cos t = 0.48690$ \\
$y < 0$ means $\sin t < 0$, so $t$ is between $\frac{3\pi}{2}$ and $2\pi$ \\
$\cos^{-1}(0.48690) = 1.0623$ \\
$t = 2\pi - 1.0623$ \\
$t = 5.2209$ \\
Find $x$: $x = 22\cos t = 22 \times 0.48690$ \\
$x = 10.712$ \\
Find $\sin t$ (negative): $\sin t = -\sqrt{1 - \frac{55}{232}}$ \\
$= -\sqrt{\frac{177}{232}}$ \\
$= -0.87346$ \\
Find $y$: $y = 2\sqrt{5}\sin t = 4.4721 \times (-0.87346)$ \\
$y = -3.9062$ \\
$S = (10.7, -3.91)$ to 3 significant figures \\
(Check: $10.712^{2} + 3.9062^{2} = 114.74 + 15.26 = 130.00$)

@q 5
@topic Sum as integral, root x
@marks 3
@question
As $\delta x \to 0$ the sum of the thin rectangle areas becomes an integral \\
$\lim_{\delta x \to 0} \sum_{x=1}^{16} y \, \delta x = \int_{1}^{16} y \, dx$ \\
For $x \geq 1$, $\sqrt{x}$ is positive, so $|\sqrt{x}| = \sqrt{x}$ \\
$\int_{1}^{16} \sqrt{x} \, dx = \int_{1}^{16} x^{\frac{1}{2}} dx$ \\
Add 1 to the power and divide by the new power: \\
$= \left[ \frac{x^{\frac{3}{2}}}{\frac{3}{2}} \right]_{1}^{16}$ \\
$= \left[ \frac{2}{3}x^{\frac{3}{2}} \right]_{1}^{16}$ \\
Upper limit: $\frac{2}{3} \times 16^{\frac{3}{2}}$ \\
$16^{\frac{3}{2}} = (\sqrt{16})^{3} = 4^{3} = 64$ \\
$\frac{2}{3} \times 64 = \frac{128}{3}$ \\
Lower limit: $\frac{2}{3} \times 1^{\frac{3}{2}} = \frac{2}{3}$ \\
Subtract: $\frac{128}{3} - \frac{2}{3}$ \\
$= \frac{126}{3}$ \\
$= 42$

@q 6
@topic Piecewise function, inverse
@marks 10
@question
(a) First find $g(0)$. Since $0 \leq 3$, use $g(x) = (x - 3)^{2} + 1$ \\
$g(0) = (0 - 3)^{2} + 1$ \\
$= 9 + 1$ \\
$= 10$ \\
So $gg(0) = g(10)$ \\
Since $10 > 3$, use $g(x) = 3x - 8$ \\
$g(10) = 3(10) - 8$ \\
$= 30 - 8$ \\
$gg(0) = 22$ \\
(b) Do each part of the function separately \\
Case 1: $x \leq 3$ \\
$(x - 3)^{2} + 1 > 9$ \\
Subtract 1 from both sides: \\
$(x - 3)^{2} > 8$ \\
Square root: $x - 3 > \sqrt{8}$ or $x - 3 < -\sqrt{8}$ \\
$\sqrt{8} = 2\sqrt{2}$ \\
$x > 3 + 2\sqrt{2}$ or $x < 3 - 2\sqrt{2}$ \\
$3 + 2\sqrt{2} = 5.83$, which is not $\leq 3$, so reject \\
$3 - 2\sqrt{2} = 0.17$, which is $\leq 3$, so keep: $x < 3 - 2\sqrt{2}$ \\
Case 2: $x > 3$ \\
$3x - 8 > 9$ \\
Add 8 to both sides: \\
$3x > 17$ \\
Divide by 3: \\
$x > \frac{17}{3}$ \\
$\frac{17}{3} = 5.67$, which is greater than 3, so keep \\
$g(x) > 9$ when $x < 3 - 2\sqrt{2}$ or $x > \frac{17}{3}$ \\
(c) For $x \leq 6$, $h(x) = (x - 6)^{2} + 6$ is always going down as $x$ increases, so every output comes from just one input \\
h is one-to-one, so it has an inverse \\
g is many-to-one: $g(0) = 10$ and $g(6) = 3(6) - 8 = 10$ \\
Two different inputs give the same output, so g has no inverse \\
(d) Find $h^{-1}(x)$. Let $y = (x - 6)^{2} + 6$ \\
Subtract 6 from both sides: \\
$y - 6 = (x - 6)^{2}$ \\
Square root: $x - 6 = \pm \sqrt{y - 6}$ \\
The domain of h is $x \leq 6$, so $x - 6$ is not positive \\
Take the negative root: $x - 6 = -\sqrt{y - 6}$ \\
Add 6: $x = 6 - \sqrt{y - 6}$ \\
Swap the letters: $h^{-1}(x) = 6 - \sqrt{x - 6}$ \\
Solve $h^{-1}(x) = -2$: \\
$6 - \sqrt{x - 6} = -2$ \\
Subtract 6 from both sides: \\
$-\sqrt{x - 6} = -8$ \\
Multiply by $-1$: \\
$\sqrt{x - 6} = 8$ \\
Square both sides: \\
$x - 6 = 64$ \\
Add 6: \\
$x = 70$ \\
(Check: $h(-2) = (-2 - 6)^{2} + 6 = 64 + 6 = 70$)

@q 7
@topic Linear cost model, bakery profit
@marks 7
@question
(a) The cost is a fixed part plus a part proportional to the number of pies: \\
$y = C + Kx$ \\
(b) Pies sell at GBP 5 each, so selling $x$ pies brings in $5x$ \\
Profit $=$ money in $-$ cost \\
650 pies, profit GBP 200: \\
Money in: $650 \times 5 = 3250$ \\
$3250 - (C + 650K) = 200$ \\
Subtract 3250 from both sides: \\
$-(C + 650K) = -3050$ \\
$C + 650K = 3050$ \\
230 pies, loss of GBP 80, so profit is $-80$: \\
Money in: $230 \times 5 = 1150$ \\
$1150 - (C + 230K) = -80$ \\
Subtract 1150 from both sides: \\
$-(C + 230K) = -1230$ \\
$C + 230K = 1230$ \\
Subtract the second equation from the first: \\
$(C + 650K) - (C + 230K) = 3050 - 1230$ \\
$420K = 1820$ \\
Divide by 420: \\
$K = \frac{1820}{420}$ \\
Divide the top and bottom by 140: \\
$K = \frac{13}{3}$ \\
Substitute into $C + 230K = 1230$: \\
$C + 230 \times \frac{13}{3} = 1230$ \\
$C + \frac{2990}{3} = 1230$ \\
Write 1230 as thirds: $1230 = \frac{3690}{3}$ \\
$C = \frac{3690}{3} - \frac{2990}{3}$ \\
$C = \frac{700}{3}$ \\
$y = \frac{13}{3}x + \frac{700}{3}$ \\
(Check with 650 pies: $\frac{13 \times 650}{3} + \frac{700}{3} = \frac{9150}{3} = 3050$) \\
(c) The gradient is $K = \frac{13}{3}$, about GBP 4.33 \\
It is the cost of making each extra pie \\
(d) Let the bakery make $n$ pies \\
Profit $= 5n - \left( \frac{13}{3}n + \frac{700}{3} \right)$ \\
Write $5n$ as thirds: $5n = \frac{15n}{3}$ \\
Profit $= \frac{15n - 13n - 700}{3}$ \\
Profit $= \frac{2n - 700}{3}$ \\
We need a profit, so the profit must be greater than zero: \\
$\frac{2n - 700}{3} > 0$ \\
Multiply by 3: \\
$2n - 700 > 0$ \\
Add 700: \\
$2n > 700$ \\
Divide by 2: \\
$n > 350$ \\
At $n = 350$ the profit is exactly zero, which is not a profit \\
The least whole number of pies is 351 \\
(Check: for 351 pies the profit is $\frac{702 - 700}{3} = \frac{2}{3}$ GBP, which is positive)

@q 8
@topic Infinite GP sum, telescoping logs
@marks 6
@question
(i) The sum starts at $k = 3$ \\
First term, $k = 3$: $6\left( \frac{1}{2} \right)^{3} = 6 \times \frac{1}{8}$ \\
$a = \frac{3}{4}$ \\
Each term is half of the one before, so the common ratio is $r = \frac{1}{2}$ \\
$|r| < 1$, so the series converges \\
Sum to infinity: $S_{\infty} = \frac{a}{1 - r}$ \\
$S_{\infty} = \frac{\frac{3}{4}}{1 - \frac{1}{2}}$ \\
$S_{\infty} = \frac{\frac{3}{4}}{\frac{1}{2}}$ \\
Dividing by $\frac{1}{2}$ is multiplying by 2: \\
$S_{\infty} = \frac{3}{4} \times 2$ \\
$S_{\infty} = \frac{3}{2}$ \\
(ii) Use the log law $\log a + \log b = \log ab$: the sum of logs is the log of the product \\
Write out the first two and last two terms: \\
$\log_{4}\frac{3}{2} + \log_{4}\frac{4}{3} + \ldots + \log_{4}\frac{127}{126} + \log_{4}\frac{128}{127}$ \\
$= \log_{4}\left( \frac{3}{2} \times \frac{4}{3} \times \ldots \times \frac{127}{126} \times \frac{128}{127} \right)$ \\
The numerators are $3 \times 4 \times \ldots \times 127 \times 128$ \\
The denominators are $2 \times 3 \times \ldots \times 126 \times 127$ \\
Every number from 3 to 127 appears on the top and the bottom, so cancels \\
Left with 128 on the top and 2 on the bottom: \\
$= \log_{4}\frac{128}{2}$ \\
$= \log_{4} 64$ \\
$4^{3} = 64$, so $\log_{4} 64 = 3$ \\
So the sum is 3 as required

@q 9
@topic Log-log graph, model d = kV^n
@marks 9
@question
(a) Start with $d = kV^{n}$ and take logs (base 10) of both sides: \\
$\log_{10} d = \log_{10}(kV^{n})$ \\
Use $\log ab = \log a + \log b$: \\
$\log_{10} d = \log_{10} k + \log_{10} V^{n}$ \\
Use $\log a^{n} = n\log a$: \\
$\log_{10} d = \log_{10} k + n\log_{10} V$ \\
Compare with $Y = mX + c$ where $Y = \log_{10} d$ and $X = \log_{10} V$ \\
This is a straight line with gradient $n$ and intercept $\log_{10} k$ \\
Figure 6 is a straight line, so $d = kV^{n}$ is a suitable model \\
(b) Figure 6 passes through $(0, -2)$, so the intercept is $-2$ \\
$\log_{10} k = -2$ \\
$k = 10^{-2}$ \\
$k = 0.01$ \\
Figure 5 has the point $(24, 16)$, so $V = 24$ and $d = 16$ \\
$\log_{10} 16 = -2 + n\log_{10} 24$ \\
Add 2 to both sides: \\
$\log_{10} 16 + 2 = n\log_{10} 24$ \\
Divide by $\log_{10} 24$: \\
$n = \frac{\log_{10} 16 + 2}{\log_{10} 24}$ \\
$\log_{10} 16 = 1.20412$ \\
$\log_{10} 24 = 1.38021$ \\
$n = \frac{1.20412 + 2}{1.38021}$ \\
$n = \frac{3.20412}{1.38021}$ \\
$n = 2.3215$ \\
$n = 2.32$ to 3 significant figures \\
The model is $d = 0.01V^{2.32}$ \\
(c) Reaction distance: change 44 km per hour to metres per second \\
$44 \text{ km h}^{-1} = \frac{44 \times 1000}{3600} \text{ m s}^{-1}$ \\
$= 12.222 \text{ m s}^{-1}$ \\
Distance in 0.8 seconds: $12.222 \times 0.8 = 9.78$ m \\
Braking distance: $d = 0.01 \times 44^{2.32}$ \\
$44^{2.32} = 6498.5$ \\
$d = 0.01 \times 6498.5$ \\
$d = 64.98$ m \\
Total stopping distance: $9.78 + 64.98$ \\
$= 74.76$ m \\
The puddle is 70 m away and $74.76 > 70$ \\
So Sean will not be able to stop before reaching the puddle

@q 10
@topic Vectors, line cuts OB, ratio ON:NB
@marks 6
@question
(a) $AM : MB = 2 : 1$, so $M$ is two thirds of the way from $A$ to $B$ \\
$\text{AM} = \frac{2}{3}\text{AB}$ \\
$\text{AB} = \text{AO} + \text{OB} = -\mathbf{a} + \mathbf{b}$ \\
$\text{AM} = \frac{2}{3}(\mathbf{b} - \mathbf{a})$ \\
$\text{OC} = 2\text{OA} = 2\mathbf{a}$ \\
$\text{CA} = \text{CO} + \text{OA} = -2\mathbf{a} + \mathbf{a} = -\mathbf{a}$ \\
$\text{CM} = \text{CA} + \text{AM}$ \\
$\text{CM} = -\mathbf{a} + \frac{2}{3}(\mathbf{b} - \mathbf{a})$ \\
Expand the bracket: \\
$\text{CM} = -\mathbf{a} + \frac{2}{3}\mathbf{b} - \frac{2}{3}\mathbf{a}$ \\
Collect the $\mathbf{a}$ terms: $-1 - \frac{2}{3} = -\frac{5}{3}$ \\
$\text{CM} = -\frac{5}{3}\mathbf{a} + \frac{2}{3}\mathbf{b}$ \\
(b) $N$ lies on the line $CM$, so $\text{CN} = k\text{CM}$ for some scalar $k$ \\
$\text{ON} = \text{OC} + \text{CN}$ \\
$\text{ON} = 2\mathbf{a} + k\left( -\frac{5}{3}\mathbf{a} + \frac{2}{3}\mathbf{b} \right)$ \\
Expand the bracket: \\
$\text{ON} = 2\mathbf{a} - \frac{5}{3}k\mathbf{a} + \frac{2}{3}k\mathbf{b}$ \\
Collect the $\mathbf{a}$ terms: \\
$\text{ON} = \left( 2 - \frac{5}{3}k \right)\mathbf{a} + \frac{2}{3}k\mathbf{b}$ \\
(c) $N$ lies on $OB$, so $\text{ON}$ is a multiple of $\mathbf{b}$ only \\
The coefficient of $\mathbf{a}$ must be zero: \\
$2 - \frac{5}{3}k = 0$ \\
Add $\frac{5}{3}k$ to both sides: \\
$2 = \frac{5}{3}k$ \\
Multiply by $\frac{3}{5}$: \\
$k = \frac{6}{5}$ \\
Put $k = \frac{6}{5}$ into the $\mathbf{b}$ coefficient: $\frac{2}{3} \times \frac{6}{5} = \frac{12}{15}$ \\
$\text{ON} = \frac{4}{5}\mathbf{b}$ \\
$\text{NB} = \text{OB} - \text{ON}$ \\
$\text{NB} = \mathbf{b} - \frac{4}{5}\mathbf{b}$ \\
$\text{NB} = \frac{1}{5}\mathbf{b}$ \\
$ON : NB = \frac{4}{5} : \frac{1}{5}$ \\
Multiply both sides by 5: \\
$ON : NB = 4 : 1$

@q 11
@topic y = x^x, turning point, iteration
@marks 11
@question
(a) Take natural logs of both sides of $y = x^{x}$: \\
$\ln y = \ln x^{x}$ \\
Use $\ln a^{n} = n\ln a$: \\
$\ln y = x\ln x$ \\
Differentiate both sides with respect to $x$ \\
Left side (chain rule): $\frac{1}{y}\frac{dy}{dx}$ \\
Right side (product rule): $1 \times \ln x + x \times \frac{1}{x}$ \\
$\frac{1}{y}\frac{dy}{dx} = \ln x + 1$ \\
Multiply by $y$: \\
$\frac{dy}{dx} = y(\ln x + 1)$ \\
At a turning point $\frac{dy}{dx} = 0$ \\
$y = x^{x}$ is always positive, so $\ln x + 1 = 0$ \\
Subtract 1: \\
$\ln x = -1$ \\
Take exponentials: \\
$x = e^{-1}$ \\
$x = \frac{1}{e}$ \\
(b) Let $f(x) = x^{x} - 2$. A root is where $x^{x} = 2$ \\
$f(1.5) = 1.5^{1.5} - 2$ \\
$1.5^{1.5} = 1.8371$ \\
$f(1.5) = -0.1629$, which is negative \\
$f(1.6) = 1.6^{1.6} - 2$ \\
$1.6^{1.6} = 2.1213$ \\
$f(1.6) = 0.1213$, which is positive \\
There is a change of sign and $f$ is continuous \\
So the root $\alpha$ lies between 1.5 and 1.6 \\
(c) $x_{n+1} = 2x_{n}^{1 - x_{n}}$ with $x_{1} = 1.5$ \\
$x_{2} = 2 \times 1.5^{1 - 1.5}$ \\
$= 2 \times 1.5^{-0.5}$ \\
$x_{2} = 1.63299$ \\
$x_{3} = 2 \times 1.63299^{1 - 1.63299}$ \\
$x_{3} = 1.46626$ \\
$x_{4} = 2 \times 1.46626^{1 - 1.46626}$ \\
$x_{4} = 1.67314$ \\
$x_{4} = 1.673$ to 3 decimal places \\
(d) Carry on with the iteration: \\
$x_{5} = 1.4144$ \\
$x_{6} = 1.7324$ \\
$x_{7} = 1.3374$ \\
$x_{8} = 1.8131$ \\
$x_{12} = 1.9746$ \\
$x_{13} = 1.0305$ \\
The values jump up and down, and the swings get bigger \\
They get closer and closer to 2 and 1 \\
Check: if $x = 1$ then $2 \times 1^{0} = 2$ \\
Check: if $x = 2$ then $2 \times 2^{-1} = 1$ \\
So $x_{n}$ does not converge to a single value \\
It oscillates (is periodic), alternating between values close to 1 and 2

@q 12
@topic Compound angle proof, cot 2t equation
@marks 7
@question
(a) Write both fractions over the common denominator $3\sin \theta \cos \theta$ \\
Multiply the top and bottom of the first fraction by $\cos \theta$: \\
$\frac{\cos 3\theta}{3\sin \theta} = \frac{\cos 3\theta \cos \theta}{3\sin \theta \cos \theta}$ \\
Multiply the top and bottom of the second fraction by $\sin \theta$: \\
$\frac{\sin 3\theta}{3\cos \theta} = \frac{\sin 3\theta \sin \theta}{3\sin \theta \cos \theta}$ \\
Add the fractions: \\
$\frac{\cos 3\theta}{3\sin \theta} + \frac{\sin 3\theta}{3\cos \theta} = \frac{\cos 3\theta \cos \theta + \sin 3\theta \sin \theta}{3\sin \theta \cos \theta}$ \\
Use $\cos(A - B) = \cos A\cos B + \sin A\sin B$ on the top with $A = 3\theta$, $B = \theta$ \\
Top $= \cos(3\theta - \theta) = \cos 2\theta$ \\
Use $\sin 2\theta = 2\sin \theta \cos \theta$ on the bottom \\
$3\sin \theta \cos \theta = \frac{3}{2}(2\sin \theta \cos \theta)$ \\
$3\sin \theta \cos \theta = \frac{3}{2}\sin 2\theta$ \\
The expression is $\frac{\cos 2\theta}{\frac{3}{2}\sin 2\theta}$ \\
Dividing by $\frac{3}{2}$ is multiplying by $\frac{2}{3}$: \\
$= \frac{2}{3} \times \frac{\cos 2\theta}{\sin 2\theta}$ \\
$\frac{\cos 2\theta}{\sin 2\theta} = \cot 2\theta$ \\
$= \frac{2}{3}\cot 2\theta$ as required \\
(b) From part (a) the equation becomes $\frac{2}{3}\cot 2\theta = 1$ \\
Multiply both sides by $\frac{3}{2}$: \\
$\cot 2\theta = \frac{3}{2}$ \\
Take the reciprocal of both sides: \\
$\tan 2\theta = \frac{2}{3}$ \\
For $0 < \theta < 180$ degrees we need $0 < 2\theta < 360$ degrees \\
$2\theta = \tan^{-1}\frac{2}{3} = 33.690 \text{ degrees}$ \\
Tangent repeats every 180 degrees: \\
$2\theta = 33.690 + 180 = 213.690 \text{ degrees}$ \\
Divide by 2: \\
$\theta = 16.845$ or $\theta = 106.845$ \\
$\theta = 16.8$ or $106.8$ degrees to 1 decimal place \\
(Neither value is a multiple of 90 degrees, so both are allowed)

@q 13
@topic Tank surface area, minimise
@marks 10
@question
(a) Volume of the cylinder: $\pi r^{2}h$ \\
The hemisphere is half a sphere: $\frac{1}{2} \times \frac{4}{3}\pi r^{3} = \frac{2}{3}\pi r^{3}$ \\
Total volume is 5.4: \\
$\pi r^{2}h + \frac{2}{3}\pi r^{3} = 5.4$ \\
Subtract $\frac{2}{3}\pi r^{3}$ from both sides: \\
$\pi r^{2}h = 5.4 - \frac{2}{3}\pi r^{3}$ \\
Divide by $\pi r^{2}$: \\
$h = \frac{5.4 - \frac{2}{3}\pi r^{3}}{\pi r^{2}}$ \\
Exterior surface area has three parts: \\
Closed circular base: $\pi r^{2}$ \\
Curved wall of the cylinder: $2\pi rh$ \\
Hemisphere: $\frac{1}{2} \times 4\pi r^{2} = 2\pi r^{2}$ \\
$A = \pi r^{2} + 2\pi rh + 2\pi r^{2}$ \\
$A = 3\pi r^{2} + 2\pi rh$ \\
Substitute for $h$: \\
$2\pi rh = 2\pi r \times \frac{5.4 - \frac{2}{3}\pi r^{3}}{\pi r^{2}}$ \\
Cancel $\pi r$ from the top and bottom: \\
$2\pi rh = \frac{2\left( 5.4 - \frac{2}{3}\pi r^{3} \right)}{r}$ \\
Multiply out the top: \\
$2\pi rh = \frac{10.8 - \frac{4}{3}\pi r^{3}}{r}$ \\
Divide each term by $r$: \\
$2\pi rh = \frac{10.8}{r} - \frac{4}{3}\pi r^{2}$ \\
$A = 3\pi r^{2} + \frac{10.8}{r} - \frac{4}{3}\pi r^{2}$ \\
Collect the $r^{2}$ terms: $3 - \frac{4}{3} = \frac{5}{3}$ \\
$A = \frac{10.8}{r} + \frac{5}{3}\pi r^{2}$ \\
(b) Write $A = 10.8r^{-1} + \frac{5}{3}\pi r^{2}$ \\
Differentiate: \\
$\frac{dA}{dr} = -10.8r^{-2} + \frac{10}{3}\pi r$ \\
$\frac{dA}{dr} = -\frac{10.8}{r^{2}} + \frac{10}{3}\pi r$ \\
At a minimum $\frac{dA}{dr} = 0$: \\
$-\frac{10.8}{r^{2}} + \frac{10}{3}\pi r = 0$ \\
Add $\frac{10.8}{r^{2}}$ to both sides: \\
$\frac{10}{3}\pi r = \frac{10.8}{r^{2}}$ \\
Multiply both sides by $r^{2}$: \\
$\frac{10}{3}\pi r^{3} = 10.8$ \\
Multiply by 3 and divide by $10\pi$: \\
$r^{3} = \frac{32.4}{10\pi}$ \\
$r^{3} = 1.03132$ \\
Cube root: \\
$r = 1.0103$ \\
$r = 1.01$ m to 3 significant figures \\
Check it is a minimum: $\frac{d^{2}A}{dr^{2}} = \frac{21.6}{r^{3}} + \frac{10}{3}\pi$ \\
For $r > 0$ this is positive, so $r = 1.01$ gives a minimum \\
(c) Substitute $r = 1.01$ into $A = \frac{10.8}{r} + \frac{5}{3}\pi r^{2}$: \\
$\frac{10.8}{1.01} = 10.693$ \\
$r^{2} = 1.0201$ \\
$\frac{5}{3}\pi \times 1.0201 = 5.341$ \\
$A = 10.693 + 5.341$ \\
$A = 16.03$ \\
The minimum surface area is 16 m$^{2}$ to the nearest integer

@q 14
@topic Substitution, differential equation, tree
@marks 15
@question
(a) Let $u = 6 - \sqrt{h}$ \\
Rearrange for $\sqrt{h}$: $\sqrt{h} = 6 - u$ \\
Square both sides: $h = (6 - u)^{2}$ \\
Differentiate with respect to $u$: \\
$\frac{dh}{du} = 2(6 - u) \times (-1)$ \\
$\frac{dh}{du} = -2(6 - u)$ \\
$dh = -2(6 - u) \, du$ \\
Substitute $u$ and $dh$ into the integral: \\
$\int \frac{1}{6 - \sqrt{h}} dh = \int \frac{1}{u} \times \left( -2(6 - u) \right) du$ \\
$= \int \frac{-2(6 - u)}{u} du$ \\
Expand the bracket on the top: \\
$= \int \frac{-12 + 2u}{u} du$ \\
Divide each term on the top by $u$: \\
$= \int \left( -\frac{12}{u} + 2 \right) du$ \\
Integrate: \\
$= -12\ln |u| + 2u + c$ \\
Replace $u$ by $6 - \sqrt{h}$: \\
$= -12\ln |6 - \sqrt{h}| + 2(6 - \sqrt{h}) + c$ \\
Expand the bracket: \\
$= -12\ln |6 - \sqrt{h}| + 12 - 2\sqrt{h} + c$ \\
Combine the constants $12 + c$ into one constant $k$: \\
$= -12\ln |6 - \sqrt{h}| - 2\sqrt{h} + k$ as required \\
(b) Growth stops when $\frac{dh}{dt} = 0$ \\
$\frac{t^{0.25}(6 - \sqrt{h})}{20} = 0$ \\
$t^{0.25}$ is positive for $t > 0$, so $6 - \sqrt{h} = 0$ \\
$\sqrt{h} = 6$ \\
$h = 36$ \\
For $h < 36$ we have $6 - \sqrt{h} > 0$, so $\frac{dh}{dt} > 0$ and the tree grows \\
The height approaches 36 m but never goes past it \\
So the heights of trees are in the range $0 < h < 36$ metres \\
(c) Separate the variables: \\
$\frac{dh}{dt} = \frac{t^{0.25}(6 - \sqrt{h})}{20}$ \\
Divide by $(6 - \sqrt{h})$ and multiply by $dt$: \\
$\frac{1}{6 - \sqrt{h}} dh = \frac{t^{0.25}}{20} dt$ \\
Integrate both sides \\
Left side, from part (a): $-12\ln (6 - \sqrt{h}) - 2\sqrt{h}$ \\
(the modulus is not needed as $6 - \sqrt{h} > 0$) \\
Right side: $\int \frac{t^{0.25}}{20} dt = \frac{1}{20} \times \frac{t^{1.25}}{1.25}$ \\
$= \frac{t^{1.25}}{25}$ \\
Put all the constants together in $k$: \\
$-12\ln (6 - \sqrt{h}) - 2\sqrt{h} + k = \frac{t^{1.25}}{25}$ \\
When $t = 0$, $h = 1$: \\
$-12\ln (6 - \sqrt{1}) - 2\sqrt{1} + k = 0$ \\
$-12\ln 5 - 2 + k = 0$ \\
Add $12\ln 5 + 2$ to both sides: \\
$k = 2 + 12\ln 5$ \\
$k = 21.3133$ \\
Now put in $h = 15$: \\
$-12\ln (6 - \sqrt{15}) - 2\sqrt{15} + 21.3133 = \frac{t^{1.25}}{25}$ \\
$\sqrt{15} = 3.87298$ \\
$6 - \sqrt{15} = 2.12702$ \\
$\ln 2.12702 = 0.75472$ \\
$-12 \times 0.75472 = -9.05664$ \\
$-2\sqrt{15} = -7.74597$ \\
Add the three numbers: $-9.05664 - 7.74597 + 21.3133 = 4.51069$ \\
$\frac{t^{1.25}}{25} = 4.5107$ \\
Multiply by 25: \\
$t^{1.25} = 112.77$ \\
Raise both sides to the power $\frac{1}{1.25} = 0.8$: \\
$t = 112.77^{0.8}$ \\
$t = 43.83$ \\
The tree takes 43.8 years to reach 15 m (3 significant figures)
