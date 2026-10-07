@paper P2 Shadow June 2024

@q 1
@topic First and second derivative, d2y = 0
@marks 5
@question
(a)(i) Differentiate each term of $y = 2x^{3} - 5x^{2} - 3x + 8$: \\
$2x^{3} \to 6x^{2}$ \\
$-5x^{2} \to -10x$ \\
$-3x \to -3$ \\
$8 \to 0$ \\
$\frac{dy}{dx} = 6x^{2} - 10x - 3$ \\
(ii) Differentiate again: \\
$\frac{d^{2}y}{dx^{2}} = 12x - 10$ \\
(b) Set the second derivative to zero: \\
$12x - 10 = 0$ \\
Add 10 to both sides: \\
$12x = 10$ \\
Divide by 12: \\
$x = \frac{10}{12}$ \\
Divide the top and bottom by 2: \\
$x = \frac{5}{6}$

@q 2
@topic Arithmetic series, loan repayments
@marks 5
@question
(a) The payments are 720, 705, 690, ... \\
They go down by 15 each month, so $a = 720$ and $d = -15$ \\
The $n$th term is $a + (n - 1)d$ \\
$u_{12} = 720 + (12 - 1)(-15)$ \\
$= 720 + 11 \times (-15)$ \\
$= 720 - 165$ \\
$= 555$ \\
So Jeannie repays GBP 555 in month 12 \\
(b) The total repaid after $N$ payments is the sum of the first $N$ terms: \\
$S_{N} = \frac{N}{2}\{ 2a + (N - 1)d \}$ \\
The loan is GBP 17 640, so $S_{N} = 17640$ \\
$17640 = \frac{N}{2}\{ 2(720) + (N - 1)(-15) \}$ \\
Multiply both sides by 2: \\
$35280 = N\{ 1440 - 15(N - 1) \}$ \\
Expand the inner bracket: $-15(N - 1) = -15N + 15$ \\
$35280 = N(1440 - 15N + 15)$ \\
$35280 = N(1455 - 15N)$ \\
Expand: \\
$35280 = 1455N - 15N^{2}$ \\
Add $15N^{2}$ and subtract $1455N$ from both sides: \\
$15N^{2} - 1455N + 35280 = 0$ \\
Divide every term by 15: \\
$N^{2} - 97N + 2352 = 0$ as required \\
(c) Find two numbers that multiply to 2352 and add to 97: 48 and 49 \\
$48 \times 49 = 2352$ and $48 + 49 = 97$ \\
$(N - 48)(N - 49) = 0$ \\
$N = 48$ or $N = 49$ \\
The 49th payment would be $720 + 48(-15) = 0$, so nothing is paid in month 49 \\
The loan is completely paid back after the 48th payment: \\
$N = 48$ \\
(Check: $S_{48} = 24(1440 - 705) = 24 \times 735 = 17640$)

@q 3
@topic Transformations of a point
@marks 4
@question
(i) $y = f(x - 3)$ moves the curve 3 units to the right \\
Add 3 to the $x$ coordinate: $x = 2 + 3 = 5$ \\
The $y$ coordinate does not change \\
$P$ is mapped to $(5, -1)$ \\
(ii) $y = f(4x)$ squashes the curve towards the $y$ axis by a factor of 4 \\
Divide the $x$ coordinate by 4: $x = \frac{2}{4} = 0.5$ \\
The $y$ coordinate does not change \\
$P$ is mapped to $(0.5, -1)$ \\
(iii) $y = 2f(-x) + 7$ \\
$f(-x)$ reflects in the $y$ axis, so change the sign of the $x$ coordinate: $x = -2$ \\
Multiply the $y$ coordinate by 2: $2 \times (-1) = -2$ \\
Add 7: $-2 + 7 = 5$ \\
$P$ is mapped to $(-2, 5)$

@q 4
@topic Recurrence u(n+1) = k u(n) - 3
@marks 5
@question
(a) Use $u_{n+1} = ku_{n} - 3$ with $u_{1} = 8$ \\
$u_{2} = k(8) - 3$ \\
$u_{2} = 8k - 3$ \\
$u_{3} = k(u_{2}) - 3$ \\
$u_{3} = k(8k - 3) - 3$ \\
We are told $u_{3} = 8$: \\
$k(8k - 3) - 3 = 8$ \\
Expand the bracket: \\
$8k^{2} - 3k - 3 = 8$ \\
Subtract 8 from both sides: \\
$8k^{2} - 3k - 11 = 0$ as required \\
(b)(i) Factorise: \\
$(8k - 11)(k + 1) = 0$ \\
$k = \frac{11}{8}$ or $k = -1$ \\
$k$ is positive, so $k = \frac{11}{8}$ \\
(ii) Put $k = \frac{11}{8}$ back in: \\
$u_{2} = \frac{11}{8} \times 8 - 3$ \\
$= 11 - 3$ \\
$= 8$ \\
$u_{3} = 8$ (given) \\
$\sum_{r=1}^{3} u_{r} = u_{1} + u_{2} + u_{3}$ \\
$= 8 + 8 + 8$ \\
$= 24$

