@paper P1 Mock Set 4

@q 1
@topic Straight line, gradient, perpendicular
@marks 5
@question
(a) $A = (-3, -2)$ and $B = (7, 5)$ \\
Gradient $= \frac{y_{2} - y_{1}}{x_{2} - x_{1}}$ \\
$m = \frac{5 - (-2)}{7 - (-3)}$ \\
$= \frac{5 + 2}{7 + 3}$ \\
$= \frac{7}{10}$ \\
(b) Use $B(7, 5)$ and $m = \frac{7}{10}$ in $y - y_{1} = m(x - x_{1})$: \\
$y - 5 = \frac{7}{10}(x - 7)$ \\
Multiply both sides by 10: \\
$10(y - 5) = 7(x - 7)$ \\
Expand both brackets: \\
$10y - 50 = 7x - 49$ \\
Move every term to the right-hand side (subtract $10y$ from both sides and add 50 to both sides): \\
$0 = 7x - 49 - 10y + 50$ \\
$0 = 7x - 10y + 1$ \\
$7x - 10y + 1 = 0$ \\
Check with $A(-3, -2)$: $7(-3) - 10(-2) + 1 = -21 + 20 + 1 = 0$ \\
(c) For perpendicular lines the gradients multiply to $-1$: $m_{1} \times m_{2} = -1$ \\
$\frac{7}{10} \times m_{2} = -1$ \\
$m_{2} = -1 \div \frac{7}{10}$ \\
$m_{2} = -\frac{10}{7}$

@q 2
@topic Recurrence relation, sum of terms
@marks 4
@question
(a) $u_{n+1} = pu_{n} + q$ and $u_{1} = 4$ \\
$u_{2} = pu_{1} + q$ \\
$u_{2} = 4p + q$ \\
(b) Given $u_{2} = 10$: \\
$4p + q = 10$ \\
Equation 1: $4p + q = 10$ \\
$u_{3} = pu_{2} + q = 10p + q$ \\
$\sum_{r=1}^{3} u_{r} = u_{1} + u_{2} + u_{3} = 42$ \\
$4 + 10 + 10p + q = 42$ \\
$14 + 10p + q = 42$ \\
Subtract 14 from both sides: \\
$10p + q = 28$ \\
Equation 2: $10p + q = 28$ \\
Subtract equation 1 from equation 2: \\
$(10p + q) - (4p + q) = 28 - 10$ \\
$6p = 18$ \\
$p = 3$ \\
Substitute $p = 3$ into equation 1: \\
$4(3) + q = 10$ \\
$12 + q = 10$ \\
$q = -2$ \\
So $p = 3$ and $q = -2$

@q 3
@topic Functions, range, composite and inverse
@marks 6
@question
(a) $f(x) = e^{3x} + 2$ \\
$e^{3x}$ is always positive, so $e^{3x} > 0$ \\
Add 2 to both sides: $e^{3x} + 2 > 2$ \\
Range of $f$: $f(x) > 2$ \\
(b) $\text{fg}(x) = f(g(x)) = f(\ln x)$ \\
$= e^{3\ln x} + 2$ \\
Use the power law $3\ln x = \ln(x^{3})$: \\
$= e^{\ln(x^{3})} + 2$ \\
Use $e^{\ln a} = a$: \\
$= x^{3} + 2$ \\
(c) Let $y = e^{3x} + 2$ \\
Subtract 2 from both sides: \\
$y - 2 = e^{3x}$ \\
Take natural logs of both sides: \\
$\ln(y - 2) = \ln(e^{3x})$ \\
$\ln(y - 2) = 3x$ \\
Divide both sides by 3: \\
$x = \frac{1}{3}\ln(y - 2)$ \\
Replace $y$ by $x$: \\
$f^{-1}(x) = \frac{1}{3}\ln(x - 2)$ \\
The domain of $f^{-1}$ is the range of $f$: $x > 2$

