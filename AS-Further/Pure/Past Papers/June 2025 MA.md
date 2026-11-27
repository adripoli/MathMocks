@paper AS Core Pure June 2025

@q 1
@topic Complex numbers and rotations
@marks 6
@question
$|z|=\sqrt{3^2+(-3)^2}=3\sqrt{2}$ \\
The argument of $z$ is $-\pi/4$, since $z$ lies in quadrant IV \\
Thus $z=3\sqrt{2}(\cos(-\pi/4)+i\sin(-\pi/4))$ \\
$P=(3,-3)$ and $iz=i(3-3i)=3+3i$, so $Q=(3,3)$ \\
Multiplication by $i$ adds $\pi/2$ to the argument and preserves modulus \\
Hence the transformation is a $90$ degrees anticlockwise rotation about the origin

@q 2
@topic Polynomial roots and complex numbers
@marks 7
@question
Divide $f(z)$ by $z+5$; the quotient is $4z^2-32z+65$ and remainder is $0$ \\
Thus $f(z)=(z+5)(4z^2-32z+65)$ \\
Solve the quadratic: $z=(32\pm\sqrt{1024-1040})/8=(32\pm4i)/8=(8\pm i)/2$ \\
For $f(2z-1)=0$, set $2z-1$ equal to each root of $f$ \\
$2z-1=-5$ gives $z=-2$ \\
$2z-1=(8\pm i)/2$ gives $z=(10\pm i)/4$

@q 3
@topic Matrix inverse
@marks 6
@question
Determinant of $M$ is $a(-1)-b(-1)=b-a$ \\
$M^{-1}=\frac{1}{b-a}\begin{pmatrix}-1&-b\\1&a\end{pmatrix}$ \\
The $(2,1)$ entry of $M+M^{-1}=I$ gives $-1+1/(b-a)=0$, so $b-a=1$ \\
The $(1,1)$ entry gives $a-1/(b-a)=1$, hence $a=2$ \\
Therefore $b=3$

@q 4
@topic Transformations and area scale
@marks 10
@question
(i)(a) $(x,y)$ maps to $(2x,y)$, so $P$ is a stretch with scale factor $2$ parallel to the $x$-axis \\
(i)(b) The $y$-coordinate stays unchanged, so every horizontal line $y=k$ is invariant; the vertical line $x=0$ is also invariant \\
(ii) The triangle has base $6$ and height $3$, so its area is $9$ \\
Determinant of $Q$ is $\cos 2\theta\tan 2\theta=\sin 2\theta$ \\
Area scales by the absolute determinant, so $9|\sin 2\theta|=9/2$ \\
Therefore $|\sin 2\theta|=1/2$ \\
For $0\leq\theta<360$, $2\theta=30,150,210,330,390,510,570,690$ degrees \\
Hence $\theta=15,75,105,165,195,255,285,345$ degrees

@q 5
@topic Complex loci and tangents
@marks 8
@question
$|z-1|=1$ is a circle with centre $(1,0)$ and radius $1$ \\
The point represented by $-1$ is $2$ units from the centre \\
For a tangent from $-1$, the radius to the contact point is perpendicular to the tangent \\
The right triangle has hypotenuse $2$ and opposite side $1$, so the angle of the tangent ray is $\pi/6$ \\
The two possible arguments of $z+1$ are $\pi/6$ and $11\pi/6$ \\
The contact points have real part $1/2$ and imaginary parts $\pm\sqrt{3}/2$ \\
Therefore $z=1/2+(\sqrt{3}/2)i$ or $z=1/2-(\sqrt{3}/2)i$

@q 6
@topic Induction and summation
@marks 6
@question
For $n=1$, both sides equal $1$ \\
Assume $\sum_{r=1}^{k}r^3=\frac14k^2(k+1)^2$ \\
$\sum_{r=1}^{k+1}r^3=\frac14k^2(k+1)^2+(k+1)^3$ \\
$=(k+1)^2(\frac14k^2+k+1)$ \\
$=\frac14(k+1)^2(k^2+4k+4)=\frac14(k+1)^2(k+2)^2$ \\
So the statement for $k$ implies the statement for $k+1$ \\
Therefore the result holds for all positive integers $n$ by induction

