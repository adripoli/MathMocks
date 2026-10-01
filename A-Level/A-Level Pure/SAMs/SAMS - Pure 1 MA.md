@paper P1 SAMs

@q 1
@topic Stationary point, second derivative
@marks 7
@question
(a)(i) $y = 3x^{4} - 8x^{3} - 3$ \\
Differentiate each term using $x^{n} \to nx^{n-1}$: \\
$3x^{4} \to 12x^{3}$ \\
$-8x^{3} \to -24x^{2}$ \\
$-3 \to 0$ \\
$\frac{dy}{dx} = 12x^{3} - 24x^{2}$ \\
(ii) Differentiate again: \\
$12x^{3} \to 36x^{2}$ \\
$-24x^{2} \to -48x$ \\
$\frac{d^{2}y}{dx^{2}} = 36x^{2} - 48x$ \\
(b) Substitute $x = 2$ into $\frac{dy}{dx}$: \\
$\frac{dy}{dx} = 12(2)^{3} - 24(2)^{2}$ \\
$= 12(8) - 24(4)$ \\
$= 96 - 96$ \\
$= 0$ \\
Since $\frac{dy}{dx} = 0$ when $x = 2$, $C$ has a stationary point when $x = 2$ \\
(c) Substitute $x = 2$ into $\frac{d^{2}y}{dx^{2}}$: \\
$\frac{d^{2}y}{dx^{2}} = 36(2)^{2} - 48(2)$ \\
$= 36(4) - 96$ \\
$= 144 - 96$ \\
$= 48$ \\
Since $\frac{d^{2}y}{dx^{2}} = 48 > 0$, the stationary point is a minimum

@q 2
@topic Sectors, arc length and area
@marks 5
@question
(a) Arc length $s = r\theta$ \\
Sector $COD$ has arc $CD = 3$, radius $OD$ and angle $0.4$: \\
$3 = OD \times 0.4$ \\
Divide both sides by 0.4: \\
$OD = \frac{3}{0.4}$ \\
$OD = 7.5$ cm \\
(b) $AOD$ is a straight line, so the angles on it add up to $\pi$ \\
The angle $COD$ is 0.4 and the rest of the angle is the sector $AOB$: \\
Angle $AOB = \pi - 0.4$ \\
$= 2.7416$ radians \\
The radius of sector $AOB$ is $OA$: \\
$OA = AD - OD = 12 - 7.5 = 4.5$ cm \\
Area of a sector $= \frac{1}{2}r^{2}\theta$ \\
$= \frac{1}{2}(4.5)^{2}(\pi - 0.4)$ \\
$= \frac{1}{2}(20.25)(2.7416)$ \\
$= 10.125 \times 2.7416$ \\
$= 27.76$ \\
Area of $AOB = 27.8$ cm$^2$ (3 sf)

@q 3
@topic Circle, centre and range of k
@marks 4
@question
(a) $x^{2} + y^{2} - 4x + 10y = k$ \\
Group the $x$ terms and the $y$ terms: \\
$(x^{2} - 4x) + (y^{2} + 10y) = k$ \\
Complete the square for each: \\
$x^{2} - 4x = (x - 2)^{2} - 4$ \\
$y^{2} + 10y = (y + 5)^{2} - 25$ \\
$(x - 2)^{2} - 4 + (y + 5)^{2} - 25 = k$ \\
Add 4 and 25 to both sides: \\
$(x - 2)^{2} + (y + 5)^{2} = k + 4 + 25$ \\
$(x - 2)^{2} + (y + 5)^{2} = k + 29$ \\
The centre of $C$ is $(2, -5)$ \\
(b) The right-hand side is $r^{2}$, so it must be positive for the circle to exist: \\
$k + 29 > 0$ \\
Subtract 29 from both sides: \\
$k > -29$

