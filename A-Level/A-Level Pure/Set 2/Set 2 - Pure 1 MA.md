@paper P1 Mock Set 2

@q 1
@topic Exponential model - weed area
@marks 6
@question
(a) At the start, $t = 0$ \\
Substitute $t = 0$ into $A = 105 - 12e^{0.08t}$: \\
$A = 105 - 12e^{0.08 \times 0}$ \\
$= 105 - 12e^{0}$ \\
Use $e^{0} = 1$: \\
$= 105 - 12(1)$ \\
$= 105 - 12$ \\
$= 93$ \\
The surface area covered by weed at the start is $93 \text{ m}^{2}$ \\
(b) Set $A = 40$: \\
$40 = 105 - 12e^{0.08t}$ \\
Subtract 105 from both sides: \\
$40 - 105 = -12e^{0.08t}$ \\
$-65 = -12e^{0.08t}$ \\
Divide both sides by $-12$: \\
$\frac{65}{12} = e^{0.08t}$ \\
Take natural logs of both sides: \\
$\ln\left(\frac{65}{12}\right) = \ln\left(e^{0.08t}\right)$ \\
Use $\ln(e^{y}) = y$: \\
$\ln\left(\frac{65}{12}\right) = 0.08t$ \\
Divide both sides by 0.08: \\
$t = \frac{\ln\left(\frac{65}{12}\right)}{0.08}$ \\
$= \frac{1.68948}{0.08}$ \\
$= 21.1185$ \\
$t = 21.1$ days (1 dp) \\
(c) Substitute $t = 30$ into the model: \\
$A = 105 - 12e^{0.08 \times 30}$ \\
$= 105 - 12e^{2.4}$ \\
Evaluate $e^{2.4} = 11.02318$: \\
$= 105 - 12 \times 11.02318$ \\
$= 105 - 132.278$ \\
$= -27.3$ (1 dp) \\
The area covered by weed cannot be negative \\
So the model gives an impossible answer at $t = 30$, and Stuart should not use it to predict the area then

@q 2
@topic Binomial expansion of sqrt(1+4x)
@marks 7
@question
(a) Write $\sqrt{1 + 4x} = (1 + 4x)^{\frac{1}{2}}$ \\
Binomial expansion: $(1 + X)^{n} = 1 + nX + \frac{n(n-1)}{2!}X^{2} + \frac{n(n-1)(n-2)}{3!}X^{3} + \ldots$ \\
Here $n = \frac{1}{2}$ and $X = 4x$ \\
Term 1: $1$ \\
Term 2: $nX = \frac{1}{2}(4x) = 2x$ \\
Term 3: $\frac{n(n-1)}{2!}X^{2} = \frac{\frac{1}{2}\left(-\frac{1}{2}\right)}{2}(4x)^{2}$ \\
$\frac{1}{2} \times \left(-\frac{1}{2}\right) = -\frac{1}{4}$ \\
$-\frac{1}{4} \div 2 = -\frac{1}{8}$ \\
$(4x)^{2} = 16x^{2}$ \\
So term 3 $= -\frac{1}{8} \times 16x^{2} = -2x^{2}$ \\
Term 4: $\frac{n(n-1)(n-2)}{3!}X^{3} = \frac{\frac{1}{2}\left(-\frac{1}{2}\right)\left(-\frac{3}{2}\right)}{6}(4x)^{3}$ \\
$\frac{1}{2} \times \left(-\frac{1}{2}\right) \times \left(-\frac{3}{2}\right) = \frac{3}{8}$ \\
$\frac{3}{8} \div 6 = \frac{3}{48} = \frac{1}{16}$ \\
$(4x)^{3} = 64x^{3}$ \\
So term 4 $= \frac{1}{16} \times 64x^{3} = 4x^{3}$ \\
$\sqrt{1 + 4x} = 1 + 2x - 2x^{2} + 4x^{3} + \ldots$ \\
(b) The expansion of $(1 + 4x)^{\frac{1}{2}}$ is only valid when $|4x| < 1$ \\
Divide by 4: $|x| < \frac{1}{4}$ \\
$x = \frac{25}{4} = 6.25$, and $6.25 > \frac{1}{4}$ \\
So $x = \frac{25}{4}$ is outside the valid range, and it should not be used \\
(c) Write 26 as $25 + 1$ and take out a factor of 25: \\
$26 = 25\left(1 + \frac{1}{25}\right)$ \\
$\frac{1}{25} = \frac{4}{100}$, so $26 = 25\left(1 + 4 \times \frac{1}{100}\right)$ \\
Take the square root of both sides: \\
$\sqrt{26} = \sqrt{25} \times \sqrt{1 + 4 \times \frac{1}{100}}$ \\
$\sqrt{26} = 5\sqrt{1 + 4x}$ with $x = \frac{1}{100}$ \\
$x = \frac{1}{100}$ is inside the valid range $|x| < \frac{1}{4}$ \\
So substitute $x = \frac{1}{100}$ into $1 + 2x - 2x^{2} + 4x^{3}$ to get an approximation for $\sqrt{1 + 4x}$ \\
Then multiply the result by 5 to get an approximation for $\sqrt{26}$