@q 5
@topic Small angle approximation, numeric limit
@marks 3
@question
Small angle approximations: $\tan x \approx x$ and $\cos x \approx 1 - \frac{x^{2}}{2}$ \\
Top: $\tan 3\theta \approx 3\theta$ \\
$\theta \tan 3\theta \approx \theta \times 3\theta$ \\
$\theta \tan 3\theta \approx 3\theta^{2}$ \\
Bottom: $\cos 5\theta \approx 1 - \frac{(5\theta)^{2}}{2}$ \\
$(5\theta)^{2} = 25\theta^{2}$ \\
$\cos 5\theta \approx 1 - \frac{25\theta^{2}}{2}$ \\
$1 - \cos 5\theta \approx 1 - \left( 1 - \frac{25\theta^{2}}{2} \right)$ \\
$1 - \cos 5\theta \approx \frac{25\theta^{2}}{2}$ \\
$\frac{\theta \tan 3\theta}{1 - \cos 5\theta} \approx \frac{3\theta^{2}}{\frac{25\theta^{2}}{2}}$ \\
Dividing by $\frac{25\theta^{2}}{2}$ is multiplying by $\frac{2}{25\theta^{2}}$: \\
$\approx 3\theta^{2} \times \frac{2}{25\theta^{2}}$ \\
Cancel $\theta^{2}$: \\
$\approx \frac{6}{25}$

@q 6
@topic Derivatives equal, iteration
@marks 7
@question
(a)(i) $f(x) = e^{3x^{2} - 2}$ \\
Chain rule: the derivative of $e^{u}$ is $e^{u}\frac{du}{dx}$ \\
$u = 3x^{2} - 2$, so $\frac{du}{dx} = 6x$ \\
$f'(x) = 6xe^{3x^{2} - 2}$ \\
(ii) $g(x) = 6\ln x$ \\
$g'(x) = \frac{6}{x}$ \\
(b) $f'(\alpha) = g'(\alpha)$, so set the derivatives equal: \\
$6xe^{3x^{2} - 2} = \frac{6}{x}$ \\
Divide both sides by 6: \\
$xe^{3x^{2} - 2} = \frac{1}{x}$ \\
Divide both sides by $x$: \\
$e^{3x^{2} - 2} = \frac{1}{x^{2}}$ \\
Take natural logs of both sides: \\
$3x^{2} - 2 = \ln \frac{1}{x^{2}}$ \\
Use $\ln \frac{1}{x^{2}} = \ln x^{-2} = -2\ln x$: \\
$3x^{2} - 2 = -2\ln x$ \\
Add $2\ln x$ to both sides: \\
$3x^{2} + 2\ln x - 2 = 0$ as required \\
(c)(i) $x_{1} = 0.8$ \\
$\ln 0.8 = -0.22314$ \\
$2 - 2\ln 0.8 = 2 + 0.44629$ \\
$= 2.44629$ \\
Divide by 3: $\frac{2.44629}{3} = 0.81543$ \\
$x_{2} = \sqrt{0.81543}$ \\
$x_{2} = 0.9030$ \\
(ii) Keep iterating with the ANS key: \\
$x_{3} = 0.85713$ \\
$x_{4} = 0.87718$ \\
$x_{5} = 0.86835$ \\
$x_{6} = 0.87222$ \\
$x_{7} = 0.87052$ \\
$x_{8} = 0.87127$ \\
$x_{9} = 0.87094$ \\
$x_{10} = 0.87108$ \\
$x_{11} = 0.87102$ \\
The values settle at 0.8710 \\
$\alpha = 0.8710$ to 4 decimal places

