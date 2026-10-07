@paper P1 Shadow June 2019

@q 1
@topic Factor theorem, find b
@marks 3
@question
$(x + 1)$ is a factor of $f(x)$, so by the factor theorem $f(-1) = 0$ \\
$f(-1) = (-1)^{3} + 2b(-1)^{2} - 6(-1) - b$ \\
Evaluate the powers: $(-1)^{3} = -1$ and $(-1)^{2} = 1$ \\
$f(-1) = -1 + 2b + 6 - b$ \\
Collect the constants: $-1 + 6 = 5$ \\
Collect the $b$ terms: $2b - b = b$ \\
$f(-1) = b + 5$ \\
Set this equal to zero: \\
$b + 5 = 0$ \\
Subtract 5 from both sides: \\
$b = -5$ \\
(Check: $f(x) = x^{3} - 10x^{2} - 6x + 5$ and $f(-1) = -1 - 10 + 6 + 5 = 0$)

@q 2
@topic Small angle approximation, one root
@marks 5
@question
(a) Rearrange the equation to get the cosine curve on its own: \\
$2\cos 4x - 10x - 1 = 0$ \\
Add $10x$ and add 1 to both sides: \\
$2\cos 4x = 10x + 1$ \\
The roots are where the curve $y = 2\cos 4x$ meets the line $y = 10x + 1$ \\
Draw the line on Figure 1: it passes through $(0, 1)$ and has gradient 10 \\
So it rises 1 unit for every 0.1 across: very steep \\
At $x = 0$ the curve is at 2 and the line is at 1, so the line starts below the curve \\
The line climbs through the curve once, just to the right of the $y$ axis \\
The curve always stays between $-2$ and 2 \\
The line reaches 2 at $x = 0.1$ and is at $-2$ when $x = -0.3$ \\
Outside $-0.3 < x < 0.1$ the line is out of the range of the curve, so there is no crossing there \\
Inside that range the steep line crosses the curve only once \\
There is only one intersection, so the equation has only one root \\
(Check: let $g(x) = 10x + 1 - 2\cos 4x$) \\
$g'(x) = 10 + 8\sin 4x$ \\
Since $\sin 4x \geq -1$, $g'(x) \geq 2$, which is positive \\
So $g$ is always increasing and can only cross zero once \\
(b) Small angle approximation: $\cos \theta \approx 1 - \frac{\theta^{2}}{2}$ \\
Use $\theta = 4x$: $\cos 4x \approx 1 - \frac{(4x)^{2}}{2}$ \\
Square the bracket: $(4x)^{2} = 16x^{2}$ \\
$\cos 4x \approx 1 - \frac{16x^{2}}{2}$ \\
$\cos 4x \approx 1 - 8x^{2}$ \\
Substitute into $2\cos 4x - 10x - 1 = 0$: \\
$2(1 - 8x^{2}) - 10x - 1 \approx 0$ \\
Expand the bracket: \\
$2 - 16x^{2} - 10x - 1 \approx 0$ \\
Collect the constants: $2 - 1 = 1$ \\
$1 - 16x^{2} - 10x \approx 0$ \\
Multiply every term by $-1$ and reorder: \\
$16x^{2} + 10x - 1 = 0$ \\
Use the quadratic formula with $a = 16$, $b = 10$, $c = -1$ \\
$x = \frac{-10 \pm \sqrt{10^{2} - 4(16)(-1)}}{2(16)}$ \\
$x = \frac{-10 \pm \sqrt{100 + 64}}{32}$ \\
$x = \frac{-10 \pm \sqrt{164}}{32}$ \\
$\sqrt{164} = 12.8062$ \\
$x = \frac{-10 + 12.8062}{32} = \frac{2.8062}{32}$ \\
$x = 0.08770$ \\
$x = \frac{-10 - 12.8062}{32} = \frac{-22.8062}{32}$ \\
$x = -0.7127$ \\
Reject $x = -0.7127$: then $4x = -2.85$, which is not small, so the small angle approximation is not valid \\
Also part (a) showed the root lies between 0 and 0.1 \\
$\alpha = 0.088$ to 3 decimal places