@q 4
@topic Logarithms, solving with log laws
@marks 4
@question
$\log_{2}(x + 2) + \log_{2}(x + 3) - 2\log_{2} x = 1$ \\
Use the power law on the last term: $2\log_{2} x = \log_{2}(x^{2})$ \\
$\log_{2}(x + 2) + \log_{2}(x + 3) - \log_{2}(x^{2}) = 1$ \\
Use the addition law $\log a + \log b = \log(ab)$ on the first two terms: \\
$\log_{2}[(x + 2)(x + 3)] - \log_{2}(x^{2}) = 1$ \\
Use the subtraction law $\log a - \log b = \log\frac{a}{b}$: \\
$\log_{2}\left( \frac{(x + 2)(x + 3)}{x^{2}} \right) = 1$ \\
Undo the logarithm: if $\log_{2} y = 1$ then $y = 2^{1} = 2$ \\
$\frac{(x + 2)(x + 3)}{x^{2}} = 2$ \\
Multiply both sides by $x^{2}$: \\
$(x + 2)(x + 3) = 2x^{2}$ \\
Expand the bracket: \\
$x^{2} + 3x + 2x + 6 = 2x^{2}$ \\
$x^{2} + 5x + 6 = 2x^{2}$ \\
Subtract $x^{2} + 5x + 6$ from both sides: \\
$0 = x^{2} - 5x - 6$ \\
Factorise: the numbers with product $-6$ and sum $-5$ are $-6$ and $1$ \\
$(x - 6)(x + 1) = 0$ \\
$x = 6$ or $x = -1$ \\
$x = -1$ makes $\log_{2} x$ undefined, so it is rejected \\
Check $x = 6$: $\log_{2} 8 + \log_{2} 9 - 2\log_{2} 6 = \log_{2}\frac{72}{36} = \log_{2} 2 = 1$ \\
$x = 6$

@q 5
@topic Binomial expansion, (2+3x)^6, coefficient
@marks 7
@question
(a) Use the binomial expansion with the coefficients $6C0 = 1$, $6C1 = 6$, $6C2 = 15$, $6C3 = 20$: \\
$(2 + 3x)^{6} = 2^{6} + 6C1(2^{5})(3x) + 6C2(2^{4})(3x)^{2} + 6C3(2^{3})(3x)^{3} + \ldots$ \\
Term 1: $2^{6} = 64$ \\
Term 2: $6 \times 32 \times 3x = 576x$ \\
Term 3: $15 \times 16 \times 9x^{2} = 2160x^{2}$ \\
Term 4: $20 \times 8 \times 27x^{3} = 4320x^{3}$ \\
$(2 + 3x)^{6} = 64 + 576x + 2160x^{2} + 4320x^{3} + \ldots$ \\
(b) Find the terms that give $x^{1}$ when $\left( 3x - \frac{1}{8x^{2}} \right)$ is multiplied by the expansion \\
$3x$ times the constant term: $3x \times 64 = 192x$ \\
$-\frac{1}{8x^{2}}$ times the $x^{3}$ term: $-\frac{1}{8x^{2}} \times 4320x^{3} = -\frac{4320}{8}x = -540x$ \\
(No other pairs give $x^{1}$: $3x \times 576x$ gives $x^{2}$, and $-\frac{1}{8x^{2}} \times 2160x^{2}$ gives $x^{0}$.) \\
Coefficient of $x$ $= 192 - 540$ \\
$= -348$

@q 6
@topic Proof by contradiction, x + 4/x >= 4
@marks 4
@question
Assume the opposite: there is a positive real $x$ for which $x + \frac{4}{x} < 4$ \\
Multiply both sides by $x$ (positive, so the inequality does not change direction): \\
$x^{2} + 4 < 4x$ \\
Subtract $4x$ from both sides: \\
$x^{2} - 4x + 4 < 0$ \\
Factorise the left-hand side as a perfect square: \\
$(x - 2)^{2} < 0$ \\
But a real number squared is never negative, so $(x - 2)^{2} \ge 0$ for all real $x$ \\
This is a contradiction, so the assumption is false \\
Therefore $x + \frac{4}{x} \ge 4$ for all positive real $x$

