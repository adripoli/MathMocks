@paper P1 Shadow October 2021

@q 1
@topic Factor theorem, find a
@marks 3
@question
$(x - 2)$ is a factor of $f(x)$, so by the factor theorem $f(2) = 0$ \\
$f(2) = a(2)^{3} + 3(2)^{2} - 5a(2) + 8$ \\
Evaluate the powers: $2^{3} = 8$ and $2^{2} = 4$ \\
$f(2) = 8a + 12 - 10a + 8$ \\
Collect the $a$ terms: $8a - 10a = -2a$ \\
Collect the numbers: $12 + 8 = 20$ \\
$f(2) = 20 - 2a$ \\
Set this equal to zero: \\
$20 - 2a = 0$ \\
Add $2a$ to both sides: \\
$20 = 2a$ \\
Divide by 2: \\
$a = 10$ \\
(Check: $f(x) = 10x^{3} + 3x^{2} - 50x + 8$ and $f(2) = 80 + 12 - 100 + 8 = 0$)

@q 2
@topic Completing the square, P and Q
@marks 4
@question
(a) Halve the coefficient of $x$: $\frac{-6}{2} = -3$ \\
$x^{2} - 6x = (x - 3)^{2} - 9$ \\
$f(x) = (x - 3)^{2} - 9 + 7$ \\
$f(x) = (x - 3)^{2} - 2$ \\
So $a = -3$ and $b = -2$ \\
(b)(i) $P$ is where the curve meets the $y$-axis, so $x = 0$ \\
$f(0) = 0 - 0 + 7 = 7$ \\
$P = (0, 7)$ \\
(ii) $(x - 3)^{2}$ is never negative, so the smallest value of $f(x)$ is when $x - 3 = 0$ \\
That is $x = 3$, and then $f(3) = 0 - 2 = -2$ \\
$Q = (3, -2)$

@q 3
@topic Recurrence relation, find k and u3
@marks 6
@question
(a) $u_{1} = 7$ \\
$u_{2} = k - 3 - \frac{42}{u_{1}}$ \\
$u_{2} = k - 3 - \frac{42}{7}$ \\
$u_{2} = k - 3 - 6$ \\
$u_{2} = k - 9$ \\
$u_{3} = k - 3 - \frac{42}{u_{2}}$ \\
$u_{3} = k - 3 - \frac{42}{k - 9}$ \\
Substitute into $(6u_{1} - 2) + 5u_{2} - u_{3} = 0$: \\
$6u_{1} - 2 = 6(7) - 2 = 40$ \\
$5u_{2} = 5(k - 9) = 5k - 45$ \\
$-u_{3} = -k + 3 + \frac{42}{k - 9}$ \\
$40 + 5k - 45 - k + 3 + \frac{42}{k - 9} = 0$ \\
Collect the $k$ terms: $5k - k = 4k$ \\
Collect the numbers: $40 - 45 + 3 = -2$ \\
$4k - 2 + \frac{42}{k - 9} = 0$ \\
Multiply every term by $(k - 9)$, which is not zero: \\
$(4k - 2)(k - 9) + 42 = 0$ \\
Expand the bracket: \\
$4k^{2} - 36k - 2k + 18 + 42 = 0$ \\
Collect like terms: \\
$4k^{2} - 38k + 60 = 0$ as required \\
(b) Divide every term by 2: \\
$2k^{2} - 19k + 30 = 0$ \\
Factorise: \\
$(k - 2)(2k - 15) = 0$ \\
$k = 2$ or $k = \frac{15}{2}$ \\
$k$ is an integer, and $\frac{15}{2} = 7.5$ is not \\
So $k = 2$ \\
(c) $u_{2} = k - 9 = 2 - 9 = -7$ \\
$u_{3} = k - 3 - \frac{42}{u_{2}}$ \\
$u_{3} = 2 - 3 - \frac{42}{-7}$ \\
$u_{3} = -1 + 6$ \\
$u_{3} = 5$ \\
(Check: $(6 \times 7 - 2) + 5(-7) - 5 = 40 - 35 - 5 = 0$)