@q 3
@topic Quotient rule, show dy/dx = A/(x+6)^n
@marks 5
@question
(a) Use the quotient rule with $u = 9x^{2} + 54x$ and $v = (x + 6)^{2}$ \\
$\frac{du}{dx} = 18x + 54$ \\
$\frac{dv}{dx} = 2(x + 6)$ \\
$\frac{dy}{dx} = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^{2}}$ \\
$\frac{dy}{dx} = \frac{(x + 6)^{2}(18x + 54) - (9x^{2} + 54x) \times 2(x + 6)}{(x + 6)^{4}}$ \\
Both terms on top have a factor $(x + 6)$. Divide top and bottom by $(x + 6)$: \\
$\frac{dy}{dx} = \frac{(x + 6)(18x + 54) - 2(9x^{2} + 54x)}{(x + 6)^{3}}$ \\
Expand $(x + 6)(18x + 54)$: \\
$= 18x^{2} + 54x + 108x + 324$ \\
$= 18x^{2} + 162x + 324$ \\
Expand $2(9x^{2} + 54x) = 18x^{2} + 108x$ \\
Subtract on the top: \\
$18x^{2} + 162x + 324 - 18x^{2} - 108x$ \\
The $x^{2}$ terms cancel: \\
$= 54x + 324$ \\
Factorise: $54x + 324 = 54(x + 6)$ \\
$\frac{dy}{dx} = \frac{54(x + 6)}{(x + 6)^{3}}$ \\
Cancel one factor of $(x + 6)$: \\
$\frac{dy}{dx} = \frac{54}{(x + 6)^{2}}$ \\
So $A = 54$ and $n = 2$ \\
(b) The top, 54, is positive \\
$(x + 6)^{2}$ is a square, so it is positive for every $x \ne -6$ \\
A positive number divided by a positive number is positive \\
So $\frac{dy}{dx} > 0$ for all $x \ne -6$

@q 4
@topic Binomial expansion, root approximation
@marks 6
@question
(a) Write the root as a power: \\
$\frac{1}{\sqrt{9 - x}} = (9 - x)^{-\frac{1}{2}}$ \\
Take 9 out of the bracket: $9 - x = 9\left( 1 - \frac{x}{9} \right)$ \\
$(9 - x)^{-\frac{1}{2}} = 9^{-\frac{1}{2}}\left( 1 - \frac{x}{9} \right)^{-\frac{1}{2}}$ \\
$9^{-\frac{1}{2}} = \frac{1}{\sqrt{9}} = \frac{1}{3}$ \\
Binomial expansion: $(1 + y)^{n} = 1 + ny + \frac{n(n - 1)}{2}y^{2} + \ldots$ \\
Here $n = -\frac{1}{2}$ and $y = -\frac{x}{9}$ \\
Second term: $ny = \left( -\frac{1}{2} \right)\left( -\frac{x}{9} \right) = \frac{x}{18}$ \\
Third term: $\frac{n(n - 1)}{2} = \frac{\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right)}{2}$ \\
$= \frac{\frac{3}{4}}{2} = \frac{3}{8}$ \\
$y^{2} = \left( -\frac{x}{9} \right)^{2} = \frac{x^{2}}{81}$ \\
Third term: $\frac{3}{8} \times \frac{x^{2}}{81} = \frac{3x^{2}}{648} = \frac{x^{2}}{216}$ \\
$\left( 1 - \frac{x}{9} \right)^{-\frac{1}{2}} = 1 + \frac{x}{18} + \frac{x^{2}}{216} + \ldots$ \\
Multiply by $\frac{1}{3}$: \\
$\frac{1}{3} \times 1 = \frac{1}{3}$ \\
$\frac{1}{3} \times \frac{x}{18} = \frac{x}{54}$ \\
$\frac{1}{3} \times \frac{x^{2}}{216} = \frac{x^{2}}{648}$ \\
$\frac{1}{\sqrt{9 - x}} = \frac{1}{3} + \frac{1}{54}x + \frac{1}{648}x^{2} + \ldots$ \\
(b)(i) The expansion of $\left( 1 - \frac{x}{9} \right)^{-\frac{1}{2}}$ is only valid when $\left| \frac{x}{9} \right| < 1$ \\
That means $|x| < 9$ \\
$x = -18$ has $|x| = 18 > 9$, so $x = -18$ should not be used \\
(ii) The terms in the expansion get smaller faster when $|x|$ is smaller \\
$x = \frac{2}{3}$ has the smallest $|x|$ \\
So $x = \frac{2}{3}$ gives the most accurate approximation to $\sqrt{3}$