@q 7
@topic Line through A and B, point P with ratio
@marks 5
@question
(a) $\text{AB} = \text{OB} - \text{OA}$ \\
$\text{AB} = (2\mathbf{i} + 5\mathbf{j} + 7\mathbf{k}) - (5\mathbf{i} - 4\mathbf{j} + \mathbf{k})$ \\
$\mathbf{i}$ terms: $2 - 5 = -3$ \\
$\mathbf{j}$ terms: $5 - (-4) = 9$ \\
$\mathbf{k}$ terms: $7 - 1 = 6$ \\
$\text{AB} = -3\mathbf{i} + 9\mathbf{j} + 6\mathbf{k}$ \\
(b) $P$ lies on the line $l$, so $\text{AP} = \lambda\text{AB}$ for some number $\lambda$ \\
$\text{BP} = \text{AP} - \text{AB}$ \\
$\text{BP} = \lambda\text{AB} - \text{AB}$ \\
$\text{BP} = (\lambda - 1)\text{AB}$ \\
$|\text{BP}| = 2|\text{AP}|$ \\
$|\lambda - 1||\text{AB}| = 2|\lambda||\text{AB}|$ \\
Divide by $|\text{AB}|$: \\
$|\lambda - 1| = 2|\lambda|$ \\
This gives two cases \\
Case 1: $\lambda - 1 = 2\lambda$ \\
Subtract $\lambda$: \\
$\lambda = -1$ \\
Case 2: $\lambda - 1 = -2\lambda$ \\
Add $2\lambda$ and add 1: \\
$3\lambda = 1$ \\
$\lambda = \frac{1}{3}$ \\
Find $\text{OP} = \text{OA} + \lambda\text{AB}$ \\
For $\lambda = -1$: $\text{OP} = (5\mathbf{i} - 4\mathbf{j} + \mathbf{k}) - (-3\mathbf{i} + 9\mathbf{j} + 6\mathbf{k})$ \\
$\mathbf{i}$ terms: $5 + 3 = 8$ \\
$\mathbf{j}$ terms: $-4 - 9 = -13$ \\
$\mathbf{k}$ terms: $1 - 6 = -5$ \\
$\text{OP} = 8\mathbf{i} - 13\mathbf{j} - 5\mathbf{k}$ \\
For $\lambda = \frac{1}{3}$: $\text{OP} = (5\mathbf{i} - 4\mathbf{j} + \mathbf{k}) + \frac{1}{3}(-3\mathbf{i} + 9\mathbf{j} + 6\mathbf{k})$ \\
$\frac{1}{3}(-3\mathbf{i} + 9\mathbf{j} + 6\mathbf{k}) = -\mathbf{i} + 3\mathbf{j} + 2\mathbf{k}$ \\
$\mathbf{i}$ terms: $5 - 1 = 4$ \\
$\mathbf{j}$ terms: $-4 + 3 = -1$ \\
$\mathbf{k}$ terms: $1 + 2 = 3$ \\
$\text{OP} = 4\mathbf{i} - \mathbf{j} + 3\mathbf{k}$ \\
The possible position vectors are $8\mathbf{i} - 13\mathbf{j} - 5\mathbf{k}$ and $4\mathbf{i} - \mathbf{j} + 3\mathbf{k}$

