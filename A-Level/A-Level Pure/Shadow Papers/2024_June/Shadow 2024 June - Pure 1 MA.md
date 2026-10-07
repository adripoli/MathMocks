@paper P1 Shadow June 2024

@q 1
@topic Factor theorem, find k
@marks 3
@question
$(x + 2)$ is a factor of $g(x)$, so by the factor theorem $g(-2) = 0$ \\
$g(-2) = 5(-2)^{3} + k(-2)^{2} + (-2) + 2k$ \\
Evaluate the powers: $(-2)^{3} = -8$ and $(-2)^{2} = 4$ \\
$g(-2) = 5(-8) + 4k - 2 + 2k$ \\
$g(-2) = -40 + 4k - 2 + 2k$ \\
Collect the $k$ terms: $4k + 2k = 6k$ \\
Collect the numbers: $-40 - 2 = -42$ \\
$g(-2) = 6k - 42$ \\
Set this equal to zero: \\
$6k - 42 = 0$ \\
Add 42 to both sides: \\
$6k = 42$ \\
Divide by 6: \\
$k = 7$ \\
(Check: $g(x) = 5x^{3} + 7x^{2} + x + 14$ and $g(-2) = -40 + 28 - 2 + 14 = 0$)

@q 2
@topic Binomial (1 - 4x)^(1/3), validity
@marks 4
@question
(a) Binomial expansion: $(1 + y)^{n} = 1 + ny + \frac{n(n - 1)}{2!}y^{2} + \frac{n(n - 1)(n - 2)}{3!}y^{3} + \ldots$ \\
Here $n = \frac{1}{3}$ and $y = -4x$ \\
Second term: $ny = \frac{1}{3}(-4x)$ \\
$= -\frac{4}{3}x$ \\
Third term: $\frac{n(n - 1)}{2!} = \frac{\frac{1}{3}\left( -\frac{2}{3} \right)}{2}$ \\
$= \frac{-\frac{2}{9}}{2}$ \\
$= -\frac{1}{9}$ \\
$y^{2} = (-4x)^{2} = 16x^{2}$ \\
$-\frac{1}{9} \times 16x^{2} = -\frac{16}{9}x^{2}$ \\
Fourth term: $\frac{n(n - 1)(n - 2)}{3!} = \frac{\frac{1}{3}\left( -\frac{2}{3} \right)\left( -\frac{5}{3} \right)}{6}$ \\
$= \frac{\frac{10}{27}}{6}$ \\
$= \frac{5}{81}$ \\
$y^{3} = (-4x)^{3} = -64x^{3}$ \\
$\frac{5}{81} \times (-64x^{3}) = -\frac{320}{81}x^{3}$ \\
$(1 - 4x)^{\frac{1}{3}} = 1 - \frac{4}{3}x - \frac{16}{9}x^{2} - \frac{320}{81}x^{3} + \ldots$ \\
(b) The expansion of $(1 + y)^{n}$ for a fraction $n$ is only valid when $|y| < 1$ \\
Here $|-4x| < 1$, so $|x| < \frac{1}{4}$ \\
$x = -\frac{1}{2}$ has $|x| = \frac{1}{2}$, which is bigger than $\frac{1}{4}$ \\
So $x = -\frac{1}{2}$ is outside the range where the expansion is valid, and it should not be used \\
(As printed, the question mentions $\sqrt{3}$, but $x = -\frac{1}{2}$ gives $(1 + 2)^{\frac{1}{3}} = 3^{\frac{1}{3}}$. Either way the value of $x$ is outside the valid range)