@q 3
@topic Periodic sequence and sum
@marks 5
@question
(a) $u_{n+1} = \frac{4}{2 - u_n}$ and $u_1 = 1$ \\
$u_2 = \frac{4}{2 - u_1}$ \\
$= \frac{4}{2 - 1}$ \\
$= \frac{4}{1}$ \\
$= 4$ \\
$u_3 = \frac{4}{2 - u_2}$ \\
$= \frac{4}{2 - 4}$ \\
$= \frac{4}{-2}$ \\
$= -2$ \\
$u_4 = \frac{4}{2 - u_3}$ \\
$= \frac{4}{2 - (-2)}$ \\
$= \frac{4}{4}$ \\
$= 1$ \\
So $u_4 = u_1$ \\
Every term is found from the one before using the same rule, so the sequence now repeats: $1, 4, -2, 1, 4, -2, \ldots$ \\
So the sequence is periodic, with period 3 \\
(b) The sum of one full period: $1 + 4 + (-2) = 3$ \\
Divide the number of terms by the period: $50 \div 3 = 16$ remainder $2$ \\
So $50 = 16 \times 3 + 2$ \\
The first $16 \times 3 = 48$ terms are 16 complete periods: $16 \times 3 = 48$ \\
Since $u_{n+3} = u_{n}$, we have $u_{49} = u_{1} = 1$ and $u_{50} = u_{2} = 4$ \\
$\sum_{n=1}^{50} u_{n} = 16 \times (1 + 4 + (-2)) + u_{49} + u_{50}$ \\
$= 16 \times 3 + 1 + 4$ \\
$= 48 + 5$ \\
$= 53$

@q 4
@topic Algebraic division and integration
@marks 6
@question
(a) Write $4x^{3} - 19x^{2} + 28x - 4 = (Ax + B)(x - 2)^{2} + C$ \\
Expand $(x - 2)^{2} = x^{2} - 4x + 4$ \\
$(Ax + B)(x^{2} - 4x + 4) = Ax^{3} - 4Ax^{2} + 4Ax + Bx^{2} - 4Bx + 4B$ \\
Collect like terms: \\
$= Ax^{3} + (B - 4A)x^{2} + (4A - 4B)x + 4B$ \\
So $4x^{3} - 19x^{2} + 28x - 4 = Ax^{3} + (B - 4A)x^{2} + (4A - 4B)x + 4B + C$ \\
Compare the coefficients of $x^{3}$: \\
$A = 4$ \\
Compare the coefficients of $x^{2}$: \\
$B - 4A = -19$ \\
$B - 4(4) = -19$ \\
$B - 16 = -19$ \\
$B = -3$ \\
Check with the coefficients of $x$: $4A - 4B = 4(4) - 4(-3) = 16 + 12 = 28$ \\
Compare the constant terms: \\
$4B + C = -4$ \\
$4(-3) + C = -4$ \\
$-12 + C = -4$ \\
$C = 8$ \\
So $A = 4$, $B = -3$, $C = 8$ \\
$h(x) = 4x - 3 + \frac{8}{(x - 2)^{2}}$ \\
(b) Write the last term as a power: $\frac{8}{(x-2)^{2}} = 8(x - 2)^{-2}$ \\
$\int h(x) \, dx = \int \left( 4x - 3 + 8(x - 2)^{-2} \right) dx$ \\
Integrate each term: \\
$\int 4x \, dx = 2x^{2}$ \\
$\int -3 \, dx = -3x$ \\
$\int 8(x - 2)^{-2} \, dx = 8 \times \frac{(x - 2)^{-1}}{-1} = -8(x - 2)^{-1} = -\frac{8}{x - 2}$ \\
Add a constant of integration: \\
$\int h(x) \, dx = 2x^{2} - 3x - \frac{8}{x - 2} + c$

