@paper P1 Mock Set 3

@q 1
@topic Differentiation and tangent
@marks 5
@question
(a) $y = x^{3} - 7x^{2} + 5x + 4$ \\
Differentiate each term, using $x^{n} \to nx^{n-1}$: \\
$x^{3} \to 3x^{2}$ \\
$-7x^{2} \to -14x$ \\
$5x \to 5$ \\
$4 \to 0$ \\
$\frac{dy}{dx} = 3x^{2} - 14x + 5$ \\
(b) The gradient at $P$ is the value of $\frac{dy}{dx}$ where $x = 2$: \\
$\frac{dy}{dx} = 3(2)^{2} - 14(2) + 5$ \\
$= 3(4) - 28 + 5$ \\
$= 12 - 28 + 5$ \\
$= -11$ \\
Equation of the tangent through $P(2, -6)$ with gradient $-11$: \\
$y - y_{1} = m(x - x_{1})$ \\
$y - (-6) = -11(x - 2)$ \\
$y + 6 = -11(x - 2)$ \\
Expand the bracket: \\
$y + 6 = -11x + 22$ \\
Subtract 6 from both sides: \\
$y = -11x + 22 - 6$ \\
$y = -11x + 16$

@q 2
@topic Factor theorem and cubic
@marks 7
@question
(a) $f(x) = 3x^{3} - 7x^{2} + 7x - 10$ \\
$(x - 2)$ is a factor if $f(2) = 0$ \\
$f(2) = 3(2)^{3} - 7(2)^{2} + 7(2) - 10$ \\
$= 3(8) - 7(4) + 14 - 10$ \\
$= 24 - 28 + 14 - 10$ \\
$= 0$ \\
Since $f(2) = 0$, $(x - 2)$ is a factor of $f(x)$ \\
(b) Expand the right-hand side: \\
$(x - 2)(ax^{2} + bx + c) = ax^{3} + bx^{2} + cx - 2ax^{2} - 2bx - 2c$ \\
Collect like terms: \\
$= ax^{3} + (b - 2a)x^{2} + (c - 2b)x - 2c$ \\
Compare with $3x^{3} - 7x^{2} + 7x - 10$ \\
$x^{3}$: $a = 3$ \\
Constant: $-2c = -10$, so $c = 5$ \\
$x^{2}$: $b - 2a = -7$ \\
$b - 2(3) = -7$ \\
$b - 6 = -7$ \\
$b = -1$ \\
Check the $x$ terms: $c - 2b = 5 - 2(-1) = 7$ \\
$a = 3$, $b = -1$, $c = 5$ \\
$f(x) = (x - 2)(3x^{2} - x + 5)$ \\
(c) $f(x) = 0$ gives $(x - 2)(3x^{2} - x + 5) = 0$ \\
Either $x - 2 = 0$, giving $x = 2$, or $3x^{2} - x + 5 = 0$ \\
For $3x^{2} - x + 5 = 0$: $a = 3$, $b = -1$, $c = 5$ \\
Discriminant $= b^{2} - 4ac$ \\
$= (-1)^{2} - 4(3)(5)$ \\
$= 1 - 60$ \\
$= -59$ \\
The discriminant is negative, so $3x^{2} - x + 5 = 0$ has no real roots \\
So the only real root of $f(x) = 0$ is $x = 2$

@q 3
@topic Trapezium rule from a table
@marks 6
@question
(a) The $x$ values are 0.5, 0.6, 0.7, 0.8, 0.9, so the strip width is $h = 0.1$ \\
Trapezium rule: area $\approx \frac{h}{2}\{ y_{0} + y_{4} + 2(y_{1} + y_{2} + y_{3}) \}$ \\
$\int_{0.5}^{0.9} f(x) \, dx \approx \frac{0.1}{2}\{ 1.632 + 1.930 + 2(1.711 + 1.786 + 1.859) \}$ \\
First and last: $1.632 + 1.930 = 3.562$ \\
Middle three: $1.711 + 1.786 + 1.859 = 5.356$ \\
Double the middle three: $2 \times 5.356 = 10.712$ \\
$= 0.05 \times \{ 3.562 + 10.712 \}$ \\
$= 0.05 \times 14.274$ \\
$= 0.7137$ \\
$= 0.714$ (3 sf) \\
(b) Split the integral into two parts: \\
$\int_{0.5}^{0.9} (3f(x) + 2) \, dx = 3\int_{0.5}^{0.9} f(x) \, dx + \int_{0.5}^{0.9} 2 \, dx$ \\
The first part uses the estimate from (a): $3 \times 0.714 = 2.142$ \\
The second part: $\int_{0.5}^{0.9} 2 \, dx = [2x]_{0.5}^{0.9}$ \\
$= 2(0.9) - 2(0.5)$ \\
$= 1.8 - 1$ \\
$= 0.8$ \\
$\int_{0.5}^{0.9} (3f(x) + 2) \, dx \approx 2.142 + 0.8$ \\
$= 2.942$

