@paper P1 Shadow June 2025

@q 1
@topic Transformations of a point
@marks 4
@question
(a) Adding 3 to $f(x)$ moves the curve up 3 units \\
The $x$ coordinate stays the same and the $y$ coordinate goes up by 3: \\
$y = -2 + 3 = 1$ \\
$P$ is mapped to $(-3, 1)$ \\
(b) $y = f^{-1}(x)$ is the reflection of $y = f(x)$ in the line $y = x$ \\
Reflecting in $y = x$ swaps the $x$ and $y$ coordinates: \\
$(-3, -2) \to (-2, -3)$ \\
$P$ is mapped to $(-2, -3)$ \\
(c) Work from the inside out: first $f(x + 4)$, then the modulus, then the 3 \\
Step 1: $y = f(x + 4)$ moves the curve 4 units to the left \\
Subtract 4 from the $x$ coordinate: $x = -3 - 4 = -7$ \\
The $y$ coordinate stays the same, so we have $(-7, -2)$ \\
Step 2: $y = |f(x + 4)|$ turns every negative $y$ value positive \\
$|-2| = 2$ \\
We now have $(-7, 2)$ \\
Step 3: $y = 3|f(x + 4)|$ stretches the curve vertically by a factor of 3 \\
Multiply the $y$ coordinate by 3: $3 \times 2 = 6$ \\
$P$ is mapped to $(-7, 6)$

@q 2
@topic Circle centre, radius, point inside
@marks 5
@question
(a)(i) The equation is in the form $(x - a)^{2} + (y - b)^{2} = r^{2}$ with centre $(a, b)$ \\
Compare $(x - 12)^{2}$ with $(x - a)^{2}$: $a = 12$ \\
Write $(y + 5)^{2}$ as $(y - (-5))^{2}$ and compare with $(y - b)^{2}$: $b = -5$ \\
The centre is $(12, -5)$ \\
(ii) The right-hand side is $r^{2}$, so $r^{2} = 180$ \\
Take the positive square root: \\
$r = \sqrt{180}$ \\
Write 180 as a product with a square number: $180 = 36 \times 5$ \\
$r = \sqrt{36 \times 5}$ \\
$r = \sqrt{36} \times \sqrt{5}$ \\
$r = 6\sqrt{5}$ \\
(b) The origin is inside the circle if its distance from the centre is less than the radius \\
Distance from the centre $(12, -5)$ to the origin $(0, 0)$: \\
$d = \sqrt{(12 - 0)^{2} + (-5 - 0)^{2}}$ \\
$d = \sqrt{144 + 25}$ \\
$d = \sqrt{169}$ \\
$d = 13$ \\
Now compare $d$ with $r = 6\sqrt{5}$ by squaring both: \\
$d^{2} = 169$ and $r^{2} = 180$ \\
$169 < 180$, so $d < r$ \\
(Check: $6\sqrt{5} = 13.416...$, which is bigger than 13) \\
The distance to the origin (13) is less than the radius ($6\sqrt{5}$), so the origin lies inside the circle \\
Alt: put $(0, 0)$ into the left-hand side: $(-12)^{2} + 5^{2} = 144 + 25 = 169$ \\
$169 < 180$, so the origin is inside the circle

@q 3
@topic Arithmetic sequence, find k, sum
@marks 5
@question
(a) In an arithmetic sequence the difference between consecutive terms is constant \\
Second term minus first term = third term minus second term: \\
$(2k + 3) - 16 = 3k - (2k + 3)$ \\
Simplify the left-hand side: \\
$2k + 3 - 16 = 2k - 13$ \\
Remove the bracket on the right-hand side, changing both signs: \\
$3k - 2k - 3 = k - 3$ \\
So $2k - 13 = k - 3$ \\
Subtract $k$ from both sides: \\
$k - 13 = -3$ \\
Add 13 to both sides: \\
$k = 10$ \\
(Check: the terms are 16, 23, 30 and the differences are 7 and 7) \\
(b) The first term is $a = 16$ \\
The common difference is $d = 23 - 16 = 7$ \\
Use the sum formula $S_{n} = \frac{n}{2}\{ 2a + (n - 1)d \}$ with $n = 40$ \\
$S_{40} = \frac{40}{2}\{ 2(16) + 39(7) \}$ \\
Evaluate each product: $2(16) = 32$ and $39(7) = 273$ \\
$S_{40} = 20\{ 32 + 273 \}$ \\
$S_{40} = 20 \times 305$ \\
$S_{40} = 6100$

@q 4
@topic Factor theorem, distinct roots
@marks 5
@question
(a) $f(-2) = 0$, so by the factor theorem $(x + 2)$ is a factor \\
So $a = 2$ and we write $f(x) = (x + 2)(x^{2} + bx + c)$ \\
Expand the right-hand side, multiplying each term of the second bracket by $x$ and then by 2: \\
$x^{3} + bx^{2} + cx + 2x^{2} + 2bx + 2c$ \\
Collect like terms: \\
$x^{3} + (b + 2)x^{2} + (c + 2b)x + 2c$ \\
Compare coefficients with $x^{3} - 4x^{2} - 3x + 18$ \\
Coefficient of $x^{2}$: $b + 2 = -4$ \\
Subtract 2 from both sides: \\
$b = -6$ \\
Constant term: $2c = 18$ \\
Divide both sides by 2: \\
$c = 9$ \\
(Check with the $x$ term: $c + 2b = 9 + 2(-6) = 9 - 12 = -3$, which matches) \\
$f(x) = (x + 2)(x^{2} - 6x + 9)$ \\
(b) Set $f(x) = 0$: \\
$(x + 2)(x^{2} - 6x + 9) = 0$ \\
Factorise the quadratic. Two numbers that multiply to 9 and add to $-6$ are $-3$ and $-3$: \\
$x^{2} - 6x + 9 = (x - 3)(x - 3)$ \\
$x^{2} - 6x + 9 = (x - 3)^{2}$ \\
$(x + 2)(x - 3)^{2} = 0$ \\
Each factor can be zero: $x + 2 = 0$ or $(x - 3)^{2} = 0$ \\
$x = -2$ or $x = 3$ \\
$x = 3$ is a repeated root, so it counts as one distinct root \\
There are exactly 2 distinct roots, $x = -2$ and $x = 3$, as required