@q 8
@topic Prove sec identity, solve equation
@marks 7
@question
(a) Start with the left hand side and add the two fractions \\
Common denominator: $(\sec \theta - 1)(\sec \theta + 1)$ \\
$\frac{1}{\sec \theta - 1} + \frac{1}{\sec \theta + 1} = \frac{(\sec \theta + 1) + (\sec \theta - 1)}{(\sec \theta - 1)(\sec \theta + 1)}$ \\
Simplify the top: $\sec \theta + 1 + \sec \theta - 1 = 2\sec \theta$ \\
Simplify the bottom (difference of two squares): $(\sec \theta - 1)(\sec \theta + 1) = \sec^{2} \theta - 1$ \\
$= \frac{2\sec \theta}{\sec^{2} \theta - 1}$ \\
Use $\sec^{2} \theta - 1 = \tan^{2} \theta$: \\
$= \frac{2\sec \theta}{\tan^{2} \theta}$ \\
Write in terms of sine and cosine: $\sec \theta = \frac{1}{\cos \theta}$ and $\tan^{2} \theta = \frac{\sin^{2} \theta}{\cos^{2} \theta}$ \\
$= \frac{2}{\cos \theta} \times \frac{\cos^{2} \theta}{\sin^{2} \theta}$ \\
Cancel one $\cos \theta$: \\
$= \frac{2\cos \theta}{\sin^{2} \theta}$ \\
Split $\sin^{2} \theta$ into $\sin \theta \times \sin \theta$: \\
$= 2 \times \frac{\cos \theta}{\sin \theta} \times \frac{1}{\sin \theta}$ \\
Use $\cot \theta = \frac{\cos \theta}{\sin \theta}$ and $\text{cosec } \theta = \frac{1}{\sin \theta}$: \\
$= 2\cot \theta \text{cosec } \theta$ as required \\
(b) The left hand side is the same as in part (a) with $\theta = 2x$ \\
So the equation becomes $2\cot 2x \text{cosec } 2x = \tan 2x \text{cosec } 2x$ \\
Subtract the right side from both sides: \\
$2\cot 2x \text{cosec } 2x - \tan 2x \text{cosec } 2x = 0$ \\
Factorise out $\text{cosec } 2x$: \\
$\text{cosec } 2x(2\cot 2x - \tan 2x) = 0$ \\
$\text{cosec } 2x = \frac{1}{\sin 2x}$ is never zero, so \\
$2\cot 2x - \tan 2x = 0$ \\
Add $\tan 2x$ to both sides: \\
$2\cot 2x = \tan 2x$ \\
Write $\cot 2x = \frac{1}{\tan 2x}$: \\
$\frac{2}{\tan 2x} = \tan 2x$ \\
Multiply both sides by $\tan 2x$: \\
$2 = \tan^{2} 2x$ \\
Square root both sides: \\
$\tan 2x = \pm \sqrt{2}$ \\
For $0 < x < 90$ degrees, $0 < 2x < 180$ degrees \\
$\tan 2x = \sqrt{2}$: $2x = 54.74$ degrees \\
$\tan 2x = -\sqrt{2}$: $2x = 180 - 54.74 = 125.26$ degrees \\
Divide each by 2: \\
$x = 27.37$ or $x = 62.63$ \\
$x = 27.4$ or $62.6$ degrees to 1 decimal place \\
(Check: $\tan^{2}(54.74) = 2$ and $\tan^{2}(125.26) = 2$)

@q 9
@topic Quadratic model, thrown ball
@marks 7
@question
(a) Let $H = ax^{2} + bx + c$ \\
At $A$, $x = 0$ and $H = 1.8$: \\
$1.8 = a(0) + b(0) + c$ \\
$c = 1.8$ \\
$H = ax^{2} + bx + 1.8$ \\
The maximum is at $x = 7$, so $\frac{dH}{dx} = 0$ there: \\
$\frac{dH}{dx} = 2ax + b$ \\
$2a(7) + b = 0$ \\
Equation 1: $14a + b = 0$ \\
At $B$, $x = 18$ and $H = 0.9$: \\
$0.9 = a(18)^{2} + b(18) + 1.8$ \\
$18^{2} = 324$ \\
$0.9 = 324a + 18b + 1.8$ \\
Subtract 1.8 from both sides: \\
Equation 2: $324a + 18b = -0.9$ \\
From equation 1: $b = -14a$ \\
Substitute into equation 2: \\
$324a + 18(-14a) = -0.9$ \\
$18 \times 14 = 252$ \\
$324a - 252a = -0.9$ \\
$72a = -0.9$ \\
Divide by 72: \\
$a = -0.0125$ \\
$b = -14 \times (-0.0125)$ \\
$b = 0.175$ \\
$H = -0.0125x^{2} + 0.175x + 1.8$ \\
(Check at $x = 18$: $-0.0125(324) + 0.175(18) + 1.8 = -4.05 + 3.15 + 1.8 = 0.9$) \\
(b) One limitation: the ball is unlikely to follow a perfect quadratic (parabolic) path, since wind or air resistance would affect it \\
(c) Chandler is at $x = 12$ \\
$H = -0.0125(12)^{2} + 0.175(12) + 1.8$ \\
$12^{2} = 144$ \\
$-0.0125 \times 144 = -1.8$ \\
$0.175 \times 12 = 2.1$ \\
$H = -1.8 + 2.1 + 1.8$ \\
$H = 2.1$ m \\
Chandler can only catch the ball if it is less than 2 m above the ground \\
$2.1 > 2$, so Chandler would not be able to catch the ball