@q 5
@topic Vectors - magnitude and angle
@marks 6
@question
(a) $\text{OA} = -2\mathbf{i} + 3\mathbf{j}$ and $\text{OB} = 3\mathbf{i} + p\mathbf{j}$ \\
$\text{AB} = \text{OB} - \text{OA}$ \\
$= (3\mathbf{i} + p\mathbf{j}) - (-2\mathbf{i} + 3\mathbf{j})$ \\
$= (3 + 2)\mathbf{i} + (p - 3)\mathbf{j}$ \\
$= 5\mathbf{i} + (p - 3)\mathbf{j}$ \\
Use Pythagoras for the magnitude: \\
$|\text{AB}|^{2} = 5^{2} + (p - 3)^{2}$ \\
Given $|\text{AB}| = 5\sqrt{2}$, so $|\text{AB}|^{2} = (5\sqrt{2})^{2} = 25 \times 2 = 50$ \\
$25 + (p - 3)^{2} = 50$ \\
Subtract 25 from both sides: \\
$(p - 3)^{2} = 25$ \\
Take the square root of both sides (positive and negative): \\
$p - 3 = 5$ or $p - 3 = -5$ \\
$p = 8$ or $p = -2$ \\
(b) $\text{OC} = q\mathbf{i} + 7\mathbf{j}$ \\
$\text{AC} = \text{OC} - \text{OA}$ \\
$= (q\mathbf{i} + 7\mathbf{j}) - (-2\mathbf{i} + 3\mathbf{j})$ \\
$= (q + 2)\mathbf{i} + (7 - 3)\mathbf{j}$ \\
$= (q + 2)\mathbf{i} + 4\mathbf{j}$ \\
The angle between $\text{AC}$ and $\mathbf{i}$ is $\frac{\pi}{3}$, so in the right-angled triangle formed by the components: \\
$\tan\left(\frac{\pi}{3}\right) = \frac{\text{vertical}}{\text{horizontal}} = \frac{4}{q + 2}$ \\
Use $\tan\left(\frac{\pi}{3}\right) = \sqrt{3}$: \\
$\sqrt{3} = \frac{4}{q + 2}$ \\
Multiply both sides by $(q + 2)$: \\
$\sqrt{3}(q + 2) = 4$ \\
Divide both sides by $\sqrt{3}$: \\
$q + 2 = \frac{4}{\sqrt{3}}$ \\
Subtract 2 from both sides: \\
$q = \frac{4}{\sqrt{3}} - 2$ \\
Rationalise the denominator, multiplying top and bottom by $\sqrt{3}$: \\
$\frac{4}{\sqrt{3}} = \frac{4\sqrt{3}}{\sqrt{3} \times \sqrt{3}} = \frac{4\sqrt{3}}{3}$ \\
$q = \frac{4\sqrt{3}}{3} - 2$

@q 6
@topic Tan addition formula proof
@marks 6
@question
(a) Let $t = \tan \theta$ to keep the working short \\
Use $\tan(A + B) = \frac{\tan A + \tan B}{1 - \tan A \tan B}$ with $A = B = \theta$: \\
$\tan 2\theta = \frac{t + t}{1 - t \times t}$ \\
$\tan 2\theta = \frac{2t}{1 - t^{2}}$ \\
Write $3\theta = 2\theta + \theta$ and use the formula again: \\
$\tan 3\theta = \tan(2\theta + \theta) = \frac{\tan 2\theta + \tan \theta}{1 - \tan 2\theta \tan \theta}$ \\
Substitute $\tan 2\theta = \frac{2t}{1 - t^{2}}$ and $\tan \theta = t$: \\
$\tan 3\theta = \frac{\frac{2t}{1 - t^{2}} + t}{1 - \frac{2t}{1 - t^{2}} \times t}$ \\
Multiply the top and the bottom by $(1 - t^{2})$ to clear the small fractions \\
Top: $\left( \frac{2t}{1 - t^{2}} + t \right)(1 - t^{2}) = 2t + t(1 - t^{2})$ \\
$= 2t + t - t^{3}$ \\
$= 3t - t^{3}$ \\
Bottom: $\left( 1 - \frac{2t^{2}}{1 - t^{2}} \right)(1 - t^{2}) = (1 - t^{2}) - 2t^{2}$ \\
$= 1 - t^{2} - 2t^{2}$ \\
$= 1 - 3t^{2}$ \\
$\tan 3\theta = \frac{3t - t^{3}}{1 - 3t^{2}}$ \\
Replace $t$ by $\tan \theta$: \\
$\tan 3\theta = \frac{3\tan \theta - \tan^{3} \theta}{1 - 3\tan^{2} \theta}$ as required \\
(b) Use the result in (a) with $\tan \beta = \sqrt{6}$ \\
$\tan 3\beta = \frac{3\tan \beta - \tan^{3} \beta}{1 - 3\tan^{2} \beta} = \frac{3\sqrt{6} - (\sqrt{6})^{3}}{1 - 3(\sqrt{6})^{2}}$ \\
$(\sqrt{6})^{2} = 6$ \\
$(\sqrt{6})^{3} = (\sqrt{6})^{2} \times \sqrt{6} = 6\sqrt{6}$ \\
Numerator: $3\sqrt{6} - 6\sqrt{6} = -3\sqrt{6}$ \\
Denominator: $1 - 3(6) = 1 - 18 = -17$ \\
$\tan 3\beta = \frac{-3\sqrt{6}}{-17}$ \\
The negatives cancel: \\
$= \frac{3\sqrt{6}}{17}$ \\
$= \frac{3}{17}\sqrt{6}$ \\
So $k = \frac{3}{17}$