@q 7
@topic Vectors: minimum distance and ratio
@marks 9
@question
(a) $\text{OA} = (8, -3, 2)$ and $\text{OB} = (t, 2t, 5t)$ \\
$\text{AB} = \text{OB} - \text{OA}$ \\
$= (t - 8, 2t - (-3), 5t - 2)$ \\
$= (t - 8, 2t + 3, 5t - 2)$ \\
$|\text{AB}|^{2} = (t - 8)^{2} + (2t + 3)^{2} + (5t - 2)^{2}$ \\
Expand each bracket: \\
$(t - 8)^{2} = t^{2} - 16t + 64$ \\
$(2t + 3)^{2} = 4t^{2} + 12t + 9$ \\
$(5t - 2)^{2} = 25t^{2} - 20t + 4$ \\
$|\text{AB}|^{2} = t^{2} - 16t + 64 + 4t^{2} + 12t + 9 + 25t^{2} - 20t + 4$ \\
Collect the $t^{2}$ terms: $t^{2} + 4t^{2} + 25t^{2} = 30t^{2}$ \\
Collect the $t$ terms: $-16t + 12t - 20t = -24t$ \\
Collect the numbers: $64 + 9 + 4 = 77$ \\
$|\text{AB}|^{2} = 30t^{2} - 24t + 77$ as required \\
(b)(i) $|\text{AB}|$ is smallest when $|\text{AB}|^{2}$ is smallest \\
Differentiate: $\frac{d}{dt}(30t^{2} - 24t + 77) = 60t - 24$ \\
Set equal to zero: \\
$60t - 24 = 0$ \\
$60t = 24$ \\
$t = \frac{24}{60} = \frac{2}{5}$ \\
The second derivative is $60 > 0$, so this is a minimum \\
(ii) Substitute $t = \frac{2}{5}$ into $|\text{AB}|^{2} = 30t^{2} - 24t + 77$: \\
$= 30\left( \frac{2}{5} \right)^{2} - 24\left( \frac{2}{5} \right) + 77$ \\
$= 30 \times \frac{4}{25} - \frac{48}{5} + 77$ \\
$= \frac{120}{25} - \frac{48}{5} + 77$ \\
$= \frac{24}{5} - \frac{48}{5} + 77$ \\
$= -\frac{24}{5} + \frac{385}{5}$ \\
$= \frac{361}{5}$ \\
$|\text{AB}| = \sqrt{\frac{361}{5}} = \frac{\sqrt{361}}{\sqrt{5}} = \frac{19}{\sqrt{5}}$ \\
Rationalise the denominator, multiplying top and bottom by $\sqrt{5}$: \\
$= \frac{19\sqrt{5}}{5}$ \\
(c) At $t = \frac{2}{5}$: $\text{AB} = \left( \frac{2}{5} - 8, \frac{4}{5} + 3, 5 \times \frac{2}{5} - 2 \right)$ \\
$= \left( -\frac{38}{5}, \frac{19}{5}, 0 \right)$ \\
$C$ divides $AB$ in the ratio $5 : 3$, so $AC = \frac{5}{8}AB$ \\
$\text{OC} = \text{OA} + \frac{5}{8}\text{AB}$ \\
$= (8, -3, 2) + \frac{5}{8}\left( -\frac{38}{5}, \frac{19}{5}, 0 \right)$ \\
$\frac{5}{8} \times \left( -\frac{38}{5} \right) = -\frac{38}{8} = -\frac{19}{4}$ \\
$\frac{5}{8} \times \frac{19}{5} = \frac{19}{8}$ \\
$= (8, -3, 2) + \left( -\frac{19}{4}, \frac{19}{8}, 0 \right)$ \\
$= \left( 8 - \frac{19}{4}, -3 + \frac{19}{8}, 2 \right)$ \\
$= \left( \frac{32}{4} - \frac{19}{4}, -\frac{24}{8} + \frac{19}{8}, 2 \right)$ \\
$C = \left( \frac{13}{4}, -\frac{5}{8}, 2 \right)$