@q 10
@topic Parametric tangent, max height
@marks 6
@question
(a) Find the value of $t$ at $P(16, 11)$ \\
$x = (t + 5)^{2} = 16$ \\
$t + 5 = \pm 4$ \\
For $-3 \leq t \leq 2$ we have $2 \leq t + 5 \leq 7$, so $t + 5$ is positive: \\
$t + 5 = 4$ \\
$t = -1$ \\
Check with $y$: $y = 10 - (-1)^{3} = 10 + 1 = 11$ \\
Differentiate: \\
$\frac{dx}{dt} = 2(t + 5)$ \\
$\frac{dy}{dt} = -3t^{2}$ \\
$\frac{dy}{dx} = \frac{dy}{dt} \div \frac{dx}{dt}$ \\
$\frac{dy}{dx} = \frac{-3t^{2}}{2(t + 5)}$ \\
At $t = -1$: \\
$-3(-1)^{2} = -3$ \\
$2(-1 + 5) = 8$ \\
$\frac{dy}{dx} = -\frac{3}{8}$ \\
The tangent has gradient $-\frac{3}{8}$ and passes through $(16, 11)$: \\
$y - 11 = -\frac{3}{8}(x - 16)$ \\
Multiply both sides by 8: \\
$8y - 88 = -3(x - 16)$ \\
Expand the bracket: \\
$8y - 88 = -3x + 48$ \\
Add $3x$ and add 88 to both sides: \\
$3x + 8y = 136$ as required \\
(b) The height is $y = 10 - t^{3}$ for $-3 \leq t \leq 2$ \\
$y$ is largest when $t^{3}$ is smallest, which is at $t = -3$ \\
$y = 10 - (-3)^{3}$ \\
$(-3)^{3} = -27$ \\
$y = 10 + 27$ \\
$y = 37$ \\
The maximum height is 37 m

@q 11
@topic Integration by parts twice, exact area
@marks 5
@question
The area of $R$ is $\int_{0}^{1} 5x^{2}e^{-4x} dx$ \\
Use integration by parts with $u = 5x^{2}$ and $\frac{dv}{dx} = e^{-4x}$ \\
$\frac{du}{dx} = 10x$ \\
$v = -\frac{1}{4}e^{-4x}$ \\
$\int 5x^{2}e^{-4x} dx = 5x^{2}\left( -\frac{1}{4}e^{-4x} \right) - \int 10x\left( -\frac{1}{4}e^{-4x} \right) dx$ \\
$= -\frac{5x^{2}}{4}e^{-4x} + \int \frac{5x}{2}e^{-4x} dx$ \\
Use parts again on $\int \frac{5x}{2}e^{-4x} dx$ with $u = \frac{5x}{2}$ and $\frac{dv}{dx} = e^{-4x}$ \\
$\frac{du}{dx} = \frac{5}{2}$ \\
$v = -\frac{1}{4}e^{-4x}$ \\
$\int \frac{5x}{2}e^{-4x} dx = \frac{5x}{2}\left( -\frac{1}{4}e^{-4x} \right) - \int \frac{5}{2}\left( -\frac{1}{4}e^{-4x} \right) dx$ \\
$= -\frac{5x}{8}e^{-4x} + \int \frac{5}{8}e^{-4x} dx$ \\
$\int \frac{5}{8}e^{-4x} dx = \frac{5}{8} \times \left( -\frac{1}{4}e^{-4x} \right)$ \\
$= -\frac{5}{32}e^{-4x}$ \\
Put it all together: \\
$\int 5x^{2}e^{-4x} dx = -\frac{5x^{2}}{4}e^{-4x} - \frac{5x}{8}e^{-4x} - \frac{5}{32}e^{-4x}$ \\
Upper limit $x = 1$: \\
$-\frac{5}{4}e^{-4} - \frac{5}{8}e^{-4} - \frac{5}{32}e^{-4}$ \\
Write over the denominator 32: \\
$-\frac{40}{32}e^{-4} - \frac{20}{32}e^{-4} - \frac{5}{32}e^{-4}$ \\
$= -\frac{65}{32}e^{-4}$ \\
Lower limit $x = 0$: \\
$-0 - 0 - \frac{5}{32}e^{0}$ \\
$e^{0} = 1$ \\
$= -\frac{5}{32}$ \\
Subtract the lower limit from the upper limit: \\
$-\frac{65}{32}e^{-4} - \left( -\frac{5}{32} \right)$ \\
$= -\frac{65}{32}e^{-4} + \frac{5}{32}$ \\
Area of $R = \frac{5}{32} - \frac{65}{32}e^{-4}$ \\
So $A = \frac{5}{32}$ and $B = -\frac{65}{32}$ \\
(Check: $0.15625 - 2.03125 \times 0.018316 = 0.15625 - 0.037205 = 0.11905$, which matches a numerical integration)

