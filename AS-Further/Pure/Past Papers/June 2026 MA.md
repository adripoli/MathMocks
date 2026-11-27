@paper AS Core Pure June 2026

@q 1
@topic Symmetric functions of roots
@marks 9
@question
By Vieta, $\alpha+\beta+\gamma=3/2$, $\alpha\beta+\alpha\gamma+\beta\gamma=5/2$, and $\alpha\beta\gamma=-7/2$ \\
(i) $\alpha^2+\beta^2+\gamma^2=(\alpha+\beta+\gamma)^2-2(\alpha\beta+\alpha\gamma+\beta\gamma)$ \\
$=9/4-5=-11/4$ \\
(ii) $3(1/\alpha+1/\beta+1/\gamma)=3(\alpha\beta+\alpha\gamma+\beta\gamma)/(\alpha\beta\gamma)$ \\
$=3(5/2)/(-7/2)=-15/7$ \\
(iii) $2(1-\alpha)(1-\beta)(1-\gamma)=f(1)$ \\
$f(1)=2-3+5+7=11$ \\
Therefore $(1-\alpha)(1-\beta)(1-\gamma)=11/2$

@q 2
@topic Summation and integer solutions
@marks 8
@question
Expand $(r+2)(r-1)=r^2+r-2$ \\
Sum: $\sum r^2+\sum r-2n$ \\
$=n(n+1)(2n+1)/6+n(n+1)/2-2n$ \\
$=n(2n^2+6n-8)/6=n(n+4)(n-1)/3$ \\
Thus $a=4$ and $b=-1$ \\
(b) Set $k(k+4)(k-1)/3=3k^2$ and divide by positive $k$ \\
$(k+4)(k-1)=9k$, so $k^2-6k-4=0$ \\
$k=3\pm\sqrt{13}$, neither is an integer \\
Therefore no positive integer $k$ satisfies the equation

@q 3
@topic Complex roots of a cubic
@marks 8
@question
Since $f$ has real coefficients, the conjugate $4+i$ is also a root \\
Let the third root be $r$ \\
By Vieta, $(4-i)(4+i)r=-17/3$ \\
$17r=-17/3$, so $r=-1/3$ \\
The roots are $4-i,4+i,-1/3$ \\
Their sum is $23/3=-a/3$, so $a=-23$ \\
Their pairwise product sum is $17-8/3=43/3=b/3$, so $b=43$ \\
For $f(z+2)=0$, $z+2$ must be a root of $f$ \\
Thus $z=2-i,2+i,-7/3$

@q 4
@topic Invariant lines and points
@marks 7
@question
An invariant line through the origin has direction vector $(1,m)$, which maps to $(m,5-4m)$ \\
For the image to have slope $m$, $5-4m=m^2$ \\
$m^2+4m-5=0=(m-1)(m+5)$ \\
Thus the invariant lines are $y=x$ and $y=-5x$ \\
For invariant points require $(x,y)=(y,5x-4y)$ \\
The first equation gives $y=x$, and this also satisfies the second \\
The line of invariant points is $y=x$

@q 5
@topic Induction and summation
@marks 6
@question
For $n=1$, the left side is $3$ and the right side is $1(2)(9)/6=3$ \\
Assume $\sum_{r=1}^{k}r(r+2)=\frac16k(k+1)(2k+7)$ \\
Then $\sum_{r=1}^{k+1}r(r+2)=\frac16k(k+1)(2k+7)+(k+1)(k+3)$ \\
$=(k+1)[k(2k+7)/6+k+3]$ \\
$=(k+1)(2k^2+13k+18)/6$ \\
$=(k+1)(k+2)(2k+9)/6$ \\
This is the required formula with $n=k+1$ \\
Therefore the result holds for all positive integers by induction