@q 5
@topic Completing the square, sketch, range
@marks 10
@question
(a) Take out the factor 2 from the $x$ terms: \\
$2x^{2} + 8x + 11 = 2(x^{2} + 4x) + 11$ \\
Complete the square: $x^{2} + 4x = (x + 2)^{2} - 4$ \\
$2x^{2} + 8x + 11 = 2\left[ (x + 2)^{2} - 4 \right] + 11$ \\
Expand the outer bracket: \\
$= 2(x + 2)^{2} - 8 + 11$ \\
$= 2(x + 2)^{2} + 3$ \\
So $a = 2$, $b = 2$, $c = 3$ \\
(b) From part (a), $y = 2(x + 2)^{2} + 3$ \\
The squared term is never negative, so the minimum is when $x + 2 = 0$ \\
Minimum point: $(-2, 3)$ \\
The coefficient of $x^{2}$ is positive, so the curve is U shaped \\
$y$ intercept: put $x = 0$, $y = 11$ \\
So the curve meets the $y$ axis at $(0, 11)$ \\
The minimum value, 3, is above the $x$ axis, so the curve does not meet the $x$ axis \\
(Check the discriminant: $8^{2} - 4(2)(11) = 64 - 88 = -24$, which is negative) \\
(Diagram: a U shaped curve with its minimum at $(-2, 3)$, crossing the $y$ axis at $(0, 11)$ and staying above the $x$ axis) \\
(c)(i) Write the $x$ term of $g(x)$ in terms of $(x - 3)$: \\
$8x - 19 = 8(x - 3) + 24 - 19$ \\
$8x - 19 = 8(x - 3) + 5$ \\
$g(x) = 2(x - 3)^{2} + 8(x - 3) + 5$ \\
Replace $x$ by $(x - 3)$ in $f(x) = 2x^{2} + 8x + 11$: \\
$f(x - 3) = 2(x - 3)^{2} + 8(x - 3) + 11$ \\
Compare: $g(x)$ has $5$ where $f(x - 3)$ has $11$ \\
$5 = 11 - 6$ \\
$g(x) = f(x - 3) - 6$ \\
$f(x - 3)$ moves the curve 3 to the right \\
Then the $-6$ moves it 6 down \\
A translation by the column vector $(3, -6)$ \\
(ii) Use $2x^{2} + 8x + 11 = 2(x + 2)^{2} + 3$ \\
$h(x) = \frac{15}{2(x + 2)^{2} + 3}$ \\
$2(x + 2)^{2} \geq 0$, so the denominator is at least 3 \\
The denominator is smallest, 3, when $x = -2$ \\
$h(x)$ is largest then: $\frac{15}{3} = 5$ \\
As $x$ gets large the denominator gets large, so $h(x)$ gets close to 0 \\
The denominator is positive, so $h(x)$ is always positive and never 0 \\
$0 < h(x) \leq 5$

@q 6
@topic Trig equation 9 sin 2t = 16 tan t
@marks 8
@question
(a) Use the double angle formula $\sin 2\theta = 2\sin \theta \cos \theta$ \\
$9(2\sin \theta \cos \theta) = 16\tan \theta$ \\
$18\sin \theta \cos \theta = 16\tan \theta$ \\
Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$ \\
$18\sin \theta \cos \theta = 16\frac{\sin \theta}{\cos \theta}$ \\
$\tan \theta$ only exists when $\cos \theta \ne 0$, so multiply both sides by $\cos \theta$ \\
$18\sin \theta \cos^{2} \theta = 16\sin \theta$ \\
Subtract $16\sin \theta$ from both sides: \\
$18\sin \theta \cos^{2} \theta - 16\sin \theta = 0$ \\
Factorise out $2\sin \theta$ (do not divide by $\sin \theta$, or the solutions with $\sin \theta = 0$ are lost): \\
$2\sin \theta (9\cos^{2} \theta - 8) = 0$ \\
Either $\sin \theta = 0$ or $9\cos^{2} \theta - 8 = 0$ \\
Case 1: $\sin \theta = 0$ \\
$\theta = -180, 0, 180 \text{ degrees}$ \\
Case 2: $9\cos^{2} \theta = 8$ \\
Divide by 9: $\cos^{2} \theta = \frac{8}{9}$ \\
Square root both sides: $\cos \theta = \pm \sqrt{\frac{8}{9}}$ \\
$\cos \theta = \pm 0.94281$ \\
$\cos \theta = 0.94281$: $\theta = 19.471 \text{ degrees}$ \\
Cosine is even, so also $\theta = -19.471 \text{ degrees}$ \\
$\cos \theta = -0.94281$: $\theta = 180 - 19.471 = 160.529 \text{ degrees}$ \\
Also $\theta = -160.529 \text{ degrees}$ \\
Round to 1 decimal place and list all the solutions: \\
$\theta = -180, -160.5, -19.5, 0, 19.5, 160.5, 180 \text{ degrees}$ \\
(b) Let $\theta = x - 30$ \\
Then $2x - 60 = 2(x - 30) = 2\theta$ \\
So the equation is $9\sin 2\theta = 16\tan \theta$, exactly as in part (a) \\
Solve for $x$ using $x = \theta + 30$ \\
For $x$ to be positive we need $\theta > -30$ \\
The values of $\theta$ in part (a) above $-30$ are $-19.5$, 0, 19.5, ... \\
The smallest is $\theta = -19.471$ \\
$x = -19.471 + 30$ \\
$x = 10.529$ \\
The smallest positive solution is $x = 10.5$ degrees

