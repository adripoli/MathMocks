@paper AS1 Shadow October 2021

@q 1
@topic Quadratic inequality in set notation
@marks 3
@question
Subtract 30 from both sides so that one side is 0: \\
$x^{2} - x - 30 > 0$ \\
Factorise. Two numbers that multiply to $-30$ and add to $-1$ are $-6$ and $5$: \\
$(x - 6)(x + 5) > 0$ \\
The critical values are where each bracket is 0: \\
$x = 6$ and $x = -5$ \\
The graph of $y = x^{2} - x - 30$ is a U-shape (the $x^{2}$ coefficient is positive), so it is above the $x$-axis outside the two roots \\
$x < -5$ or $x > 6$ \\
(Check: $x = 0$ is between the roots and gives $0 - 0 - 30 = -30$, which is not above 0) \\
In set notation: \\
$\{ x : x < -5 \} \text{ or } \{ x : x > 6 \}$

@q 2
@topic Index laws, y in terms of x
@marks 3
@question
Write every number as a power of 2. Use $8 = 2^{3}$ and $64 = 2^{6}$: \\
$8^{x-1} = \left( 2^{3} \right)^{x-1}$ \\
Multiply the indices: \\
$= 2^{3(x-1)}$ \\
$= 2^{3x-3}$ \\
The equation becomes: \\
$\frac{2^{3x-3}}{2^{y+2}} = 2^{6}$ \\
Subtract the indices when dividing powers of the same base: \\
$2^{(3x-3)-(y+2)} = 2^{6}$ \\
Remove the brackets in the index: \\
$2^{3x-3-y-2} = 2^{6}$ \\
$2^{3x-y-5} = 2^{6}$ \\
The bases are equal, so the indices are equal: \\
$3x - y - 5 = 6$ \\
Add $y$ to both sides: \\
$3x - 5 = 6 + y$ \\
Subtract 6 from both sides: \\
$3x - 5 - 6 = y$ \\
$y = 3x - 11$ \\
(Check with $x = 4$, $y = 1$: $\frac{8^{3}}{2^{3}} = \frac{512}{8} = 64$)

