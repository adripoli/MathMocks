@paper AS1 Shadow June 2019

@q 1
@topic Gradient and perpendicular line
@marks 4
@question
(a) Make $y$ the subject of $4x + 2y - 3 = 0$. \\
Subtract $4x$ from both sides: \\
$2y - 3 = -4x$ \\
Add 3 to both sides: \\
$2y = -4x + 3$ \\
Divide every term by 2: \\
$y = -2x + \frac{3}{2}$ \\
The gradient of $L_{1}$ is $-2$ \\
(b) Perpendicular lines have gradients that multiply to give $-1$: \\
$m_{1} \times m_{2} = -1$ \\
$-2 \times m_{2} = -1$ \\
Divide both sides by $-2$: \\
$m_{2} = \frac{1}{2}$ \\
Use $y - y_{1} = m(x - x_{1})$ with $m = \frac{1}{2}$ and the point $(2, 5)$: \\
$y - 5 = \frac{1}{2}(x - 2)$ \\
Expand the bracket: \\
$y - 5 = \frac{1}{2}x - 1$ \\
Add 5 to both sides: \\
$y = \frac{1}{2}x + 4$ \\
(Check with $(2, 5)$: $\frac{1}{2}(2) + 4 = 1 + 4 = 5$)

@q 2
@topic Quartic quadratic in a squared
@marks 4
@question
Notice $a^{4} = \left( a^{2} \right)^{2}$, so this is a quadratic in $a^{2}$. Let $u = a^{2}$: \\
$u^{2} - 2u - 80 = 0$ \\
Factorise. Two numbers that multiply to $-80$ and add to $-2$ are $-10$ and $8$: \\
$(u - 10)(u + 8) = 0$ \\
$u = 10$ or $u = -8$ \\
Replace $u$ with $a^{2}$: \\
$a^{2} = 10$ or $a^{2} = -8$ \\
A square cannot be negative, so $a^{2} = -8$ has no real solutions. Reject it \\
Take the square root of $a^{2} = 10$, remembering both signs: \\
$a = \sqrt{10}$ or $a = -\sqrt{10}$

@q 3
@topic Integrate to find y, using a point
@marks 6
@question
Split the fraction into two, dividing each term of the top by $2x^{3}$: \\
$\frac{4x - 5}{2x^{3}} = \frac{4x}{2x^{3}} - \frac{5}{2x^{3}}$ \\
Simplify the first fraction by cancelling $2x$: \\
$\frac{4x}{2x^{3}} = \frac{2}{x^{2}} = 2x^{-2}$ \\
Write the second fraction as a power: \\
$\frac{5}{2x^{3}} = \frac{5}{2}x^{-3}$ \\
So the gradient function is: \\
$\frac{dy}{dx} = -x^{3} + 2x^{-2} - \frac{5}{2}x^{-3}$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$ \\
$-x^{3} \to -\frac{x^{4}}{4}$ \\
$2x^{-2} \to 2 \times \frac{x^{-1}}{-1} = -2x^{-1}$ \\
$-\frac{5}{2}x^{-3} \to -\frac{5}{2} \times \frac{x^{-2}}{-2} = \frac{5}{4}x^{-2}$ \\
Add the constant of integration $c$: \\
$y = -\frac{1}{4}x^{4} - 2x^{-1} + \frac{5}{4}x^{-2} + c$ \\
Substitute $x = 1$ and $y = 7$: \\
$7 = -\frac{1}{4} - 2 + \frac{5}{4} + c$ \\
Combine $-\frac{1}{4} + \frac{5}{4} = 1$: \\
$7 = 1 - 2 + c$ \\
$7 = -1 + c$ \\
Add 1 to both sides: \\
$c = 8$ \\
$y = -\frac{1}{4}x^{4} - \frac{2}{x} + \frac{5}{4x^{2}} + 8$ \\
(Check: differentiating gives $-x^{3} + \frac{2}{x^{2}} - \frac{5}{2x^{3}}$, which is $-x^{3} + \frac{4x - 5}{2x^{3}}$)