@q 7
@topic Exponential model, caravan value
@marks 7
@question
(a) Try an exponential model $V = Ae^{-kt}$ with $A$ and $k$ positive constants \\
When $t = 0$ the value is 13 000: \\
$13000 = Ae^{0}$ \\
$e^{0} = 1$, so $A = 13000$ \\
When $t = 1$ the value is 5 900: \\
$5900 = 13000e^{-k}$ \\
Divide both sides by 13 000: \\
$e^{-k} = \frac{5900}{13000}$ \\
$e^{-k} = 0.45385$ \\
Take natural logs of both sides: \\
$-k = \ln 0.45385$ \\
$-k = -0.79000$ \\
$k = 0.79$ \\
$V = 13000e^{-0.79t}$ \\
(b) When $t = 3$: \\
$V = 13000e^{-0.79 \times 3}$ \\
$0.79 \times 3 = 2.37$ \\
$V = 13000e^{-2.37}$ \\
$e^{-2.37} = 0.093481$ \\
$V = 13000 \times 0.093481$ \\
$V = 1215$ (nearest pound) \\
The model predicts GBP 1215 and the actual value is GBP 1100 \\
Difference: $1215 - 1100 = 115$ \\
As a percentage of the actual value: $\frac{115}{1100} = 0.1045$, about 10 percent \\
The value has fallen from GBP 13 000 to about GBP 1100, so a difference of GBP 115 is small \\
So the model is reasonably reliable \\
(c) Caravan $B$ starts at the same value, so keep $A = 13000$ \\
It loses value more slowly, so decrease $k$ (a smaller $k$ makes $e^{-kt}$ fall more slowly)

@q 8
@topic Area under cubic, quartic verification
@marks 10
@question
(a) Expand the brackets: $(x + 1)(x - 4) = x^{2} - 4x + x - 4$ \\
$(x + 1)(x - 4) = x^{2} - 3x - 4$ \\
$y = x(x^{2} - 3x - 4)$ \\
$y = x^{3} - 3x^{2} - 4x$ \\
$R_{1}$ lies between $x = -1$ and $x = 0$ and is above the $x$ axis, so its area is the integral \\
Area of $R_{1} = \int_{-1}^{0} (x^{3} - 3x^{2} - 4x) dx$ \\
Integrate each term: \\
$= \left[ \frac{x^{4}}{4} - x^{3} - 2x^{2} \right]_{-1}^{0}$ \\
Upper limit $x = 0$: $0$ \\
Lower limit $x = -1$: $\frac{(-1)^{4}}{4} - (-1)^{3} - 2(-1)^{2}$ \\
$= \frac{1}{4} + 1 - 2$ \\
$= -\frac{3}{4}$ \\
Subtract the lower limit from the upper limit: \\
Area $= 0 - \left( -\frac{3}{4} \right)$ \\
Area $= \frac{3}{4}$ as required \\
(b) $R_{2}$ lies below the $x$ axis between $x = 0$ and $x = b$, so the integral is negative \\
Area of $R_{2} = -\int_{0}^{b} (x^{3} - 3x^{2} - 4x) dx$ \\
$\int_{0}^{b} (x^{3} - 3x^{2} - 4x) dx = \frac{b^{4}}{4} - b^{3} - 2b^{2} - 0$ \\
The areas are equal: \\
$-\left( \frac{b^{4}}{4} - b^{3} - 2b^{2} \right) = \frac{3}{4}$ \\
Multiply both sides by $-1$: \\
$\frac{b^{4}}{4} - b^{3} - 2b^{2} = -\frac{3}{4}$ \\
Multiply every term by 4: \\
$b^{4} - 4b^{3} - 8b^{2} = -3$ \\
Add 3 to both sides: \\
$b^{4} - 4b^{3} - 8b^{2} + 3 = 0$ \\
Now expand the given expression, starting with $(b + 1)^{2} = b^{2} + 2b + 1$ \\
$(b^{2} + 2b + 1)(b^{2} - 6b + 3)$ \\
$b^{2}(b^{2} - 6b + 3) = b^{4} - 6b^{3} + 3b^{2}$ \\
$2b(b^{2} - 6b + 3) = 2b^{3} - 12b^{2} + 6b$ \\
$1(b^{2} - 6b + 3) = b^{2} - 6b + 3$ \\
Add the three lines and collect like terms: \\
$b^{3}$ terms: $-6b^{3} + 2b^{3} = -4b^{3}$ \\
$b^{2}$ terms: $3b^{2} - 12b^{2} + b^{2} = -8b^{2}$ \\
$b$ terms: $6b - 6b = 0$ \\
Constant: $3$ \\
$(b + 1)^{2}(b^{2} - 6b + 3) = b^{4} - 4b^{3} - 8b^{2} + 3$ \\
This is the same quartic as above \\
So $b$ satisfies $(b + 1)^{2}(b^{2} - 6b + 3) = 0$ \\
(c) The equation was found using $\int_{0}^{b} y \, dx = -\frac{3}{4}$, which is a signed area \\
For $b = 5.449$, which is greater than 4, the curve is below the axis from 0 to 4 and above the axis from 4 to 5.449 \\
The signed area from 0 to 5.449 is $-\frac{3}{4}$ \\
The signed area from $-1$ to 0 is $+\frac{3}{4}$ \\
Add them: the signed area from $-1$ to 5.449 is $\frac{3}{4} - \frac{3}{4} = 0$ \\
So between $x = -1$ and $x = 5.449$ the area above the $x$ axis equals the area below it \\
(Diagram: the curve with $x$ intercepts $-1$, 0 and 4, and the line $x = 5.449$, with the areas above the axis ($R_{1}$ and the part from 4 to 5.449) equal to the area below the axis from 0 to 4) \\
5.449 does not give $R_{2}$ as defined, since $R_{2}$ needs $0 < b < 4$ \\
That is why only $b = 0.551$ is the answer to the problem

