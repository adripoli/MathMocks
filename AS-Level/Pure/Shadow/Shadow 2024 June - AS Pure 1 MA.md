@paper AS1 Shadow June 2024

@q 1
@topic Integrate algebraic fraction with root
@marks 4
@question
Split the fraction into two, dividing each term of the top by $x^{3}$: \\
$\frac{4 - \sqrt{x}}{x^{3}} = \frac{4}{x^{3}} - \frac{\sqrt{x}}{x^{3}}$ \\
Write each as a power of $x$. The first is $4x^{-3}$ \\
For the second, $\sqrt{x} = x^{\frac{1}{2}}$ and subtract the indices when dividing: \\
$\frac{x^{\frac{1}{2}}}{x^{3}} = x^{\frac{1}{2} - 3}$ \\
$= x^{-\frac{5}{2}}$ \\
The integral is now: \\
$\int \left( 4x^{-3} - x^{-\frac{5}{2}} \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$ \\
$4x^{-3} \to 4 \times \frac{x^{-2}}{-2} = -2x^{-2}$ \\
$-x^{-\frac{5}{2}} \to -\frac{x^{-\frac{3}{2}}}{-\frac{3}{2}}$ \\
Dividing by $-\frac{3}{2}$ is the same as multiplying by $-\frac{2}{3}$: \\
$= +\frac{2}{3}x^{-\frac{3}{2}}$ \\
Add the constant of integration $c$: \\
$\int \frac{4 - \sqrt{x}}{x^{3}} dx = -2x^{-2} + \frac{2}{3}x^{-\frac{3}{2}} + c$ \\
This can be written as $-\frac{2}{x^{2}} + \frac{2}{3x^{\frac{3}{2}}} + c$

@q 2
@topic Factor theorem with unknown k
@marks 8
@question
(a) By the factor theorem, $x - 3$ is a factor so $f(3) = 0$: \\
$3(3)^{3} + k(3)^{2} - 19(3) + 3k = 0$ \\
Evaluate the powers: $3^{3} = 27$ and $3^{2} = 9$ \\
$3(27) + k(9) - 19(3) + 3k = 0$ \\
Multiply out: $3(27) = 81$ and $19(3) = 57$ \\
$81 + 9k - 57 + 3k = 0$ \\
Collect the $k$ terms and the numbers: \\
$12k + 24 = 0$ \\
Subtract 24 from both sides: \\
$12k = -24$ \\
Divide both sides by 12: \\
$k = -2$ \\
(b) With $k = -2$: \\
$f(x) = 3x^{3} - 2x^{2} - 19x - 6$ \\
Write $f(x) = (x - 3)\left( 3x^{2} + px + q \right)$ and expand: \\
$(x - 3)\left( 3x^{2} + px + q \right) = 3x^{3} + px^{2} + qx - 9x^{2} - 3px - 3q$ \\
$= 3x^{3} + (p - 9)x^{2} + (q - 3p)x - 3q$ \\
Compare coefficients of $x^{2}$: \\
$p - 9 = -2$ \\
$p = 7$ \\
Compare constant terms: \\
$-3q = -6$ \\
$q = 2$ \\
Check the $x$ terms: $q - 3p = 2 - 21 = -19$, which matches \\
$f(x) = (x - 3)\left( 3x^{2} + 7x + 2 \right)$ \\
Factorise the quadratic. Two numbers that multiply to $3 \times 2 = 6$ and add to 7 are 6 and 1: \\
$3x^{2} + 6x + x + 2$ \\
$= 3x(x + 2) + 1(x + 2)$ \\
$= (3x + 1)(x + 2)$ \\
$f(x) = (x - 3)(3x + 1)(x + 2)$ \\
(c) $f(x + 2) = 0$ when $x + 2$ is a root of $f$. The roots of $f$ are $3$, $-\frac{1}{3}$ and $-2$ \\
Set $x + 2$ equal to each root, then subtract 2: \\
$x + 2 = 3$ gives $x = 1$ \\
$x + 2 = -\frac{1}{3}$ gives $x = -\frac{1}{3} - 2 = -\frac{7}{3}$ \\
$x + 2 = -2$ gives $x = -4$ \\
$x = 1$, $x = -\frac{7}{3}$ or $x = -4$

@q 3
@topic Vectors, midpoint, area of quadrilateral
@marks 8
@question
(a) $\text{AC} = \text{OC} - \text{OA}$ (end point minus start point) \\
$= (6\mathbf{i} + 15\mathbf{j}) - (10\mathbf{i} + 3\mathbf{j})$ \\
$\mathbf{i}$ part: $6 - 10 = -4$ \\
$\mathbf{j}$ part: $15 - 3 = 12$ \\
$\text{AC} = -4\mathbf{i} + 12\mathbf{j}$ \\
(b) $M$ is the midpoint of $AC$, so $\text{MC}$ is half of $\text{AC}$: \\
$\text{MC} = \frac{1}{2}(-4\mathbf{i} + 12\mathbf{j})$ \\
$= -2\mathbf{i} + 6\mathbf{j}$ \\
$\text{MB}$ is the reverse of $\text{BM}$: \\
$\text{MB} = -(9\mathbf{i} + 3\mathbf{j})$ \\
$= -9\mathbf{i} - 3\mathbf{j}$ \\
The angle $BMC$ is the angle between $\text{MB}$ and $\text{MC}$. Work out the scalar product, multiplying the $\mathbf{i}$ parts and the $\mathbf{j}$ parts and adding: \\
$\text{MB} \cdot \text{MC} = (-9)(-2) + (-3)(6)$ \\
$= 18 - 18$ \\
$= 0$ \\
A scalar product of 0 means the vectors are perpendicular, so angle $BMC$ is 90 degrees, as required \\
Alt: the gradient of $MB$ is $\frac{-3}{-9} = \frac{1}{3}$ and the gradient of $MC$ is $\frac{6}{-2} = -3$. Since $\frac{1}{3} \times (-3) = -1$, the lines are perpendicular \\
(c) Find $\text{BD}$: \\
$\text{BD} = \frac{5}{3}\text{BM}$ \\
$= \frac{5}{3}(9\mathbf{i} + 3\mathbf{j})$ \\
$= 15\mathbf{i} + 5\mathbf{j}$ \\
$D$ is on the line $BM$ extended, so the diagonal $BD$ is perpendicular to the diagonal $AC$ (from part (b), since $M$ is on both). The area of a quadrilateral with perpendicular diagonals is $\frac{1}{2} \times (\text{length of one diagonal}) \times (\text{length of the other})$ \\
Length of $AC$: \\
$|\text{AC}| = \sqrt{(-4)^{2} + 12^{2}}$ \\
$= \sqrt{16 + 144}$ \\
$= \sqrt{160}$ \\
$= \sqrt{16 \times 10}$ \\
$= 4\sqrt{10}$ \\
Length of $BD$: \\
$|\text{BD}| = \sqrt{15^{2} + 5^{2}}$ \\
$= \sqrt{225 + 25}$ \\
$= \sqrt{250}$ \\
$= \sqrt{25 \times 10}$ \\
$= 5\sqrt{10}$ \\
$\text{Area} = \frac{1}{2} \times 4\sqrt{10} \times 5\sqrt{10}$ \\
$= \frac{1}{2} \times 20 \times \left( \sqrt{10} \right)^{2}$ \\
$= \frac{1}{2} \times 20 \times 10$ \\
$= 100$ \\
(Check: $M$ is between $B$ and $D$, as $BM$ is $\frac{3}{5}$ of $BD$, so the diagonals cross at $M$ and the quadrilateral is a proper four-sided shape)

@q 4
@topic Cosine rule in an isosceles triangle
@marks 6
@question
(a) Use the cosine rule in triangle $ABD$, with the 120 degree angle at $D$ and the opposite side $AB$: \\
$AB^{2} = AD^{2} + BD^{2} - 2(AD)(BD)\cos 120$ \\
$\cos 120$ degrees $= -\frac{1}{2}$, so $-2\cos 120 = +1$: \\
$(x + k)^{2} = (x - k)^{2} + x^{2} + (x - k)(x)$ \\
Expand each bracket one at a time: \\
$(x + k)^{2} = x^{2} + 2xk + k^{2}$ \\
$(x - k)^{2} = x^{2} - 2xk + k^{2}$ \\
$(x - k)(x) = x^{2} - xk$ \\
Substitute these back in: \\
$x^{2} + 2xk + k^{2} = x^{2} - 2xk + k^{2} + x^{2} + x^{2} - xk$ \\
Collect like terms on the right-hand side: \\
$x^{2} + 2xk + k^{2} = 3x^{2} - 3xk + k^{2}$ \\
Subtract $x^{2} + 2xk + k^{2}$ from both sides: \\
$0 = 2x^{2} - 5xk$ \\
Take out the common factor $x$: \\
$0 = x(2x - 5k)$ \\
$x \neq 0$, as $x > k > 0$, so: \\
$2x - 5k = 0$ \\
$2x = 5k$ \\
$x = \frac{5k}{2}$, as required \\
(b) Triangle $ABC$ is isosceles with $AB = BC$, so the base angles at $A$ and $C$ are equal. So angle $BAD = \theta$ degrees \\
Find the sides of triangle $ABD$ in terms of $k$, using $x = \frac{5k}{2}$: \\
$AB = x + k = \frac{5k}{2} + k = \frac{7k}{2}$ \\
$AD = x - k = \frac{5k}{2} - k = \frac{3k}{2}$ \\
$BD = x = \frac{5k}{2}$ \\
Use the cosine rule for the angle at $A$, $\cos A = \frac{AB^{2} + AD^{2} - BD^{2}}{2(AB)(AD)}$: \\
$\cos \theta = \frac{\left( \frac{7k}{2} \right)^{2} + \left( \frac{3k}{2} \right)^{2} - \left( \frac{5k}{2} \right)^{2}}{2\left( \frac{7k}{2} \right)\left( \frac{3k}{2} \right)}$ \\
$= \frac{\frac{49k^{2}}{4} + \frac{9k^{2}}{4} - \frac{25k^{2}}{4}}{\frac{21k^{2}}{2}}$ \\
$= \frac{\frac{33k^{2}}{4}}{\frac{21k^{2}}{2}}$ \\
Divide, cancelling $k^{2}$: \\
$= \frac{33}{4} \times \frac{2}{21}$ \\
$= \frac{66}{84}$ \\
$= \frac{11}{14}$ \\
$\theta = \cos^{-1}\left( \frac{11}{14} \right)$ \\
$\theta = 38.2$ degrees (3 sf)

@q 5
@topic Intersecting curves, cubic factorise
@marks 8
@question
(a) As $x$ gets very large (positive or negative), $\frac{12}{x}$ gets closer to 0, so $y$ gets closer to $-8$ \\
The asymptote is $l: y = -8$ \\
(b) At a point of intersection the $y$ values are equal: \\
$\frac{12}{x} - 8 = 2x^{2} - 13x + 15$ \\
Multiply every term by $x$ (not zero, as $x = 0$ is not on $C_{1}$): \\
$12 - 8x = 2x^{3} - 13x^{2} + 15x$ \\
Move every term to the right-hand side: \\
$0 = 2x^{3} - 13x^{2} + 15x + 8x - 12$ \\
$0 = 2x^{3} - 13x^{2} + 23x - 12$ \\
$2x^{3} - 13x^{2} + 23x - 12 = 0$, as required \\
(c) $P_{2}$ is on the $x$-axis, so $y = 0$ on $C_{1}$: \\
$\frac{12}{x} - 8 = 0$ \\
Add 8 to both sides: \\
$\frac{12}{x} = 8$ \\
Multiply both sides by $x$: \\
$12 = 8x$ \\
$x = \frac{12}{8}$ \\
$x = \frac{3}{2}$ \\
So $\frac{3}{2}$ is a root of the cubic. Check: \\
$2\left( \frac{3}{2} \right)^{3} - 13\left( \frac{3}{2} \right)^{2} + 23\left( \frac{3}{2} \right) - 12$ \\
$= 2\left( \frac{27}{8} \right) - 13\left( \frac{9}{4} \right) + \frac{69}{2} - 12$ \\
$= 6.75 - 29.25 + 34.5 - 12$ \\
$= 0$ \\
$(2x - 3)$ is a factor. Write the cubic as $(2x - 3)\left( x^{2} + px + q \right)$ and expand: \\
$(2x - 3)\left( x^{2} + px + q \right) = 2x^{3} + 2px^{2} + 2qx - 3x^{2} - 3px - 3q$ \\
$= 2x^{3} + (2p - 3)x^{2} + (2q - 3p)x - 3q$ \\
Compare coefficients of $x^{2}$: \\
$2p - 3 = -13$ \\
$2p = -10$ \\
$p = -5$ \\
Compare constant terms: \\
$-3q = -12$ \\
$q = 4$ \\
Check the $x$ terms: $2q - 3p = 8 + 15 = 23$, which matches \\
$(2x - 3)\left( x^{2} - 5x + 4 \right) = 0$ \\
Factorise the quadratic. Two numbers that multiply to 4 and add to $-5$ are $-1$ and $-4$: \\
$(2x - 3)(x - 1)(x - 4) = 0$ \\
$x = \frac{3}{2}$ or $x = 1$ or $x = 4$ \\
The points are labelled from left to right, so: \\
$P_{1}$ has $x = 1$, $P_{2}$ has $x = \frac{3}{2}$ and $P_{3}$ has $x = 4$

@q 6
@topic Binomial expansion estimate
@marks 6
@question
(a) Use the binomial expansion with first term 1, second term $kx$ and $n = 10$: \\
$(1 + kx)^{10} = 1 + 10C1(kx) + 10C2(kx)^{2} + ...$ \\
$10C1 = 10$ and $10C2 = \frac{10 \times 9}{2} = 45$ \\
$(1 + kx)^{10} = 1 + 10kx + 45k^{2}x^{2} + ...$ \\
Compare the $x$ terms with $-8x$: \\
$10k = -8$ \\
Divide both sides by 10: \\
$k = -\frac{8}{10}$ \\
$k = -\frac{4}{5}$, as required \\
(b) Compare the $x^{2}$ terms: $c = 45k^{2}$ \\
Substitute $k = -\frac{4}{5}$: \\
$c = 45 \times \left( -\frac{4}{5} \right)^{2}$ \\
$= 45 \times \frac{16}{25}$ \\
Divide 45 and 25 by 5: \\
$= 9 \times \frac{16}{5}$ \\
$= \frac{144}{5}$ \\
$c = 28.8$ \\
(c) The expansion is $(1 - 0.8x)^{10} = 1 - 8x + 28.8x^{2} + ...$ \\
Find the value of $x$ that makes the bracket equal to 0.96: \\
$1 - 0.8x = 0.96$ \\
Subtract 1 from both sides: \\
$-0.8x = -0.04$ \\
Divide both sides by $-0.8$: \\
$x = 0.05$ \\
Substitute $x = 0.05$ into the three terms of the expansion: \\
$0.96^{10} \approx 1 - 8(0.05) + 28.8(0.05)^{2}$ \\
$= 1 - 0.4 + 28.8(0.0025)$ \\
$= 1 - 0.4 + 0.072$ \\
$= 0.672$ \\
The estimate is 0.672 (3 dp) \\
(For comparison, the true value is $0.96^{10} = 0.6648...$)

@q 7
@topic Log graph to find power model
@marks 5
@question
(a) Write the model as a power: \\
$V = a \times (t + 1)^{\frac{1}{k}}$ \\
Take logs to base 10 of both sides: \\
$\log_{10} V = \log_{10} \left( a(t + 1)^{\frac{1}{k}} \right)$ \\
Use the product law $\log (ab) = \log a + \log b$: \\
$\log_{10} V = \log_{10} a + \log_{10} (t + 1)^{\frac{1}{k}}$ \\
Use the power law $\log a^{n} = n\log a$: \\
$\log_{10} V = \log_{10} a + \frac{1}{k}\log_{10} (t + 1)$ \\
Write it in the form of a line, with $\log_{10} (t + 1)$ on the horizontal axis: \\
$\log_{10} V = \frac{1}{k} \times \log_{10} (t + 1) + \log_{10} a$ \\
So the gradient of the line is $\frac{1}{k}$ and the vertical intercept is $\log_{10} a$ \\
The line passes through $(0, -0.18)$, so the intercept is: \\
$\log_{10} a = -0.18$ \\
Use the definition of a log: \\
$a = 10^{-0.18}$ \\
$a = 0.66069...$ \\
$a = 0.6607$ (4 sf) \\
Find the gradient from $(0, -0.18)$ and $(3, 0.57)$: \\
$\text{gradient} = \frac{0.57 - (-0.18)}{3 - 0}$ \\
$= \frac{0.75}{3}$ \\
$= 0.25$ \\
$\frac{1}{k} = 0.25$ \\
$k = 4$ \\
The model is: \\
$V = 0.6607 \times \sqrt[4]{t + 1}$ \\
(b) When $t = 0$: \\
$V = 0.6607 \times \sqrt[4]{0 + 1}$ \\
$= 0.6607 \times 1$ \\
$V = 0.6607$ litres

@q 8
@topic Bitangent to a quartic, area
@marks 10
@question
(a) Find the $y$ coordinate of $A$ by putting $x = -1$: \\
$y = (-1)^{4} - 4(-1)^{3} - 2(-1)^{2} + 9(-1) + 20$ \\
$= 1 + 4 - 2 - 9 + 20$ \\
$= 14$ \\
$A = (-1, 14)$ \\
Differentiate, using $\frac{d}{dx}(x^{n}) = nx^{n-1}$: \\
$\frac{dy}{dx} = 4x^{3} - 12x^{2} - 4x + 9$ \\
At $x = -1$: \\
$\frac{dy}{dx} = 4(-1)^{3} - 12(-1)^{2} - 4(-1) + 9$ \\
$= -4 - 12 + 4 + 9$ \\
$= -3$ \\
Use $y - y_{1} = m(x - x_{1})$ with $m = -3$ and $A(-1, 14)$: \\
$y - 14 = -3(x + 1)$ \\
Expand the bracket: \\
$y - 14 = -3x - 3$ \\
Add 14 to both sides: \\
$y = -3x + 11$ \\
$y = 11 - 3x$, as required \\
(b) $l$ is a tangent at $B$ if, at $x = 3$, the curve and the line have the same $y$ value and the same gradient \\
The $y$ value on the curve at $x = 3$: \\
$y = 3^{4} - 4(3)^{3} - 2(3)^{2} + 9(3) + 20$ \\
$= 81 - 108 - 18 + 27 + 20$ \\
$= 2$ \\
The $y$ value on the line at $x = 3$: \\
$y = 11 - 3(3)$ \\
$= 11 - 9$ \\
$= 2$ \\
These match. Now the gradient of the curve at $x = 3$: \\
$\frac{dy}{dx} = 4(3)^{3} - 12(3)^{2} - 4(3) + 9$ \\
$= 108 - 108 - 12 + 9$ \\
$= -3$ \\
This equals the gradient of $l$, which is $-3$ \\
So $l$ touches $C$ at $x = 3$, and the $x$ coordinate of $B$ is 3, as required \\
(c) $R$ lies between the curve (above) and the line (below), from $x = -1$ to $x = 3$ \\
Curve minus line: \\
$\left( x^{4} - 4x^{3} - 2x^{2} + 9x + 20 \right) - (11 - 3x)$ \\
$= x^{4} - 4x^{3} - 2x^{2} + 9x + 20 - 11 + 3x$ \\
$= x^{4} - 4x^{3} - 2x^{2} + 12x + 9$ \\
$\text{Area} = \int_{-1}^{3} \left( x^{4} - 4x^{3} - 2x^{2} + 12x + 9 \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$: \\
$= \left[ \frac{x^{5}}{5} - x^{4} - \frac{2x^{3}}{3} + 6x^{2} + 9x \right]_{-1}^{3}$ \\
Upper limit $x = 3$: \\
$\frac{243}{5} - 81 - \frac{2(27)}{3} + 6(9) + 27$ \\
$= \frac{243}{5} - 81 - 18 + 54 + 27$ \\
$= \frac{243}{5} - 18$ \\
$= \frac{243}{5} - \frac{90}{5}$ \\
$= \frac{153}{5}$ \\
Lower limit $x = -1$: \\
$\frac{-1}{5} - 1 - \frac{2(-1)}{3} + 6(1) + 9(-1)$ \\
$= -\frac{1}{5} - 1 + \frac{2}{3} + 6 - 9$ \\
$= -\frac{1}{5} + \frac{2}{3} - 4$ \\
Write over the common denominator 15: \\
$= -\frac{3}{15} + \frac{10}{15} - \frac{60}{15}$ \\
$= -\frac{53}{15}$ \\
Subtract the lower limit from the upper limit: \\
$\text{Area} = \frac{153}{5} - \left( -\frac{53}{15} \right)$ \\
$= \frac{459}{15} + \frac{53}{15}$ \\
$= \frac{512}{15}$, as required \\
(Check: the integrand factorises as $(x + 1)^{2}(x - 3)^{2}$, which is never negative, so the curve is above the line between $A$ and $B$)

@q 9
@topic Logs in terms of x and y
@marks 5
@question
(a) Write 9 as $3^{2}$ in $x = \log_{a} 9$: \\
$x = \log_{a} 3^{2}$ \\
Use the power law $\log a^{n} = n\log a$: \\
$x = 2\log_{a} 3$ \\
Divide both sides by 2: \\
$\log_{a} 3 = \frac{x}{2}$ \\
(b) Write 6 as $2 \times 3$ and use the product law $\log (ab) = \log a + \log b$: \\
$\log_{a} 6 = \log_{a} 2 + \log_{a} 3$ \\
We know $\log_{a} 3 = \frac{x}{2}$. For $\log_{a} 2$, write 64 as $2^{6}$ in $y = \log_{a} 64$: \\
$y = \log_{a} 2^{6}$ \\
$y = 6\log_{a} 2$ \\
Divide both sides by 6: \\
$\log_{a} 2 = \frac{y}{6}$ \\
$\log_{a} 6 = \frac{y}{6} + \frac{x}{2}$ \\
(c) Use the product law on $8a$: \\
$\log_{a} (8a) = \log_{a} 8 + \log_{a} a$ \\
$\log_{a} a = 1$, and $8 = 2^{3}$ so $\log_{a} 8 = 3\log_{a} 2$: \\
$= 3\log_{a} 2 + 1$ \\
Replace $\log_{a} 2$ with $\frac{y}{6}$: \\
$= 3 \times \frac{y}{6} + 1$ \\
$= \frac{y}{2} + 1$

@q 10
@topic Circle tangent gradient, find equation
@marks 8
@question
(a) The radius $PQ$ is perpendicular to the tangent $l$ at $Q$. The gradient of $l$ is $\frac{1}{3}$, so the gradient of $PQ$ is the negative reciprocal: \\
$m_{PQ} = -3$ \\
Work out the gradient of $PQ$ from the coordinates, $P(k + 3, 7)$ and $Q(2k + 4, k^{2})$. Expand $2(k + 2) = 2k + 4$: \\
$m_{PQ} = \frac{k^{2} - 7}{(2k + 4) - (k + 3)}$ \\
$= \frac{k^{2} - 7}{k + 1}$ \\
Set this equal to $-3$: \\
$\frac{k^{2} - 7}{k + 1} = -3$ \\
Multiply both sides by $(k + 1)$ (not zero, as $k$ is positive): \\
$k^{2} - 7 = -3(k + 1)$ \\
Expand the bracket: \\
$k^{2} - 7 = -3k - 3$ \\
Add $3k$ to both sides: \\
$k^{2} - 7 + 3k = -3$ \\
Add 3 to both sides: \\
$k^{2} + 3k - 7 + 3 = 0$ \\
$k^{2} + 3k - 4 = 0$, as required \\
(b) Factorise. Two numbers that multiply to $-4$ and add to 3 are 4 and $-1$: \\
$(k + 4)(k - 1) = 0$ \\
$k = -4$ or $k = 1$ \\
$k$ is positive, so reject $k = -4$ \\
$k = 1$ \\
Centre $P = (k + 3, 7) = (4, 7)$ \\
Point $Q = (2(k + 2), k^{2}) = (2(3), 1) = (6, 1)$ \\
The radius is the distance $PQ$. Use $r^{2} = (x_{2} - x_{1})^{2} + (y_{2} - y_{1})^{2}$: \\
$r^{2} = (6 - 4)^{2} + (1 - 7)^{2}$ \\
$= 2^{2} + (-6)^{2}$ \\
$= 4 + 36$ \\
$= 40$ \\
The circle has centre $(4, 7)$, so: \\
$(x - 4)^{2} + (y - 7)^{2} = 40$ \\
(Check: the gradient of $PQ$ is $\frac{1 - 7}{6 - 4} = -3$, which is perpendicular to the tangent gradient $\frac{1}{3}$)

@q 11
@topic Exponential models, fish populations
@marks 6
@question
(a) Put $t = 0$ in each model. $e^{0} = 1$: \\
$P_{A} = 50e^{0} = 50$ \\
$P_{B} = 35 + ke^{0} = 35 + k$ \\
The numbers are equal at $t = 0$: \\
$50 = 35 + k$ \\
Subtract 35 from both sides: \\
$k = 15$ \\
(b) Differentiate each model. The derivative of $e^{at}$ is $ae^{at}$: \\
$P_{A} = 50e^{-0.004t}$ \\
$\frac{dP_{A}}{dt} = 50 \times (-0.004)e^{-0.004t}$ \\
$= -0.2e^{-0.004t}$ \\
$P_{B} = 35 + 15e^{0.006t}$ \\
$\frac{dP_{B}}{dt} = 15 \times 0.006e^{0.006t}$ \\
$= 0.09e^{0.006t}$ \\
The rate of decrease of $A$ is the negative of $\frac{dP_{A}}{dt}$, which is $0.2e^{-0.004t}$ \\
At $t = T$ the rate of decrease of $A$ equals the rate of increase of $B$: \\
$0.2e^{-0.004T} = 0.09e^{0.006T}$ \\
Divide both sides by $0.2$: \\
$e^{-0.004T} = \frac{0.09}{0.2}e^{0.006T}$ \\
Divide both sides by $e^{0.006T}$: \\
$\frac{e^{-0.004T}}{e^{0.006T}} = \frac{0.09}{0.2}$ \\
Subtract the indices on the left-hand side: \\
$e^{-0.004T - 0.006T} = 0.45$ \\
$e^{-0.01T} = 0.45$ \\
Take natural logs of both sides: \\
$-0.01T = \ln 0.45$ \\
$\ln 0.45 = -0.798507...$ \\
Divide both sides by $-0.01$: \\
$T = \frac{-0.798507...}{-0.01}$ \\
$T = 79.85...$ \\
$T = 80$ weeks (nearest integer) \\
(Check with $T = 79.85$: $0.2e^{-0.004 \times 79.85} = 0.1453$ and $0.09e^{0.006 \times 79.85} = 0.1453$)

@q 12
@topic Enclosure perimeter, minimise
@marks 13
@question
(a) The semicircle has diameter $x$, so its radius is $\frac{x}{2}$. Its area is: \\
$\frac{1}{2}\pi \left( \frac{x}{2} \right)^{2}$ \\
$= \frac{1}{2}\pi \times \frac{x^{2}}{4}$ \\
$= \frac{\pi x^{2}}{8}$ \\
The area of the rectangle is $xy$. The total area is 200: \\
$xy + \frac{\pi x^{2}}{8} = 200$ \\
Subtract $\frac{\pi x^{2}}{8}$ from both sides: \\
$xy = 200 - \frac{\pi x^{2}}{8}$ \\
Divide both sides by $x$: \\
$y = \frac{200}{x} - \frac{\pi x}{8}$ \\
The perimeter is the curved part plus the straight sides. The curved part is half a circle, which is half of $\pi \times \text{diameter}$: \\
$\text{curved part} = \frac{1}{2}\pi x$ \\
The straight parts are two sides of length $y$ and one side of length $x$ (the diameter is not part of the perimeter, as it is inside the shape): \\
$P = \frac{\pi x}{2} + 2y + x$ \\
Work out $2y$: \\
$2y = \frac{400}{x} - \frac{\pi x}{4}$ \\
Substitute into $P$: \\
$P = \frac{\pi x}{2} + \frac{400}{x} - \frac{\pi x}{4} + x$ \\
Collect the $x$ terms. $\frac{\pi x}{2} - \frac{\pi x}{4} = \frac{\pi x}{4}$: \\
$P = x + \frac{\pi x}{4} + \frac{400}{x}$ \\
Take out the common factor $x$ from the first two terms: \\
$P = \left( 1 + \frac{\pi}{4} \right)x + \frac{400}{x}$, as required \\
(b) Write the last term as a power: \\
$P = \left( 1 + \frac{\pi}{4} \right)x + 400x^{-1}$ \\
Differentiate, using $\frac{d}{dx}(x^{n}) = nx^{n-1}$: \\
$\frac{dP}{dx} = 1 + \frac{\pi}{4} - 400x^{-2}$ \\
$\frac{dP}{dx} = 1 + \frac{\pi}{4} - \frac{400}{x^{2}}$ \\
A stationary value is where $\frac{dP}{dx} = 0$: \\
$1 + \frac{\pi}{4} - \frac{400}{x^{2}} = 0$ \\
Add $\frac{400}{x^{2}}$ to both sides: \\
$1 + \frac{\pi}{4} = \frac{400}{x^{2}}$ \\
Multiply both sides by $x^{2}$: \\
$\left( 1 + \frac{\pi}{4} \right)x^{2} = 400$ \\
Divide both sides by $\left( 1 + \frac{\pi}{4} \right)$: \\
$x^{2} = \frac{400}{1 + \frac{\pi}{4}}$ \\
Multiply the top and the bottom by 4: \\
$x^{2} = \frac{1600}{4 + \pi}$ \\
$x^{2} = 224.04...$ \\
Take the positive square root, as $x$ is a length: \\
$x = \frac{40}{\sqrt{4 + \pi}}$ \\
$x = 14.968...$ metres \\
(c) Differentiate $\frac{dP}{dx} = 1 + \frac{\pi}{4} - 400x^{-2}$ again: \\
$\frac{d^{2}P}{dx^{2}} = -400 \times (-2)x^{-3}$ \\
$\frac{d^{2}P}{dx^{2}} = 800x^{-3}$ \\
$\frac{d^{2}P}{dx^{2}} = \frac{800}{x^{3}}$ \\
$x$ is positive, so $x^{3} > 0$ and: \\
$\frac{d^{2}P}{dx^{2}} > 0$ \\
A positive second derivative at a stationary point means a minimum, so this value of $x$ gives a minimum value of $P$ \\
(d) The curved part of the fence has length $\frac{\pi x}{2}$. At the minimum, $x = 14.968...$: \\
$\text{curved part} = \frac{\pi \times 14.968...}{2}$ \\
$= 23.51...$ metres \\
Only 20 metres of the flexible fencing is available, and $23.51 > 20$ \\
So the curved part of the fence cannot be built when $P$ takes its minimum value

@q 13
@topic Trig equation to quadratic in tan
@marks 9
@question
(a) Expand the bracket: \\
$5\sin^{2} \theta - 5\sin \theta \cos \theta = 3$ \\
Divide every term by $\cos^{2} \theta$ (not zero: if $\cos \theta = 0$ then $\sin^{2} \theta = 1$ and the left-hand side would be 5, not 3): \\
$\frac{5\sin^{2} \theta}{\cos^{2} \theta} - \frac{5\sin \theta \cos \theta}{\cos^{2} \theta} = \frac{3}{\cos^{2} \theta}$ \\
Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$ and $\frac{1}{\cos^{2} \theta} = \sec^{2} \theta$: \\
$5\tan^{2} \theta - 5\tan \theta = 3\sec^{2} \theta$ \\
Use the identity $\sec^{2} \theta = 1 + \tan^{2} \theta$: \\
$5\tan^{2} \theta - 5\tan \theta = 3\left( 1 + \tan^{2} \theta \right)$ \\
Expand the bracket: \\
$5\tan^{2} \theta - 5\tan \theta = 3 + 3\tan^{2} \theta$ \\
Subtract $3 + 3\tan^{2} \theta$ from both sides: \\
$5\tan^{2} \theta - 3\tan^{2} \theta - 5\tan \theta - 3 = 0$ \\
$2\tan^{2} \theta - 5\tan \theta - 3 = 0$, as required \\
(b) The equation is the same with $\theta$ replaced by $x$. Let $t = \tan x$: \\
$2t^{2} - 5t - 3 = 0$ \\
Factorise. Two numbers that multiply to $2 \times (-3) = -6$ and add to $-5$ are $-6$ and $1$: \\
$2t^{2} - 6t + t - 3 = 0$ \\
$2t(t - 3) + 1(t - 3) = 0$ \\
$(2t + 1)(t - 3) = 0$ \\
$t = -\frac{1}{2}$ or $t = 3$ \\
Case $\tan x = 3$: \\
$x = \tan^{-1}(3) = 71.565...$ degrees \\
Tan repeats every 180 degrees, so add 180: \\
$x = 71.565... + 180 = 251.565...$ degrees \\
Case $\tan x = -\frac{1}{2}$: \\
$\tan^{-1}\left( -\frac{1}{2} \right) = -26.565...$ degrees, which is outside the range, so add 180 and 360: \\
$x = -26.565... + 180 = 153.434...$ degrees \\
$x = -26.565... + 360 = 333.434...$ degrees \\
$x = 71.6$, $153.4$, $251.6$ or $333.4$ degrees (1 dp) \\
(c) Let $x = 3\alpha$. The equation is the one in part (b), so $3\alpha$ is any angle that is a solution of it, plus or minus whole turns of 360 degrees: \\
$3\alpha = 71.565... + 360n$, $153.434... + 360n$, $251.565... + 360n$ or $333.434... + 360n$ \\
The range $1080 < \alpha < 1440$ means $3240 < 3\alpha < 4320$ degrees \\
$3240 = 9 \times 360$, so the first turn in this range starts at 9 turns: \\
$3\alpha = 71.565... + 3240$ \\
$= 3311.565...$ \\
This is the smallest, as all other solutions in the turn are larger and the previous turn ends at 3240 \\
Divide by 3: \\
$\alpha = \frac{3311.565...}{3}$ \\
$= 1103.855...$ \\
$\alpha = 1103.9$ degrees (1 dp)

@q 14
@topic Counterexample, sum of five squares
@marks 4
@question
(a) Try the square numbers 1, 4 and 9: \\
$1 + 4 + 9 = 14$ \\
$14 \div 3 = 4$ remainder 2, so 14 is not divisible by 3 \\
So the statement is false \\
(b) Let the five consecutive whole numbers be $n - 2$, $n - 1$, $n$, $n + 1$ and $n + 2$. The sum of their squares is: \\
$(n - 2)^{2} + (n - 1)^{2} + n^{2} + (n + 1)^{2} + (n + 2)^{2}$ \\
Expand each bracket one at a time: \\
$(n - 2)^{2} = n^{2} - 4n + 4$ \\
$(n - 1)^{2} = n^{2} - 2n + 1$ \\
$(n + 1)^{2} = n^{2} + 2n + 1$ \\
$(n + 2)^{2} = n^{2} + 4n + 4$ \\
Add all five squares: \\
$n^{2} - 4n + 4 + n^{2} - 2n + 1 + n^{2} + n^{2} + 2n + 1 + n^{2} + 4n + 4$ \\
The $n$ terms cancel: $-4n - 2n + 2n + 4n = 0$ \\
The $n^{2}$ terms: $5n^{2}$ \\
The numbers: $4 + 1 + 1 + 4 = 10$ \\
Sum $= 5n^{2} + 10$ \\
Take out the common factor 5: \\
$= 5\left( n^{2} + 2 \right)$ \\
$n^{2} + 2$ is a whole number, so the sum is 5 times a whole number \\
So the sum of 5 consecutive square numbers is always divisible by 5, as required