@q 5
@topic Sum as limit of integral, ln
@marks 3
@question
(a) A sum of strips $\sum f(x) \delta x$ becomes an integral as $\delta x \to 0$ \\
The first value of $x$ is $a$ and the last is $a^{4}$, so these are the limits: \\
$\lim_{\delta x \to 0} \sum_{x=a}^{a^{4}} \frac{2}{x} \delta x = \int_{a}^{a^{4}} \frac{2}{x} dx$ \\
(b) Integrate $\frac{2}{x}$ using $\int \frac{1}{x} dx = \ln x$: \\
$\int_{a}^{a^{4}} \frac{2}{x} dx = \left[ 2 \ln x \right]_{a}^{a^{4}}$ \\
Substitute the upper limit, then the lower limit, and subtract: \\
$= 2 \ln (a^{4}) - 2 \ln a$ \\
Use the power law $\ln (a^{n}) = n \ln a$ on the first term: \\
$\ln (a^{4}) = 4 \ln a$ \\
$= 2(4 \ln a) - 2 \ln a$ \\
$= 8 \ln a - 2 \ln a$ \\
$= 6 \ln a$ \\
Compare with $k \ln a$: \\
$k = 6$

@q 6
@topic Hang-glider model A - Bt^(2/3)
@marks 7
@question
(a) Use the first piece of information: $h = 74$ when $t = 1$ \\
$74 = A - B(1)^{\frac{2}{3}}$ \\
$1^{\frac{2}{3}} = 1$ \\
Equation 1: $74 = A - B$ \\
Use the second piece of information: $h = 56$ when $t = 8$ \\
$56 = A - B(8)^{\frac{2}{3}}$ \\
Work out $8^{\frac{2}{3}}$: take the cube root of 8, then square it: \\
$8^{\frac{2}{3}} = (\sqrt[3]{8})^{2} = 2^{2} = 4$ \\
Equation 2: $56 = A - 4B$ \\
Subtract equation 2 from equation 1 to remove $A$: \\
$74 - 56 = (A - B) - (A - 4B)$ \\
$18 = A - B - A + 4B$ \\
$18 = 3B$ \\
Divide both sides by 3: \\
$B = 6$ \\
Substitute $B = 6$ into equation 1: \\
$74 = A - 6$ \\
Add 6 to both sides: \\
$A = 80$ \\
(Check in equation 2: $80 - 4(6) = 80 - 24 = 56$) \\
The model is $h = 80 - 6t^{\frac{2}{3}}$ \\
(b) The hang-glider lands when $h = 0$, so find $t$ when $h = 0$ \\
$0 = 80 - 6t^{\frac{2}{3}}$ \\
Add $6t^{\frac{2}{3}}$ to both sides: \\
$6t^{\frac{2}{3}} = 80$ \\
Divide both sides by 6: \\
$t^{\frac{2}{3}} = \frac{80}{6}$ \\
$t^{\frac{2}{3}} = \frac{40}{3}$ \\
Raise both sides to the power $\frac{3}{2}$ (the reciprocal of $\frac{2}{3}$): \\
$t = \left( \frac{40}{3} \right)^{\frac{3}{2}}$ \\
$t = 48.69$ to 4 sf \\
The model says the hang-glider lands after about 48.7 minutes \\
The hang-glider actually stays airborne for 1 hour = 60 minutes \\
$48.7 \neq 60$, so the model is about 11 minutes out \\
The model is not suitable: it predicts the landing about 11 minutes too early \\
(Check: at $t = 60$ the model gives $h = 80 - 6(60)^{\frac{2}{3}} = 80 - 91.96 = -11.96$, which is below the ground) \\
(c) The ground is level, so the hang-glider has landed exactly when $h = 0$

