@paper AS Core Pure June 2021

@q 1
@topic Matrix transformations
@marks 7
@question
(a)(i) The matrix $\begin{pmatrix}0&-1\\1&0\end{pmatrix}$ maps $(x,y)$ to $(-y,x)$ \\
This is a rotation of $90$ degrees anticlockwise about the origin \\
(a)(ii) The matrix $\begin{pmatrix}1&0\\0&3\end{pmatrix}$ maps $(x,y)$ to $(x,3y)$ \\
The $x$-coordinate is unchanged and the $y$-coordinate is multiplied by $3$ \\
This is a stretch with scale factor $3$ parallel to the $y$-axis \\
(b) The transformation $P$ is followed by $Q$, so multiply in the order $QP$: \\
$R=QP=\begin{pmatrix}1&0\\0&3\end{pmatrix}\begin{pmatrix}0&-1\\1&0\end{pmatrix}$ \\
$R=\begin{pmatrix}0&-1\\3&0\end{pmatrix}$ \\
(c)(i) $det(R)=0(0)-(-1)(3)=3$ \\
(c)(ii) The absolute determinant is the area scale factor \\
Therefore areas are multiplied by $|3|=3$

@q 2
@topic Transformation of cubic roots
@marks 5
@question
Let $w=3x-2$, so the inverse relation is $x=\frac{w+2}{3}$ \\
Substitute $x=\frac{w+2}{3}$ into the original equation: \\
$9\left(\frac{w+2}{3}\right)^3-5\left(\frac{w+2}{3}\right)^2+4\left(\frac{w+2}{3}\right)+7=0$ \\
Simplify each term: \\
$\frac{(w+2)^3}{3}-\frac{5(w+2)^2}{9}+\frac{4(w+2)}{3}+7=0$ \\
Multiply by $9$: \\
$3(w+2)^3-5(w+2)^2+12(w+2)+63=0$ \\
Expand: \\
$3(w^3+6w^2+12w+8)-5(w^2+4w+4)+12w+24+63=0$ \\
Collect like terms: \\
$3w^3+18w^2+36w+24-5w^2-20w-20+12w+87=0$ \\
$3w^3+13w^2+28w+91=0$

@q 3
@topic Summation and algebraic equations
@marks 9
@question
(a) Expand the summand: \\
$(5r-2)^2=25r^2-20r+4$ \\
Sum each term from $r=1$ to $n$: \\
$\sum(5r-2)^2=25\sum r^2-20\sum r+4\sum 1$ \\
Use the standard sums: \\
$=25\frac{n(n+1)(2n+1)}6-20\frac{n(n+1)}2+4n$ \\
Factor out $n/6$: \\
$=\frac n6[25(n+1)(2n+1)-60(n+1)+24]$ \\
Expand $(n+1)(2n+1)=2n^2+3n+1$: \\
$=\frac n6[50n^2+75n+25-60n-60+24]$ \\
$=\frac n6(50n^2+15n-11)$ \\
Thus $a=50$, $b=15$, $c=-11$ \\
(b) Set the result equal to $94k^2$: \\
$\frac k6(50k^2+15k-11)=94k^2$ \\
For positive $k$, divide by $k$ and multiply by $6$: \\
$50k^2+15k-11=564k$ \\
$50k^2-549k-11=0$ \\
Factor: \\
$(k-11)(50k+1)=0$ \\
$k=11$ or $k=-\frac1{50}$ \\
Since $k$ is a positive integer, $k=11$