@q 12
@topic Partial fractions, logistic bacteria model
@marks 12
@question
(a) Write $\frac{1}{N(16 - N)} = \frac{P}{N} + \frac{Q}{16 - N}$ \\
Multiply both sides by $N(16 - N)$: \\
$1 = P(16 - N) + QN$ \\
Put $N = 0$ (this removes the $Q$ term): \\
$1 = P(16)$ \\
$P = \frac{1}{16}$ \\
Put $N = 16$ (this removes the $P$ term): \\
$1 = Q(16)$ \\
$Q = \frac{1}{16}$ \\
$\frac{1}{N(16 - N)} = \frac{1}{16N} + \frac{1}{16(16 - N)}$ \\
(b) Separate the variables in $\frac{dN}{dt} = \frac{1}{5}N(16 - N)$: \\
$\frac{1}{N(16 - N)} dN = \frac{1}{5} dt$ \\
Use part (a) on the left side: \\
$\left( \frac{1}{16N} + \frac{1}{16(16 - N)} \right) dN = \frac{1}{5} dt$ \\
Integrate both sides: \\
$\int \frac{1}{16N} dN = \frac{1}{16}\ln N$ \\
$\int \frac{1}{16(16 - N)} dN = -\frac{1}{16}\ln (16 - N)$ \\
(the minus sign comes from the $-N$ inside the bracket) \\
$\frac{1}{16}\ln N - \frac{1}{16}\ln (16 - N) = \frac{1}{5}t + c$ \\
Initially $t = 0$ and $N = 12$: \\
$\frac{1}{16}\ln 12 - \frac{1}{16}\ln (16 - 12) = 0 + c$ \\
$c = \frac{1}{16}(\ln 12 - \ln 4)$ \\
Use $\ln a - \ln b = \ln \frac{a}{b}$: \\
$c = \frac{1}{16}\ln 3$ \\
$\frac{1}{16}\ln N - \frac{1}{16}\ln (16 - N) = \frac{1}{5}t + \frac{1}{16}\ln 3$ \\
Put $N = 14$: \\
$\frac{1}{16}\ln 14 - \frac{1}{16}\ln 2 = \frac{1}{5}t + \frac{1}{16}\ln 3$ \\
Combine the logs on the left: $\ln 14 - \ln 2 = \ln 7$ \\
$\frac{1}{16}\ln 7 = \frac{1}{5}t + \frac{1}{16}\ln 3$ \\
Subtract $\frac{1}{16}\ln 3$: \\
$\frac{1}{5}t = \frac{1}{16}\ln 7 - \frac{1}{16}\ln 3$ \\
$\frac{1}{5}t = \frac{1}{16}\ln \frac{7}{3}$ \\
Multiply by 5: \\
$t = \frac{5}{16}\ln \frac{7}{3}$ \\
$\ln \frac{7}{3} = 0.84730$ \\
$t = 0.3125 \times 0.84730$ \\
$t = 0.26478$ hours \\
The question asks for minutes, so multiply by 60: \\
$0.26478 \times 60 = 15.887$ minutes \\
The time is about 16 minutes, or exactly $\frac{75}{4}\ln \frac{7}{3}$ minutes \\
(Check: $60 \times \frac{5}{16} = \frac{300}{16} = \frac{75}{4}$) \\
(c) Start from the equation before putting in $N = 14$: \\
$\frac{1}{16}\ln N - \frac{1}{16}\ln (16 - N) = \frac{1}{5}t + \frac{1}{16}\ln 3$ \\
Multiply every term by 16: \\
$\ln N - \ln (16 - N) = \frac{16}{5}t + \ln 3$ \\
$\frac{16}{5} = 3.2$ \\
$\ln N - \ln (16 - N) = 3.2t + \ln 3$ \\
Subtract $\ln 3$ from both sides: \\
$\ln N - \ln (16 - N) - \ln 3 = 3.2t$ \\
Combine the logs: \\
$\ln \frac{N}{3(16 - N)} = 3.2t$ \\
Take exponentials of both sides: \\
$\frac{N}{3(16 - N)} = e^{3.2t}$ \\
Multiply both sides by $3(16 - N)$: \\
$N = 3e^{3.2t}(16 - N)$ \\
Expand the bracket: \\
$N = 48e^{3.2t} - 3Ne^{3.2t}$ \\
Add $3Ne^{3.2t}$ to both sides: \\
$N + 3Ne^{3.2t} = 48e^{3.2t}$ \\
Factorise out $N$: \\
$N(1 + 3e^{3.2t}) = 48e^{3.2t}$ \\
Divide by $(1 + 3e^{3.2t})$: \\
$N = \frac{48e^{3.2t}}{1 + 3e^{3.2t}}$ \\
Divide the top and bottom by $e^{3.2t}$: \\
$N = \frac{48}{e^{-3.2t} + 3}$ \\
So $A = 48$, $B = 3$ and $k = 3.2$ \\
(d) As $t$ gets very large, $e^{-3.2t}$ gets close to 0 \\
$N \to \frac{48}{0 + 3}$ \\
$N \to 16$ \\
The upper limit is $L = 16$ million, since $e^{-3.2t} \to 0$ as $t \to \infty$

