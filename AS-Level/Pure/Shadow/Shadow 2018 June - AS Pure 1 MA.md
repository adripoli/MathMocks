@paper AS1 Shadow June 2018

@q 1
@topic Integrate polynomial with surd term
@marks 4
@question
Rewrite $6x\sqrt{x}$ as a single power of $x$, using $\sqrt{x} = x^{\frac{1}{2}}$: \\
$6x\sqrt{x} = 6x^{1} \times x^{\frac{1}{2}}$ \\
Add the indices, $1 + \frac{1}{2} = \frac{3}{2}$: \\
$6x\sqrt{x} = 6x^{\frac{3}{2}}$ \\
The integral is now: \\
$\int \left( \frac{2}{5}x^{5} - 6x^{\frac{3}{2}} - 1 \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$ \\
First term: $\frac{2}{5}x^{5} \to \frac{2}{5} \times \frac{x^{6}}{6}$ \\
$= \frac{2x^{6}}{30}$ \\
$= \frac{x^{6}}{15}$ \\
Second term: $-6x^{\frac{3}{2}} \to -6 \times \frac{x^{\frac{5}{2}}}{\frac{5}{2}}$ \\
Dividing by $\frac{5}{2}$ is the same as multiplying by $\frac{2}{5}$: \\
$= -6 \times \frac{2}{5}x^{\frac{5}{2}}$ \\
$= -\frac{12}{5}x^{\frac{5}{2}}$ \\
Third term: $-1 \to -x$ \\
Add the constant of integration $c$: \\
$\int \left( \frac{2}{5}x^{5} - 6x\sqrt{x} - 1 \right) dx = \frac{1}{15}x^{6} - \frac{12}{5}x^{\frac{5}{2}} - x + c$

@q 2
@topic Always positive quadratic, inequality
@marks 5
@question
(i) Complete the square on $x^{2} - 7x$. Half of $-7$ is $-\frac{7}{2}$: \\
$x^{2} - 7x = \left( x - \frac{7}{2} \right)^{2} - \frac{49}{4}$ \\
Put this back into the expression: \\
$x^{2} - 7x + 18 = \left( x - \frac{7}{2} \right)^{2} - \frac{49}{4} + 18$ \\
Write 18 as $\frac{72}{4}$: \\
$= \left( x - \frac{7}{2} \right)^{2} - \frac{49}{4} + \frac{72}{4}$ \\
$= \left( x - \frac{7}{2} \right)^{2} + \frac{23}{4}$ \\
A square is never negative, so $\left( x - \frac{7}{2} \right)^{2} \geq 0$ \\
So $x^{2} - 7x + 18 \geq 0 + \frac{23}{4}$ \\
$x^{2} - 7x + 18 \geq \frac{23}{4} > 0$ for all real $x$, as required \\
Alt: the discriminant is $(-7)^{2} - 4(1)(18) = 49 - 72 = -23 < 0$, so there are no real roots, and the $x^{2}$ coefficient is positive so the curve is always above the $x$-axis \\
(ii) Let the number be $n$. The statement says: \\
$(n + 4)^{2} > n^{2}$ \\
Expand the bracket: \\
$n^{2} + 8n + 16 > n^{2}$ \\
Subtract $n^{2}$ from both sides: \\
$8n + 16 > 0$ \\
Subtract 16 from both sides: \\
$8n > -16$ \\
Divide both sides by 8: \\
$n > -2$ \\
The statement is only true when $n > -2$, so it is sometimes true \\
Reason, with examples: $n = 1$ gives $5^{2} = 25 > 1^{2} = 1$ (true), but $n = -3$ gives $1^{2} = 1$ which is not greater than $(-3)^{2} = 9$ (false)

@q 3
@topic Vector AB and its magnitude
@marks 4
@question
(a) $\text{AB} = \text{OB} - \text{OA}$ (end point minus start point) \\
$\text{AB} = (-2\mathbf{i} - 3\mathbf{j}) - (5\mathbf{i} + 4\mathbf{j})$ \\
Subtract the $\mathbf{i}$ parts: $-2 - 5 = -7$ \\
Subtract the $\mathbf{j}$ parts: $-3 - 4 = -7$ \\
$\text{AB} = -7\mathbf{i} - 7\mathbf{j}$ \\
(b) The magnitude is $\sqrt{(\text{i part})^{2} + (\text{j part})^{2}}$ \\
$|\text{AB}| = \sqrt{(-7)^{2} + (-7)^{2}}$ \\
$= \sqrt{49 + 49}$ \\
$= \sqrt{98}$ \\
Write 98 as $49 \times 2$: \\
$= \sqrt{49 \times 2}$ \\
$= \sqrt{49} \times \sqrt{2}$ \\
$= 7\sqrt{2}$

@q 4
@topic Parallel or perpendicular lines
@marks 4
@question
Find the gradient of $l_{1}$. Make $y$ the subject: \\
$3y - 4x = 10$ \\
Add $4x$ to both sides: \\
$3y = 4x + 10$ \\
Divide every term by 3: \\
$y = \frac{4}{3}x + \frac{10}{3}$ \\
So the gradient of $l_{1}$ is $m_{1} = \frac{4}{3}$ \\
Find the gradient of $l_{2}$, using $m = \frac{y_{2} - y_{1}}{x_{2} - x_{1}}$: \\
$m_{2} = \frac{8 - 5}{1 - (-1)}$ \\
$= \frac{3}{2}$ \\
Parallel test: parallel lines have equal gradients. \\
$\frac{4}{3} = \frac{8}{6}$ and $\frac{3}{2} = \frac{9}{6}$, so $m_{1} \neq m_{2}$ and the lines are not parallel \\
Perpendicular test: perpendicular lines have $m_{1} \times m_{2} = -1$ \\
$m_{1} \times m_{2} = \frac{4}{3} \times \frac{3}{2}$ \\
$= \frac{12}{6}$ \\
$= 2$ \\
$2 \neq -1$, so the lines are not perpendicular \\
The lines are neither parallel nor perpendicular

@q 5
@topic Spot the errors in a log solution
@marks 5
@question
(a) Error 1, in line 2. The subtraction law is $\log a - \log b = \log \frac{a}{b}$. The first term is $2\log_{2} x$, which has a coefficient 2, but the second term $\log_{2} \sqrt{x}$ does not. The student has wrongly multiplied both logs by 2 \\
Error 2, in the last line. By the definition of a log, $\log_{2} x = 6$ means $x = 2^{6}$, because the base is 2. The student used $6^{2}$ instead, which swaps the base and the power \\
(b) Use the power law $n\log a = \log a^{n}$ on both terms: \\
$2\log_{2} x = \log_{2} x^{2}$ \\
$\log_{2} \sqrt{x} = \log_{2} x^{\frac{1}{2}}$ \\
The equation becomes: \\
$\log_{2} x^{2} - \log_{2} x^{\frac{1}{2}} = 6$ \\
Use the subtraction law: \\
$\log_{2} \left( \frac{x^{2}}{x^{\frac{1}{2}}} \right) = 6$ \\
Subtract the indices, $2 - \frac{1}{2} = \frac{3}{2}$: \\
$\log_{2} x^{\frac{3}{2}} = 6$ \\
Use the definition of a log, $\log_{a} b = c \Rightarrow b = a^{c}$: \\
$x^{\frac{3}{2}} = 2^{6}$ \\
$x^{\frac{3}{2}} = 64$ \\
Raise both sides to the power $\frac{2}{3}$: \\
$x = 64^{\frac{2}{3}}$ \\
The cube root of 64 is 4: \\
$x = 4^{2}$ \\
$x = 16$ \\
(Check: $2\log_{2} 16 = 2 \times 4 = 8$ and $\log_{2} \sqrt{16} = \log_{2} 4 = 2$, so $8 - 2 = 6$) \\
Alt: use $\log_{2} \sqrt{x} = \frac{1}{2}\log_{2} x$. With $L = \log_{2} x$ the equation is $2L - \frac{1}{2}L = 6$, so $\frac{3}{2}L = 6$ and $L = 4$, giving $x = 2^{4} = 16$

@q 6
@topic Quadratic model: profit and price
@marks 7
@question
(a) Substitute $x = 15$ into the model: \\
$P = 120 - 6.25(15 - 9)^{2}$ \\
$= 120 - 6.25(6)^{2}$ \\
$= 120 - 6.25 \times 36$ \\
$= 120 - 225$ \\
$= -105$ \\
$P$ is in thousands of pounds, so this is a loss of GBP 105000. A selling price of GBP 15 would make a loss, so it is not sensible \\
(b) A profit of more than GBP 90000 means $P > 90$ (in thousands): \\
$120 - 6.25(x - 9)^{2} > 90$ \\
Subtract 120 from both sides: \\
$-6.25(x - 9)^{2} > -30$ \\
Divide both sides by $-6.25$ and reverse the inequality sign: \\
$(x - 9)^{2} < \frac{30}{6.25}$ \\
$(x - 9)^{2} < 4.8$ \\
Take square roots, remembering both signs: \\
$-\sqrt{4.8} < x - 9 < \sqrt{4.8}$ \\
$\sqrt{4.8} = 2.19089...$ \\
Add 9 to every part, taking the lower end: \\
$x > 9 - 2.19089...$ \\
$x > 6.80911...$ \\
The least selling price is GBP 6.81, to the nearest penny \\
(Check: at GBP 6.81, $P = 120 - 6.25(2.19)^{2} = 90.02$, which is above 90. At GBP 6.80, $P = 89.75$, which is below 90) \\
(c)(i) $(x - 9)^{2} \geq 0$, so $6.25(x - 9)^{2} \geq 0$ and $P \leq 120$ \\
The maximum is $P = 120$, which is GBP 120000 \\
(c)(ii) $P$ is largest when $(x - 9)^{2} = 0$, so $x = 9$ \\
The selling price that maximises profit is GBP 9

@q 7
@topic Triangle area and cosine rule
@marks 6
@question
(a) Use the area formula $\text{Area} = \frac{1}{2}ab\sin C$ with sides $AB$ and $AC$ and the angle $\theta$ between them: \\
$18 = \frac{1}{2} \times 12 \times 6 \times \sin \theta$ \\
$18 = 36\sin \theta$ \\
Divide both sides by 36: \\
$\sin \theta = \frac{18}{36}$ \\
$\sin \theta = \frac{1}{2}$ \\
Use $\sin^{2} \theta + \cos^{2} \theta = 1$: \\
$\cos^{2} \theta = 1 - \sin^{2} \theta$ \\
$= 1 - \left( \frac{1}{2} \right)^{2}$ \\
$= 1 - \frac{1}{4}$ \\
$= \frac{3}{4}$ \\
Take square roots, giving two values: \\
$\cos \theta = \pm \sqrt{\frac{3}{4}}$ \\
$\cos \theta = \pm \frac{\sqrt{3}}{2}$ \\
(b) Use the cosine rule $BC^{2} = AB^{2} + AC^{2} - 2(AB)(AC)\cos \theta$: \\
$BC^{2} = 12^{2} + 6^{2} - 2(12)(6)\cos \theta$ \\
$BC^{2} = 144 + 36 - 144\cos \theta$ \\
$BC^{2} = 180 - 144\cos \theta$ \\
Try $\cos \theta = \frac{\sqrt{3}}{2}$: \\
$BC^{2} = 180 - 144 \times \frac{\sqrt{3}}{2}$ \\
$= 180 - 72\sqrt{3}$ \\
$= 55.29...$, so $BC = 7.44$ cm (3 sf) \\
This is shorter than $AB = 12$ cm, so $BC$ would not be the longest side. Reject it \\
Try $\cos \theta = -\frac{\sqrt{3}}{2}$: \\
$BC^{2} = 180 - 144 \times \left( -\frac{\sqrt{3}}{2} \right)$ \\
$= 180 + 72\sqrt{3}$ \\
$= 304.7...$, so $BC = 17.5$ cm (3 sf) \\
This is longer than both 12 cm and 6 cm, so $BC$ is the longest side. Accept it \\
Take out the square number 36, since $180 = 36 \times 5$ and $72 = 36 \times 2$: \\
$BC^{2} = 36 \left( 5 + 2\sqrt{3} \right)$ \\
$BC = \sqrt{36} \times \sqrt{5 + 2\sqrt{3}}$ \\
$BC = 6\sqrt{5 + 2\sqrt{3}}$ cm

@q 8
@topic Minimise cost, second derivative
@marks 9
@question
(a)(i) Write each term as a power of $v$: \\
$C = 1400v^{-1} + \frac{3}{13}v + 50$ \\
Differentiate, using $\frac{d}{dv}(v^{n}) = nv^{n-1}$: \\
$\frac{dC}{dv} = -1400v^{-2} + \frac{3}{13}$ \\
$\frac{dC}{dv} = -\frac{1400}{v^{2}} + \frac{3}{13}$ \\
At a minimum, $\frac{dC}{dv} = 0$: \\
$-\frac{1400}{v^{2}} + \frac{3}{13} = 0$ \\
Add $\frac{1400}{v^{2}}$ to both sides: \\
$\frac{3}{13} = \frac{1400}{v^{2}}$ \\
Multiply both sides by $13v^{2}$: \\
$3v^{2} = 1400 \times 13$ \\
$3v^{2} = 18200$ \\
Divide both sides by 3: \\
$v^{2} = \frac{18200}{3}$ \\
A speed must be positive, so take the positive root: \\
$v = \sqrt{\frac{18200}{3}}$ \\
Write 18200 as $100 \times 182$: \\
$v = \sqrt{100 \times \frac{182}{3}}$ \\
Take the square root of 100 out of the root: \\
$v = 10\sqrt{\frac{182}{3}}$ \\
Split the root of a fraction, $\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}}$: \\
$v = \frac{10\sqrt{182}}{\sqrt{3}}$ \\
Rationalise the denominator, multiplying top and bottom by $\sqrt{3}$: \\
$v = \frac{10\sqrt{182} \times \sqrt{3}}{\sqrt{3} \times \sqrt{3}}$ \\
Multiply the roots: $\sqrt{182} \times \sqrt{3} = \sqrt{546}$ and $\sqrt{3} \times \sqrt{3} = 3$ \\
$v = \frac{10\sqrt{546}}{3}$ \\
This is $v = 77.889$ km per hour (3 dp) \\
(a)(ii) At this speed, $\frac{3}{13} = \frac{1400}{v^{2}}$. Multiply both sides by $v$: \\
$\frac{3v}{13} = \frac{1400}{v}$ \\
So the first two terms of $C$ are equal. Replace $\frac{1400}{v}$ with $\frac{3v}{13}$: \\
$C = \frac{3v}{13} + \frac{3v}{13} + 50$ \\
$C = \frac{6v}{13} + 50$ \\
Substitute $v = \frac{10\sqrt{546}}{3}$: \\
$C = \frac{6}{13} \times \frac{10\sqrt{546}}{3} + 50$ \\
$= \frac{60\sqrt{546}}{39} + 50$ \\
Divide top and bottom by 3: \\
$= \frac{20\sqrt{546}}{13} + 50$ \\
$= 35.949 + 50$ \\
The minimum cost is GBP 85.95 \\
(Check with $v = 77.889$: $\frac{1400}{77.889} = 17.974$ and $\frac{3 \times 77.889}{13} = 17.974$, so $C = 17.974 + 17.974 + 50 = 85.95$) \\
(b) Differentiate $\frac{dC}{dv} = -1400v^{-2} + \frac{3}{13}$ again: \\
$\frac{d^{2}C}{dv^{2}} = -1400 \times (-2)v^{-3}$ \\
$\frac{d^{2}C}{dv^{2}} = 2800v^{-3}$ \\
$\frac{d^{2}C}{dv^{2}} = \frac{2800}{v^{3}}$ \\
The speed is positive, so $v^{3} > 0$ and: \\
$\frac{d^{2}C}{dv^{2}} > 0$ at $v = \frac{10\sqrt{546}}{3}$ \\
A positive second derivative at a stationary point means a minimum, so the cost is minimised at this speed \\
(c) One limitation: the model assumes the lorry travels at a steady speed for the whole journey, but in real life traffic, roadworks and speed limits make the speed vary