@q 4
@topic Turning point, iteration, change of sign
@marks 9
@question
(a) Differentiate $f(x) = x^{2} + \ln (3x^{2} - 6x + 7)$ \\
$x^{2} \to 2x$ \\
Use the rule $\frac{d}{dx}\ln u = \frac{1}{u}\frac{du}{dx}$ with $u = 3x^{2} - 6x + 7$ \\
$\frac{du}{dx} = 6x - 6$ \\
$f'(x) = 2x + \frac{6x - 6}{3x^{2} - 6x + 7}$ \\
At the turning point $f'(x) = 0$: \\
$2x + \frac{6x - 6}{3x^{2} - 6x + 7} = 0$ \\
Multiply every term by $(3x^{2} - 6x + 7)$, which is never zero: \\
$2x(3x^{2} - 6x + 7) + 6x - 6 = 0$ \\
Expand the bracket: \\
$6x^{3} - 12x^{2} + 14x + 6x - 6 = 0$ \\
Collect the $x$ terms: \\
$6x^{3} - 12x^{2} + 20x - 6 = 0$ \\
Divide every term by 2: \\
$3x^{3} - 6x^{2} + 10x - 3 = 0$ as required \\
(b)(i) $x_{2} = \frac{1}{10}\left( 3 + 6x_{1}^{2} - 3x_{1}^{3} \right)$ with $x_{1} = 0.3$ \\
$6(0.3)^{2} = 6 \times 0.09 = 0.54$ \\
$3(0.3)^{3} = 3 \times 0.027 = 0.081$ \\
$x_{2} = \frac{1}{10}(3 + 0.54 - 0.081)$ \\
$x_{2} = \frac{1}{10}(3.459)$ \\
$x_{2} = 0.3459$ \\
(ii) Use the ANS key to keep every digit: \\
$x_{3} = 0.35937$ \\
$x_{4} = 0.36357$ \\
$x_{4} = 0.3636$ to 4 decimal places \\
(c) Let $h(x) = 3x^{3} - 6x^{2} + 10x - 3$ \\
To show $\alpha = 0.366$ to 3 decimal places, use the interval $[0.3655, 0.3665]$ \\
$h(0.3655) = 3(0.3655)^{3} - 6(0.3655)^{2} + 10(0.3655) - 3$ \\
$h(0.3655) = -0.0000598$, which is negative \\
$h(0.3665) = 3(0.3665)^{3} - 6(0.3665)^{2} + 10(0.3665) - 3$ \\
$h(0.3665) = 0.00675$, which is positive \\
$h(x)$ is continuous and changes sign on the interval \\
So there is a root between 0.3655 and 0.3665 \\
So $\alpha = 0.366$ to 3 decimal places

@q 5
@topic Geometric sequence, profit model
@marks 6
@question
(a) The profit increases by 9% each year, so multiply by 1.09 each year \\
Year 1: GBP 30 000 \\
Year 2: $30000 \times 1.09 = 32700$ \\
Year 3: $32700 \times 1.09 = 35643$ \\
So the profit for Year 3 is GBP 35 643 as required \\
(b) The profit in Year $n$ is $u_{n} = 30000 \times 1.09^{n-1}$ \\
We need $30000 \times 1.09^{n-1} > 180000$ \\
Divide both sides by 30 000: \\
$1.09^{n-1} > 6$ \\
Take natural logs of both sides: \\
$(n - 1)\ln 1.09 > \ln 6$ \\
Divide by $\ln 1.09$, which is positive: \\
$n - 1 > \frac{\ln 6}{\ln 1.09}$ \\
$n - 1 > \frac{1.79176}{0.086178}$ \\
$n - 1 > 20.79$ \\
Add 1: \\
$n > 21.79$ \\
The first whole number is $n = 22$, so Year 22 \\
(Check: Year 21 is GBP 168 132, which is less than 180 000; Year 22 is GBP 183 264, which is more) \\
(c) Sum of a geometric series: $S_{n} = \frac{a(r^{n} - 1)}{r - 1}$ with $a = 30000$, $r = 1.09$, $n = 30$ \\
$S_{30} = \frac{30000(1.09^{30} - 1)}{1.09 - 1}$ \\
$1.09^{30} = 13.2677$ \\
$1.09^{30} - 1 = 12.2677$ \\
Denominator: $1.09 - 1 = 0.09$ \\
$S_{30} = \frac{30000 \times 12.2677}{0.09}$ \\
$S_{30} = 4089226$ \\
To the nearest GBP 10 000 the total profit is GBP 4 090 000