@q 8
@topic Trig identity, double angle, tan equation
@marks 8
@question
(a) Use $\sin 2\theta = 2\sin \theta \cos \theta$ and $\cos 2\theta = 2\cos^{2}\theta - 1$ \\
Numerator: \\
$\sin 2\theta + \sin \theta = 2\sin \theta \cos \theta + \sin \theta$ \\
Factorise out $\sin \theta$: \\
$= \sin \theta(2\cos \theta + 1)$ \\
Denominator: \\
$\cos 2\theta + \cos \theta + 1 = 2\cos^{2}\theta - 1 + \cos \theta + 1$ \\
The $-1$ and $+1$ cancel: \\
$= 2\cos^{2}\theta + \cos \theta$ \\
Factorise out $\cos \theta$: \\
$= \cos \theta(2\cos \theta + 1)$ \\
$\frac{\sin 2\theta + \sin \theta}{\cos 2\theta + \cos \theta + 1} = \frac{\sin \theta(2\cos \theta + 1)}{\cos \theta(2\cos \theta + 1)}$ \\
Cancel the common factor $(2\cos \theta + 1)$: \\
$= \frac{\sin \theta}{\cos \theta}$ \\
$= \tan \theta$ as required \\
(b) By part (a), the equation becomes $\tan x = 2\cos x$ \\
Use $\tan x = \frac{\sin x}{\cos x}$: \\
$\frac{\sin x}{\cos x} = 2\cos x$ \\
Multiply both sides by $\cos x$: \\
$\sin x = 2\cos^{2} x$ \\
Use $\cos^{2} x = 1 - \sin^{2} x$: \\
$\sin x = 2(1 - \sin^{2} x)$ \\
Expand the bracket: \\
$\sin x = 2 - 2\sin^{2} x$ \\
Move everything to the left-hand side: \\
$2\sin^{2} x + \sin x - 2 = 0$ \\
This is a quadratic in $\sin x$, with $a = 2$, $b = 1$, $c = -2$ \\
$\sin x = \frac{-b \pm \sqrt{b^{2} - 4ac}}{2a}$ \\
$= \frac{-1 \pm \sqrt{1 - 4(2)(-2)}}{2(2)}$ \\
$= \frac{-1 \pm \sqrt{1 + 16}}{4}$ \\
$= \frac{-1 \pm \sqrt{17}}{4}$ \\
$\sin x = 0.7808$ or $\sin x = -1.2808$ \\
$\sin x = -1.2808$ is impossible, as $-1 \le \sin x \le 1$ \\
$\sin x = 0.7808$: \\
$x = \sin^{-1}(0.7808) = 0.896$ \\
In the range $0 < x < \pi$ the other solution is $x = \pi - 0.896$ \\
$x = 3.1416 - 0.8959 = 2.246$ \\
$x = 0.896$ or $x = 2.246$ (3 dp)

@q 9
@topic Exponential decay model - kettle
@marks 9
@question
(a) $\theta = 21 + Ae^{-kt}$ \\
At $t = 0$, $\theta = 80$: \\
$80 = 21 + Ae^{0}$ \\
$80 = 21 + A$ \\
$A = 59$ \\
At $t = 40$, $\theta = 33$: \\
$33 = 21 + 59e^{-40k}$ \\
Subtract 21 from both sides: \\
$12 = 59e^{-40k}$ \\
Divide both sides by 59: \\
$e^{-40k} = \frac{12}{59}$ \\
Take natural logs of both sides: \\
$-40k = \ln\left( \frac{12}{59} \right)$ \\
Divide both sides by $-40$: \\
$k = -\frac{1}{40}\ln\left( \frac{12}{59} \right)$ \\
$= \frac{1}{40}\ln\left( \frac{59}{12} \right)$ \\
$= \frac{1.5926}{40}$ \\
$= 0.0398$ (3 sf) \\
$\theta = 21 + 59e^{-0.0398t}$ \\
(b) Use the model at $t = 20$: \\
$\theta = 21 + 59e^{-0.0398 \times 20}$ \\
$= 21 + 59e^{-0.796}$ \\
$= 21 + 59(0.45113)$ \\
$= 21 + 26.617$ \\
$= 47.6$ degrees C \\
The model gives $47.6$, which is very close to the actual $48$ degrees C \\
So the model is appropriate \\
(c) Differentiate $\theta = 21 + 59e^{-0.0398t}$: \\
$\frac{d\theta}{dt} = 59 \times (-0.0398)e^{-0.0398t}$ \\
$= -2.3482e^{-0.0398t}$ \\
At $t = 20$: \\
$\frac{d\theta}{dt} = -2.3482e^{-0.0398 \times 20}$ \\
$= -2.3482e^{-0.796}$ \\
$= -2.3482(0.45113)$ \\
$= -1.06$ \\
The temperature is decreasing at a rate of $1.06$ degrees C per minute