@q 7
@topic Volumes of revolution and modelling
@marks 8
@question
(a) The intercepts satisfy $A-y^2=0$; the upper intercept is $y=12$ because the total height is $24$ \\
Thus $A=12^2=144$ \\
(b) Rearrange: $x^2=(12+y)^2(144-y^2)/350$ \\
The volume is $V=\pi\int_{-12}^{12}x^2dy$ \\
Expand $(12+y)^2(144-y^2)=20736+3456y-24y^3-y^4$ \\
$V=\frac{\pi}{350}\int_{-12}^{12}(20736+3456y-24y^3-y^4)dy$ \\
The odd terms integrate to zero on $[-12,12]$ \\
$V=\frac{\pi}{350}(20736(24)-2(12^5/5))\approx3574$ cubic metres \\
To 2 significant figures, $V=3.6\times10^3$ cubic metres \\
(c) Scale all lengths by $13/12$; the coefficient becomes $350(13/12)^2\approx411$ \\
One suitable equation is $411x^2=(13+y)^2(169-y^2)$ \\
(d) The actual balloon may not have this exact cross-section or be perfectly rotationally symmetric

@q 8
@topic Triangular numbers and summation
@marks 7
@question
The $r$th triangular number is $\frac12r(r+1)$ \\
Sum the first $n$: $\frac12\sum_{r=1}^{n}(r^2+r)$ \\
$=\frac12(\frac{n(n+1)(2n+1)}6+\frac{n(n+1)}2)$ \\
$=\frac{n(n+1)}{12}(2n+1+3)$ \\
$=\frac16n(n+1)(n+2)$ \\
(b) Set $\frac16n(n+1)(n+2)=22n$ and divide by positive $n$ \\
$(n+1)(n+2)=132$, so $n^2+3n-130=0$ \\
$(n-10)(n+13)=0$, hence the positive value is $n=10$

@q 9
@topic Distance and projection to a plane
@marks 7
@question
The plane normal is $(1,-2,8)$, with magnitude $\sqrt{69}$ \\
At $W$, $x-2y+8z-1=6+4-32-1=-23$ \\
The shortest distance is $23/\sqrt{69}=2.77$ m to 3 significant figures \\
(b) The answer is not necessarily reliable because the actual ground may not be flat or the water source may not be a single point \\
(c) The perpendicular foot is $P=W+(1/3)(1,-2,8)$ \\
$P=(6+1/3,-2-2/3,-4+8/3)=(19/3,-8/3,-4/3)$ \\
(d) The model gives $2.77$ m versus the actual $2.52$ m, an overestimate of about $0.25$ m; it is reasonably close but not exact

@q 10
@topic Perpendicular planes and a sheaf
@marks 8
@question
The normals are $(1,1,-1)$ and $(a,3,5)$ \\
Perpendicular planes have perpendicular normals: $a+3-5=0$, hence $a=2$ \\
For a sheaf, the coefficients of $P_3$ must be the same linear combination of the coefficients of $P_1$ and $P_2$ \\
Solve $\lambda(1,1,-1)+\mu(2,3,5)=(1,b,13)$ \\
$\lambda+2\mu=1$ and $-\lambda+5\mu=13$ \\
Adding gives $7\mu=14$, so $\mu=2$ and $\lambda=-3$ \\
Thus $b=\lambda+3\mu=-3+6=3$ \\
Apply the same combination to the right sides: $c=-3(3)+2(4)=-1$

@q 11
@topic Cubic roots in arithmetic progression
@marks 7
@question
By Vieta, the sum of roots is $21$ \\
$\alpha+(\alpha+3\beta)+(\alpha+6\beta)=21$ \\
Thus $\alpha+3\beta=7$ \\
The product is $91$ \\
Write the roots as $7-3\beta$, $7$, $7+3\beta$ \\
$7(49-9\beta^2)=91$ \\
$49-9\beta^2=13$, so $\beta^2=4$ and $\beta=\pm2$ \\
The roots are $1,7,13$ in either order
