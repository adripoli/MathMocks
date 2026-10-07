@paper P2 June 2026

@q 1
@topic Factor theorem, find k
@marks 3
@question
Factor theorem: if $(x - 2)$ is a factor of $\mathrm{g}(x)$, then $\mathrm{g}(2) = 0$ \\
Substitute $x = 2$ into $\mathrm{g}(x)$: \\
$\mathrm{g}(2) = 2^{3} - (2k + 14)(2)^{2} + (k + 8)(2) + 14$ \\
Work out the powers of 2: \\
$= 8 - 4(2k + 14) + 2(k + 8) + 14$ \\
Expand the brackets: \\
$= 8 - 8k - 56 + 2k + 16 + 14$ \\
Collect the $k$ terms and the numbers separately: \\
$= (-8k + 2k) + (8 - 56 + 16 + 14)$ \\
$= -6k - 18$ \\
Set $\mathrm{g}(2) = 0$: \\
$-6k - 18 = 0$ \\
Add 18 to both sides: \\
$-6k = 18$ \\
Divide both sides by $-6$: \\
$k = -3$ \\
(Check: with $k = -3$, $\mathrm{g}(x) = x^{3} - 8x^{2} + 5x + 14$) \\
(Check: $\mathrm{g}(2) = 8 - 32 + 10 + 14 = 0$)

@q 2
@topic Trapezium rule and integration
@marks 6
@question
(a) There are 5 values of $y$, so there are 4 strips of equal width \\
Strip width: \\
$h = \frac{0.8 - 0.6}{4}$ \\
$= \frac{0.2}{4}$ \\
$= 0.05$ \\
Trapezium rule: \\
$\int_{a}^{b} y dx \approx \frac{h}{2} \{ y_{0} + y_{n} + 2(y_{1} + y_{2} + \ldots) \}$ \\
First plus last $y$ values: \\
$11.1 + 24.5 = 35.6$ \\
Middle $y$ values, added together: \\
$13.5 + 16.4 + 20.1 = 50$ \\
Double the middle sum: \\
$2 \times 50 = 100$ \\
Put these into the rule: \\
$\int_{0.6}^{0.8} \mathrm{f}(x) dx \approx \frac{0.05}{2} \{ 35.6 + 100 \}$ \\
$= 0.025 \times 135.6$ \\
$= 3.39$ \\
(b) Split the integral into three pieces: \\
$\int_{0.6}^{0.8} \left( \mathrm{f}(x) + 5x^{\frac{3}{2}} + 3 \right) dx$ \\
$= \int_{0.6}^{0.8} \mathrm{f}(x) dx$ \\
$+ \int_{0.6}^{0.8} 5x^{\frac{3}{2}} dx$ \\
$+ \int_{0.6}^{0.8} 3 dx$ \\
Piece 1 is the estimate from part (a): \\
$\int_{0.6}^{0.8} \mathrm{f}(x) dx \approx 3.39$ \\
Piece 2: add 1 to the power, divide by the new power \\
New power: $\frac{3}{2} + 1 = \frac{5}{2}$ \\
$\int 5x^{\frac{3}{2}} dx = 5 \times \frac{x^{\frac{5}{2}}}{\frac{5}{2}}$ \\
Dividing by $\frac{5}{2}$ is multiplying by $\frac{2}{5}$: \\
$= 5 \times \frac{2}{5} x^{\frac{5}{2}}$ \\
$= 2x^{\frac{5}{2}}$ \\
Upper limit $x = 0.8$: \\
$2(0.8)^{\frac{5}{2}} = 2 \times 0.5724334$ \\
$= 1.1448668$ \\
Lower limit $x = 0.6$: \\
$2(0.6)^{\frac{5}{2}} = 2 \times 0.2788548$ \\
$= 0.5577096$ \\
Upper minus lower: \\
$1.1448668 - 0.5577096 = 0.5871572$ \\
Piece 3: $\int 3 dx = 3x$ \\
Upper limit: $3(0.8) = 2.4$ \\
Lower limit: $3(0.6) = 1.8$ \\
Upper minus lower: \\
$2.4 - 1.8 = 0.6$ \\
Add the three pieces: \\
$3.39 + 0.5871572 + 0.6$ \\
$= 4.5771572$ \\
$\int_{0.6}^{0.8} \left( \mathrm{f}(x) + 5x^{\frac{3}{2}} + 3 \right) dx \approx 4.577$ to 4 significant figures