@q 4
@topic Definite integral with ln, find a
@marks 4
@question
Divide each term of the numerator by $t$: \\
$\frac{t + 1}{t} = \frac{t}{t} + \frac{1}{t} = 1 + \frac{1}{t}$ \\
$\int_{a}^{2a} \frac{t + 1}{t} \, dt = \int_{a}^{2a} \left( 1 + \frac{1}{t} \right) dt$ \\
Integrate each term: \\
$\int 1 \, dt = t$ \\
$\int \frac{1}{t} \, dt = \ln t$ \\
$= \left[ t + \ln t \right]_{a}^{2a}$ \\
Substitute the upper limit $t = 2a$ and subtract the lower limit $t = a$: \\
$= (2a + \ln 2a) - (a + \ln a)$ \\
Remove the brackets: \\
$= 2a + \ln 2a - a - \ln a$ \\
$= a + \ln 2a - \ln a$ \\
Use $\ln x - \ln y = \ln\frac{x}{y}$: \\
$= a + \ln\frac{2a}{a}$ \\
$= a + \ln 2$ \\
Set this equal to $\ln 7$: \\
$a + \ln 2 = \ln 7$ \\
Subtract $\ln 2$ from both sides: \\
$a = \ln 7 - \ln 2$ \\
$a = \ln\frac{7}{2}$ \\
So $a = \ln k$ with $k = \frac{7}{2}$

@q 5
@topic Parametric to Cartesian equation
@marks 3
@question
$x = 2t - 1$ and $y = 4t - 7 + \frac{3}{t}$ \\
Rearrange the first equation for $t$: \\
$x + 1 = 2t$ \\
$t = \frac{x + 1}{2}$ \\
Substitute into $y$: \\
$y = 4\left( \frac{x + 1}{2} \right) - 7 + \frac{3}{\frac{x + 1}{2}}$ \\
$4 \times \frac{x + 1}{2} = 2(x + 1) = 2x + 2$ \\
$\frac{3}{\frac{x + 1}{2}} = 3 \times \frac{2}{x + 1} = \frac{6}{x + 1}$ \\
$y = 2x + 2 - 7 + \frac{6}{x + 1}$ \\
$y = 2x - 5 + \frac{6}{x + 1}$ \\
Write $2x - 5$ over the denominator $(x + 1)$: \\
$y = \frac{(2x - 5)(x + 1)}{x + 1} + \frac{6}{x + 1}$ \\
$y = \frac{(2x - 5)(x + 1) + 6}{x + 1}$ \\
Expand the bracket: $(2x - 5)(x + 1) = 2x^{2} + 2x - 5x - 5 = 2x^{2} - 3x - 5$ \\
$y = \frac{2x^{2} - 3x - 5 + 6}{x + 1}$ \\
$y = \frac{2x^{2} - 3x + 1}{x + 1}$ \\
So $a = -3$ and $b = 1$

@q 6
@topic Linear vs exponential, oil field
@marks 7
@question
(a)(i) Model A is a straight line through $(0, 16000)$ and $(4, 9000)$ \\
Gradient $= \frac{9000 - 16000}{4 - 0} = \frac{-7000}{4} = -1750$ \\
$V = 16000 - 1750t$ \\
At $t = 3$: \\
$V = 16000 - 1750(3)$ \\
$= 16000 - 5250$ \\
$= 10750$ barrels \\
(ii) Model A gives $V = 0$ when $16000 - 1750t = 0$, so $t = \frac{16000}{1750} = \frac{64}{7} = 9.14$ years \\
After this it gives negative values, which is impossible, as the daily volume extracted cannot be negative \\
(b)(i) Choose an exponential model $V = Ae^{kt}$ \\
At the start, $t = 0$ and $V = 16000$: \\
$16000 = Ae^{0}$ \\
$A = 16000$ \\
At $t = 4$, $V = 9000$: \\
$9000 = 16000e^{4k}$ \\
Divide both sides by 16000: \\
$e^{4k} = \frac{9}{16}$ \\
Take natural logs of both sides: \\
$4k = \ln\frac{9}{16}$ \\
$k = \frac{1}{4}\ln\frac{9}{16}$ \\
$= \frac{-0.5754}{4}$ \\
$= -0.144$ (3 sf) \\
$V = 16000e^{-0.144t}$ \\
(ii) At $t = 3$: \\
$V = 16000e^{-0.144 \times 3}$ \\
$= 16000e^{-0.432}$ \\
$= 16000 \times 0.6491$ \\
$= 10385$ \\
$V = 10400$ barrels (3 sf)