@q 4
@topic Integral as limit of a sum
@marks 4
@question
(a) The limit of a sum of strips of width $\delta x$ is an integral, with the same limits: \\
$\lim_{\delta x \to 0} \sum_{x=4}^{12} (1 + 2x)^{\frac{1}{2}} \, \delta x = \int_{4}^{12} (1 + 2x)^{\frac{1}{2}} \, dx$ \\
(b) Integrate: add 1 to the power, then divide by the new power and by the derivative of $(1 + 2x)$, which is 2 \\
The new power is $\frac{3}{2}$ \\
$\int (1 + 2x)^{\frac{1}{2}} \, dx = \frac{(1 + 2x)^{\frac{3}{2}}}{\frac{3}{2} \times 2} + c$ \\
$= \frac{(1 + 2x)^{\frac{3}{2}}}{3} + c$ \\
$= \frac{1}{3}(1 + 2x)^{\frac{3}{2}} + c$ \\
Apply the limits: \\
$\int_{4}^{12} (1 + 2x)^{\frac{1}{2}} \, dx = \left[ \frac{1}{3}(1 + 2x)^{\frac{3}{2}} \right]_{4}^{12}$ \\
Upper limit $x = 12$: $1 + 2(12) = 25$, and $25^{\frac{3}{2}} = (\sqrt{25})^{3} = 5^{3} = 125$ \\
Lower limit $x = 4$: $1 + 2(4) = 9$, and $9^{\frac{3}{2}} = (\sqrt{9})^{3} = 3^{3} = 27$ \\
$= \frac{1}{3}(125) - \frac{1}{3}(27)$ \\
$= \frac{1}{3}(125 - 27)$ \\
$= \frac{98}{3}$ as required

@q 5
@topic Functions, composite, range, inverse, k
@marks 8
@question
(a)(i) $g(x) = 2 + 3x - x^{2}$ \\
$g(4) = 2 + 3(4) - 4^{2}$ \\
$= 2 + 12 - 16$ \\
$= -2$ \\
$fg(4) = f(-2)$ \\
$= \frac{k(-2)}{2(-2) - 1}$ \\
$= \frac{-2k}{-5}$ \\
$= \frac{2k}{5}$ \\
(ii) Split $f(x)$ using $kx = \frac{k}{2}(2x - 1) + \frac{k}{2}$: \\
$f(x) = \frac{\frac{k}{2}(2x - 1) + \frac{k}{2}}{2x - 1}$ \\
$= \frac{k}{2} + \frac{\frac{k}{2}}{2x - 1}$ \\
The fraction $\frac{\frac{k}{2}}{2x - 1}$ can take any value except 0 \\
So $f(x)$ can take any value except $\frac{k}{2}$ \\
Range of $f$: $f(x) \in \mathbb{R}$, $f(x) \ne \frac{k}{2}$ \\
(iii) Let $y = \frac{kx}{2x - 1}$ \\
Multiply both sides by $(2x - 1)$: \\
$y(2x - 1) = kx$ \\
Expand the bracket: \\
$2xy - y = kx$ \\
Get the $x$ terms on one side: \\
$2xy - kx = y$ \\
Factorise the left-hand side: \\
$x(2y - k) = y$ \\
Divide both sides by $(2y - k)$: \\
$x = \frac{y}{2y - k}$ \\
Replace $y$ by $x$: \\
$f^{-1}(x) = \frac{x}{2x - k}$, $x \in \mathbb{R}$, $x \ne \frac{k}{2}$ \\
(The domain of $f^{-1}$ is the range of $f$.) \\
(b) $g(2) = 2 + 3(2) - 2^{2}$ \\
$= 2 + 6 - 4$ \\
$= 4$ \\
$f^{-1}(2) = \frac{2}{2(2) - k} = \frac{2}{4 - k}$ \\
The condition $f^{-1}(2) = \frac{11}{3g(2)}$ becomes: \\
$\frac{2}{4 - k} = \frac{11}{3(4)}$ \\
$\frac{2}{4 - k} = \frac{11}{12}$ \\
Cross-multiply: \\
$2 \times 12 = 11(4 - k)$ \\
$24 = 44 - 11k$ \\
Add $11k$ to both sides: \\
$24 + 11k = 44$ \\
Subtract 24 from both sides: \\
$11k = 20$ \\
$k = \frac{20}{11}$