@q 7
@topic Exponential growth model - squirrels
@marks 9
@question
(a) The line $l$ passes through $(0, 2)$ and $(20, 2.4)$ \\
Gradient $= \frac{2.4 - 2}{20 - 0}$ \\
$= \frac{0.4}{20}$ \\
$= 0.02$ \\
The line crosses the vertical axis at $(0, 2)$, so the intercept is 2 \\
$\log_{10} P = 0.02t + 2$ \\
(b) At the start, $t = 0$: \\
$\log_{10} P = 0.02(0) + 2 = 2$ \\
Undo the logarithm: $P = 10^{2}$ \\
$P = 100$ \\
The initial number of red squirrels was 100 \\
(c) Start with $P = ab^{t}$ \\
Take $\log_{10}$ of both sides: \\
$\log_{10} P = \log_{10}(ab^{t})$ \\
Use $\log(xy) = \log x + \log y$: \\
$\log_{10} P = \log_{10} a + \log_{10}(b^{t})$ \\
Use $\log(x^{n}) = n\log x$: \\
$\log_{10} P = \log_{10} a + t\log_{10} b$ \\
Compare with $\log_{10} P = 2 + 0.02t$ \\
Constant terms: $\log_{10} a = 2$, so $a = 10^{2} = 100$ \\
Coefficients of $t$: $\log_{10} b = 0.02$ \\
$b = 10^{0.02}$ \\
$b = 1.0471\ldots$ \\
$b = 1.047$ (4 sf) \\
So the model is $P = 100 \times 1.047^{t}$ \\
(d)(i) 1st June 2019 is $2019 - 1996 = 23$ years after 1996, so $t = 23$ \\
$P = 100 \times 1.047^{23}$ \\
$1.047^{23} = 2.8759$ \\
$P = 100 \times 2.8759$ \\
$P = 287.6$ \\
$P = 288$ (nearest whole number) \\
The model predicts 288 squirrels, but 198 were found \\
The prediction is nearly 100 too high, so the model is not valid on 1st June 2019 \\
(d)(ii) The model gives unlimited exponential growth \\
In a real wood, food and territory are limited (a carrying capacity), so the population stops growing so fast once it gets large \\
Predators, disease or competition could also slow the growth

@q 8
@topic Trig equation - cos and sin degrees
@marks 8
@question
(a) $y = 5\cos(x - 30)$ has minimum value $-5$, when $\cos(x - 30) = -1$ \\
$\cos \theta = -1$ when $\theta = 180$ degrees (the first positive angle) \\
$x - 30 = 180$ \\
Add 30 to both sides: \\
$x = 210$ \\
The next possible value, $x - 30 = -180$, gives $x = -150$, which is not positive \\
So $P = (210, -5)$ \\
(b) $5\cos(x - 30) = 4\sin x$ \\
Use $\cos(A - B) = \cos A \cos B + \sin A \sin B$: \\
$5(\cos x \cos 30 + \sin x \sin 30) = 4\sin x$ \\
Expand the bracket: \\
$5\cos x \cos 30 + 5\sin x \sin 30 = 4\sin x$ \\
Get the $\sin x$ terms on one side (subtract $5\sin x \sin 30$ from both sides): \\
$5\cos x \cos 30 = 4\sin x - 5\sin x \sin 30$ \\
Factorise the right-hand side: \\
$5\cos x \cos 30 = \sin x(4 - 5\sin 30)$ \\
Divide both sides by $\cos x$, using $\frac{\sin x}{\cos x} = \tan x$: \\
$5\cos 30 = \tan x(4 - 5\sin 30)$ \\
Divide both sides by $(4 - 5\sin 30)$: \\
$\tan x = \frac{5\cos 30}{4 - 5\sin 30}$ \\
Substitute $\cos 30 = \frac{\sqrt{3}}{2}$ and $\sin 30 = \frac{1}{2}$: \\
$\tan x = \frac{5 \times \frac{\sqrt{3}}{2}}{4 - 5 \times \frac{1}{2}}$ \\
Top: $5 \times \frac{\sqrt{3}}{2} = \frac{5\sqrt{3}}{2}$ \\
Bottom: $4 - \frac{5}{2} = \frac{8}{2} - \frac{5}{2} = \frac{3}{2}$ \\
$\tan x = \frac{5\sqrt{3}}{2} \div \frac{3}{2}$ \\
$= \frac{5\sqrt{3}}{2} \times \frac{2}{3}$ \\
$= \frac{5\sqrt{3}}{3}$ \\
$= 2.8868$ \\
Principal value: $x = \tan^{-1}(2.8868) = 70.9$ degrees \\
$\tan$ repeats every 180 degrees: \\
$x = 70.9 + 180 = 250.9$ degrees \\
The next value, $70.9 + 360 = 430.9$, is outside the range $0 \le x < 360$ \\
$x = 70.9$ degrees or $x = 250.9$ degrees \\
(c) Let $X = 2x$ \\
The equation $5\cos(2x - 30) = 4\sin 2x$ becomes $5\cos(X - 30) = 4\sin X$ \\
This is the equation from (b) with $X$ in place of $x$ \\
The range $0 \le x < 3600$ becomes $0 \le X < 7200$ \\
Every 360 degrees of $X$ gives 2 roots (as found in (b)) \\
$7200 \div 360 = 20$ cycles \\
Number of roots for $X$: $20 \times 2 = 40$ \\
Each value of $X$ gives exactly one value of $x = \frac{X}{2}$ \\
So there are 40 roots \\
(Equivalently, doubling the angle gives 4 roots in each 360 degrees of $x$, and $0 \le x < 3600$ is 10 cycles, so $10 \times 4 = 40$.)