@q 9
@topic Logs, make p the subject, restriction
@marks 5
@question
(a) Use the addition law $\log a + \log b = \log ab$ on the right hand side: \\
$\log p = \log q + \log (p - q)$ \\
$\log p = \log \left[ q(p - q) \right]$ \\
Logs are one-to-one, so the numbers inside are equal: \\
$p = q(p - q)$ \\
Expand the bracket: \\
$p = pq - q^{2}$ \\
Add $q^{2}$ to both sides: \\
$p + q^{2} = pq$ \\
Subtract $p$ from both sides: \\
$q^{2} = pq - p$ \\
Factorise the right hand side: \\
$q^{2} = p(q - 1)$ \\
Divide both sides by $(q - 1)$: \\
$p = \frac{q^{2}}{q - 1}$ as required \\
(b) The denominator cannot be zero, so $q - 1 \ne 0$ \\
That gives $q \ne 1$ \\
We are told $p > 0$, so $\frac{q^{2}}{q - 1} > 0$ \\
$q^{2}$ is positive (as $q > 0$) \\
So $q - 1$ must be positive \\
Add 1 to both sides: $q > 1$ \\
The full restriction is $q > 1$ \\
(Check: for $q = 2$, $p = \frac{4}{1} = 4$, and $p > q > 0$ holds)