@q 6
@topic Binomial expansion, negative power
@marks 7
@question
(a) Take out a factor of 4 from inside the root: \\
$\frac{10}{\sqrt{4 - 3x}} = 10(4 - 3x)^{-\frac{1}{2}}$ \\
$= 10\left( 4\left( 1 - \frac{3}{4}x \right) \right)^{-\frac{1}{2}}$ \\
$= 10 \times 4^{-\frac{1}{2}} \times \left( 1 - \frac{3}{4}x \right)^{-\frac{1}{2}}$ \\
$4^{-\frac{1}{2}} = \frac{1}{\sqrt{4}} = \frac{1}{2}$ \\
$= 5\left( 1 - \frac{3}{4}x \right)^{-\frac{1}{2}}$ \\
So $A = 5$ \\
Binomial expansion: $(1 + X)^{n} = 1 + nX + \frac{n(n-1)}{2!}X^{2} + \frac{n(n-1)(n-2)}{3!}X^{3} + \ldots$ \\
Here $n = -\frac{1}{2}$ and $X = -\frac{3}{4}x$ \\
Term 2: $nX = \left( -\frac{1}{2} \right)\left( -\frac{3}{4}x \right) = \frac{3}{8}x$ \\
Term 3: $\frac{n(n-1)}{2!}X^{2} = \frac{\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right)}{2}\left( -\frac{3}{4}x \right)^{2}$ \\
$\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right) = \frac{3}{4}$ \\
$\frac{3}{4} \div 2 = \frac{3}{8}$ \\
$\left( -\frac{3}{4}x \right)^{2} = \frac{9}{16}x^{2}$ \\
Term 3 $= \frac{3}{8} \times \frac{9}{16}x^{2} = \frac{27}{128}x^{2}$ \\
Term 4: $\frac{n(n-1)(n-2)}{3!}X^{3} = \frac{\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right)\left( -\frac{5}{2} \right)}{6}\left( -\frac{3}{4}x \right)^{3}$ \\
$\left( -\frac{1}{2} \right)\left( -\frac{3}{2} \right)\left( -\frac{5}{2} \right) = -\frac{15}{8}$ \\
$-\frac{15}{8} \div 6 = -\frac{15}{48} = -\frac{5}{16}$ \\
$\left( -\frac{3}{4}x \right)^{3} = -\frac{27}{64}x^{3}$ \\
Term 4 $= \left( -\frac{5}{16} \right)\left( -\frac{27}{64} \right)x^{3} = \frac{135}{1024}x^{3}$ \\
$\left( 1 - \frac{3}{4}x \right)^{-\frac{1}{2}} = 1 + \frac{3}{8}x + \frac{27}{128}x^{2} + \frac{135}{1024}x^{3} + \ldots$ \\
Multiply every term by 5: \\
$f(x) = 5 + \frac{15}{8}x + \frac{135}{128}x^{2} + \frac{675}{1024}x^{3} + \ldots$ \\
So $A = 5$, $B = \frac{15}{8}$, $C = \frac{135}{128}$ \\
(b) The expansion of $(1 + X)^{n}$ is valid for $|X| < 1$ \\
$\left| -\frac{3}{4}x \right| < 1$ \\
$|x| < \frac{4}{3}$ \\
The largest value of $k$ is $\frac{4}{3}$ \\
(c) Substitute $x = \frac{1}{3}$ into $f(x)$: \\
$f\left( \frac{1}{3} \right) = \frac{10}{\sqrt{4 - 3\left( \frac{1}{3} \right)}} = \frac{10}{\sqrt{4 - 1}} = \frac{10}{\sqrt{3}}$ \\
Substitute $x = \frac{1}{3}$ into the expansion: \\
$5 + \frac{15}{8}\left( \frac{1}{3} \right) + \frac{135}{128}\left( \frac{1}{3} \right)^{2} + \frac{675}{1024}\left( \frac{1}{3} \right)^{3}$ \\
$= 5 + \frac{5}{8} + \frac{15}{128} + \frac{25}{1024}$ \\
Write each term over 1024: \\
$= \frac{5120}{1024} + \frac{640}{1024} + \frac{120}{1024} + \frac{25}{1024}$ \\
$= \frac{5905}{1024}$ \\
So $\frac{10}{\sqrt{3}} \approx \frac{5905}{1024}$ \\
Multiply both sides by $\sqrt{3}$: \\
$10 \approx \frac{5905}{1024}\sqrt{3}$ \\
Multiply both sides by $\frac{1024}{5905}$: \\
$\sqrt{3} \approx \frac{10 \times 1024}{5905}$ \\
$= \frac{10240}{5905}$ \\
Divide the top and the bottom by 5: \\
$\sqrt{3} \approx \frac{2048}{1181}$

