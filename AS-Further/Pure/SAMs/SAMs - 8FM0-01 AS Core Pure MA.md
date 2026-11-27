@paper AS Core Pure SAMs

@q 1
@marks 7
@question
Use the product of roots of a monic cubic: $-(-15)=15$. \\
$\alpha\left(\frac{5}{\alpha}\right)\left(\alpha+\frac{5}{\alpha}-1\right)=15$ \\
Cancel $\alpha$ in the first two factors: \\
$5\left(\alpha+\frac{5}{\alpha}-1\right)=15$ \\
Divide by 5: $\alpha+\frac{5}{\alpha}-1=3$ \\
Add 1: $\alpha+\frac{5}{\alpha}=4$ \\
Multiply by $\alpha$: $\alpha^{2}+5=4\alpha$ \\
$\alpha^{2}-4\alpha+5=0$ \\
Complete the square: $(\alpha-2)^{2}+1=0$ \\
$(\alpha-2)^{2}=-1$ \\
$\alpha=2\pm\mathrm{i}$ \\
As the coefficients are real, both conjugates are roots. \\
The third root is $\alpha+\frac{5}{\alpha}-1=4-1=3$. \\
(a) $z=2+\mathrm{i},\ 2-\mathrm{i},\ 3$ \\
(b) Use the sum of roots $=-p$. \\
$-p=(2+\mathrm{i})+(2-\mathrm{i})+3$ \\
$-p=7$ \\
$p=-7$


@q 2
@marks 10
@question
(a) The normal to $Pi$ is $(3,-1,2)$. \\
Use $\mathbf{n}\cdot(\mathbf{r}-\text{OA})=0$: \\
$3(x-5)-(y+3)+2(z+4)=0$ \\
Expand: $3x-15-y-3+2z+8=0$ \\
$3x-y+2z=10$ \\
(b) The line direction is $\mathbf{d}=(-1,-5,3)$. \\
Calculate the scalar product: \\
$\mathbf{n}\cdot\mathbf{d}=3(-1)+(-1)(-5)+2(3)$ \\
$=-3+5+6=8$ \\
$|\mathbf{n}|=\sqrt{3^{2}+(-1)^{2}+2^{2}}=\sqrt{14}$ \\
$|\mathbf{d}|=\sqrt{(-1)^{2}+(-5)^{2}+3^{2}}=\sqrt{35}$ \\
The angle $\theta$ between the line and plane is complementary to the angle between $\mathbf{n}$ and $\mathbf{d}$. \\
$\sin\theta=\frac{|\mathbf{n}\cdot\mathbf{d}|}{|\mathbf{n}||\mathbf{d}|}$ \\
$=\frac{8}{\sqrt{14}\sqrt{35}}$ \\
$\theta=21.18639398...$ degrees \\
(b) $\theta=21.2$ degrees (1 dp). \\
(c) On the line, $x=7-\lambda$, $y=3-5\lambda$ and $z=-2+3\lambda$. \\
Substitute in the plane equation: \\
$3(7-\lambda)-(3-5\lambda)+2(-2+3\lambda)=10$ \\
$21-3\lambda-3+5\lambda-4+6\lambda=10$ \\
$14+8\lambda=10$ \\
$8\lambda=-4$ \\
$\lambda=-\frac{1}{2}$ \\
$x=7+\frac{1}{2}=7.5$ \\
$y=3+\frac{5}{2}=5.5$ \\
$z=-2-\frac{3}{2}=-3.5$ \\
(c) $X=(7.5,5.5,-3.5)$


@q 3
@marks 7
@question
Let $x$, $y$, $z$ be the amounts initially invested in savings, property bonds and shares, in pounds. \\
The total investment gives $x+y+z=5000$. \\
The property bond condition gives $y=x+400$. \\
Subtract $y$ from $x$: $x-y=-400$. \\
The total increase gives $0.015x+0.035y-0.025z=79$. \\
Form a matrix $A$ with rows $(1,1,1)$; $(1,-1,0)$; $(0.015,0.035,-0.025)$. \\
Then $A(x,y,z)=(5000,-400,79)$. \\
Solve using $A^{-1}$: $(x,y,z)=A^{-1}(5000,-400,79)$. \\
Check the result by substitution. \\
$1800+2200+1000=5000$ \\
$2200-1800=400$ \\
$0.015(1800)+0.035(2200)-0.025(1000)$ \\
$=27+77-25=79$ \\
Savings: 1800 pounds; property bonds: 2200 pounds; shares: 1000 pounds.