@q 7
@topic Quartic sketch, f'(x) > 0, equation
@marks 7
@question
(a) $f'(x) > 0$ where the curve is going up (the gradient is positive) \\
The curve is going down for $x < 2$ \\
It goes up between the minimum at $x = 2$ and the maximum at $x = 4$ \\
So $f'(x) > 0$ for $2 < x < 4$ \\
It goes down between the maximum at $x = 4$ and the minimum at $x = 6$ \\
It goes up again for $x > 6$ \\
So $f'(x) > 0$ for $x > 6$ \\
In set notation: \\
$\{ x : 2 < x < 4 \} \text{ or } \{ x : x > 6 \}$ \\
(b) $C$ touches the $x$-axis at $x = 2$ and $x = 6$, and these are turning points \\
So each is a repeated root: $(x - 2)^{2}$ and $(x - 6)^{2}$ are factors \\
A quartic has degree 4, so only a constant $a$ is left to find: \\
$f(x) = a(x - 2)^{2}(x - 6)^{2}$ \\
The maximum point $(4, 80)$ is on the curve, so $f(4) = 80$ \\
$80 = a(4 - 2)^{2}(4 - 6)^{2}$ \\
Evaluate the brackets: $(4 - 2)^{2} = 4$ and $(4 - 6)^{2} = (-2)^{2} = 4$ \\
$80 = a \times 4 \times 4$ \\
$80 = 16a$ \\
Divide both sides by 16: \\
$a = 5$ \\
The equation of $C$ is $y = 5(x - 2)^{2}(x - 6)^{2}$ \\
(c) $y = f(x) + k$ is the curve $C$ moved up by $k$ units \\
$C_{1}$ meets the $x$-axis where $f(x) + k = 0$ \\
Subtract $k$ from both sides: \\
$f(x) = -k$ \\
So the horizontal line $y = -k$ must cross $C$ at exactly 4 points \\
$C$ has minimum value 0 (at $x = 2$ and $x = 6$) and a local maximum value 80 \\
The line crosses 4 times when it is above the minimum value and below the maximum value: \\
$0 < -k < 80$ \\
(If $-k = 0$ the line touches $C$ at 2 points, and if $-k = 80$ it meets $C$ at 3 points) \\
Multiply through by $-1$, which reverses the inequalities: \\
$0 > k > -80$ \\
$-80 < k < 0$ \\
Now find $c_{1}$, the $y$ coordinate where $C_{1}$ meets the $y$-axis: \\
$c_{1} = f(0) + k$ \\
$f(0) = 5(0 - 2)^{2}(0 - 6)^{2}$ \\
$f(0) = 5(4)(36)$ \\
$f(0) = 720$ \\
So $c_{1} = 720 + k$ \\
Add 720 to every part of $-80 < k < 0$: \\
$720 - 80 < 720 + k < 720 + 0$ \\
$640 < c_{1} < 720$

@q 8
@topic Proof by exhaustion, counterexample
@marks 5
@question
(a) Every positive integer leaves remainder 0, 1 or 2 when divided by 3 \\
So any positive integer $m$ is of the form $3k$, $3k + 1$ or $3k + 2$, where $k$ is a whole number \\
The proof in the box covers $3k$ and $3k + 1$ \\
The missing case is $m = 3k + 2$ \\
Let $m = 3k + 2$ \\
Consider $m^{2} = (3k + 2)^{2}$ \\
Expand the square: \\
$(3k + 2)(3k + 2) = 9k^{2} + 6k + 6k + 4$ \\
$= 9k^{2} + 12k + 4$ \\
Split the 4 as $3 + 1$ so that the rest is a multiple of 3: \\
$= 9k^{2} + 12k + 3 + 1$ \\
Take out the common factor 3 from the first three terms: \\
$= 3(3k^{2} + 4k + 1) + 1$ \\
$= 3n + 1$ where $n = 3k^{2} + 4k + 1$ \\
$n$ is a positive integer, since $k$ is a whole number \\
Statement: every positive integer is of the form $3k$, $3k + 1$ or $3k + 2$, and their squares are of the form $3n$, $3n + 1$ and $3n + 1$ \\
So the square of any positive integer can be written as $3n$ or $3n + 1$ where $n \in \mathbb{N}$, as required \\
(b) To disprove the statement we need one value of $x$ greater than 0 for which $2x^{2}(x + 1) > x$ is false \\
Try $x = 0.1$ \\
Evaluate the left-hand side: \\
$2(0.1)^{2}(0.1 + 1) = 2(0.01)(1.1)$ \\
$= 0.02 \times 1.1$ \\
$= 0.022$ \\
Compare with the right-hand side, $x = 0.1$: \\
$0.022 < 0.1$ \\
So $2x^{2}(x + 1) > x$ is false when $x = 0.1$ \\
$x = 0.1$ is greater than 0, so it is a counterexample and the statement is disproved

