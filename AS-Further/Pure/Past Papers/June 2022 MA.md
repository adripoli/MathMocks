@paper AS Core Pure June 2022

@q 1
@topic Matrices and simultaneous equations
@marks 7
@question
(a)(i) Multiply $A$ by $B$: \\
$AB=\begin{pmatrix}8+1&12-6&8-5\\14-2&21+12&14+10\\-10-8&-15+48&-10+40\end{pmatrix}$ \\
$AB=\begin{pmatrix}9&6&3\\12&33&24\\-18&33&30\end{pmatrix}$ \\
Calculate $3C$: \\
$3C=\begin{pmatrix}-15&6&3\\12&9&24\\-18&33&6\end{pmatrix}$ \\
Subtract: \\
$AB-3C=\begin{pmatrix}24&0&0\\0&24&0\\0&0&24\end{pmatrix}=24I$ \\
Thus $AB-3C-24I=0$, so $k=-24$ \\
(a)(ii) $B$ is $2\times3$ and $A$ is $3\times2$, so $BA$ is $2\times2$ \\
But $C$ and $I$ are $3\times3$ \\
Matrices of different dimensions cannot be subtracted, so no such $m$ exists \\
(b)(i) The coefficient matrix is $C$, so the system is $C\begin{pmatrix}x\\y\\z\end{pmatrix}=\begin{pmatrix}-14\\3\\7\end{pmatrix}$ \\
Since $C$ is nonsingular, multiply by $C^{-1}$: \\
$\begin{pmatrix}x\\y\\z\end{pmatrix}=C^{-1}\begin{pmatrix}-14\\3\\7\end{pmatrix}$ \\
(b)(ii) Solving gives $x=7/2$, $y=3$, $z=-5/2$

@q 2
@topic Complex numbers and loci
@marks 10
@question
(a) The modulus is $r=\sqrt{(4\sqrt3)^2+(-4)^2}=\sqrt{48+16}=8$ \\
The point is in quadrant IV and $\tan|\theta|=4/(4\sqrt3)=1/\sqrt3$ \\
$\theta=-\pi/6$ \\
$w=8(\cos(-\pi/6)+i\sin(-\pi/6))$ \\
(b)(i) Plot $w=(4\sqrt3,-4)$, approximately $(6.93,-4)$ \\
(b)(ii) The argument is measured from the point $-10i=(0,-10)$ \\
Draw the half-line from $(0,-10)$ in direction $(1,\sqrt3)$ \\
(c) The supporting line is $y=\sqrt3x-10$ \\
Its perpendicular distance from $w$ is $|\sqrt3(4\sqrt3)-(-4)-10|/\sqrt{3+1}$ \\
$=|12+4-10|/2=3$ \\
The perpendicular foot lies on the half-line, so the minimum distance is $3$

@q 3
@topic 3D rotations and vectors
@marks 8
@question
(a) Reflection in $y=0$ changes the sign of $y$: $Q=(8,-3,2)$ \\
(b) Apply the rotation matrix about the $y$-axis: \\
$x'=8\cos120+2\sin120=-4+\sqrt3$ \\
$y'=3$ \\
$z'=-8\sin120+2\cos120=-4\sqrt3-1$ \\
$R=(-4+\sqrt3,3,-4\sqrt3-1)$ \\
(c) $PR=(-12+\sqrt3,0,-3-4\sqrt3)$ \\
$|PR|^2=(-12+\sqrt3)^2+(-3-4\sqrt3)^2=204$ \\
$|PR|=2\sqrt{51}$ \\
(d) $PQ=(0,-6,0)$ \\
$PR\cdot PQ=0$, so the two vectors are perpendicular \\
(e) $|PQ|=6$ \\
The triangle area is $\frac12|PQ||PR|=\frac12(6)(2\sqrt{51})=6\sqrt{51}$

@q 4
@topic Roots and symmetric expressions
@marks 9
@question
Divide the quartic by $3$ and compare coefficients with the monic polynomial \\
$\sum\alpha=-5/3$, $\sum\alpha_i\alpha_j=0$, $\sum\alpha_i\alpha_j\alpha_k=7/3$, and the product of roots is $2$ \\
(i) $\sum\alpha^2=(\sum\alpha)^2-2\sum\alpha_i\alpha_j$ \\
$=(-5/3)^2-2(0)=25/9$ \\
(ii) $\sum 1/\alpha=(\sum\alpha_i\alpha_j\alpha_k)/(\text{product of roots})$ \\
$=(7/3)/2=7/6$ \\
Therefore $2\sum1/\alpha=7/3$ \\
(iii) Expand the product using the symmetric sums: \\
$(3-\alpha)(3-\beta)(3-\gamma)(3-\delta)=3^4-3^3\sum\alpha+3^2\sum\alpha_i\alpha_j-3\sum\alpha_i\alpha_j\alpha_k+$ product of roots \\
$=81-27(-5/3)+9(0)-3(7/3)+2$ \\
$=81+45-7+2=121$