@q 9
@topic Trapezium rule and estimation
@marks 8
@question
(a) Four strips between $x = -0.5$ and $x = 1.5$: \\
$h = \frac{1.5 - (-0.5)}{4} = \frac{2}{4} = 0.5$ \\
The $x$ values are $-0.5, 0, 0.5, 1, 1.5$ \\
Use $y = 2^{x^{2}} - x$ at each $x$ value: \\
$x = -0.5$: $y = 2^{0.25} - (-0.5) = 1.1892 + 0.5 = 1.689$ \\
$x = 0$: $y = 2^{0} - 0 = 1$ \\
$x = 0.5$: $y = 2^{0.25} - 0.5 = 1.1892 - 0.5 = 0.689$ \\
$x = 1$: $y = 2^{1} - 1 = 1$ \\
$x = 1.5$: $y = 2^{2.25} - 1.5 = 4.7568 - 1.5 = 3.257$ \\
Trapezium rule: area $\approx \frac{h}{2}\{ y_{0} + y_{4} + 2(y_{1} + y_{2} + y_{3}) \}$ \\
$= \frac{0.5}{2}\{ 1.689 + 3.257 + 2(1 + 0.689 + 1) \}$ \\
First and last: $1.689 + 3.257 = 4.946$ \\
Middle three: $1 + 0.689 + 1 = 2.689$ \\
Double the middle three: $2 \times 2.689 = 5.378$ \\
$= 0.25 \times \{ 4.946 + 5.378 \}$ \\
$= 0.25 \times 10.324$ \\
$= 2.581$ \\
Area of $R \approx 2.58$ (2 dp) \\
(b) The curve is convex (it bends upwards) \\
So the top of each trapezium, a straight line joining two points on the curve, lies above the curve \\
Each trapezium is larger than the area under the curve beneath it \\
So the trapezium rule gives an overestimate of the true area of $R$ \\
(c) Use $2^{x^{2}+1} = 2^{x^{2}} \times 2^{1} = 2 \times 2^{x^{2}}$ \\
$2^{x^{2}+1} + 2x = 2 \times 2^{x^{2}} + 2x$ \\
Write $2x = -2x + 4x$: \\
$= 2 \times 2^{x^{2}} - 2x + 4x$ \\
Factorise the first two terms: \\
$= 2\left( 2^{x^{2}} - x \right) + 4x$ \\
So $\int_{-0.5}^{1.5} \left( 2^{x^{2}+1} + 2x \right) dx = 2\int_{-0.5}^{1.5} \left( 2^{x^{2}} - x \right) dx + \int_{-0.5}^{1.5} 4x \, dx$ \\
The first integral is the area of $R$, which is $2.58$ from (a) \\
The second integral: $\int_{-0.5}^{1.5} 4x \, dx = \left[ 2x^{2} \right]_{-0.5}^{1.5}$ \\
$= 2(1.5)^{2} - 2(-0.5)^{2}$ \\
$= 2(2.25) - 2(0.25)$ \\
$= 4.5 - 0.5$ \\
$= 4$ \\
So the integral is $2 \times 2.58 + 4$ \\
$= 5.16 + 4$ \\
$= 9.16$