@q 6
@topic Vectors in a triangle, cos ABC = 0
@marks 5
@question
(a) $\text{AC} = \text{AB} + \text{BC}$ \\
$\text{AC} = (-2\mathbf{i} - 6\mathbf{j} - 3\mathbf{k}) + (6\mathbf{i} - 3\mathbf{j} + 2\mathbf{k})$ \\
$\mathbf{i}$ terms: $-2 + 6 = 4$ \\
$\mathbf{j}$ terms: $-6 - 3 = -9$ \\
$\mathbf{k}$ terms: $-3 + 2 = -1$ \\
$\text{AC} = 4\mathbf{i} - 9\mathbf{j} - \mathbf{k}$ \\
(b) Find the squares of the three side lengths \\
$AB^{2} = (-2)^{2} + (-6)^{2} + (-3)^{2}$ \\
$AB^{2} = 4 + 36 + 9 = 49$ \\
$AB = 7$ \\
$BC^{2} = 6^{2} + (-3)^{2} + 2^{2}$ \\
$BC^{2} = 36 + 9 + 4 = 49$ \\
$BC = 7$ \\
$AC^{2} = 4^{2} + (-9)^{2} + (-1)^{2}$ \\
$AC^{2} = 16 + 81 + 1 = 98$ \\
Use the cosine rule in triangle $ABC$ for the angle at $B$: \\
$AC^{2} = AB^{2} + BC^{2} - 2(AB)(BC)\cos ABC$ \\
$98 = 49 + 49 - 2(7)(7)\cos ABC$ \\
$98 = 98 - 98\cos ABC$ \\
Subtract 98 from both sides: \\
$0 = -98\cos ABC$ \\
Divide by $-98$: \\
$\cos ABC = 0$ as required \\
(So angle $ABC$ is a right angle)

@q 7
@topic Circle centre/radius, tangent, find k
@marks 9
@question
(a) Complete the square for $x$ and for $y$: \\
$x^{2} - 12x = (x - 6)^{2} - 36$ \\
$y^{2} + 8y = (y + 4)^{2} - 16$ \\
$(x - 6)^{2} - 36 + (y + 4)^{2} - 16 + 7 = 0$ \\
Collect the numbers: $-36 - 16 + 7 = -45$ \\
$(x - 6)^{2} + (y + 4)^{2} - 45 = 0$ \\
Add 45 to both sides: \\
$(x - 6)^{2} + (y + 4)^{2} = 45$ \\
(i) The centre is $(6, -4)$ \\
(ii) $r^{2} = 45$ \\
$r = \sqrt{45}$ \\
Pull out the square factor: $\sqrt{45} = \sqrt{9 \times 5}$ \\
$r = 3\sqrt{5}$ \\
(b) Substitute $y = 2x + k$ into the equation of the circle: \\
$x^{2} + (2x + k)^{2} - 12x + 8(2x + k) + 7 = 0$ \\
Expand the first bracket: $(2x + k)^{2} = 4x^{2} + 4kx + k^{2}$ \\
Expand the second bracket: $8(2x + k) = 16x + 8k$ \\
$x^{2} + 4x^{2} + 4kx + k^{2} - 12x + 16x + 8k + 7 = 0$ \\
Collect the $x^{2}$ terms: $x^{2} + 4x^{2} = 5x^{2}$ \\
Collect the $x$ terms: $4kx - 12x + 16x = (4k + 4)x$ \\
Collect the rest: $k^{2} + 8k + 7$ \\
$5x^{2} + (4k + 4)x + (k^{2} + 8k + 7) = 0$ \\
A tangent meets the circle once, so the discriminant is zero: \\
$b^{2} - 4ac = 0$ \\
$(4k + 4)^{2} - 4(5)(k^{2} + 8k + 7) = 0$ \\
Expand the first term: $(4k + 4)^{2} = 16k^{2} + 32k + 16$ \\
Expand the second term: $20(k^{2} + 8k + 7) = 20k^{2} + 160k + 140$ \\
$16k^{2} + 32k + 16 - 20k^{2} - 160k - 140 = 0$ \\
Collect like terms: \\
$-4k^{2} - 128k - 124 = 0$ \\
Divide by $-4$: \\
$k^{2} + 32k + 31 = 0$ \\
Factorise: \\
$(k + 1)(k + 31) = 0$ \\
$k = -1$ or $k = -31$ \\
(Check with the distance from the centre to the line: $\frac{|2(6) - (-4) + k|}{\sqrt{5}} = \frac{|16 + k|}{\sqrt{5}}$ \\
This must equal $r = 3\sqrt{5}$, so $|16 + k| = 15$, giving $k = -1$ or $k = -31$)