@q 5
@topic Summations and trigonometric sequences
@marks 12
@question
(a) Expand and use the sums of squares, integers, and constants: \\
$\sum(3r^2-17r-25)=3\frac{n(n+1)(2n+1)}6-17\frac{n(n+1)}2-25n$ \\
$=\frac n2[(n+1)(2n+1)-17(n+1)-50]$ \\
$=\frac n2[2n^2+3n+1-17n-17-50]$ \\
$=n(n^2-7n-33)$ \\
Thus $A=7$, $B=33$ \\
(b) Group the terms in threes; tangent has period $180$ degrees: \\
$\tan60+2\tan120+3\tan180=\sqrt3-2\sqrt3+0=-\sqrt3$ \\
Every next block has the same tangent values, and the coefficient offsets cancel, so each block contributes $-\sqrt3$ \\
There are $k$ blocks, giving $-k\sqrt3$ \\
(c) Write $S_n=n(n^2-7n-33)$ \\
$\sum_{r=5}^n(3r^2-17r-25)=S_n-S_4=n(n^2-7n-33)+180$ \\
The sum from $r=1$ to $3n$ of $r\tan(60r)$ is $-n\sqrt3$ \\
The first five terms sum to $-2\sqrt3$, so the sum from $6$ to $3n$ is $-(n-2)\sqrt3$ \\
Substitute and square: \\
$n(n^2-7n-33)+180=45(n-2)^2$ \\
$n^3-52n^2+147n=0$ \\
$n(n-3)(n-49)=0$ \\
Since $n>5$, $n=49$

@q 6
@topic Vectors and parametric paths
@marks 13
@question
(a) At ground level, the $k$-component is zero: \\
$0.84+0.8\lambda-\lambda^2=0$ \\
$\lambda^2-0.8\lambda-0.84=0$ \\
$(\lambda-1.4)(\lambda+0.6)=0$ \\
Since $\lambda\geq0$, $\lambda=1.4$ \\
(b) Substitute into the direction vector: \\
$(9-4.6(1.4),15,0.8-2(1.4))=(2.56,15,-2)$ \\
(c) The vertical component is $-2$ and the horizontal component has magnitude $\sqrt{2.56^2+15^2}$ \\
$\tan\theta=2/\sqrt{2.56^2+15^2}$ \\
$\theta=7.5$ degrees to 1 d.p. \\
(d) In the net plane the $j$-component is zero: \\
$-10.25+15\lambda=0$, so $\lambda=10.25/15=41/60$ \\
Substitute in the path: \\
$x=-4.1+9(41/60)-2.3(41/60)^2\approx0.976$ \\
$z=0.84+0.8(41/60)-(41/60)^2\approx0.920$ \\
Position is approximately $(0.976,0,0.920)$ \\
(e) Since $0.920>0.9$, it passes over the net in the model \\
(f) This conclusion depends on idealisations: the ball is treated as a particle and its trajectory is assumed exact \\
The real ball has size and the path is affected by spin, air resistance, and other factors, so the model cannot guarantee it clears the net

@q 7
@topic Matrix induction
@marks 6
@question
For $n=1$, the left side is $\begin{pmatrix}-5&9\\-4&7\end{pmatrix}$ \\
The right side is $\begin{pmatrix}1-6&9\\-4&1+6\end{pmatrix}=\begin{pmatrix}-5&9\\-4&7\end{pmatrix}$ \\
Thus the statement holds for $n=1$ \\
Assume it holds for $n=k$: \\
$A^k=\begin{pmatrix}1-6k&9k\\-4k&1+6k\end{pmatrix}$, where $A=\begin{pmatrix}-5&9\\-4&7\end{pmatrix}$ \\
Then $A^{k+1}=A^kA$ \\
$=\begin{pmatrix}1-6k&9k\\-4k&1+6k\end{pmatrix}\begin{pmatrix}-5&9\\-4&7\end{pmatrix}$ \\
$=\begin{pmatrix}-5-6k&9+9k\\-4-4k&7+6k\end{pmatrix}$ \\
$=\begin{pmatrix}1-6(k+1)&9(k+1)\\-4(k+1)&1+6(k+1)\end{pmatrix}$ \\
So the statement holds for $k+1$; by induction it is true for every positive integer $n$

@q 8
@topic Modelling and volume of revolution
@marks 15
@question
(a) The diameter is 8 cm, so the radius is $a=4$ cm \\
(b) Model A: $y=4-2\sin(22.5x\text{ degrees})$ \\
The minimum of the sine is $-1$ at $x=-4$, so the maximum radius is $6$ cm \\
The base is at $x=-8$, so the widest point is $4$ cm from the base; its diameter is $12$ cm \\
Model B: $y=4+x(x^2-64)/100$ \\
Differentiate: $dy/dx=(3x^2-64)/100$ \\
Set to zero: $x=\pm8/\sqrt3$; the maximum on the curve is at $x=-8/\sqrt3$ \\
Distance from the base is $8-8/\sqrt3\approx3.38$ cm \\
At this point $y\approx5.97$ cm, so the diameter is approximately $11.9$ cm \\
(c) Model B better matches the measured widest point: about $3.38$ cm from the base and diameter about $12$ cm \\
(d) The vase volume is $V=\pi\int_{-8}^{8}y^2dx$ \\
For Model B, $y=4+(x^3-64x)/100$ \\
The cross term is odd and integrates to zero on $[-8,8]$ \\
$V/\pi=256+\frac1{10000}\int_{-8}^{8}(x^6-128x^4+4096x^2)dx$ \\
$=256+\frac{2}{10000}[x^7/7-128x^5/5+4096x^3/3]_0^8$ \\
$=18897152/65625$ \\
$V=\frac{18897152\pi}{65625}\text{ cm}^3\approx905\text{ cm}^3$ \\
(e) The observed capacity is $1000-100=900\text{ cm}^3$ \\
The model prediction is about $905\text{ cm}^3$, close to the observed capacity, so Model B is suitable