@q 10
@topic Modulus graph and line intersection
@marks 8
@question
(a) $y = |2x - 9| + 3$ \\
The vertex is where the expression inside the modulus is zero: \\
$2x - 9 = 0$ \\
$2x = 9$ \\
$x = \frac{9}{2}$ \\
At this point $y = |0| + 3 = 3$ \\
The vertex is $\left( \frac{9}{2}, 3 \right)$ \\
$y$-intercept: put $x = 0$: \\
$y = |2(0) - 9| + 3$ \\
$= |-9| + 3$ \\
$= 9 + 3$ \\
$= 12$ \\
The graph crosses the $y$-axis at $(0, 12)$ \\
$x$-intercepts: put $y = 0$: \\
$0 = |2x - 9| + 3$ \\
$|2x - 9| = -3$ \\
A modulus can never be negative, so there are no $x$-intercepts \\
For $x < \frac{9}{2}$: $2x - 9 < 0$, so $|2x - 9| = 9 - 2x$ \\
$y = 9 - 2x + 3 = 12 - 2x$, a line with gradient $-2$ \\
For $x \ge \frac{9}{2}$: $|2x - 9| = 2x - 9$ \\
$y = 2x - 9 + 3 = 2x - 6$, a line with gradient $2$ \\
Sketch: a V shape with its vertex at $\left( \frac{9}{2}, 3 \right)$, crossing the $y$-axis at $(0, 12)$ and lying above the $x$-axis \\
(b) $3x + 1 = |2x - 9| + 3$ \\
Case 1: $x < \frac{9}{2}$, where $|2x - 9| = 9 - 2x$ \\
$3x + 1 = 9 - 2x + 3$ \\
$3x + 1 = 12 - 2x$ \\
Add $2x$ to both sides: $5x + 1 = 12$ \\
Subtract 1 from both sides: $5x = 11$ \\
$x = \frac{11}{5}$ \\
$\frac{11}{5} = 2.2 < \frac{9}{2}$, so this solution is valid \\
Case 2: $x \ge \frac{9}{2}$, where $|2x - 9| = 2x - 9$ \\
$3x + 1 = 2x - 9 + 3$ \\
$3x + 1 = 2x - 6$ \\
Subtract $2x$ from both sides: $x + 1 = -6$ \\
Subtract 1 from both sides: $x = -7$ \\
$-7$ is not $\ge \frac{9}{2}$, so this solution is rejected \\
The only solution is $x = \frac{11}{5}$ \\
(c) The line $l$ is $y = kx + 1$, so it passes through $(0, 1)$, which is below the graph \\
Lower limit for $k$: the left arm of the graph is $y = 12 - 2x$ with gradient $-2$ \\
If $k = -2$, the line $y = -2x + 1$ is parallel to this arm \\
Check: $-2x + 1 = 12 - 2x$ gives $1 = 12$, which is impossible, so they never meet \\
If $k < -2$, the line is steeper than the left arm and would cross it further to the left \\
So $k \ge -2$ \\
Upper limit for $k$: as $k$ increases, the line first touches the graph at the vertex $\left( \frac{9}{2}, 3 \right)$ \\
Substitute the vertex into $y = kx + 1$: \\
$3 = \frac{9}{2}k + 1$ \\
Subtract 1 from both sides: $2 = \frac{9}{2}k$ \\
Multiply both sides by $\frac{2}{9}$: $k = \frac{4}{9}$ \\
When $k = \frac{4}{9}$ the line passes through the vertex, so it does meet the graph \\
For $k < \frac{4}{9}$ the line passes below the vertex and misses both arms \\
So the range of values of $k$ is $-2 \le k < \frac{4}{9}$

@q 11
@topic Function - inverse, range, decreasing
@marks 6
@question
(a) $f^{-1}(a) = \frac{5}{3}$ means that $f\left( \frac{5}{3} \right) = a$ \\
$a = f\left( \frac{5}{3} \right) = \frac{2 + 3\left( \frac{5}{3} \right)}{\frac{5}{3}}$ \\
Numerator: $2 + 3 \times \frac{5}{3} = 2 + 5 = 7$ \\
$a = \frac{7}{\frac{5}{3}}$ \\
Dividing by a fraction is the same as multiplying by its reciprocal: \\
$a = 7 \times \frac{3}{5}$ \\
$a = \frac{21}{5}$ \\
(b) Split the fraction into two: \\
$f(x) = \frac{2 + 3x}{x} = \frac{2}{x} + \frac{3x}{x}$ \\
$f(x) = \frac{2}{x} + 3$ \\
Since $x > 0$, $\frac{2}{x} > 0$ \\
Add 3 to both sides: $\frac{2}{x} + 3 > 3$ \\
So $f(x) > 3$ for all $x > 0$ \\
$3 > \frac{3}{2}$, so $f(x) > \frac{3}{2}$ for all $x > 0$ \\
So there are no values of $x$ for which $f(x) < \frac{3}{2}$ \\
(c) Write $f(x) = 3 + 2x^{-1}$ \\
Differentiate: $f'(x) = 0 + 2(-1)x^{-2}$ \\
$f'(x) = -2x^{-2}$ \\
$f'(x) = -\frac{2}{x^{2}}$ \\
Since $x > 0$, $x^{2} > 0$, so $\frac{2}{x^{2}} > 0$ \\
So $-\frac{2}{x^{2}} < 0$, and $f'(x) < 0$ for all $x > 0$ \\
Since $f'(x) < 0$ for all $x$ in the domain, $f$ is a decreasing function

