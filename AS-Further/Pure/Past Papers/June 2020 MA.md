@paper AS Core Pure June 2020

@q 1
@topic Simultaneous equations and planes
@marks 6
@question
The coefficient matrix is $[k,3,-1;3,-1,1;-16,-k,-k]$ \\
Find its determinant: \\
$det=2k^2+12k-32$ \\
$=2(k+8)(k-2)$ \\
No unique solution requires a zero determinant \\
$2(k+8)(k-2)=0$ \\
Since $k$ is positive, $k=2$ \\
(b) Substitute $k=2$ into the equations: \\
$2x+3y-z=3$ \\
$3x-y+z=-2$ \\
$-16x-2y-2z=2$ \\
Add the first two equations: \\
$5x+2y=1$ \\
The third equation simplifies to the same relation: \\
$-10x-4y+4=2$ \\
$5x+2y=1$ \\
There is one independent equation in three variables, so infinitely many solutions exist \\
(c) Each equation represents a plane \\
The three planes intersect along a common line

@q 2
@topic Complex numbers in polar form
@marks 8
@question
For $z_1=2+3i$, find its modulus: \\
$r=|z_1|=\sqrt{2^2+3^2}$ \\
$=\sqrt{4+9}=\sqrt{13}$ \\
Its argument is in the first quadrant: \\
$\theta=\arctan(3/2)=0.982793\ldots$ radians \\
To 4 significant figures, $\theta=0.9828$ \\
Therefore $z_1=\sqrt{13}(\cos(0.9828)+i\sin(0.9828))$ \\
(b) The modulus and argument of the product give \\
$z_1z_2=39\sqrt2(\cos\frac\pi4+i\sin\frac\pi4)$ \\
Since $\cos\frac\pi4=\sin\frac\pi4=\frac{\sqrt2}{2}$, \\
$z_1z_2=39+39i$ \\
Divide by $z_1$: \\
$z_2=\frac{39+39i}{2+3i}$ \\
Multiply top and bottom by the conjugate $2-3i$: \\
$z_2=\frac{(39+39i)(2-3i)}{(2+3i)(2-3i)}$ \\
The denominator is $4+9=13$ \\
The numerator is $78-117i+78i-117i^2$ \\
$=195-39i$ \\
$z_2=\frac{195-39i}{13}=15-3i$

@q 3
@topic Integration and volume of revolution
@marks 5
@question
The circle has equation $x^2+y^2=r^2$ \\
On the upper semicircle, $y=\sqrt{r^2-x^2}$ \\
The radius of a cross-section perpendicular to the $x$-axis is $y$ \\
The volume is \\
$V=\pi\int_{-r}^{r}y^2\,dx$ \\
Substitute $y^2=r^2-x^2$: \\
$V=\pi\int_{-r}^{r}(r^2-x^2)\,dx$ \\
Integrate: \\
$V=\pi[r^2x-\frac{x^3}{3}]_{-r}^{r}$ \\
Evaluate at $x=r$: $r^3-\frac{r^3}{3}=\frac23r^3$ \\
Evaluate at $x=-r$: $-r^3+\frac{r^3}{3}=-\frac23r^3$ \\
Subtract the lower value: \\
$V=\pi(\frac23r^3+\frac23r^3)$ \\
$V=\frac43\pi r^3$

@q 4
@topic Planes, lines and modelling
@marks 13
@question
(a) Find two direction vectors in the lawn: \\
$LM=M-L=(8,1,1)$ \\
$LN=N-L=(4,3,1)$ \\
Use point $L$ and both directions: \\
$\mathbf{r}=(-2,-3,-1)+\lambda(8,1,1)+\mu(4,3,1)$ \\
(b) Dot the given vector with each plane direction: \\
$(1,2,-10)\cdot(8,1,1)=8+2-10=0$ \\
$(1,2,-10)\cdot(4,3,1)=4+6-10=0$ \\
Thus it is a normal vector to the plane \\
Use $L$ in the Cartesian equation: \\
$x+2y-10z=(-2)+2(-3)-10(-1)=2$ \\
So the plane is $x+2y-10z=2$ \\
(c) The washing line direction is \\
$Q-P=(16,-4,1)$ \\
Hence $\mathbf{r}=(-10,8,2)+\lambda(16,-4,1)$ \\
(d) One limitation is that the lawn may not be perfectly flat \\
(e) Use the point-to-plane distance formula for $R(2,5,2.75)$: \\
$d=\frac{|2+2(5)-10(2.75)-2|}{\sqrt{1^2+2^2+(-10)^2}}$ \\
$=\frac{17.5}{\sqrt{105}}$ \\
$=1.7078\ldots$ m \\
To the nearest centimetre, $d=1.71$ m \\
(f) The model predicts 1.71 m, compared with the actual 1.5 m \\
The difference is 0.21 m, so the model is not very accurate