@q 3
@topic Arithmetic series, largest sum
@marks 8
@question
(a) Sum of the first $n$ terms of an arithmetic series: \\
$S_{n} = \frac{n}{2} \{ 2a + (n - 1)d \}$ \\
Put $n = 65$ and $S_{65} = 4940$: \\
$4940 = \frac{65}{2} \{ 2a + 64d \}$ \\
Take a factor of 2 out of the bracket: \\
$2a + 64d = 2(a + 32d)$ \\
$4940 = \frac{65}{2} \times 2(a + 32d)$ \\
Cancel the 2s: \\
$4940 = 65(a + 32d)$ \\
Divide both sides by 65: \\
$76 = a + 32d$ \\
$a + 32d = 76$ as required \\
(b) The $n$th term is $a + (n - 1)d$ \\
Put $n = 49$ and the 49th term equal to 64: \\
$a + 48d = 64$ \\
(c) Subtract the equation from part (a) from the equation in part (b): \\
$(a + 48d) - (a + 32d) = 64 - 76$ \\
$16d = -12$ \\
Divide both sides by 16: \\
$d = -\frac{12}{16}$ \\
$d = -\frac{3}{4}$ \\
Substitute $d = -\frac{3}{4}$ into $a + 32d = 76$: \\
$a + 32 \times \left( -\frac{3}{4} \right) = 76$ \\
$a - 24 = 76$ \\
Add 24 to both sides: \\
$a = 100$ \\
(Check: $a + 48d = 100 - 36 = 64$) \\
(d) The terms go down by $\frac{3}{4}$ each time, so the terms eventually become negative \\
$S_{n}$ is largest when we add up all the positive terms and stop before the first negative term \\
The $n$th term is $100 + (n - 1) \left( -\frac{3}{4} \right)$ \\
We need the $n$th term to be positive: \\
$100 - \frac{3}{4}(n - 1) > 0$ \\
Multiply both sides by 4: \\
$400 - 3(n - 1) > 0$ \\
Expand the bracket: \\
$400 - 3n + 3 > 0$ \\
$403 - 3n > 0$ \\
Add $3n$ to both sides: \\
$403 > 3n$ \\
Divide both sides by 3: \\
$n < 134.33...$ \\
$n$ is a whole number, so the last positive term is the 134th \\
(Check: 134th term $= 100 - \frac{3}{4}(133) = 0.25$, which is positive) \\
(Check: 135th term $= 100 - \frac{3}{4}(134) = -0.5$, which is negative) \\
Now work out $S_{134}$: \\
$S_{134} = \frac{134}{2} \{ 2(100) + 133 \left( -\frac{3}{4} \right) \}$ \\
$= 67 \{ 200 - 99.75 \}$ \\
$= 67 \times 100.25$ \\
Split $100.25$ into $100 + 0.25$: \\
$= 67 \times 100 + 67 \times 0.25$ \\
$= 6700 + 16.75$ \\
$= 6716.75$ \\
The largest possible positive value of $S_{n}$ is $6716.75$

@q 4
@topic Recurrence relation, find k
@marks 6
@question
(a) Find $u_{2}$ by putting $n = 1$ and $u_{1} = k$: \\
$u_{2} = 3(u_{1})^{2} - 1$ \\
$= 3k^{2} - 1$ \\
Find $u_{3}$ by putting $n = 2$: \\
$u_{3} = 3(u_{2})^{2} - 1$ \\
Replace $u_{2}$ by $3k^{2} - 1$: \\
$= 3(3k^{2} - 1)^{2} - 1$ \\
Expand the square: \\
$(3k^{2} - 1)^{2} = (3k^{2} - 1)(3k^{2} - 1)$ \\
$= 9k^{4} - 3k^{2} - 3k^{2} + 1$ \\
$= 9k^{4} - 6k^{2} + 1$ \\
Multiply by 3: \\
$3(9k^{4} - 6k^{2} + 1) = 27k^{4} - 18k^{2} + 3$ \\
Subtract 1: \\
$u_{3} = 27k^{4} - 18k^{2} + 3 - 1$ \\
$u_{3} = 27k^{4} - 18k^{2} + 2$ as required \\
(b) Put the two expressions into $u_{3} - 5u_{2} = 11$: \\
$27k^{4} - 18k^{2} + 2 - 5(3k^{2} - 1) = 11$ \\
Expand the bracket: \\
$27k^{4} - 18k^{2} + 2 - 15k^{2} + 5 = 11$ \\
Collect like terms: \\
$27k^{4} - 33k^{2} + 7 = 11$ \\
Subtract 11 from both sides: \\
$27k^{4} - 33k^{2} - 4 = 0$ \\
Let $m = k^{2}$ to get a quadratic: \\
$27m^{2} - 33m - 4 = 0$ \\
Two numbers that multiply to $27 \times (-4) = -108$ and add to $-33$ are $-36$ and $3$ \\
Split the middle term: \\
$27m^{2} - 36m + 3m - 4 = 0$ \\
Factorise in pairs: \\
$9m(3m - 4) + 1(3m - 4) = 0$ \\
$(9m + 1)(3m - 4) = 0$ \\
$m = -\frac{1}{9}$ or $m = \frac{4}{3}$ \\
Replace $m$ by $k^{2}$: \\
$k^{2} = -\frac{1}{9}$ has no real solutions, since a real number squared cannot be negative \\
$k^{2} = \frac{4}{3}$ \\
Square root both sides, keeping both signs: \\
$k = \pm \sqrt{\frac{4}{3}}$ \\
$= \pm \frac{2}{\sqrt{3}}$ \\
Multiply the top and bottom by $\sqrt{3}$ to rationalise: \\
$= \pm \frac{2\sqrt{3}}{3}$ \\
$k = \frac{2\sqrt{3}}{3}$ or $k = -\frac{2\sqrt{3}}{3}$