@q 7
@topic Differentiation, root location, iteration
@marks 10
@question
(a) $y = (x^{2} - 5x + 8)e^{x^{2}}$ \\
Use the product rule with $u = x^{2} - 5x + 8$ and $v = e^{x^{2}}$ \\
$u' = 2x - 5$ \\
$v' = 2xe^{x^{2}}$ \\
$\frac{dy}{dx} = u'v + uv'$ \\
$= (2x - 5)e^{x^{2}} + (x^{2} - 5x + 8)(2x)e^{x^{2}}$ \\
Take out the common factor $e^{x^{2}}$: \\
$= e^{x^{2}}\left[ (2x - 5) + 2x(x^{2} - 5x + 8) \right]$ \\
Expand the second bracket: $2x(x^{2} - 5x + 8) = 2x^{3} - 10x^{2} + 16x$ \\
$= e^{x^{2}}\left[ 2x - 5 + 2x^{3} - 10x^{2} + 16x \right]$ \\
Collect like terms: \\
$= e^{x^{2}}\left[ 2x^{3} - 10x^{2} + 18x - 5 \right]$ \\
$\frac{dy}{dx} = (2x^{3} - 10x^{2} + 18x - 5)e^{x^{2}}$ as required \\
(b) $\frac{dy}{dx}$ is negative at $x = 0.3$ and positive at $x = 0.4$ \\
$\frac{dy}{dx}$ is continuous, so it changes sign by passing through zero somewhere between them \\
So the stationary point has $0.3 < \alpha < 0.4$ \\
(c) At a stationary point, $\frac{dy}{dx} = 0$: \\
$(2x^{3} - 10x^{2} + 18x - 5)e^{x^{2}} = 0$ \\
$e^{x^{2}}$ is never zero, so \\
$2x^{3} - 10x^{2} + 18x - 5 = 0$ \\
Move the $-10x^{2}$ and $-5$ to the right-hand side: \\
$2x^{3} + 18x = 10x^{2} + 5$ \\
Factorise each side: \\
$2x(x^{2} + 9) = 5(2x^{2} + 1)$ \\
Divide both sides by $2(x^{2} + 9)$: \\
$x = \frac{5(2x^{2} + 1)}{2(x^{2} + 9)}$ as required \\
(d)(i) $x_{1} = 0.3$ \\
$x_{2} = \frac{5(2(0.3)^{2} + 1)}{2((0.3)^{2} + 9)}$ \\
$= \frac{5(2(0.09) + 1)}{2(0.09 + 9)}$ \\
$= \frac{5(1.18)}{2(9.09)}$ \\
$= \frac{5.9}{18.18}$ \\
$= 0.32453\ldots$ \\
$x_{3} = \frac{5(2(0.32453\ldots)^{2} + 1)}{2((0.32453\ldots)^{2} + 9)}$ \\
$= 0.33240\ldots$ \\
$x_{3} = 0.3324$ (4 dp) \\
(d)(ii) Keep iterating (using the ANS key): \\
$x_{4} = 0.3350$, $x_{5} = 0.3360$, $x_{6} = 0.3363$, $x_{7} = 0.3364$, $x_{8} = 0.3364$ \\
The values settle at $0.3364$ \\
Check with a sign change of $h(x) = 2x^{3} - 10x^{2} + 18x - 5$: \\
$h(0.33635) = -0.0009$ (negative) \\
$h(0.33645) = 0.0003$ (positive) \\
So $\alpha$ is between $0.33635$ and $0.33645$ \\
$\alpha = 0.3364$ (4 dp)

