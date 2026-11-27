@paper AS Core Pure Shadow October 2020

@q 1
@marks 6
@question
(a) The coefficient matrix has rows $(1,k,-2)$; $(k,k,-k)$; $(-3,-1,2)$. \\
A unique solution requires a nonzero determinant. \\
Expanding the determinant gives $k(k-3)$. \\
For no unique solution, $k(k-3)=0$. \\
As $k>0$, $k=3$. \\
(b) Substitute $k=3$. The equations are $x+3y-2z=1$, $3x+3y-3z=0$, $-3x-y+2z=1$. \\
Divide the second by 3: $x+y-z=0$, so $x=-y+z$. \\
Put this into the first: $-y+z+3y-2z=1$. \\
$2y-z=1$, so $z=2y-1$. \\
Then $x=-y+(2y-1)=y-1$. \\
Check the third: $-3(y-1)-y+2(2y-1)=1$. \\
The left side is $-3y+3-y+4y-2=1$, so it holds for every $y$. \\
The equations are consistent with infinitely many solutions $(x,y,z)=(t-1,t,2t-1)$. \\
(c) The three planes share a common line.


@q 2
@marks 8
@question
(a) $r=|z_{1}|=\sqrt{1^{2}+5^{2}}=\sqrt{26}$. \\
$\theta=\tan^{-1}(5)=1.373400...$ radians. \\
To 4 significant figures, $\theta=1.373$. \\
$z_{1}=\sqrt{26}(\cos1.373400...+\mathrm{i}\sin1.373400...)$. \\
(b) Use $|z_{1}z_{2}|=|z_{1}||z_{2}|$. \\
$|z_{2}|=\frac{52}{\sqrt{26}}=2\sqrt{26}$. \\
So $|z_{2}|=2|z_{1}|$. \\
The argument of $z_{1}/z_{2}$ is $\frac{\pi}{2}$, so $z_{2}$ is $z_{1}$ rotated clockwise by $\frac{\pi}{2}$ and scaled by 2. \\
Multiplication by $-\mathrm{i}$ makes this rotation. \\
$z_{2}=-2\mathrm{i}(1+5\mathrm{i})$. \\
$=-2\mathrm{i}-10\mathrm{i}^{2}$. \\
Use $\mathrm{i}^{2}=-1$: $z_{2}=10-2\mathrm{i}$. \\
Check $|z_{2}|=\sqrt{10^{2}+(-2)^{2}}=2\sqrt{26}$.


@q 3
@marks 5
@question
The circle is $x^{2}+y^{2}=r^{2}$. \\
For a horizontal disc at height $y$, its radius is $x\geq0$. \\
Rearrange: $x^{2}=r^{2}-y^{2}$. \\
Use the disc volume formula: \\
$V=\pi\int_{-r}^{r}x^{2}\,dy$. \\
$=\pi\int_{-r}^{r}(r^{2}-y^{2})\,dy$. \\
Integrate: $V=\pi[r^{2}y-\frac{y^{3}}{3}]_{-r}^{r}$. \\
At $y=r$, the bracket is $r^{3}-\frac{r^{3}}{3}=\frac{2r^{3}}{3}$. \\
At $y=-r$, the bracket is $-r^{3}+\frac{r^{3}}{3}=-\frac{2r^{3}}{3}$. \\
Subtract: $V=\pi(\frac{2r^{3}}{3}-(-\frac{2r^{3}}{3}))$. \\
$V=\frac{4}{3}\pi r^{3}$ as required.