@q 5
@topic Trig model, harbour depth
@marks 6
@question
(a) 3:00 am is $t = 3$, so $30t = 90$ and the depth is 10 \\
$10 = a + b \sin 90$ degrees \\
$\sin 90$ degrees $= 1$, so: \\
Equation 1: $a + b = 10$ \\
5:00 am is $t = 5$, so $30t = 150$ and the depth is 8.5 \\
$8.5 = a + b \sin 150$ degrees \\
$\sin 150$ degrees $= \sin 30$ degrees $= \frac{1}{2}$, so: \\
Equation 2: $a + \frac{1}{2}b = 8.5$ \\
Subtract equation 2 from equation 1 to remove $a$: \\
$(a + b) - \left( a + \frac{1}{2}b \right) = 10 - 8.5$ \\
$\frac{1}{2}b = 1.5$ \\
Multiply both sides by 2: \\
$b = 3$ \\
Substitute $b = 3$ into $a + b = 10$: \\
$a + 3 = 10$ \\
Subtract 3 from both sides: \\
$a = 7$ \\
(Check: $7 + \frac{1}{2}(3) = 8.5$) \\
$D = 7 + 3 \sin (30t)$ degrees \\
(b) $\sin (30t)$ swings between $-1$ and $1$ \\
So $D$ swings between $7 - 3 = 4$ and $7 + 3 = 10$, centred on 7 \\
$a = 7$ is the mean (average) depth of the water in the harbour, in metres \\
(c) 10:30 am is $t = 10.5$, so $30t = 315$ \\
$D = 7 + 3 \sin 315$ degrees \\
$\sin 315$ degrees $= -\sin 45$ degrees $= -\frac{\sqrt{2}}{2}$ \\
$D = 7 + 3 \times \left( -\frac{\sqrt{2}}{2} \right)$ \\
$= 7 - \frac{3\sqrt{2}}{2}$ \\
$= 7 - 2.1213$ \\
$= 4.8787$ \\
The model gives 4.88 m, and the real depth was 4.9 m \\
These are very close (they differ by only about 0.02 m), so the model is a good fit and is suitable for this harbour

@q 6
@topic Differentiation from first principles
@marks 4
@question
Let $\mathrm{f}(x) = 5x^{3}$ \\
First principles: \\
$\frac{dy}{dx} = \lim_{h \to 0} \frac{\mathrm{f}(x + h) - \mathrm{f}(x)}{h}$ \\
Work out $\mathrm{f}(x + h)$: \\
$\mathrm{f}(x + h) = 5(x + h)^{3}$ \\
Expand $(x + h)^{3}$ in two steps. First the square: \\
$(x + h)^{2} = x^{2} + 2xh + h^{2}$ \\
Now multiply by $(x + h)$: \\
$(x + h)(x^{2} + 2xh + h^{2})$ \\
$= x^{3} + 2x^{2}h + xh^{2} + x^{2}h + 2xh^{2} + h^{3}$ \\
$= x^{3} + 3x^{2}h + 3xh^{2} + h^{3}$ \\
Multiply by 5: \\
$\mathrm{f}(x + h) = 5x^{3} + 15x^{2}h + 15xh^{2} + 5h^{3}$ \\
Subtract $\mathrm{f}(x) = 5x^{3}$: \\
$\mathrm{f}(x + h) - \mathrm{f}(x) = 15x^{2}h + 15xh^{2} + 5h^{3}$ \\
Divide every term by $h$: \\
$\frac{\mathrm{f}(x + h) - \mathrm{f}(x)}{h} = 15x^{2} + 15xh + 5h^{2}$ \\
Now let $h \to 0$. The terms $15xh$ and $5h^{2}$ both go to 0: \\
$\frac{dy}{dx} = 15x^{2}$ as required

@q 7
@topic Angle between two vectors
@marks 4
@question
Angle $BAC$ is the angle between $\text{AB}$ and $\text{AC}$, both of which start at $A$ \\
Use the scalar product: \\
$\text{AB} \cdot \text{AC} = |\text{AB}| |\text{AC}| \cos (BAC)$ \\
Scalar product: multiply the matching components and add: \\
$\text{AB} \cdot \text{AC} = (4)(3) + (-3)(5) + (-1)(2)$ \\
$= 12 - 15 - 2$ \\
$= -5$ \\
Length of $\text{AB}$: \\
$|\text{AB}| = \sqrt{4^{2} + (-3)^{2} + (-1)^{2}}$ \\
$= \sqrt{16 + 9 + 1}$ \\
$= \sqrt{26}$ \\
Length of $\text{AC}$: \\
$|\text{AC}| = \sqrt{3^{2} + 5^{2} + 2^{2}}$ \\
$= \sqrt{9 + 25 + 4}$ \\
$= \sqrt{38}$ \\
Put these into the scalar product formula: \\
$-5 = \sqrt{26} \times \sqrt{38} \times \cos (BAC)$ \\
Divide both sides by $\sqrt{26} \times \sqrt{38}$: \\
$\cos (BAC) = \frac{-5}{\sqrt{26} \times \sqrt{38}}$ \\
$= \frac{-5}{\sqrt{988}}$ \\
$= \frac{-5}{31.4325}$ \\
$= -0.159071$ \\
Take the inverse cosine: \\
$BAC = \cos^{-1} (-0.159071)$ \\
$= 99.153$ degrees \\
(The cosine is negative, so the angle is obtuse) \\
Angle $BAC = 99.2$ degrees (1 decimal place)

