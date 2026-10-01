@paper P1 June 2026

@q 1
@topic Transformations, mapping a point
@marks 4
@question
$P(-4, 5)$ is on $y = f(x)$, so $f(-4) = 5$ \\
(a) $y = 4f(2x)$ \\
The input to $f$ must be $-4$, so put $2x = -4$: \\
$x = -2$ \\
Then $y = 4f(2 \times (-2))$ \\
$= 4f(-4)$ \\
$= 4 \times 5$ \\
$= 20$ \\
$P$ maps to $(-2, 20)$ \\
(b) $y = f(x + 3) - 2$ \\
The input to $f$ must be $-4$, so put $x + 3 = -4$: \\
$x = -7$ \\
Then $y = f(-7 + 3) - 2$ \\
$= f(-4) - 2$ \\
$= 5 - 2$ \\
$= 3$ \\
$P$ maps to $(-7, 3)$

@q 2
@topic Root in interval, iteration
@marks 5
@question
(a) $f(x) = e^{2x - 1} + 3x - 7$ \\
$f(1.1) = e^{2(1.1) - 1} + 3(1.1) - 7$ \\
$= e^{1.2} + 3.3 - 7$ \\
$= 3.3201 + 3.3 - 7$ \\
$= -0.380$ (negative) \\
$f(1.2) = e^{2(1.2) - 1} + 3(1.2) - 7$ \\
$= e^{1.4} + 3.6 - 7$ \\
$= 4.0552 + 3.6 - 7$ \\
$= 0.655$ (positive) \\
$f$ is continuous and changes sign, so $\alpha$ lies in $[1.1, 1.2]$ \\
(b)(i) $x_{n+1} = \frac{1 + \ln(7 - 3x_{n})}{2}$ and $x_{1} = 1.1$ \\
$x_{2} = \frac{1 + \ln(7 - 3(1.1))}{2}$ \\
$= \frac{1 + \ln(7 - 3.3)}{2}$ \\
$= \frac{1 + \ln 3.7}{2}$ \\
$= \frac{1 + 1.3083}{2}$ \\
$= 1.1542$ (4 dp) \\
(ii) Keep iterating (using the ANS key so that rounding errors do not build up): \\
$x_{3} = 1.1317$, $x_{4} = 1.1411$, $x_{5} = 1.1372$, $x_{6} = 1.1389$ \\
$x_{7} = 1.1382$, $x_{8} = 1.1385$, $x_{9} = 1.1383$, $x_{10} = 1.1384$, $x_{11} = 1.1384$ \\
The values settle at $1.1384$ \\
Check with a sign change of $f$: \\
$f(1.13835) = -0.0002$ (negative) \\
$f(1.13845) = 0.0009$ (positive) \\
So $\alpha$ is between $1.13835$ and $1.13845$, and every number in this interval rounds to $1.1384$ \\
$\alpha = 1.1384$ (4 dp)

@q 3
@topic Differentiation, tangent to a cubic
@marks 5
@question
(a) $y = x^{3} - 2x^{2} + 5x - 7$ \\
Differentiate each term using $x^{n} \to nx^{n-1}$: \\
$x^{3} \to 3x^{2}$ \\
$-2x^{2} \to -4x$ \\
$5x \to 5$ \\
$-7 \to 0$ \\
$\frac{dy}{dx} = 3x^{2} - 4x + 5$ \\
(b) At $x = 2$: \\
$y = 2^{3} - 2(2)^{2} + 5(2) - 7$ \\
$= 8 - 8 + 10 - 7$ \\
$= 3$ \\
The point is $(2, 3)$ \\
The gradient at $x = 2$: \\
$\frac{dy}{dx} = 3(2)^{2} - 4(2) + 5$ \\
$= 12 - 8 + 5$ \\
$= 9$ \\
Tangent through $(2, 3)$ with gradient 9: \\
$y - 3 = 9(x - 2)$ \\
Expand the bracket: \\
$y - 3 = 9x - 18$ \\
Add 3 to both sides: \\
$y = 9x - 15$

