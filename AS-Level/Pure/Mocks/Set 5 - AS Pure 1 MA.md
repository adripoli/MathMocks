@paper AS1 Mock Set 5

@q 1
@topic Differentiation, parallel line
@marks 5
@question
(a) Write each term as a power of $x$ so it can be differentiated: \\
$y = \frac{1}{4}x^{3} + 2x^{-1} - 7$ \\
Differentiate each term: multiply by the power, then reduce the power by 1 \\
$\frac{d}{dx}\left( \frac{1}{4}x^{3} \right) = 3 \times \frac{1}{4}x^{2}$ \\
$= \frac{3}{4}x^{2}$ \\
$\frac{d}{dx}\left( 2x^{-1} \right) = -1 \times 2x^{-2}$ \\
$= -2x^{-2}$ \\
$\frac{d}{dx}(-7) = 0$ \\
$\frac{dy}{dx} = \frac{3}{4}x^{2} - 2x^{-2}$ \\
Write the negative power as a fraction: \\
$\frac{dy}{dx} = \frac{3}{4}x^{2} - \frac{2}{x^{2}}$ \\
(b) The gradient of the tangent at $P$ is the value of $\frac{dy}{dx}$ at $x = 2$: \\
$\frac{dy}{dx} = \frac{3}{4}(2)^{2} - \frac{2}{2^{2}}$ \\
Evaluate each power: \\
$= \frac{3}{4}(4) - \frac{2}{4}$ \\
$= 3 - \frac{1}{2}$ \\
$= \frac{5}{2}$ \\
Parallel lines have the same gradient, so $l$ has gradient $\frac{5}{2}$ \\
Use $y - y_{1} = m(x - x_{1})$ with $m = \frac{5}{2}$ and the point $(3, 11)$: \\
$y - 11 = \frac{5}{2}(x - 3)$ \\
Multiply both sides by 2 to remove the fraction: \\
$2(y - 11) = 5(x - 3)$ \\
Expand both brackets: \\
$2y - 22 = 5x - 15$ \\
Move every term to the right-hand side (subtract $2y$ and add 22 on both sides): \\
$0 = 5x - 2y - 15 + 22$ \\
$0 = 5x - 2y + 7$ \\
So the equation of $l$ is: \\
$5x - 2y + 7 = 0$ \\
(Check: the point $(3, 11)$ gives $15 - 22 + 7 = 0$)

@q 2
@topic Vectors, magnitude inequality
@marks 6
@question
(a) Go from $P$ back to $O$ and then on to $Q$: \\
$\text{PQ} = \text{OQ} - \text{OP}$ \\
$= (2\mathbf{i} - 4\mathbf{j}) - (a\mathbf{i} + 6\mathbf{j})$ \\
Remove the brackets, changing the signs in the second one: \\
$= 2\mathbf{i} - 4\mathbf{j} - a\mathbf{i} - 6\mathbf{j}$ \\
Collect the $\mathbf{i}$ terms and the $\mathbf{j}$ terms: \\
$\mathbf{i}$ part: $2 - a$ \\
$\mathbf{j}$ part: $-4 - 6 = -10$ \\
$\text{PQ} = (2 - a)\mathbf{i} - 10\mathbf{j}$ \\
(b) The magnitude is the square root of (i part squared plus j part squared): \\
$|\text{PQ}| = \sqrt{(2 - a)^{2} + (-10)^{2}}$ \\
$= \sqrt{(2 - a)^{2} + 100}$ \\
We are told this is less than $10\sqrt{2}$: \\
$\sqrt{(2 - a)^{2} + 100} < 10\sqrt{2}$ \\
Both sides are positive, so square both sides: \\
$(2 - a)^{2} + 100 < \left( 10\sqrt{2} \right)^{2}$ \\
$\left( 10\sqrt{2} \right)^{2} = 100 \times 2 = 200$ \\
$(2 - a)^{2} + 100 < 200$ \\
Expand the bracket: $(2 - a)^{2} = 4 - 4a + a^{2}$ \\
$4 - 4a + a^{2} + 100 < 200$ \\
Collect the numbers: \\
$a^{2} - 4a + 104 < 200$ \\
Subtract 200 from both sides: \\
$a^{2} - 4a - 96 < 0$ \\
Factorise: two numbers that multiply to $-96$ and add to $-4$ are $-12$ and $8$ \\
$(a - 12)(a + 8) < 0$ \\
The critical values are where each bracket is zero: \\
$a = 12$ and $a = -8$ \\
The graph of $a^{2} - 4a - 96$ is a U-shaped parabola, so it is below zero between its roots: \\
$-8 < a < 12$ \\
(Check: $a = 0$ gives $4 + 100 = 104 < 200$, which is true)