@q 8
@topic Exponential model, mass of compound
@marks 7
@question
(a) At the start, $t = 0$ and $M = 25$: \\
$25 = \frac{200}{5 + k\mathrm{e}^{0}}$ \\
$\mathrm{e}^{0} = 1$, so: \\
$25 = \frac{200}{5 + k}$ \\
Multiply both sides by $(5 + k)$: \\
$25(5 + k) = 200$ \\
Divide both sides by 25: \\
$5 + k = 8$ \\
Subtract 5 from both sides: \\
$k = 3$ \\
$M = \frac{200}{5 + 3\mathrm{e}^{-0.15t}}$ \\
(b) Put $t = T$ and $M = 35$: \\
$35 = \frac{200}{5 + 3\mathrm{e}^{-0.15T}}$ \\
Multiply both sides by $(5 + 3\mathrm{e}^{-0.15T})$: \\
$35(5 + 3\mathrm{e}^{-0.15T}) = 200$ \\
Divide both sides by 35: \\
$5 + 3\mathrm{e}^{-0.15T} = \frac{200}{35}$ \\
Simplify the fraction (divide top and bottom by 5): \\
$5 + 3\mathrm{e}^{-0.15T} = \frac{40}{7}$ \\
Subtract 5 from both sides, writing 5 as $\frac{35}{7}$: \\
$3\mathrm{e}^{-0.15T} = \frac{40}{7} - \frac{35}{7}$ \\
$3\mathrm{e}^{-0.15T} = \frac{5}{7}$ \\
Divide both sides by 3: \\
$\mathrm{e}^{-0.15T} = \frac{5}{21}$ \\
Take natural logs of both sides: \\
$-0.15T = \ln \left( \frac{5}{21} \right)$ \\
Use $\ln \left( \frac{5}{21} \right) = -\ln \left( \frac{21}{5} \right)$: \\
$-0.15T = -\ln \left( \frac{21}{5} \right)$ \\
Divide both sides by $-0.15$: \\
$T = \frac{\ln 4.2}{0.15}$ \\
$= \frac{1.43508}{0.15}$ \\
$= 9.5672$ \\
$T = 9.57$ minutes (3 significant figures) \\
(Check: $\frac{200}{5 + 3\mathrm{e}^{-0.15(9.5672)}} = 35.0$) \\
(c) As $t$ gets very large, $-0.15t$ gets very negative \\
So $\mathrm{e}^{-0.15t}$ gets closer and closer to 0 \\
Then $3\mathrm{e}^{-0.15t}$ also gets closer to 0, and the denominator gets closer to 5 \\
$M \to \frac{200}{5 + 0}$ \\
$M \to 40$ \\
$L = 40$ grams \\
Reason: as $t \to \infty$, $\mathrm{e}^{-0.15t} \to 0$, so $M$ approaches 40 but never goes above it, because the denominator is always bigger than 5

@q 9
@topic Log model, UK coal mined
@marks 7
@question
(a) Take $\log_{10}$ of both sides of $L = ab^{t}$: \\
$\log_{10} L = \log_{10} (ab^{t})$ \\
Use the product law $\log (xy) = \log x + \log y$: \\
$\log_{10} L = \log_{10} a + \log_{10} (b^{t})$ \\
Use the power law $\log (x^{n}) = n \log x$: \\
$\log_{10} L = \log_{10} a + t \log_{10} b$ \\
Write it in the form of a straight line: \\
$\log_{10} L = (\log_{10} b) t + \log_{10} a$ \\
Compare with $Y = mX + c$, where $Y = \log_{10} L$ and $X = t$: \\
- gradient $= \log_{10} b = 0.0108$ \\
- intercept $= \log_{10} a = 0.304$ \\
For $b$: raise 10 to the power of both sides: \\
$b = 10^{0.0108}$ \\
$= 1.02518$ \\
$b = 1.025$ (3 decimal places) \\
For $a$: raise 10 to the power of both sides: \\
$a = 10^{0.304}$ \\
$= 2.01372$ \\
$a = 2.014$ (3 decimal places) \\
$L = 2.014 \times 1.025^{t}$ \\
(b) When $t = 0$ (the year 1700), $L = ab^{0} = a$ \\
So $a = 2.014$ is the amount of coal mined in the UK in 1700, which is about 2.014 million tonnes \\
(c) The year 2000 is $t = 300$ \\
Use the unrounded values, because 300 is a big power and rounding $b$ would change the answer a lot: \\
$\log_{10} L = 0.304 + 0.0108 \times 300$ \\
$= 0.304 + 3.24$ \\
$= 3.544$ \\
Raise 10 to the power of both sides: \\
$L = 10^{3.544}$ \\
$= 3499.45$ \\
$L = 3500$ million tonnes (3 significant figures) \\
(Using the rounded $a$ and $b$ instead gives about 3321, so keep the unrounded values) \\
(d) The data used to build the model only covers 1700 to 1900 \\
The year 2000 is well outside that range, so the estimate is an extrapolation and is not reliable