@q 3
@topic Root in interval, Newton-Raphson
@marks 6
@question
(a) Work in radians \\
$f(0.6) = 0.6 - \cos \left( \frac{3}{2} \times 0.6 \right)$ \\
$\frac{3}{2} \times 0.6 = 0.9$ \\
$\cos 0.9 = 0.62161$ \\
$f(0.6) = 0.6 - 0.62161$ \\
$f(0.6) = -0.0216$, which is negative \\
$f(0.7) = 0.7 - \cos \left( \frac{3}{2} \times 0.7 \right)$ \\
$\frac{3}{2} \times 0.7 = 1.05$ \\
$\cos 1.05 = 0.49757$ \\
$f(0.7) = 0.7 - 0.49757$ \\
$f(0.7) = 0.2024$, which is positive \\
$f(x)$ is continuous and changes sign between 0.6 and 0.7 \\
So there is a root $\alpha$ in the interval $[0.6, 0.7]$ \\
(b) Differentiate $f(x) = x - \cos \left( \frac{3x}{2} \right)$ \\
$x \to 1$ \\
$\cos \left( \frac{3x}{2} \right)$ differentiates, by the chain rule, to $-\sin \left( \frac{3x}{2} \right) \times \frac{3}{2}$ \\
So $-\cos \left( \frac{3x}{2} \right) \to +\frac{3}{2}\sin \left( \frac{3x}{2} \right)$ \\
$f'(x) = 1 + \frac{3}{2}\sin \left( \frac{3x}{2} \right)$ \\
(c) Newton-Raphson: $x_{1} = x_{0} - \frac{f(x_{0})}{f'(x_{0})}$ with $x_{0} = 0.6$ \\
$f(0.6) = -0.021610$ \\
$f'(0.6) = 1 + \frac{3}{2}\sin (0.9)$ \\
$\sin 0.9 = 0.78333$ \\
$f'(0.6) = 1 + 1.17499$ \\
$f'(0.6) = 2.17499$ \\
$x_{1} = 0.6 - \frac{-0.021610}{2.17499}$ \\
$x_{1} = 0.6 + 0.009936$ \\
$x_{1} = 0.609936$ \\
$x_{1} = 0.610$ to 3 decimal places

@q 4
@topic Differentiation from first principles x^3
@marks 3
@question
$f(x) = x^{3}$ \\
$f(x + h) = (x + h)^{3}$ \\
Expand the bracket: $(x + h)^{3} = x^{3} + 3x^{2}h + 3xh^{2} + h^{3}$ \\
Gradient from first principles: $\frac{f(x + h) - f(x)}{h}$ \\
$= \frac{x^{3} + 3x^{2}h + 3xh^{2} + h^{3} - x^{3}}{h}$ \\
The $x^{3}$ terms cancel: \\
$= \frac{3x^{2}h + 3xh^{2} + h^{3}}{h}$ \\
Divide every term on the top by $h$: \\
$= 3x^{2} + 3xh + h^{2}$ \\
As $h \to 0$, the terms $3xh$ and $h^{2}$ both go to 0: \\
$\frac{dy}{dx} = \lim_{h \to 0}(3x^{2} + 3xh + h^{2})$ \\
$\frac{dy}{dx} = 3x^{2}$ as required

@q 5
@topic Quotient rule, decreasing function
@marks 6
@question
(a) Use the quotient rule with $u = 5x + 14$ and $v = x^{2} - 3$ \\
$\frac{du}{dx} = 5$ \\
$\frac{dv}{dx} = 2x$ \\
$f'(x) = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^{2}}$ \\
$f'(x) = \frac{(x^{2} - 3)(5) - (5x + 14)(2x)}{(x^{2} - 3)^{2}}$ \\
Expand the top, one part at a time: \\
$(x^{2} - 3)(5) = 5x^{2} - 15$ \\
$(5x + 14)(2x) = 10x^{2} + 28x$ \\
Subtract: $5x^{2} - 15 - 10x^{2} - 28x$ \\
Collect like terms: \\
$= -5x^{2} - 28x - 15$ \\
$f'(x) = \frac{-5x^{2} - 28x - 15}{(x^{2} - 3)^{2}}$ \\
So $a = -5$, $b = -28$, $c = -15$ \\
(b) $f$ is decreasing where $f'(x) < 0$ \\
The bottom $(x^{2} - 3)^{2}$ is a square, so it is positive wherever it is defined \\
So we need the top to be negative: \\
$-5x^{2} - 28x - 15 < 0$ \\
Multiply by $-1$, which reverses the inequality: \\
$5x^{2} + 28x + 15 > 0$ \\
Factorise: \\
$(5x + 3)(x + 5) > 0$ \\
The critical values are $x = -\frac{3}{5}$ and $x = -5$ \\
The graph of $5x^{2} + 28x + 15$ is a U shape, so it is positive outside the roots: \\
$x < -5$ or $x > -\frac{3}{5}$ \\
(f is not defined at $x = \pm \sqrt{3}$, so those two values are left out of these ranges)

@q 6
@topic Modulus graph, vertex, line meets twice
@marks 6
@question
(a) The vertex is where the modulus is zero: $x + 3 = 0$, so $x = -3$ \\
$y = 2(0) + 5 = 5$ \\
$P = (-3, 5)$ \\
(b) Solve $5x + 4 = 2|x + 3| + 5$ \\
Subtract 5 from both sides: \\
$5x - 1 = 2|x + 3|$ \\
The right side is not negative, so we need $5x - 1 \geq 0$, which means $x \geq \frac{1}{5}$ \\
Then $x + 3 > 0$, so $|x + 3| = x + 3$ \\
$5x + 4 = 2(x + 3) + 5$ \\
Expand the bracket: \\
$5x + 4 = 2x + 6 + 5$ \\
$5x + 4 = 2x + 11$ \\
Subtract $2x$ and 4: \\
$3x = 7$ \\
$x = \frac{7}{3}$ \\
(Check the other arm: $5x + 4 = -2(x + 3) + 5$ gives $7x = -5$, so $x = -\frac{5}{7}$, which is greater than $-3$, so it is not on that arm and is rejected) \\
$x = \frac{7}{3}$ \\
(c) The graph has two arms: for $x \geq -3$ it is $y = 2x + 11$, and for $x < -3$ it is $y = -2x - 1$ \\
The line $y = kx + 4$ passes through $(0, 4)$, which is below the graph (at $x = 0$ the graph is at 11) \\
To meet the graph twice, the line must cut the left arm and the right arm once each \\
Limit 1: the line through $(0, 4)$ and the vertex $P(-3, 5)$ \\
$k = \frac{5 - 4}{-3 - 0}$ \\
$k = -\frac{1}{3}$ \\
For $k$ greater than $-\frac{1}{3}$ the line goes under the vertex and misses the graph on the left, so it meets the right arm only once \\
Limit 2: the line parallel to the left arm, which has gradient $-2$ \\
$k = -2$ \\
A line with gradient $-2$ never meets the left arm, and for $k < -2$ it meets only the right arm \\
Test $k = -1$ (between the limits): \\
$-x + 4 = 2x + 11$ gives $3x = -7$, so $x = -\frac{7}{3}$, which is greater than $-3$, so it is on the right arm \\
$-x + 4 = -2x - 1$ gives $x = -5$, which is less than $-3$, so it is on the left arm \\
So there are 2 points when $k = -1$ \\
$-2 < k < -\frac{1}{3}$

@q 7
@topic Cooling steak, differential equation
@marks 8
@question
(a) Integrate $\frac{d\theta}{dt} = -90e^{-0.4t}$ with respect to $t$: \\
$\int -90e^{-0.4t} dt = -90 \times \frac{e^{-0.4t}}{-0.4} + c$ \\
$\frac{-90}{-0.4} = 225$ \\
$\theta = 225e^{-0.4t} + c$ \\
At the start $t = 0$ and $\theta = 240$: \\
$240 = 225e^{0} + c$ \\
$e^{0} = 1$ \\
$240 = 225 + c$ \\
Subtract 225: \\
$c = 15$ \\
$\theta = 225e^{-0.4t} + 15$ \\
So $A = 225$ and $B = 15$ \\
(b) Put $\theta = 70$: \\
$70 = 225e^{-0.4t} + 15$ \\
Subtract 15: \\
$55 = 225e^{-0.4t}$ \\
Divide by 225: \\
$e^{-0.4t} = \frac{55}{225}$ \\
$e^{-0.4t} = 0.24444$ \\
Take natural logs of both sides: \\
$-0.4t = \ln 0.24444$ \\
$-0.4t = -1.40876$ \\
Divide by $-0.4$: \\
$t = 3.5219$ minutes \\
Convert the decimal part to seconds: $0.5219 \times 60 = 31.3$ \\
The time is 3 minutes 31 seconds \\
(c) As $t$ gets large, $e^{-0.4t}$ gets close to 0 \\
$\theta \to 225(0) + 15$ \\
$\theta \to 15$ \\
The ambient temperature is 15 degrees C

@q 8
@topic Composite, inverse, range, no real roots
@marks 11
@question
(a) $fg(-1)$ means $f(g(-1))$, so do $g$ first \\
$g(-1) = \frac{5}{2(-1) - 7}$ \\
$= \frac{5}{-9}$ \\
$= -\frac{5}{9}$ \\
$f\left( -\frac{5}{9} \right) = 5\left( -\frac{5}{9} \right)^{2} - 4$ \\
$\left( -\frac{5}{9} \right)^{2} = \frac{25}{81}$ \\
$= 5 \times \frac{25}{81} - 4$ \\
$= \frac{125}{81} - 4$ \\
Write 4 over 81: $4 = \frac{324}{81}$ \\
$= \frac{125 - 324}{81}$ \\
$fg(-1) = -\frac{199}{81}$ \\
(b) Let $y = \frac{5}{2x - 7}$ \\
Multiply both sides by $(2x - 7)$: \\
$y(2x - 7) = 5$ \\
Expand the bracket: \\
$2xy - 7y = 5$ \\
Add $7y$ to both sides: \\
$2xy = 5 + 7y$ \\
Divide by $2y$: \\
$x = \frac{5 + 7y}{2y}$ \\
Swap $x$ and $y$: \\
$g^{-1}(x) = \frac{5 + 7x}{2x}$, $x \ne 0$ \\
(c) $gf(x)$ means $g(f(x))$ \\
Replace $x$ in $g(x) = \frac{5}{2x - 7}$ by $f(x) = 5x^{2} - 4$: \\
$gf(x) = \frac{5}{2(5x^{2} - 4) - 7}$ \\
Expand the bracket in the denominator: \\
$2(5x^{2} - 4) = 10x^{2} - 8$ \\
Subtract 7: $10x^{2} - 8 - 7 = 10x^{2} - 15$ \\
$gf(x) = \frac{5}{10x^{2} - 15}$ \\
Divide the top and bottom by 5: \\
$gf(x) = \frac{1}{2x^{2} - 3}$ \\
For the range, look at the bottom $2x^{2} - 3$ \\
$x^{2} \geq 0$, so $2x^{2} - 3 \geq -3$ \\
The bottom can be any value from $-3$ upwards, but it cannot be 0 (the function is not defined there) \\
When the bottom is in $[-3, 0)$: $\frac{1}{\text{bottom}} \leq -\frac{1}{3}$ \\
(at bottom $= -3$ the value is $-\frac{1}{3}$, and as the bottom gets close to 0 from below it gets very negative) \\
When the bottom is in $(0, \infty)$: $\frac{1}{\text{bottom}} > 0$ \\
Range of $gf$: $gf(x) \leq -\frac{1}{3}$ or $gf(x) > 0$ \\
(d) Set $f(x) = h(x)$: \\
$5x^{2} - 4 = 9x^{2} + 6x + k$ \\
Subtract $5x^{2}$ and add 4 to the right: \\
$0 = 4x^{2} + 6x + k + 4$ \\
$4x^{2} + 6x + (k + 4) = 0$ \\
No real roots means the discriminant is negative: $b^{2} - 4ac < 0$ \\
$a = 4$, $b = 6$, $c = k + 4$ \\
$6^{2} - 4(4)(k + 4) < 0$ \\
$36 - 16(k + 4) < 0$ \\
Expand the bracket: \\
$36 - 16k - 64 < 0$ \\
Collect the numbers: \\
$-16k - 28 < 0$ \\
Add 28 to both sides: \\
$-16k < 28$ \\
Divide by $-16$, which reverses the inequality: \\
$k > -\frac{28}{16}$ \\
$k > -\frac{7}{4}$

@q 9
@topic Geometric sequence with powers of 2
@marks 6
@question
(a) Write every term as a power of 2 \\
$8 = 2^{3}$, so $8^{2(k-2)} = \left( 2^{3} \right)^{2(k-2)} = 2^{6(k-2)}$ \\
The three terms are $2^{2(k+2)}$, $2^{6(k-2)}$, $2^{2k}$ \\
In a geometric sequence the common ratio is the same: $\frac{\text{second}}{\text{first}} = \frac{\text{third}}{\text{second}}$ \\
$\frac{2^{6(k-2)}}{2^{2(k+2)}} = \frac{2^{2k}}{2^{6(k-2)}}$ \\
Subtract the powers on each side (index law for division): \\
$2^{6(k-2) - 2(k+2)} = 2^{2k - 6(k-2)}$ \\
Simplify the left power: $6k - 12 - 2k - 4 = 4k - 16$ \\
Simplify the right power: $2k - 6k + 12 = -4k + 12$ \\
$2^{4k - 16} = 2^{-4k + 12}$ \\
The bases are equal, so the powers are equal: \\
$4k - 16 = -4k + 12$ \\
Add $4k$ and add 16 to both sides: \\
$8k = 28$ \\
Divide by 8: \\
$k = \frac{28}{8}$ \\
$k = \frac{7}{2}$ as required \\
(b) First term: $a = 2^{2(k+2)}$ with $k = \frac{7}{2}$ \\
$k + 2 = \frac{11}{2}$ \\
$2\left( \frac{11}{2} \right) = 11$ \\
$a = 2^{11}$ \\
$a = 2048$ \\
Common ratio: $r = 2^{4k - 16}$ with $k = \frac{7}{2}$ \\
$4 \times \frac{7}{2} = 14$ \\
$4k - 16 = 14 - 16 = -2$ \\
$r = 2^{-2}$ \\
$r = \frac{1}{4}$ \\
(Check the terms: $2048$, then $8^{3} = 512$, then $2^{7} = 128$, and $\frac{512}{2048} = \frac{128}{512} = \frac{1}{4}$) \\
$|r| < 1$, so the sum to infinity exists \\
$S_{\infty} = \frac{a}{1 - r}$ \\
$S_{\infty} = \frac{2048}{1 - \frac{1}{4}}$ \\
$S_{\infty} = \frac{2048}{\frac{3}{4}}$ \\
Dividing by $\frac{3}{4}$ is multiplying by $\frac{4}{3}$: \\
$S_{\infty} = 2048 \times \frac{4}{3}$ \\
$S_{\infty} = \frac{8192}{3}$

@q 10
@topic Tangent, area between line and curve
@marks 8
@question
(a) Put $x = 4$ into $y = 8\sqrt{x} - x^{2}$: \\
$y = 8\sqrt{4} - 4^{2}$ \\
$= 8 \times 2 - 16$ \\
$= 16 - 16$ \\
$= 0$ \\
So the curve meets the $x$-axis at $x = 4$, and $A = (4, 0)$ \\
(b) Write the curve as $y = 8x^{\frac{1}{2}} - x^{2}$ and differentiate: \\
$\frac{dy}{dx} = 8 \times \frac{1}{2}x^{-\frac{1}{2}} - 2x$ \\
$\frac{dy}{dx} = 4x^{-\frac{1}{2}} - 2x$ \\
At $A$, $x = 4$: \\
$4 \times 4^{-\frac{1}{2}} = 4 \times \frac{1}{2} = 2$ \\
$2x = 8$ \\
$\frac{dy}{dx} = 2 - 8$ \\
$\frac{dy}{dx} = -6$ \\
The tangent has gradient $-6$ and passes through $(4, 0)$: \\
$y - 0 = -6(x - 4)$ \\
Expand the bracket: \\
$y = -6x + 24$ \\
Add $6x$ to both sides: \\
$6x + y = 24$ as required \\
(c) $B$ is on the $y$-axis, where $x = 0$ on the line: \\
$y = 24$, so $B = (0, 24)$ \\
The triangle formed by $O$, $A$ and $B$ has base $OA = 4$ and height $OB = 24$ \\
Area of the triangle $= \frac{1}{2} \times 4 \times 24$ \\
$= 48$ \\
Area under the curve from $x = 0$ to $x = 4$: \\
$\int_{0}^{4} \left( 8x^{\frac{1}{2}} - x^{2} \right) dx$ \\
Integrate each term: \\
$8x^{\frac{1}{2}} \to 8 \times \frac{x^{\frac{3}{2}}}{\frac{3}{2}} = \frac{16}{3}x^{\frac{3}{2}}$ \\
$-x^{2} \to -\frac{x^{3}}{3}$ \\
$\left[ \frac{16}{3}x^{\frac{3}{2}} - \frac{1}{3}x^{3} \right]_{0}^{4}$ \\
Upper limit $x = 4$: $4^{\frac{3}{2}} = 8$ and $4^{3} = 64$ \\
$\frac{16}{3} \times 8 - \frac{64}{3}$ \\
$= \frac{128}{3} - \frac{64}{3}$ \\
$= \frac{64}{3}$ \\
Lower limit $x = 0$ gives 0 \\
Area under the curve $= \frac{64}{3}$ \\
The region $R$ is the triangle with the area under the curve cut out of it: \\
Area of $R = 48 - \frac{64}{3}$ \\
Write 48 over 3: $48 = \frac{144}{3}$ \\
Area of $R = \frac{144}{3} - \frac{64}{3}$ \\
Area of $R = \frac{80}{3}$

@q 11
@topic Shield area, circular arcs
@marks 5
@question
Let $O$ be the centre of the circle of radius $r$ \\
$A$, $B$, $C$ are placed symmetrically, so they are 120 degrees apart round the circle \\
angle $AOB$ = angle $BOC$ = angle $COA$ = $\frac{2\pi}{3}$ \\
Triangle $ABC$ is equilateral, so each of its angles is $\frac{\pi}{3}$ \\
angle $ACB = \frac{\pi}{3}$ \\
Triangle $OBC$ has $OB = OC = r$, so it is isosceles with apex angle $\frac{2\pi}{3}$ \\
The base angles are $\frac{1}{2}\left( \pi - \frac{2\pi}{3} \right) = \frac{\pi}{6}$ \\
angle $OBC = \frac{\pi}{6}$ \\
Find the side $BC$ by splitting the isosceles triangle $OBC$ in half down the middle: \\
$BC = 2 \times r\cos \frac{\pi}{6}$ \\
$\cos \frac{\pi}{6} = \frac{\sqrt{3}}{2}$ \\
$BC = 2r \times \frac{\sqrt{3}}{2}$ \\
$BC = r\sqrt{3}$ \\
The arc $AB$ is part of a circle with centre $C$, so its radius is $CA = CB = r\sqrt{3}$ and its angle is $\frac{\pi}{3}$ \\
Area of sector $ABC$ (centre $C$) $= \frac{1}{2}\left( r\sqrt{3} \right)^{2}\left( \frac{\pi}{3} \right)$ \\
$\left( r\sqrt{3} \right)^{2} = 3r^{2}$ \\
$= \frac{1}{2} \times 3r^{2} \times \frac{\pi}{3}$ \\
$= \frac{\pi r^{2}}{2}$ \\
The shield is made of three such sectors, which overlap, so subtract the overlaps \\
Area of triangle $OBC$ $= \frac{1}{2}r^{2}\sin \frac{2\pi}{3}$ \\
$\sin \frac{2\pi}{3} = \frac{\sqrt{3}}{2}$ \\
$= \frac{1}{2}r^{2} \times \frac{\sqrt{3}}{2}$ \\
$= \frac{r^{2}\sqrt{3}}{4}$ \\
Triangles $OBC$ and $OAC$ are the same size, so \\
One third of $R$ = sector $ABC$ $-$ triangle $OBC$ $-$ triangle $OAC$ \\
$\frac{1}{3}R = \frac{\pi r^{2}}{2} - 2\left( \frac{r^{2}\sqrt{3}}{4} \right)$ \\
$\frac{1}{3}R = \frac{\pi r^{2}}{2} - \frac{r^{2}\sqrt{3}}{2}$ \\
Multiply by 3: \\
$R = \frac{3\pi r^{2}}{2} - \frac{3\sqrt{3}r^{2}}{2}$ \\
$R = \left( \frac{3}{2}\pi - \frac{3}{2}\sqrt{3} \right)r^{2}$ \\
(Check with $r = 1$: $\frac{3}{2}(3.1416 - 1.7321) = 2.1142$, and the same shape computed as three sectors minus two equilateral triangles of side $\sqrt{3}$ gives $3(1.5708) - 2(1.2990) = 2.1142$)

@q 12
@topic R sin form, sunlight hours model
@marks 11
@question
(a) Write $K\sin (\theta - \alpha)$ out using the compound angle formula: \\
$K\sin (\theta - \alpha) = K\sin \theta \cos \alpha - K\cos \theta \sin \alpha$ \\
Compare with $2\sin \theta - 3.75\cos \theta$ \\
Coefficient of $\sin \theta$: $K\cos \alpha = 2$ \\
Coefficient of $\cos \theta$: $K\sin \alpha = 3.75$ \\
Square both equations and add: \\
$K^{2}\cos^{2} \alpha + K^{2}\sin^{2} \alpha = 2^{2} + 3.75^{2}$ \\
$K^{2}(\cos^{2} \alpha + \sin^{2} \alpha) = 4 + 14.0625$ \\
$K^{2} = 18.0625$ \\
$K = 4.25$ \\
Divide $K\sin \alpha = 3.75$ by $K\cos \alpha = 2$: \\
$\tan \alpha = \frac{3.75}{2}$ \\
$\tan \alpha = 1.875$ \\
$\alpha = \tan^{-1}(1.875)$ \\
$\alpha = 61.93$ degrees \\
$2\sin \theta - 3.75\cos \theta = 4.25\sin (\theta - 61.93)$ \\
(b)(i) Use part (a) with $\theta = 30t$: \\
$h = A + 4.25\sin (30t - 61.93)$ degrees \\
The largest value of sine is 1, so the maximum of $h$ is $A + 4.25$ \\
$A + 4.25 = 16.5$ \\
Subtract 4.25: \\
$A = 12.25$ \\
$h = 12.25 + 4.25\sin (30t - 61.93)$ degrees \\
(ii) The smallest value of sine is $-1$, so the minimum of $h$ is $A - 4.25$ \\
$12.25 - 4.25 = 8$ \\
The minimum is 8 hours \\
(c) The spring equinox is in March, so take $t = 2$ (two months after January) \\
$h = 12.25 + 4.25\sin (30 \times 2 - 61.93)$ \\
$30 \times 2 = 60$ \\
$60 - 61.93 = -1.93$ \\
$\sin (-1.93 \text{ degrees}) = -0.03367$ \\
$4.25 \times (-0.03367) = -0.1431$ \\
$h = 12.25 - 0.1431$ \\
$h = 12.107$ hours \\
Or solve $h = 12$ for $t$: \\
$12.25 + 4.25\sin (30t - 61.93) = 12$ \\
$4.25\sin (30t - 61.93) = -0.25$ \\
$\sin (30t - 61.93) = -0.05882$ \\
$30t - 61.93 = -3.373$ \\
$30t = 58.557$ \\
$t = 1.95$ \\
The model gives 12.1 hours at $t = 2$ and the real value is 12 hours, and it gives exactly 12 hours at $t = 1.95$, which is about 2 \\
These are very close, so the model is reasonable \\
(d) The rainfall is smallest when $\sin (30t + 60)$ degrees takes its smallest value, $-1$ \\
$30t + 60 = 270$ \\
Subtract 60: \\
$30t = 210$ \\
Divide by 30: \\
$t = 7$ \\
(The next time would be $30t + 60 = 630$, which is $t = 19$, outside the year) \\
So $T = 7$ \\
Put $t = 7$ into the sunlight model: \\
$30t = 210$ \\
$h = 12.25 + 4.25\sin (210 - 61.93)$ \\
$210 - 61.93 = 148.07$ \\
$\sin 148.07 = 0.5307$ \\
$4.25 \times 0.5307 = 2.2555$ \\
$h = 12.25 + 2.2555$ \\
$h = 14.50$ hours \\
(Check with the other form: $12.25 + 2\sin 210 - 3.75\cos 210 = 12.25 - 1 + 3.2476 = 14.4976$) \\
The mean daily sunlight is 14.5 hours, which is 14 hours 30 minutes

@q 13
@topic Substitution x = a tan^2 t, integrate
@marks 8
@question
(a) $x = a\tan^{2} \theta$ \\
Differentiate: $\frac{dx}{d\theta} = a \times 2\tan \theta \times \sec^{2} \theta$ \\
$\frac{dx}{d\theta} = 2a\sec^{2} \theta \tan \theta$ \\
$dx = 2a\sec^{2} \theta \tan \theta \, d\theta$ \\
Replace $x$ inside the square root: \\
$a + x = a + a\tan^{2} \theta$ \\
Factorise out $a$: \\
$a + x = a(1 + \tan^{2} \theta)$ \\
Use $1 + \tan^{2} \theta = \sec^{2} \theta$: \\
$a + x = a\sec^{2} \theta$ \\
$\sqrt{a + x} = \sqrt{a}\sec \theta$ \\
(taking $\sec \theta > 0$ for $\theta$ between 0 and $\frac{\pi}{4}$) \\
Put everything into the integral: \\
$x\sqrt{a + x} \, dx = a\tan^{2} \theta \times \sqrt{a}\sec \theta \times 2a\sec^{2} \theta \tan \theta \, d\theta$ \\
Collect the powers of $a$: $a \times a^{\frac{1}{2}} \times a = a^{\frac{5}{2}}$ \\
Collect the trig terms: $\tan^{2} \theta \times \tan \theta = \tan^{3} \theta$ \\
$\sec \theta \times \sec^{2} \theta = \sec^{3} \theta$ \\
$x\sqrt{a + x} \, dx = 2a^{\frac{5}{2}}\tan^{3} \theta \sec^{3} \theta \, d\theta$ \\
Now the limits. When $x = 0$: $\tan^{2} \theta = 0$, so $\theta = 0$ \\
When $x = a$: $a\tan^{2} \theta = a$, so $\tan^{2} \theta = 1$ and $\tan \theta = 1$, so $\theta = \frac{\pi}{4}$ \\
$\int_{0}^{a} x\sqrt{a + x} \, dx = 2a^{\frac{5}{2}}\int_{0}^{\frac{\pi}{4}} \tan^{3} \theta \sec^{3} \theta \, d\theta$ as required \\
(b) Split $\tan^{3} \theta \sec^{3} \theta$ so that a $\sec \theta \tan \theta$ is on its own: \\
$\tan^{3} \theta \sec^{3} \theta = \tan^{2} \theta \times \sec^{2} \theta \times \sec \theta \tan \theta$ \\
Use $\tan^{2} \theta = \sec^{2} \theta - 1$: \\
$= (\sec^{2} \theta - 1)\sec^{2} \theta \times \sec \theta \tan \theta$ \\
Let $u = \sec \theta$, so $\frac{du}{d\theta} = \sec \theta \tan \theta$ \\
$\int (u^{2} - 1)u^{2} \, du$ \\
Expand the bracket: \\
$= \int \left( u^{4} - u^{2} \right) du$ \\
$= \frac{u^{5}}{5} - \frac{u^{3}}{3}$ \\
Replace $u$ by $\sec \theta$: \\
$\int \tan^{3} \theta \sec^{3} \theta \, d\theta = \frac{1}{5}\sec^{5} \theta - \frac{1}{3}\sec^{3} \theta$ \\
Upper limit $\theta = \frac{\pi}{4}$: $\sec \frac{\pi}{4} = \sqrt{2}$ \\
$\sec^{3} \frac{\pi}{4} = 2\sqrt{2}$ \\
$\sec^{5} \frac{\pi}{4} = 4\sqrt{2}$ \\
$\frac{4\sqrt{2}}{5} - \frac{2\sqrt{2}}{3}$ \\
Write over the denominator 15: \\
$= \frac{12\sqrt{2}}{15} - \frac{10\sqrt{2}}{15}$ \\
$= \frac{2\sqrt{2}}{15}$ \\
Lower limit $\theta = 0$: $\sec 0 = 1$ \\
$\frac{1}{5} - \frac{1}{3}$ \\
$= \frac{3}{15} - \frac{5}{15}$ \\
$= -\frac{2}{15}$ \\
Subtract the lower limit from the upper limit: \\
$\frac{2\sqrt{2}}{15} - \left( -\frac{2}{15} \right)$ \\
$= \frac{2\sqrt{2}}{15} + \frac{2}{15}$ \\
Multiply by $2a^{\frac{5}{2}}$ from part (a): \\
$\int_{0}^{a} x\sqrt{a + x} \, dx = 2a^{\frac{5}{2}}\left( \frac{2\sqrt{2}}{15} + \frac{2}{15} \right)$ \\
$= a^{\frac{5}{2}}\left( \frac{4\sqrt{2}}{15} + \frac{4}{15} \right)$ \\
So $p = \frac{4}{15}$ and $q = \frac{4}{15}$ \\
(Check with $a = 1$: $\int_{0}^{1} x\sqrt{1 + x} \, dx = \frac{4\sqrt{2} + 4}{15} = 0.6438$)

@q 14
@topic Conical vessel, differential equation
@marks 9
@question
(a) The volume of a cone is proportional to the cube of its depth, since the radius is in proportion to the depth \\
$V = ch^{3}$ for a constant $c$ \\
Take the cube root of both sides: \\
$h = \left( \frac{V}{c} \right)^{\frac{1}{3}}$ \\
So $h$ is proportional to $V^{\frac{1}{3}}$ \\
The volume is decreasing at a rate proportional to $h$: \\
$-\frac{dV}{dt}$ is proportional to $h$ \\
$-\frac{dV}{dt}$ is proportional to $V^{\frac{1}{3}}$ \\
$\frac{dV}{dt} = -kV^{\frac{1}{3}}$ where $k$ is a positive constant, as required \\
(b) At $t = 5$, $V = 8$ and $\frac{dV}{dt} = -0.6$: \\
$-0.6 = -k(8)^{\frac{1}{3}}$ \\
$8^{\frac{1}{3}} = 2$ \\
$0.6 = 2k$ \\
Divide by 2: \\
$k = 0.3$ \\
$\frac{dV}{dt} = -0.3V^{\frac{1}{3}}$ \\
Separate the variables: \\
$V^{-\frac{1}{3}} dV = -0.3 \, dt$ \\
Integrate both sides: \\
$\frac{V^{\frac{2}{3}}}{\frac{2}{3}} = -0.3t + c$ \\
$\frac{3}{2}V^{\frac{2}{3}} = -0.3t + c$ \\
At $t = 5$, $V = 8$: \\
$8^{\frac{2}{3}} = 4$ \\
$\frac{3}{2} \times 4 = -0.3 \times 5 + c$ \\
$6 = -1.5 + c$ \\
Add 1.5: \\
$c = 7.5$ \\
$\frac{3}{2}V^{\frac{2}{3}} = 7.5 - 0.3t$ \\
Multiply both sides by $\frac{2}{3}$: \\
$V^{\frac{2}{3}} = 5 - 0.2t$ as required \\
(c) Put $t = 12$: \\
$V^{\frac{2}{3}} = 5 - 0.2 \times 12$ \\
$0.2 \times 12 = 2.4$ \\
$V^{\frac{2}{3}} = 2.6$ \\
Raise both sides to the power $\frac{3}{2}$: \\
$V = 2.6^{\frac{3}{2}}$ \\
$\sqrt{2.6} = 1.61245$ \\
$V = 2.6 \times 1.61245$ \\
$V = 4.1924$ \\
$V = 4.2$ cm$^{3}$ to 2 significant figures

@q 15
@topic Positive quadratic, proof by contradiction
@marks 6
@question
(i) Complete the square: \\
$k^{2} - 6k = (k - 3)^{2} - 9$ \\
$k^{2} - 6k + 10 = (k - 3)^{2} - 9 + 10$ \\
$k^{2} - 6k + 10 = (k - 3)^{2} + 1$ \\
A square is never negative: $(k - 3)^{2} \geq 0$ \\
So $(k - 3)^{2} + 1 \geq 1$ \\
So $k^{2} - 6k + 10$ is always at least 1, which is positive, for all real $k$ \\
(ii) Maria's strategy is proof by contradiction \\
She assumes the proposition is false: positive integers $x$ and $y$ do exist with $(2x + 3y)(x - 3y) = 45$ \\
She then tries to reach something impossible \\
$x$ and $y$ are positive, so $2x + 3y > 0$ \\
The product is 45, which is positive, so $x - 3y$ must be positive too \\
So both factors are positive integers that multiply to 45 \\
The pairs of positive factors of 45 are $1 \times 45$, $3 \times 15$ and $5 \times 9$ \\
Also $2x + 3y > x - 3y$, since $x + 6y > 0$ \\
So $2x + 3y$ is the larger factor in each pair, which leaves just 3 cases \\
Maria uses proof by exhaustion: she checks every case \\
The case she shows is $2x + 3y = 9$ and $x - 3y = 5$, which gives $3x = 14$ and $x$ is not an integer \\
Case: $2x + 3y = 45$ and $x - 3y = 1$ \\
Add the equations: $3x = 46$, so $x$ is not an integer \\
Case: $2x + 3y = 15$ and $x - 3y = 3$ \\
Add the equations: $3x = 18$, so $x = 6$ \\
Put $x = 6$ into $x - 3y = 3$: $6 - 3y = 3$, so $y = 1$ \\
Check: $(2 \times 6 + 3 \times 1)(6 - 3 \times 1) = 15 \times 3 = 45$ \\
This case gives positive integers $x = 6$ and $y = 1$ \\
So Maria will not reach a contradiction \\
Positive integers $x = 6$, $y = 1$ do exist, so this is a counter-example \\
The conclusion she should reach is that the proposition is false