@q 10
@topic Proof n^2-2n+2 not divisible by 4
@marks 6
@question
(a) Every natural number $n$ is either even or odd, so deal with both cases \\
Case 1: $n$ is even, so $n = 2m$ where $m$ is an integer \\
$n^{2} - 2n + 2 = (2m)^{2} - 2(2m) + 2$ \\
$= 4m^{2} - 4m + 2$ \\
Factorise the first two terms: \\
$= 4(m^{2} - m) + 2$ \\
$4(m^{2} - m)$ is a multiple of 4 \\
Adding 2 leaves a remainder of 2 when divided by 4 \\
So it is not divisible by 4 \\
Case 2: $n$ is odd, so $n = 2m + 1$ where $m$ is an integer \\
$n^{2} - 2n + 2 = (2m + 1)^{2} - 2(2m + 1) + 2$ \\
Expand $(2m + 1)^{2} = 4m^{2} + 4m + 1$ \\
Expand $-2(2m + 1) = -4m - 2$ \\
$= 4m^{2} + 4m + 1 - 4m - 2 + 2$ \\
The $4m$ terms cancel and $-2 + 2 = 0$: \\
$= 4m^{2} + 1$ \\
$4m^{2}$ is a multiple of 4 \\
Adding 1 leaves a remainder of 1 when divided by 4 \\
So it is not divisible by 4 \\
Both cases give a non-multiple of 4 \\
So for all $n \in \mathbb{N}$, $n^{2} - 2n + 2$ is not divisible by 4 \\
(b) Test the statement $|4x - 19| \geq x - 4$ with values of $x$ \\
Try $x = 4.8$: \\
$4x - 19 = 19.2 - 19 = 0.2$, so $|4x - 19| = 0.2$ \\
$x - 4 = 0.8$ \\
$0.2 < 0.8$, so the statement is false for $x = 4.8$ \\
Try $x = 6$: \\
$4x - 19 = 24 - 19 = 5$, so $|4x - 19| = 5$ \\
$x - 4 = 2$ \\
$5 \geq 2$, so the statement is true for $x = 6$ \\
The statement is true for some values of $x$ and false for others \\
So it is sometimes true

@q 11
@topic Geometric series, race time model
@marks 7
@question
(a) Time for the first 6 km: $6 \times 6.2 = 37.2$ minutes \\
The 7th km takes 7% more than the 6th km, so multiply by 1.07 \\
7th km: $6.2 \times 1.07 = 6.634$ minutes \\
Time for the first 7 km: $37.2 + 6.634$ \\
$= 43.834$ minutes \\
(b) Each kilometre takes 1.07 times the one before, so the times form a geometric sequence \\
7th km: $6.2 \times 1.07^{1}$ \\
8th km: $6.2 \times 1.07^{2}$ \\
9th km: $6.2 \times 1.07^{3}$ \\
The power is 6 less than the kilometre number: \\
$r$th km: $6.2 \times 1.07^{r - 6}$ minutes \\
(c) Total time $= $ first 6 km $+$ km 7 to km 24 \\
Km 7 to km 24 is $24 - 7 + 1 = 18$ terms \\
First term: $a = 6.2 \times 1.07 = 6.634$ \\
Common ratio: $r = 1.07$ \\
Sum of a geometric series: $S_{n} = \frac{a(r^{n} - 1)}{r - 1}$ \\
$S_{18} = \frac{6.634(1.07^{18} - 1)}{1.07 - 1}$ \\
$1.07^{18} = 3.37993$ \\
$1.07^{18} - 1 = 2.37993$ \\
$6.634 \times 2.37993 = 15.7885$ \\
Denominator: $1.07 - 1 = 0.07$ \\
$S_{18} = \frac{15.7885}{0.07}$ \\
$S_{18} = 225.55$ minutes \\
Total time: $37.2 + 225.55$ \\
$= 262.75$ minutes \\
Convert the decimal part to seconds: $0.7496 \times 60 = 44.97$ \\
That is 45 seconds to the nearest second \\
Total time is about 262 minutes 45 seconds