@q 4
@topic Matrix multiplication and linear systems
@marks 7
@question
(a) Multiply each row of $M$ by each column of $N$: \\
$MN=\begin{pmatrix}2(k-7)+2-12&12-20+8&-20+24-4\\k(k-7)+4+6&6k-40-4&-10k+48-2\\4(k-7)+2+6&24-20+4&-40+24+2\end{pmatrix}$ \\
$MN=\begin{pmatrix}2k-24&0&0\\k^2-7k+10&6k-44&-10k+50\\4k-20&0&-14\end{pmatrix}$ \\
(b)(i) Substitute $k=5$: \\
$MN=\begin{pmatrix}-14&0&0\\0&-14&0\\0&0&-14\end{pmatrix}=-14I$ \\
(b)(ii) Since $MN=-14I$, divide by $-14$: \\
$M^{-1}=-\frac1{14}N=-\frac1{14}\begin{pmatrix}-2&6&-10\\2&-20&24\\-3&2&-1\end{pmatrix}$ \\
(c) The equations are $M\begin{pmatrix}x\\y\\z\end{pmatrix}=\begin{pmatrix}2\\3\\-1\end{pmatrix}$ \\
Multiply by $M^{-1}$: \\
$\begin{pmatrix}x\\y\\z\end{pmatrix}=-\frac1{14}\begin{pmatrix}-2&6&-10\\2&-20&24\\-3&2&-1\end{pmatrix}\begin{pmatrix}2\\3\\-1\end{pmatrix}$ \\
$=-\frac1{14}\begin{pmatrix}24\\-80\\1\end{pmatrix}$ \\
$\begin{pmatrix}x\\y\\z\end{pmatrix}=\begin{pmatrix}-12/7\\40/7\\-1/14\end{pmatrix}$ \\
(d) These coordinates give the unique point common to the three planes

@q 5
@topic Complex loci and circular segments
@marks 10
@question
(a) The inner and outer radii from the diagram are $1$ and $2$ \\
The centre is $(-2,1)$, so the modulus is $|z+2-i|$ \\
Thus $a=1$, $b=2$, $c=-1$, and $d=2$ \\
(b) Write $z=x+iy$ and find the boundary of the second locus: \\
$|z-i|=|z-3i|$ \\
$x^2+(y-1)^2=x^2+(y-3)^2$ \\
$y=2$ \\
The required half-plane satisfies $y\leq2$ \\
The annulus has area $\pi(2^2-1^2)=3\pi$ \\
The small circle is entirely below $y=2$, so only the cap above $y=2$ must be removed from the annulus \\
For the outer circle, the centre is $(-2,1)$ and the perpendicular distance to the chord is $1$ \\
With radius $2$, the half-angle satisfies $\cos\theta=1/2$, so $\theta=\pi/3$ \\
The sector area is $\frac12(2^2)(2\pi/3)=4\pi/3$ \\
The triangle area is $\frac12(2\sqrt3)(1)=\sqrt3$ \\
The cap area is $4\pi/3-\sqrt3$ \\
Therefore area $Q=3\pi-(4\pi/3-\sqrt3)=5\pi/3+\sqrt3$

@q 6
@topic Planes and scalar products
@marks 11
@question
(a) Form two direction vectors in the plane: \\
$AB=(15-10,30-5,-45+50)=(5,25,5)$ \\
$AC=(-5-10,20-5,-60+50)=(-15,15,-10)$ \\
Take a cross product to find a normal: \\
$AB\times AC=(-325,-25,450)=25(-13,-1,18)$ \\
Use the normal $(13,1,-18)$ and point $A$: \\
$\mathbf r\cdot(13,1,-18)=10(13)+5-50(-18)=1035$ \\
(b) The ground has normal vector $(0,0,1)$ \\
The mineral plane has normal $(13,1,-18)$, whose magnitude is $\sqrt{494}$ \\
The acute angle between the planes is the angle between their normals, or its supplement: \\
$\cos\theta=\frac{18}{\sqrt{494}}$ \\
$\theta=36.0$ degrees to the nearest degree \\
(c) On the vertical line, $x=5$, $y=12$ and $z=-\lambda$ \\
Substitute into the plane: \\
$13(5)+12-18(-\lambda)=1035$ \\
$77+18\lambda=1035$ \\
$\lambda=958/18=53.222\ldots$ \\
The distance to drill is $53.2$ m \\
(d) A real mineral layer may be uneven or have significant thickness rather than being a flat plane