@q 13
@topic Exponential model from log graph, rabbits
@marks 9
@question
(a) Take logs (base 10) of $P = ab^{t}$: \\
$\log_{10} P = \log_{10}(ab^{t})$ \\
$\log_{10} P = \log_{10} a + \log_{10} b^{t}$ \\
$\log_{10} P = \log_{10} a + t\log_{10} b$ \\
This is a straight line of $\log_{10} P$ against $t$ \\
Gradient $= \log_{10} b = 0.0061$ \\
Intercept $= \log_{10} a = 0.76$ \\
Raise 10 to the power of each side: \\
$b = 10^{0.0061}$ \\
$b = 1.0141$ \\
$b = 1.014$ to 3 decimal places \\
$a = 10^{0.76}$ \\
$a = 5.7544$ \\
$a = 5.754$ to 3 decimal places \\
(b)(i) $a$ is the value of $P$ when $t = 0$ \\
So $a = 5.754$ is the world rabbit population, in millions, in 2010 \\
(ii) $b$ is the number that $P$ is multiplied by each year \\
$b = 1.014$ means the world rabbit population grows by a factor of 1.014 each year, which is an increase of about 1.4 percent a year \\
(c) 2045 is 35 years after 2010, so $t = 35$ \\
$P = 5.754 \times 1.014^{35}$ \\
Or use logs: $\log_{10} P = 0.76 + 35 \times 0.0061$ \\
$35 \times 0.0061 = 0.2135$ \\
$\log_{10} P = 0.9735$ \\
$P = 10^{0.9735}$ \\
$P = 9.41$ \\
The estimate is about 9 million rabbits \\
(d) The model was built from data for 2010 to 2015 only \\
2045 is 30 years beyond that data, so the estimate is an extrapolation and cannot be trusted \\
It is not reliable

@q 14
@topic Circles, centre, radius, two intersections
@marks 8
@question
(a) Complete the square on the $x$ terms and the $y$ terms: \\
$x^{2} - 4x = (x - 2)^{2} - 4$ \\
$y^{2} + 16y = (y + 8)^{2} - 64$ \\
$(x - 2)^{2} - 4 + (y + 8)^{2} - 64 + 19 = 0$ \\
Collect the numbers: $-4 - 64 + 19 = -49$ \\
$(x - 2)^{2} + (y + 8)^{2} - 49 = 0$ \\
Add 49 to both sides: \\
$(x - 2)^{2} + (y + 8)^{2} = 49$ \\
(i) The centre of $C_{1}$ is $(2, -8)$ \\
(ii) $r^{2} = 49$, so the radius of $C_{1}$ is $7$ \\
(b) Find the distance between the two centres $(2, -8)$ and $(-1, 3)$: \\
$d = \sqrt{(2 - (-1))^{2} + (-8 - 3)^{2}}$ \\
$= \sqrt{3^{2} + (-11)^{2}}$ \\
$= \sqrt{9 + 121}$ \\
$= \sqrt{130}$ \\
$\sqrt{130} = 11.40$ \\
Two circles meet at 2 distinct points when the distance between centres is less than the sum of the radii and more than the difference of the radii \\
Sum of radii: $7 + k$ \\
$\sqrt{130} < 7 + k$ \\
Subtract 7: \\
$k > \sqrt{130} - 7$ \\
Difference of radii: $|k - 7|$ \\
$|k - 7| < \sqrt{130}$ \\
This means $-\sqrt{130} < k - 7 < \sqrt{130}$ \\
Add 7: \\
$7 - \sqrt{130} < k < 7 + \sqrt{130}$ \\
$7 - \sqrt{130}$ is negative, and $k$ is a radius so it is positive, so only the upper limit matters here: \\
$k < \sqrt{130} + 7$ \\
Putting the two conditions together: \\
$\sqrt{130} - 7 < k < \sqrt{130} + 7$ \\
In numbers, $4.40 < k < 18.40$ \\
$\{ k : \sqrt{130} - 7 < k < \sqrt{130} + 7 \}$