@q 9
@topic Factor theorem, repeated root, sketch
@marks 9
@question
(a) By the factor theorem, $(x + 3)$ is a factor if $g(-3) = 0$ \\
$g(-3) = 25(-3)^{3} + 55(-3)^{2} - 56(-3) + 12$ \\
Evaluate the powers: $(-3)^{3} = -27$ and $(-3)^{2} = 9$ \\
$= 25(-27) + 55(9) - 56(-3) + 12$ \\
Multiply out each term: $25(-27) = -675$, $55(9) = 495$ and $-56(-3) = 168$ \\
$= -675 + 495 + 168 + 12$ \\
$= -180 + 168 + 12$ \\
$= -12 + 12$ \\
$= 0$ \\
Since $g(-3) = 0$, $(x + 3)$ is a factor of $g(x)$ \\
(b) Write $g(x) = (x + 3)(25x^{2} + px + q)$ and expand the right-hand side: \\
$(x + 3)(25x^{2} + px + q) = 25x^{3} + px^{2} + qx + 75x^{2} + 3px + 3q$ \\
Collect like terms: \\
$= 25x^{3} + (p + 75)x^{2} + (q + 3p)x + 3q$ \\
Compare coefficients of $x^{2}$: \\
$p + 75 = 55$ \\
$p = -20$ \\
Compare coefficients of $x$: \\
$q + 3p = -56$ \\
$q + 3(-20) = -56$ \\
$q - 60 = -56$ \\
$q = 4$ \\
Check the constant term: $3q = 12$, which matches \\
$g(x) = (x + 3)(25x^{2} - 20x + 4)$ \\
Factorise the quadratic. $25x^{2} = (5x)^{2}$, $4 = (-2)^{2}$ and $2 \times 5x \times (-2) = -20x$, so it is a perfect square: \\
$25x^{2} - 20x + 4 = (5x - 2)^{2}$ \\
$g(x) = (x + 3)(5x - 2)^{2}$ \\
So $a = 5$ and $b = -2$ \\
(c)(i) The roots of $g(x) = 0$ are $x = -3$ and $x = \frac{2}{5}$ (a repeated root) \\
From the sketch, the curve is below the $x$-axis to the left of $x = -3$, above it between $-3$ and $\frac{2}{5}$, and touches it at $x = \frac{2}{5}$ before rising again \\
$g(x) \leq 0$ when $x \leq -3$ or $x = \frac{2}{5}$ \\
(c)(ii) $g(2x) = 0$ when $2x$ is a root of $g$: \\
$2x = -3$ or $2x = \frac{2}{5}$ \\
Divide both by 2: \\
$x = -\frac{3}{2}$ or $x = \frac{1}{5}$