@q 10
@topic Partial fractions, binomial expansion
@marks 10
@question
(a) Multiply both sides by $(1 - x)(1 - 2x)$: \\
$4x^{2} - x + 1 \equiv A(1 - x)(1 - 2x) + B(1 - 2x) + C(1 - x)$ \\
Expand $(1 - x)(1 - 2x)$: \\
$= 1 - 2x - x + 2x^{2}$ \\
$= 2x^{2} - 3x + 1$ \\
So the identity is: \\
$4x^{2} - x + 1 \equiv A(2x^{2} - 3x + 1) + B(1 - 2x) + C(1 - x)$ \\
Compare the coefficients of $x^{2}$: \\
$4 = 2A$ \\
Divide both sides by 2: \\
$A = 2$ \\
Substitute $x = 1$, which makes the bracket $(1 - x)$ equal to 0: \\
Left side: $4(1)^{2} - 1 + 1 = 4$ \\
Right side: $A(0) + B(1 - 2) + C(0) = -B$ \\
$4 = -B$ \\
$B = -4$ \\
Substitute $x = \frac{1}{2}$, which makes the bracket $(1 - 2x)$ equal to 0: \\
Left side: $4 \left( \frac{1}{2} \right)^{2} - \frac{1}{2} + 1$ \\
$= 1 - \frac{1}{2} + 1$ \\
$= \frac{3}{2}$ \\
Right side: $A(0) + B(0) + C \left( 1 - \frac{1}{2} \right) = \frac{1}{2}C$ \\
$\frac{3}{2} = \frac{1}{2}C$ \\
Multiply both sides by 2: \\
$C = 3$ \\
(Check the constant terms: $A + B + C = 2 - 4 + 3 = 1$, which matches the 1 on the left) \\
$A = 2$, $B = -4$, $C = 3$ \\
(b) Use the partial fractions from part (a): \\
$\frac{4x^{2} - x + 1}{(1 - x)(1 - 2x)} = 2 - \frac{4}{1 - x} + \frac{3}{1 - 2x}$ \\
Write the fractions as negative powers: \\
$= 2 - 4(1 - x)^{-1} + 3(1 - 2x)^{-1}$ \\
Binomial expansion with power $-1$: \\
$(1 + z)^{-1} = 1 + (-1)z + \frac{(-1)(-2)}{2}z^{2} + \ldots$ \\
$= 1 - z + z^{2} - \ldots$ \\
For $(1 - x)^{-1}$ put $z = -x$: \\
$(1 - x)^{-1} = 1 - (-x) + (-x)^{2}$ \\
$= 1 + x + x^{2}$ \\
For $(1 - 2x)^{-1}$ put $z = -2x$: \\
$(1 - 2x)^{-1} = 1 - (-2x) + (-2x)^{2}$ \\
$= 1 + 2x + 4x^{2}$ \\
Multiply the first expansion by $-4$: \\
$-4(1 + x + x^{2}) = -4 - 4x - 4x^{2}$ \\
Multiply the second expansion by 3: \\
$3(1 + 2x + 4x^{2}) = 3 + 6x + 12x^{2}$ \\
Add these to the 2: \\
$2 + (-4 - 4x - 4x^{2}) + (3 + 6x + 12x^{2})$ \\
Collect the numbers: $2 - 4 + 3 = 1$ \\
Collect the $x$ terms: $-4x + 6x = 2x$ \\
Collect the $x^{2}$ terms: $-4x^{2} + 12x^{2} = 8x^{2}$ \\
$\frac{4x^{2} - x + 1}{(1 - x)(1 - 2x)} = 1 + 2x + 8x^{2} + \ldots$ \\
(c) $(1 - x)^{-1}$ is valid when $|x| < 1$ \\
$(1 - 2x)^{-1}$ is valid when $|2x| < 1$, which means $|x| < \frac{1}{2}$ \\
Both must hold, so the stricter one wins: \\
$|x| < \frac{1}{2}$ \\
$-\frac{1}{2} < x < \frac{1}{2}$

@q 11
@topic Integration by substitution
@marks 8
@question
(a) The substitution is $u = \sqrt{5x - 2}$ \\
Square both sides: \\
$u^{2} = 5x - 2$ \\
Differentiate both sides with respect to $x$: \\
$2u \frac{du}{dx} = 5$ \\
Divide both sides by $2u$ and then flip: \\
$\frac{du}{dx} = \frac{5}{2u}$ \\
$\frac{dx}{du} = \frac{2u}{5}$ \\
$dx = \frac{2u}{5} du$ \\
Change the limits using $u = \sqrt{5x - 2}$: \\
When $x = \frac{3}{5}$: $u = \sqrt{5 \times \frac{3}{5} - 2}$ \\
$= \sqrt{3 - 2}$ \\
$= \sqrt{1}$ \\
$= 1$ \\
When $x = \frac{27}{5}$: $u = \sqrt{5 \times \frac{27}{5} - 2}$ \\
$= \sqrt{27 - 2}$ \\
$= \sqrt{25}$ \\
$= 5$ \\
Replace $\sqrt{5x - 2}$ by $u$, $dx$ by $\frac{2u}{5} du$, and use the new limits: \\
$\int_{1}^{5} \frac{1}{3 + u} \times \frac{2u}{5} du$ \\
Take the constant $\frac{2}{5}$ outside: \\
$= \frac{2}{5} \int_{1}^{5} \frac{u}{3 + u} du$ \\
So $k = \frac{2}{5}$, $p = 1$ and $q = 5$ (and $q > p$, as required) \\
(b) Write the top as $u = (3 + u) - 3$ so that we can divide: \\
$\frac{u}{3 + u} = \frac{(3 + u) - 3}{3 + u}$ \\
Split into two fractions: \\
$= \frac{3 + u}{3 + u} - \frac{3}{3 + u}$ \\
$= 1 - \frac{3}{3 + u}$ \\
Integrate each term ($\int \frac{1}{3 + u} du = \ln (3 + u)$, as $3 + u$ is positive): \\
$\int \frac{u}{3 + u} du = u - 3 \ln (3 + u)$ \\
Upper limit $u = 5$: \\
$5 - 3 \ln (3 + 5)$ \\
$= 5 - 3 \ln 8$ \\
Lower limit $u = 1$: \\
$1 - 3 \ln (3 + 1)$ \\
$= 1 - 3 \ln 4$ \\
Upper minus lower: \\
$\int_{1}^{5} \frac{u}{3 + u} du = (5 - 3 \ln 8) - (1 - 3 \ln 4)$ \\
$= 5 - 3 \ln 8 - 1 + 3 \ln 4$ \\
$= 4 - 3 \ln 8 + 3 \ln 4$ \\
Write $8 = 2^{3}$ and $4 = 2^{2}$, then use $\ln (a^{n}) = n \ln a$: \\
$\ln 8 = \ln 2^{3} = 3 \ln 2$ \\
$\ln 4 = \ln 2^{2} = 2 \ln 2$ \\
$= 4 - 3(3 \ln 2) + 3(2 \ln 2)$ \\
$= 4 - 9 \ln 2 + 6 \ln 2$ \\
$= 4 - 3 \ln 2$ \\
Multiply by the $\frac{2}{5}$ from part (a): \\
$\int_{\frac{3}{5}}^{\frac{27}{5}} \frac{1}{3 + \sqrt{5x - 2}} dx = \frac{2}{5}(4 - 3 \ln 2)$ \\
Expand the bracket: \\
$= \frac{8}{5} - \frac{6}{5} \ln 2$ \\
This is $A + B \ln 2$ with $A = \frac{8}{5}$ and $B = -\frac{6}{5}$ as required