@q 3
@topic Counter example and proof
@marks 4
@question
(i) Try $n = 3$, which is in $\mathbb{N}$: \\
$2n^{2} + 3n + 1 = 2(3)^{2} + 3(3) + 1$ \\
$= 2(9) + 9 + 1$ \\
$= 18 + 9 + 1$ \\
$= 28$ \\
The multiples of 3 near 28 are $3 \times 9 = 27$ and $3 \times 10 = 30$ \\
28 is between them, so 28 is not a multiple of 3 \\
So the statement is false for $n = 3$, which is a counter example \\
(ii) Complete the square on $x^{2} - 6x + 10$ \\
Half of the coefficient of $x$ is $-3$, so use $(x - 3)^{2}$ \\
Expand it: $(x - 3)^{2} = x^{2} - 6x + 9$ \\
So $x^{2} - 6x = (x - 3)^{2} - 9$ \\
$x^{2} - 6x + 10 = (x - 3)^{2} - 9 + 10$ \\
$= (x - 3)^{2} + 1$ \\
A real number squared is never negative: \\
$(x - 3)^{2} \geq 0$ for all real $x$ \\
Add 1 to both sides: \\
$(x - 3)^{2} + 1 \geq 1$ \\
Since $1 > 0$: \\
$x^{2} - 6x + 10 > 0$ for all real values of $x$, as required

@q 4
@topic Exponential equation, substitution
@marks 5
@question
(a) Write 16 as a power of 4: $16 = 4^{2}$ \\
$16^{x} = \left( 4^{2} \right)^{x}$ \\
Power of a power, multiply the indices: \\
$= 4^{2x}$ \\
Write $4^{2x}$ as a square: \\
$= \left( 4^{x} \right)^{2}$ \\
Since $p = 4^{x}$: \\
$16^{x} = p^{2}$ \\
Now $2^{2x - 1}$. Use $a^{m - n} = \frac{a^{m}}{a^{n}}$: \\
$2^{2x - 1} = \frac{2^{2x}}{2^{1}}$ \\
Write $2^{2x}$ as a power of 4: \\
$2^{2x} = \left( 2^{2} \right)^{x} = 4^{x} = p$ \\
$2^{2x - 1} = \frac{p}{2}$ \\
Also $3 \times 4^{x} = 3p$ \\
Substitute $16^{x} = p^{2}$, $2^{2x - 1} = \frac{p}{2}$ and $4^{x} = p$ into the equation: \\
$1 + 4p^{2} = 11 \times \frac{p}{2} + 3p$ \\
Write $3p$ as a fraction over 2: \\
$1 + 4p^{2} = \frac{11p}{2} + \frac{6p}{2}$ \\
$1 + 4p^{2} = \frac{17p}{2}$ \\
Multiply both sides by 2: \\
$2 + 8p^{2} = 17p$ \\
Subtract $17p$ from both sides: \\
$8p^{2} - 17p + 2 = 0$ as required \\
(b) Factorise $8p^{2} - 17p + 2 = 0$ \\
Two numbers that multiply to $8 \times 2 = 16$ and add to $-17$ are $-16$ and $-1$ \\
Split the middle term: \\
$8p^{2} - 16p - p + 2 = 0$ \\
Factorise in pairs: \\
$8p(p - 2) - 1(p - 2) = 0$ \\
$(8p - 1)(p - 2) = 0$ \\
So $8p - 1 = 0$ or $p - 2 = 0$ \\
$p = \frac{1}{8}$ or $p = 2$ \\
Now put back $p = 4^{x}$ \\
Case 1: $4^{x} = 2$ \\
Write 4 as $2^{2}$: \\
$\left( 2^{2} \right)^{x} = 2^{1}$ \\
$2^{2x} = 2^{1}$ \\
Same base, so the indices are equal: \\
$2x = 1$ \\
$x = \frac{1}{2}$ \\
Case 2: $4^{x} = \frac{1}{8}$ \\
Write $\frac{1}{8}$ as a power of 2: $\frac{1}{8} = \frac{1}{2^{3}} = 2^{-3}$ \\
$2^{2x} = 2^{-3}$ \\
Same base, so the indices are equal: \\
$2x = -3$ \\
$x = -\frac{3}{2}$ \\
Both values are fine because $4^{x}$ is positive for every $x$ \\
$x = \frac{1}{2}$ or $x = -\frac{3}{2}$ \\
(Check $x = \frac{1}{2}$: left side $1 + 4 \times 16^{\frac{1}{2}} = 1 + 16 = 17$ and right side $11 \times 2^{0} + 3 \times 2 = 11 + 6 = 17$) \\
(Check $x = -\frac{3}{2}$: left side $1 + \frac{4}{64} = \frac{17}{16}$ and right side $\frac{11}{16} + \frac{3}{8} = \frac{11}{16} + \frac{6}{16} = \frac{17}{16}$)