@q 10
@topic Differentiate x^4 from first principles
@marks 4
@question
Let $f(x) = x^{4}$. The definition of the derivative is: \\
$f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}$ \\
$f'(x) = \lim_{h \to 0} \frac{(x + h)^{4} - x^{4}}{h}$ \\
Expand $(x + h)^{4}$ using the binomial coefficients 1, 4, 6, 4, 1: \\
$(x + h)^{4} = x^{4} + 4x^{3}h + 6x^{2}h^{2} + 4xh^{3} + h^{4}$ \\
Subtract $x^{4}$: \\
$(x + h)^{4} - x^{4} = 4x^{3}h + 6x^{2}h^{2} + 4xh^{3} + h^{4}$ \\
Divide every term by $h$ (as $h \neq 0$ before taking the limit): \\
$\frac{(x + h)^{4} - x^{4}}{h} = 4x^{3} + 6x^{2}h + 4xh^{2} + h^{3}$ \\
Let $h \to 0$. Every term containing $h$ goes to 0: \\
$f'(x) = 4x^{3} + 0 + 0 + 0$ \\
$f'(x) = 4x^{3}$ \\
So the derivative of $x^{4}$ is $4x^{3}$, as required

@q 11
@topic Binomial expansion, find a and b
@marks 8
@question
(a) Use the binomial expansion, with the first term $2$, the second term $-\frac{x}{9}$ and $n = 10$: \\
$(2 + y)^{10} = 2^{10} + 10C1 \times 2^{9}y + 10C2 \times 2^{8}y^{2} + ...$ \\
where $y = -\frac{x}{9}$. The coefficients are $10C1 = 10$ and $10C2 = \frac{10 \times 9}{2} = 45$ \\
First term: $2^{10} = 1024$ \\
Second term: $10 \times 2^{9} \times \left( -\frac{x}{9} \right)$ \\
$= 10 \times 512 \times \left( -\frac{x}{9} \right)$ \\
$= -\frac{5120x}{9}$ \\
Third term: $45 \times 2^{8} \times \left( -\frac{x}{9} \right)^{2}$ \\
$= 45 \times 256 \times \frac{x^{2}}{81}$ \\
$= \frac{11520x^{2}}{81}$ \\
Divide top and bottom by 9: \\
$= \frac{1280x^{2}}{9}$ \\
$\left( 2 - \frac{x}{9} \right)^{10} = 1024 - \frac{5120}{9}x + \frac{1280}{9}x^{2} + ...$ \\
(b) Expand $f(x) = (a + bx)\left( 1024 - \frac{5120}{9}x + ... \right)$ \\
The constant term comes only from $a \times 1024$: \\
$1024a = 512$ \\
Divide both sides by 1024: \\
$a = \frac{1}{2}$ \\
(c) The $x$ term comes from $a \times \left( -\frac{5120}{9}x \right)$ and from $bx \times 1024$: \\
$-\frac{5120}{9}a + 1024b = 1024$ \\
Substitute $a = \frac{1}{2}$: \\
$-\frac{2560}{9} + 1024b = 1024$ \\
Add $\frac{2560}{9}$ to both sides: \\
$1024b = 1024 + \frac{2560}{9}$ \\
Write 1024 as $\frac{9216}{9}$: \\
$1024b = \frac{9216}{9} + \frac{2560}{9}$ \\
$1024b = \frac{11776}{9}$ \\
Divide both sides by 1024: \\
$b = \frac{11776}{9216}$ \\
Divide top and bottom by 512: \\
$b = \frac{23}{18}$