@q 3
@topic Integrate an algebraic fraction
@marks 4
@question
Split the fraction into two, dividing each term of the top by $3x^{2}$: \\
$\frac{4x^{3} - 6}{3x^{2}} = \frac{4x^{3}}{3x^{2}} - \frac{6}{3x^{2}}$ \\
Simplify each fraction: \\
$\frac{4x^{3}}{3x^{2}} = \frac{4}{3}x$ \\
$\frac{6}{3x^{2}} = \frac{2}{x^{2}} = 2x^{-2}$ \\
The integral is now: \\
$\int \left( \frac{4}{3}x - 2x^{-2} \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$ \\
$\frac{4}{3}x \to \frac{4}{3} \times \frac{x^{2}}{2} = \frac{2}{3}x^{2}$ \\
$-2x^{-2} \to -2 \times \frac{x^{-1}}{-1} = 2x^{-1}$ \\
Add the constant of integration $c$: \\
$\int \frac{4x^{3} - 6}{3x^{2}} dx = \frac{2}{3}x^{2} + \frac{2}{x} + c$ \\
(Check: differentiating gives $\frac{4}{3}x - \frac{2}{x^{2}}$, which is $\frac{4x^{3} - 6}{3x^{2}}$)

@q 4
@topic Stone on ice, vectors and speed
@marks 5
@question
(a) Find the vector $\text{AB}$, the displacement from $A$ to $B$: \\
$\text{AB} = \text{OB} - \text{OA}$ \\
$= (24\mathbf{i} + 7\mathbf{j}) - (-48\mathbf{i} - 14\mathbf{j})$ \\
$\mathbf{i}$ part: $24 - (-48) = 72$ \\
$\mathbf{j}$ part: $7 - (-14) = 21$ \\
$\text{AB} = 72\mathbf{i} + 21\mathbf{j}$ \\
The stone moves in a straight line from $A$, so its position is $\text{OA} + \lambda \text{AB}$, where $\lambda = 1$ is at $B$: \\
$\text{OA} + \lambda \text{AB} = (-48 + 72\lambda)\mathbf{i} + (-14 + 21\lambda)\mathbf{j}$ \\
The stone is at $O$ when both parts are 0. For the $\mathbf{i}$ part: \\
$-48 + 72\lambda = 0$ \\
$72\lambda = 48$ \\
$\lambda = \frac{48}{72} = \frac{2}{3}$ \\
For the $\mathbf{j}$ part, with $\lambda = \frac{2}{3}$: \\
$-14 + 21 \times \frac{2}{3} = -14 + 14 = 0$ \\
Both parts are 0 for the same $\lambda = \frac{2}{3}$, and $0 < \frac{2}{3} < 1$, so the stone passes through $O$ on its way from $A$ to $B$ \\
(b) The distance travelled from $A$ to $B$ is the magnitude of $\text{AB}$: \\
$|\text{AB}| = \sqrt{72^{2} + 21^{2}}$ \\
$72^{2} = 5184$ and $21^{2} = 441$: \\
$= \sqrt{5184 + 441}$ \\
$= \sqrt{5625}$ \\
$= 75$ m \\
This takes 5 seconds. Use $\text{speed} = \frac{\text{distance}}{\text{time}}$: \\
$\text{speed} = \frac{75}{5}$ \\
$= 15$ m per second

@q 5
@topic Gradient of tangent and chord PQ
@marks 6
@question
(a) Differentiate $y = 2x^{2} + 2$, using $\frac{d}{dx}(x^{n}) = nx^{n-1}$: \\
$\frac{dy}{dx} = 4x$ \\
At $P$, $x = 2$: \\
$\frac{dy}{dx} = 4(2)$ \\
$= 8$ \\
The gradient of the tangent at $P$ is 8 \\
(b) $Q$ has $x$ coordinate $2 + h$. Find its $y$ coordinate: \\
$y_{Q} = 2(2 + h)^{2} + 2$ \\
Expand the bracket: $(2 + h)^{2} = 4 + 4h + h^{2}$ \\
$y_{Q} = 2\left( 4 + 4h + h^{2} \right) + 2$ \\
$= 8 + 8h + 2h^{2} + 2$ \\
$= 10 + 8h + 2h^{2}$ \\
Gradient of $PQ = \frac{y_{Q} - y_{P}}{x_{Q} - x_{P}}$: \\
$= \frac{10 + 8h + 2h^{2} - 10}{(2 + h) - 2}$ \\
$= \frac{8h + 2h^{2}}{h}$ \\
Divide the top and the bottom by $h$ (not zero, as $Q$ is a different point from $P$): \\
$= 8 + 2h$ \\
(c) As $Q$ gets closer to $P$, $h$ gets closer to 0 and the line $PQ$ becomes the tangent at $P$ \\
When $h \to 0$, the gradient $8 + 2h \to 8$, which is the gradient of the tangent found in part (a) \\
So the gradient of the chord $PQ$ tends to the gradient of the tangent at $P$ as $h \to 0$

@q 6
@topic Solve cubic, then hence for (y-3)
@marks 6
@question
(a) Take out the common factor $x$: \\
$x\left( 5x^{2} - 13x - 6 \right) = 0$ \\
Factorise the quadratic. Two numbers that multiply to $5 \times (-6) = -30$ and add to $-13$ are $-15$ and $2$: \\
$5x^{2} - 15x + 2x - 6$ \\
$= 5x(x - 3) + 2(x - 3)$ \\
$= (5x + 2)(x - 3)$ \\
$x(5x + 2)(x - 3) = 0$ \\
$x = 0$ or $5x + 2 = 0$ or $x - 3 = 0$ \\
$x = 0$ or $x = -\frac{2}{5}$ or $x = 3$ \\
(b) Let $x = (y - 3)^{2}$. Then $(y - 3)^{4} = x^{2}$ and $(y - 3)^{6} = x^{3}$ \\
The equation becomes: \\
$5x^{3} - 13x^{2} - 6x = 0$ \\
This is the equation from part (a), so: \\
$x = 0$ or $x = -\frac{2}{5}$ or $x = 3$ \\
Replace $x$ with $(y - 3)^{2}$ in each case: \\
Case $(y - 3)^{2} = 0$: \\
$y - 3 = 0$ \\
$y = 3$ \\
Case $(y - 3)^{2} = -\frac{2}{5}$: \\
A square cannot be negative, so there are no real solutions. Reject it \\
Case $(y - 3)^{2} = 3$: \\
Take square roots, giving both signs: \\
$y - 3 = \pm \sqrt{3}$ \\
$y = 3 \pm \sqrt{3}$ \\
The real solutions are $y = 3$, $y = 3 + \sqrt{3}$ and $y = 3 - \sqrt{3}$

@q 7
@topic Parallelogram area and diagonal
@marks 5
@question
(a) Opposite sides of a parallelogram are equal, so $PS = QR = 7$ cm \\
The area of a parallelogram is $PQ \times PS \times \sin(SPQ)$: \\
$40 = 14 \times 7 \times \sin(SPQ)$ \\
$40 = 98\sin(SPQ)$ \\
Divide both sides by 98: \\
$\sin(SPQ) = \frac{40}{98}$ \\
$\sin(SPQ) = \frac{20}{49}$ \\
$\sin^{-1}\left( \frac{20}{49} \right) = 24.0895...$ degrees \\
Another angle has the same sine, which is $180 - 24.0895...$ \\
$= 155.9105...$ degrees \\
The angle $SPQ$ is obtuse, so take the second one: \\
$SPQ = 155.91$ degrees (2 dp) \\
(b) Use the cosine rule in triangle $SPQ$, $SQ^{2} = SP^{2} + PQ^{2} - 2(SP)(PQ)\cos(SPQ)$: \\
$SQ^{2} = 7^{2} + 14^{2} - 2(7)(14)\cos(155.9105...)$ \\
$SQ^{2} = 49 + 196 - 196\cos(155.9105...)$ \\
$\cos(155.9105...) = -0.912909$ \\
$SQ^{2} = 245 - 196 \times (-0.912909)$ \\
$= 245 + 178.93$ \\
$= 423.93$ \\
Take the positive square root: \\
$SQ = \sqrt{423.93}$ \\
$= 20.59...$ \\
$SQ = 20.6$ cm (1 dp)

@q 8
@topic Binomial coefficient, constant term
@marks 7
@question
(a) The term in $x^{r}$ in the expansion of $(2 + ax)^{8}$ is $8Cr \times 2^{8-r} \times (ax)^{r}$ \\
For the $x^{4}$ term, $r = 4$: \\
$8C4 \times 2^{4} \times a^{4}x^{4}$ \\
$8C4 = \frac{8 \times 7 \times 6 \times 5}{4 \times 3 \times 2 \times 1} = 70$ and $2^{4} = 16$: \\
$70 \times 16 \times a^{4}x^{4}$ \\
$= 1120a^{4}x^{4}$ \\
This equals $5670x^{4}$: \\
$1120a^{4} = 5670$ \\
Divide both sides by 1120: \\
$a^{4} = \frac{5670}{1120}$ \\
Divide top and bottom by 70: \\
$a^{4} = \frac{81}{16}$ \\
Take the fourth root of both sides. $\left( \frac{3}{2} \right)^{4} = \frac{81}{16}$, and an even power also works for the negative: \\
$a = \frac{3}{2}$ or $a = -\frac{3}{2}$ \\
(The question says "this value of $a$" in part (b), but $a$ is only given as a constant and could have either sign, so part (b) is worked for both) \\
(b) The constant term of the product comes from two pairs: \\
1 times the constant term of $(2 + ax)^{8}$ \\
$\frac{1}{x^{3}}$ times the $x^{3}$ term of $(2 + ax)^{8}$ \\
The constant term of $(2 + ax)^{8}$ is $2^{8} = 256$ \\
The $x^{3}$ term has $r = 3$: \\
$8C3 \times 2^{5} \times a^{3}x^{3}$ \\
$8C3 = \frac{8 \times 7 \times 6}{3 \times 2 \times 1} = 56$ and $2^{5} = 32$: \\
$56 \times 32 \times a^{3}x^{3}$ \\
$= 1792a^{3}x^{3}$ \\
Multiply this by $\frac{1}{x^{3}}$, so the $x^{3}$ cancels: \\
$\frac{1}{x^{3}} \times 1792a^{3}x^{3} = 1792a^{3}$ \\
Constant term $= 256 + 1792a^{3}$ \\
With $a = \frac{3}{2}$: $a^{3} = \frac{27}{8}$ \\
$1792 \times \frac{27}{8} = 224 \times 27 = 6048$ \\
Constant term $= 256 + 6048$ \\
$= 6304$ \\
(With the other value $a = -\frac{3}{2}$, $a^{3} = -\frac{27}{8}$ and the constant term is $256 - 6048 = -5792$)

@q 9
@topic Definite integral, cube root, find k
@marks 4
@question
Write the integrand as a power of $x$: \\
$\frac{10}{\sqrt[3]{x}} = 10x^{-\frac{1}{3}}$ \\
Integrate using $x^{n} \to \frac{x^{n+1}}{n+1}$: \\
$10x^{-\frac{1}{3}} \to 10 \times \frac{x^{\frac{2}{3}}}{\frac{2}{3}}$ \\
$= 10 \times \frac{3}{2}x^{\frac{2}{3}}$ \\
$= 15x^{\frac{2}{3}}$ \\
$\int_{8}^{k} 10x^{-\frac{1}{3}} dx = \left[ 15x^{\frac{2}{3}} \right]_{8}^{k}$ \\
Upper limit: $15k^{\frac{2}{3}}$ \\
Lower limit: $15 \times 8^{\frac{2}{3}}$. The cube root of 8 is 2 and $2^{2} = 4$: \\
$15 \times 4 = 60$ \\
Subtract the lower limit from the upper limit and set equal to $\frac{135}{4}$: \\
$15k^{\frac{2}{3}} - 60 = \frac{135}{4}$ \\
Add 60 to both sides. Write 60 as $\frac{240}{4}$: \\
$15k^{\frac{2}{3}} = \frac{135}{4} + \frac{240}{4}$ \\
$15k^{\frac{2}{3}} = \frac{375}{4}$ \\
Divide both sides by 15: \\
$k^{\frac{2}{3}} = \frac{375}{60}$ \\
$k^{\frac{2}{3}} = \frac{25}{4}$ \\
Raise both sides to the power $\frac{3}{2}$: \\
$k = \left( \frac{25}{4} \right)^{\frac{3}{2}}$ \\
The square root of $\frac{25}{4}$ is $\frac{5}{2}$: \\
$k = \left( \frac{5}{2} \right)^{3}$ \\
$k = \frac{125}{8}$ \\
$\frac{125}{8} = 15.625$, which is greater than 8, so it satisfies $k > 8$

@q 10
@topic Proof with odd numbers, counterexample
@marks 5
@question
(a) Let $n$ be any odd number. Write $n = 2m + 1$, where $m$ is a whole number \\
Factorise first: \\
$n^{3} + n = n\left( n^{2} + 1 \right)$ \\
Work out $n^{2} + 1$ by expanding the bracket: \\
$n^{2} + 1 = (2m + 1)^{2} + 1$ \\
$= 4m^{2} + 4m + 1 + 1$ \\
$= 4m^{2} + 4m + 2$ \\
Take out a factor of 2: \\
$= 2\left( 2m^{2} + 2m + 1 \right)$ \\
So: \\
$n^{3} + n = (2m + 1) \times 2\left( 2m^{2} + 2m + 1 \right)$ \\
$= 2(2m + 1)\left( 2m^{2} + 2m + 1 \right)$ \\
$2m + 1$ is odd \\
$2m^{2} + 2m + 1 = 2\left( m^{2} + m \right) + 1$ is odd \\
The product of two odd numbers is odd, so $(2m + 1)\left( 2m^{2} + 2m + 1 \right)$ is odd \\
So $n^{3} + n$ is 2 times an odd number. It is even (a multiple of 2), and it is not a multiple of 4, because 2 times an odd number is never divisible by 4 \\
So the statement is true for all odd numbers \\
(b) Try an even number. $n = 4$: \\
$n^{3} + n = 4^{3} + 4$ \\
$= 64 + 4$ \\
$= 68$ \\
$68 = 4 \times 17$, which is a multiple of 4 \\
So the statement is not true for $n = 4$, and it is not always true

@q 11
@topic Exponential model, orchard area
@marks 6
@question
(a) Just before planting started is $t = 0$: \\
$A = 10 - 5.5e^{0}$ \\
$e^{0} = 1$, so: \\
$A = 10 - 5.5$ \\
$A = 4.5$ km$^{2}$ \\
(b) 1st January 2019 is $2019 - 2005 = 14$ years after 1st January 2005, so $t = 14$ and $A = 8$: \\
$8 = 10 - 5.5e^{14c}$ \\
Subtract 10 from both sides: \\
$-2 = -5.5e^{14c}$ \\
Divide both sides by $-5.5$: \\
$e^{14c} = \frac{2}{5.5}$ \\
$e^{14c} = \frac{4}{11}$ \\
Take natural logs of both sides: \\
$14c = \ln \left( \frac{4}{11} \right)$ \\
$14c = -1.011601...$ \\
Divide both sides by 14: \\
$c = -0.0722572...$ \\
$c = -0.07226$ (4 sf) \\
The complete equation is: \\
$A = 10 - 5.5e^{-0.07226t}$ \\
(c) $c$ is negative, so as $t$ gets large, $e^{ct}$ gets closer to 0 and $A$ gets closer to 10 \\
The area never goes above 10 km$^{2}$, so the model can never reach the planned 12 km$^{2}$

@q 12
@topic Trig equation, student errors, solutions
@marks 9
@question
(i) Use $\sin^{2} \theta = 1 - \cos^{2} \theta$ to get an equation in $\cos \theta$ only: \\
$5\left( 1 - \cos^{2} \theta \right) = 6\cos \theta$ \\
Expand the bracket: \\
$5 - 5\cos^{2} \theta = 6\cos \theta$ \\
Move every term to the right-hand side: \\
$0 = 5\cos^{2} \theta + 6\cos \theta - 5$ \\
Let $s = \cos \theta$: \\
$5s^{2} + 6s - 5 = 0$ \\
This does not factorise (the discriminant $36 + 100 = 136$ is not a square), so use the quadratic formula $s = \frac{-b \pm \sqrt{b^{2} - 4ac}}{2a}$ with $a = 5$, $b = 6$, $c = -5$: \\
$s = \frac{-6 \pm \sqrt{6^{2} - 4(5)(-5)}}{2(5)}$ \\
$= \frac{-6 \pm \sqrt{36 + 100}}{10}$ \\
$= \frac{-6 \pm \sqrt{136}}{10}$ \\
$\sqrt{136} = 11.6619...$ \\
$\cos \theta = \frac{-6 + 11.6619}{10} = 0.566190...$ \\
or $\cos \theta = \frac{-6 - 11.6619}{10} = -1.766190...$ \\
$\cos \theta = -1.766...$ is impossible, as cosine is between $-1$ and 1. Reject it \\
$\cos \theta = 0.566190...$ \\
$\theta = \cos^{-1}(0.566190...) = 55.515...$ degrees \\
The other solution in one turn is $360 - 55.515... = 304.485...$ degrees \\
Add 360 to each to find those in the next turn: \\
$55.515... + 360 = 415.515...$ degrees \\
$304.485... + 360 = 664.485...$ degrees, which is above 450, so reject it \\
$\theta = 55.5$, $304.5$ or $415.5$ degrees (1 dp) \\
(ii)(a) Error 1. The student divided both sides of $5\sin^{2} x = 3\sin x$ by $\sin x$. This loses the solution $\sin x = 0$, which in the range $0 < x \leq 180$ gives $x = 180$ degrees. They should have factorised: $\sin x(5\sin x - 3) = 0$ \\
Error 2. After $\sin x = \frac{3}{5}$, only the calculator value 36.9 degrees is given. The second solution in the range, $180 - 36.9 = 143.1$ degrees, is missing \\
(b) Let $\theta = 5\alpha + 40$. Then we need $\sin \theta = \frac{3}{5}$ \\
$\sin^{-1}\left( \frac{3}{5} \right) = 36.87...$ degrees, and the other angle in one turn is $180 - 36.87... = 143.13...$ degrees \\
All solutions are $\theta = 36.87... + 360n$ and $\theta = 143.13... + 360n$, where $n$ is a whole number \\
$\alpha > 0$ means $5\alpha > 0$, so $\theta > 40$ \\
The value $36.87...$ is below 40, so it would give a negative $\alpha$. Leave it out \\
The four smallest values of $\theta$ above 40 are: \\
$143.13...$ \\
$36.87... + 360 = 396.87...$ \\
$143.13... + 360 = 503.13...$ \\
$36.87... + 720 = 756.87...$ \\
Use $\alpha = \frac{\theta - 40}{5}$ for each: \\
$\alpha_{1} = \frac{143.13 - 40}{5} = 20.6...$ \\
$\alpha_{2} = \frac{396.87 - 40}{5} = 71.4...$ \\
$\alpha_{3} = \frac{503.13 - 40}{5} = 92.6...$ \\
$\alpha_{4} = \frac{756.87 - 40}{5}$ \\
$= \frac{716.87}{5}$ \\
$= 143.37...$ \\
$\alpha_{4} = 143$ degrees (nearest degree)

@q 13
@topic Power model using logs, reptiles
@marks 7
@question
(a) Take logs to base 10 of both sides of $h = pm^{q}$: \\
$\log_{10} h = \log_{10} \left( pm^{q} \right)$ \\
Use the product law $\log (ab) = \log a + \log b$: \\
$\log_{10} h = \log_{10} p + \log_{10} m^{q}$ \\
Use the power law $\log a^{n} = n\log a$: \\
$\log_{10} h = \log_{10} p + q\log_{10} m$ \\
Write it in the form of a straight line, $\log_{10} h = q \times (\log_{10} m) + \log_{10} p$ \\
This is a line with gradient $q$ and vertical intercept $\log_{10} p$ \\
The gradient is $-0.486$: \\
$q = -0.486$ \\
The intercept is 2.25: \\
$\log_{10} p = 2.25$ \\
Use the definition of a log: \\
$p = 10^{2.25}$ \\
$p = 177.83...$ \\
$p = 178$ (3 sf) \\
(b) Put $m = 2$ into the model, using the unrounded value of $p$: \\
$h = 10^{2.25} \times 2^{-0.486}$ \\
$= 177.83 \times 0.7140$ \\
$= 126.97$ \\
The model predicts about 127 beats per minute, and the real rate is 125 \\
The difference is about 2 beats per minute, which is $\frac{2}{125} = 0.016$, or 1.6 percent, of the real rate \\
This is very close, so the model is suitable for this reptile \\
(c) Put $m = 1$ into the model: \\
$h = p \times 1^{q} = p$ \\
So $p$ is the resting heart rate of a reptile with a mass of 1 kg, which is about 178 beats per minute

@q 14
@topic Complete the square, area to a line
@marks 10
@question
(a) Take out a factor of $-5$ from the $x^{2}$ and $x$ terms: \\
$f(x) = -5\left( x^{2} - 6x \right) + 6$ \\
Complete the square inside the bracket. Half of $-6$ is $-3$: \\
$x^{2} - 6x = (x - 3)^{2} - 9$ \\
$f(x) = -5\left[ (x - 3)^{2} - 9 \right] + 6$ \\
Expand the square bracket, multiplying both terms by $-5$: \\
$= -5(x - 3)^{2} + 45 + 6$ \\
$= -5(x - 3)^{2} + 51$ \\
So $a = -5$, $b = -3$ and $c = 51$ \\
(b) $(x - 3)^{2} \geq 0$, so $-5(x - 3)^{2} \leq 0$ and $f(x) \leq 51$ \\
The greatest value is 51, when $(x - 3)^{2} = 0$, that is $x = 3$ \\
$M = (3, 51)$ \\
(c) The line $l$ passes through $M$ and is parallel to the $x$-axis, so $l$ is $y = 51$ \\
$R$ lies between the line (above) and the curve (below), from $x = 0$ (the $y$-axis) to $x = 3$ (at $M$) \\
$\text{Area} = \int_{0}^{3} (51 - f(x)) dx$ \\
Work out the integrand: \\
$51 - f(x) = 51 - \left( -5x^{2} + 30x + 6 \right)$ \\
$= 51 + 5x^{2} - 30x - 6$ \\
$= 5x^{2} - 30x + 45$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$: \\
$\text{Area} = \left[ \frac{5x^{3}}{3} - 15x^{2} + 45x \right]_{0}^{3}$ \\
Upper limit $x = 3$: \\
$\frac{5(27)}{3} - 15(9) + 45(3) = 45 - 135 + 135 = 45$ \\
Lower limit $x = 0$ gives 0 \\
$\text{Area} = 45 - 0$ \\
$= 45$ square units \\
(Check: $5x^{2} - 30x + 45 = 5(x - 3)^{2}$, and $\int_{0}^{3} 5(x - 3)^{2} dx = \left[ \frac{5(x - 3)^{3}}{3} \right]_{0}^{3} = 0 - \frac{5(-27)}{3} = 45$)

@q 15
@topic Circle tangent, centre and second tangent
@marks 9
@question
(a) $PN$ is a radius, and a radius is perpendicular to the tangent at $P$ \\
The gradient of $l$ is $\frac{1}{5}$, so the gradient of $PN$ is the negative reciprocal: \\
$m = -5$ \\
Use $y - y_{1} = m(x - x_{1})$ through $N(5, 14)$: \\
$y - 14 = -5(x - 5)$ \\
Expand the bracket: \\
$y - 14 = -5x + 25$ \\
Add 14 to both sides: \\
$y = -5x + 39$ \\
(b) $P$ is where the line $l$ meets the line $PN$. Make the $y$ values equal: \\
$\frac{1}{5}x = -5x + 39$ \\
Multiply every term by 5: \\
$x = -25x + 195$ \\
Add $25x$ to both sides: \\
$26x = 195$ \\
$x = \frac{195}{26}$ \\
$x = 7.5$ \\
Find $y$ from $y = \frac{1}{5}x$: \\
$y = \frac{1}{5} \times 7.5 = 1.5$ \\
$P = (7.5, 1.5)$ \\
The radius is the distance $NP$. Use $r^{2} = (x_{2} - x_{1})^{2} + (y_{2} - y_{1})^{2}$: \\
$r^{2} = (7.5 - 5)^{2} + (1.5 - 14)^{2}$ \\
$= 2.5^{2} + (-12.5)^{2}$ \\
$= 6.25 + 156.25$ \\
$= 162.5$ \\
The circle has centre $(5, 14)$, so: \\
$(x - 5)^{2} + (y - 14)^{2} = 162.5$ \\
(c) The other tangent with gradient $\frac{1}{5}$ is on the opposite side of the circle. It touches $C$ at the point $P'$ that is directly opposite $P$, so $N$ is the midpoint of $PP'$ \\
Let $P' = (p, q)$. For the $x$ coordinates: \\
$\frac{7.5 + p}{2} = 5$ \\
$7.5 + p = 10$ \\
$p = 2.5$ \\
For the $y$ coordinates: \\
$\frac{1.5 + q}{2} = 14$ \\
$1.5 + q = 28$ \\
$q = 26.5$ \\
$P' = (2.5, 26.5)$ \\
The tangent at $P'$ has gradient $\frac{1}{5}$ and equation $y = \frac{1}{5}x + k$. Substitute $P'$: \\
$26.5 = \frac{1}{5}(2.5) + k$ \\
$26.5 = 0.5 + k$ \\
Subtract 0.5 from both sides: \\
$k = 26$ \\
(Check: $P'$ is on the line $PN$, as $-5(2.5) + 39 = 26.5$, and $k = 26$ is not zero)

@q 16
@topic Cubic with unknowns, stationary points
@marks 11
@question
(a)(i) Differentiate, using $\frac{d}{dx}(x^{n}) = nx^{n-1}$: \\
$f'(x) = 3ax^{2} + 34x - 17$ \\
The gradient at $x = 2$ is 3: \\
$f'(2) = 3a(2)^{2} + 34(2) - 17$ \\
$= 12a + 68 - 17$ \\
$= 12a + 51$ \\
$12a + 51 = 3$ \\
Subtract 51 from both sides: \\
$12a = -48$ \\
Divide both sides by 12: \\
$a = -4$, as required \\
(a)(ii) The point $(2, 8)$ is on the curve, so $f(2) = 8$: \\
$a(2)^{3} + 17(2)^{2} - 17(2) + b = 8$ \\
$8a + 68 - 34 + b = 8$ \\
$8a + 34 + b = 8$ \\
Substitute $a = -4$: \\
$-32 + 34 + b = 8$ \\
$2 + b = 8$ \\
$b = 6$ \\
(b) Now $f(x) = -4x^{3} + 17x^{2} - 17x + 6$ and the gradient function is: \\
$f'(x) = -12x^{2} + 34x - 17$ \\
Stationary points are where $f'(x) = 0$: \\
$-12x^{2} + 34x - 17 = 0$ \\
Multiply both sides by $-1$: \\
$12x^{2} - 34x + 17 = 0$ \\
Find the discriminant $b^{2} - 4ac$ with $a = 12$, $b = -34$, $c = 17$: \\
$(-34)^{2} - 4(12)(17)$ \\
$= 1156 - 816$ \\
$= 340$ \\
The discriminant is positive, so there are two distinct real roots. So $C$ has two stationary points \\
(c) Test $x = 3$ in $f(x)$: \\
$f(3) = -4(27) + 17(9) - 17(3) + 6$ \\
$= -108 + 153 - 51 + 6$ \\
$= 0$ \\
So $(x - 3)$ is a factor. Write $f(x) = (x - 3)\left( -4x^{2} + px + q \right)$ and expand: \\
$(x - 3)\left( -4x^{2} + px + q \right) = -4x^{3} + px^{2} + qx + 12x^{2} - 3px - 3q$ \\
$= -4x^{3} + (p + 12)x^{2} + (q - 3p)x - 3q$ \\
Compare coefficients of $x^{2}$: \\
$p + 12 = 17$ \\
$p = 5$ \\
Compare constant terms: \\
$-3q = 6$ \\
$q = -2$ \\
Check the $x$ terms: $q - 3p = -2 - 15 = -17$, which matches \\
$f(x) = (x - 3)\left( -4x^{2} + 5x - 2 \right)$ \\
$Q(x) = -4x^{2} + 5x - 2$ \\
(d) The curve $y = f(0.2x)$ meets the $y$-axis where $x = 0$: \\
$y = f(0) = 6$ \\
So $(0, 6)$ \\
It meets the $x$-axis where $f(0.2x) = 0$. Use the factorised form with $x$ replaced by $0.2x$: \\
$(0.2x - 3)Q(0.2x) = 0$ \\
First factor: \\
$0.2x - 3 = 0$ \\
$0.2x = 3$ \\
$x = 15$ \\
Second factor: $Q(0.2x) = 0$. Let $u = 0.2x$, so $-4u^{2} + 5u - 2 = 0$ \\
Discriminant: $5^{2} - 4(-4)(-2) = 25 - 32 = -7$ \\
This is negative, so there are no real solutions \\
The curve meets the axes at $(0, 6)$ and $(15, 0)$
