@paper AS Core Pure June 2018

@q 1
@topic Inverse matrix and simultaneous equations
@marks 5
@question
Find the determinant by expanding along row 1: \\
$det(M)=2((-2)(-2)-1(5))-1(4(-2)-1(3))+(-3)(4(5)-(-2)(3))$ \\
$=2(4-5)-1(-8-3)-3(20+6)$ \\
$=-2+11-78$ \\
$=-69$ \\
Calculate the cofactors in row 1: \\
$C_{11}=(-2)(-2)-1(5)=-1$ \\
$C_{12}=-[4(-2)-1(3)]=11$ \\
$C_{13}=4(5)-(-2)(3)=26$ \\
Calculate the cofactors in row 2: \\
$C_{21}=-[1(-2)-(-3)(5)]=-13$ \\
$C_{22}=2(-2)-(-3)(3)=5$ \\
$C_{23}=-[2(5)-1(3)]=-7$ \\
Calculate the cofactors in row 3: \\
$C_{31}=1(1)-(-3)(-2)=-5$ \\
$C_{32}=-[2(1)-(-3)(4)]=-14$ \\
$C_{33}=2(-2)-1(4)=-8$ \\
The cofactor matrix has rows $(-1,11,26)$, $(-13,5,-7)$ and $(-5,-14,-8)$ \\
Transpose it to get the adjugate, with rows $(-1,-13,-5)$, $(11,5,-14)$ and $(26,-7,-8)$ \\
Divide the adjugate by the determinant: \\
The inverse rows are $(-1,-13,-5)/(-69)$, $(11,5,-14)/(-69)$, $(26,-7,-8)/(-69)$ \\
So $M^{-1}$ has rows $(1,13,5)/69$, $(-11,-5,14)/69$, $(-26,7,8)/69$ \\
(b) Multiply each row of $M^{-1}$ by $(-4,9,5)$ \\
First coordinate: \\
$x=[1(-4)+13(9)+5(5)]/69$ \\
$=(-4+117+25)/69$ \\
$=138/69$ \\
$=2$ \\
Second coordinate: \\
$y=[(-11)(-4)+(-5)(9)+14(5)]/69$ \\
$=(44-45+70)/69$ \\
$=69/69$ \\
$=1$ \\
Third coordinate: \\
$z=[(-26)(-4)+7(9)+8(5)]/69$ \\
$=(104+63+40)/69$ \\
$=207/69$ \\
$=3$ \\
So the unique solution is $(x,y,z)=(2,1,3)$ \\
(c) Each equation represents a plane in three dimensions \\
The three planes meet at the single point $(2,1,3)$

@q 2
@topic Transformation of cubic roots
@marks 5
@question
Let $w$ be one of the transformed roots, so $w=2z+1$ \\
Rearrange to express $z$ in terms of $w$: \\
$w-1=2z$ \\
$z=(w-1)/2$ \\
Substitute this expression into the original cubic: \\
$((w-1)/2)^3-3((w-1)/2)^2+(w-1)/2+5=0$ \\
Multiply every term by 8 to clear denominators: \\
$(w-1)^3-6(w-1)^2+4(w-1)+40=0$ \\
Expand each power: \\
$w^3-3w^2+3w-1-6(w^2-2w+1)+4w-4+40=0$ \\
Distribute the -6: \\
$w^3-3w^2+3w-1-6w^2+12w-6+4w-4+40=0$ \\
Collect like terms: \\
$w^3-9w^2+19w+29=0$ \\
So $p=-9$, $q=19$ and $r=29$

@q 3
@topic Argand diagram and modulus
@marks 9
@question
(a) Write $z=x+iy$, so the first boundary is a circle: \\
Its centre is $(1,1)$ and its radius is 3 \\
The argument boundaries start from $(2,0)$ on the real axis \\
The ray at argument $\pi/4$ has equation $y=x-2$ and extends rightwards \\
The ray at argument $3\pi/4$ has equation $y=2-x$ and extends leftwards \\
Draw both rays as solid boundaries because the inequalities include equality \\
Shade the region inside the circle and between those rays \\
(b) Write $w=x+iy$ and use the specified ray: \\
$y=x-2$ \\
The circle condition becomes $(x-1)^2+(y-1)^2=9$ \\
Substitute $y=x-2$: \\
$(x-1)^2+(x-3)^2=9$ \\
Expand both squares: \\
$x^2-2x+1+x^2-6x+9=9$ \\
Collect terms: \\
$2x^2-8x+1=0$ \\
Use the quadratic formula: \\
$x=\frac{8\pm\sqrt{64-8}}{4}$ \\
$=\frac{8\pm2\sqrt{14}}{4}$ \\
$=2\pm\frac{\sqrt{14}}{2}$ \\
The ray has argument $\pi/4$, so $y=x-2>0$ \\
Choose $x=2+\frac{\sqrt{14}}{2}$, giving $y=\frac{\sqrt{14}}{2}$ \\
Now find the squared modulus: \\
$|w|^2=x^2+y^2$ \\
$=(2+\frac{\sqrt{14}}{2})^2+(\frac{\sqrt{14}}{2})^2$ \\
$=4+2\sqrt{14}+\frac{14}{4}+\frac{14}{4}$ \\
$=11+2\sqrt{14}$