@q 12
@topic Trig identity and equation
@marks 8
@question
(a) Start with $11\cos \theta - 10 = -3\sin \theta \tan \theta$ \\
Use $\tan \theta = \frac{\sin \theta}{\cos \theta}$ on the right-hand side: \\
$11\cos \theta - 10 = -3\sin \theta \times \frac{\sin \theta}{\cos \theta}$ \\
$11\cos \theta - 10 = -\frac{3\sin^{2} \theta}{\cos \theta}$ \\
Multiply both sides by $\cos \theta$ (not zero, as $\tan \theta$ is defined) to clear the fraction: \\
$11\cos^{2} \theta - 10\cos \theta = -3\sin^{2} \theta$ \\
Use $\sin^{2} \theta = 1 - \cos^{2} \theta$: \\
$11\cos^{2} \theta - 10\cos \theta = -3\left( 1 - \cos^{2} \theta \right)$ \\
Expand the bracket: \\
$11\cos^{2} \theta - 10\cos \theta = -3 + 3\cos^{2} \theta$ \\
Add 3 to both sides: \\
$11\cos^{2} \theta - 10\cos \theta + 3 = 3\cos^{2} \theta$ \\
Subtract $3\cos^{2} \theta$ from both sides: \\
$11\cos^{2} \theta - 3\cos^{2} \theta - 10\cos \theta + 3 = 0$ \\
$8\cos^{2} \theta - 10\cos \theta + 3 = 0$, as required \\
(b) The equation in (b) is the same as in (a) with $\theta$ replaced by $2x$, so: \\
$8\cos^{2} 2x - 10\cos 2x + 3 = 0$ \\
Let $c = \cos 2x$: \\
$8c^{2} - 10c + 3 = 0$ \\
Factorise. Two numbers that multiply to $8 \times 3 = 24$ and add to $-10$ are $-4$ and $-6$: \\
$8c^{2} - 4c - 6c + 3 = 0$ \\
$4c(2c - 1) - 3(2c - 1) = 0$ \\
$(2c - 1)(4c - 3) = 0$ \\
$c = \frac{1}{2}$ or $c = \frac{3}{4}$ \\
The range $0 \leq x < 90$ degrees means $0 \leq 2x < 180$ degrees \\
Case $\cos 2x = \frac{1}{2}$: \\
$2x = 60$ degrees (the other solution, 300 degrees, is outside the range) \\
$x = 30$ degrees \\
Case $\cos 2x = \frac{3}{4}$: \\
$2x = \cos^{-1}(0.75) = 41.4096...$ degrees (the other solution, 318.59 degrees, is outside the range) \\
$x = 20.7048...$ degrees \\
$x = 30.0$ degrees or $x = 20.7$ degrees (1 dp) \\
(Check $x = 30$: LHS $= 11\cos 60 - 10 = -4.5$ and RHS $= -3\sin 60 \tan 60 = -3 \times \frac{\sqrt{3}}{2} \times \sqrt{3} = -4.5$)