@q 4
@topic Functions, range, composite, inverse
@marks 5
@question
(a) $f(x) = 3x^{2} - 2$ \\
$x^{2} \ge 0$ for all real $x$ \\
Multiply by 3: $3x^{2} \ge 0$ \\
Subtract 2: $3x^{2} - 2 \ge -2$ \\
The minimum is $-2$ (at $x = 0$) and $f$ increases without limit \\
Range of $f$: $f(x) \ge -2$ \\
(b) $gf(2) = g(f(2))$ \\
$f(2) = 3(2)^{2} - 2 = 3(4) - 2 = 12 - 2 = 10$ \\
$g(10) = \frac{5(10) - 1}{10 - 4}$ \\
$= \frac{50 - 1}{6}$ \\
$= \frac{49}{6}$ \\
(c) Let $y = \frac{5x - 1}{x - 4}$ \\
Multiply both sides by $(x - 4)$: \\
$y(x - 4) = 5x - 1$ \\
Expand the bracket: \\
$xy - 4y = 5x - 1$ \\
Get the $x$ terms on one side: \\
$xy - 5x = 4y - 1$ \\
Factorise the left-hand side: \\
$x(y - 5) = 4y - 1$ \\
Divide both sides by $(y - 5)$: \\
$x = \frac{4y - 1}{y - 5}$ \\
Replace $y$ by $x$: \\
$g^{-1}(x) = \frac{4x - 1}{x - 5}$, $x \in \mathbb{R}$, $x \ne 5$

@q 5
@topic Parametric model, helicopter flight
@marks 5
@question
(a) $y = 10\sin\left( \frac{t^{2}}{4} \right)$ \\
The greatest value of $\sin$ is 1: \\
$y_{max} = 10 \times 1$ \\
$= 10$ m \\
(b) Set $y = 5$: \\
$10\sin\left( \frac{t^{2}}{4} \right) = 5$ \\
Divide both sides by 10: \\
$\sin\left( \frac{t^{2}}{4} \right) = \frac{1}{2}$ \\
As $t$ increases from 0, $\frac{t^{2}}{4}$ increases from 0, so the solutions come in order \\
The first time is $\frac{t^{2}}{4} = \frac{\pi}{6}$ \\
The second time is $\frac{t^{2}}{4} = \pi - \frac{\pi}{6} = \frac{5\pi}{6}$ \\
The helicopter has not landed by then, as it lands when $\frac{t^{2}}{4} = \pi$ \\
Multiply both sides by 4: \\
$t^{2} = \frac{20\pi}{6} = \frac{10\pi}{3}$ \\
Take the square root: \\
$t = \sqrt{\frac{10\pi}{3}}$ \\
$= 3.2360$ seconds \\
Horizontal distance: $x = 100\sqrt{t}$ \\
$= 100\sqrt{3.2360}$ \\
$= 100 \times 1.7989$ \\
$= 179.9$ m \\
The helicopter has travelled about 180 m (3 sf)

@q 6
@topic Integrating 3/(7x+1), ln, find p
@marks 5
@question
(a) $\int \frac{3}{7x + 1} \, dx$ \\
Use $\int \frac{1}{ax + b} \, dx = \frac{1}{a}\ln|ax + b|$, with $a = 7$: \\
$\int \frac{1}{7x + 1} \, dx = \frac{1}{7}\ln|7x + 1|$ \\
Multiply by 3: \\
$\int \frac{3}{7x + 1} \, dx = \frac{3}{7}\ln|7x + 1| + c$ \\
(b) $\int_{2}^{p} \frac{3}{7x + 1} \, dx = \left[ \frac{3}{7}\ln(7x + 1) \right]_{2}^{p}$ \\
Upper limit $x = p$: $\frac{3}{7}\ln(7p + 1)$ \\
Lower limit $x = 2$: $\frac{3}{7}\ln(7 \times 2 + 1) = \frac{3}{7}\ln 15$ \\
$= \frac{3}{7}\ln(7p + 1) - \frac{3}{7}\ln 15$ \\
Factorise: \\
$= \frac{3}{7}\left( \ln(7p + 1) - \ln 15 \right)$ \\
Set equal to $\frac{6}{7}$: \\
$\frac{3}{7}\left( \ln(7p + 1) - \ln 15 \right) = \frac{6}{7}$ \\
Multiply both sides by $\frac{7}{3}$: \\
$\ln(7p + 1) - \ln 15 = 2$ \\
Use $\ln a - \ln b = \ln\frac{a}{b}$: \\
$\ln\left( \frac{7p + 1}{15} \right) = 2$ \\
Raise $e$ to the power of both sides: \\
$\frac{7p + 1}{15} = e^{2}$ \\
Multiply both sides by 15: \\
$7p + 1 = 15e^{2}$ \\
Subtract 1 from both sides: \\
$7p = 15e^{2} - 1$ \\
Divide both sides by 7: \\
$p = \frac{15e^{2} - 1}{7}$