@q 10
@topic Geometric series, convergence, range of k
@marks 5
@question
(a) First term $a = 4 + k$ and second term $ar = 8 - 2k$ \\
Common ratio $r = \frac{\text{second term}}{\text{first term}} = \frac{8 - 2k}{4 + k}$ \\
When $k = 20$: \\
$r = \frac{8 - 2(20)}{4 + 20}$ \\
$= \frac{8 - 40}{24}$ \\
$= \frac{-32}{24}$ \\
$= -\frac{4}{3}$ \\
A geometric series converges only if $|r| < 1$ \\
$\left| -\frac{4}{3} \right| = \frac{4}{3} > 1$, so the series does not converge \\
(b) For the series to converge, $-1 < r < 1$: \\
$-1 < \frac{8 - 2k}{4 + k} < 1$ \\
$k$ is positive, so $4 + k > 0$, and multiplying by it does not change the direction of the inequalities \\
Right-hand inequality: $\frac{8 - 2k}{4 + k} < 1$ \\
Multiply both sides by $(4 + k)$: \\
$8 - 2k < 4 + k$ \\
Add $2k$ to both sides: \\
$8 < 4 + 3k$ \\
Subtract 4 from both sides: \\
$4 < 3k$ \\
$k > \frac{4}{3}$ \\
Left-hand inequality: $\frac{8 - 2k}{4 + k} > -1$ \\
Multiply both sides by $(4 + k)$: \\
$8 - 2k > -(4 + k)$ \\
$8 - 2k > -4 - k$ \\
Add $2k$ to both sides: \\
$8 > -4 + k$ \\
Add 4 to both sides: \\
$12 > k$ \\
$k < 12$ \\
Combine both: \\
$\frac{4}{3} < k < 12$

@q 11
@topic Exponential model - wind farm energy
@marks 8
@question
(a)(i) $t$ is the number of years after 1996 \\
2006: $t = 10$ and $E = 74$: $74 = ab^{10}$ \\
2010: $t = 14$ and $E = 198$: $198 = ab^{14}$ \\
Divide the second equation by the first: \\
$\frac{198}{74} = \frac{ab^{14}}{ab^{10}}$ \\
$\frac{198}{74} = b^{4}$ \\
Take the 4th root of both sides: \\
$b = \left( \frac{198}{74} \right)^{\frac{1}{4}}$ \\
$= (2.6757)^{\frac{1}{4}}$ \\
$= 1.279$ (3 dp) \\
(a)(ii) Use $74 = ab^{10}$: \\
$a = \frac{74}{b^{10}}$ \\
$= \frac{74}{1.279^{10}}$ \\
$= \frac{74}{11.71}$ \\
$= 6.3$ (1 dp) \\
(b)(i) When $t = 0$, $E = ab^{0} = a$ \\
So $a$ is the global yearly energy output, in GW, from onshore wind farms in 1996 \\
(b)(ii) Each year $E$ is multiplied by $b$ \\
So $b$ is the factor by which the energy output grows each year (an increase of about 27.9 percent a year) \\
(c) 2025 is $2025 - 1996 = 29$ years after 1996, so $t = 29$ \\
$E = 6.3 \times 1.279^{29}$ \\
$1.279^{29} = 1256.7$ \\
$E = 6.3 \times 1256.7$ \\
$= 7917$ \\
The predicted output in 2025 is about 7920 GW \\
(Using the unrounded values of $a$ and $b$ from the calculator gives 7935 GW, which is also accepted.)