@q 4
@topic Linear model, water depth
@marks 5
@question
(a) A linear model has the form $D = mt + c$. Find the gradient from the two readings $(5, 13.52)$ and $(8, 18.68)$: \\
$m = \frac{18.68 - 13.52}{8 - 5}$ \\
$= \frac{5.16}{3}$ \\
$= 1.72$ \\
So $D = 1.72t + c$ \\
Substitute $t = 5$ and $D = 13.52$: \\
$13.52 = 1.72(5) + c$ \\
$13.52 = 8.6 + c$ \\
Subtract 8.6 from both sides: \\
$c = 4.92$ \\
$D = 1.72t + 4.92$ \\
(Check with $t = 8$: $1.72(8) + 4.92 = 13.76 + 4.92 = 18.68$) \\
(b) The initial depth is when $t = 0$: \\
$D = 1.72(0) + 4.92$ \\
$D = 4.92$ cm \\
(c) The pot is wider at the top than at the bottom, so water poured in at a constant rate would make the depth rise more slowly as the pot fills. The depth would not rise at a constant rate, so a linear model is not suitable

@q 5
@topic Differentiate roots, increasing curve
@marks 5
@question
(a) Write each term as a power of $x$: \\
$y = x^{\frac{1}{2}} + 4x^{-1} + 4$ \\
Differentiate each term using $\frac{d}{dx}(x^{n}) = nx^{n-1}$: \\
$x^{\frac{1}{2}} \to \frac{1}{2}x^{-\frac{1}{2}}$ \\
$4x^{-1} \to 4 \times (-1)x^{-2} = -4x^{-2}$ \\
The constant 4 differentiates to 0 \\
$\frac{dy}{dx} = \frac{1}{2}x^{-\frac{1}{2}} - 4x^{-2}$ \\
Write with positive powers: \\
$\frac{dy}{dx} = \frac{1}{2\sqrt{x}} - \frac{4}{x^{2}}$ \\
The common denominator is $2x^{2}$ \\
Multiply the first fraction by $\frac{x^{\frac{3}{2}}}{x^{\frac{3}{2}}}$ and the second by $\frac{2}{2}$: \\
$\frac{dy}{dx} = \frac{x^{\frac{3}{2}}}{2x^{2}} - \frac{8}{2x^{2}}$ \\
$\frac{dy}{dx} = \frac{x^{\frac{3}{2}} - 8}{2x^{2}}$ \\
(b) The curve is increasing when $\frac{dy}{dx} > 0$: \\
$\frac{x^{\frac{3}{2}} - 8}{2x^{2}} > 0$ \\
Since $x > 0$, the denominator $2x^{2}$ is positive, so the sign comes from the top: \\
$x^{\frac{3}{2}} - 8 > 0$ \\
Add 8 to both sides: \\
$x^{\frac{3}{2}} > 8$ \\
Raise both sides to the power $\frac{2}{3}$ (both sides are positive, and raising to a positive power keeps the inequality the same way round): \\
$x > 8^{\frac{2}{3}}$ \\
The cube root of 8 is 2, and $2^{2} = 4$: \\
$x > 4$ \\
(Check: at $x = 4$, $\frac{dy}{dx} = \frac{1}{4} - \frac{4}{16} = 0$, and at $x = 9$, $\frac{dy}{dx} = \frac{1}{6} - \frac{4}{81} > 0$)

@q 6
@topic Differentiate x^2 from first principles
@marks 3
@question
Let $f(x) = x^{2}$. The definition of the derivative is: \\
$f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}$ \\
$f'(x) = \lim_{h \to 0} \frac{(x + h)^{2} - x^{2}}{h}$ \\
Expand the bracket: \\
$(x + h)^{2} = x^{2} + 2xh + h^{2}$ \\
Subtract $x^{2}$: \\
$(x + h)^{2} - x^{2} = 2xh + h^{2}$ \\
Divide every term by $h$ (as $h \neq 0$ before taking the limit): \\
$\frac{2xh + h^{2}}{h} = 2x + h$ \\
Let $h \to 0$: \\
$f'(x) = 2x + 0$ \\
$f'(x) = 2x$ \\
So $\frac{d}{dx}\left( x^{2} \right) = 2x$, as required