@q 7
@topic Complex roots and quartic equations
@marks 9
@question
(a)(i) The coefficients are real, so the non-real root $2+i$ has conjugate root $2-i$ \\
Therefore $\gamma=2-i$ \\
(a)(ii) The roots $2+i$ and $2-i$ form a conjugate pair, and $\alpha=3$ is real \\
The one remaining root cannot be non-real without requiring a fifth root for its conjugate \\
Hence $\delta$ is real \\
(b) For a monic quartic, the sum of roots is $6$ because the coefficient of $z^3$ is $-6$ \\
$3+(2+i)+(2-i)+\delta=6$ \\
$7+\delta=6$, so $\delta=-1$ \\
(c) The four factors are $(z-3)$, $(z+1)$, $(z-2-i)$ and $(z-2+i)$ \\
Pair conjugates: $(z-2-i)(z-2+i)=(z-2)^2+1=z^2-4z+5$ \\
The real factors give $(z-3)(z+1)=z^2-2z-3$ \\
Multiply: $(z^2-2z-3)(z^2-4z+5)$ \\
$=z^4-4z^3+5z^2-2z^3+8z^2-10z-3z^2+12z-15$ \\
$=z^4-6z^3+10z^2+2z-15$ \\
Thus $p=10$, $q=2$, and $r=-15$ \\
(d) In $f(-2z)=0$, the value $-2z$ must equal one of the roots of $f$ \\
For roots $3$ and $-1$, $z=-3/2$ and $z=1/2$ \\
For roots $2\pm i$, $z=-(2\pm i)/2=-1\mp i/2$ \\
The roots are $-3/2$, $1/2$, and $-1\pm i/2$

@q 8
@topic Induction and summation
@marks 9
@question
(a) Let $S_n=\sum_{r=1}^n r(r+1)(2r+1)$ \\
For $n=1$, $S_1=1(2)(3)=6$ \\
The formula gives $\frac12(1)(2)^2(3)=6$, so it is true for $n=1$ \\
Assume $S_k=\frac12k(k+1)^2(k+2)$ \\
Then $S_{k+1}=S_k+(k+1)(k+2)(2k+3)$ \\
$=\frac12k(k+1)^2(k+2)+(k+1)(k+2)(2k+3)$ \\
Factor $\frac12(k+1)(k+2)$: \\
$S_{k+1}=\frac12(k+1)(k+2)[k(k+1)+2(2k+3)]$ \\
$=\frac12(k+1)(k+2)(k^2+5k+6)$ \\
$=\frac12(k+1)(k+2)(k+2)(k+3)$ \\
$=\frac12(k+1)((k+1)+1)^2((k+1)+2)$ \\
Thus the formula holds for $k+1$; with the base case, it holds for all positive integers $n$ \\
(b) Use the formula with upper limits $2n$ and $n-1$: \\
$\sum_{r=n}^{2n}r(r+1)(2r+1)=S_{2n}-S_{n-1}$ \\
$=\frac12(2n)(2n+1)^2(2n+2)-\frac12(n-1)n^2(n+1)$ \\
Factor $\frac12n(n+1)$: \\
$=\frac12n(n+1)[4(2n+1)^2-n(n-1)]$ \\
=$\frac12n(n+1)(15n^2+17n+4)$ \\
Factor the quadratic: \\
$15n^2+17n+4=(3n+1)(5n+4)$ \\
Thus $a=3$, $b=1$, $c=5$, and $d=4$

@q 9
@topic Volumes of revolution and modelling
@marks 13
@question
(a) Substitute $C=(5,15)$ into the curve equation: \\
$15=\frac{\sqrt{225(5)^2-2025}}{a}$ \\
$15=\frac{\sqrt{5625-2025}}a=\frac{60}a$ \\
$a=4$ \\
(b) For curve $BC$, rearrange to find $x^2$: \\
$4y=\sqrt{225x^2-2025}$ \\
$16y^2=225x^2-2025$ \\
$x^2=\frac{16y^2+2025}{225}$ \\
The $y$-limits are $0$ to $15$: \\
$V_1=\pi\int_0^{15}x^2\,dy=\frac\pi{225}\int_0^{15}(16y^2+2025)\,dy$ \\
$=\frac\pi{225}[\frac{16}{3}y^3+2025y]_0^{15}$ \\
$=\frac\pi{225}(18000+30375)=215\pi$ \\
For curve $CD$, rearrange $y=16-0.04x^2$: \\
$x^2=25(16-y)$ \\
The $y$-limits are $15$ to $16$: \\
$V_2=25\pi\int_{15}^{16}(16-y)\,dy$ \\
$=25\pi[16y-y^2/2]_{15}^{16}$ \\
$=25\pi(128-127.5)=12.5\pi$ \\
Add the two volumes: \\
$V=215\pi+12.5\pi=227.5\pi=\frac{455\pi}{2}\text{ cm}^3$ \\
(c) The model does not include the hole needed for the wick \\
(d) The model gives $227.5\pi\approx715.4\text{ cm}^3$ \\
This is about $15.4\text{ cm}^3$ more than the actual $700\text{ cm}^3$ \\
The difference is small relative to the total, so the model gives a reasonable estimate