@q 12
@topic Algebraic integration with logs
@marks 5
@question
Write the numerator in terms of $(x + 3)$: \\
$4x + 9 = 4x + 12 - 3 = 4(x + 3) - 3$ \\
$\frac{4x + 9}{x + 3} = \frac{4(x + 3) - 3}{x + 3}$ \\
Split into two fractions: \\
$= \frac{4(x + 3)}{x + 3} - \frac{3}{x + 3}$ \\
Cancel the common factor in the first fraction: \\
$= 4 - \frac{3}{x + 3}$ \\
$\int_{1}^{5} \frac{4x + 9}{x + 3} \, dx = \int_{1}^{5} \left( 4 - \frac{3}{x + 3} \right) dx$ \\
Integrate each term ($\int \frac{1}{x + 3} dx = \ln(x + 3)$): \\
$= \left[ 4x - 3\ln(x + 3) \right]_{1}^{5}$ \\
Substitute the upper limit $x = 5$: $4(5) - 3\ln(5 + 3) = 20 - 3\ln 8$ \\
Substitute the lower limit $x = 1$: $4(1) - 3\ln(1 + 3) = 4 - 3\ln 4$ \\
Subtract: \\
$= (20 - 3\ln 8) - (4 - 3\ln 4)$ \\
Remove the brackets: \\
$= 20 - 3\ln 8 - 4 + 3\ln 4$ \\
$= 16 - 3\ln 8 + 3\ln 4$ \\
Factorise the log terms: \\
$= 16 - 3(\ln 8 - \ln 4)$ \\
Use $\ln a - \ln b = \ln \frac{a}{b}$: \\
$= 16 - 3\ln\left( \frac{8}{4} \right)$ \\
$= 16 - 3\ln 2$ \\
Now write this in the form $a + \ln b$ \\
Use $n\ln x = \ln(x^{n})$: $-3\ln 2 = \ln(2^{-3})$ \\
$2^{-3} = \frac{1}{2^{3}} = \frac{1}{8}$ \\
$-3\ln 2 = \ln\left( \frac{1}{8} \right)$ \\
$= 16 + \ln\left( \frac{1}{8} \right)$ \\
So $a = 16$ and $b = \frac{1}{8}$

@q 13
@topic Related rates - leaking cone
@marks 11
@question
(a) The water forms a smaller cone, similar to the container, so the ratio of radius to height is the same: \\
$\frac{r}{h} = \frac{2.5}{4} = \frac{5}{8}$ \\
Multiply both sides by $h$: \\
$r = \frac{5}{8}h$ \\
Substitute into $V = \frac{1}{3}\pi r^{2} h$: \\
$V = \frac{1}{3}\pi \left( \frac{5}{8}h \right)^{2} h$ \\
$\left( \frac{5}{8}h \right)^{2} = \frac{25}{64}h^{2}$ \\
$V = \frac{1}{3}\pi \times \frac{25}{64}h^{2} \times h$ \\
$V = \frac{25}{192}\pi h^{3}$ \\
Differentiate with respect to $h$: \\
$\frac{dV}{dh} = 3 \times \frac{25}{192}\pi h^{2}$ \\
$\frac{dV}{dh} = \frac{75}{192}\pi h^{2}$ \\
Water leaks out, so the volume decreases: $\frac{dV}{dt} = -\frac{\pi}{512}\sqrt{h}$ \\
Chain rule: $\frac{dV}{dt} = \frac{dV}{dh} \times \frac{dh}{dt}$ \\
$-\frac{\pi}{512}\sqrt{h} = \frac{75}{192}\pi h^{2} \times \frac{dh}{dt}$ \\
Divide both sides by $\frac{75}{192}\pi h^{2}$: \\
$\frac{dh}{dt} = -\frac{\pi}{512}\sqrt{h} \times \frac{192}{75\pi h^{2}}$ \\
Cancel $\pi$: \\
$= -\frac{192}{512 \times 75} \times \frac{\sqrt{h}}{h^{2}}$ \\
$512 \times 75 = 38400$, and $\frac{192}{38400} = \frac{1}{200}$ \\
Use $\frac{h^{\frac{1}{2}}}{h^{2}} = h^{\frac{1}{2} - 2} = h^{-\frac{3}{2}}$: \\
$\frac{dh}{dt} = -\frac{1}{200}h^{-\frac{3}{2}}$ \\
Multiply both sides by $h^{\frac{3}{2}}$: \\
$h^{\frac{3}{2}}\frac{dh}{dt} = -\frac{1}{200}$ as required \\
(b) Separate the variables: \\
$h^{\frac{3}{2}} \, dh = -\frac{1}{200} \, dt$ \\
Integrate both sides: \\
$\int h^{\frac{3}{2}} \, dh = \int -\frac{1}{200} \, dt$ \\
$\frac{h^{\frac{5}{2}}}{\frac{5}{2}} = -\frac{1}{200}t + c$ \\
$\frac{2}{5}h^{\frac{5}{2}} = -\frac{1}{200}t + c$ \\
The container is initially full, so $h = 4$ when $t = 0$: \\
$\frac{2}{5}(4)^{\frac{5}{2}} = -\frac{1}{200}(0) + c$ \\
$4^{\frac{5}{2}} = \left( \sqrt{4} \right)^{5} = 2^{5} = 32$ \\
$\frac{2}{5} \times 32 = c$ \\
$c = \frac{64}{5}$ \\
$\frac{2}{5}h^{\frac{5}{2}} = -\frac{1}{200}t + \frac{64}{5}$ \\
(c) The container is empty when $h = 0$: \\
$0 = -\frac{1}{200}t + \frac{64}{5}$ \\
Add $\frac{1}{200}t$ to both sides: \\
$\frac{1}{200}t = \frac{64}{5}$ \\
Multiply both sides by 200: \\
$t = 200 \times \frac{64}{5}$ \\
$= 40 \times 64$ \\
$= 2560$ seconds \\
Convert to minutes: $2560 \div 60 = 42.67$ minutes \\
$= 42$ minutes 40 seconds \\
The actual time is about 43 minutes, which is 2580 seconds \\
The model is only 20 seconds out, less than 1 percent \\
So the model is very close to the real time and is suitable