@q 7
@topic Sketch k/x^2 + 2, intersection
@marks 5
@question
(a) Features of $y = \frac{k}{x^{2}} + 2$: \\
As $x$ gets very large (positive or negative), $\frac{k}{x^{2}}$ gets closer and closer to 0, so $y$ gets closer to 2 \\
The horizontal asymptote is $y = 2$ \\
As $x \to 0$, $x^{2}$ is a small positive number, so $\frac{k}{x^{2}}$ becomes very large, with the same sign as $k$. The $y$-axis ($x = 0$) is a vertical asymptote \\
Replacing $x$ with $-x$ gives the same $y$ (as $(-x)^{2} = x^{2}$), so the curve is symmetrical in the $y$-axis \\
Sketch for $k > 0$: two branches that are mirror images in the $y$-axis. Both lie above the line $y = 2$. Each starts very high up beside the $y$-axis and falls towards $y = 2$ as $|x|$ gets larger \\
Sketch for $k < 0$: two mirror-image branches below the line $y = 2$. Each starts very far down beside the $y$-axis and rises towards $y = 2$ as $|x|$ gets larger, crossing the $x$-axis where $\frac{k}{x^{2}} = -2$, that is $x = \pm \sqrt{-\frac{k}{2}}$ \\
Label the horizontal asymptote $y = 2$ \\
(b) At a point of intersection the $y$ values are equal: \\
$\frac{k}{x^{2}} + 2 = -2x + 5$ \\
Multiply every term by $x^{2}$ (not zero, as $x \neq 0$): \\
$k + 2x^{2} = -2x^{3} + 5x^{2}$ \\
Add $2x^{3}$ to both sides and subtract $5x^{2}$ from both sides: \\
$k + 2x^{2} + 2x^{3} - 5x^{2} = 0$ \\
Collect the $x^{2}$ terms, $2x^{2} - 5x^{2} = -3x^{2}$: \\
$k - 3x^{2} + 2x^{3} = 0$, as required

@q 8
@topic Binomial expansion and estimate
@marks 5
@question
(a) Use the binomial expansion with first term 3, second term $\frac{4x}{5}$ and $n = 5$: \\
$\left( 3 + \frac{4x}{5} \right)^{5} = 3^{5} + 5C1 \times 3^{4} \times \frac{4x}{5} + 5C2 \times 3^{3} \times \left( \frac{4x}{5} \right)^{2} + ...$ \\
The coefficients are $5C1 = 5$ and $5C2 = \frac{5 \times 4}{2} = 10$ \\
First term: $3^{5} = 243$ \\
Second term: $5 \times 81 \times \frac{4x}{5}$ \\
Cancel the 5s: \\
$= 81 \times 4x$ \\
$= 324x$ \\
Third term: $10 \times 27 \times \frac{16x^{2}}{25}$ \\
$= \frac{4320x^{2}}{25}$ \\
Divide top and bottom by 5: \\
$= \frac{864}{5}x^{2}$ \\
$\left( 3 + \frac{4x}{5} \right)^{5} = 243 + 324x + \frac{864}{5}x^{2} + ...$ \\
(b) Find the value of $x$ that makes the bracket equal to 2.96: \\
$3 + \frac{4x}{5} = 2.96$ \\
Subtract 3 from both sides: \\
$\frac{4x}{5} = -0.04$ \\
Multiply both sides by $\frac{5}{4}$: \\
$x = -0.05$ \\
Substitute $x = -0.05$ into the three terms of the expansion. The value of $x$ is small, so the terms left out are very small and the estimate of $2.96^{5}$ is close to the true value \\
(Optional check: $243 + 324(-0.05) + \frac{864}{5}(-0.05)^{2} = 243 - 16.2 + 0.432 = 227.232$, and the true value of $2.96^{5}$ is 227.226...)