@q 15
@topic Implicit diff, normal, no return
@marks 12
@question
(a) Differentiate $(x + y)^{3} = 2x^{2} - 2y - 1$ with respect to $x$ \\
Left side (chain rule): $3(x + y)^{2} \times \left( 1 + \frac{dy}{dx} \right)$ \\
Right side: $4x - 2\frac{dy}{dx}$ \\
$3(x + y)^{2}\left( 1 + \frac{dy}{dx} \right) = 4x - 2\frac{dy}{dx}$ \\
Expand the bracket: \\
$3(x + y)^{2} + 3(x + y)^{2}\frac{dy}{dx} = 4x - 2\frac{dy}{dx}$ \\
Collect the $\frac{dy}{dx}$ terms on the left and the others on the right: \\
$3(x + y)^{2}\frac{dy}{dx} + 2\frac{dy}{dx} = 4x - 3(x + y)^{2}$ \\
Factorise out $\frac{dy}{dx}$: \\
$\left( 3(x + y)^{2} + 2 \right)\frac{dy}{dx} = 4x - 3(x + y)^{2}$ \\
Divide by $\left( 3(x + y)^{2} + 2 \right)$: \\
$\frac{dy}{dx} = \frac{4x - 3(x + y)^{2}}{3(x + y)^{2} + 2}$ \\
(b) First check that $P(1, 0)$ is on $C$: $(1 + 0)^{3} = 1$ and $2(1) - 0 - 1 = 1$ \\
At $P$, $x = 1$ and $y = 0$: \\
$x + y = 1$ \\
Top: $4(1) - 3(1)^{2} = 4 - 3 = 1$ \\
Bottom: $3(1)^{2} + 2 = 5$ \\
$\frac{dy}{dx} = \frac{1}{5}$ \\
The normal is perpendicular to the tangent, so its gradient is the negative reciprocal: \\
Gradient of the normal $= -5$ \\
$y - 0 = -5(x - 1)$ \\
Expand the bracket: \\
$y = -5x + 5$ as required \\
(c) Substitute $y = -5x + 5$ into the equation of $C$ to find where the normal meets $C$ \\
$x + y = x + (-5x + 5) = 5 - 4x$ \\
Left side: $(5 - 4x)^{3}$ \\
Expand: $(5 - 4x)^{3} = 125 - 3(25)(4x) + 3(5)(16x^{2}) - 64x^{3}$ \\
$= 125 - 300x + 240x^{2} - 64x^{3}$ \\
Right side: $2x^{2} - 2(-5x + 5) - 1$ \\
$= 2x^{2} + 10x - 10 - 1$ \\
$= 2x^{2} + 10x - 11$ \\
Set them equal: \\
$125 - 300x + 240x^{2} - 64x^{3} = 2x^{2} + 10x - 11$ \\
Move everything to the right side, so that the $x^{3}$ term is positive: \\
$0 = 64x^{3} + 2x^{2} - 240x^{2} + 10x + 300x - 11 - 125$ \\
Collect like terms: \\
$64x^{3} - 238x^{2} + 310x - 136 = 0$ \\
Divide every term by 2: \\
$32x^{3} - 119x^{2} + 155x - 68 = 0$ \\
We know $x = 1$ is a solution (the point $P$), so $(x - 1)$ is a factor \\
Divide: $32x^{3} - 119x^{2} + 155x - 68 = (x - 1)(32x^{2} + bx + 68)$ \\
Expand: $(x - 1)(32x^{2} + bx + 68) = 32x^{3} + (b - 32)x^{2} + (68 - b)x - 68$ \\
Compare the $x^{2}$ terms: $b - 32 = -119$ \\
$b = -87$ \\
(Check the $x$ terms: $68 - b = 68 + 87 = 155$, which matches) \\
$(x - 1)(32x^{2} - 87x + 68) = 0$ \\
The normal meets $C$ again only if $32x^{2} - 87x + 68 = 0$ has real roots \\
Find the discriminant, with $a = 32$, $b = -87$, $c = 68$: \\
$b^{2} - 4ac = (-87)^{2} - 4(32)(68)$ \\
$(-87)^{2} = 7569$ \\
$4 \times 32 \times 68 = 8704$ \\
$b^{2} - 4ac = 7569 - 8704$ \\
$b^{2} - 4ac = -1135$ \\
The discriminant is negative, so $32x^{2} - 87x + 68 = 0$ has no real roots \\
The only intersection is $x = 1$, which is $P$ \\
So the normal to $C$ at $P$ does not meet $C$ again