@q 8
@topic Exponential growth model, bacteria
@marks 9
@question
(a) At the start, $t = 0$ and $N = 2000$ \\
$2000 = Ae^{0}$ \\
$e^{0} = 1$, so $A = 2000$ \\
It triples in 2 hours, so when $t = 2$, $N = 3 \times 2000 = 6000$ \\
$6000 = 2000e^{2k}$ \\
Divide by 2000: \\
$3 = e^{2k}$ \\
Take natural logs of both sides: \\
$\ln 3 = 2k$ \\
$k = \frac{1}{2}\ln 3$ \\
$k = 0.5493$ \\
$N = 2000e^{\left( \frac{1}{2}\ln 3 \right)t}$ \\
$N = 2000e^{0.549t}$ \\
(b) Differentiate $N = 2000e^{kt}$ with respect to $t$: \\
$\frac{dN}{dt} = 2000ke^{kt}$ \\
At $t = 7$: \\
$\frac{dN}{dt} = 2000 \times \frac{1}{2}\ln 3 \times e^{7 \times \frac{1}{2}\ln 3}$ \\
$e^{3.5\ln 3} = 3^{3.5}$ \\
$3^{3.5} = 46.765$ \\
$\frac{1}{2}\ln 3 = 0.54931$ \\
$\frac{dN}{dt} = 2000 \times 0.54931 \times 46.765$ \\
$\frac{dN}{dt} = 51377$ \\
The rate of increase is 51 000 bacteria per hour (2 significant figures) \\
(c) The two numbers are equal at time $T$: \\
$6000e^{0.2kT} = 2000e^{kT}$ \\
Divide both sides by 2000: \\
$3e^{0.2kT} = e^{kT}$ \\
Divide both sides by $e^{0.2kT}$: \\
$3 = \frac{e^{kT}}{e^{0.2kT}}$ \\
Use the index law, subtract the powers: \\
$3 = e^{kT - 0.2kT}$ \\
$3 = e^{0.8kT}$ \\
Take natural logs of both sides: \\
$\ln 3 = 0.8kT$ \\
Divide by $0.8k$: \\
$T = \frac{\ln 3}{0.8k}$ \\
Put in $k = \frac{1}{2}\ln 3$: \\
$0.8k = 0.4\ln 3$ \\
$T = \frac{\ln 3}{0.4\ln 3}$ \\
Cancel $\ln 3$: \\
$T = \frac{1}{0.4}$ \\
$T = 2.5$ hours

@q 9
@topic Partial fractions, binomial expansion
@marks 11
@question
(a)(i) Multiply both sides of the identity by $(3x + 2)^{2}(1 - 5x)$: \\
$36x^{2} + 43x + 17 = A(3x + 2)(1 - 5x) + B(1 - 5x) + C(3x + 2)^{2}$ \\
Put $x = \frac{1}{5}$, which makes $1 - 5x = 0$ and removes the $A$ and $B$ terms: \\
Left side: $36\left( \frac{1}{25} \right) + 43\left( \frac{1}{5} \right) + 17$ \\
$= \frac{36}{25} + \frac{215}{25} + \frac{425}{25}$ \\
$= \frac{676}{25}$ \\
Right side: $C\left( \frac{3}{5} + 2 \right)^{2}$ \\
$= C\left( \frac{13}{5} \right)^{2}$ \\
$= \frac{169}{25}C$ \\
$\frac{676}{25} = \frac{169}{25}C$ \\
Multiply by $\frac{25}{169}$: \\
$C = 4$ \\
Put $x = -\frac{2}{3}$, which makes $3x + 2 = 0$ and removes the $A$ and $C$ terms: \\
Left side: $36\left( \frac{4}{9} \right) + 43\left( -\frac{2}{3} \right) + 17$ \\
$= 16 - \frac{86}{3} + 17$ \\
$= \frac{48 - 86 + 51}{3}$ \\
$= \frac{13}{3}$ \\
Right side: $B\left( 1 + \frac{10}{3} \right)$ \\
$= \frac{13}{3}B$ \\
$\frac{13}{3} = \frac{13}{3}B$ \\
$B = 1$ \\
(ii) Put $x = 0$ into the identity: \\
$17 = A(2)(1) + B(1) + C(2)^{2}$ \\
$17 = 2A + B + 4C$ \\
Substitute $B = 1$ and $C = 4$: \\
$17 = 2A + 1 + 16$ \\
$17 = 2A + 17$ \\
Subtract 17: \\
$2A = 0$ \\
$A = 0$ as required \\
(b)(i) With $A = 0$: $f(x) = \frac{1}{(3x + 2)^{2}} + \frac{4}{1 - 5x}$ \\
First term: $\frac{1}{(3x + 2)^{2}} = (3x + 2)^{-2}$ \\
Take 2 out of the bracket: $3x + 2 = 2\left( 1 + \frac{3}{2}x \right)$ \\
$(3x + 2)^{-2} = 2^{-2}\left( 1 + \frac{3}{2}x \right)^{-2}$ \\
$2^{-2} = \frac{1}{4}$ \\
Binomial expansion: $(1 + y)^{-2} = 1 + (-2)y + \frac{(-2)(-3)}{2!}y^{2} + \ldots$ \\
$(1 + y)^{-2} = 1 - 2y + 3y^{2} + \ldots$ \\
Put $y = \frac{3}{2}x$: \\
$-2y = -3x$ \\
$3y^{2} = 3 \times \frac{9x^{2}}{4} = \frac{27x^{2}}{4}$ \\
$\left( 1 + \frac{3}{2}x \right)^{-2} = 1 - 3x + \frac{27}{4}x^{2} + \ldots$ \\
Multiply by $\frac{1}{4}$: \\
$\frac{1}{(3x + 2)^{2}} = \frac{1}{4} - \frac{3}{4}x + \frac{27}{16}x^{2} + \ldots$ \\
Second term: $\frac{4}{1 - 5x} = 4(1 - 5x)^{-1}$ \\
$(1 + y)^{-1} = 1 - y + y^{2} - \ldots$ with $y = -5x$ \\
$(1 - 5x)^{-1} = 1 + 5x + 25x^{2} + \ldots$ \\
Multiply by 4: \\
$\frac{4}{1 - 5x} = 4 + 20x + 100x^{2} + \ldots$ \\
Add the two expansions \\
Constant terms: $\frac{1}{4} + 4 = \frac{17}{4}$ \\
$x$ terms: $-\frac{3}{4} + 20 = \frac{77}{4}$ \\
$x^{2}$ terms: $\frac{27}{16} + 100 = \frac{27}{16} + \frac{1600}{16} = \frac{1627}{16}$ \\
$f(x) = \frac{17}{4} + \frac{77}{4}x + \frac{1627}{16}x^{2} + \ldots$ \\
So $p = \frac{17}{4}$, $q = \frac{77}{4}$, $r = \frac{1627}{16}$ \\
(ii) The first expansion needs $\left| \frac{3}{2}x \right| < 1$, which is $|x| < \frac{2}{3}$ \\
The second expansion needs $|5x| < 1$, which is $|x| < \frac{1}{5}$ \\
Both must hold, so the smaller range wins: \\
$|x| < \frac{1}{5}$