@q 12
@topic Product rule, turning points, modelling
@marks 10
@question
(a) Use the product rule with $u = 12e^{-\frac{x}{3}}$ and $v = \sin x$ \\
$\frac{du}{dx} = 12 \times \left( -\frac{1}{3} \right)e^{-\frac{x}{3}}$ \\
$\frac{du}{dx} = -4e^{-\frac{x}{3}}$ \\
$\frac{dv}{dx} = \cos x$ \\
$f'(x) = \frac{du}{dx}v + u\frac{dv}{dx}$ \\
$f'(x) = -4e^{-\frac{x}{3}}\sin x + 12e^{-\frac{x}{3}}\cos x$ \\
Factorise out $e^{-\frac{x}{3}}$: \\
$f'(x) = e^{-\frac{x}{3}}(12\cos x - 4\sin x)$ \\
Turning points are where $f'(x) = 0$: \\
$e^{-\frac{x}{3}}(12\cos x - 4\sin x) = 0$ \\
$e^{-\frac{x}{3}}$ is never zero, so \\
$12\cos x - 4\sin x = 0$ \\
Add $4\sin x$ to both sides: \\
$12\cos x = 4\sin x$ \\
$\cos x \ne 0$ here (if it were, the equation would give $\sin x = 0$ too, which is impossible), so divide both sides by $4\cos x$ \\
$\frac{12}{4} = \frac{\sin x}{\cos x}$ \\
$3 = \tan x$ \\
So $\tan x = 3$ as required \\
(b) $H(t) = |f(t)|$, so every part of the curve below the $t$ axis is reflected upwards \\
The graph starts at the origin \\
It is a series of arches, all above the $t$ axis \\
The arches touch the $t$ axis at $t = \pi, 2\pi, 3\pi, \ldots$ \\
Each arch is lower than the one before, because of the factor $e^{-\frac{t}{3}}$ \\
In the long term $H \to 0$: the arches shrink towards the $t$ axis \\
(Diagram: arches above the $t$ axis starting at the origin, touching the axis at $t = \pi, 2\pi, 3\pi$ and getting smaller towards the $t$ axis) \\
(c) The ball touches the ground when $H = 0$, at $t = \pi, 2\pi, \ldots$ \\
So the first bounce is at $t = \pi$ and the second at $t = 2\pi$ \\
The maximum between them is a turning point, where $\tan t = 3$ \\
$t = \tan^{-1} 3 = 1.2490$ is the first solution \\
Tangent repeats every $\pi$, so the solution between $\pi$ and $2\pi$ is: \\
$t = \pi + 1.2490$ \\
$t = 4.3906$ \\
Substitute into $H(t)$: \\
$H = 12e^{-\frac{4.3906}{3}}|\sin 4.3906|$ \\
$\frac{4.3906}{3} = 1.46355$ \\
$e^{-1.46355} = 0.23141$ \\
$12 \times 0.23141 = 2.7769$ \\
$\sin 4.3906 = -0.94868$ \\
$|\sin 4.3906| = 0.94868$ \\
$H = 2.7769 \times 0.94868$ \\
$H = 2.634$ \\
The maximum height is 2.63 m (3 significant figures) \\
(d) The model has the bounces at $t = \pi, 2\pi, 3\pi, \ldots$, which are always $\pi$ seconds apart \\
In real life each bounce is lower than the last, so the ball spends less time in the air each time \\
The gaps between bounces should get shorter, not stay the same \\
So the model should not be used to predict the time of each bounce

@q 13
@topic Asymptotes, partial fractions, ln area
@marks 11
@question
(a)(i) The vertical asymptotes are where the denominator is zero \\
$(2x - q)(x + 3) = 0$ gives $x = \frac{q}{2}$ and $x = -3$ \\
The asymptotes are $x = 1$ and $x = -3$, so $\frac{q}{2} = 1$ \\
Multiply both sides by 2: $q = 2$ \\
(ii) Put $q = 2$ into the equation: \\
$y = \frac{p - 3x}{(2x - 2)(x + 3)}$ \\
The curve passes through $\left( 2, \frac{3}{2} \right)$, so put $x = 2$ and $y = \frac{3}{2}$ \\
$\frac{3}{2} = \frac{p - 3(2)}{(2(2) - 2)(2 + 3)}$ \\
$\frac{3}{2} = \frac{p - 6}{(2)(5)}$ \\
$\frac{3}{2} = \frac{p - 6}{10}$ \\
Multiply both sides by 10: \\
$15 = p - 6$ \\
Add 6 to both sides: \\
$p = 21$ \\
(b) With $p = 21$ and $q = 2$: $y = \frac{21 - 3x}{(2x - 2)(x + 3)}$ \\
Write the bottom as $2(x - 1)(x + 3)$ \\
Use partial fractions: $\frac{21 - 3x}{(2x - 2)(x + 3)} = \frac{A}{2x - 2} + \frac{B}{x + 3}$ \\
Multiply both sides by $(2x - 2)(x + 3)$: \\
$21 - 3x = A(x + 3) + B(2x - 2)$ \\
Put $x = 1$ (this makes the $B$ term zero): \\
$21 - 3 = A(4)$ \\
$18 = 4A$ \\
$A = \frac{9}{2}$ \\
Put $x = -3$ (this makes the $A$ term zero): \\
$21 + 9 = B(-6 - 2)$ \\
$30 = -8B$ \\
$B = -\frac{15}{4}$ \\
$y = \frac{9}{2(2x - 2)} - \frac{15}{4(x + 3)}$ \\
Simplify the first fraction: $2(2x - 2) = 4(x - 1)$ \\
$y = \frac{9}{4(x - 1)} - \frac{15}{4(x + 3)}$ \\
The curve meets the $x$ axis when $21 - 3x = 0$, so $x = 7$ \\
$R$ is between $x = 5$ and $x = 7$, above the axis \\
Area of $R = \int_{5}^{7} \left( \frac{9}{4(x - 1)} - \frac{15}{4(x + 3)} \right) dx$ \\
Integrate each term (both brackets are positive on this interval): \\
$= \left[ \frac{9}{4}\ln (x - 1) - \frac{15}{4}\ln (x + 3) \right]_{5}^{7}$ \\
Upper limit $x = 7$: $\frac{9}{4}\ln 6 - \frac{15}{4}\ln 10$ \\
Lower limit $x = 5$: $\frac{9}{4}\ln 4 - \frac{15}{4}\ln 8$ \\
Area $= \frac{9}{4}\ln 6 - \frac{15}{4}\ln 10 - \frac{9}{4}\ln 4 + \frac{15}{4}\ln 8$ \\
Write each log in terms of $\ln 2$, $\ln 3$, $\ln 5$: \\
$\ln 6 = \ln 2 + \ln 3$ \\
$\ln 10 = \ln 2 + \ln 5$ \\
$\ln 4 = 2\ln 2$ \\
$\ln 8 = 3\ln 2$ \\
Area $= \frac{9}{4}(\ln 2 + \ln 3) - \frac{15}{4}(\ln 2 + \ln 5) - \frac{9}{4}(2\ln 2) + \frac{15}{4}(3\ln 2)$ \\
Expand the brackets: \\
$= \frac{9}{4}\ln 2 + \frac{9}{4}\ln 3 - \frac{15}{4}\ln 2 - \frac{15}{4}\ln 5 - \frac{18}{4}\ln 2 + \frac{45}{4}\ln 2$ \\
Collect the $\ln 2$ terms: $\frac{9 - 15 - 18 + 45}{4} = \frac{21}{4}$ \\
Area $= \frac{21}{4}\ln 2 + \frac{9}{4}\ln 3 - \frac{15}{4}\ln 5$ \\
So $a = \frac{21}{4}$, $b = \frac{9}{4}$, $c = -\frac{15}{4}$ \\
(Check: $3.6390 + 2.4719 - 6.0354 = 0.0755$, which matches a numerical integration of the curve from 5 to 7)