@q 9
@topic Asteroid model, iteration
@marks 9
@question
(a) The asteroid is visible when it is within 100 million km, so $x \leq 100$ \\
$te^{0.1t} - 8t + 100 \leq 100$ \\
Subtract 100 from both sides: \\
$te^{0.1t} - 8t \leq 0$ \\
Factorise by taking out $t$: \\
$t(e^{0.1t} - 8) \leq 0$ \\
For $t > 0$ divide both sides by $t$ (positive, so the inequality keeps its direction): \\
$e^{0.1t} - 8 \leq 0$ \\
Add 8 to both sides: \\
$e^{0.1t} \leq 8$ \\
Take natural logs of both sides: \\
$0.1t \leq \ln 8$ \\
Multiply both sides by 10: \\
$t \leq 10 \ln 8$ \\
$t \leq 20.794...$ \\
At $t = 0$, $x = 100$ exactly, so the asteroid is visible from $t = 0$ \\
It is visible from $t = 0$ to $t = 20.8$ \\
The asteroid is visible for 20.8 days to 1 dp \\
(b) The asteroid is closest when $x$ is a minimum, so find $\frac{dx}{dt}$ and set it to 0 \\
Differentiate $te^{0.1t}$ with the product rule, $u = t$ and $v = e^{0.1t}$ \\
$u' = 1$ and $v' = 0.1e^{0.1t}$ \\
$\frac{d}{dt}(te^{0.1t}) = (1)(e^{0.1t}) + (t)(0.1e^{0.1t})$ \\
$= e^{0.1t} + 0.1te^{0.1t}$ \\
Factorise by taking out $e^{0.1t}$: \\
$= e^{0.1t}(1 + 0.1t)$ \\
The other terms: $\frac{d}{dt}(-8t) = -8$ and $\frac{d}{dt}(100) = 0$ \\
$\frac{dx}{dt} = e^{0.1t}(1 + 0.1t) - 8$ \\
Set $\frac{dx}{dt} = 0$: \\
$e^{0.1t}(1 + 0.1t) - 8 = 0$ \\
Add 8 to both sides: \\
$e^{0.1t}(1 + 0.1t) = 8$ \\
Write $1 + 0.1t = \frac{10 + t}{10}$ \\
$e^{0.1t} \times \frac{10 + t}{10} = 8$ \\
Multiply both sides by 10: \\
$e^{0.1t}(10 + t) = 80$ \\
Divide both sides by $(10 + t)$: \\
$e^{0.1t} = \frac{80}{t + 10}$ \\
Take natural logs of both sides: \\
$0.1t = \ln \left( \frac{80}{t + 10} \right)$ \\
Multiply both sides by 10: \\
$t = 10 \ln \left( \frac{80}{t + 10} \right)$ as required \\
(The graph falls and then rises, so this stationary point is a minimum: the closest distance) \\
(c)(i) Use $t_{n+1} = 10 \ln \left( \frac{80}{t_{n} + 10} \right)$ with $t_{1} = 13$ \\
Find $t_{2}$: \\
$t_{2} = 10 \ln \left( \frac{80}{13 + 10} \right)$ \\
$t_{2} = 10 \ln \left( \frac{80}{23} \right)$ \\
$t_{2} = 12.465324...$ \\
Find $t_{3}$ using the unrounded $t_{2}$ (the ANS key): \\
$t_{3} = 10 \ln \left( \frac{80}{12.465324... + 10} \right)$ \\
$t_{3} = 10 \ln \left( \frac{80}{22.465324...} \right)$ \\
$t_{3} = 12.700537...$ \\
$t_{3} = 12.701$ to 3 dp \\
(ii) Keep iterating using ANS each time (values to 5 dp): \\
$t_{4} = 12.59638$ \\
$t_{5} = 12.64237$ \\
$t_{6} = 12.62204$ \\
$t_{7} = 12.63102$ \\
$t_{8} = 12.62705$ \\
$t_{9} = 12.62881$ \\
$t_{10} = 12.62803$ \\
$t_{11} = 12.62837$ \\
$t_{12} = 12.62822$ \\
$t_{13} = 12.62829$ \\
$t_{14} = 12.62826$ \\
$t_{15} = 12.62827$ \\
The values are settling on 12.628 \\
Check this with a sign change. Let $g(t) = t - 10 \ln \left( \frac{80}{t + 10} \right)$ \\
$g(12.6275) = -0.0011$ (negative) \\
$g(12.6285) = 0.0003$ (positive) \\
$g$ changes sign, so the root lies in $(12.6275, 12.6285)$ \\
So $t = 12.628$ to 3 dp \\
The asteroid is closest to the Earth about 12.628 days after it is first seen

@q 10
@topic Vectors, isosceles, right angle test
@marks 6
@question
(a) Go from $P$ to $Q$ and then from $Q$ to $R$: \\
$\text{PR} = \text{PQ} + \text{QR}$ \\
$= (-7\mathbf{i} - 5\mathbf{j} + 6\mathbf{k}) + (16\mathbf{i} + 3\mathbf{j} - \mathbf{k})$ \\
Add the $\mathbf{i}$ components: $-7 + 16 = 9$ \\
Add the $\mathbf{j}$ components: $-5 + 3 = -2$ \\
Add the $\mathbf{k}$ components: $6 - 1 = 5$ \\
$\text{PR} = 9\mathbf{i} - 2\mathbf{j} + 5\mathbf{k}$ \\
(b)(i) The length of $x\mathbf{i} + y\mathbf{j} + z\mathbf{k}$ is $\sqrt{x^{2} + y^{2} + z^{2}}$ \\
$|\text{PQ}| = \sqrt{(-7)^{2} + (-5)^{2} + 6^{2}}$ \\
$= \sqrt{49 + 25 + 36}$ \\
$= \sqrt{110}$ \\
$|\text{PR}| = \sqrt{9^{2} + (-2)^{2} + 5^{2}}$ \\
$= \sqrt{81 + 4 + 25}$ \\
$= \sqrt{110}$ \\
$|\text{QR}| = \sqrt{16^{2} + 3^{2} + (-1)^{2}}$ \\
$= \sqrt{256 + 9 + 1}$ \\
$= \sqrt{266}$ \\
$|\text{PQ}| = |\text{PR}| = \sqrt{110}$, so two sides are equal \\
So triangle $PQR$ is isosceles, as required \\
(ii) In a right-angled triangle the square of the longest side equals the sum of the squares of the other two sides (Pythagoras) \\
The longest side is $QR$, with $|\text{QR}|^{2} = 266$ \\
$|\text{PQ}|^{2} + |\text{PR}|^{2} = 110 + 110$ \\
$= 220$ \\
$220 \neq 266$ \\
So Pythagoras' theorem fails for the longest side \\
The hypotenuse of a right-angled triangle is its longest side, so triangle $PQR$ is not right angled