@q 4
@topic Line and plane geometry
@marks 11
@question
(a) Subtract the coordinates of $A$ from $B$: \\
Direction vector $=(1-(-1),2-(-1),-3-(-3))$ \\
$=(2,3,0)$ \\
A normal vector to the road plane is $(3,-5,-18)$ \\
Find the dot product and lengths: \\
The dot product is $2(3)+3(-5)+0(-18)=6-15+0=-9$ \\
The direction vector has length $\sqrt{2^2+3^2+0^2}=\sqrt{13}$ \\
The normal vector has length $\sqrt{3^2+(-5)^2+(-18)^2}=\sqrt{358}$ \\
For the acute line-plane angle, use the sine of the angle: \\
$\sin\theta=\frac{|-9|}{\sqrt{13}\sqrt{358}}$ \\
$\theta=\sin^{-1}(\frac{9}{\sqrt{4654}})$ degrees \\
$\theta=7.58088\ldots$ degrees \\
$\theta=7.58$ degrees to 3 significant figures \\
(b) Parametrise the pipe through $A$ with direction $(2,3,0)$: \\
$W=(-1+2t,-1+3t,-3)$ \\
The vector from $C=(-1,-2,0)$ to this point is \\
$(2t,1+3t,-3)$ \\
Its squared length is \\
$D^2=(2t)^2+(1+3t)^2+(-3)^2$ \\
Expand: \\
$D^2=4t^2+1+6t+9t^2+9$ \\
$D^2=13t^2+6t+10$ \\
Complete the square to find the minimum: \\
$D^2=13(t^2+\frac{6}{13}t)+10$ \\
$=13((t+\frac{3}{13})^2-\frac{9}{169})+10$ \\
$=13(t+\frac{3}{13})^2+\frac{121}{13}$ \\
This is minimised when $t=-3/13$ \\
The minimum squared length is $121/13$ \\
So the shortest length is $\sqrt{121/13}=11/\sqrt{13}$ metres \\
$=3.050851\ldots$ metres \\
To the nearest centimetre, the pipe length is 3.05 metres

@q 5
@topic Matrices, rotations and invariant points
@marks 10
@question
(a) Compare the first column of $A$ with the standard rotation matrix: \\
The cosine is $-1/2$ and the sine is $\sqrt{3}/2$ \\
This corresponds to a rotation of 120 degrees anticlockwise \\
The matrix has no translation terms, so the centre is the origin \\
(b) Reflection in $y=-x$ swaps the coordinates and changes both signs \\
Thus $B$ has rows $(0,-1)$ and $(-1,0)$ \\
(c) Apply $U$ first and then $V$, so multiply $B$ by $A$: \\
$C=BA$ \\
Row 1 of $C$ is minus row 2 of $A$: \\
$(-\sqrt{3}/2,1/2)$ \\
Row 2 of $C$ is minus row 1 of $A$: \\
$(1/2,\sqrt{3}/2)$ \\
(d) Apply $C$ to $(1,k)$: \\
The image is $(-\sqrt{3}/2+k/2,\ 1/2+\sqrt{3}k/2)$ \\
For invariance, the first coordinate must equal 1: \\
$-\sqrt{3}/2+k/2=1$ \\
$k-\sqrt{3}=2$ \\
$k=2+\sqrt{3}$ \\
Check the second coordinate: \\
$1/2+\sqrt{3}(2+\sqrt{3})/2$ \\
$=(1+2\sqrt{3}+3)/2$ \\
$=2+\sqrt{3}$ \\
This equals $k$, so $(1,2+\sqrt{3})$ is invariant