@q 14
@topic Parametric curve and circle radius
@marks 9
@question
(a) $x = 2\sin t$ and $y = 3\sin 2t$ \\
Use the double angle formula $\sin 2t = 2\sin t \cos t$: \\
$y = 3(2\sin t \cos t)$ \\
$y = 6\sin t \cos t$ \\
From $x = 2\sin t$: $\sin t = \frac{x}{2}$ \\
Substitute this for $\sin t$: \\
$y = 6 \times \frac{x}{2} \times \cos t$ \\
$y = 3x\cos t$ \\
Square both sides: \\
$y^{2} = 9x^{2}\cos^{2} t$ \\
Use $\cos^{2} t = 1 - \sin^{2} t$: \\
$y^{2} = 9x^{2}(1 - \sin^{2} t)$ \\
Substitute $\sin t = \frac{x}{2}$: \\
$y^{2} = 9x^{2}\left( 1 - \frac{x^{2}}{4} \right)$ \\
Write $1 = \frac{4}{4}$ inside the bracket: \\
$y^{2} = 9x^{2}\left( \frac{4 - x^{2}}{4} \right)$ \\
$y^{2} = \frac{9}{4}x^{2}(4 - x^{2})$ \\
So $k = \frac{9}{4}$ \\
(b) The circle $C_{2}$ has its centre at $O$, and touches $C_{1}$ at the four points furthest from $O$ \\
A point $(x, y)$ is at distance $r$ from $O$ when $r^{2} = x^{2} + y^{2}$ \\
Substitute $y^{2} = \frac{9}{4}x^{2}(4 - x^{2})$: \\
$r^{2} = x^{2} + \frac{9}{4}x^{2}(4 - x^{2})$ \\
Expand the bracket: \\
$r^{2} = x^{2} + 9x^{2} - \frac{9}{4}x^{4}$ \\
$r^{2} = 10x^{2} - \frac{9}{4}x^{4}$ \\
The circle touches where $r^{2}$ is a maximum, so differentiate and set equal to zero: \\
$\frac{d(r^{2})}{dx} = 20x - 9x^{3}$ \\
$20x - 9x^{3} = 0$ \\
Factorise: \\
$x(20 - 9x^{2}) = 0$ \\
$x = 0$ is the origin, where $r = 0$, so use $20 - 9x^{2} = 0$: \\
$9x^{2} = 20$ \\
$x^{2} = \frac{20}{9}$ \\
Check it is a maximum: $\frac{d^{2}(r^{2})}{dx^{2}} = 20 - 27x^{2} = 20 - 27 \times \frac{20}{9} = 20 - 60 = -40 < 0$ \\
Substitute $x^{2} = \frac{20}{9}$ into $r^{2} = 10x^{2} - \frac{9}{4}x^{4}$: \\
$r^{2} = 10 \times \frac{20}{9} - \frac{9}{4}\left( \frac{20}{9} \right)^{2}$ \\
$\left( \frac{20}{9} \right)^{2} = \frac{400}{81}$ \\
$r^{2} = \frac{200}{9} - \frac{9}{4} \times \frac{400}{81}$ \\
$\frac{9}{4} \times \frac{400}{81} = \frac{3600}{324} = \frac{100}{9}$ \\
$r^{2} = \frac{200}{9} - \frac{100}{9}$ \\
$r^{2} = \frac{100}{9}$ \\
Take the positive square root: \\
$r = \frac{10}{3}$