@q 5
@topic Circle, cosine rule, area
@marks 8
@question
(a)(i) The radius is the distance from the centre $A(3, 6)$ to $P(10, 7)$ \\
Use $r^{2} = (x_{P} - x_{A})^{2} + (y_{P} - y_{A})^{2}$ \\
$r^{2} = (10 - 3)^{2} + (7 - 6)^{2}$ \\
$= 7^{2} + 1^{2}$ \\
$= 49 + 1$ \\
$= 50$ \\
$r = \sqrt{50}$ \\
Write 50 as $25 \times 2$: \\
$= \sqrt{25} \times \sqrt{2}$ \\
$r = 5\sqrt{2}$ \\
(a)(ii) A circle with centre $(a, b)$ and radius $r$ has equation $(x - a)^{2} + (y - b)^{2} = r^{2}$ \\
Here the centre is $(3, 6)$ and $r^{2} = 50$: \\
$(x - 3)^{2} + (y - 6)^{2} = 50$ \\
(b) Find the three side lengths of triangle $PQR$ \\
$PQ^{2} = (10 - 8)^{2} + (7 - 1)^{2}$ \\
$= 2^{2} + 6^{2}$ \\
$= 4 + 36$ \\
$= 40$ \\
$PQ = \sqrt{40}$ \\
Write 40 as $4 \times 10$: \\
$= \sqrt{4} \times \sqrt{10}$ \\
$PQ = 2\sqrt{10}$ \\
$QR^{2} = (8 - 2)^{2} + (1 - 13)^{2}$ \\
$= 6^{2} + (-12)^{2}$ \\
$= 36 + 144$ \\
$= 180$ \\
$PR = 10$ is given, so $PR^{2} = 100$ \\
Cosine rule in triangle $PQR$, for the side $QR$ opposite angle $RPQ$: \\
$QR^{2} = PR^{2} + PQ^{2} - 2 \times PR \times PQ \times \cos RPQ$ \\
Substitute the values: \\
$180 = 100 + 40 - 2(10)\left( 2\sqrt{10} \right)\cos RPQ$ \\
$180 = 140 - 40\sqrt{10} \cos RPQ$ \\
Subtract 140 from both sides: \\
$40 = -40\sqrt{10} \cos RPQ$ \\
Divide both sides by $-40\sqrt{10}$: \\
$\cos RPQ = -\frac{40}{40\sqrt{10}}$ \\
Cancel the 40: \\
$\cos RPQ = -\frac{1}{\sqrt{10}}$ \\
Rationalise the denominator: multiply the top and bottom by $\sqrt{10}$ \\
$= -\frac{1 \times \sqrt{10}}{\sqrt{10} \times \sqrt{10}}$ \\
$= -\frac{\sqrt{10}}{10}$ \\
So $\cos RPQ = -\frac{\sqrt{10}}{10}$ as required \\
(c) Area of a triangle $= \frac{1}{2}ab\sin C$ \\
$\text{Area} = \frac{1}{2} \times PR \times PQ \times \sin RPQ$ \\
First find $\sin RPQ$ using $\sin^{2} RPQ + \cos^{2} RPQ = 1$ \\
$\sin^{2} RPQ = 1 - \cos^{2} RPQ$ \\
$= 1 - \left( -\frac{\sqrt{10}}{10} \right)^{2}$ \\
$= 1 - \frac{10}{100}$ \\
$= 1 - \frac{1}{10}$ \\
$= \frac{9}{10}$ \\
Angle $RPQ$ is between 0 and 180 degrees, so its sine is positive: \\
$\sin RPQ = \sqrt{\frac{9}{10}}$ \\
$= \frac{3}{\sqrt{10}}$ \\
Substitute into the area formula: \\
$\text{Area} = \frac{1}{2} \times 10 \times 2\sqrt{10} \times \frac{3}{\sqrt{10}}$ \\
$\frac{1}{2} \times 10 = 5$ \\
$= 5 \times 2\sqrt{10} \times \frac{3}{\sqrt{10}}$ \\
$= 10\sqrt{10} \times \frac{3}{\sqrt{10}}$ \\
The $\sqrt{10}$ cancels: \\
$= 10 \times 3$ \\
$\text{Area} = 30$ \\
(Check with the coordinates of $P(10, 7)$, $Q(8, 1)$, $R(2, 13)$: area $= \frac{1}{2} \left| 10(1 - 13) + 8(13 - 7) + 2(7 - 1) \right| = \frac{1}{2} \left| -120 + 48 + 12 \right| = \frac{1}{2}(60) = 30$)

@q 6
@topic Binomial expansion, find constants
@marks 8
@question
(a) Use the binomial expansion with first term $3$, second term $-\frac{2}{9}x$ and power 7 \\
Term 1: $3^{7}$ \\
$= 2187$ \\
Term 2: $7C1 \times 3^{6} \times \left( -\frac{2}{9}x \right)$ \\
$7C1 = 7$ and $3^{6} = 729$ \\
$= 7 \times 729 \times \left( -\frac{2}{9}x \right)$ \\
Cancel the 9 into 729, since $729 \div 9 = 81$: \\
$= 7 \times 81 \times (-2x)$ \\
$= 567 \times (-2x)$ \\
$= -1134x$ \\
Term 3: $7C2 \times 3^{5} \times \left( -\frac{2}{9}x \right)^{2}$ \\
$7C2 = \frac{7 \times 6}{2} = 21$ and $3^{5} = 243$ \\
Square the bracket: $\left( -\frac{2}{9}x \right)^{2} = \frac{4}{81}x^{2}$ \\
$= 21 \times 243 \times \frac{4}{81}x^{2}$ \\
Cancel the 81 into 243, since $243 \div 81 = 3$: \\
$= 21 \times 3 \times 4x^{2}$ \\
$= 63 \times 4x^{2}$ \\
$= 252x^{2}$ \\
The first 3 terms are $2187 - 1134x + 252x^{2}$ \\
(b) $f(x) = (a + bx)\left( 2187 - 1134x + 252x^{2} + \ldots \right)$ \\
Multiply out, keeping only the constant term and the $x$ term: \\
Constant term: $a \times 2187 = 2187a$ \\
$x$ term: $a \times (-1134x) + bx \times 2187$ \\
$= -1134ax + 2187bx$ \\
$= (2187b - 1134a)x$ \\
The constant term is 729: \\
$2187a = 729$ \\
Divide both sides by 2187: \\
$a = \frac{729}{2187}$ \\
Since $2187 = 3 \times 729$: \\
$a = \frac{1}{3}$ \\
(c) The coefficient of $x$ is 243: \\
$2187b - 1134a = 243$ \\
Substitute $a = \frac{1}{3}$: \\
$2187b - 1134 \times \frac{1}{3} = 243$ \\
$1134 \times \frac{1}{3} = 378$ \\
$2187b - 378 = 243$ \\
Add 378 to both sides: \\
$2187b = 621$ \\
Divide both sides by 2187: \\
$b = \frac{621}{2187}$ \\
Divide the top and bottom by 27, since $621 = 27 \times 23$ and $2187 = 27 \times 81$: \\
$b = \frac{23}{81}$