@q 11
@topic Reservoir drought model Ae^(-kt)
@marks 8
@question
(a) At the start $t = 0$ and $V = 50000$ \\
$50000 = 20000 + Ae^{-k(0)}$ \\
Anything to the power 0 is 1, so $e^{0} = 1$: \\
$50000 = 20000 + A$ \\
Subtract 20000 from both sides: \\
$A = 30000$ \\
After 3 weeks $t = 3$ and $V = 28000$ \\
$28000 = 20000 + 30000e^{-3k}$ \\
Subtract 20000 from both sides: \\
$8000 = 30000e^{-3k}$ \\
Divide both sides by 30000: \\
$e^{-3k} = \frac{8000}{30000}$ \\
Cancel the common factor 1000: \\
$e^{-3k} = \frac{8}{30}$ \\
Cancel the common factor 2: \\
$e^{-3k} = \frac{4}{15}$ \\
Take natural logs of both sides (using $\ln e^{x} = x$): \\
$-3k = \ln \left( \frac{4}{15} \right)$ \\
Divide both sides by $-3$: \\
$k = -\frac{1}{3} \ln \left( \frac{4}{15} \right)$ \\
Use $-\ln \left( \frac{a}{b} \right) = \ln \left( \frac{b}{a} \right)$: \\
$k = \frac{1}{3} \ln \left( \frac{15}{4} \right)$ \\
$k = 0.440585...$ \\
$k = 0.44$ to 2 significant figures \\
(Check: $20000 + 30000e^{-0.44 \times 3} = 28014$, which is close to 28000) \\
The model is $V = 20000 + 30000e^{-0.44t}$ \\
(b) The rate of change of the volume is $\frac{dV}{dt}$ \\
Differentiate $V = 20000 + Ae^{-kt}$ with respect to $t$ \\
The constant 20000 differentiates to 0 \\
The derivative of $e^{ax}$ is $ae^{ax}$, so $\frac{d}{dt}(e^{-kt}) = -ke^{-kt}$ \\
$\frac{dV}{dt} = A \times (-k)e^{-kt}$ \\
$\frac{dV}{dt} = -kAe^{-kt}$ \\
Now write $Ae^{-kt}$ in terms of $V$. Start from $V = 20000 + Ae^{-kt}$ \\
Subtract 20000 from both sides: \\
$V - 20000 = Ae^{-kt}$ \\
Replace $Ae^{-kt}$ in the derivative: \\
$\frac{dV}{dt} = -k(V - 20000)$ as required \\
(c) As $t$ increases, $e^{-kt}$ gets closer and closer to 0 \\
So $V$ gets closer and closer to 20000 but never goes below it \\
Limitation: the model says 20000 m$^{3}$ of water always stays in the reservoir, but in a long drought the reservoir could run completely dry (for example through evaporation and use of the water)

@q 12
@topic Curve and line intersect, cubic
@marks 8
@question
(a) At $x = -2$, find $y$ on the curve $C$: \\
$y = \frac{10(-2)}{(-2 + 3)(1 - 2(-2))}$ \\
Work out the top and each bracket: \\
Top: $10(-2) = -20$ \\
First bracket: $-2 + 3 = 1$ \\
Second bracket: $1 - 2(-2) = 1 + 4 = 5$ \\
$y = \frac{-20}{(1)(5)}$ \\
$y = \frac{-20}{5}$ \\
$y = -4$ \\
At $x = -2$, find $y$ on the line $l$, $x + y + 6 = 0$: \\
$-2 + y + 6 = 0$ \\
$y + 4 = 0$ \\
$y = -4$ \\
Both give $y = -4$ at $x = -2$, so $C$ and $l$ meet at $(-2, -4)$ \\
(b) Make $y$ the subject of $x + y + 6 = 0$ by subtracting $x$ and 6 from both sides: \\
$y = -x - 6$ \\
At an intersection the two $y$ values are equal: \\
$\frac{10x}{(x + 3)(1 - 2x)} = -x - 6$ \\
Multiply both sides by $(x + 3)(1 - 2x)$, which is not zero as $x \neq -3$ and $x \neq \frac{1}{2}$: \\
$10x = (-x - 6)(x + 3)(1 - 2x)$ \\
Take out a factor of $-1$ from the first bracket: \\
$10x = -(x + 6)(x + 3)(1 - 2x)$ \\
Expand $(x + 3)(1 - 2x)$ first: \\
$x(1) + x(-2x) + 3(1) + 3(-2x)$ \\
$= x - 2x^{2} + 3 - 6x$ \\
$= -2x^{2} - 5x + 3$ \\
So $10x = -(x + 6)(-2x^{2} - 5x + 3)$ \\
Take the minus sign into the second bracket, changing every sign in it: \\
$10x = (x + 6)(2x^{2} + 5x - 3)$ \\
Expand the right-hand side, multiplying the second bracket by $x$ and then by 6: \\
$x(2x^{2} + 5x - 3) = 2x^{3} + 5x^{2} - 3x$ \\
$6(2x^{2} + 5x - 3) = 12x^{2} + 30x - 18$ \\
Add these: \\
$10x = 2x^{3} + 5x^{2} - 3x + 12x^{2} + 30x - 18$ \\
Collect like terms: $5x^{2} + 12x^{2} = 17x^{2}$ and $-3x + 30x = 27x$ \\
$10x = 2x^{3} + 17x^{2} + 27x - 18$ \\
Subtract $10x$ from both sides: \\
$0 = 2x^{3} + 17x^{2} + 27x - 10x - 18$ \\
$0 = 2x^{3} + 17x^{2} + 17x - 18$ \\
So $2x^{3} + 17x^{2} + 17x - 18 = 0$ as required \\
(c) $x = -2$ is a root (it is where $C$ and $l$ meet), so $(x + 2)$ is a factor \\
(Check: $2(-2)^{3} + 17(-2)^{2} + 17(-2) - 18 = -16 + 68 - 34 - 18 = 0$) \\
Write $2x^{3} + 17x^{2} + 17x - 18 = (x + 2)(2x^{2} + px - 9)$ \\
The first term of the quadratic is $2x^{2}$ to give $2x^{3}$, and the last is $-9$ since $2 \times (-9) = -18$ \\
Expand the right-hand side: \\
$2x^{3} + px^{2} - 9x + 4x^{2} + 2px - 18$ \\
$= 2x^{3} + (p + 4)x^{2} + (2p - 9)x - 18$ \\
Compare the $x^{2}$ coefficients: $p + 4 = 17$ \\
Subtract 4 from both sides: \\
$p = 13$ \\
(Check with the $x$ term: $2p - 9 = 26 - 9 = 17$, which matches) \\
$(x + 2)(2x^{2} + 13x - 9) = 0$ \\
Either $x + 2 = 0$ or $2x^{2} + 13x - 9 = 0$ \\
The first gives $x = -2$, the point found in part (a) \\
So $Q$ comes from the quadratic $2x^{2} + 13x - 9 = 0$ \\
Use the quadratic formula $x = \frac{-b \pm \sqrt{b^{2} - 4ac}}{2a}$ with $a = 2$, $b = 13$, $c = -9$ \\
$x = \frac{-13 \pm \sqrt{13^{2} - 4(2)(-9)}}{2(2)}$ \\
Work out the discriminant: $13^{2} = 169$ and $-4(2)(-9) = 72$ \\
$x = \frac{-13 \pm \sqrt{169 + 72}}{4}$ \\
$x = \frac{-13 \pm \sqrt{241}}{4}$ \\
So $x = \frac{-13 + \sqrt{241}}{4}$ or $x = \frac{-13 - \sqrt{241}}{4}$ \\
Decide which is $Q$. In the sketch $Q$ is to the right of the asymptote $x = \frac{1}{2}$ \\
$\frac{-13 + \sqrt{241}}{4} = 0.631...$, which is greater than $\frac{1}{2}$ \\
$\frac{-13 - \sqrt{241}}{4} = -7.131...$, which is on the far left, so it is the other intersection \\
The exact $x$ coordinate of $Q$ is $\frac{-13 + \sqrt{241}}{4}$