@q 9
@topic Quadratic model: plastic bags
@marks 6
@question
(a) The year ending 31st December 2014 is when the charge started, so $n = 0$: \\
$x = 7.6 - 0.2(0 - 2)^{2}$ \\
$= 7.6 - 0.2(-2)^{2}$ \\
$= 7.6 - 0.2 \times 4$ \\
$= 7.6 - 0.8$ \\
$= 6.8$ \\
According to the model, 6.8 billion bags were used \\
(b)(i) $(n - 2)^{2} \geq 0$, so $0.2(n - 2)^{2} \geq 0$ and $x \leq 7.6$ \\
$x$ is largest when $(n - 2)^{2} = 0$, which is when $n = 2$ \\
$n = 2$ is 2 years after 31st December 2014, which is the year ending 31st December 2016. The year of highest usage is 2016 \\
(b)(ii) At $n = 2$: \\
$x = 7.6 - 0.2(0)^{2}$ \\
$x = 7.6$ \\
The model predicts 7.6 billion bags in 2016 \\
(c) The year ending 31st December 2018 is $n = 4$: \\
$x = 7.6 - 0.2(4 - 2)^{2}$ \\
$= 7.6 - 0.2(2)^{2}$ \\
$= 7.6 - 0.2 \times 4$ \\
$= 7.6 - 0.8$ \\
$= 6.8$ \\
The target was 6.8 billion bags but 7 billion were used. $7 > 6.8$, so the government were not meeting their target (they were 0.2 billion bags over it) \\
(d) The year ending 31st December 2025 is $n = 11$: \\
$x = 7.6 - 0.2(11 - 2)^{2}$ \\
$= 7.6 - 0.2(9)^{2}$ \\
$= 7.6 - 0.2 \times 81$ \\
$= 7.6 - 16.2$ \\
$= -8.6$ \\
The model gives a negative number of bags, which is impossible, so the model is not valid in 2025

@q 10
@topic Circle centre, radius, vertical line
@marks 5
@question
(a) Complete the square on the $x$ terms and on the $y$ terms. Half of 6 is 3 and half of $-4$ is $-2$: \\
$x^{2} + 6x = (x + 3)^{2} - 9$ \\
$y^{2} - 4y = (y - 2)^{2} - 4$ \\
Substitute into the equation of the circle: \\
$(x + 3)^{2} - 9 + (y - 2)^{2} - 4 + 5 = 0$ \\
$(x + 3)^{2} + (y - 2)^{2} - 8 = 0$ \\
Add 8 to both sides: \\
$(x + 3)^{2} + (y - 2)^{2} = 8$ \\
Compare with $(x - a)^{2} + (y - b)^{2} = r^{2}$: \\
(a)(i) The centre is $(-3, 2)$ \\
(a)(ii) $r^{2} = 8$, so $r = \sqrt{8}$ \\
Write 8 as $4 \times 2$: \\
$r = \sqrt{4} \times \sqrt{2}$ \\
$r = 2\sqrt{2}$ \\
(b) The line $x = k$ is vertical. It cuts the circle twice when it passes between the leftmost and rightmost points of the circle, which are one radius either side of the centre's $x$ coordinate $-3$: \\
Leftmost point: $x = -3 - 2\sqrt{2}$ \\
Rightmost point: $x = -3 + 2\sqrt{2}$ \\
$-3 - 2\sqrt{2} < k < -3 + 2\sqrt{2}$ \\
(Check: this is about $-5.83 < k < -0.17$)