@q 8
@topic Double angle identity, sec^2, equation
@marks 7
@question
(a) Numerator: use $\cos 2\theta = 1 - 2\sin^{2}\theta$ \\
$1 - \cos 2\theta = 1 - (1 - 2\sin^{2}\theta)$ \\
$= 1 - 1 + 2\sin^{2}\theta$ \\
$= 2\sin^{2}\theta$ \\
Denominator: use $\sin 2\theta = 2\sin \theta \cos \theta$ \\
$\sin^{2} 2\theta = (2\sin \theta \cos \theta)^{2}$ \\
$= 4\sin^{2}\theta \cos^{2}\theta$ \\
$\frac{1 - \cos 2\theta}{\sin^{2} 2\theta} = \frac{2\sin^{2}\theta}{4\sin^{2}\theta \cos^{2}\theta}$ \\
Cancel the common factor $2\sin^{2}\theta$ from the top and the bottom: \\
$= \frac{1}{2\cos^{2}\theta}$ \\
$= \frac{1}{2} \times \frac{1}{\cos^{2}\theta}$ \\
Use $\sec \theta = \frac{1}{\cos \theta}$: \\
$= \frac{1}{2}\sec^{2}\theta$ \\
So $k = \frac{1}{2}$ \\
(b) By part (a), the left-hand side is $\frac{1}{2}\sec^{2} x$: \\
$\frac{1}{2}\sec^{2} x = (1 + 2\tan x)^{2}$ \\
Expand the right-hand side: \\
$(1 + 2\tan x)^{2} = 1 + 4\tan x + 4\tan^{2} x$ \\
$\frac{1}{2}\sec^{2} x = 1 + 4\tan x + 4\tan^{2} x$ \\
Multiply both sides by 2: \\
$\sec^{2} x = 2 + 8\tan x + 8\tan^{2} x$ \\
Use $\sec^{2} x = 1 + \tan^{2} x$: \\
$1 + \tan^{2} x = 2 + 8\tan x + 8\tan^{2} x$ \\
Move everything to the right-hand side: \\
$0 = 2 - 1 + 8\tan x + 8\tan^{2} x - \tan^{2} x$ \\
$0 = 7\tan^{2} x + 8\tan x + 1$ \\
Factorise: \\
$(7\tan x + 1)(\tan x + 1) = 0$ \\
$\tan x = -\frac{1}{7}$ or $\tan x = -1$ \\
$\tan x = -1$: $x = -\frac{\pi}{4}$ \\
$\tan x = -\frac{1}{7}$: $x = \tan^{-1}\left( -\frac{1}{7} \right) = -0.142$ (3 sf) \\
Both are inside $-\frac{\pi}{2} < x < \frac{\pi}{2}$, and $\tan x$ takes each value only once in this range \\
$x = -\frac{\pi}{4}$ or $x = -0.142$

@q 9
@topic Exponential model - skydiver
@marks 6
@question
(a) $v = A + Be^{-0.5t}$ \\
At $t = 0$, $v = 56$: \\
$56 = A + Be^{0}$ \\
$56 = A + B$ \\
Equation 1: $A + B = 56$ \\
At $t = 5$, $v = 10$: \\
$10 = A + Be^{-0.5 \times 5}$ \\
Equation 2: $A + Be^{-2.5} = 10$ \\
Subtract equation 2 from equation 1: \\
$B - Be^{-2.5} = 56 - 10$ \\
Factorise the left-hand side: \\
$B(1 - e^{-2.5}) = 46$ \\
Divide both sides by $(1 - e^{-2.5})$: \\
$B = \frac{46}{1 - e^{-2.5}}$ \\
$e^{-2.5} = 0.08208$ \\
$B = \frac{46}{1 - 0.08208}$ \\
$= \frac{46}{0.91792}$ \\
$= 50.114$ \\
$B = 50.1$ (3 sf) \\
From equation 1: $A = 56 - B$ \\
$A = 56 - 50.114$ \\
$= 5.886$ \\
$A = 5.89$ (3 sf) \\
$v = 5.89 + 50.1e^{-0.5t}$ \\
(b) As $t$ gets large, $e^{-0.5t} \to 0$ \\
So $v \to 5.89$ \\
The model predicts that the skydiver's speed levels off at $5.89 \text{ m s}^{-1}$ \\
This is very close to the actual constant speed of $6 \text{ m s}^{-1}$ \\
So the model is appropriate