@q 7
@topic Gradients with surds, area of triangle
@marks 8
@question
(a) Gradient $= \frac{y_{B} - y_{A}}{x_{B} - x_{A}}$ \\
$m = \frac{5 - 1}{4 - 2\sqrt{2}}$ \\
$= \frac{4}{4 - 2\sqrt{2}}$ \\
Divide the top and bottom by 2: \\
$= \frac{2}{2 - \sqrt{2}}$ \\
Rationalise the denominator: multiply the top and bottom by $2 + \sqrt{2}$ \\
$= \frac{2(2 + \sqrt{2})}{(2 - \sqrt{2})(2 + \sqrt{2})}$ \\
Bottom, using the difference of two squares: \\
$(2 - \sqrt{2})(2 + \sqrt{2}) = 2^{2} - \left( \sqrt{2} \right)^{2}$ \\
$= 4 - 2$ \\
$= 2$ \\
Top: $2(2 + \sqrt{2}) = 4 + 2\sqrt{2}$ \\
$m = \frac{4 + 2\sqrt{2}}{2}$ \\
Divide each term on the top by 2: \\
$m = 2 + \sqrt{2}$ \\
So the gradient is $p + \sqrt{2}$ with $p = 2$ \\
(b) $l_{2}$ is perpendicular to $l_{1}$, so its gradient is $-\frac{1}{m}$ \\
$m_{2} = -\frac{1}{2 + \sqrt{2}}$ \\
Rationalise: multiply the top and bottom by $2 - \sqrt{2}$ \\
$= -\frac{2 - \sqrt{2}}{(2 + \sqrt{2})(2 - \sqrt{2})}$ \\
The bottom is $4 - 2 = 2$ \\
$m_{2} = -\frac{2 - \sqrt{2}}{2}$ \\
Equation of $l_{2}$ through $B(4, 5)$, using $y - y_{1} = m(x - x_{1})$: \\
$y - 5 = -\frac{2 - \sqrt{2}}{2}(x - 4)$ \\
$C$ is on the $x$-axis, so put $y = 0$: \\
$0 - 5 = -\frac{2 - \sqrt{2}}{2}(x - 4)$ \\
$-5 = -\frac{2 - \sqrt{2}}{2}(x - 4)$ \\
Multiply both sides by $-2$: \\
$10 = (2 - \sqrt{2})(x - 4)$ \\
Divide both sides by $2 - \sqrt{2}$: \\
$x - 4 = \frac{10}{2 - \sqrt{2}}$ \\
Rationalise: multiply the top and bottom by $2 + \sqrt{2}$ \\
$= \frac{10(2 + \sqrt{2})}{(2 - \sqrt{2})(2 + \sqrt{2})}$ \\
$= \frac{10(2 + \sqrt{2})}{2}$ \\
$= 5(2 + \sqrt{2})$ \\
$= 10 + 5\sqrt{2}$ \\
Add 4 to both sides: \\
$x = 14 + 5\sqrt{2}$ \\
So $C$ is the point $\left( 14 + 5\sqrt{2}, 0 \right)$ \\
Triangle $OBC$ has base $OC$ along the $x$-axis: \\
base $= 14 + 5\sqrt{2}$ \\
Its height is the $y$ coordinate of $B$: \\
height $= 5$ \\
$\text{Area} = \frac{1}{2} \times \text{base} \times \text{height}$ \\
$= \frac{1}{2} \times \left( 14 + 5\sqrt{2} \right) \times 5$ \\
Expand the bracket: \\
$= \frac{1}{2}\left( 70 + 25\sqrt{2} \right)$ \\
Halve each term: \\
$= 35 + \frac{25}{2}\sqrt{2}$ \\
So $a = 35$ and $b = \frac{25}{2}$