@q 7
@topic Sectors, segments, Newton-Raphson
@marks 7
@question
(a) $R_{1}$ is the segment between chord $BC$ and arc $BC$, with angle $\theta$ at the centre \\
Area of segment = area of sector $-$ area of triangle \\
Sector: $\frac{1}{2}r^{2}\theta$ \\
Triangle: $\frac{1}{2}r^{2}\sin \theta$ \\
$R_{1} = \frac{1}{2}r^{2}\theta - \frac{1}{2}r^{2}\sin \theta$ \\
$= \frac{1}{2}r^{2}(\theta - \sin \theta)$ \\
$COA$ is a straight line (the diameter), so angle $AOB = \pi - \theta$ \\
$R_{2}$ is the segment with angle $\pi - \theta$: \\
$R_{2} = \frac{1}{2}r^{2}\left( (\pi - \theta) - \sin(\pi - \theta) \right)$ \\
Use $\sin(\pi - \theta) = \sin \theta$: \\
$R_{2} = \frac{1}{2}r^{2}(\pi - \theta - \sin \theta)$ \\
Given $R_{1} = 2R_{2}$: \\
$\frac{1}{2}r^{2}(\theta - \sin \theta) = 2 \times \frac{1}{2}r^{2}(\pi - \theta - \sin \theta)$ \\
Divide both sides by $\frac{1}{2}r^{2}$: \\
$\theta - \sin \theta = 2(\pi - \theta - \sin \theta)$ \\
Expand the bracket: \\
$\theta - \sin \theta = 2\pi - 2\theta - 2\sin \theta$ \\
Add $2\theta$ and $2\sin \theta$ to both sides, and subtract $2\pi$ from both sides: \\
$\theta + 2\theta - \sin \theta + 2\sin \theta - 2\pi = 0$ \\
$3\theta + \sin \theta - 2\pi = 0$ \\
$\sin \theta + 3\theta - 2\pi = 0$ \\
So $p = 1$ and $q = 3$ \\
(b) $f(\theta) = \sin \theta + 3\theta - 2\pi$ \\
$f'(\theta) = \cos \theta + 3$ \\
Newton-Raphson: $\theta_{2} = \theta_{1} - \frac{f(\theta_{1})}{f'(\theta_{1})}$, with $\theta_{1} = 1.3$ \\
$f(1.3) = \sin 1.3 + 3(1.3) - 2\pi$ \\
$= 0.96356 + 3.9 - 6.28319$ \\
$= -1.41963$ \\
$f'(1.3) = \cos 1.3 + 3$ \\
$= 0.26750 + 3$ \\
$= 3.26750$ \\
$\theta_{2} = 1.3 - \frac{-1.41963}{3.26750}$ \\
$= 1.3 + 0.43447$ \\
$= 1.73447$ \\
$\theta_{2} = 1.734$ (3 dp)

@q 8
@topic Limit of a sum, integration by parts
@marks 5
@question
(a) The limit of a sum of strips of width $\delta x$ is an integral with the same limits: \\
$\lim_{\delta x \to 0} \sum_{x=0}^{3} xe^{2x} \, \delta x = \int_{0}^{3} xe^{2x} \, dx$ \\
(b) Integrate by parts: let $u = x$ and $\frac{dv}{dx} = e^{2x}$ \\
$\frac{du}{dx} = 1$ and $v = \frac{1}{2}e^{2x}$ \\
$\int xe^{2x} \, dx = uv - \int v\frac{du}{dx} \, dx$ \\
$= x \times \frac{1}{2}e^{2x} - \int \frac{1}{2}e^{2x} \times 1 \, dx$ \\
$= \frac{x}{2}e^{2x} - \frac{1}{2} \times \frac{1}{2}e^{2x}$ \\
$= \frac{x}{2}e^{2x} - \frac{1}{4}e^{2x}$ \\
Apply the limits: \\
$\left[ \frac{x}{2}e^{2x} - \frac{1}{4}e^{2x} \right]_{0}^{3}$ \\
Upper limit $x = 3$: $\frac{3}{2}e^{6} - \frac{1}{4}e^{6} = \frac{6}{4}e^{6} - \frac{1}{4}e^{6} = \frac{5}{4}e^{6}$ \\
Lower limit $x = 0$: $0 - \frac{1}{4}e^{0} = -\frac{1}{4}$ \\
Subtract: \\
$\int_{0}^{3} xe^{2x} \, dx = \frac{5}{4}e^{6} - \left( -\frac{1}{4} \right)$ \\
$= \frac{5}{4}e^{6} + \frac{1}{4}$ \\
So $A = \frac{5}{4}$ and $B = \frac{1}{4}$

@q 9
@topic Trig identity, cot 2x, equation
@marks 8
@question
(a) Write $\cosec \theta$ and $\sec \theta$ in terms of $\sin$ and $\cos$: \\
$\cosec \theta - \sec \theta = \frac{1}{\sin \theta} - \frac{1}{\cos \theta}$ \\
Use the common denominator $\sin \theta \cos \theta$: \\
$= \frac{\cos \theta}{\sin \theta \cos \theta} - \frac{\sin \theta}{\sin \theta \cos \theta}$ \\
$= \frac{\cos \theta - \sin \theta}{\sin \theta \cos \theta}$ \\
$(\cos \theta + \sin \theta)(\cosec \theta - \sec \theta) = \frac{(\cos \theta + \sin \theta)(\cos \theta - \sin \theta)}{\sin \theta \cos \theta}$ \\
Expand the numerator (difference of two squares): \\
$= \frac{\cos^{2} \theta - \sin^{2} \theta}{\sin \theta \cos \theta}$ \\
Use $\cos^{2} \theta - \sin^{2} \theta = \cos 2\theta$ and $\sin \theta \cos \theta = \frac{1}{2}\sin 2\theta$: \\
$= \frac{\cos 2\theta}{\frac{1}{2}\sin 2\theta}$ \\
$= 2 \times \frac{\cos 2\theta}{\sin 2\theta}$ \\
$= 2\cot 2\theta$ \\
So $k = 2$ \\
(b) By part (a): $(\cos x + \sin x)(\cosec x - \sec x) = 2\cot 2x$ \\
$5(\cos x + \sin x)(\cosec x - \sec x) = 5 \times 2\cot 2x = 10\cot 2x$ \\
$10\cot 2x = 4\cosec^{2} 2x$ \\
Use $\cosec^{2} 2x = 1 + \cot^{2} 2x$: \\
$10\cot 2x = 4(1 + \cot^{2} 2x)$ \\
Expand the bracket: \\
$10\cot 2x = 4 + 4\cot^{2} 2x$ \\
Rearrange to one side: \\
$0 = 4\cot^{2} 2x - 10\cot 2x + 4$ \\
Divide every term by 2: \\
$2\cot^{2} 2x - 5\cot 2x + 2 = 0$ \\
Factorise: \\
$(2\cot 2x - 1)(\cot 2x - 2) = 0$ \\
$\cot 2x = \frac{1}{2}$ or $\cot 2x = 2$ \\
Take reciprocals: $\tan 2x = 2$ or $\tan 2x = \frac{1}{2}$ \\
$-90 < x < 90$ gives $-180 < 2x < 180$ \\
$\tan 2x = 2$: $2x = \tan^{-1} 2 = 63.43$ degrees, or $63.43 - 180 = -116.57$ degrees \\
$x = 31.7$ degrees or $x = -58.3$ degrees \\
$\tan 2x = \frac{1}{2}$: $2x = \tan^{-1}\frac{1}{2} = 26.57$ degrees, or $26.57 - 180 = -153.43$ degrees \\
$x = 13.3$ degrees or $x = -76.7$ degrees \\
$x = -76.7$, $-58.3$, $13.3$, $31.7$ degrees (1 dp)

@q 10
@topic Normal to a curve, area enclosed
@marks 11
@question
(a) $y = \frac{7x}{\sqrt{3x^{2} + 4}}$ \\
Write it as a product: $y = 7x(3x^{2} + 4)^{-\frac{1}{2}}$ \\
Product rule with $u = 7x$ and $v = (3x^{2} + 4)^{-\frac{1}{2}}$ \\
$u' = 7$ \\
Chain rule: $v' = -\frac{1}{2}(3x^{2} + 4)^{-\frac{3}{2}} \times 6x = -3x(3x^{2} + 4)^{-\frac{3}{2}}$ \\
$\frac{dy}{dx} = u'v + uv'$ \\
$= 7(3x^{2} + 4)^{-\frac{1}{2}} + 7x \times \left( -3x(3x^{2} + 4)^{-\frac{3}{2}} \right)$ \\
$= 7(3x^{2} + 4)^{-\frac{1}{2}} - 21x^{2}(3x^{2} + 4)^{-\frac{3}{2}}$ \\
Take out the common factor $(3x^{2} + 4)^{-\frac{3}{2}}$: \\
$= (3x^{2} + 4)^{-\frac{3}{2}}\left( 7(3x^{2} + 4) - 21x^{2} \right)$ \\
Expand the bracket: $7(3x^{2} + 4) - 21x^{2} = 21x^{2} + 28 - 21x^{2} = 28$ \\
$\frac{dy}{dx} = \frac{28}{(3x^{2} + 4)^{\frac{3}{2}}}$ \\
At $x = 2$: $3x^{2} + 4 = 12 + 4 = 16$ \\
$y = \frac{7(2)}{\sqrt{16}} = \frac{14}{4} = \frac{7}{2}$ \\
$\frac{dy}{dx} = \frac{28}{16^{\frac{3}{2}}} = \frac{28}{64} = \frac{7}{16}$ \\
The normal is perpendicular to the tangent, so its gradient is $-1 \div \frac{7}{16} = -\frac{16}{7}$ \\
Equation of $l$ through $P\left( 2, \frac{7}{2} \right)$: \\
$y - \frac{7}{2} = -\frac{16}{7}(x - 2)$ \\
Multiply every term by 14: \\
$14y - 49 = -32(x - 2)$ \\
Expand the bracket: \\
$14y - 49 = -32x + 64$ \\
Move everything to the left-hand side: \\
$32x + 14y - 49 - 64 = 0$ \\
$32x + 14y - 113 = 0$ \\
(b) $Q$ is on the $y$-axis, so put $x = 0$: \\
$14y - 113 = 0$ \\
$14y = 113$ \\
$y = \frac{113}{14}$ \\
(c) Area of $R$ = area under the line $l$ $-$ area under the curve $C$, from $x = 0$ to $x = 2$ \\
Area under $l$: a trapezium with parallel sides $\frac{113}{14}$ (at $x = 0$) and $\frac{7}{2} = \frac{49}{14}$ (at $x = 2$), and width 2 \\
$= \frac{1}{2}(2)\left( \frac{113}{14} + \frac{49}{14} \right)$ \\
$= \frac{162}{14}$ \\
$= \frac{81}{7}$ \\
Area under $C$: $\int_{0}^{2} \frac{7x}{\sqrt{3x^{2} + 4}} \, dx$ \\
Let $u = 3x^{2} + 4$, so $du = 6x \, dx$ and $7x \, dx = \frac{7}{6} \, du$ \\
Limits: $x = 0$ gives $u = 4$, and $x = 2$ gives $u = 16$ \\
$= \int_{4}^{16} \frac{7}{6}u^{-\frac{1}{2}} \, du$ \\
$= \frac{7}{6}\left[ 2u^{\frac{1}{2}} \right]_{4}^{16}$ \\
$= \frac{7}{3}\left[ \sqrt{u} \right]_{4}^{16}$ \\
$= \frac{7}{3}(\sqrt{16} - \sqrt{4})$ \\
$= \frac{7}{3}(4 - 2)$ \\
$= \frac{14}{3}$ \\
Area of $R = \frac{81}{7} - \frac{14}{3}$ \\
Write both fractions over 21: \\
$= \frac{243}{21} - \frac{98}{21}$ \\
$= \frac{145}{21}$

@q 11
@topic R cos form, electricity demand
@marks 11
@question
(a) Let $4\cos x - 13\sin x = R\cos(x + \alpha)$ \\
Expand the right-hand side using $\cos(A + B) = \cos A \cos B - \sin A \sin B$: \\
$R\cos(x + \alpha) = R\cos x \cos \alpha - R\sin x \sin \alpha$ \\
Compare the coefficients of $\cos x$: $R\cos \alpha = 4$ \\
Compare the coefficients of $\sin x$: $R\sin \alpha = 13$ \\
Square and add: \\
$R^{2}\cos^{2}\alpha + R^{2}\sin^{2}\alpha = 4^{2} + 13^{2}$ \\
$R^{2} = 16 + 169 = 185$ \\
$R = \sqrt{185}$ \\
Divide $R\sin \alpha = 13$ by $R\cos \alpha = 4$: \\
$\tan \alpha = \frac{13}{4}$ \\
$\alpha = \tan^{-1}\left( \frac{13}{4} \right) = 1.272$ radians (3 dp) \\
$4\cos x - 13\sin x = \sqrt{185}\cos(x + 1.272)$ \\
(b)(i) Use (a) with $x = \frac{\pi t}{12} + 0.2$: \\
$D = 30 + \sqrt{185}\cos\left( \frac{\pi t}{12} + 0.2 + 1.2723 \right)$ \\
$D = 30 + \sqrt{185}\cos\left( \frac{\pi t}{12} + 1.4723 \right)$ \\
The smallest value of $\cos$ is $-1$: \\
$D_{min} = 30 - \sqrt{185}$ \\
$= 30 - 13.601$ \\
$= 16.4$ GW (3 sf) \\
(ii) The minimum happens when $\cos\left( \frac{\pi t}{12} + 1.4723 \right) = -1$ \\
$\frac{\pi t}{12} + 1.4723 = \pi$ \\
$0 < t < 24$ makes the angle run from $1.47$ to $7.76$, so $\pi$ is the only value where $\cos = -1$ in range \\
Subtract 1.4723 from both sides: \\
$\frac{\pi t}{12} = \pi - 1.4723 = 1.6693$ \\
Multiply both sides by $\frac{12}{\pi}$: \\
$t = \frac{12 \times 1.6693}{\pi}$ \\
$= 6.376$ \\
$0.376 \times 60 = 22.6$ minutes \\
The minimum demand happens at about 6:23 am \\
(c) Differentiate $D = 30 + \sqrt{185}\cos\left( \frac{\pi t}{12} + 1.4723 \right)$: \\
$\frac{dD}{dt} = -\sqrt{185} \times \frac{\pi}{12}\sin\left( \frac{\pi t}{12} + 1.4723 \right)$ \\
$= -\frac{\pi\sqrt{185}}{12}\sin\left( \frac{\pi t}{12} + 1.4723 \right)$ \\
3 pm is $t = 15$: \\
$\frac{15\pi}{12} + 1.4723 = 3.9270 + 1.4723 = 5.3993$ \\
$\sin(5.3993) = -0.7732$ \\
$\frac{\pi\sqrt{185}}{12} = 3.5609$ \\
$\frac{dD}{dt} = -3.5609 \times (-0.7732)$ \\
$= 2.753$ \\
$k = 2.75$ (3 sf) \\
(d) Electricity demand changes through the year (for example more heating and lighting is used in winter than in summer, and weekends differ from weekdays) \\
So one equation cannot fit every day of the year

@q 12
@topic Modulus graph meets k/x, range of k
@marks 7
@question
(a) $y = |px - q|$, where $p > 0$ and $q > 0$ \\
The vertex is where $px - q = 0$: \\
$x = \frac{q}{p}$ \\
The graph touches the $x$-axis at $\left( \frac{q}{p}, 0 \right)$ \\
$y$-intercept: put $x = 0$: $y = |-q| = q$ \\
The graph crosses the $y$-axis at $(0, q)$ \\
Sketch: a V shape above the $x$-axis, with its vertex at $\left( \frac{q}{p}, 0 \right)$, passing through $(0, q)$, where the left branch has gradient $-p$ and the right branch has gradient $p$ \\
(b) $C$ is $y = \frac{k}{x}$, with $k > 0$ \\
For $x < 0$: $\frac{k}{x} < 0$, but $|px - q| \ge 0$, so there are no intersections \\
For $x > \frac{q}{p}$: the V is $y = px - q$, which increases from 0 without limit, while $y = \frac{k}{x}$ is positive and decreasing \\
So there is exactly 1 intersection for $x > \frac{q}{p}$ \\
So for 3 intersections in total, there must be 2 distinct intersections for $0 < x < \frac{q}{p}$, where $|px - q| = q - px$ \\
$\frac{k}{x} = q - px$ \\
Multiply both sides by $x$: \\
$k = qx - px^{2}$ \\
Rearrange: \\
$px^{2} - qx + k = 0$ \\
Two distinct real roots means the discriminant is positive: \\
$(-q)^{2} - 4(p)(k) > 0$ \\
$q^{2} - 4pk > 0$ \\
$q^{2} > 4pk$ \\
$k < \frac{q^{2}}{4p}$ \\
Check that both roots are in $0 < x < \frac{q}{p}$: the sum of the roots is $\frac{q}{p}$ and the product is $\frac{k}{p}$, which is positive, so both roots are positive \\
Each root also has $q - px = \frac{k}{x} > 0$, so $x < \frac{q}{p}$ \\
As $k$ is positive: \\
$0 < k < \frac{q^{2}}{4p}$

@q 13
@topic Geometric sequence with trig terms
@marks 7
@question
(a) The 3rd, 4th and 5th terms are $\sin \theta$, $\sqrt{2}\cos \theta$ and $\sqrt{3}\cot \theta$ \\
In a geometric sequence, the ratio of consecutive terms is constant: \\
$\frac{u_{4}}{u_{3}} = \frac{u_{5}}{u_{4}}$ \\
$\frac{\sqrt{2}\cos \theta}{\sin \theta} = \frac{\sqrt{3}\cot \theta}{\sqrt{2}\cos \theta}$ \\
Write $\cot \theta = \frac{\cos \theta}{\sin \theta}$: \\
$\frac{\sqrt{2}\cos \theta}{\sin \theta} = \frac{\sqrt{3}\cos \theta}{\sqrt{2}\cos \theta\sin \theta}$ \\
Cancel $\cos \theta$ on the right-hand side: \\
$\frac{\sqrt{2}\cos \theta}{\sin \theta} = \frac{\sqrt{3}}{\sqrt{2}\sin \theta}$ \\
Multiply both sides by $\sin \theta$: \\
$\sqrt{2}\cos \theta = \frac{\sqrt{3}}{\sqrt{2}}$ \\
Multiply both sides by $\sqrt{2}$: \\
$2\cos \theta = \sqrt{3}$ \\
$\cos \theta = \frac{\sqrt{3}}{2}$ \\
$0 < \theta < \frac{\pi}{2}$, so $\theta = \frac{\pi}{6}$ \\
Common ratio $r = \frac{u_{4}}{u_{3}} = \frac{\sqrt{2}\cos \theta}{\sin \theta}$ \\
$= \frac{\sqrt{2} \times \frac{\sqrt{3}}{2}}{\frac{1}{2}}$ \\
$= \sqrt{2} \times \sqrt{3}$ \\
$= \sqrt{6}$ \\
Check with the next term: $u_{5} = \sqrt{3}\cot\frac{\pi}{6} = \sqrt{3} \times \sqrt{3} = 3$, and $\frac{u_{5}}{u_{4}} = \frac{3}{\frac{\sqrt{6}}{2}} = \frac{6}{\sqrt{6}} = \sqrt{6}$ \\
(b) $u_{3} = ar^{2} = \sin\frac{\pi}{6} = \frac{1}{2}$ \\
$r^{2} = 6$ \\
$6a = \frac{1}{2}$ \\
$a = \frac{1}{12}$ \\
$S_{3} = a + ar + ar^{2}$ \\
$= a(1 + r + r^{2})$ \\
$= \frac{1}{12}\left( 1 + \sqrt{6} + 6 \right)$ \\
$= \frac{1}{12}\left( 7 + \sqrt{6} \right)$ \\
$= \frac{7 + \sqrt{6}}{12}$

@q 14
@topic Separable DE, chemical in a lake
@marks 11
@question
(a) $\frac{dx}{dt} = x(A - t)$ \\
Separate the variables: \\
$\frac{1}{x} \, dx = (A - t) \, dt$ \\
Integrate both sides: \\
$\int \frac{1}{x} \, dx = \int (A - t) \, dt$ \\
$\ln x = At - \frac{t^{2}}{2} + c$ \\
Initially $t = 0$ and $x = 0.3$: \\
$\ln 0.3 = 0 - 0 + c$ \\
$c = \ln 0.3$ \\
$\ln x = At - \frac{t^{2}}{2} + \ln 0.3$ \\
Subtract $\ln 0.3$ from both sides: \\
$\ln x - \ln 0.3 = At - \frac{t^{2}}{2}$ \\
$\ln\left( \frac{x}{0.3} \right) = At - \frac{t^{2}}{2}$ \\
Raise $e$ to the power of both sides: \\
$\frac{x}{0.3} = e^{At - \frac{t^{2}}{2}}$ \\
$x = 0.3e^{At - \frac{t^{2}}{2}}$ \\
When $t = 4$, $x = 21$: \\
$21 = 0.3e^{4A - 8}$ \\
Divide both sides by 0.3: \\
$e^{4A - 8} = 70$ \\
Take natural logs: \\
$4A - 8 = \ln 70$ \\
$4A = 8 + \ln 70$ \\
$A = 2 + \frac{1}{4}\ln 70$ \\
$x = 0.3e^{\left( 2 + \frac{1}{4}\ln 70 \right)t - \frac{t^{2}}{2}}$ \\
(b) The concentration is greatest when $\frac{dx}{dt} = 0$ \\
$x(A - t) = 0$ \\
$x > 0$, so $A - t = 0$, giving $t = A$ \\
For $t < A$, $\frac{dx}{dt} > 0$, and for $t > A$, $\frac{dx}{dt} < 0$, so this is a maximum \\
$A = 2 + \frac{1}{4}\ln 70 = 2 + 1.0621 = 3.0621$ \\
Substitute $t = A$: \\
$x_{max} = 0.3e^{A \times A - \frac{A^{2}}{2}}$ \\
$= 0.3e^{\frac{A^{2}}{2}}$ \\
$\frac{A^{2}}{2} = \frac{9.3766}{2} = 4.6883$ \\
$= 0.3e^{4.6883}$ \\
$= 0.3 \times 108.67$ \\
$= 32.6$ mg L$^{-1}$ (3 sf) \\
(c) Set $x = 0.1$ when $t = T$: \\
$0.1 = 0.3e^{AT - \frac{T^{2}}{2}}$ \\
Divide both sides by 0.3: \\
$e^{AT - \frac{T^{2}}{2}} = \frac{1}{3}$ \\
Take natural logs: \\
$AT - \frac{T^{2}}{2} = \ln\frac{1}{3} = -\ln 3$ \\
Multiply every term by $-2$: \\
$T^{2} - 2AT = 2\ln 3$ \\
$T^{2} - 2AT - 2\ln 3 = 0$ \\
Use the quadratic formula with $a = 1$, $b = -2A$, $c = -2\ln 3$: \\
$T = \frac{2A \pm \sqrt{4A^{2} + 8\ln 3}}{2}$ \\
$= A \pm \sqrt{A^{2} + 2\ln 3}$ \\
$A^{2} + 2\ln 3 = 9.3766 + 2.1972 = 11.5738$ \\
$\sqrt{11.5738} = 3.4020$ \\
$T = 3.0621 + 3.4020 = 6.4641$ or $T = 3.0621 - 3.4020 = -0.3399$ \\
$T > 0$, so reject the negative root \\
$T = 6.46$ (3 sf)

@q 15
@topic Proof by contradiction, odd a and b
@marks 4
@question
Assume $a$ and $b$ are both odd, so $a = 2m + 1$ and $b = 2n + 1$ \\
$a^{2} + b^{2} = (2m + 1)^{2} + (2n + 1)^{2}$ \\
Expand each bracket: \\
$(2m + 1)^{2} = 4m^{2} + 4m + 1$ \\
$(2n + 1)^{2} = 4n^{2} + 4n + 1$ \\
$a^{2} + b^{2} = 4m^{2} + 4m + 1 + 4n^{2} + 4n + 1$ \\
Collect like terms: \\
$= 4m^{2} + 4m + 4n^{2} + 4n + 2$ \\
Factorise the first four terms: \\
$= 4(m^{2} + m + n^{2} + n) + 2$ \\
$c^{2} = a^{2} + b^{2}$, so $c^{2} = 4(m^{2} + m + n^{2} + n) + 2$ \\
$4(m^{2} + m + n^{2} + n)$ is even and 2 is even, so $c^{2}$ is even \\
Using the given result, if $c^{2}$ is even then $c$ is even \\
So $c = 2k$ for some $k \in \mathbb{N}$, and $c^{2} = 4k^{2}$ \\
$4k^{2} = 4(m^{2} + m + n^{2} + n) + 2$ \\
Divide every term by 2: \\
$2k^{2} = 2(m^{2} + m + n^{2} + n) + 1$ \\
The left-hand side $2k^{2}$ is even \\
The right-hand side is $2 \times (\text{an integer}) + 1$, which is odd \\
An even number cannot equal an odd number, which is a contradiction \\
So the assumption is false, and $a$ and $b$ cannot both be odd