@q 7
@topic Vectors, angle in a triangle
@marks 5
@question
$\text{AB} = 2\mathbf{i} + 3\mathbf{j} + \mathbf{k}$ and $\text{BC} = \mathbf{i} - 9\mathbf{j} + 3\mathbf{k}$ \\
Find $\text{AC}$ by adding: \\
$\text{AC} = \text{AB} + \text{BC}$ \\
$= (2 + 1)\mathbf{i} + (3 - 9)\mathbf{j} + (1 + 3)\mathbf{k}$ \\
$= 3\mathbf{i} - 6\mathbf{j} + 4\mathbf{k}$ \\
Find the three lengths using 3D Pythagoras: \\
$|\text{AB}| = \sqrt{2^{2} + 3^{2} + 1^{2}} = \sqrt{4 + 9 + 1} = \sqrt{14}$ \\
$|\text{BC}| = \sqrt{1^{2} + (-9)^{2} + 3^{2}} = \sqrt{1 + 81 + 9} = \sqrt{91}$ \\
$|\text{AC}| = \sqrt{3^{2} + (-6)^{2} + 4^{2}} = \sqrt{9 + 36 + 16} = \sqrt{61}$ \\
Use the cosine rule for the angle at $A$, opposite the side $BC$: \\
$\cos BAC = \frac{|AB|^{2} + |AC|^{2} - |BC|^{2}}{2|AB||AC|}$ \\
$= \frac{14 + 61 - 91}{2\sqrt{14}\sqrt{61}}$ \\
$= \frac{-16}{2\sqrt{854}}$ \\
$= \frac{-8}{\sqrt{854}}$ \\
$= -0.2738$ \\
$\text{angle } BAC = \cos^{-1}(-0.2738)$ \\
$= 105.9$ degrees (1 dp)