@q 10
@topic Double angle identity, equation in 3x
@marks 8
@question
(a) Rewrite the top and the bottom using double angle formulae \\
Top: use $\cos 2\theta = 2\cos^{2} \theta - 1$ and $\sin 2\theta = 2\sin \theta \cos \theta$ \\
$\cos 2\theta - 1 - \sin 2\theta = 2\cos^{2} \theta - 1 - 1 - 2\sin \theta \cos \theta$ \\
$= 2\cos^{2} \theta - 2 - 2\sin \theta \cos \theta$ \\
Use $\cos^{2} \theta - 1 = -\sin^{2} \theta$, so $2\cos^{2} \theta - 2 = -2\sin^{2} \theta$ \\
Top $= -2\sin^{2} \theta - 2\sin \theta \cos \theta$ \\
Factorise: Top $= -2\sin \theta (\sin \theta + \cos \theta)$ \\
Bottom: use $\cos 2\theta = 1 - 2\sin^{2} \theta$ and $\sin 2\theta = 2\sin \theta \cos \theta$ \\
$1 + \cos 2\theta + \sin 2\theta = 1 + 1 - 2\sin^{2} \theta + 2\sin \theta \cos \theta$ \\
$= 2 - 2\sin^{2} \theta + 2\sin \theta \cos \theta$ \\
Use $1 - \sin^{2} \theta = \cos^{2} \theta$, so $2 - 2\sin^{2} \theta = 2\cos^{2} \theta$ \\
Bottom $= 2\cos^{2} \theta + 2\sin \theta \cos \theta$ \\
Factorise: Bottom $= 2\cos \theta (\cos \theta + \sin \theta)$ \\
$\frac{\cos 2\theta - 1 - \sin 2\theta}{1 + \cos 2\theta + \sin 2\theta} = \frac{-2\sin \theta (\sin \theta + \cos \theta)}{2\cos \theta (\cos \theta + \sin \theta)}$ \\
Cancel the 2 and the common bracket $(\sin \theta + \cos \theta)$, which is not zero as the bottom is not zero: \\
$= \frac{-\sin \theta}{\cos \theta}$ \\
Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$: \\
$= -\tan \theta$ as required \\
(b) The left hand side is part (a) with $\theta = 3x$ (so $2\theta = 6x$) \\
$-\tan 3x = 4\sin 3x$ \\
Write $\tan 3x = \frac{\sin 3x}{\cos 3x}$: \\
$-\frac{\sin 3x}{\cos 3x} = 4\sin 3x$ \\
Multiply both sides by $\cos 3x$: \\
$-\sin 3x = 4\sin 3x \cos 3x$ \\
Add $\sin 3x$ to both sides: \\
$0 = \sin 3x + 4\sin 3x \cos 3x$ \\
Factorise out $\sin 3x$ (do not divide by it): \\
$\sin 3x (1 + 4\cos 3x) = 0$ \\
Either $\sin 3x = 0$ or $\cos 3x = -\frac{1}{4}$ \\
The range $0 < x < 180$ degrees means $0 < 3x < 540$ degrees \\
Case 1: $\sin 3x = 0$ \\
$3x = 180$ or $3x = 360$ degrees \\
$x = 60$ or $x = 120$ degrees \\
Case 2: $\cos 3x = -\frac{1}{4}$ \\
$3x = \cos^{-1}(-0.25) = 104.48$ degrees \\
Cosine is also negative in the third quadrant: $3x = 360 - 104.48 = 255.52$ degrees \\
Add 360 to the first value: $3x = 360 + 104.48 = 464.48$ degrees \\
(The next value, 615.52, is too big) \\
Divide each by 3: \\
$x = 34.83$, $85.17$, $154.83$ degrees \\
The solutions are $x = 34.8, 60, 85.2, 120, 154.8$ degrees