@q 5
@topic Summation formulae and sequences
@marks 7
@question
The volume of the $r$th block is \\
$r(r+1)(r+2)$ \\
Expand: \\
$r(r+1)(r+2)=r(r^2+3r+2)=r^3+3r^2+2r$ \\
Sum from $r=1$ to $n$: \\
$V=\sum r^3+3\sum r^2+2\sum r$ \\
Use the standard formulae: \\
$V=\frac{n^2(n+1)^2}{4}+\frac{n(n+1)(2n+1)}{2}+n(n+1)$ \\
Factor out $\frac{n(n+1)}4$: \\
$V=\frac{n(n+1)}4[n(n+1)+2(2n+1)+4]$ \\
Simplify the bracket: \\
$= \frac{n(n+1)}4(n^2+5n+6)$ \\
Factor the quadratic: \\
$V=\frac n4(n+1)(n+2)(n+3)$ \\
(b) Equate the formula to the given volume: \\
$\frac n4(n+1)(n+2)(n+3)=n^4+6n^3-11710$ \\
Test the positive integer root $n=10$: \\
$V=\frac{10}{4}(11)(12)(13)=4290$ \\
$10^4+6(10)^3-11710=10000+6000-11710=4290$ \\
Thus the set contains 10 blocks

@q 6
@topic Matrices and linear transformations
@marks 16
@question
(i)(a) Self-inverse means $A^2=I$ \\
$A=[2,a;a-4,b]$ \\
The top-left entry of $A^2$ is \\
$4+a(a-4)$ \\
Set it equal to 1: \\
$4+a^2-4a=1$ \\
$a^2-4a+3=0$ \\
$(a-1)(a-3)=0$ \\
Therefore $a=1$ or $a=3$ \\
The top-right entry is $2a+ab=a(2+b)$ and must equal 0 \\
Since $a\neq0$, $2+b=0$ \\
$b=-2$ \\
(i)(b) Use the smaller value $a=1$: \\
$A=[2,1;-3,-2]$ \\
An invariant point satisfies $A(x,y)=(x,y)$ \\
The first coordinate gives $2x+y=x$ \\
$x+y=0$ \\
$y=-x$ \\
The second coordinate gives the same equation, so the invariant points form the line $y=-x$ \\
(ii)(a) The triangle $T$ has base length 2 and height 3 \\
Its area is $\frac12(2)(3)=3$ \\
The determinant of $P=[p,2p;-1,3p]$ is \\
$det(P)=3p^2+2p$ \\
Area scale factor is $|det(P)|$; since $p>0$, it is $3p^2+2p$ \\
The image area is 15: \\
$3(3p^2+2p)=15$ \\
$3p^2+2p=5$ \\
$3p^2+2p-5=0$ \\
$(3p+5)(p-1)=0$ \\
The positive solution is $p=1$ \\
(ii)(b) The first stretch has matrix $[3,0;0,1]$ \\
The second stretch has matrix $[1,0;0,-2]$ \\
Together they give $Q=[3,0;0,-2]$ \\
(ii)(c) $U$ is followed by $V$, so multiply $Q$ by $P$ \\
At $p=1$, $P=[1,2;-1,3]$ \\
$R=QP=[3,0;0,-2][1,2;-1,3]$ \\
$R=[3,6;2,-6]$