@q 13
@topic Exponential model using logs
@marks 8
@question
(a) Take logs to base 10 of both sides of $V = pq^{t}$: \\
$\log_{10} V = \log_{10} \left( pq^{t} \right)$ \\
Use the product law $\log (ab) = \log a + \log b$: \\
$\log_{10} V = \log_{10} p + \log_{10} q^{t}$ \\
Use the power law $\log a^{n} = n\log a$: \\
$\log_{10} V = \log_{10} p + t\log_{10} q$ \\
Write it in the form of the line, gradient first: \\
$\log_{10} V = (\log_{10} q)t + \log_{10} p$ \\
Compare with $\log_{10} V = 0.04t + 5.2$ \\
The intercept: $\log_{10} p = 5.2$ \\
$p = 10^{5.2}$ \\
$p = 158489.3...$ \\
$p = 158500$ (4 sf) \\
The gradient: $\log_{10} q = 0.04$ \\
$q = 10^{0.04}$ \\
$q = 1.09648...$ \\
$q = 1.096$ (4 sf) \\
(b)(i) $p$ is the value of the painting when $t = 0$, so it is the value on 1st January 1980, which is about GBP 158500 \\
(b)(ii) $q$ is the factor that the value is multiplied by each year. Since $q = 1.096$, the value goes up by about 9.6% every year \\
(c) 1st January 2010 is 30 years after 1st January 1980, so $t = 30$ \\
Substitute into the line, to avoid using rounded values of $p$ and $q$: \\
$\log_{10} V = 0.04 \times 30 + 5.2$ \\
$= 1.2 + 5.2$ \\
$= 6.4$ \\
Use the definition of a log: \\
$V = 10^{6.4}$ \\
$V = 2511886...$ \\
To the nearest hundred thousand pounds, the value is GBP 2500000