@q 12
@topic Parametric curve, normal, intersection
@marks 11
@question
(a) Put $t = \frac{\pi}{4}$ into each equation \\
$x = 1 - \cos \frac{\pi}{2}$ \\
$= 1 - 0$ \\
$= 1$ \\
$y = \sin \frac{\pi}{4} \sin \frac{\pi}{2}$ \\
$= \frac{\sqrt{2}}{2} \times 1$ \\
$= \frac{\sqrt{2}}{2}$ \\
$P$ is the point $\left( 1, \frac{\sqrt{2}}{2} \right)$ \\
(b) Differentiate $x = 1 - \cos 2t$ with respect to $t$: \\
$\frac{dx}{dt} = 2 \sin 2t$ \\
Differentiate $y = \sin t \sin 2t$ using the product rule with $u = \sin t$ and $v = \sin 2t$: \\
$u' = \cos t$ and $v' = 2 \cos 2t$ \\
$\frac{dy}{dt} = u'v + uv'$ \\
$= \cos t \sin 2t + 2 \sin t \cos 2t$ \\
At $t = \frac{\pi}{4}$ we have $2t = \frac{\pi}{2}$, so: \\
$\sin 2t = 1$, $\cos 2t = 0$, $\sin t = \cos t = \frac{\sqrt{2}}{2}$ \\
$\frac{dx}{dt} = 2(1) = 2$ \\
$\frac{dy}{dt} = \frac{\sqrt{2}}{2}(1) + 2 \times \frac{\sqrt{2}}{2} \times 0$ \\
$= \frac{\sqrt{2}}{2}$ \\
Parametric differentiation: \\
$\frac{dy}{dx} = \frac{dy}{dt} \div \frac{dx}{dt}$ \\
$= \frac{\sqrt{2}}{2} \div 2$ \\
$= \frac{\sqrt{2}}{4}$ \\
The normal is perpendicular to the tangent, so its gradient is $-1$ divided by the tangent gradient: \\
$m = -1 \div \frac{\sqrt{2}}{4}$ \\
$= -\frac{4}{\sqrt{2}}$ \\
Multiply the top and bottom by $\sqrt{2}$ to rationalise: \\
$= -\frac{4\sqrt{2}}{2}$ \\
$= -2\sqrt{2}$ \\
Equation of the line through $P \left( 1, \frac{\sqrt{2}}{2} \right)$: \\
$y - \frac{\sqrt{2}}{2} = -2\sqrt{2}(x - 1)$ \\
Multiply every term by $\sqrt{2}$: \\
$\sqrt{2}y - \frac{\sqrt{2} \times \sqrt{2}}{2} = -2\sqrt{2} \times \sqrt{2}(x - 1)$ \\
Use $\sqrt{2} \times \sqrt{2} = 2$: \\
$\sqrt{2}y - 1 = -4(x - 1)$ \\
Expand the bracket: \\
$\sqrt{2}y - 1 = -4x + 4$ \\
Add $4x$ and add 1 to both sides: \\
$4x + \sqrt{2}y = 5$ \\
This is $ax + \sqrt{2}y = b$ with $a = 4$ and $b = 5$ \\
(c) Rearrange the line for $\sqrt{2}y$: \\
$\sqrt{2}y = 5 - 4x$ \\
Square both sides: \\
$2y^{2} = (5 - 4x)^{2}$ \\
The curve has $2y^{2} = x^{2}(2 - x)$, so: \\
$(5 - 4x)^{2} = x^{2}(2 - x)$ \\
Expand the left side: \\
$25 - 40x + 16x^{2} = x^{2}(2 - x)$ \\
Expand the right side: \\
$25 - 40x + 16x^{2} = 2x^{2} - x^{3}$ \\
Add $x^{3}$ and subtract $2x^{2}$ on both sides: \\
$x^{3} + 14x^{2} - 40x + 25 = 0$ \\
$P$ is on both $l$ and $C$, so $x = 1$ is a root. Check: \\
$1 + 14 - 40 + 25 = 0$ \\
So $(x - 1)$ is a factor. Divide the cubic by $(x - 1)$: \\
$x^{3} + 14x^{2} - 40x + 25 = (x - 1)(x^{2} + 15x - 25)$ \\
(Check: $(x - 1)(x^{2} + 15x - 25) = x^{3} + 15x^{2} - 25x - x^{2} - 15x + 25$) \\
(Check: $= x^{3} + 14x^{2} - 40x + 25$) \\
Solve $x^{2} + 15x - 25 = 0$ with the quadratic formula: \\
$x = \frac{-15 \pm \sqrt{15^{2} - 4(1)(-25)}}{2}$ \\
$= \frac{-15 \pm \sqrt{225 + 100}}{2}$ \\
$= \frac{-15 \pm \sqrt{325}}{2}$ \\
Simplify the surd: $\sqrt{325} = \sqrt{25 \times 13} = 5\sqrt{13}$ \\
$x = \frac{-15 \pm 5\sqrt{13}}{2}$ \\
On $C$, $x = 1 - \cos 2t$ and $\cos 2t$ is between $-1$ and $1$, so $0 \leq x \leq 2$ \\
$x = \frac{-15 - 5\sqrt{13}}{2} = -16.5$ is not in this range, so reject it \\
$x = \frac{-15 + 5\sqrt{13}}{2} = 1.514$ is in the range \\
The $x$ coordinate of $Q$ is $\frac{-15 + 5\sqrt{13}}{2}$