@q 7
@topic Complex roots and polynomial coefficients
@marks 6
@question
The coefficients are real, so the conjugate of $2+3i$ is also a root: \\
$z_2=2-3i$ \\
The square has one vertex in each quadrant; the remaining vertices are $-4+3i$ and $-4-3i$ \\
Thus the roots are $2+3i$, $2-3i$, $-4+3i$, and $-4-3i$ \\
Pair the conjugates to form quadratic factors: \\
$(z-(2+3i))(z-(2-3i))=(z-2)^2+9$ \\
$=z^2-4z+13$ \\
$(z-(-4+3i))(z-(-4-3i))=(z+4)^2+9$ \\
$=z^2+8z+25$ \\
Multiply the factors: \\
$f(z)=(z^2-4z+13)(z^2+8z+25)$ \\
$=z^4+8z^3+25z^2-4z^3-32z^2-100z+13z^2+104z+325$ \\
Collect terms: \\
$f(z)=z^4+4z^3+6z^2+4z+325$ \\
Therefore $a=4$, $b=6$, $c=4$, and $d=325$

@q 8
@topic Induction and divisibility
@marks 6
@question
For $n=1$, \\
$f(1)=2^{1+2}+3^{2(1)+1}$ \\
$=2^3+3^3$ \\
$=8+27$ \\
$=35$ \\
This is divisible by 7, so the base case is true \\
Assume $f(k)=2^{k+2}+3^{2k+1}$ is divisible by 7 \\
Now evaluate the next term: \\
$f(k+1)=2^{k+3}+3^{2k+3}$ \\
Rewrite the powers: \\
$=2(2^{k+2})+9(3^{2k+1})$ \\
Since $9=2+7$: \\
$=2(2^{k+2})+(2+7)(3^{2k+1})$ \\
$=2(2^{k+2}+3^{2k+1})+7(3^{2k+1})$ \\
$=2f(k)+7(3^{2k+1})$ \\
Both terms are divisible by 7 by the assumption and the explicit factor of 7 \\
Therefore $f(k+1)$ is divisible by 7 \\
The statement holds for $n=1$ and truth for $k$ implies truth for $k+1$ \\
Hence it holds for all positive integers $n$ by induction

@q 9
@topic Vieta formulae and reciprocal roots
@marks 6
@question
For $3x^3+x^2-4x+1=0$, Vieta's formulae give \\
$\alpha\beta+\beta\gamma+\gamma\alpha=-4/3$ \\
$\alpha\beta\gamma=-1/3$ \\
(a) Combine the fractions: \\
$\frac1\alpha+\frac1\beta+\frac1\gamma=\frac{\alpha\beta+\beta\gamma+\gamma\alpha}{\alpha\beta\gamma}$ \\
$=\frac{-4/3}{-1/3}$ \\
$=4$ \\
(b) Let a new root be $x=1/\alpha$, so $\alpha=1/x$ \\
Substitute $1/x$ into the original equation: \\
$3(1/x)^3+(1/x)^2-4(1/x)+1=0$ \\
Multiply through by $x^3$: \\
$3+x-4x^2+x^3=0$ \\
Write in descending powers: \\
$x^3-4x^2+x+3=0$

@q 10
@topic Complex loci and intersections
@marks 7
@question
The equation $|z-(3+5i)|=2r$ is a circle with centre $C=(3,5)$ and radius $2r$ \\
The condition $argument(z-2)=3\pi/4$ is a ray starting at $S=(2,0)$ in direction $(-1,1)$ \\
The distance from $C$ to the line through the ray is \\
$\frac{|(-1)(5)-(1)(1)|}{\sqrt{(-1)^2+1^2}}=\frac6{\sqrt2}=3\sqrt2$ \\
To meet the line at two distinct points, the circle radius must be greater: \\
$2r>3\sqrt2$ \\
The projection of $C-S=(1,5)$ onto unit direction $(-1,1)/\sqrt2$ is \\
$\frac{(1,5)\cdot(-1,1)}{\sqrt2}=\frac4{\sqrt2}=2\sqrt2$ \\
The centre's distance from the ray's starting point is \\
$|C-S|=\sqrt{1^2+5^2}=\sqrt{26}$ \\
If the circle radius reaches $\sqrt{26}$, one intersection is the starting point $S$, where the argument is undefined \\
For both intersections to lie strictly forward on the ray, require $2r<\sqrt{26}$ \\
Combine the strict bounds: \\
$3\sqrt2<2r<\sqrt{26}$ \\
$\frac{3\sqrt2}{2}<r<\frac{\sqrt{26}}{2}$