@q 4
@marks 13
@question
(a) From $L$, calculate $\text{LM}=(4-1,-1-0,-3-4)=(3,-1,-7)$. \\
$\text{LN}=(-3-1,-1-0,-2-4)=(-4,-1,-6)$. \\
The plane is $\mathbf{r}=(1,0,4)+\lambda(3,-1,-7)+\mu(-4,-1,-6)$. \\
(b)(i) Test the given normal vector against both directions. \\
$(1,-46,7)\cdot(3,-1,-7)=3+46-49=0$. \\
$(1,-46,7)\cdot(-4,-1,-6)=-4+46-42=0$. \\
It is perpendicular to the plane. \\
(b)(ii) Use normal form through $L$: \\
$(x-1)-46y+7(z-4)=0$. \\
$x-1-46y+7z-28=0$. \\
$x-46y+7z=29$. \\
(c) $\text{PQ}=(2-(-3),6-2,6-(-6))=(5,4,12)$. \\
The zipline is $\mathbf{r}=(-3,2,-6)+t(5,4,12)$. \\
(d) A real zipline can sag, so it need not be straight. \\
(e) The point-to-plane distance formula is $d=\frac{|ax_{0}+by_{0}+cz_{0}-d_{0}|}{\sqrt{a^{2}+b^{2}+c^{2}}}$. \\
Substitute $R(-0.5,4,0)$ into $x-46y+7z=29$: \\
Numerator $=|-0.5-184-29|=213.5$. \\
Denominator $=\sqrt{1^{2}+(-46)^{2}+7^{2}}=\sqrt{2166}$. \\
$d=\frac{213.5}{\sqrt{2166}}=4.587421...$ m. \\
To the nearest cm, $d=4.59$ m. \\
(f) The model predicts 4.59 m versus the actual 4.5 m, an overestimate of 0.09 m, about 2%. It is a close approximation.


@q 5
@marks 7
@question
(a) The block of length $r$ has volume $r(r+1)(r+3)$. \\
Expand: $r(r^{2}+4r+3)=r^{3}+4r^{2}+3r$. \\
Sum the three terms: \\
$V=\sum r^{3}+4\sum r^{2}+3\sum r$. \\
Use the standard formulae: \\
$V=\frac{n^{2}(n+1)^{2}}{4}+\frac{2n(n+1)(2n+1)}{3}+\frac{3n(n+1)}{2}$. \\
Factor $\frac{n(n+1)}{12}$: \\
$V=\frac{n(n+1)}{12}[3n(n+1)+8(2n+1)+18]$. \\
Expand the bracket: $3n^{2}+3n+16n+8+18=3n^{2}+19n+26$. \\
Factor: $3n^{2}+19n+26=(n+2)(3n+13)$. \\
$V=\frac{n}{12}(n+1)(n+2)(3n+13)$ as required. \\
(b) Set this equal to the given volume and multiply by 12. \\
After expansion and collection, $(n-8)(9n^{3}+2n^{2}+3n+4)=0$. \\
For positive $n$, the cubic factor is strictly positive. \\
Therefore $n=8$ blocks.


@q 6
@marks 16
@question
(i)(a) Self-inverse means $A^{2}=I$. \\
The upper-left entry is $9+a(a-6)=1$. \\
$a^{2}-6a+8=0$. \\
Factor: $(a-2)(a-4)=0$, so $a=2$ or $a=4$. \\
The lower-left entry is $a(3+b)=0$. \\
Since $a\neq0$, $3+b=0$, so $b=-3$. \\
The other entries of $A^{2}$ agree with $I$ for both values. \\
(i)(b) With $a=2$, $A$ has rows $(3,-4)$; $(2,-3)$. \\
An invariant point satisfies $A(x,y)=(x,y)$. \\
$3x-4y=x$, giving $2x-4y=0$. \\
$2x-3y=y$, giving the same condition. \\
Thus the invariant line is $x=2y$. \\
(ii)(a) The original triangle has vertical base 4 and horizontal height 2. \\
Its area is $\frac{1}{2}(4)(2)=4$. \\
Area scales by $|\mathrm{det}(P)|$, so $|\mathrm{det}(P)|=80/4=20$. \\
$\mathrm{det}(P)=(2p)(p)-(-3)(p+2)=2p^{2}+3p+6$. \\
For positive $p$ this is positive, so set it equal to 20. \\
$2p^{2}+3p-14=0$. \\
Factor: $(2p+7)(p-2)=0$. \\
Since $p>0$, $p=2$. \\
(ii)(b) The first stretch changes $x$ by factor $-4$, and the second changes $y$ by factor 2. \\
$Q$ has rows $(-4,0)$; $(0,2)$. \\
(ii)(c) With $p=2$, $P$ has rows $(4,-3)$; $(4,2)$. \\
Applying $Q$ then $P$ gives $R=PQ$. \\
$R$ has rows $(-16,-6)$; $(-16,4)$.