@q 4
@marks 5
@question
Let $w=x-1$ so a root $x=\alpha$ gives $w=\alpha-1$, and similarly for the other roots. \\
Rearrange: $x=w+1$. \\
Substitute into the original equation: \\
$(w+1)^{3}+3(w+1)^{2}-8(w+1)+6=0$ \\
Expand the cube: $(w+1)^{3}=w^{3}+3w^{2}+3w+1$. \\
Expand the square: $(w+1)^{2}=w^{2}+2w+1$. \\
$w^{3}+3w^{2}+3w+1+3w^{2}+6w+3-8w-8+6=0$ \\
Collect the $w^{2}$ terms: $3w^{2}+3w^{2}=6w^{2}$. \\
Collect the $w$ terms: $3w+6w-8w=w$. \\
Collect constants: $1+3-8+6=2$. \\
$w^{3}+6w^{2}+w+2=0$ \\
$p=6$, $q=1$, $r=2$.


@q 5
@marks 7
@question
(a) Use the determinant formula $ad-bc$. \\
$\mathrm{det}(M)=1(1)-(-\sqrt{3})(\sqrt{3})$ \\
$=1-(-3)$ \\
$=4$ \\
Since $4\neq0$, $M$ is non-singular. \\
(b) Areas scale by the absolute determinant. \\
$\mathrm{Area}(S)=|4|\times5$ \\
$=20$ square units. \\
(c) An enlargement by $k$ scales area by $k^{2}$; a rotation preserves area. \\
$k^{2}=4$ \\
Since $k>0$, $k=2$. \\
(d) Compare $M$ with the enlargement then rotation matrix, whose first row is $(k\cos\theta,-k\sin\theta)$. \\
$2\cos\theta=1$ \\
$\cos\theta=\frac{1}{2}$ \\
$2\sin\theta=\sqrt{3}$ \\
$\sin\theta=\frac{\sqrt{3}}{2}$ \\
The rotation is anticlockwise, so $\theta=60$ degrees.


@q 6
@marks 15
@question
(a) Use mathematical induction. \\
Base case $n=1$: $\sum_{r=1}^{1}r^{2}=1$. \\
The formula gives $\frac{1}{6}(1)(2)(3)=1$. \\
Assume for $n=k$ that $\sum_{r=1}^{k}r^{2}=\frac{1}{6}k(k+1)(2k+1)$. \\
For $n=k+1$, add the next term: \\
$\sum_{r=1}^{k+1}r^{2}=\frac{1}{6}k(k+1)(2k+1)+(k+1)^{2}$ \\
Factor $k+1$: \\
$=\frac{1}{6}(k+1)[k(2k+1)+6(k+1)]$ \\
Expand inside the bracket: \\
$=\frac{1}{6}(k+1)(2k^{2}+7k+6)$ \\
Factor the quadratic: \\
$=\frac{1}{6}(k+1)(k+2)(2k+3)$ \\
Since $2k+3=2(k+1)+1$, this is the formula for $k+1$. \\
The base case and induction step prove the result for all positive integers. \\
(b) Expand the summand: \\
$r(r+6)(r-6)=r(r^{2}-36)$ \\
$=r^{3}-36r$ \\
Use $\sum r^{3}=[\frac{n(n+1)}{2}]^{2}$ and $\sum r=\frac{n(n+1)}{2}$. \\
$\sum_{r=1}^{n}(r^{3}-36r)=\frac{n^{2}(n+1)^{2}}{4}-18n(n+1)$ \\
Factor out $\frac{1}{4}n(n+1)$: \\
$=\frac{1}{4}n(n+1)[n(n+1)-72]$ \\
$=\frac{1}{4}n(n+1)(n^{2}+n-72)$ \\
$=\frac{1}{4}n(n+1)(n-8)(n+9)$ as required. \\
(c) Substitute the two results into the equation: \\
$\frac{1}{4}n(n+1)(n-8)(n+9)=\frac{17}{6}n(n+1)(2n+1)$ \\
As $n$ is positive, $n(n+1)\neq0$; cancel it. \\
$\frac{1}{4}(n-8)(n+9)=\frac{17}{6}(2n+1)$ \\
Multiply by 12: $3(n-8)(n+9)=34(2n+1)$. \\
Expand: $3(n^{2}+n-72)=68n+34$. \\
$3n^{2}+3n-216=68n+34$ \\
$3n^{2}-65n-250=0$ \\
Factor: $(3n+10)(n-25)=0$. \\
$n=-\frac{10}{3}$ or $n=25$. \\
Reject the negative, noninteger root. \\
$n=25$.


