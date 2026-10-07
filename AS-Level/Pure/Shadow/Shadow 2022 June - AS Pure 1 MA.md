@paper AS1 Shadow June 2022

@q 1
@topic Integrate with a root term
@marks 4
@question
Write the root term as a power of $x$: \\
$\frac{2}{3\sqrt{x}} = \frac{2}{3}x^{-\frac{1}{2}}$ \\
The integral is now: \\
$\int \left( 4x^{3} + \frac{2}{3}x^{-\frac{1}{2}} - 1 \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$ \\
$4x^{3} \to 4 \times \frac{x^{4}}{4} = x^{4}$ \\
$\frac{2}{3}x^{-\frac{1}{2}} \to \frac{2}{3} \times \frac{x^{\frac{1}{2}}}{\frac{1}{2}}$ \\
Dividing by $\frac{1}{2}$ is the same as multiplying by 2: \\
$= \frac{2}{3} \times 2x^{\frac{1}{2}}$ \\
$= \frac{4}{3}x^{\frac{1}{2}}$ \\
$-1 \to -x$ \\
Add the constant of integration $c$: \\
$\int \left( 4x^{3} + \frac{2}{3\sqrt{x}} - 1 \right) dx = x^{4} + \frac{4}{3}\sqrt{x} - x + c$

@q 2
@topic Factor theorem, one real root
@marks 7
@question
(a) By the factor theorem, $(x + 2)$ is a factor if $f(-2) = 0$ \\
$f(-2) = 3(-2)^{3} + 10(-2)^{2} + 13(-2) + 10$ \\
Evaluate the powers: $(-2)^{3} = -8$ and $(-2)^{2} = 4$ \\
$= 3(-8) + 10(4) - 26 + 10$ \\
$= -24 + 40 - 26 + 10$ \\
$= 16 - 26 + 10$ \\
$= 0$ \\
Since $f(-2) = 0$, $(x + 2)$ is a factor of $f(x)$ \\
(b) Expand the right-hand side of $f(x) = (x + 2)\left( ax^{2} + bx + c \right)$: \\
$(x + 2)\left( ax^{2} + bx + c \right) = ax^{3} + bx^{2} + cx + 2ax^{2} + 2bx + 2c$ \\
$= ax^{3} + (b + 2a)x^{2} + (c + 2b)x + 2c$ \\
Compare coefficients of $x^{3}$: \\
$a = 3$ \\
Compare coefficients of $x^{2}$: \\
$b + 2a = 10$ \\
$b + 6 = 10$ \\
$b = 4$ \\
Compare constant terms: \\
$2c = 10$ \\
$c = 5$ \\
Check the $x$ terms: $c + 2b = 5 + 8 = 13$, which matches \\
So $a = 3$, $b = 4$ and $c = 5$ \\
(c) $f(x) = (x + 2)\left( 3x^{2} + 4x + 5 \right)$ \\
$x + 2 = 0$ gives the root $x = -2$ \\
Look at the quadratic $3x^{2} + 4x + 5 = 0$. Its discriminant is $b^{2} - 4ac$: \\
$4^{2} - 4(3)(5)$ \\
$= 16 - 60$ \\
$= -44$ \\
The discriminant is negative, so the quadratic has no real roots \\
So the only real root of $f(x) = 0$ is $x = -2$ \\
(d) $f(x - 3) = 0$ when $x - 3$ is a root of $f$. The only real root of $f$ is $-2$: \\
$x - 3 = -2$ \\
Add 3 to both sides: \\
$x = 1$

@q 3
@topic Vectors in a triangle, ratio
@marks 6
@question
(a) Go from $Q$ to $P$ and then from $P$ to $R$: \\
$\text{QR} = \text{QP} + \text{PR}$ \\
$\text{QP} = -\text{PQ} = -2\mathbf{i} - 5\mathbf{j}$ \\
$\text{QR} = (-2\mathbf{i} - 5\mathbf{j}) + (10\mathbf{i} - 7\mathbf{j})$ \\
$\mathbf{i}$ part: $-2 + 10 = 8$ \\
$\mathbf{j}$ part: $-5 - 7 = -12$ \\
$\text{QR} = 8\mathbf{i} - 12\mathbf{j}$ \\
(b) The magnitude is $\sqrt{(\text{i part})^{2} + (\text{j part})^{2}}$: \\
$|\text{QR}| = \sqrt{8^{2} + (-12)^{2}}$ \\
$= \sqrt{64 + 144}$ \\
$= \sqrt{208}$ \\
Write 208 as $16 \times 13$: \\
$= \sqrt{16 \times 13}$ \\
$= \sqrt{16} \times \sqrt{13}$ \\
$= 4\sqrt{13}$ \\
(c) $QS : SR = 1 : 3$, so $QS$ is 1 part out of 4 parts of $QR$: \\
$\text{QS} = \frac{1}{4}\text{QR}$ \\
$= \frac{1}{4}(8\mathbf{i} - 12\mathbf{j})$ \\
$= 2\mathbf{i} - 3\mathbf{j}$ \\
Go from $P$ to $Q$ and then from $Q$ to $S$: \\
$\text{PS} = \text{PQ} + \text{QS}$ \\
$= (2\mathbf{i} + 5\mathbf{j}) + (2\mathbf{i} - 3\mathbf{j})$ \\
$\mathbf{i}$ part: $2 + 2 = 4$ \\
$\mathbf{j}$ part: $5 - 3 = 2$ \\
$\text{PS} = 4\mathbf{i} + 2\mathbf{j}$

@q 4
@topic Cosine rule leading to quadratic
@marks 6
@question
(a)(i) Use the cosine rule $a^{2} = b^{2} + c^{2} - 2bc\cos A$ with the 60 degree angle at $A$ and the opposite side $BC$: \\
$BC^{2} = AB^{2} + AC^{2} - 2(AB)(AC)\cos 60$ \\
$\cos 60$ degrees $= \frac{1}{2}$, so $2\cos 60 = 1$: \\
$(2x + 1)^{2} = (x + 2)^{2} + (3x - 3)^{2} - (x + 2)(3x - 3)$ \\
Expand each bracket one at a time: \\
$(2x + 1)^{2} = 4x^{2} + 4x + 1$ \\
$(x + 2)^{2} = x^{2} + 4x + 4$ \\
$(3x - 3)^{2} = 9x^{2} - 18x + 9$ \\
$(x + 2)(3x - 3) = 3x^{2} - 3x + 6x - 6 = 3x^{2} + 3x - 6$ \\
Substitute these back in: \\
$4x^{2} + 4x + 1 = x^{2} + 4x + 4 + 9x^{2} - 18x + 9 - \left( 3x^{2} + 3x - 6 \right)$ \\
Remove the bracket, changing every sign: \\
$4x^{2} + 4x + 1 = x^{2} + 4x + 4 + 9x^{2} - 18x + 9 - 3x^{2} - 3x + 6$ \\
Collect like terms on the right-hand side: \\
$x^{2}: 1 + 9 - 3 = 7$ \\
$x: 4 - 18 - 3 = -17$ \\
numbers: $4 + 9 + 6 = 19$ \\
$4x^{2} + 4x + 1 = 7x^{2} - 17x + 19$ \\
Subtract the left-hand side from both sides: \\
$0 = 7x^{2} - 4x^{2} - 17x - 4x + 19 - 1$ \\
$0 = 3x^{2} - 21x + 18$ \\
Divide every term by 3: \\
$0 = x^{2} - 7x + 6$ \\
$x^{2} - 7x + 6 = 0$, as required \\
(a)(ii) Factorise. Two numbers that multiply to 6 and add to $-7$ are $-1$ and $-6$: \\
$(x - 1)(x - 6) = 0$ \\
$x = 1$ or $x = 6$ \\
If $x = 1$ then $AC = 3(1) - 3 = 0$, which is impossible for a side of a triangle. Reject it \\
$x = 6$ \\
(b) With $x = 6$ the sides are: \\
$AB = 6 + 2 = 8$ cm \\
$BC = 2(6) + 1 = 13$ cm \\
$AC = 3(6) - 3 = 15$ cm \\
Angle $\theta$ is at $C$, opposite the side $AB = 8$. Use the cosine rule $\cos C = \frac{AC^{2} + BC^{2} - AB^{2}}{2(AC)(BC)}$: \\
$\cos \theta = \frac{15^{2} + 13^{2} - 8^{2}}{2(15)(13)}$ \\
$= \frac{225 + 169 - 64}{390}$ \\
$= \frac{330}{390}$ \\
$= \frac{11}{13}$ \\
$\theta = \cos^{-1}\left( \frac{11}{13} \right)$ \\
$\theta = 32.2$ degrees (1 dp)

@q 5
@topic Exponential growth of bacteria mass
@marks 10
@question
(a) Take logs to base 10 of both sides of $M = pq^{t}$: \\
$\log_{10} M = \log_{10} \left( pq^{t} \right)$ \\
Use the product law $\log (ab) = \log a + \log b$: \\
$\log_{10} M = \log_{10} p + \log_{10} q^{t}$ \\
Use the power law $\log a^{n} = n\log a$: \\
$\log_{10} M = \log_{10} p + t\log_{10} q$ \\
Write it in the form of the line, gradient first: \\
$\log_{10} M = (\log_{10} q)t + \log_{10} p$ \\
Compare with $\log_{10} M = 0.02t + 0.6$ \\
The intercept: $\log_{10} p = 0.6$ \\
$p = 10^{0.6}$ \\
$p = 3.98107...$ \\
$p = 3.981$ (4 sf) \\
The gradient: $\log_{10} q = 0.02$ \\
$q = 10^{0.02}$ \\
$q = 1.04713...$ \\
$q = 1.047$ (4 sf) \\
The complete equation is: \\
$M = 3.981 \times 1.047^{t}$ \\
(b)(i) $p$ is the value of $M$ when $t = 0$, so it is the mass of the colony when it was first recorded, 3.981 grams \\
(b)(ii) $q$ is the factor that the mass is multiplied by each day. Since $q = 1.047$, the mass goes up by about 4.7% each day \\
(c)(i) Put $t = 5$ into the linear relationship, to avoid using rounded values of $p$ and $q$: \\
$\log_{10} M = 0.02(5) + 0.6$ \\
$= 0.1 + 0.6$ \\
$= 0.7$ \\
Use the definition of a log: \\
$M = 10^{0.7}$ \\
$M = 5.0118...$ \\
The mass is 5 grams (nearest gram) \\
(c)(ii) Put $M = 7$: \\
$\log_{10} 7 = 0.02t + 0.6$ \\
$0.845098... = 0.02t + 0.6$ \\
Subtract 0.6 from both sides: \\
$0.245098... = 0.02t$ \\
Divide both sides by 0.02: \\
$t = 12.2549...$ \\
It takes about 12.3 days \\
(d) The model has the mass growing by the same percentage every day without limit. In the long term the colony would run out of food and space, so the mass could not keep growing like this

@q 6
@topic Binomial expansion times a fraction
@marks 6
@question
(a) Use the binomial expansion with first term 2, second term $-\frac{5x}{6}$ and $n = 7$: \\
$\left( 2 - \frac{5x}{6} \right)^{7} = 2^{7} + 7C1 \times 2^{6} \left( -\frac{5x}{6} \right) + 7C2 \times 2^{5} \left( -\frac{5x}{6} \right)^{2} + 7C3 \times 2^{4} \left( -\frac{5x}{6} \right)^{3} + ...$ \\
The coefficients are $7C1 = 7$, $7C2 = \frac{7 \times 6}{2} = 21$ and $7C3 = \frac{7 \times 6 \times 5}{6} = 35$ \\
First term: $2^{7} = 128$ \\
Second term: $7 \times 64 \times \left( -\frac{5x}{6} \right)$ \\
$= -\frac{2240x}{6}$ \\
$= -\frac{1120}{3}x$ \\
Third term: $21 \times 32 \times \frac{25x^{2}}{36}$ \\
$= \frac{16800x^{2}}{36}$ \\
$= \frac{1400}{3}x^{2}$ \\
Fourth term: $35 \times 16 \times \left( -\frac{125x^{3}}{216} \right)$ \\
$= -\frac{70000x^{3}}{216}$ \\
Divide top and bottom by 8: \\
$= -\frac{8750}{27}x^{3}$ \\
$\left( 2 - \frac{5x}{6} \right)^{7} = 128 - \frac{1120}{3}x + \frac{1400}{3}x^{2} - \frac{8750}{27}x^{3} + ...$ \\
(b) Split the fraction in front into two parts: \\
$\frac{x + 1}{3x} = \frac{x}{3x} + \frac{1}{3x}$ \\
$= \frac{1}{3} + \frac{1}{3x}$ \\
So $f(x) = \left( \frac{1}{3} + \frac{1}{3x} \right)\left( 128 - \frac{1120}{3}x + \frac{1400}{3}x^{2} - \frac{8750}{27}x^{3} + ... \right)$ \\
An $x^{2}$ term comes from two products: \\
$\frac{1}{3}$ times the $x^{2}$ term: $\frac{1}{3} \times \frac{1400}{3}x^{2} = \frac{1400}{9}x^{2}$ \\
$\frac{1}{3x}$ times the $x^{3}$ term: $\frac{1}{3x} \times \left( -\frac{8750}{27}x^{3} \right) = -\frac{8750}{81}x^{2}$ \\
Add them, writing $\frac{1400}{9}$ as $\frac{12600}{81}$: \\
coefficient $= \frac{12600}{81} - \frac{8750}{81}$ \\
$= \frac{3850}{81}$

@q 7
@topic Factorise cubic, sketch, 3 intersections
@marks 7
@question
(a) Take out the common factor $x$: \\
$4x - x^{3} = x\left( 4 - x^{2} \right)$ \\
$4 - x^{2}$ is a difference of two squares, $2^{2} - x^{2}$: \\
$= x(2 - x)(2 + x)$ \\
(b) $y = 0$ when $x(2 - x)(2 + x) = 0$: \\
$x = 0$ or $x = 2$ or $x = -2$ \\
The curve cuts the $x$-axis at $(-2, 0)$, $(0, 0)$ and $(2, 0)$ \\
The $x^{3}$ coefficient is negative, so the curve starts high on the left and ends low on the right \\
Test a value in each gap: \\
$x = -3$: $y = 4(-3) - (-27) = -12 + 27 = 15$, above the axis \\
$x = -1$: $y = 4(-1) - (-1) = -4 + 1 = -3$, below the axis \\
$x = 1$: $y = 4(1) - 1 = 3$, above the axis \\
$x = 3$: $y = 4(3) - 27 = -15$, below the axis \\
Sketch: the curve comes down from the top left, crosses at $(-2, 0)$, dips to a minimum below the axis, rises through $(0, 0)$, reaches a maximum above the axis, then falls through $(2, 0)$ to the bottom right \\
(c) The line $y = k$ is horizontal. It meets the curve at 3 distinct points when $k$ is between the $y$ value of the minimum and the $y$ value of the maximum \\
Find the turning points: \\
$\frac{dy}{dx} = 4 - 3x^{2}$ \\
Set $\frac{dy}{dx} = 0$: \\
$3x^{2} = 4$ \\
$x^{2} = \frac{4}{3}$ \\
$x = \pm \frac{2}{\sqrt{3}}$ \\
Substitute $x = \frac{2}{\sqrt{3}}$ into $y = 4x - x^{3}$: \\
$y = \frac{8}{\sqrt{3}} - \frac{8}{3\sqrt{3}}$ \\
Write over a common denominator: \\
$= \frac{24}{3\sqrt{3}} - \frac{8}{3\sqrt{3}}$ \\
$= \frac{16}{3\sqrt{3}}$ \\
Rationalise the denominator, multiplying top and bottom by $\sqrt{3}$: \\
$= \frac{16\sqrt{3}}{9}$ \\
The curve is odd ($y(-x) = -y(x)$), so at $x = -\frac{2}{\sqrt{3}}$ the $y$ value is $-\frac{16\sqrt{3}}{9}$ \\
The maximum is $\frac{16\sqrt{3}}{9}$ and the minimum is $-\frac{16\sqrt{3}}{9}$, which is about $\pm 3.08$ \\
$\left\{ k : -\frac{16\sqrt{3}}{9} < k < \frac{16\sqrt{3}}{9} \right\}$

@q 8
@topic Exponential decay of pool volume
@marks 6
@question
(a) The initial volume is when $t = 0$ and $V = 2000$: \\
$2000 = k + 1900e^{0}$ \\
$e^{0} = 1$, so: \\
$2000 = k + 1900$ \\
Subtract 1900 from both sides: \\
$k = 100$ \\
(b) Put $V = 500$ into $V = 100 + 1900e^{-0.1t}$: \\
$500 = 100 + 1900e^{-0.1t}$ \\
Subtract 100 from both sides: \\
$400 = 1900e^{-0.1t}$ \\
Divide both sides by 1900: \\
$e^{-0.1t} = \frac{400}{1900}$ \\
$e^{-0.1t} = \frac{4}{19}$ \\
Take natural logs of both sides: \\
$-0.1t = \ln \left( \frac{4}{19} \right)$ \\
Divide both sides by $-0.1$: \\
$t = -10\ln \left( \frac{4}{19} \right)$ \\
Use $-\ln \left( \frac{4}{19} \right) = \ln \left( \frac{19}{4} \right)$: \\
$t = 10\ln \left( \frac{19}{4} \right)$ \\
$= 10 \times 1.558145...$ \\
$= 15.58145...$ \\
The time taken is 15.6 minutes (1 dp) \\
(c) The rate of change of the volume is $\frac{dV}{dt}$. The derivative of $e^{-0.1t}$ is $-0.1e^{-0.1t}$: \\
$\frac{dV}{dt} = 1900 \times (-0.1)e^{-0.1t}$ \\
$\frac{dV}{dt} = -190e^{-0.1t}$ \\
At $t = 20$: \\
$\frac{dV}{dt} = -190e^{-2}$ \\
$= -190 \times 0.135335...$ \\
$= -25.7137...$ \\
The volume is decreasing at 25.7 litres per minute (3 sf)

@q 9
@topic Logs in terms of p, solve equation
@marks 6
@question
(a)(i) Use the subtraction law $\log \frac{a}{b} = \log a - \log b$: \\
$\log_{5} \left( \frac{x}{25} \right) = \log_{5} x - \log_{5} 25$ \\
$\log_{5} x = p$ and $\log_{5} 25 = 2$, because $5^{2} = 25$: \\
$= p - 2$ \\
(a)(ii) Write the cube root as a power, $\sqrt[3]{x} = x^{\frac{1}{3}}$: \\
$\log_{5} \left( \sqrt[3]{x} \right) = \log_{5} x^{\frac{1}{3}}$ \\
Use the power law $\log a^{n} = n\log a$: \\
$= \frac{1}{3}\log_{5} x$ \\
$= \frac{p}{3}$ \\
(b) Replace each log with its form in terms of $p$: \\
$5(p - 2) + 3\left( \frac{p}{3} \right) = -28$ \\
Expand the first bracket and cancel the 3s in the second term: \\
$5p - 10 + p = -28$ \\
Collect the $p$ terms: \\
$6p - 10 = -28$ \\
Add 10 to both sides: \\
$6p = -18$ \\
Divide both sides by 6: \\
$p = -3$ \\
Replace $p$ with $\log_{5} x$: \\
$\log_{5} x = -3$ \\
Use the definition of a log, $\log_{a} b = c \Rightarrow b = a^{c}$: \\
$x = 5^{-3}$ \\
A negative power is a reciprocal: \\
$x = \frac{1}{5^{3}}$ \\
$x = \frac{1}{125}$ \\
(Check: $5\log_{5} \left( \frac{1}{125 \times 25} \right) + 3\log_{5} \left( \frac{1}{5} \right) = 5(-5) + 3(-1) = -25 - 3 = -28$)

@q 10
@topic Tangent to a curve, area with line
@marks 10
@question
(a) Find the $y$ coordinate of $P$ by putting $x = 4$: \\
$y = \frac{1}{4}(4)^{2} - \sqrt{4} + 1$ \\
$= 4 - 2 + 1$ \\
$= 3$ \\
$P = (4, 3)$ \\
Write $\sqrt{x}$ as a power and differentiate, using $\frac{d}{dx}(x^{n}) = nx^{n-1}$: \\
$y = \frac{1}{4}x^{2} - x^{\frac{1}{2}} + 1$ \\
$\frac{dy}{dx} = \frac{1}{2}x - \frac{1}{2}x^{-\frac{1}{2}}$ \\
$\frac{dy}{dx} = \frac{x}{2} - \frac{1}{2\sqrt{x}}$ \\
At $x = 4$: \\
$\frac{dy}{dx} = \frac{4}{2} - \frac{1}{2\sqrt{4}}$ \\
$= 2 - \frac{1}{4}$ \\
$= \frac{7}{4}$ \\
Use $y - y_{1} = m(x - x_{1})$ with $m = \frac{7}{4}$ and $P(4, 3)$: \\
$y - 3 = \frac{7}{4}(x - 4)$ \\
Multiply both sides by 4: \\
$4y - 12 = 7(x - 4)$ \\
Expand the bracket: \\
$4y - 12 = 7x - 28$ \\
Subtract $4y$ from both sides: \\
$-12 = 7x - 28 - 4y$ \\
Add 12 to both sides: \\
$0 = 7x - 4y - 28 + 12$ \\
$0 = 7x - 4y - 16$ \\
$7x - 4y - 16 = 0$, as required \\
(b) Find where $l$ meets the $x$-axis by putting $y = 0$ in $7x - 4y - 16 = 0$: \\
$7x - 16 = 0$ \\
$x = \frac{16}{7}$ \\
Split $R$ into two pieces. Piece 1 is the whole area under the curve from $x = 0$ to $x = 4$. Then take away the triangle between the line $l$, the $x$-axis and $x = 4$, because that part is under the curve but is not in $R$ \\
Piece 1: $\int_{0}^{4} \left( \frac{1}{4}x^{2} - x^{\frac{1}{2}} + 1 \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$: \\
$\frac{1}{4}x^{2} \to \frac{1}{4} \times \frac{x^{3}}{3} = \frac{x^{3}}{12}$ \\
$-x^{\frac{1}{2}} \to -\frac{x^{\frac{3}{2}}}{\frac{3}{2}} = -\frac{2}{3}x^{\frac{3}{2}}$ \\
$1 \to x$ \\
$= \left[ \frac{x^{3}}{12} - \frac{2}{3}x^{\frac{3}{2}} + x \right]_{0}^{4}$ \\
Upper limit $x = 4$. $4^{\frac{3}{2}} = \left( \sqrt{4} \right)^{3} = 8$: \\
$\frac{64}{12} - \frac{2}{3}(8) + 4$ \\
$= \frac{16}{3} - \frac{16}{3} + 4$ \\
$= 4$ \\
Lower limit $x = 0$ gives 0 \\
Piece 1 $= 4$ \\
The triangle has vertices $\left( \frac{16}{7}, 0 \right)$, $(4, 0)$ and $(4, 3)$ \\
Base $= 4 - \frac{16}{7}$ \\
$= \frac{28}{7} - \frac{16}{7}$ \\
$= \frac{12}{7}$ \\
Height $= 3$ \\
Triangle area $= \frac{1}{2} \times \frac{12}{7} \times 3$ \\
$= \frac{18}{7}$ \\
Area of $R = 4 - \frac{18}{7}$ \\
$= \frac{28}{7} - \frac{18}{7}$ \\
$= \frac{10}{7}$

@q 11
@topic Circle and line, shortest distance
@marks 8
@question
(a) Complete the square on the $x$ terms and the $y$ terms. Half of $-6$ is $-3$ and half of $-8$ is $-4$: \\
$x^{2} - 6x = (x - 3)^{2} - 9$ \\
$y^{2} - 8y = (y - 4)^{2} - 16$ \\
Substitute into the equation of the circle: \\
$(x - 3)^{2} - 9 + (y - 4)^{2} - 16 + 21 = 0$ \\
$(x - 3)^{2} + (y - 4)^{2} - 4 = 0$ \\
Add 4 to both sides: \\
$(x - 3)^{2} + (y - 4)^{2} = 4$ \\
Compare with $(x - a)^{2} + (y - b)^{2} = r^{2}$: \\
(a)(i) The centre is $(3, 4)$ \\
(a)(ii) $r^{2} = 4$, so the radius is $r = 2$ \\
(b) The shortest distance from the circle to the line is along the perpendicular from the centre to $l$, minus the radius \\
Find the gradient of $l$. Make $y$ the subject of $3y + 2x + 6 = 0$: \\
$3y = -2x - 6$ \\
$y = -\frac{2}{3}x - 2$ \\
The gradient of $l$ is $-\frac{2}{3}$, so the perpendicular has gradient $\frac{3}{2}$ \\
The perpendicular through the centre $(3, 4)$: \\
$y - 4 = \frac{3}{2}(x - 3)$ \\
$y - 4 = \frac{3}{2}x - \frac{9}{2}$ \\
$y = \frac{3}{2}x - \frac{1}{2}$ \\
Find where this meets $l$. Substitute $y = \frac{3}{2}x - \frac{1}{2}$ into $3y + 2x + 6 = 0$: \\
$3\left( \frac{3}{2}x - \frac{1}{2} \right) + 2x + 6 = 0$ \\
$\frac{9}{2}x - \frac{3}{2} + 2x + 6 = 0$ \\
Collect the $x$ terms and the numbers: \\
$\frac{13}{2}x + \frac{9}{2} = 0$ \\
Multiply both sides by 2: \\
$13x + 9 = 0$ \\
$x = -\frac{9}{13}$ \\
Find $y$ from $y = \frac{3}{2}x - \frac{1}{2}$: \\
$y = \frac{3}{2} \times \left( -\frac{9}{13} \right) - \frac{1}{2}$ \\
$= -\frac{27}{26} - \frac{13}{26}$ \\
$= -\frac{40}{26}$ \\
$= -\frac{20}{13}$ \\
The foot of the perpendicular is $F\left( -\frac{9}{13}, -\frac{20}{13} \right)$ \\
The distance from the centre $(3, 4)$ to $F$: \\
$3 - \left( -\frac{9}{13} \right) = \frac{39}{13} + \frac{9}{13} = \frac{48}{13}$ \\
$4 - \left( -\frac{20}{13} \right) = \frac{52}{13} + \frac{20}{13} = \frac{72}{13}$ \\
$\text{distance} = \sqrt{\left( \frac{48}{13} \right)^{2} + \left( \frac{72}{13} \right)^{2}}$ \\
Write $\frac{48}{13} = \frac{24}{13} \times 2$ and $\frac{72}{13} = \frac{24}{13} \times 3$, then take $\left( \frac{24}{13} \right)^{2}$ out of the root, so $\frac{24}{13}$ comes outside: \\
$= \frac{24}{13}\sqrt{2^{2} + 3^{2}}$ \\
$= \frac{24}{13}\sqrt{13}$ \\
$= \frac{24}{\sqrt{13}}$ \\
Rationalise, multiplying top and bottom by $\sqrt{13}$: \\
$= \frac{24\sqrt{13}}{13}$ \\
$= 6.6564...$ \\
The shortest distance between the circle and the line is this distance minus the radius 2: \\
$\frac{24\sqrt{13}}{13} - 2 = 4.656...$ \\
The shortest distance is $\frac{24\sqrt{13}}{13} - 2$, which is 4.66 (3 sf)

@q 12
@topic Minimise cost of a cylinder
@marks 12
@question
(a) The capacity (volume) of the cylinder is $\pi r^{2}h = 7800$. Make $h$ the subject: \\
$h = \frac{7800}{\pi r^{2}}$ \\
The area of the base is $\pi r^{2}$ and the area of the curved side is $2\pi rh$. These cost 0.05 pence per cm$^{2}$: \\
$\text{cost of base and side} = 0.05\left( \pi r^{2} + 2\pi rh \right)$ \\
$= 0.05\pi r^{2} + 0.1\pi rh$ \\
The area of the top is $\pi r^{2}$ and it costs 0.08 pence per cm$^{2}$: \\
$\text{cost of top} = 0.08\pi r^{2}$ \\
Add the two costs: \\
$C = 0.05\pi r^{2} + 0.1\pi rh + 0.08\pi r^{2}$ \\
$C = 0.13\pi r^{2} + 0.1\pi rh$ \\
Substitute $h = \frac{7800}{\pi r^{2}}$: \\
$0.1\pi rh = 0.1\pi r \times \frac{7800}{\pi r^{2}}$ \\
Cancel $\pi$ and one $r$: \\
$= \frac{0.1 \times 7800}{r}$ \\
$= \frac{780}{r}$ \\
$C = 0.13\pi r^{2} + \frac{780}{r}$, as required \\
(b) Write the second term as a power: \\
$C = 0.13\pi r^{2} + 780r^{-1}$ \\
Differentiate, using $\frac{d}{dr}(r^{n}) = nr^{n-1}$: \\
$\frac{dC}{dr} = 0.26\pi r - 780r^{-2}$ \\
$\frac{dC}{dr} = 0.26\pi r - \frac{780}{r^{2}}$ \\
At a minimum, $\frac{dC}{dr} = 0$: \\
$0.26\pi r - \frac{780}{r^{2}} = 0$ \\
Add $\frac{780}{r^{2}}$ to both sides: \\
$0.26\pi r = \frac{780}{r^{2}}$ \\
Multiply both sides by $r^{2}$: \\
$0.26\pi r^{3} = 780$ \\
Divide both sides by $0.26\pi$: \\
$r^{3} = \frac{780}{0.26\pi}$ \\
$r^{3} = \frac{3000}{\pi}$ \\
$r^{3} = 954.93...$ \\
Take the cube root: \\
$r = 9.8474...$ \\
$r = 9.85$ cm (3 sf) \\
(c) Differentiate $\frac{dC}{dr} = 0.26\pi r - 780r^{-2}$ again: \\
$\frac{d^{2}C}{dr^{2}} = 0.26\pi + 1560r^{-3}$ \\
$\frac{d^{2}C}{dr^{2}} = 0.26\pi + \frac{1560}{r^{3}}$ \\
$r$ is positive, so both terms are positive and: \\
$\frac{d^{2}C}{dr^{2}} > 0$ \\
A positive second derivative at a stationary point means a minimum, so the cost is minimised at this value of $r$ \\
(d) Substitute the unrounded $r = 9.8474...$ into $C = 0.13\pi r^{2} + \frac{780}{r}$: \\
$0.13\pi r^{2} = 0.13\pi \times 96.972...$ \\
$= 39.604...$ \\
$\frac{780}{r} = \frac{780}{9.8474...}$ \\
$= 79.208...$ \\
$C = 39.604 + 79.208$ \\
$= 118.812$ \\
The minimum cost is 119 pence (nearest integer)

@q 13
@topic Trig identity then equation
@marks 8
@question
(a) Work with the left-hand side. Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$, so $\frac{1}{\tan \theta} = \frac{\cos \theta}{\sin \theta}$: \\
$\frac{1}{\sin \theta} + \frac{1}{\tan \theta} = \frac{1}{\sin \theta} + \frac{\cos \theta}{\sin \theta}$ \\
The denominators are the same, so add the tops: \\
$= \frac{1 + \cos \theta}{\sin \theta}$ \\
Multiply the top and the bottom by $(1 - \cos \theta)$ (not zero, as $\theta \neq 180n$ degrees): \\
$= \frac{(1 + \cos \theta)(1 - \cos \theta)}{\sin \theta (1 - \cos \theta)}$ \\
The top is a difference of two squares: \\
$(1 + \cos \theta)(1 - \cos \theta) = 1 - \cos^{2} \theta$ \\
Use $\sin^{2} \theta + \cos^{2} \theta = 1$, so $1 - \cos^{2} \theta = \sin^{2} \theta$: \\
$= \frac{\sin^{2} \theta}{\sin \theta (1 - \cos \theta)}$ \\
Cancel one factor of $\sin \theta$ (not zero): \\
$= \frac{\sin \theta}{1 - \cos \theta}$, as required \\
(b) Use the result of part (a) with $\theta = 2x$ on the left-hand side: \\
$\frac{\sin 2x}{1 - \cos 2x} = 4\sin 2x$ \\
Divide both sides by $\sin 2x$ (not zero, as given): \\
$\frac{1}{1 - \cos 2x} = 4$ \\
Multiply both sides by $(1 - \cos 2x)$: \\
$1 = 4(1 - \cos 2x)$ \\
Divide both sides by 4: \\
$\frac{1}{4} = 1 - \cos 2x$ \\
Add $\cos 2x$ to both sides and subtract $\frac{1}{4}$ from both sides: \\
$\cos 2x = 1 - \frac{1}{4}$ \\
$\cos 2x = \frac{3}{4}$ \\
The range $0 \leq x \leq 180$ degrees means $0 \leq 2x \leq 360$ degrees \\
$2x = \cos^{-1}(0.75) = 41.4096...$ degrees \\
The other solution in this range is $360 - 41.4096... = 318.5903...$ degrees \\
Divide both by 2: \\
$x = 20.7048...$ or $x = 159.2951...$ \\
$x = 20.7$ degrees or $x = 159.3$ degrees (1 dp) \\
(Check $x = 20.7048$: $2x = 41.4096$, $\frac{1}{\sin 2x} + \frac{1}{\tan 2x} = 1.5119 + 1.1339 = 2.6458$ and $4\sin 2x = 2.6458$)

@q 14
@topic Disprove a statement, prove divisibility
@marks 4
@question
(i) The statement is false. Use a counter example with a negative number. Take $x = 1$ and $y = -1$ \\
$x > y$, since $1 > -1$ \\
$\frac{x}{y} = \frac{1}{-1} = -1$ \\
$-1$ is not greater than 1, so the statement is not true \\
(ii) Take out the common factor $n$: \\
$n^{3} - 3n^{2} + 2n = n\left( n^{2} - 3n + 2 \right)$ \\
Factorise the quadratic. Two numbers that multiply to 2 and add to $-3$ are $-1$ and $-2$: \\
$= n(n - 1)(n - 2)$ \\
This is the product of three consecutive integers, $(n - 2)$, $(n - 1)$ and $n$ \\
Divisible by 2: of any two consecutive integers one is even. If $n$ is even then $n$ is a multiple of 2. If $n$ is odd then $n - 1$ is even. So the product always has a factor of 2 \\
Divisible by 3: there are three cases for $n$. If $n = 3k$ then $n$ is a multiple of 3. If $n = 3k + 1$ then $n - 1 = 3k$ is a multiple of 3. If $n = 3k + 2$ then $n - 2 = 3k$ is a multiple of 3. So the product always has a factor of 3 \\
The product has a factor of 2 and a factor of 3, and $2 \times 3 = 6$. As 2 and 3 share no common factor, a number divisible by both is divisible by 6 \\
So $n^{3} - 3n^{2} + 2n$ is divisible by 6 for all positive integers $n$