@q 11
@topic Trapezium rule, parts integral, exact area
@marks 8
@question
(a) There are 5 values of $y$, so 4 strips, each of width $h = 0.25$ \\
Trapezium rule: $\frac{h}{2}\left\{ y_{0} + y_{4} + 2(y_{1} + y_{2} + y_{3}) \right\}$ \\
Add the first and last: $3.7654 + 5.7709 = 9.5363$ \\
Add the middle ones: $4.2807 + 4.7867 + 5.2834 = 14.3508$ \\
Double them: $2 \times 14.3508 = 28.7016$ \\
Total in the brackets: $9.5363 + 28.7016 = 38.2379$ \\
$\frac{0.25}{2} \times 38.2379$ \\
$= 0.125 \times 38.2379$ \\
$= 4.7797$ \\
The area is about 4.78 \\
(b) Use integration by parts on $\int 3(\ln x)^{2} dx$ \\
Let $u = (\ln x)^{2}$ and $\frac{dv}{dx} = 1$ \\
$\frac{du}{dx} = \frac{2\ln x}{x}$ and $v = x$ \\
$\int (\ln x)^{2} dx = x(\ln x)^{2} - \int x \times \frac{2\ln x}{x} dx$ \\
Cancel $x$ in the integral: \\
$= x(\ln x)^{2} - 2\int \ln x \, dx$ \\
Now find $\int \ln x \, dx$ by parts with $u = \ln x$ and $\frac{dv}{dx} = 1$ \\
$\int \ln x \, dx = x\ln x - \int x \times \frac{1}{x} dx$ \\
$= x\ln x - \int 1 \, dx$ \\
$= x\ln x - x$ \\
$\int (\ln x)^{2} dx = x(\ln x)^{2} - 2(x\ln x - x)$ \\
$= x(\ln x)^{2} - 2x\ln x + 2x$ \\
Multiply by 3: $\int 3(\ln x)^{2} dx = 3x(\ln x)^{2} - 6x\ln x + 6x$ \\
$\int 2 \, dx = 2x$ \\
$\int \left( 3(\ln x)^{2} - 2 \right) dx = 3x(\ln x)^{2} - 6x\ln x + 6x - 2x$ \\
$= 3x(\ln x)^{2} - 6x\ln x + 4x$ \\
Upper limit $x = 5$: $15(\ln 5)^{2} - 30\ln 5 + 20$ \\
Lower limit $x = 4$: $12(\ln 4)^{2} - 24\ln 4 + 16$ \\
Use $\ln 4 = 2\ln 2$, so $(\ln 4)^{2} = 4(\ln 2)^{2}$ \\
$12 \times 4(\ln 2)^{2} = 48(\ln 2)^{2}$ \\
$24 \times 2\ln 2 = 48\ln 2$ \\
Lower limit $= 48(\ln 2)^{2} - 48\ln 2 + 16$ \\
Area $= 15(\ln 5)^{2} - 30\ln 5 + 20 - \left( 48(\ln 2)^{2} - 48\ln 2 + 16 \right)$ \\
Remove the bracket: \\
$= 15(\ln 5)^{2} - 30\ln 5 + 20 - 48(\ln 2)^{2} + 48\ln 2 - 16$ \\
Collect the numbers: $20 - 16 = 4$ \\
Area $= 15(\ln 5)^{2} - 48(\ln 2)^{2} - 30\ln 5 + 48\ln 2 + 4$ \\
So $a = 15$, $b = 48$, $c = 30$, $d = 48$, $e = 4$ \\
(Check: $38.853 - 23.062 - 48.283 + 33.271 + 4 = 4.779$, close to the estimate in part (a))