@q 6
@topic Series and trigonometric sums
@marks 10
@question
(a) Expand the squared term: \\
$(3r-2)^2=9r^2-12r+4$ \\
Sum each term from $r=1$ to $n$: \\
$\sum(3r-2)^2=9\sum r^2-12\sum r+4n$ \\
Use the standard formulae $\sum r^2=n(n+1)(2n+1)/6$ and $\sum r=n(n+1)/2$: \\
$=9\frac{n(n+1)(2n+1)}{6}-12\frac{n(n+1)}{2}+4n$ \\
Factor out $n/2$: \\
$=\frac12n[3(n+1)(2n+1)-12(n+1)+8]$ \\
Expand inside the square brackets: \\
$=\frac12n[6n^2+9n+3-12n-12+8]$ \\
Collect like terms: \\
$=\frac12n(6n^2-3n-1)$ \\
(b) Use the result from part (a) and subtract the first four terms: \\
$\sum_{r=5}^{n}(3r-2)^2=\frac12n(6n^2-3n-1)-\frac12(4)(6(4)^2-3(4)-1)$ \\
Evaluate the first four terms: \\
$\frac12(4)(96-12-1)=2(83)=166$ \\
So the first sum is $\frac12n(6n^2-3n-1)-166$ \\
Evaluate the cosine terms in groups of four: \\
$\sum_{r=1}^{28}r\cos(\frac{r\pi}{2})=0-2+0+4+0-6+0+8+\cdots+0-26+0+28$ \\
Each group contributes 2, and there are 7 groups: \\
$\sum_{r=1}^{28}r\cos(\frac{r\pi}{2})=14$ \\
Substitute both sums into the equation: \\
$\frac12n(6n^2-3n-1)-166+103(14)=3n^3$ \\
Expand the left side: \\
$3n^3-\frac32n^2-\frac12n-166+1442=3n^3$ \\
Cancel $3n^3$ from both sides and simplify: \\
$-\frac32n^2-\frac12n+1276=0$ \\
Multiply by -2: \\
$3n^2+n-2552=0$ \\
Use the quadratic formula: \\
$n=\frac{-1\pm\sqrt{1+4(3)(2552)}}{6}$ \\
$=\frac{-1\pm\sqrt{30625}}{6}$ \\
$=\frac{-1\pm175}{6}$ \\
The roots are $n=29$ and $n=-88/3$ \\
Since $n$ is a positive integer, the required value is $n=29$
@q 7
@topic Complex roots and triangle area
@marks 7
@question
For a cubic with real coefficients, non-real roots occur in conjugate pairs \\
Write the other two roots as $\alpha+\beta i$ and $\alpha-\beta i$ \\
The sum of the three roots is $-1$: \\
$3+(\alpha+\beta i)+(\alpha-\beta i)=-1$ \\
$3+2\alpha=-1$ \\
$2\alpha=-4$ \\
$\alpha=-2$ \\
The two conjugate roots therefore have real part $-2$ \\
Their Argand points are $(-2,\beta)$ and $(-2,-\beta)$, while the point for $z_1$ is $(3,0)$ \\
The vertical base has length $2\beta$ and the perpendicular distance from $(3,0)$ to $x=-2$ is $5$ \\
Use the triangle area: \\
$\frac12(2\beta)(5)=35$ \\
$5\beta=35$ \\
$\beta=7$ \\
So the roots are $3$, $-2+7i$ and $-2-7i$ \\
For a monic cubic, the coefficient $p$ is the sum of pairwise products: \\
$p=3(-2+7i)+3(-2-7i)+(-2+7i)(-2-7i)$ \\
$p=(-6+21i)+(-6-21i)+(4+49)$ \\
$p=-12+53$ \\
$p=41$ \\
The constant term is $q$ and the product of roots is $-q$: \\
$3(-2+7i)(-2-7i)=-q$ \\
$3(4+49)=-q$ \\
$159=-q$ \\
$q=-159$
@q 8
@topic Induction with matrices and divisibility
@marks 12
@question
(i) Let $A=\begin{pmatrix}5&-8\\2&-3\end{pmatrix}$ \\
For $n=1$, the right-hand side is $\begin{pmatrix}4(1)+1&-8(1)\\2(1)&1-4(1)\end{pmatrix}=\begin{pmatrix}5&-8\\2&-3\end{pmatrix}=A$ \\
So the statement is true for $n=1$ \\
Assume it is true for $n=k$: \\
$A^k=\begin{pmatrix}4k+1&-8k\\2k&1-4k\end{pmatrix}$ \\
Then $A^{k+1}=A^kA$ \\
$=\begin{pmatrix}4k+1&-8k\\2k&1-4k\end{pmatrix}\begin{pmatrix}5&-8\\2&-3\end{pmatrix}$ \\
$=\begin{pmatrix}5(4k+1)-16k&-8(4k+1)+24k\\10k+2(1-4k)&-16k-3(1-4k)\end{pmatrix}$ \\
$=\begin{pmatrix}20k+5-16k&-32k-8+24k\\10k+2-8k&-16k-3+12k\end{pmatrix}$ \\
$=\begin{pmatrix}4k+5&-8k-8\\2k+2&-4k-3\end{pmatrix}$ \\
$=\begin{pmatrix}4(k+1)+1&-8(k+1)\\2(k+1)&1-4(k+1)\end{pmatrix}$ \\
This is the required result for $k+1$ \\
The result holds for $n=1$, and truth for $k$ implies truth for $k+1$ \\
Therefore it holds for all positive integers $n$ by induction \\
(ii) Let $f(n)=4^{n+1}+5^{2n-1}$ \\
For $n=1$, $f(1)=4^2+5^1=16+5=21$, which is divisible by 21 \\
Assume $f(k)$ is divisible by 21 \\
$f(k)=4^{k+1}+5^{2k-1}$ \\
Now evaluate the next term: \\
$f(k+1)=4^{k+2}+5^{2k+1}$ \\
Rewrite the powers using $4^{k+1}$ and $5^{2k-1}$: \\
$f(k+1)=4(4^{k+1})+25(5^{2k-1})$ \\
Since $25=4+21$: \\
$f(k+1)=4(4^{k+1})+(4+21)(5^{2k-1})$ \\
$=4(4^{k+1}+5^{2k-1})+21(5^{2k-1})$ \\
$=4f(k)+21(5^{2k-1})$ \\
By the assumption, $4f(k)$ is divisible by 21, and the second term is also divisible by 21 \\
Therefore $f(k+1)$ is divisible by 21 \\
The result holds for $n=1$, and truth for $k$ implies truth for $k+1$ \\
Hence $f(n)$ is divisible by 21 for every positive integer $n$
@q 9
@topic Volumes of revolution and modelling
@marks 11
@question
(a) From the diagram, the curve runs through $(4,14)$ and $(1,18)$ \\
Substitute $(4,14)$ into $y=ax^2+b$: \\
$14=16a+b$ \\
Substitute $(1,18)$: \\
$18=a+b$ \\
Subtract the second equation from the first: \\
$-4=15a$ \\
$a=-\frac{4}{15}$ \\
Substitute into $18=a+b$: \\
$b=18+\frac{4}{15}$ \\
$b=\frac{270}{15}+\frac{4}{15}$ \\
$b=\frac{274}{15}$ \\
(b) The lower cylindrical section has radius 4 cm and height 14 cm: \\
$V_1=\pi(4)^2(14)=224\pi$ \\
The upper cylindrical section has radius 1 cm and height 10 cm: \\
$V_2=\pi(1)^2(10)=10\pi$ \\
For the curved section, $y=-\frac{4}{15}x^2+\frac{274}{15}$ \\
Rearrange to express radius squared in terms of height: \\
$15y=-4x^2+274$ \\
$4x^2=274-15y$ \\
$x^2=\frac{274-15y}{4}$ \\
Rotate the curve around the $y$-axis and integrate from $y=14$ to $y=18$: \\
$V_3=\pi\int_{14}^{18}x^2\,dy$ \\
$=\frac{\pi}{4}\int_{14}^{18}(274-15y)\,dy$ \\
Integrate: \\
$=\frac{\pi}{4}[274y-\frac{15y^2}{2}]_{14}^{18}$ \\
Evaluate the upper endpoint: \\
$274(18)-\frac{15(18)^2}{2}=4932-2430=2502$ \\
Evaluate the lower endpoint: \\
$274(14)-\frac{15(14)^2}{2}=3836-1470=2366$ \\
Subtract: $2502-2366=136$ \\
$V_3=34\pi$ \\
Add the three sections: \\
$V=224\pi+10\pi+34\pi=268\pi$ \\
$V\approx841.95$ cm$^3$ \\
So the model predicts approximately $842$ cm$^3$ \\
(c) One limitation is that this model ignores the thickness of the glass \\
(d) The model gives about $842$ cm$^3$, compared with the labelled $750$ cm$^3$ \\
It overestimates by about $842-750=92$ cm$^3$ \\
This is a noticeable difference, so the model is not very accurate