@q 8
@topic Exponential model from log graph
@marks 8
@question
(a) The graph of $\log_{10} N$ against $t$ is a straight line, so $\log_{10} N = mt + c$ \\
It cuts the vertical axis at $(0, 1.3)$, so $c = 1.3$ \\
Gradient: \\
$m = \frac{2.9 - 1.3}{8 - 0}$ \\
$= \frac{1.6}{8}$ \\
$= 0.2$ \\
$\log_{10} N = 0.2t + 1.3$ \\
Raise 10 to the power of each side, since $10^{\log_{10} N} = N$: \\
$N = 10^{0.2t + 1.3}$ \\
Split the index using $10^{m + n} = 10^{m} \times 10^{n}$: \\
$N = 10^{1.3} \times 10^{0.2t}$ \\
Write $10^{0.2t}$ as $\left( 10^{0.2} \right)^{t}$: \\
$N = 10^{1.3} \times \left( 10^{0.2} \right)^{t}$ \\
Compare with $N = ab^{t}$: \\
$a = 10^{1.3} = 19.9526...$ \\
$a = 20$ to 2 significant figures \\
$b = 10^{0.2} = 1.58489...$ \\
$b = 1.585$ to 4 significant figures \\
$N = 20 \times 1.585^{t}$ \\
(Check by logs: $\log_{10} N = \log_{10} a + t\log_{10} b$, so $\log_{10} a = 1.3$ and $\log_{10} b = 0.2$) \\
(b) Put $t = 1$ into $N = ab^{t}$: \\
$N = ab^{1} = ab$ \\
So $ab$ is the value of $N$ when $t = 1$ \\
$ab = 10^{1.3} \times 10^{0.2}$ \\
$= 10^{1.5}$ \\
$= 31.6...$ \\
After 1 year the service has about 32 million subscribers \\
(c) Put $t = 4$ into $\log_{10} N = 0.2t + 1.3$: \\
$\log_{10} N = 0.2(4) + 1.3$ \\
$= 0.8 + 1.3$ \\
$= 2.1$ \\
Raise 10 to the power of each side: \\
$N = 10^{2.1}$ \\
$= 125.89...$ \\
To 2 significant figures: \\
$N = 130$ \\
After exactly 4 years there are about 130 million subscribers \\
(Check with the rounded equation: $20 \times 1.585^{4} = 126.2$, which is also 130 to 2 significant figures) \\
(d) The model has $N$ growing exponentially for ever, with no upper limit \\
In reality the number of subscribers cannot be more than the number of people who could use the service, so growth would slow down and level off

@q 9
@topic Area under curve, find k
@marks 8
@question
(a) The area of $R$ is the integral of $y$ from $x = 4$ to $x = k$ \\
Write $\frac{5}{\sqrt{x}}$ as a power of $x$: $\frac{5}{\sqrt{x}} = 5x^{-\frac{1}{2}}$ \\
$\text{Area} = \int_{4}^{k} \left( 5x^{-\frac{1}{2}} + 3 \right) dx$ \\
Integrate each term: add 1 to the power, then divide by the new power \\
For $5x^{-\frac{1}{2}}$ the new power is $-\frac{1}{2} + 1 = \frac{1}{2}$ \\
$\frac{5x^{\frac{1}{2}}}{\frac{1}{2}} = 10x^{\frac{1}{2}}$ \\
For $3$, the integral is $3x$ \\
$= \left[ 10x^{\frac{1}{2}} + 3x \right]_{4}^{k}$ \\
Upper limit, put in $x = k$: \\
$10k^{\frac{1}{2}} + 3k = 10\sqrt{k} + 3k$ \\
Lower limit, put in $x = 4$: \\
$10(4)^{\frac{1}{2}} + 3(4)$ \\
$= 10(2) + 12$ \\
$= 32$ \\
Subtract the lower limit from the upper limit: \\
$\text{Area} = 10\sqrt{k} + 3k - 32$ \\
The area is 16: \\
$10\sqrt{k} + 3k - 32 = 16$ \\
Subtract 16 from both sides: \\
$3k + 10\sqrt{k} - 48 = 0$ as required \\
(b) Let $u = \sqrt{k}$, so $k = u^{2}$ \\
$3u^{2} + 10u - 48 = 0$ \\
Factorise: two numbers that multiply to $3 \times (-48) = -144$ and add to $10$ are $18$ and $-8$ \\
Split the middle term: \\
$3u^{2} + 18u - 8u - 48 = 0$ \\
Factorise in pairs: \\
$3u(u + 6) - 8(u + 6) = 0$ \\
$(3u - 8)(u + 6) = 0$ \\
$u = \frac{8}{3}$ or $u = -6$ \\
$u = \sqrt{k}$ cannot be negative, so reject $u = -6$ \\
$\sqrt{k} = \frac{8}{3}$ \\
Square both sides: \\
$k = \frac{64}{9}$ \\
This is bigger than 4, as the question needs \\
(Check: $3 \times \frac{64}{9} + 10 \times \frac{8}{3} - 48 = \frac{64}{3} + \frac{80}{3} - 48 = 48 - 48 = 0$)