@q 14
@topic Implicit curve x = 9 sin 2y, derivative
@marks 7
@question
(a) Differentiate $x = 9\sin 2y$ with respect to $y$: \\
$\frac{dx}{dy} = 9 \times 2\cos 2y$ \\
$\frac{dx}{dy} = 18\cos 2y$ \\
Invert to get $\frac{dy}{dx}$: \\
$\frac{dy}{dx} = \frac{1}{18\cos 2y}$ \\
At the origin $y = 0$: \\
$\cos 0 = 1$ \\
$\frac{dy}{dx} = \frac{1}{18}$ \\
(b)(i) Small angle approximation: $\sin \theta \approx \theta$ \\
So $\sin 2y \approx 2y$ \\
$x = 9\sin 2y \approx 9(2y)$ \\
$x \approx 18y$ \\
(ii) Divide both sides by 18: $y \approx \frac{x}{18}$ \\
This is a straight line through the origin with gradient $\frac{1}{18}$ \\
That is the same as the gradient of $C$ at the origin found in part (a) \\
So the small angle approximation gives the tangent to $C$ at the origin \\
(c) From $x = 9\sin 2y$: \\
$\sin 2y = \frac{x}{9}$ \\
Use $\sin^{2} 2y + \cos^{2} 2y = 1$ \\
$\cos^{2} 2y = 1 - \sin^{2} 2y$ \\
$\cos^{2} 2y = 1 - \frac{x^{2}}{81}$ \\
For $-\frac{\pi}{4} < y < \frac{\pi}{4}$ we have $-\frac{\pi}{2} < 2y < \frac{\pi}{2}$ \\
So $\cos 2y$ is positive and we take the positive root \\
$\cos 2y = \sqrt{1 - \frac{x^{2}}{81}}$ \\
Write over a common denominator: $1 - \frac{x^{2}}{81} = \frac{81 - x^{2}}{81}$ \\
$\cos 2y = \frac{\sqrt{81 - x^{2}}}{\sqrt{81}}$ \\
$\cos 2y = \frac{\sqrt{81 - x^{2}}}{9}$ \\
Substitute into $\frac{dy}{dx} = \frac{1}{18\cos 2y}$: \\
$\frac{dy}{dx} = \frac{1}{18 \times \frac{\sqrt{81 - x^{2}}}{9}}$ \\
Simplify $18 \times \frac{1}{9} = 2$: \\
$\frac{dy}{dx} = \frac{1}{2\sqrt{81 - x^{2}}}$ \\
So $a = 2$ and $b = 81$