@q 12
@topic Integration by substitution and by parts
@marks 7
@question
(a) $\int x^{2}e^{x^{3}} \, dx$ \\
The derivative of $x^{3}$ is $3x^{2}$, so reverse the chain rule: \\
$\frac{d}{dx}\left( e^{x^{3}} \right) = 3x^{2}e^{x^{3}}$ \\
So $\int 3x^{2}e^{x^{3}} \, dx = e^{x^{3}}$ \\
Divide by 3: \\
$\int x^{2}e^{x^{3}} \, dx = \frac{1}{3}e^{x^{3}} + c$ \\
(b) Let $u = x^{3}$ \\
$\frac{du}{dx} = 3x^{2}$ \\
So $x^{2} \, dx = \frac{1}{3} \, du$ \\
Write $x^{8} = x^{6} \times x^{2}$ and $x^{6} = (x^{3})^{2} = u^{2}$: \\
$\int x^{8}e^{x^{3}} \, dx = \int x^{6}e^{x^{3}} \times x^{2} \, dx$ \\
$= \int u^{2}e^{u} \times \frac{1}{3} \, du$ \\
$= \frac{1}{3}\int u^{2}e^{u} \, du$ \\
Integrate by parts: let $p = u^{2}$ and $\frac{dq}{du} = e^{u}$, so $\frac{dp}{du} = 2u$ and $q = e^{u}$ \\
$\int u^{2}e^{u} \, du = u^{2}e^{u} - \int 2ue^{u} \, du$ \\
$= u^{2}e^{u} - 2\int ue^{u} \, du$ \\
Integrate by parts again: let $p = u$ and $\frac{dq}{du} = e^{u}$, so $\frac{dp}{du} = 1$ and $q = e^{u}$ \\
$\int ue^{u} \, du = ue^{u} - \int e^{u} \, du$ \\
$= ue^{u} - e^{u}$ \\
Substitute back: \\
$\int u^{2}e^{u} \, du = u^{2}e^{u} - 2(ue^{u} - e^{u})$ \\
$= u^{2}e^{u} - 2ue^{u} + 2e^{u}$ \\
Factorise: \\
$= e^{u}(u^{2} - 2u + 2)$ \\
$\int x^{8}e^{x^{3}} \, dx = \frac{1}{3}e^{u}(u^{2} - 2u + 2) + c$ \\
Replace $u$ by $x^{3}$: \\
$= \frac{1}{3}e^{x^{3}}(x^{6} - 2x^{3} + 2) + c$ \\
So $A = -2$ and $B = 2$