@q 10
@topic Modulus graph, inequality in terms of a
@marks 9
@question
(a) $y = |3x - 2a|$, where $a > 0$ \\
The vertex is where $3x - 2a = 0$: \\
$3x = 2a$ \\
$x = \frac{2a}{3}$ \\
At the vertex $y = 0$, so the graph touches the $x$-axis at $\left( \frac{2a}{3}, 0 \right)$ \\
$y$-intercept: put $x = 0$: \\
$y = |-2a| = 2a$ \\
The graph crosses the $y$-axis at $(0, 2a)$ \\
Sketch: a V shape with its vertex at $\left( \frac{2a}{3}, 0 \right)$, crossing the $y$-axis at $(0, 2a)$, with the gradient of each arm having size 3 \\
(b) $|3x - 2a| \le x + a$ \\
Find where the V meets the line $y = x + a$ \\
Right arm, $3x - 2a = x + a$: \\
Subtract $x$ from both sides: $2x - 2a = a$ \\
Add $2a$ to both sides: $2x = 3a$ \\
$x = \frac{3a}{2}$ \\
Left arm, $-(3x - 2a) = x + a$: \\
$-3x + 2a = x + a$ \\
Add $3x$ to both sides: $2a = 4x + a$ \\
Subtract $a$ from both sides: $a = 4x$ \\
$x = \frac{a}{4}$ \\
The V is below the line between these two points \\
Check: at the vertex $x = \frac{2a}{3}$, $|3x - 2a| = 0 \le \frac{2a}{3} + a$, which is true \\
Check: at $x = 0$, $|-2a| = 2a$, which is not $\le a$, so outside the interval it is false \\
$\frac{a}{4} \le x \le \frac{3a}{2}$ \\
(c) $g(x) = 5a - \left| \frac{1}{2}a - x \right|$ for $\frac{a}{4} \le x \le \frac{3a}{2}$ \\
$g(x)$ is largest when $\left| \frac{1}{2}a - x \right| = 0$, which is at $x = \frac{a}{2}$ \\
$\frac{a}{4} \le \frac{a}{2} \le \frac{3a}{2}$, so this value is in the range \\
Maximum: $g\left( \frac{a}{2} \right) = 5a - 0 = 5a$ \\
$g(x)$ is smallest where $x$ is furthest from $\frac{a}{2}$ \\
At $x = \frac{3a}{2}$: $\left| \frac{1}{2}a - \frac{3a}{2} \right| = |-a| = a$ \\
$g\left( \frac{3a}{2} \right) = 5a - a = 4a$ \\
At $x = \frac{a}{4}$: $\left| \frac{1}{2}a - \frac{a}{4} \right| = \frac{a}{4}$ \\
$g\left( \frac{a}{4} \right) = 5a - \frac{a}{4} = \frac{19a}{4}$, which is bigger than $4a$ \\
So the minimum is $4a$ \\
$4a \le g(x) \le 5a$