@q 11
@topic Factor theorem, roots, transformations
@marks 10
@question
(a) By the factor theorem, $(x - 3)$ is a factor if $f(3) = 0$ \\
$f(3) = 3^{3} + 3^{2} - 8(3) - 12$ \\
$= 27 + 9 - 24 - 12$ \\
$= 36 - 36$ \\
$= 0$ \\
Since $f(3) = 0$, $(x - 3)$ is a factor of $f(x)$ \\
(b) Write $f(x) = (x - 3)(x^{2} + px + q)$ and expand the right-hand side: \\
$(x - 3)(x^{2} + px + q) = x^{3} + px^{2} + qx - 3x^{2} - 3px - 3q$ \\
$= x^{3} + (p - 3)x^{2} + (q - 3p)x - 3q$ \\
Compare coefficients of $x^{2}$: \\
$p - 3 = 1$ \\
$p = 4$ \\
Compare constant terms: \\
$-3q = -12$ \\
$q = 4$ \\
Check the $x$ terms: $q - 3p = 4 - 12 = -8$, which matches \\
$f(x) = (x - 3)\left( x^{2} + 4x + 4 \right)$ \\
Factorise the quadratic, which is a perfect square: \\
$x^{2} + 4x + 4 = (x + 2)^{2}$ \\
$f(x) = (x - 3)(x + 2)^{2}$ \\
Solve $f(x) = 0$: \\
$x - 3 = 0$ gives $x = 3$ \\
$(x + 2)^{2} = 0$ gives $x = -2$ (a repeated root) \\
There are only 2 distinct roots, $x = 3$ and $x = -2$, as required \\
(c) Compare $2x^{3} + 2x^{2} - 16x - 50$ with $2f(x) = 2x^{3} + 2x^{2} - 16x - 24$: \\
$2x^{3} + 2x^{2} - 16x - 50 = 2f(x) - 26$ \\
Check: $2f(x) - 26 = 2x^{3} + 2x^{2} - 16x - 24 - 26$ \\
$= 2x^{3} + 2x^{2} - 16x - 50$ \\
So the equation $2x^{3} + 2x^{2} - 16x - 50 = 0$ becomes: \\
$2f(x) - 26 = 0$ \\
Add 26 to both sides: \\
$2f(x) = 26$ \\
Divide both sides by 2: \\
$f(x) = 13$ \\
The roots are the points where the curve $y = f(x)$ meets the horizontal line $y = 13$ \\
From part (b) the curve touches the $x$-axis at its maximum point $x = -2$, so its greatest value for $x < 3$ is 0. The curve only goes above the $x$-axis for $x > 3$, where it keeps rising \\
So the line $y = 13$ is met exactly once, and the equation has 1 real root \\
(d) The curve $y = f(kx)$ passes through $(1, 0)$, so put $x = 1$ and $y = 0$: \\
$f(k \times 1) = 0$ \\
$f(k) = 0$ \\
$k$ must be a root of $f$, so from part (b): \\
$k = 3$ or $k = -2$

@q 12
@topic Prove a trig identity
@marks 4
@question
Work with the left-hand side. Use $\cos^{2} x = 1 - \sin^{2} x$ on the top: \\
$10\cos^{2} x - \sin x - 7 = 10\left( 1 - \sin^{2} x \right) - \sin x - 7$ \\
Expand the bracket: \\
$= 10 - 10\sin^{2} x - \sin x - 7$ \\
Collect the constants: \\
$= 3 - \sin x - 10\sin^{2} x$ \\
Let $s = \sin x$, and write the top in the order $s^{2}$, $s$, number: \\
$3 - s - 10s^{2} = -\left( 10s^{2} + s - 3 \right)$ \\
Factorise $10s^{2} + s - 3$. Two numbers that multiply to $10 \times (-3) = -30$ and add to $1$ are $6$ and $-5$: \\
$10s^{2} + 6s - 5s - 3$ \\
$= 2s(5s + 3) - 1(5s + 3)$ \\
$= (2s - 1)(5s + 3)$ \\
So the top is $-(2s - 1)(5s + 3)$ \\
The fraction becomes: \\
$\frac{-(2s - 1)(5s + 3)}{2s - 1}$ \\
Cancel the common factor $(2s - 1)$ (it is not zero, as the fraction exists): \\
$= -(5s + 3)$ \\
Expand the bracket: \\
$= -5s - 3$ \\
Replace $s$ by $\sin x$: \\
$\frac{10\cos^{2} x - \sin x - 7}{2\sin x - 1} = -3 - 5\sin x$, as required