@q 10
@topic Reciprocal curve, discriminant
@marks 9
@question
(a) As $x$ gets very large (positive or negative), $\frac{k}{x}$ gets closer and closer to 0 \\
So $y = \frac{k}{x} + 3$ gets closer and closer to 3 \\
The horizontal asymptote is: \\
$y = 3$ \\
(b) The curve is $y = \frac{k}{x}$ moved up by 3, and $k$ is positive \\
It has a vertical asymptote $x = 0$ and the horizontal asymptote $y = 3$ \\
Crossing the $y$-axis needs $x = 0$, which is not allowed, so there is no $y$ intercept \\
Crossing the $x$-axis: put $y = 0$ \\
$0 = \frac{k}{x} + 3$ \\
Subtract 3 from both sides: \\
$-3 = \frac{k}{x}$ \\
Multiply both sides by $x$: \\
$-3x = k$ \\
Divide both sides by $-3$: \\
$x = -\frac{k}{3}$ \\
The curve crosses the $x$-axis at $\left( -\frac{k}{3}, 0 \right)$ \\
Sketch: two separate branches. The right-hand branch (for $x > 0$) is above the line $y = 3$, falling from very high up beside the $y$-axis and flattening towards $y = 3$ as $x$ increases. The left-hand branch (for $x < 0$) is below the line $y = 3$. It starts close to $y = 3$ on the far left, falls through $\left( -\frac{k}{3}, 0 \right)$ and drops steeply down beside the $y$-axis. Draw the dashed lines $y = 3$ and $x = 0$ and mark the point $\left( -\frac{k}{3}, 0 \right)$ \\
(c) Make $y$ the subject of $2y + x = k$: \\
Subtract $x$ from both sides: \\
$2y = k - x$ \\
Divide both sides by 2: \\
$y = \frac{k - x}{2}$ \\
Where the line meets the curve, the $y$ values are equal: \\
$\frac{k}{x} + 3 = \frac{k - x}{2}$ \\
Multiply both sides by $2x$ (which is not zero): \\
$2k + 6x = x(k - x)$ \\
Expand the bracket: \\
$2k + 6x = kx - x^{2}$ \\
Add $x^{2}$ to both sides and subtract $kx$ from both sides: \\
$x^{2} + 6x - kx + 2k = 0$ \\
Collect the $x$ terms: \\
$x^{2} + (6 - k)x + 2k = 0$ \\
Two distinct points means two different real roots, so the discriminant is positive: $b^{2} - 4ac > 0$ \\
Here $a = 1$, $b = 6 - k$ and $c = 2k$ \\
$(6 - k)^{2} - 4(1)(2k) > 0$ \\
Expand $(6 - k)^{2} = 36 - 12k + k^{2}$ \\
$36 - 12k + k^{2} - 8k > 0$ \\
Collect the $k$ terms: \\
$k^{2} - 20k + 36 > 0$ \\
Factorise: two numbers that multiply to 36 and add to $-20$ are $-2$ and $-18$ \\
$(k - 2)(k - 18) > 0$ \\
The critical values are $k = 2$ and $k = 18$ \\
The graph of $k^{2} - 20k + 36$ is a U-shaped parabola, so it is above zero outside its roots: \\
$k < 2$ or $k > 18$ \\
But $k$ is a positive constant, so $k > 0$ as well: \\
$0 < k < 2$ or $k > 18$ \\
(Neither root of the quadratic in $x$ is $x = 0$, since the constant term $2k$ is not zero, so both points really are on $C$) \\
In set notation: \\
$\{k : 0 < k < 2\} \text{ or } \{k : k > 18\}$

@q 11
@topic Exponential model, rate of change
@marks 8
@question
(a) At the start, $t = 0$ and $A = 120$ \\
$120 = 750 - Me^{k \times 0}$ \\
Any number to the power 0 is 1, so $e^{0} = 1$: \\
$120 = 750 - M$ \\
Add $M$ to both sides and subtract 120 from both sides: \\
$M = 750 - 120$ \\
$M = 630$ \\
(b) After 8 years, $t = 8$ and $A = 400$ \\
$400 = 750 - 630e^{8k}$ \\
Subtract 750 from both sides: \\
$-350 = -630e^{8k}$ \\
Divide both sides by $-630$: \\
$\frac{350}{630} = e^{8k}$ \\
Divide the top and bottom by 70: \\
$\frac{5}{9} = e^{8k}$ \\
Take natural logs of both sides: \\
$\ln \frac{5}{9} = \ln e^{8k}$ \\
Use $\ln e^{x} = x$: \\
$\ln \frac{5}{9} = 8k$ \\
Divide both sides by 8: \\
$k = \frac{1}{8}\ln \frac{5}{9}$ \\
$\ln \frac{5}{9} = -0.587787$ \\
$k = \frac{-0.587787}{8}$ \\
$= -0.0734733...$ \\
$k = -0.0735$ to 3 significant figures \\
The complete equation is: \\
$A = 750 - 630e^{-0.0735t}$ \\
(c) The rate of increase is $\frac{dA}{dt}$ \\
Differentiate $A = 750 - 630e^{kt}$ with respect to $t$ \\
The derivative of $e^{kt}$ is $ke^{kt}$ and the derivative of 750 is 0: \\
$\frac{dA}{dt} = -630ke^{kt}$ \\
Substitute $k = -0.0735$: \\
$\frac{dA}{dt} = -630(-0.0735)e^{-0.0735t}$ \\
Multiply the numbers: $630 \times 0.0735 = 46.305$ \\
$\frac{dA}{dt} = 46.305e^{-0.0735t}$ \\
Put in $t = 3$: \\
$\frac{dA}{dt} = 46.305e^{-0.0735 \times 3}$ \\
$= 46.305e^{-0.2205}$ \\
$e^{-0.2205} = 0.802118$ \\
$= 46.305 \times 0.802118$ \\
$= 37.142...$ \\
The area is increasing at $37.1 \text{ km}^{2}$/year \\
(Using the unrounded $k = -0.0734733...$ gives $37.13...$, which is also 37.1 to 3 significant figures) \\
(d) In the model, $e^{kt}$ tends to 0 as $t$ gets large (because $k$ is negative) \\
So $A$ tends to 750 and can never reach 1000 \\
Refine the model by changing the 750 to 1000: \\
$A = 1000 - Me^{kt}$ \\
(then work out $M$ and $k$ again from the same information)