@q 13
@topic Integration by substitution, find k
@marks 5
@question
Let $u = 3x + 1$ \\
Differentiate: $\frac{du}{dx} = 3$ \\
Rearrange to find $dx$: \\
$dx = \frac{1}{3} du$ \\
Write $x$ in terms of $u$: subtract 1 from both sides, then divide by 3: \\
$3x = u - 1$ \\
$x = \frac{u - 1}{3}$ \\
Change the limits. When $x = 0$: \\
$u = 3(0) + 1 = 1$ \\
When $x = 1$: \\
$u = 3(1) + 1 = 4$ \\
Replace everything in the integral. The top $x$ becomes $\frac{u - 1}{3}$ and the bottom becomes $u^{4}$: \\
$\int_{0}^{1} \frac{x}{(3x + 1)^{4}} dx = \int_{1}^{4} \frac{u - 1}{3u^{4}} \times \frac{1}{3} du$ \\
Multiply the two thirds: $\frac{1}{3} \times \frac{1}{3} = \frac{1}{9}$ \\
$= \frac{1}{9} \int_{1}^{4} \frac{u - 1}{u^{4}} du$ \\
Split the fraction into two: \\
$\frac{u - 1}{u^{4}} = \frac{u}{u^{4}} - \frac{1}{u^{4}}$ \\
Use $\frac{u}{u^{4}} = u^{-3}$ and $\frac{1}{u^{4}} = u^{-4}$ \\
$= \frac{1}{9} \int_{1}^{4} \left( u^{-3} - u^{-4} \right) du$ \\
Integrate each term (add 1 to the power, divide by the new power): \\
$\int u^{-3} du = \frac{u^{-2}}{-2}$ \\
$\int u^{-4} du = \frac{u^{-3}}{-3}$ \\
$= \frac{1}{9} \left[ -\frac{1}{2}u^{-2} + \frac{1}{3}u^{-3} \right]_{1}^{4}$ \\
Upper limit $u = 4$: \\
$-\frac{1}{2}(4)^{-2} + \frac{1}{3}(4)^{-3}$ \\
$4^{-2} = \frac{1}{16}$ and $4^{-3} = \frac{1}{64}$ \\
$= -\frac{1}{2} \times \frac{1}{16} + \frac{1}{3} \times \frac{1}{64}$ \\
$= -\frac{1}{32} + \frac{1}{192}$ \\
Write over the common denominator 192: $-\frac{1}{32} = -\frac{6}{192}$ \\
$= -\frac{6}{192} + \frac{1}{192}$ \\
$= -\frac{5}{192}$ \\
Lower limit $u = 1$: \\
$-\frac{1}{2}(1)^{-2} + \frac{1}{3}(1)^{-3}$ \\
$= -\frac{1}{2} + \frac{1}{3}$ \\
Write over the common denominator 6: \\
$= -\frac{3}{6} + \frac{2}{6}$ \\
$= -\frac{1}{6}$ \\
Subtract the lower limit from the upper limit: \\
$-\frac{5}{192} - \left( -\frac{1}{6} \right)$ \\
$= -\frac{5}{192} + \frac{1}{6}$ \\
Write $\frac{1}{6}$ over 192: $\frac{1}{6} = \frac{32}{192}$ \\
$= -\frac{5}{192} + \frac{32}{192}$ \\
$= \frac{27}{192}$ \\
Divide the top and bottom by 3: \\
$= \frac{9}{64}$ \\
So the whole integral is $\frac{1}{9} \times \frac{9}{64}$ \\
Cancel the 9s: \\
$= \frac{1}{64}$ \\
The original equation is $k \int_{0}^{1} \frac{x}{(3x + 1)^{4}} dx = 1$ \\
$k \times \frac{1}{64} = 1$ \\
Multiply both sides by 64: \\
$k = 64$