@q 8
@topic Root in interval, Newton-Raphson
@marks 6
@question
(a) $f(x) = \ln(2x - 5) + 2x^{2} - 30$ \\
$f(3.5) = \ln(2 \times 3.5 - 5) + 2(3.5)^{2} - 30$ \\
$= \ln 2 + 2(12.25) - 30$ \\
$= 0.693 + 24.5 - 30$ \\
$= -4.807$ \\
$f(4) = \ln(2 \times 4 - 5) + 2(4)^{2} - 30$ \\
$= \ln 3 + 32 - 30$ \\
$= 1.099 + 2$ \\
$= 3.099$ \\
$f(3.5)$ is negative and $f(4)$ is positive, and $f$ is continuous for $x > 2.5$ \\
So there is a change of sign, and a root $\alpha$ lies in the interval $[3.5, 4]$ \\
(b) Newton-Raphson: $x_{1} = x_{0} - \frac{f(x_{0})}{f'(x_{0})}$, with $x_{0} = 4$ \\
$x_{1} = 4 - \frac{3.099}{16.67}$ \\
$= 4 - 0.1859$ \\
$= 3.8141$ \\
$x_{1} = 3.81$ (3 sf) \\
(c) Differentiate: \\
$f'(x) = \frac{2}{2x - 5} + 4x$ \\
For $x > 2.5$: $2x - 5 > 0$, so $\frac{2}{2x - 5} > 0$ \\
Also $4x > 0$ \\
So $f'(x) > 0$ for all $x$ in the domain \\
So $f$ is always increasing, and it can cross the $x$-axis at most once \\
A root exists in $[3.5, 4]$, so $\alpha$ is the only root of $f(x) = 0$ \\
(Or sketch $y = \ln(2x - 5)$ and $y = 30 - 2x^{2}$, which meet only once.)

@q 9
@topic Trig identity proof, tan + cot
@marks 5
@question
(a) Write $\tan \theta$ and $\cot \theta$ in terms of $\sin$ and $\cos$: \\
$\tan \theta + \cot \theta = \frac{\sin \theta}{\cos \theta} + \frac{\cos \theta}{\sin \theta}$ \\
Use the common denominator $\sin \theta \cos \theta$: \\
$= \frac{\sin \theta \times \sin \theta}{\cos \theta \sin \theta} + \frac{\cos \theta \times \cos \theta}{\sin \theta \cos \theta}$ \\
$= \frac{\sin^{2} \theta + \cos^{2} \theta}{\sin \theta \cos \theta}$ \\
Use $\sin^{2} \theta + \cos^{2} \theta = 1$: \\
$= \frac{1}{\sin \theta \cos \theta}$ \\
Use $\sin 2\theta = 2\sin \theta \cos \theta$, so $\sin \theta \cos \theta = \frac{1}{2}\sin 2\theta$: \\
$= \frac{1}{\frac{1}{2}\sin 2\theta}$ \\
$= \frac{2}{\sin 2\theta}$ \\
Use $\cosec x = \frac{1}{\sin x}$: \\
$= 2\cosec 2\theta$ as required \\
(b) $\tan \theta + \cot \theta = 1$ \\
Use (a): $2\cosec 2\theta = 1$ \\
$\cosec 2\theta = \frac{1}{2}$ \\
$\frac{1}{\sin 2\theta} = \frac{1}{2}$ \\
$\sin 2\theta = 2$ \\
But $-1 \le \sin 2\theta \le 1$, so $\sin 2\theta = 2$ is impossible \\
So there are no real solutions

@q 10
@topic First principles, derivative of sin
@marks 5
@question
Let $y = \sin \theta$ \\
Take a point on the curve with $\theta$ coordinate $\theta + h$, close to $\theta$ \\
The gradient of the chord between the two points is: \\
$\frac{\sin(\theta + h) - \sin \theta}{(\theta + h) - \theta} = \frac{\sin(\theta + h) - \sin \theta}{h}$ \\
Use $\sin(A + B) = \sin A \cos B + \cos A \sin B$ with $A = \theta$ and $B = h$: \\
$\sin(\theta + h) = \sin \theta \cos h + \cos \theta \sin h$ \\
$\frac{\sin(\theta + h) - \sin \theta}{h} = \frac{\sin \theta \cos h + \cos \theta \sin h - \sin \theta}{h}$ \\
Group the terms in $\sin \theta$: \\
$= \frac{\cos \theta \sin h + \sin \theta(\cos h - 1)}{h}$ \\
Split into two fractions: \\
$= \cos \theta \times \frac{\sin h}{h} + \sin \theta \times \frac{\cos h - 1}{h}$ \\
As $h \to 0$: $\frac{\sin h}{h} \to 1$ and $\frac{\cos h - 1}{h} \to 0$ \\
$\lim_{h \to 0} \frac{\sin(\theta + h) - \sin \theta}{h} = \cos \theta \times 1 + \sin \theta \times 0$ \\
$= \cos \theta$ \\
As $h \to 0$ the gradient of the chord tends to the gradient of the curve \\
So $\frac{d}{d\theta}(\sin \theta) = \cos \theta$ as required

@q 11
@topic Quadratic model, arrow trajectory
@marks 9
@question
(a) The arrow hits the ground when $H = 0$: \\
$1.8 + 0.4d - 0.002d^{2} = 0$ \\
Use the quadratic formula with $a = -0.002$, $b = 0.4$, $c = 1.8$: \\
$d = \frac{-b \pm \sqrt{b^{2} - 4ac}}{2a}$ \\
$= \frac{-0.4 \pm \sqrt{(0.4)^{2} - 4(-0.002)(1.8)}}{2(-0.002)}$ \\
$(0.4)^{2} = 0.16$ and $4(-0.002)(1.8) = -0.0144$ \\
$= \frac{-0.4 \pm \sqrt{0.16 + 0.0144}}{-0.004}$ \\
$= \frac{-0.4 \pm \sqrt{0.1744}}{-0.004}$ \\
$= \frac{-0.4 \pm 0.4176}{-0.004}$ \\
$d = \frac{-0.4 + 0.4176}{-0.004} = -4.4$ or $d = \frac{-0.4 - 0.4176}{-0.004} = 204.4$ \\
$d \ge 0$, so reject $d = -4.4$ \\
The arrow travels 204 m (3 sf) \\
(b) When $d = 0$, $H = 1.8$ \\
So the constant 1.8 is the initial height of the arrow above the ground, when it is shot \\
(c) Take out a factor of $-0.002$ from the terms in $d$: \\
$1.8 + 0.4d - 0.002d^{2} = -0.002(d^{2} - 200d) + 1.8$ \\
Complete the square: $d^{2} - 200d = (d - 100)^{2} - 10000$ \\
$= -0.002\left( (d - 100)^{2} - 10000 \right) + 1.8$ \\
Expand the outer bracket: \\
$= -0.002(d - 100)^{2} + 0.002 \times 10000 + 1.8$ \\
$= -0.002(d - 100)^{2} + 20 + 1.8$ \\
$= 21.8 - 0.002(d - 100)^{2}$ \\
So $A = 21.8$, $B = 0.002$ and $C = 100$ \\
(d)(i) The new formula is 0.3 higher than the old one: $2.1 = 1.8 + 0.3$ \\
$H = 2.1 + 0.4d - 0.002d^{2} = 0.3 + \left( 21.8 - 0.002(d - 100)^{2} \right)$ \\
$H = 22.1 - 0.002(d - 100)^{2}$ \\
$(d - 100)^{2} \ge 0$, so $0.002(d - 100)^{2} \ge 0$ \\
The greatest value of $H$ is 22.1, when $(d - 100)^{2} = 0$ \\
Maximum height is 22.1 m \\
(ii) The maximum occurs when $d - 100 = 0$ \\
$d = 100$ m

@q 12
@topic Log graph, N = aT^b
@marks 9
@question
(a) $N = aT^{b}$ \\
Take $\log_{10}$ of both sides: \\
$\log_{10} N = \log_{10}(aT^{b})$ \\
Use $\log(xy) = \log x + \log y$: \\
$\log_{10} N = \log_{10} a + \log_{10}(T^{b})$ \\
Use $\log(x^{n}) = n\log x$: \\
$\log_{10} N = \log_{10} a + b\log_{10} T$ \\
$\log_{10} N = b\log_{10} T + \log_{10} a$ \\
Compare with $\log_{10} N = m\log_{10} T + c$: \\
$m = b$ and $c = \log_{10} a$ \\
(b) Use the line of best fit in Figure 3 \\
The intercept on the vertical axis is $c = 1.8$ \\
$\log_{10} a = 1.8$ \\
$a = 10^{1.8} = 63$ \\
The gradient is $m = b = 2.3$ \\
$N = 63T^{2.3}$ \\
At $T = 3$: \\
$N = 63 \times 3^{2.3}$ \\
$= 63 \times 12.51$ \\
$= 788$ \\
About 800 microbes (3 sf) \\
(Or read the graph at $\log_{10} 3 = 0.48$, where $\log_{10} N \approx 2.9$, so $N = 10^{2.9} \approx 800$.) \\
(c) $N = 1\,000\,000$ means $\log_{10} N = 6$ \\
The line of best fit only covers values of $\log_{10} N$ up to about 4.5, so $\log_{10} N = 6$ is well beyond the data \\
This is extrapolation, and the model may not still hold beyond the data, so the estimate would not be reliable \\
(d) When $T = 1$: $N = a \times 1^{b} = a$ \\
So $a$ is the number of microbes present 1 day after the start of the experiment

@q 13
@topic Parametric normal and intersection
@marks 13
@question
(a) $x = 2\cos t$ and $y = \sqrt{3}\cos 2t$ \\
$\frac{dx}{dt} = -2\sin t$ \\
$\frac{dy}{dt} = -2\sqrt{3}\sin 2t$ \\
$\frac{dy}{dx} = \frac{dy}{dt} \div \frac{dx}{dt}$ \\
$= \frac{-2\sqrt{3}\sin 2t}{-2\sin t}$ \\
$= \frac{\sqrt{3}\sin 2t}{\sin t}$ \\
Use $\sin 2t = 2\sin t \cos t$: \\
$= \frac{\sqrt{3} \times 2\sin t \cos t}{\sin t}$ \\
$= 2\sqrt{3}\cos t$ \\
(b) At $t = \frac{2\pi}{3}$: \\
$\frac{dy}{dx} = 2\sqrt{3}\cos\frac{2\pi}{3}$ \\
$= 2\sqrt{3} \times \left( -\frac{1}{2} \right)$ \\
$= -\sqrt{3}$ \\
The normal has gradient $-1 \div \frac{dy}{dx}$: \\
$m = -1 \div (-\sqrt{3}) = \frac{1}{\sqrt{3}}$ \\
Coordinates of $P$: \\
$x = 2\cos\frac{2\pi}{3} = 2 \times \left( -\frac{1}{2} \right) = -1$ \\
$y = \sqrt{3}\cos\frac{4\pi}{3} = \sqrt{3} \times \left( -\frac{1}{2} \right) = -\frac{\sqrt{3}}{2}$ \\
$P = \left( -1, -\frac{\sqrt{3}}{2} \right)$ \\
Equation of the normal through $P$: \\
$y - \left( -\frac{\sqrt{3}}{2} \right) = \frac{1}{\sqrt{3}}(x - (-1))$ \\
$y + \frac{\sqrt{3}}{2} = \frac{1}{\sqrt{3}}(x + 1)$ \\
Multiply both sides by $\sqrt{3}$: \\
$\sqrt{3}y + \frac{\sqrt{3} \times \sqrt{3}}{2} = x + 1$ \\
$\sqrt{3}y + \frac{3}{2} = x + 1$ \\
Multiply every term by 2: \\
$2\sqrt{3}y + 3 = 2x + 2$ \\
Move everything to the right-hand side: \\
$0 = 2x + 2 - 2\sqrt{3}y - 3$ \\
$0 = 2x - 2\sqrt{3}y - 1$ \\
$2x - 2\sqrt{3}y - 1 = 0$ as required \\
(c) Substitute $x = 2\cos t$ and $y = \sqrt{3}\cos 2t$ into $2x - 2\sqrt{3}y - 1 = 0$: \\
$2(2\cos t) - 2\sqrt{3}(\sqrt{3}\cos 2t) - 1 = 0$ \\
$4\cos t - 6\cos 2t - 1 = 0$ \\
Use $\cos 2t = 2\cos^{2} t - 1$: \\
$4\cos t - 6(2\cos^{2} t - 1) - 1 = 0$ \\
Expand the bracket: \\
$4\cos t - 12\cos^{2} t + 6 - 1 = 0$ \\
$-12\cos^{2} t + 4\cos t + 5 = 0$ \\
Multiply by $-1$: \\
$12\cos^{2} t - 4\cos t - 5 = 0$ \\
Factorise: \\
$(6\cos t - 5)(2\cos t + 1) = 0$ \\
$\cos t = \frac{5}{6}$ or $\cos t = -\frac{1}{2}$ \\
$\cos t = -\frac{1}{2}$ is the point $P$, where $t = \frac{2\pi}{3}$, so at $Q$: \\
$\cos t = \frac{5}{6}$ \\
$x = 2\cos t = 2 \times \frac{5}{6} = \frac{5}{3}$ \\
$\cos 2t = 2\cos^{2} t - 1 = 2\left( \frac{5}{6} \right)^{2} - 1 = 2 \times \frac{25}{36} - 1 = \frac{50}{36} - \frac{36}{36} = \frac{14}{36} = \frac{7}{18}$ \\
$y = \sqrt{3}\cos 2t = \sqrt{3} \times \frac{7}{18} = \frac{7\sqrt{3}}{18}$ \\
$Q = \left( \frac{5}{3}, \frac{7\sqrt{3}}{18} \right)$

@q 14
@topic Trapezium rule, exact area with ln
@marks 10
@question
(a) The $x$ values go up in steps of 0.5, so $h = 0.5$ \\
Trapezium rule: area $\approx \frac{h}{2}\{ y_{0} + y_{4} + 2(y_{1} + y_{2} + y_{3}) \}$ \\
$= \frac{0.5}{2}\{ 3 + 2.2958 + 2(2.3041 + 1.9242 + 1.9089) \}$ \\
First and last: $3 + 2.2958 = 5.2958$ \\
Middle three: $2.3041 + 1.9242 + 1.9089 = 6.1372$ \\
Double them: $2 \times 6.1372 = 12.2744$ \\
$= 0.25 \times \{ 5.2958 + 12.2744 \}$ \\
$= 0.25 \times 17.5702$ \\
$= 4.39255$ \\
Area of $S \approx 4.393$ (3 dp) \\
(b) Use more strips (more trapezia), which makes each strip narrower \\
(c) Area of $S = \int_{1}^{3} \left( \frac{x^{2}\ln x}{3} - 2x + 5 \right) dx$ \\
First find $\int x^{2}\ln x \, dx$ by parts, with $u = \ln x$ and $\frac{dv}{dx} = x^{2}$ \\
$\frac{du}{dx} = \frac{1}{x}$ and $v = \frac{x^{3}}{3}$ \\
$\int x^{2}\ln x \, dx = \frac{x^{3}}{3}\ln x - \int \frac{x^{3}}{3} \times \frac{1}{x} \, dx$ \\
$= \frac{x^{3}}{3}\ln x - \int \frac{x^{2}}{3} \, dx$ \\
$= \frac{x^{3}}{3}\ln x - \frac{x^{3}}{9}$ \\
Divide by 3 to get $\int \frac{x^{2}\ln x}{3} \, dx$: \\
$\int \frac{x^{2}\ln x}{3} \, dx = \frac{x^{3}}{9}\ln x - \frac{x^{3}}{27}$ \\
$\int (-2x + 5) \, dx = -x^{2} + 5x$ \\
$\int \left( \frac{x^{2}\ln x}{3} - 2x + 5 \right) dx = \frac{x^{3}}{9}\ln x - \frac{x^{3}}{27} - x^{2} + 5x$ \\
Upper limit $x = 3$: \\
$\frac{27}{9}\ln 3 - \frac{27}{27} - 9 + 15$ \\
$= 3\ln 3 - 1 - 9 + 15$ \\
$= 3\ln 3 + 5$ \\
Lower limit $x = 1$: \\
$\frac{1}{9}\ln 1 - \frac{1}{27} - 1 + 5$ \\
$\ln 1 = 0$, so $= -\frac{1}{27} + 4$ \\
$= \frac{-1 + 108}{27}$ \\
$= \frac{107}{27}$ \\
Subtract: \\
Area $= 3\ln 3 + 5 - \frac{107}{27}$ \\
$= 3\ln 3 + \frac{135}{27} - \frac{107}{27}$ \\
$= 3\ln 3 + \frac{28}{27}$ \\
Use $3\ln 3 = \ln(3^{3}) = \ln 27$: \\
Area of $S = \frac{28}{27} + \ln 27$ \\
So $a = 28$, $b = 27$ and $c = 27$

@q 15
@topic Turning points, transformations
@marks 8
@question
(a) $f(x) = \frac{4\sin 2x}{e^{\sqrt{2}x - 1}}$ \\
Use the quotient rule with $u = 4\sin 2x$ and $v = e^{\sqrt{2}x - 1}$ \\
$u' = 8\cos 2x$ \\
$v' = \sqrt{2}e^{\sqrt{2}x - 1}$ \\
$f'(x) = \frac{u'v - uv'}{v^{2}}$ \\
$= \frac{8\cos 2x \times e^{\sqrt{2}x - 1} - 4\sin 2x \times \sqrt{2}e^{\sqrt{2}x - 1}}{\left( e^{\sqrt{2}x - 1} \right)^{2}}$ \\
Divide the top and the bottom by $e^{\sqrt{2}x - 1}$: \\
$f'(x) = \frac{8\cos 2x - 4\sqrt{2}\sin 2x}{e^{\sqrt{2}x - 1}}$ \\
At a turning point, $f'(x) = 0$ \\
The denominator is never zero, so the numerator is zero: \\
$8\cos 2x - 4\sqrt{2}\sin 2x = 0$ \\
$8\cos 2x = 4\sqrt{2}\sin 2x$ \\
Divide both sides by $4\sqrt{2}\cos 2x$: \\
$\frac{8}{4\sqrt{2}} = \frac{\sin 2x}{\cos 2x}$ \\
$\frac{2}{\sqrt{2}} = \tan 2x$ \\
$\frac{2}{\sqrt{2}} = \frac{2\sqrt{2}}{2} = \sqrt{2}$ \\
$\tan 2x = \sqrt{2}$ as required \\
(b)(i) For $y = f(2x)$, replace $x$ by $2x$ in the result of (a): the turning points are where $\tan 4x = \sqrt{2}$ \\
For $f(x)$ the first solution of $\tan 2x = \sqrt{2}$ gives the maximum $P$ and the second gives the minimum $Q$ \\
So for $f(2x)$ the minimum is at the second solution of $\tan 4x = \sqrt{2}$ \\
$\tan^{-1}\sqrt{2} = 0.9553$ \\
First solution: $4x = 0.9553$ \\
Second solution: $4x = 0.9553 + \pi$ \\
$4x = 4.0969$ \\
Divide both sides by 4: \\
$x = 1.02$ (3 sf) \\
(ii) For $y = 3 - 2f(x)$, the $-2$ turns the graph upside down and stretches it \\
So the maximum $P$ of $f$ becomes the minimum of $y = 3 - 2f(x)$, at the same $x$ \\
This is the first solution of $\tan 2x = \sqrt{2}$: \\
$2x = 0.9553$ \\
$x = \frac{0.9553}{2}$ \\
$= 0.478$ (3 sf)