@q 12
@topic Logarithms, cubic, reject root
@marks 8
@question
(a) Use the power law $n\log_{a} x = \log_{a} x^{n}$ on the second term: \\
$2\log_{2}(x - 4) = \log_{2}(x - 4)^{2}$ \\
Write the 1 on the right-hand side as a log, since $\log_{2} 2 = 1$: \\
$1 = \log_{2} 2$ \\
The equation becomes: \\
$\log_{2} x + \log_{2}(x - 4)^{2} = \log_{2} 2 + \log_{2}(3x - 2)$ \\
Use the product law $\log_{a} m + \log_{a} n = \log_{a} mn$ on each side: \\
$\log_{2}\left[ x(x - 4)^{2} \right] = \log_{2}\left[ 2(3x - 2) \right]$ \\
Both sides are logs to base 2, so the insides are equal: \\
$x(x - 4)^{2} = 2(3x - 2)$ \\
Expand $(x - 4)^{2} = x^{2} - 8x + 16$ \\
$x\left( x^{2} - 8x + 16 \right) = 2(3x - 2)$ \\
Expand both sides: \\
$x^{3} - 8x^{2} + 16x = 6x - 4$ \\
Subtract $6x$ from both sides and add 4 to both sides: \\
$x^{3} - 8x^{2} + 16x - 6x + 4 = 0$ \\
$x^{3} - 8x^{2} + 10x + 4 = 0$ as required \\
(b) $x = 2$ is a solution of the cubic, so $(x - 2)$ is a factor \\
Write $x^{3} - 8x^{2} + 10x + 4 = (x - 2)\left( x^{2} + px + q \right)$ \\
Expand the right-hand side: \\
$= x^{3} + px^{2} + qx - 2x^{2} - 2px - 2q$ \\
$= x^{3} + (p - 2)x^{2} + (q - 2p)x - 2q$ \\
Compare coefficients of $x^{2}$: \\
$p - 2 = -8$ \\
$p = -6$ \\
Compare the constant terms: \\
$-2q = 4$ \\
$q = -2$ \\
(Check the $x$ terms: $q - 2p = -2 + 12 = 10$, which matches) \\
$(x - 2)\left( x^{2} - 6x - 2 \right) = 0$ \\
$x = 2$ or $x^{2} - 6x - 2 = 0$ \\
Reject $x = 2$: it makes $\log_{2}(x - 4) = \log_{2}(-2)$, and the log of a negative number cannot be found \\
Solve $x^{2} - 6x - 2 = 0$ with the quadratic formula, $a = 1$, $b = -6$, $c = -2$: \\
$x = \frac{6 \pm \sqrt{(-6)^{2} - 4(1)(-2)}}{2}$ \\
$= \frac{6 \pm \sqrt{36 + 8}}{2}$ \\
$= \frac{6 \pm \sqrt{44}}{2}$ \\
Write 44 as $4 \times 11$: $\sqrt{44} = 2\sqrt{11}$ \\
$= \frac{6 \pm 2\sqrt{11}}{2}$ \\
Divide each term by 2: \\
$x = 3 \pm \sqrt{11}$ \\
The logs need $x > 0$ and $x - 4 > 0$, so $x > 4$ \\
$3 + \sqrt{11} = 6.317...$, which is bigger than 4, so it is valid \\
$3 - \sqrt{11} = -0.317...$, which is less than 4, so reject it \\
(Check: for $x = 3 + \sqrt{11}$, $3x - 2 = 7 + 3\sqrt{11}$ is positive, so every log can be found) \\
$x = 3 + \sqrt{11}$