@q 6
@topic Complex loci and region
@marks 9
@question
The circle has centre $(3,-2)$ and radius $1$, so $|z-(3-2i)|=1$ \\
Comparing with $|z+a+bi|=1$ gives $a=-3$ and $b=2$ \\
Half-line $l$ starts at the centre $3-2i$ and points northwest, so $\text{arg}(z-(3-2i))=3\pi/4$ \\
The centre lies on the line through $P$ and the centre; the direction from the centre to $P$ is $(-1,1)/\sqrt{2}$ \\
$P=(3-1/\sqrt{2})+(-2+1/\sqrt{2})i$ \\
The region is the disk $|z-(3-2i)|\leq1$ except the upper sector between $l$ and $m$ \\
Equivalently, $|z-(3-2i)|\leq1$ and either the imaginary part of $z$ is at most $-2$, or it is at most $1$ minus the real part of $z$

@q 7
@topic Matrices and simultaneous equations
@marks 12
@question
Expansion gives determinant $k-4$, so the singular value is $k=4$ \\
The adjugate is $\begin{pmatrix}-1&1&2\\-2k-1&9&3k+6\\-3k-1&13&5k+6\end{pmatrix}$ \\
Thus $M^{-1}=\frac{1}{k-4}\begin{pmatrix}-1&1&2\\-2k-1&9&3k+6\\-3k-1&13&5k+6\end{pmatrix}$ \\
(c) Multiply by the adjugate and divide by $k-4$: \\
$x=(-p-19)/(k-4)$, $y=(-(2k+1)p-21k-87)/(k-4)$, $z=(-(3k+1)p-35k-107)/(k-4)$ \\
(d) The first coefficient row equals the second row plus twice the third row \\
Therefore consistency requires $p=-5+2(-7)=-19$ \\
(e) When $p\neq-19$, the three planes have no common point; their pairwise intersection lines are parallel

@q 8
@topic Lines and planes in three dimensions
@marks 10
@question
Set $x=1+t$, $y=4+2t$, $z=t$ for $l_1$ \\
Substitute into the plane: $2(1+t)+4+2t-2t=4$, so $t=-1$ \\
The intersection is $(0,2,-1)$ \\
Direction of $l_1$ is $\mathbf{d}=(1,2,1)$ and plane normal is $\mathbf{n}=(2,1,-2)$ \\
$\sin\theta=|\mathbf{d}\cdot\mathbf{n}|/(|\mathbf{d}||\mathbf{n}|)=2/(3\sqrt{6})$ \\
Thus $\theta=15.8$ degrees to one decimal place \\
The projection of $\mathbf{d}$ into the plane is $\mathbf{d}-(\mathbf{d}\cdot\mathbf{n}/9)\mathbf{n}$ \\
$=(1,2,1)-(2/9)(2,1,-2)=(5,16,13)/9$ \\
This direction makes the required angle $\theta$ with $l_1$ \\
So one equation is $\mathbf{r}=(0,2,-1)+\mu(5,16,13)$

@q 9
@topic Volumes of revolution and modelling
@marks 11
@question
At $C=(1,k)$, $1+9(k-4)^2=9$, so $(k-4)^2=8/9$ \\
Since $C$ lies below $y=4$, $k=4-2\sqrt{2}/3$ \\
For $0\leq y\leq k$, the radius is $1$; for $k\leq y\leq5$, $x^2=9-9(y-4)^2$ \\
$V=\pi[\int_0^k1\,dy+\int_k^5(9-9(y-4)^2)\,dy]$ \\
Integrating gives $V=\pi[ k+42-9k+3(k-4)^3]$ \\
Substitute $k=4-2\sqrt{2}/3$: $V=\pi(10+32\sqrt{2}/9)\approx47.2$ cubic centimetres \\
To the nearest cubic centimetre, $V=47$ cubic centimetres \\
(c) The real handle may not be rotationally symmetric or have exactly this cross-section \\
(d) The model predicts about $47$ cubic centimetres, close to the actual $48$, so it is reasonably accurate \\
(e) Replace the profile curve with the relevant circular arc from a sphere in the cross-section