@q 14
@topic Circle, line meets circle twice
@marks 9
@question
(a) Complete the square on the $y$ terms. Half of 10 is 5: \\
$y^{2} + 10y = (y + 5)^{2} - 25$ \\
Substitute this into the equation of the circle: \\
$x^{2} + (y + 5)^{2} - 25 + 5 = 0$ \\
$x^{2} + (y + 5)^{2} - 20 = 0$ \\
Add 20 to both sides: \\
$x^{2} + (y + 5)^{2} = 20$ \\
Compare with $(x - a)^{2} + (y - b)^{2} = r^{2}$: \\
(a)(i) The centre is $(0, -5)$ \\
(a)(ii) $r^{2} = 20$, so $r = \sqrt{20}$ \\
$r = \sqrt{4 \times 5}$ \\
$r = 2\sqrt{5}$ \\
(b) Substitute $y = kx$ into $x^{2} + y^{2} + 10y + 5 = 0$: \\
$x^{2} + (kx)^{2} + 10(kx) + 5 = 0$ \\
$x^{2} + k^{2}x^{2} + 10kx + 5 = 0$ \\
Collect the $x^{2}$ terms: \\
$\left( 1 + k^{2} \right)x^{2} + 10kx + 5 = 0$ \\
The line cuts the circle at two distinct points, so this quadratic has two distinct real roots and $b^{2} - 4ac > 0$ \\
Here $a = 1 + k^{2}$, $b = 10k$ and $c = 5$: \\
$(10k)^{2} - 4\left( 1 + k^{2} \right)(5) > 0$ \\
$100k^{2} - 20\left( 1 + k^{2} \right) > 0$ \\
Expand the bracket: \\
$100k^{2} - 20 - 20k^{2} > 0$ \\
$80k^{2} - 20 > 0$ \\
Add 20 to both sides: \\
$80k^{2} > 20$ \\
Divide both sides by 80: \\
$k^{2} > \frac{1}{4}$ \\
Take square roots. $k^{2} > \frac{1}{4}$ is true when $k$ is more than $\frac{1}{2}$ away from 0: \\
$k < -\frac{1}{2}$ or $k > \frac{1}{2}$ \\
(Check: $k = 0$ gives $y = 0$, which is above the circle (its top is at $y = -5 + 2\sqrt{5} = -0.53$), so no intersections. $k = 1$ gives $2x^{2} + 10x + 5 = 0$ with discriminant $100 - 40 = 60 > 0$, so two points)