@q 11
@topic Exponential model - carbon dioxide
@marks 10
@question
(a)(i) $t$ is the number of years after 1960 \\
1980: $t = 20$ and $C = 339$: $339 = ab^{20}$ \\
2020: $t = 60$ and $C = 414$: $414 = ab^{60}$ \\
Divide the second equation by the first: \\
$\frac{414}{339} = \frac{ab^{60}}{ab^{20}}$ \\
$\frac{414}{339} = b^{40}$ \\
Take the 40th root of both sides: \\
$b = \left( \frac{414}{339} \right)^{\frac{1}{40}}$ \\
$= (1.2212)^{\frac{1}{40}}$ \\
$= 1.0050$ \\
$b = 1.005$ (3 dp) \\
(a)(ii) Use $339 = ab^{20}$ \\
$a = \frac{339}{b^{20}}$ \\
$= \frac{339}{1.005^{20}}$ \\
$= \frac{339}{1.1049}$ \\
$= 306.8$ \\
$a = 307$ (nearest integer) \\
(b)(i) When $t = 0$, $C = ab^{0} = a$ \\
So $a$ is the mean yearly concentration of carbon dioxide, in ppm, in 1960 \\
(b)(ii) Each year $C$ is multiplied by $b$ \\
So $b$ is the factor by which the concentration grows each year (an increase of 0.5 percent a year) \\
(c) Set $C = 450$: \\
$450 = 307 \times 1.005^{t}$ \\
Divide both sides by 307: \\
$1.005^{t} = \frac{450}{307}$ \\
Take natural logs of both sides: \\
$\ln(1.005^{t}) = \ln\left( \frac{450}{307} \right)$ \\
Use $\ln(x^{n}) = n\ln x$: \\
$t\ln 1.005 = \ln\left( \frac{450}{307} \right)$ \\
Divide both sides by $\ln 1.005$: \\
$t = \frac{\ln\left( \frac{450}{307} \right)}{\ln 1.005}$ \\
$= \frac{0.38236}{0.0049875}$ \\
$= 76.67$ \\
The mean yearly concentration is found each year, at whole numbers of $t$ \\
$t = 76$ (year 2036): $C = 307 \times 1.005^{76} = 448.5$, which is below 450 \\
$t = 77$ (year 2037): $C = 307 \times 1.005^{77} = 450.7$, which is above 450 \\
So the concentration is predicted to reach 450 ppm in the year 2037

@q 12
@topic Integration by parts, separable ODE
@marks 9
@question
(a) Use integration by parts on $\int x\sin kx \, dx$ \\
Let $u = x$ and $\frac{dv}{dx} = \sin kx$ \\
Then $\frac{du}{dx} = 1$ and $v = -\frac{1}{k}\cos kx$ \\
$\int x\sin kx \, dx = uv - \int v\frac{du}{dx} \, dx$ \\
$= x\left( -\frac{1}{k}\cos kx \right) - \int \left( -\frac{1}{k}\cos kx \right)(1) \, dx$ \\
$= -\frac{1}{k}x\cos kx + \frac{1}{k}\int \cos kx \, dx$ \\
$\int \cos kx \, dx = \frac{1}{k}\sin kx$ \\
$= -\frac{1}{k}x\cos kx + \frac{1}{k} \times \frac{1}{k}\sin kx + c$ \\
$= -\frac{1}{k}x\cos kx + \frac{1}{k^{2}}\sin kx + c$ \\
$= \frac{1}{k^{2}}\sin kx - \frac{1}{k}x\cos kx + c$ as required \\
(b) $\frac{dH}{dt} = \frac{t\sin\left( \frac{\pi t}{5} \right)}{10H}$ \\
Separate the variables: multiply both sides by $10H$ and by $dt$ \\
$10H \, dH = t\sin\left( \frac{\pi t}{5} \right) dt$ \\
Integrate both sides: \\
$\int 10H \, dH = \int t\sin\left( \frac{\pi t}{5} \right) dt$ \\
Left-hand side: $\int 10H \, dH = 5H^{2}$ \\
Right-hand side: use (a) with $k = \frac{\pi}{5}$ \\
$\frac{1}{k^{2}} = \frac{25}{\pi^{2}}$ and $\frac{1}{k} = \frac{5}{\pi}$ \\
$5H^{2} = \frac{25}{\pi^{2}}\sin\left( \frac{\pi t}{5} \right) - \frac{5}{\pi}t\cos\left( \frac{\pi t}{5} \right) + c$ \\
The passenger starts 5 m above ground, so $H = 5$ when $t = 0$: \\
$5(5)^{2} = \frac{25}{\pi^{2}}\sin 0 - \frac{5}{\pi}(0)\cos 0 + c$ \\
$125 = 0 - 0 + c$ \\
$c = 125$ \\
$5H^{2} = \frac{25}{\pi^{2}}\sin\left( \frac{\pi t}{5} \right) - \frac{5}{\pi}t\cos\left( \frac{\pi t}{5} \right) + 125$ \\
Substitute $t = 52$ (with the calculator in radians): \\
$\frac{\pi t}{5} = \frac{52\pi}{5} = 10.4\pi$ \\
$5H^{2} = \frac{25}{\pi^{2}}\sin(10.4\pi) - \frac{5}{\pi}(52)\cos(10.4\pi) + 125$ \\
$\sin(10.4\pi) = 0.95106$ and $\cos(10.4\pi) = 0.30902$ \\
$= 2.5330(0.95106) - 82.760(0.30902) + 125$ \\
$= 2.409 - 25.574 + 125$ \\
$= 101.835$ \\
Divide both sides by 5: \\
$H^{2} = 20.367$ \\
Take the positive square root: \\
$H = 4.51$ m