@q 14
@topic Show identity, solve trig equation
@marks 7
@question
(All angles in this answer are in degrees.) \\
(a) Use the compound angle formulae: \\
$\sin (A + B) = \sin A \cos B + \cos A \sin B$ \\
$\cos (A + B) = \cos A \cos B - \sin A \sin B$ \\
Expand $\sin (x + 30)$ with $A = x$ and $B = 30$: \\
$\sin (x + 30) = \sin x \cos 30 + \cos x \sin 30$ \\
Expand $\cos (x + 30)$ in the same way: \\
$\cos (x + 30) = \cos x \cos 30 - \sin x \sin 30$ \\
Use the exact values $\cos 30 = \frac{\sqrt{3}}{2}$ and $\sin 30 = \frac{1}{2}$ \\
$\sin (x + 30) = \frac{\sqrt{3}}{2} \sin x + \frac{1}{2} \cos x$ \\
$\cos (x + 30) = \frac{\sqrt{3}}{2} \cos x - \frac{1}{2} \sin x$ \\
Substitute both into the left-hand side: \\
$\text{LHS} = \sqrt{3} \left( \frac{\sqrt{3}}{2} \sin x + \frac{1}{2} \cos x \right)$ \\
$\quad - \left( \frac{\sqrt{3}}{2} \cos x - \frac{1}{2} \sin x \right)$ \\
Multiply the first bracket by $\sqrt{3}$ using $\sqrt{3} \times \frac{\sqrt{3}}{2} = \frac{3}{2}$ and $\sqrt{3} \times \frac{1}{2} = \frac{\sqrt{3}}{2}$ \\
Remove the second bracket, changing both signs: \\
$= \frac{3}{2} \sin x + \frac{\sqrt{3}}{2} \cos x - \frac{\sqrt{3}}{2} \cos x + \frac{1}{2} \sin x$ \\
The $\cos x$ terms cancel: $\frac{\sqrt{3}}{2} \cos x - \frac{\sqrt{3}}{2} \cos x = 0$ \\
$= \frac{3}{2} \sin x + \frac{1}{2} \sin x$ \\
$= \frac{4}{2} \sin x$ \\
$= 2 \sin x$ \\
This is the right-hand side, as required \\
(b) The left-hand side of the equation is the expression from part (a), so replace it with $2 \sin \theta$: \\
$2 \sin \theta = 4 \sin 2\theta$ \\
Use the double angle formula $\sin 2\theta = 2 \sin \theta \cos \theta$: \\
$2 \sin \theta = 4(2 \sin \theta \cos \theta)$ \\
$2 \sin \theta = 8 \sin \theta \cos \theta$ \\
Do not divide by $\sin \theta$, as that would lose the solutions where $\sin \theta = 0$ \\
Subtract $8 \sin \theta \cos \theta$ from both sides: \\
$2 \sin \theta - 8 \sin \theta \cos \theta = 0$ \\
Factorise by taking out $2 \sin \theta$: \\
$2 \sin \theta (1 - 4 \cos \theta) = 0$ \\
Either $\sin \theta = 0$ or $1 - 4 \cos \theta = 0$ \\
Case 1: $\sin \theta = 0$ \\
$\theta = 0$ or $\theta = 180$ \\
(In $0 \leq \theta < 360$ the solutions are 0 and 180, as 360 is not included) \\
Case 2: $1 - 4 \cos \theta = 0$ \\
Add $4 \cos \theta$ to both sides: \\
$1 = 4 \cos \theta$ \\
Divide both sides by 4: \\
$\cos \theta = \frac{1}{4}$ \\
Take the inverse cosine: \\
$\theta = 75.5225...$ \\
Cosine is positive in the first and fourth quadrants, so the second solution is $360 - 75.5225...$ \\
$\theta = 284.4775...$ \\
The solutions to 1 decimal place are $\theta = 0$, $75.5$, $180$ and $284.5$ degrees