@q 13
@topic Partial fractions, differential eq, fungus
@marks 10
@question
(a) $\frac{1}{x(100 - x)} = \frac{P}{x} + \frac{Q}{100 - x}$ \\
Multiply both sides by $x(100 - x)$: \\
$1 = P(100 - x) + Qx$ \\
Let $x = 0$: $1 = 100P$, so $P = \frac{1}{100}$ \\
Let $x = 100$: $1 = 100Q$, so $Q = \frac{1}{100}$ \\
$\frac{1}{x(100 - x)} = \frac{1}{100x} + \frac{1}{100(100 - x)}$ \\
(b) $500\frac{dx}{dt} = x(100 - x)$ \\
Separate the variables: \\
$\frac{1}{x(100 - x)} \, dx = \frac{1}{500} \, dt$ \\
Use (a) on the left-hand side and integrate both sides: \\
$\int \left( \frac{1}{100x} + \frac{1}{100(100 - x)} \right) dx = \int \frac{1}{500} \, dt$ \\
$\int \frac{1}{100x} \, dx = \frac{1}{100}\ln x$ \\
$\int \frac{1}{100(100 - x)} \, dx = -\frac{1}{100}\ln(100 - x)$ \\
$\frac{1}{100}\ln x - \frac{1}{100}\ln(100 - x) = \frac{t}{500} + c$ \\
Multiply every term by 100: \\
$\ln x - \ln(100 - x) = \frac{t}{5} + C$ \\
At the start, $t = 0$ and $x = 5$: \\
$\ln 5 - \ln 95 = 0 + C$ \\
$C = \ln\frac{5}{95} = \ln\frac{1}{19}$ \\
$\ln x - \ln(100 - x) = \frac{t}{5} + \ln\frac{1}{19}$ \\
Combine the logs on the left: \\
$\ln\frac{x}{100 - x} = \frac{t}{5} + \ln\frac{1}{19}$ \\
Undo the log by raising $e$ to the power of both sides: \\
$\frac{x}{100 - x} = e^{\frac{t}{5} + \ln\frac{1}{19}}$ \\
$= e^{\frac{t}{5}} \times e^{\ln\frac{1}{19}}$ \\
$\frac{x}{100 - x} = \frac{1}{19}e^{\frac{t}{5}}$ \\
Multiply both sides by $19(100 - x)$: \\
$19x = (100 - x)e^{\frac{t}{5}}$ \\
Expand the bracket: \\
$19x = 100e^{\frac{t}{5}} - xe^{\frac{t}{5}}$ \\
Get the $x$ terms together: \\
$19x + xe^{\frac{t}{5}} = 100e^{\frac{t}{5}}$ \\
Factorise: \\
$x\left( 19 + e^{\frac{t}{5}} \right) = 100e^{\frac{t}{5}}$ \\
$x = \frac{100e^{\frac{t}{5}}}{19 + e^{\frac{t}{5}}}$ \\
Divide the top and the bottom by $e^{\frac{t}{5}}$: \\
$x = \frac{100}{19e^{-\frac{t}{5}} + 1}$ \\
$x = \frac{100}{1 + 19e^{-\frac{1}{5}t}}$ \\
So $A = 100$ and $B = 19$ \\
(c) $t = 10$: \\
$x = \frac{100}{1 + 19e^{-\frac{1}{5} \times 10}}$ \\
$= \frac{100}{1 + 19e^{-2}}$ \\
$e^{-2} = 0.13534$ \\
$= \frac{100}{1 + 2.5714}$ \\
$= \frac{100}{3.5714}$ \\
$= 28.0$ \\
The area affected after 10 days is $28 \text{ m}^{2}$