@q 12
@topic Quadratic model, golf ball
@marks 9
@question
(a) Let $H = ax^{2} + bx + c$ \\
At $x = 0$ the ball is on a platform 2 m high, so $H = 2$: \\
$2 = a(0) + b(0) + c$ \\
$c = 2$ \\
$H = ax^{2} + bx + 2$ \\
The maximum is at $x = 100$, so $\frac{dH}{dx} = 0$ there: \\
$\frac{dH}{dx} = 2ax + b$ \\
$2a(100) + b = 0$ \\
Equation 1: $200a + b = 0$ \\
At $x = 160$, $H = 34$: \\
$34 = a(160)^{2} + b(160) + 2$ \\
$160^{2} = 25600$ \\
Equation 2: $25600a + 160b + 2 = 34$ \\
Subtract 2 from both sides: \\
$25600a + 160b = 32$ \\
From equation 1: $b = -200a$ \\
Substitute into equation 2: \\
$25600a + 160(-200a) = 32$ \\
$160 \times 200 = 32000$ \\
$25600a - 32000a = 32$ \\
$-6400a = 32$ \\
Divide by $-6400$: \\
$a = -\frac{32}{6400}$ \\
$a = -\frac{1}{200}$ \\
$b = -200 \times \left( -\frac{1}{200} \right)$ \\
$b = 1$ \\
$H = -\frac{1}{200}x^{2} + x + 2$ \\
(Check: at $x = 160$, $-\frac{25600}{200} + 160 + 2 = -128 + 162 = 34$) \\
(b)(i) The maximum height is at $x = 100$: \\
$H = -\frac{1}{200}(100)^{2} + 100 + 2$ \\
$= -\frac{10000}{200} + 102$ \\
$= -50 + 102$ \\
$= 52$ m \\
(ii) The ball hits the ground when $H = 0$: \\
$-\frac{1}{200}x^{2} + x + 2 = 0$ \\
Multiply every term by $-200$: \\
$x^{2} - 200x - 400 = 0$ \\
Use the quadratic formula with $a = 1$, $b = -200$, $c = -400$: \\
$x = \frac{200 \pm \sqrt{200^{2} - 4(1)(-400)}}{2}$ \\
$x = \frac{200 \pm \sqrt{40000 + 1600}}{2}$ \\
$x = \frac{200 \pm \sqrt{41600}}{2}$ \\
$\sqrt{41600} = 203.96$ \\
$x = \frac{200 + 203.96}{2} = 201.98$ \\
$x = \frac{200 - 203.96}{2} = -1.98$ \\
The ball cannot travel a negative distance, so reject $x = -1.98$ \\
The distance travelled is 202 m to the nearest metre \\
(c) Another limitation: the ground is unlikely to be horizontal all the way \\
(Or the ball is not a particle, as it has size and spin)

@q 13
@topic Parametric equations to Cartesian
@marks 3
@question
Work out $x - 2$ first, writing 2 over the denominator $t^{2} + 3$ \\
$x - 2 = \frac{t^{2} + 9}{t^{2} + 3} - \frac{2(t^{2} + 3)}{t^{2} + 3}$ \\
$x - 2 = \frac{t^{2} + 9 - 2t^{2} - 6}{t^{2} + 3}$ \\
$x - 2 = \frac{3 - t^{2}}{t^{2} + 3}$ \\
Square it: \\
$(x - 2)^{2} = \frac{(3 - t^{2})^{2}}{(t^{2} + 3)^{2}}$ \\
$9(x - 2)^{2} = \frac{9(3 - t^{2})^{2}}{(t^{2} + 3)^{2}}$ \\
Now $y^{2}$: $y^{2} = \frac{(6\sqrt{3}t)^{2}}{(t^{2} + 3)^{2}}$ \\
$(6\sqrt{3}t)^{2} = 36 \times 3 \times t^{2} = 108t^{2}$ \\
$y^{2} = \frac{108t^{2}}{(t^{2} + 3)^{2}}$ \\
Add them: \\
$9(x - 2)^{2} + y^{2} = \frac{9(3 - t^{2})^{2} + 108t^{2}}{(t^{2} + 3)^{2}}$ \\
Expand $(3 - t^{2})^{2} = 9 - 6t^{2} + t^{4}$ \\
$9(3 - t^{2})^{2} = 81 - 54t^{2} + 9t^{4}$ \\
Top: $81 - 54t^{2} + 9t^{4} + 108t^{2}$ \\
Collect the $t^{2}$ terms: $-54t^{2} + 108t^{2} = 54t^{2}$ \\
Top $= 9t^{4} + 54t^{2} + 81$ \\
Factorise out 9: Top $= 9(t^{4} + 6t^{2} + 9)$ \\
$t^{4} + 6t^{2} + 9 = (t^{2} + 3)^{2}$ \\
Top $= 9(t^{2} + 3)^{2}$ \\
$9(x - 2)^{2} + y^{2} = \frac{9(t^{2} + 3)^{2}}{(t^{2} + 3)^{2}}$ \\
Cancel the common factor: \\
$9(x - 2)^{2} + y^{2} = 9$ as required