@q 13
@topic Implicit differentiation, normal
@marks 8
@question
(a) Differentiate every term with respect to $x$ \\
$x^{2}$ gives $2x$ \\
$-2y^{2}$ gives $-4y \frac{dy}{dx}$ \\
$-xy$ needs the product rule: it gives $-\left( y + x \frac{dy}{dx} \right)$ \\
$-x$ gives $-1$ \\
$5y$ gives $5 \frac{dy}{dx}$ \\
The constant 79 gives 0 \\
Put these together: \\
$2x - 4y \frac{dy}{dx} - y - x \frac{dy}{dx} - 1 + 5 \frac{dy}{dx} = 0$ \\
Move every term without $\frac{dy}{dx}$ to the right side: \\
$-4y \frac{dy}{dx} - x \frac{dy}{dx} + 5 \frac{dy}{dx} = -2x + y + 1$ \\
Factorise out $\frac{dy}{dx}$ on the left: \\
$(5 - x - 4y) \frac{dy}{dx} = y + 1 - 2x$ \\
Divide both sides by $(5 - x - 4y)$: \\
$\frac{dy}{dx} = \frac{y + 1 - 2x}{5 - x - 4y}$ \\
(b) Substitute $x = 1 + 6\sqrt{2}$ and $y = 10 - \frac{3\sqrt{2}}{2}$ \\
Top: $y + 1 - 2x$ \\
$= 10 - \frac{3\sqrt{2}}{2} + 1 - 2(1 + 6\sqrt{2})$ \\
Expand the bracket: \\
$= 10 - \frac{3\sqrt{2}}{2} + 1 - 2 - 12\sqrt{2}$ \\
Collect the numbers and the surds: \\
$= (10 + 1 - 2) - \left( \frac{3}{2} + 12 \right) \sqrt{2}$ \\
$= 9 - \frac{27}{2}\sqrt{2}$ \\
Bottom: $5 - x - 4y$ \\
$= 5 - (1 + 6\sqrt{2}) - 4 \left( 10 - \frac{3\sqrt{2}}{2} \right)$ \\
Expand the brackets: \\
$= 5 - 1 - 6\sqrt{2} - 40 + 6\sqrt{2}$ \\
The surds cancel: \\
$= 5 - 1 - 40$ \\
$= -36$ \\
Gradient of the tangent at $P$: \\
$\frac{dy}{dx} = \frac{9 - \frac{27}{2}\sqrt{2}}{-36}$ \\
Divide each term on top by $-36$: \\
$= -\frac{9}{36} + \frac{27}{72}\sqrt{2}$ \\
Simplify each fraction: \\
$= -\frac{1}{4} + \frac{3}{8}\sqrt{2}$ \\
Write over a common denominator of 8: \\
$= \frac{-2 + 3\sqrt{2}}{8}$ \\
The normal gradient is $-1$ divided by the tangent gradient: \\
$m = -1 \div \frac{3\sqrt{2} - 2}{8}$ \\
$= -\frac{8}{3\sqrt{2} - 2}$ \\
Rationalise: multiply the top and bottom by $(3\sqrt{2} + 2)$: \\
$= -\frac{8(3\sqrt{2} + 2)}{(3\sqrt{2} - 2)(3\sqrt{2} + 2)}$ \\
Bottom, using $(p - q)(p + q) = p^{2} - q^{2}$: \\
$(3\sqrt{2})^{2} - 2^{2} = 18 - 4 = 14$ \\
Top: $-8(3\sqrt{2} + 2) = -24\sqrt{2} - 16$ \\
$m = \frac{-24\sqrt{2} - 16}{14}$ \\
Divide the top and bottom by 2: \\
$= \frac{-12\sqrt{2} - 8}{7}$ \\
Split into two fractions: \\
$= -\frac{8}{7} - \frac{12}{7}\sqrt{2}$ \\
This is $a + b\sqrt{2}$ with $a = -\frac{8}{7}$ and $b = -\frac{12}{7}$ as required