@q 13
@topic Area between cubic and tangent line
@marks 7
@question
Find the $y$ coordinate of $A$ by putting $x = -4$ in the equation of $C$: \\
$y = \frac{1}{8}(-4)^{3} + \frac{3}{4}(-4)^{2}$ \\
$= \frac{1}{8}(-64) + \frac{3}{4}(16)$ \\
$= -8 + 12$ \\
$= 4$ \\
$A$ is a turning point, so the gradient there is 0. Check: \\
$\frac{dy}{dx} = \frac{3}{8}x^{2} + \frac{3}{2}x$ \\
At $x = -4$: $\frac{3}{8}(16) + \frac{3}{2}(-4) = 6 - 6 = 0$ \\
The line $l$ touches $C$ at $A$, so it has the same gradient as $C$ there, which is 0. It is horizontal and passes through $A(-4, 4)$: \\
$l: y = 4$ \\
Check that $B$ is on this line. At $x = 2$: \\
$y = \frac{1}{8}(2)^{3} + \frac{3}{4}(2)^{2} = 1 + 3 = 4$ \\
So $B$ is the point $(2, 4)$ \\
Between $x = -4$ and $x = 2$ the line is above the curve (for example at $x = -2$ the curve is at $y = 2$, below the line at 4). So: \\
Area of $R = \int_{-4}^{2} (\text{line} - \text{curve}) dx$ \\
$= \int_{-4}^{2} \left( 4 - \frac{1}{8}x^{3} - \frac{3}{4}x^{2} \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$: \\
$4 \to 4x$ \\
$-\frac{1}{8}x^{3} \to -\frac{1}{8} \times \frac{x^{4}}{4} = -\frac{x^{4}}{32}$ \\
$-\frac{3}{4}x^{2} \to -\frac{3}{4} \times \frac{x^{3}}{3} = -\frac{x^{3}}{4}$ \\
$= \left[ 4x - \frac{x^{4}}{32} - \frac{x^{3}}{4} \right]_{-4}^{2}$ \\
Upper limit $x = 2$: \\
$4(2) - \frac{16}{32} - \frac{8}{4} = 8 - \frac{1}{2} - 2 = \frac{11}{2}$ \\
Lower limit $x = -4$: \\
$4(-4) - \frac{256}{32} - \frac{-64}{4} = -16 - 8 + 16 = -8$ \\
Subtract the lower limit from the upper limit: \\
Area of $R = \frac{11}{2} - (-8)$ \\
$= \frac{11}{2} + \frac{16}{2}$ \\
$= \frac{27}{2}$ \\
The area of $R$ is $\frac{27}{2} = 13.5$ square units

@q 14
@topic Exponential decay of leaf mass
@marks 9
@question
(a) When the leaf is picked, $t = 0$ and $m = 7.5$: \\
$7.5 = pe^{0}$ \\
$e^{0} = 1$, so: \\
$p = 7.5$ \\
Four days later, $t = 4$ and $m = 2.5$: \\
$2.5 = 7.5e^{-4k}$ \\
Divide both sides by 7.5: \\
$\frac{2.5}{7.5} = e^{-4k}$ \\
$\frac{1}{3} = e^{-4k}$ \\
Take natural logs of both sides: \\
$\ln \left( \frac{1}{3} \right) = \ln e^{-4k}$ \\
Use $\ln e^{a} = a$: \\
$\ln \left( \frac{1}{3} \right) = -4k$ \\
Use $\ln \left( \frac{1}{3} \right) = \ln 3^{-1} = -\ln 3$: \\
$-\ln 3 = -4k$ \\
Divide both sides by $-4$: \\
$k = \frac{1}{4}\ln 3$, as required \\
(b) Differentiate $m = 7.5e^{-kt}$. The derivative of $e^{-kt}$ is $-ke^{-kt}$: \\
$\frac{dm}{dt} = 7.5 \times (-k)e^{-kt}$ \\
$\frac{dm}{dt} = -7.5ke^{-kt}$ \\
Substitute $k = \frac{1}{4}\ln 3$: \\
$\frac{dm}{dt} = -7.5 \times \frac{1}{4}\ln 3 \times e^{-kt}$ \\
$\frac{dm}{dt} = -1.875\ln 3 \times e^{-kt}$ \\
Set this equal to $-0.6\ln 3$: \\
$-1.875\ln 3 \times e^{-kt} = -0.6\ln 3$ \\
Divide both sides by $-\ln 3$ (which is not zero): \\
$1.875e^{-kt} = 0.6$ \\
Divide both sides by 1.875: \\
$e^{-kt} = \frac{0.6}{1.875}$ \\
$e^{-kt} = 0.32$ \\
Take natural logs of both sides: \\
$-kt = \ln 0.32$ \\
Divide both sides by $-k$: \\
$t = \frac{\ln 0.32}{-k}$ \\
Substitute $k = \frac{1}{4}\ln 3$: \\
$t = \frac{-4\ln 0.32}{\ln 3}$ \\
$\ln 0.32 = -1.139434...$ and $\ln 3 = 1.098612...$: \\
$t = \frac{4 \times 1.139434}{1.098612}$ \\
$= \frac{4.557736}{1.098612}$ \\
$t = 4.15$ days (3 sf) \\
(Check: $-1.875\ln 3 \times e^{-kt} = -1.875 \times 1.098612 \times 0.32 = -0.6592$ and $-0.6\ln 3 = -0.6592$)

@q 15
@topic Prove an inequality for all x
@marks 4
@question
Subtract $2x + 1$ from both sides, so that one side is 0. We need to show: \\
$x^{2} + 8x + 10 - (2x + 1) \geq 0$ \\
Remove the bracket, changing both signs: \\
$x^{2} + 8x + 10 - 2x - 1 \geq 0$ \\
Collect like terms: \\
$x^{2} + 6x + 9 \geq 0$ \\
Factorise. This is a perfect square, since $3^{2} = 9$ and $2 \times 3 = 6$: \\
$(x + 3)^{2} \geq 0$ \\
The square of any real number is at least 0, so $(x + 3)^{2} \geq 0$ for every real $x$ \\
Every step above can be reversed, so $x^{2} + 8x + 10 \geq 2x + 1$ for all real $x$, as required \\
(Equality holds only when $x = -3$)

@q 16
@topic Vector magnitudes, cosine rule
@marks 5
@question
(a) $\mathbf{a}$ and $\mathbf{b}$ placed head to tail make a triangle whose third side has length $|\mathbf{a} + \mathbf{b}|$ \\
In any genuine triangle, each side is longer than the difference of the other two sides, so $|\mathbf{a} + \mathbf{b}| > |\mathbf{a}| - |\mathbf{b}|$ \\
Here the two are exactly equal, so the triangle has collapsed to a straight line \\
So $\mathbf{a}$ and $\mathbf{b}$ are parallel and point in opposite directions, and $\mathbf{a}$ is the longer vector \\
(b) Let $\mathbf{p} = \mathbf{m} - \mathbf{n}$. Then $\mathbf{n} = \mathbf{m} - \mathbf{p}$ \\
Draw $\mathbf{m}$ and $\mathbf{p}$ from the same point. The angle between them is 30 degrees, with $|\mathbf{m}| = 4$ and $|\mathbf{p}| = 6$. The vector $\mathbf{n} = \mathbf{m} - \mathbf{p}$ is the third side of the triangle \\
Use the cosine rule $c^{2} = a^{2} + b^{2} - 2ab\cos C$: \\
$|\mathbf{n}|^{2} = 4^{2} + 6^{2} - 2(4)(6)\cos 30$ degrees \\
$\cos 30$ degrees $= \frac{\sqrt{3}}{2}$, so: \\
$|\mathbf{n}|^{2} = 16 + 36 - 48 \times \frac{\sqrt{3}}{2}$ \\
$= 52 - 24\sqrt{3}$ \\
$= 10.4307...$ \\
Take the positive square root, since a length is positive: \\
$|\mathbf{n}| = \sqrt{52 - 24\sqrt{3}}$ \\
$|\mathbf{n}| = 3.23$ (3 sf)