@q 15
@topic Area with normal and curve
@marks 10
@question
Find the gradient of the curve. Write the equation using negative powers: \\
$y = 32x^{-2} + 4x - 9$ \\
Differentiate, using $\frac{d}{dx}(x^{n}) = nx^{n-1}$: \\
$\frac{dy}{dx} = -64x^{-3} + 4$ \\
At $P$, $x = 4$: \\
$\frac{dy}{dx} = -\frac{64}{4^{3}} + 4$ \\
$= -\frac{64}{64} + 4$ \\
$= -1 + 4$ \\
$= 3$ \\
The normal is perpendicular to the tangent, so its gradient is the negative reciprocal of 3: \\
$m = -\frac{1}{3}$ \\
Equation of $l$, using $y - y_{1} = m(x - x_{1})$ through $P(4, 9)$: \\
$y - 9 = -\frac{1}{3}(x - 4)$ \\
Find where $l$ meets the $x$-axis by putting $y = 0$: \\
$-9 = -\frac{1}{3}(x - 4)$ \\
Multiply both sides by $-3$: \\
$27 = x - 4$ \\
$x = 31$ \\
So $l$ meets the $x$-axis at $(31, 0)$ \\
Split $R$ into two parts at $x = 4$. Part 1 is under the curve from $x = 2$ to $x = 4$. Part 2 is the triangle under $l$ from $P$ down to the $x$-axis \\
Part 1: $\int_{2}^{4} \left( 32x^{-2} + 4x - 9 \right) dx$ \\
Integrate each term using $x^{n} \to \frac{x^{n+1}}{n+1}$: \\
$= \left[ -32x^{-1} + 2x^{2} - 9x \right]_{2}^{4}$ \\
Upper limit $x = 4$: \\
$-\frac{32}{4} + 2(16) - 9(4) = -8 + 32 - 36 = -12$ \\
Lower limit $x = 2$: \\
$-\frac{32}{2} + 2(4) - 9(2) = -16 + 8 - 18 = -26$ \\
Subtract the lower limit from the upper limit: \\
Part 1 $= -12 - (-26)$ \\
$= 14$ \\
Part 2 is a triangle with vertices $(4, 0)$, $(4, 9)$ and $(31, 0)$ \\
Base $= 31 - 4 = 27$ and height $= 9$: \\
Part 2 $= \frac{1}{2} \times 27 \times 9$ \\
$= \frac{243}{2}$ \\
Add the two parts: \\
Area of $R = 14 + \frac{243}{2}$ \\
$= \frac{28}{2} + \frac{243}{2}$ \\
$= \frac{271}{2}$, as required