@q 13
@topic Implicit differentiation, 2nd derivative
@marks 5
@question
$y^{2} - x^{2} = 8$ \\
Differentiate both sides with respect to $x$: \\
$\frac{d}{dx}(y^{2}) = 2y\frac{dy}{dx}$ \\
$\frac{d}{dx}(x^{2}) = 2x$ \\
$2y\frac{dy}{dx} - 2x = 0$ \\
Add $2x$ to both sides: \\
$2y\frac{dy}{dx} = 2x$ \\
Divide both sides by $2y$: \\
$\frac{dy}{dx} = \frac{x}{y}$ \\
Differentiate again with the quotient rule, with $u = x$ and $v = y$: \\
$u' = 1$ and $v' = \frac{dy}{dx}$ \\
$\frac{d^{2}y}{dx^{2}} = \frac{u'v - uv'}{v^{2}}$ \\
$= \frac{y(1) - x\frac{dy}{dx}}{y^{2}}$ \\
Substitute $\frac{dy}{dx} = \frac{x}{y}$: \\
$= \frac{y - x\left( \frac{x}{y} \right)}{y^{2}}$ \\
$= \frac{y - \frac{x^{2}}{y}}{y^{2}}$ \\
Write the top as a single fraction: \\
$= \frac{\frac{y^{2}}{y} - \frac{x^{2}}{y}}{y^{2}}$ \\
$= \frac{\frac{y^{2} - x^{2}}{y}}{y^{2}}$ \\
Divide by $y^{2}$: \\
$= \frac{y^{2} - x^{2}}{y \times y^{2}}$ \\
$= \frac{y^{2} - x^{2}}{y^{3}}$ \\
From the original equation, $y^{2} - x^{2} = 8$: \\
$\frac{d^{2}y}{dx^{2}} = \frac{8}{y^{3}}$ as required

@q 14
@topic Proof by deduction and contradiction
@marks 7
@question
(i) Let the two consecutive odd integers be $2n - 1$ and $2n + 1$ \\
Sum of the squares: \\
$(2n - 1)^{2} + (2n + 1)^{2}$ \\
Expand $(2n - 1)^{2} = 4n^{2} - 4n + 1$ \\
Expand $(2n + 1)^{2} = 4n^{2} + 4n + 1$ \\
$= (4n^{2} - 4n + 1) + (4n^{2} + 4n + 1)$ \\
Collect like terms: \\
$= 8n^{2} + 0n + 2$ \\
$= 8n^{2} + 2$ \\
$8n^{2} = 8 \times n^{2}$, and $n^{2}$ is an integer, so $8n^{2}$ is a multiple of 8 \\
So the sum of the squares is always 2 more than a multiple of 8 \\
(ii) Assume the opposite: $\log_{2} 5$ is rational \\
$\log_{2} 5 = \frac{a}{b}$, where $a$ and $b$ are positive integers ($\log_{2} 5$ is positive) \\
Undo the logarithm (if $\log_{2} 5 = c$ then $5 = 2^{c}$): \\
$5 = 2^{\frac{a}{b}}$ \\
Raise both sides to the power $b$: \\
$5^{b} = \left( 2^{\frac{a}{b}} \right)^{b}$ \\
$5^{b} = 2^{a}$ \\
$5^{b}$ is a product of odd numbers, so it is odd \\
$2^{a}$ has a factor of 2 (as $a \ge 1$), so it is even \\
An odd number cannot equal an even number, which is a contradiction \\
So the assumption is false, and $\log_{2} 5$ is irrational