@q 15
@topic Sector and rectangles, optimisation
@marks 9
@question
(a) Find the area of each part of the display \\
The sector has radius $r$ and angle $\theta$, so its area is $\frac{1}{2}r^{2}\theta$ \\
Each rectangle has area $r \times \frac{r}{4} = \frac{r^{2}}{4}$ \\
Two rectangles: $2 \times \frac{r^{2}}{4} = \frac{r^{2}}{2}$ \\
The total area is 60: \\
$\frac{1}{2}r^{2}\theta + \frac{1}{2}r^{2} = 60$ \\
Multiply both sides by 2: \\
$r^{2}\theta + r^{2} = 120$ \\
Subtract $r^{2}$ from both sides: \\
$r^{2}\theta = 120 - r^{2}$ \\
Divide both sides by $r^{2}$: \\
$\theta = \frac{120 - r^{2}}{r^{2}}$ \\
Split into two fractions: \\
$\theta = \frac{120}{r^{2}} - 1$ \\
Now the perimeter. It is the arc $AB$ plus six straight edges (the dashed lines $OA$ and $OB$ are inside the shape) \\
Arc length $AB = r\theta$ \\
The straight edges are $BR = \frac{r}{4}$, $RS = r$, $SO = \frac{r}{4}$, $OP = \frac{r}{4}$, $PQ = r$ and $QA = \frac{r}{4}$ \\
Add the four edges of length $\frac{r}{4}$: $4 \times \frac{r}{4} = r$ \\
Add the two edges of length $r$: $r + r = 2r$ \\
Total straight length $= r + 2r = 3r$ \\
$P = r\theta + 3r$ \\
Substitute $\theta = \frac{120}{r^{2}} - 1$: \\
$P = r \left( \frac{120}{r^{2}} - 1 \right) + 3r$ \\
Expand the bracket: \\
$P = \frac{120r}{r^{2}} - r + 3r$ \\
Cancel one factor of $r$ in the first term: \\
$P = \frac{120}{r} - r + 3r$ \\
$P = \frac{120}{r} + 2r$ as required \\
(b) Write $P$ with a negative power so it can be differentiated: \\
$P = 120r^{-1} + 2r$ \\
Differentiate each term (multiply by the power, then reduce the power by 1): \\
$\frac{d}{dr}(120r^{-1}) = 120 \times (-1)r^{-2} = -120r^{-2}$ \\
$\frac{d}{dr}(2r) = 2$ \\
$\frac{dP}{dr} = -120r^{-2} + 2$ \\
For a stationary value set $\frac{dP}{dr} = 0$: \\
$-\frac{120}{r^{2}} + 2 = 0$ \\
Add $\frac{120}{r^{2}}$ to both sides: \\
$2 = \frac{120}{r^{2}}$ \\
Multiply both sides by $r^{2}$: \\
$2r^{2} = 120$ \\
Divide both sides by 2: \\
$r^{2} = 60$ \\
Take the positive square root, as $r$ is a length: \\
$r = \sqrt{60}$ \\
$r = \sqrt{4 \times 15}$ \\
$r = 2\sqrt{15}$ \\
$r = 7.746$ to 4 sf \\
(c) Differentiate $\frac{dP}{dr} = -120r^{-2} + 2$ again: \\
$\frac{d^{2}P}{dr^{2}} = -120 \times (-2)r^{-3}$ \\
$\frac{d^{2}P}{dr^{2}} = 240r^{-3}$ \\
$\frac{d^{2}P}{dr^{2}} = \frac{240}{r^{3}}$ \\
When $r = \sqrt{60}$, $r^{3}$ is positive, so $\frac{240}{r^{3}} > 0$ \\
Numerically $\frac{240}{(\sqrt{60})^{3}} = \frac{240}{464.76} = 0.516$ \\
The second derivative is positive, so the stationary point is a minimum \\
So $r = \sqrt{60}$ gives the minimum perimeter, as required \\
(Check: $\theta = \frac{120}{60} - 1 = 1$ radian, which is positive, and the minimum perimeter is $4\sqrt{60} = 30.98$ m)

@q 16
@topic Substitution u = sec x, exact area
@marks 7
@question
(a) The area of $R$ is the integral of $y$ between $x = \frac{\pi}{6}$ and $x = \frac{\pi}{3}$ \\
Split off one factor of $\sec x$ to pair with $\tan x$: \\
$\sec^{4} x = \sec^{3} x \times \sec x$ \\
$y = \sec^{3} x \times \sec x \tan x$ \\
$\text{Area} = \int_{\frac{\pi}{6}}^{\frac{\pi}{3}} \sec^{3} x \times \sec x \tan x \, dx$ \\
Let $u = \sec x$ \\
Differentiate (the standard derivative of $\sec x$): \\
$\frac{du}{dx} = \sec x \tan x$ \\
So $du = \sec x \tan x \, dx$ \\
Replace $\sec^{3} x$ by $u^{3}$ and $\sec x \tan x \, dx$ by $du$ \\
Change the limits. When $x = \frac{\pi}{6}$: \\
$u = \sec \frac{\pi}{6} = \frac{1}{\cos \frac{\pi}{6}}$ \\
$\cos \frac{\pi}{6} = \frac{\sqrt{3}}{2}$ \\
$u = 1 \div \frac{\sqrt{3}}{2}$ \\
Flip the fraction and multiply: \\
$u = \frac{2}{\sqrt{3}}$ \\
When $x = \frac{\pi}{3}$: \\
$u = \sec \frac{\pi}{3} = \frac{1}{\cos \frac{\pi}{3}}$ \\
$\cos \frac{\pi}{3} = \frac{1}{2}$ \\
$u = 1 \div \frac{1}{2}$ \\
$u = 2$ \\
$\text{Area} = \int_{\frac{2}{\sqrt{3}}}^{2} u^{3} du$ \\
This is the form $\int_{a}^{b} u^{n} du$ with $a = \frac{2}{\sqrt{3}}$, $b = 2$ and $n = 3$ \\
(b) Integrate $u^{3}$ (add 1 to the power, divide by the new power): \\
$\int u^{3} du = \frac{u^{4}}{4}$ \\
$\text{Area} = \left[ \frac{u^{4}}{4} \right]_{\frac{2}{\sqrt{3}}}^{2}$ \\
Upper limit $u = 2$: \\
$\frac{2^{4}}{4} = \frac{16}{4} = 4$ \\
Lower limit $u = \frac{2}{\sqrt{3}}$: \\
$\frac{1}{4} \left( \frac{2}{\sqrt{3}} \right)^{4}$ \\
Raise top and bottom to the power 4: $2^{4} = 16$ and $(\sqrt{3})^{4} = 3^{2} = 9$ \\
$\left( \frac{2}{\sqrt{3}} \right)^{4} = \frac{16}{9}$ \\
$\frac{1}{4} \times \frac{16}{9} = \frac{16}{36}$ \\
Divide the top and bottom by 4: \\
$= \frac{4}{9}$ \\
Subtract the lower limit from the upper limit: \\
$\text{Area} = 4 - \frac{4}{9}$ \\
Write 4 as a fraction over 9: $4 = \frac{36}{9}$ \\
$= \frac{36}{9} - \frac{4}{9}$ \\
$= \frac{32}{9}$