@q 13
@topic Completing the square, region
@marks 7
@question
(a) Write the terms in order: $16x - 23 - 2x^{2} = -2x^{2} + 16x - 23$ \\
Take out the factor $-2$ from the first two terms: \\
$= -2\left( x^{2} - 8x \right) - 23$ \\
Complete the square: $x^{2} - 8x = (x - 4)^{2} - 16$ \\
$= -2\left[ (x - 4)^{2} - 16 \right] - 23$ \\
Expand the square bracket: \\
$= -2(x - 4)^{2} + 32 - 23$ \\
$= -2(x - 4)^{2} + 9$ \\
$16x - 23 - 2x^{2} = 9 - 2(x - 4)^{2}$ \\
So $a = 9$, $b = -2$ and $c = -4$ \\
(Check: at $x = 0$, $9 - 2(16) = -23$) \\
(b) $(x - 4)^{2}$ is never negative, so $-2(x - 4)^{2}$ is never positive \\
$y$ is biggest when $(x - 4)^{2} = 0$, that is $x = 4$ \\
$y = 9 - 2(0) = 9$ \\
$S$ is the point $(4, 9)$ \\
(c) $l_{1}$ is parallel to the $y$-axis and passes through $S(4, 9)$: \\
$l_{1}$ is the line $x = 4$ \\
Gradient of $l_{2}$ through $P(2, 1)$ and $Q(5, 7)$: \\
$m = \frac{7 - 1}{5 - 2}$ \\
$= \frac{6}{3}$ \\
$= 2$ \\
Use $y - y_{1} = m(x - x_{1})$ with the point $P(2, 1)$: \\
$y - 1 = 2(x - 2)$ \\
Expand the bracket: \\
$y - 1 = 2x - 4$ \\
Add 1 to both sides: \\
$y = 2x - 3$ \\
(Check with $Q$: $2(5) - 3 = 7$) \\
Now describe $R$ using its three boundaries: \\
$R$ is to the left of $l_{1}$ (or on it): \\
$x \leq 4$ \\
$R$ is above the line $l_{2}$ (or on it): \\
$y \geq 2x - 3$ \\
$R$ is below the curve $C$ (or on it): \\
$y \leq 16x - 23 - 2x^{2}$ \\
So $R$ is defined by: \\
$x \leq 4$, $y \geq 2x - 3$ and $y \leq 16x - 23 - 2x^{2}$

@q 14
@topic Trig identity, hence solve equation
@marks 8
@question
(a) Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$ on the top of the fraction: \\
$\cos \theta \tan \theta = \cos \theta \times \frac{\sin \theta}{\cos \theta}$ \\
The $\cos \theta$ cancels: \\
$= \sin \theta$ \\
The top becomes $5(1 + \sin \theta)$ \\
Use $\cos^{2} \theta = 1 - \sin^{2} \theta$ on the bottom: \\
$4 + 3\cos^{2} \theta = 4 + 3\left( 1 - \sin^{2} \theta \right)$ \\
Expand the bracket: \\
$= 4 + 3 - 3\sin^{2} \theta$ \\
$= 7 - 3\sin^{2} \theta$ \\
The equation is now: \\
$\frac{5(1 + \sin \theta)}{7 - 3\sin^{2} \theta} = 1$ \\
Multiply both sides by $7 - 3\sin^{2} \theta$: \\
$5(1 + \sin \theta) = 7 - 3\sin^{2} \theta$ \\
Expand the bracket: \\
$5 + 5\sin \theta = 7 - 3\sin^{2} \theta$ \\
Add $3\sin^{2} \theta$ to both sides and subtract 7 from both sides: \\
$3\sin^{2} \theta + 5\sin \theta + 5 - 7 = 0$ \\
$3\sin^{2} \theta + 5\sin \theta - 2 = 0$ \\
This is the required form with $a = 3$, $b = 5$ and $c = -2$ \\
(b) The equation has the same form as part (a), with $\theta = 2x$ \\
So it becomes: \\
$3\sin^{2} 2x + 5\sin 2x - 2 = 0$ \\
Let $s = \sin 2x$: \\
$3s^{2} + 5s - 2 = 0$ \\
Factorise: two numbers that multiply to $3 \times (-2) = -6$ and add to $5$ are $6$ and $-1$ \\
Split the middle term: \\
$3s^{2} + 6s - s - 2 = 0$ \\
Factorise in pairs: \\
$3s(s + 2) - 1(s + 2) = 0$ \\
$(3s - 1)(s + 2) = 0$ \\
$s = \frac{1}{3}$ or $s = -2$ \\
$\sin 2x = -2$ is impossible, because a sine is never less than $-1$ \\
So $\sin 2x = \frac{1}{3}$ \\
The range is $180 \leq x < 360$. Multiply by 2 to get the range for $2x$: \\
$360 \leq 2x < 720$ \\
Principal value: \\
$2x = \sin^{-1} \frac{1}{3} = 19.4712$ degrees \\
Sine is positive in the first and second quadrants, so the solutions are: \\
$2x = 19.4712 + 360n$ or $2x = 180 - 19.4712 + 360n$ \\
$2x = 19.4712 + 360n$ or $2x = 160.5288 + 360n$ \\
Choose $n$ so that $2x$ is between 360 and 720, so $n = 1$: \\
$2x = 19.4712 + 360 = 379.4712$ \\
$2x = 160.5288 + 360 = 520.5288$ \\
($n = 0$ gives values below 360 and $n = 2$ gives values above 720, so neither is in range) \\
Divide both by 2: \\
$x = \frac{379.4712}{2} = 189.7356$ \\
$x = \frac{520.5288}{2} = 260.2644$ \\
To one decimal place: \\
$x = 189.7$ degrees or $x = 260.3$ degrees \\
(Neither $2x$ value is 450 or 630, so $\tan 2x$ exists and the original equation is valid at both)