@q 14
@topic Parametric equations, area, integration
@marks 10
@question
(a) At $\theta = \frac{\pi}{3}$: \\
$x = \frac{1}{2} \times \frac{\pi}{3} \times \sin\frac{\pi}{3}$ \\
$= \frac{\pi}{6} \times \frac{\sqrt{3}}{2}$ \\
$= \frac{\pi\sqrt{3}}{12}$ \\
$y = \frac{1}{3}\sec\frac{\pi}{3}$ \\
$\sec\frac{\pi}{3} = \frac{1}{\cos\frac{\pi}{3}} = \frac{1}{\frac{1}{2}} = 2$ \\
$y = \frac{1}{3} \times 2 = \frac{2}{3}$ \\
$P = \left( \frac{\pi\sqrt{3}}{12}, \frac{2}{3} \right)$ \\
(b) $x = \frac{1}{2}\theta\sin\theta$ \\
Use the product rule: \\
$\frac{dx}{d\theta} = \frac{1}{2}\sin\theta + \frac{1}{2}\theta\cos\theta$ \\
The area under the curve is $\int y \, dx = \int y\frac{dx}{d\theta} \, d\theta$ \\
$\int y\frac{dx}{d\theta} \, d\theta = \int \frac{1}{3}\sec\theta\left( \frac{1}{2}\sin\theta + \frac{1}{2}\theta\cos\theta \right) d\theta$ \\
Take out the factor $\frac{1}{3} \times \frac{1}{2} = \frac{1}{6}$: \\
$= \frac{1}{6}\int \sec\theta(\sin\theta + \theta\cos\theta) \, d\theta$ \\
Expand the bracket: \\
$= \frac{1}{6}\int (\sec\theta\sin\theta + \theta\sec\theta\cos\theta) \, d\theta$ \\
Use $\sec\theta = \frac{1}{\cos\theta}$, so $\sec\theta\sin\theta = \tan\theta$ and $\sec\theta\cos\theta = 1$: \\
$= \frac{1}{6}\int (\tan\theta + \theta) \, d\theta$ \\
At $\theta = 0$, $x = 0$, and at $\theta = \frac{\pi}{3}$, $x = \frac{\pi\sqrt{3}}{12}$ \\
$R$ is between the line $y = \frac{2}{3}$ and the curve, from the $y$-axis to $P$ \\
Area of $R$ = area of the rectangle $-$ area under the curve \\
Rectangle: $\frac{\pi\sqrt{3}}{12} \times \frac{2}{3} = \frac{2\pi\sqrt{3}}{36} = \frac{\pi\sqrt{3}}{18}$ \\
Area of $R = \frac{\pi\sqrt{3}}{18} - \frac{1}{6}\int_{0}^{\frac{\pi}{3}} (\tan\theta + \theta) \, d\theta$ \\
So $A = \frac{1}{18}$ and $B = \frac{1}{6}$ \\
(c) $\int \tan\theta \, d\theta = \ln(\sec\theta)$ \\
$\int \theta \, d\theta = \frac{\theta^{2}}{2}$ \\
$\int_{0}^{\frac{\pi}{3}} (\tan\theta + \theta) \, d\theta = \left[ \ln(\sec\theta) + \frac{\theta^{2}}{2} \right]_{0}^{\frac{\pi}{3}}$ \\
Upper limit $\theta = \frac{\pi}{3}$: $\ln\left( \sec\frac{\pi}{3} \right) + \frac{1}{2}\left( \frac{\pi}{3} \right)^{2} = \ln 2 + \frac{\pi^{2}}{18}$ \\
Lower limit $\theta = 0$: $\ln(\sec 0) + 0 = \ln 1 = 0$ \\
$= \ln 2 + \frac{\pi^{2}}{18} - 0$ \\
Area of $R = \frac{\pi\sqrt{3}}{18} - \frac{1}{6}\left( \ln 2 + \frac{\pi^{2}}{18} \right)$ \\
Expand the bracket: \\
$= \frac{\pi\sqrt{3}}{18} - \frac{1}{6}\ln 2 - \frac{\pi^{2}}{108}$

@q 15
@topic Inverse trig functions, intersection point
@marks 4
@question
(a) $C_{1}$: $y = \cos^{-1}\left( \frac{1}{2}x \right)$ \\
Take the cosine of both sides: \\
$\cos y = \frac{1}{2}x$ \\
Multiply both sides by 2: \\
$x = 2\cos y$ \\
$C_{2}$: $y = \sin^{-1} x$ \\
Take the sine of both sides: \\
$\sin y = x$ \\
At $P$ both curves have the same $x$ and $y$, so: \\
$\sin y = 2\cos y$ \\
Divide both sides by $\cos y$: \\
$\frac{\sin y}{\cos y} = 2$ \\
$\tan y = 2$ as required \\
(b) $\tan y = 2$, so draw a right-angled triangle with opposite side 2 and adjacent side 1 \\
Hypotenuse $= \sqrt{2^{2} + 1^{2}} = \sqrt{5}$ \\
$\sin y = \frac{\text{opposite}}{\text{hypotenuse}} = \frac{2}{\sqrt{5}}$ \\
$y$ is in the first quadrant, since $\tan y > 0$ and $y = \sin^{-1} x$ lies between $-\frac{\pi}{2}$ and $\frac{\pi}{2}$ \\
$x = \sin y = \frac{2}{\sqrt{5}}$ \\
Rationalise the denominator, multiplying top and bottom by $\sqrt{5}$: \\
$x = \frac{2\sqrt{5}}{5}$