@q 7
@marks 12
@question
(a) The bowl is deepest at the centre, where $y=1$ m. \\
The rim is at $y=1.16$ m. \\
Maximum depth $=1.16-1=0.16$ m. \\
(b) At the rim, $x=0.2$ and $y=1.16$. \\
Substitute into $y=1+kx^{2}$: \\
$1.16=1+k(0.2)^{2}$ \\
$0.16=0.04k$ \\
$k=4$ \\
(c) The bowl is formed by rotating $y=1+4x^{2}$ about the $y$ axis. \\
Rearrange: $x^{2}=\frac{y-1}{4}$. \\
Use the volume of revolution formula $V=\pi\int x^{2}\,dy$. \\
The bowl runs from $y=1$ to $y=1.16$. \\
$V_{\mathrm{bowl}}=\frac{\pi}{4}\int_{1}^{1.16}(y-1)\,dy$ \\
Integrate: $V_{\mathrm{bowl}}=\frac{\pi}{4}[\frac{y^{2}}{2}-y]_{1}^{1.16}$. \\
At the upper limit: $\frac{1.16^{2}}{2}-1.16=0.6728-1.16=-0.4872$. \\
At the lower limit: $\frac{1^{2}}{2}-1=-0.5$. \\
Subtract: $-0.4872-(-0.5)=0.0128$. \\
$V_{\mathrm{bowl}}=\frac{\pi}{4}(0.0128)=0.0032\pi$. \\
The outer cylinder has radius $0.2$ and height $1.16$. \\
$V_{\mathrm{cylinder}}=\pi(0.2)^{2}(1.16)=0.0464\pi$. \\
Subtract the empty bowl: \\
$V_{\mathrm{concrete}}=0.0464\pi-0.0032\pi$ \\
$=0.0432\pi=0.1357168026...$ \\
$V_{\mathrm{concrete}}=0.136$ cubic metres (3 sf). \\
(d) The real bowl surface may not exactly follow a parabola. \\
(e) The measured volume, 0.127 cubic metres, is lower by about 0.009 cubic metres or 7%. The model gives a reasonable estimate but overestimates the concrete required.


@q 8
@marks 8
@question
(a) $|z-4\mathrm{i}|\leq3$ is the closed disc centred at $(0,4)$ with radius 3. \\
The argument $\mathrm{arg}(z+3-4\mathrm{i})$ is measured from $(-3,4)$. \\
Draw the ray from $(-3,4)$ at $\frac{\pi}{4}$ above the positive real direction, including this ray. \\
Draw the downward ray from $(-3,4)$ as the excluded lower boundary. \\
Shade the intersection of the disc and the angular sector between these rays. \\
(b) The largest argument from the origin touches the circle tangentially on its left side. \\
The centre is distance 4 from the origin and the radius is 3. \\
Let $\phi$ be the angle between the positive imaginary axis and the tangent. \\
By right-triangle geometry, $\sin\phi=\frac{3}{4}$. \\
$\phi=\sin^{-1}\left(\frac{3}{4}\right)=0.848062...$ \\
Maximum argument $=\frac{\pi}{2}+\phi$. \\
$=1.570796...+0.848062...$ \\
$=2.418858...$ \\
$\mathrm{max}\mathrm{arg} w=2.42$ radians.


@q 9
@marks 9
@question
(a) Find the direction from $A$ to $B$: \\
$\text{AB}=(9-(-3),4-1,11-(-7))$ \\
$=(12,3,18)$ \\
Points on the fish's path are $\mathbf{r}=(-3,1,-7)+\lambda(12,3,18)$, with $0\leq\lambda\leq1$. \\
The closest point $F$ to $O$ has $\text{OF}$ perpendicular to $\text{AB}$. \\
$[(-3,1,-7)+\lambda(12,3,18)]\cdot(12,3,18)=0$ \\
Expand the scalar product: \\
$-36+144\lambda+3+9\lambda-126+324\lambda=0$ \\
$477\lambda-159=0$ \\
$\lambda=\frac{159}{477}=\frac{1}{3}$ \\
This lies in $[0,1]$, so the closest point is on the path from $A$ to $B$. \\
$\text{OF}=(-3,1,-7)+\frac{1}{3}(12,3,18)$ \\
$=(-3,1,-7)+(4,1,6)$ \\
$=(1,2,-1)$ \\
$|\text{OF}|=\sqrt{1^{2}+2^{2}+(-1)^{2}}$ \\
$=\sqrt{6}=2.449489...$ m. \\
Since $2.449489...>2$, the octopus cannot catch fish $F$ under the model. \\
(b) A real fish might turn away instead of swimming exactly along a straight line. \\
(c) A real octopus could move toward the fish rather than remaining fixed at $O$.