@q 14
@topic Differentiate 6^(-3x), exact x
@marks 4
@question
(a) Write the number 6 as $\mathrm{e}^{\ln 6}$, so that $6^{-3x}$ is a power of $\mathrm{e}$: \\
$6^{-3x} = (\mathrm{e}^{\ln 6})^{-3x}$ \\
Multiply the powers: \\
$= \mathrm{e}^{-3x \ln 6}$ \\
$y = \mathrm{e}^{(-3 \ln 6)x}$ \\
$\ln 6$ is just a number, so $-3 \ln 6$ is a constant. Use $\frac{d}{dx} \mathrm{e}^{kx} = k\mathrm{e}^{kx}$: \\
$\frac{dy}{dx} = -3 \ln 6 \times \mathrm{e}^{-3x \ln 6}$ \\
Change back to base 6: \\
$\frac{dy}{dx} = -3 \ln 6 \times 6^{-3x}$ \\
(b) Put $\frac{dy}{dx} = -1$: \\
$-3 \ln 6 \times 6^{-3x} = -1$ \\
Divide both sides by $-3 \ln 6$: \\
$6^{-3x} = \frac{1}{3 \ln 6}$ \\
Take natural logs of both sides: \\
$\ln (6^{-3x}) = \ln \left( \frac{1}{3 \ln 6} \right)$ \\
Use the power law on the left: \\
$-3x \ln 6 = \ln \left( \frac{1}{3 \ln 6} \right)$ \\
Use $\ln \left( \frac{1}{A} \right) = -\ln A$ on the right: \\
$-3x \ln 6 = -\ln (3 \ln 6)$ \\
Divide both sides by $-3 \ln 6$: \\
$x = \frac{\ln (3 \ln 6)}{3 \ln 6}$ \\
(Check: $x = \frac{1.68181}{5.37528} = 0.31288$) \\
(Check: $-3 \ln 6 \times 6^{-3(0.31288)} = -5.37528 \times 0.18604 = -1.0000$)

@q 15
@topic Circle and line, set notation
@marks 8
@question
(a) Group the $x$ terms and the $y$ terms: \\
$(x^{2} + 6x) + (y^{2} - 4y) - 62 = 0$ \\
Complete the square for $x$: \\
$x^{2} + 6x = (x + 3)^{2} - 9$ \\
Complete the square for $y$: \\
$y^{2} - 4y = (y - 2)^{2} - 4$ \\
Put these back in: \\
$(x + 3)^{2} - 9 + (y - 2)^{2} - 4 - 62 = 0$ \\
Add $9 + 4 + 62 = 75$ to both sides: \\
$(x + 3)^{2} + (y - 2)^{2} = 75$ \\
Compare with $(x - a)^{2} + (y - b)^{2} = r^{2}$ \\
(i) The centre is $(a, b) = (-3, 2)$ \\
(ii) $r^{2} = 75$ \\
Square root both sides: \\
$r = \sqrt{75}$ \\
Take out the largest square factor, $75 = 25 \times 3$: \\
$= \sqrt{25} \times \sqrt{3}$ \\
$r = 5\sqrt{3}$ \\
(b) Substitute $y = 2x + k$ into the original equation of $C$: \\
$x^{2} + (2x + k)^{2} + 6x - 4(2x + k) - 62 = 0$ \\
Expand $(2x + k)^{2}$ and $-4(2x + k)$: \\
$x^{2} + 4x^{2} + 4kx + k^{2} + 6x - 8x - 4k - 62 = 0$ \\
Collect the $x^{2}$ terms, the $x$ terms and the rest: \\
$5x^{2} + (4k + 6 - 8)x + (k^{2} - 4k - 62) = 0$ \\
$5x^{2} + (4k - 2)x + (k^{2} - 4k - 62) = 0$ \\
Two distinct intersections means two distinct roots, so $b^{2} - 4ac > 0$: \\
$(4k - 2)^{2} - 4(5)(k^{2} - 4k - 62) > 0$ \\
Expand $(4k - 2)^{2}$: \\
$16k^{2} - 16k + 4$ \\
Expand $20(k^{2} - 4k - 62)$: \\
$20k^{2} - 80k - 1240$ \\
Subtract the second from the first: \\
$16k^{2} - 16k + 4 - 20k^{2} + 80k + 1240 > 0$ \\
Collect like terms: \\
$-4k^{2} + 64k + 1244 > 0$ \\
Divide both sides by $-4$. This flips the inequality: \\
$k^{2} - 16k - 311 < 0$ \\
Find where $k^{2} - 16k - 311 = 0$ using the quadratic formula: \\
$k = \frac{16 \pm \sqrt{(-16)^{2} - 4(1)(-311)}}{2}$ \\
$= \frac{16 \pm \sqrt{256 + 1244}}{2}$ \\
$= \frac{16 \pm \sqrt{1500}}{2}$ \\
Simplify the surd: $\sqrt{1500} = \sqrt{100 \times 15} = 10\sqrt{15}$ \\
$k = \frac{16 \pm 10\sqrt{15}}{2}$ \\
Divide the top and bottom by 2: \\
$k = 8 \pm 5\sqrt{15}$ \\
The graph of $k^{2} - 16k - 311$ is a U-shaped parabola, so it is below zero between its roots: \\
$8 - 5\sqrt{15} < k < 8 + 5\sqrt{15}$ \\
In set notation: \\
$\{ k : 8 - 5\sqrt{15} < k < 8 + 5\sqrt{15} \}$ \\
(Check: the roots are about $-11.36$ and $27.36$, and $k = 0$ gives $-311 < 0$, which is inside) \\
(Check: $k = 0$ gives the line $y = 2x$ through the origin, and the origin is inside $C$ because $0 + 0 + 0 - 0 - 62 < 0$)