@q 7
@marks 6
@question
Real coefficients imply $1-2\mathrm{i}$ is also a root. \\
These two points form the right vertical side of the square, of length 4. \\
The left side is 4 units to the left, at real coordinate $1-4=-3$. \\
The other roots are $-3+2\mathrm{i}$ and $-3-2\mathrm{i}$. \\
Form a real quadratic from each conjugate pair: \\
$(z-(1+2\mathrm{i}))(z-(1-2\mathrm{i}))=(z-1)^{2}+4=z^{2}-2z+5$. \\
$(z-(-3+2\mathrm{i}))(z-(-3-2\mathrm{i}))=(z+3)^{2}+4=z^{2}+6z+13$. \\
Multiply: $f(z)=(z^{2}-2z+5)(z^{2}+6z+13)$. \\
$=z^{4}+6z^{3}+13z^{2}-2z^{3}-12z^{2}-26z+5z^{2}+30z+65$. \\
$=z^{4}+4z^{3}+6z^{2}+4z+65$. \\
Thus $a=4$, $b=6$, $c=4$, $d=65$.


@q 8
@marks 6
@question
Base case $n=1$: $f(1)=2^{1}+3^{1}=5$, divisible by 5. \\
Assume $f(k)=2^{2k-1}+3^{2k-1}$ is divisible by 5. \\
For $k+1$, $f(k+1)=2^{2k+1}+3^{2k+1}$. \\
Rewrite the powers: $f(k+1)=4\cdot2^{2k-1}+9\cdot3^{2k-1}$. \\
Write $9=4+5$: \\
$f(k+1)=4(2^{2k-1}+3^{2k-1})+5\cdot3^{2k-1}$. \\
$=4f(k)+5\cdot3^{2k-1}$. \\
Both terms are divisible by 5, so $f(k+1)$ is divisible by 5. \\
By induction, the claim holds for every positive integer $n$.


@q 9
@marks 6
@question
Divide the original polynomial by 2 to make it monic. \\
$x^{3}-\frac{5}{2}x^{2}-\frac{3}{2}x+\frac{1}{2}=0$. \\
By Vieta's formula, $\alpha\beta+\beta\gamma+\gamma\alpha=-\frac{3}{2}$ and $\alpha\beta\gamma=-\frac{1}{2}$. \\
(a) The reciprocal sum is the pairwise product sum divided by the product. \\
$\frac{1}{\alpha}+\frac{1}{\beta}+\frac{1}{\gamma}=\frac{-3/2}{-1/2}=3$. \\
(b) Let $u=1/x$, so $x=1/u$ in the original equation. \\
$\frac{2}{u^{3}}-\frac{5}{u^{2}}-\frac{3}{u}+1=0$. \\
Multiply by $u^{3}$: $2-5u-3u^{2}+u^{3}=0$. \\
$u^{3}-3u^{2}-5u+2=0$. \\
Thus $a=-3$, $b=-5$, $c=2$.


@q 10
@marks 7
@question
The circle has centre $(4,7)$ and radius $2r$. \\
The argument condition is the ray from $(-1,0)$ at angle $\frac{\pi}{4}$. \\
Write points on the ray as $(x,y)=(-1+t,t)$ with $t>0$. \\
Its containing line is $y=x+1$, or $-x+y-1=0$. \\
The distance from the centre $(4,7)$ to this line is $\frac{|-4+7-1|}{\sqrt{(-1)^{2}+1^{2}}}$. \\
$=\frac{2}{\sqrt{2}}=\sqrt{2}$. \\
The foot of the perpendicular is on the ray: from $(-1,0)$ to the centre is $(5,7)$, whose projection on $(1,1)$ is positive. \\
For two intersections with the containing line, the radius must exceed $\sqrt{2}$. \\
$2r>\sqrt{2}$, so $r>\frac{\sqrt{2}}{2}$. \\
Both intersections must lie on the ray, not behind its starting point. \\
The centre projects to $t=6$ along the ray, and the intersections have $t=6\pm\sqrt{2r^{2}-1}$. \\
Require the smaller value to be positive: $6-\sqrt{2r^{2}-1}>0$. \\
$2r^{2}-1<36$, so $r^{2}<\frac{37}{2}$. \\
Together, $\frac{\sqrt{2}}{2}<r<\frac{\sqrt{74}}{2}$.