@q 14
@topic Quotient rule, show dy/dx = 1/(A root x)
@marks 4
@question
Use the quotient rule with $u = x - 16$ and $v = 4 + \sqrt{x}$ \\
$\frac{du}{dx} = 1$ \\
$v = 4 + x^{\frac{1}{2}}$, so $\frac{dv}{dx} = \frac{1}{2}x^{-\frac{1}{2}} = \frac{1}{2\sqrt{x}}$ \\
$\frac{dy}{dx} = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^{2}}$ \\
$\frac{dy}{dx} = \frac{(4 + \sqrt{x}) - (x - 16) \times \frac{1}{2\sqrt{x}}}{(4 + \sqrt{x})^{2}}$ \\
Write the top over the common denominator $2\sqrt{x}$: \\
$(4 + \sqrt{x}) = \frac{2\sqrt{x}(4 + \sqrt{x})}{2\sqrt{x}}$ \\
Expand: $2\sqrt{x}(4 + \sqrt{x}) = 8\sqrt{x} + 2x$ \\
Top $= \frac{8\sqrt{x} + 2x - (x - 16)}{2\sqrt{x}}$ \\
Remove the bracket: $8\sqrt{x} + 2x - x + 16$ \\
Top $= \frac{x + 8\sqrt{x} + 16}{2\sqrt{x}}$ \\
Factorise the numerator: $x + 8\sqrt{x} + 16 = (\sqrt{x} + 4)^{2}$ \\
Top $= \frac{(4 + \sqrt{x})^{2}}{2\sqrt{x}}$ \\
$\frac{dy}{dx} = \frac{(4 + \sqrt{x})^{2}}{2\sqrt{x}(4 + \sqrt{x})^{2}}$ \\
Cancel $(4 + \sqrt{x})^{2}$: \\
$\frac{dy}{dx} = \frac{1}{2\sqrt{x}}$ \\
So $A = 2$ \\
Alt: factorise first: $x - 16 = (\sqrt{x} - 4)(\sqrt{x} + 4)$, so $y = \sqrt{x} - 4$ \\
Then $\frac{dy}{dx} = \frac{1}{2\sqrt{x}}$, which agrees

@q 15
@topic Exhaustion and contradiction proofs
@marks 6
@question
(i) The natural numbers up to 4 are 1, 2, 3 and 4, so check each one \\
$n = 1$: $(1 + 1)^{5} = 2^{5} = 32$ and $5^{1} = 5$ \\
$32 > 5$, so true \\
$n = 2$: $(2 + 1)^{5} = 3^{5} = 243$ and $5^{2} = 25$ \\
$243 > 25$, so true \\
$n = 3$: $(3 + 1)^{5} = 4^{5} = 1024$ and $5^{3} = 125$ \\
$1024 > 125$, so true \\
$n = 4$: $(4 + 1)^{5} = 5^{5} = 3125$ and $5^{4} = 625$ \\
$3125 > 625$, so true \\
All four cases are true, so $(n + 1)^{5} > 5^{n}$ for $n \in \mathbb{N}$, $n \leq 4$ \\
(ii) Assume the opposite: $m^{5} + 7$ is odd and $m$ is not even \\
So $m$ is odd: $m = 2p + 1$ where $p$ is an integer \\
$m^{5} + 7 = (2p + 1)^{5} + 7$ \\
Expand using the binomial expansion: \\
$(2p + 1)^{5} = (2p)^{5} + 5(2p)^{4} + 10(2p)^{3} + 10(2p)^{2} + 5(2p) + 1$ \\
$(2p)^{5} = 32p^{5}$ \\
$5(2p)^{4} = 5 \times 16p^{4} = 80p^{4}$ \\
$10(2p)^{3} = 10 \times 8p^{3} = 80p^{3}$ \\
$10(2p)^{2} = 10 \times 4p^{2} = 40p^{2}$ \\
$5(2p) = 10p$ \\
$(2p + 1)^{5} = 32p^{5} + 80p^{4} + 80p^{3} + 40p^{2} + 10p + 1$ \\
Add 7: \\
$m^{5} + 7 = 32p^{5} + 80p^{4} + 80p^{3} + 40p^{2} + 10p + 8$ \\
Every term is even, so take out a factor of 2: \\
$m^{5} + 7 = 2(16p^{5} + 40p^{4} + 40p^{3} + 20p^{2} + 5p + 4)$ \\
This is 2 times an integer, so it is even \\
But we were told $m^{5} + 7$ is odd, which is a contradiction \\
So $m$ cannot be odd \\
Therefore if $m^{5} + 7$ is odd then $m$ must be even
