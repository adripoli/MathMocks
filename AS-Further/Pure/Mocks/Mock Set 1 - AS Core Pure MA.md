@paper AS Core Pure Mock Set 1

@q 1
@marks 5
@question
Let $w=2x-1$ for any of the original roots. \\
Then $x=\frac{w+1}{2}$. \\
Substitute this in $3x^3+5x^2-2x+6=0$: \\
$3(\frac{w+1}{2})^3+5(\frac{w+1}{2})^2-2(\frac{w+1}{2})+6=0$. \\
Multiply through by 8: \\
$3(w+1)^3+10(w+1)^2-8(w+1)+48=0$. \\
Expand the powers: \\
$3(w^3+3w^2+3w+1)+10(w^2+2w+1)-8w-8+48=0$. \\
Collect like terms: \\
$3w^3+19w^2+21w+53=0$. \\
Each transformed root therefore satisfies this cubic.


@q 2
@marks 9
@question
(a) First expand the summand: \\
$r(r-1)^2=r(r^2-2r+1)=r^3-2r^2+r$. \\
Therefore $\sum_{r=1}^{n}r(r-1)^2=\sum r^3-2\sum r^2+\sum r$. \\
Using the standard sums, this is \\
$\frac{n^2(n+1)^2}{4}-\frac{n(n+1)(2n+1)}{3}+\frac{n(n+1)}{2}$. \\
Take out $\frac{n(n+1)}{12}$: \\
$\frac{n(n+1)}{12}[3n(n+1)-4(2n+1)+6]$. \\
Simplify the bracket: $3n^2+3n-8n-4+6=3n^2-5n+2$. \\
Factor it: $3n^2-5n+2=(n-1)(3n-2)$. \\
Thus $\sum_{r=1}^{n}r(r-1)^2=\frac{n(n+1)(n-1)(3n-2)}{12}$. \\
Hence $a=3$ and $b=-2$. \\
(b) The right side is $\sum_{r=1}^{n}5r=\frac{5n(n+1)}{2}$. \\
Equate the two sums: $\frac{n(n+1)(n-1)(3n-2)}{12}=\frac{5n(n+1)}{2}$. \\
Since $n$ is positive, divide by $n(n+1)$: $(n-1)(3n-2)=30$. \\
Expand: $3n^2-5n+2=30$. \\
Thus $3n^2-5n-28=0=(3n+7)(n-4)$. \\
The roots are $n=4$ and $n=-\frac{7}{3}$; only $n=4$ is a positive integer.


@q 3
@marks 10
@question
(a)(i) Write $z=x+\mathrm{i}y$. \\
$|z-3|^2=|(x-3)+\mathrm{i}y|^2=(x-3)^2+y^2$. \\
As $(3\sqrt{2})^2=18$, the circle is $(x-3)^2+y^2=18$. \\
(ii) Square both sides of the equal-modulus equation: \\
$(x-2)^2+(y-1)^2=(x+4)^2+(y+1)^2$. \\
Expand: $x^2-4x+4+y^2-2y+1=x^2+8x+16+y^2+2y+1$. \\
Cancel $x^2+y^2$ and collect: $-12x-4y-12=0$. \\
Thus $3x+y+3=0$, or $y=-3x-3$. \\
(b) Substitute $y=-3x-3$ into $(x-3)^2+y^2=18$: \\
$(x-3)^2+(-3x-3)^2=18$. \\
$x^2-6x+9+9x^2+18x+9=18$. \\
$10x^2+12x=0=2x(5x+6)$. \\
Hence $x=0$ or $x=-\frac{6}{5}$. \\
For $x=0$, $y=-3$; for $x=-\frac{6}{5}$, $y=\frac{3}{5}$. \\
Therefore $z=-3\mathrm{i}$ or $z=-\frac{6}{5}+\frac{3}{5}\mathrm{i}$. \\
(c) Draw the circle centred at $(3,0)$ with radius $3\sqrt{2}$ and the line $y=-3x-3$. \\
The second inequality gives $(x-2)^2+(y-1)^2\geq(x+4)^2+(y+1)^2$, so $3x+y+3\leq0$. \\
Shade the part inside the circle on or below that line, and label it $R$. \\
Draw both boundaries as solid curves because equality is included.


@q 4
@marks 9
@question
(i) A fixed point obeys $P(x,y)=(x,y)$. \\
The first coordinate gives $2x+y=x$, hence $y=-x$. \\
The second gives $3x+4y=y$, hence $3x+3y=0$ and again $y=-x$. \\
So the invariant points form the line $y=-x$. \\
(ii)(a) Every invariant line would have a real direction preserved by $Q$. \\
A nonvertical direction may be written $(1,m)$. \\
$Q(1,m)=(3-m,3+4m)$. \\
For this to be parallel to $(1,m)$, $3+4m=m(3-m)$. \\
Rearrange: $m^2+m+3=0$. \\
Its discriminant is $1^2-4(1)(3)=-11<0$, so it has no real slope. \\
A vertical direction $(0,1)$ maps to $(-1,4)$, which is not vertical. \\
Thus no real line is invariant under $Q$. \\
(ii)(b) The area scale factor is $|\mathrm{det}(Q)|=|3(4)-(-1)(3)|=15$. \\
The original triangle has base $|8-k|$ and height $4-2=2$. \\
Its area is $\frac{1}{2}|8-k|(2)=|8-k|$. \\
The image area is therefore $15|8-k|=75$. \\
Divide by 15: $|8-k|=5$. \\
So $8-k=5$ or $8-k=-5$, giving $k=3$ or $k=13$.


@q 5
@marks 7
@question
(a) The coefficients of $f$ are real, so nonreal roots occur in conjugate pairs. \\
Therefore $\gamma=3-2\mathrm{i}$. \\
(b) The product of the roots of the monic quartic is its constant term, $-52$. \\
$(\alpha)(-\alpha)(3+2\mathrm{i})(3-2\mathrm{i})=-52$. \\
The conjugate product is $3^2+2^2=13$. \\
Thus $-13\alpha^2=-52$. \\
Divide by $-13$: $\alpha^2=4$. \\
As $\alpha$ is positive, $\alpha=2$. \\
(c) Pair the real roots and conjugate roots: \\
$f(z)=(z-2)(z+2)(z-3-2\mathrm{i})(z-3+2\mathrm{i})$. \\
$=(z^2-4)[(z-3)^2+4]$. \\
$=(z^2-4)(z^2-6z+13)$. \\
Multiply: $z^4-6z^3+13z^2-4z^2+24z-52$. \\
Hence $f(z)=z^4-6z^3+9z^2+24z-52$. \\
Comparing coefficients gives $p=-6$, $q=9$, $r=24$.


@q 6
@marks 6
@question
For $n=1$, $f(1)=6^{1}+8^{2}=6+64=70=7(10)$. \\
So the statement holds at $n=1$. \\
Assume for some positive integer $k$ that $f(k)=6^{2k-1}+8^{k+1}$ is a multiple of 7. \\
Now $f(k+1)=6^{2(k+1)-1}+8^{(k+1)+1}$. \\
$=6^{2k+1}+8^{k+2}$. \\
$=36\cdot6^{2k-1}+8\cdot8^{k+1}$. \\
Split $36=28+8$: \\
$f(k+1)=28\cdot6^{2k-1}+8\cdot6^{2k-1}+8\cdot8^{k+1}$. \\
$=28\cdot6^{2k-1}+8(6^{2k-1}+8^{k+1})$. \\
$=28\cdot6^{2k-1}+8f(k)$. \\
The first term is divisible by 7, and the second is divisible by 7 by the assumption. \\
Hence $f(k+1)$ is divisible by 7. \\
By induction, $f(n)$ is divisible by 7 for every positive integer $n$.


@q 7
@marks 5
@question
The modulus condition gives $a^2+b^2=|z|^2=25$. \\
Also $zz^*=(a+b\mathrm{i})(a-b\mathrm{i})=a^2+b^2=25$. \\
Therefore $\log_{5}(zz^*)=\log_{5}(25)=2$. \\
The second condition becomes $b+2=2a$, so $b=2a-2$. \\
Substitute in the first condition: $a^2+(2a-2)^2=25$. \\
$a^2+4a^2-8a+4=25$. \\
$5a^2-8a-21=0$. \\
Factor: $(a-3)(5a+7)=0$. \\
Thus $a=3$ or $a=-\frac{7}{5}$. \\
For $a=3$, $b=2(3)-2=4$. \\
For $a=-\frac{7}{5}$, $b=-\frac{14}{5}-\frac{10}{5}=-\frac{24}{5}$. \\
Hence $z=3+4\mathrm{i}$ or $z=-\frac{7}{5}-\frac{24}{5}\mathrm{i}$.


@q 8
@marks 7
@question
(a) All the fish are of the three named types, so $x+y+z=1400$. \\
There are 360 more carp than tench, so $x-y=360$. \\
(b) The net increase is $0.08x+0.05y-0.10z=70$. \\
(c) The equations form the matrix equation \\
$\begin{pmatrix}1&1&1\\1&-1&0\\0.08&0.05&-0.10\end{pmatrix}\begin{pmatrix}x\\y\\z\end{pmatrix}=\begin{pmatrix}1400\\360\\70\end{pmatrix}$. \\
Let the coefficient matrix be $A$. Since it is invertible, \\
$\begin{pmatrix}x\\y\\z\end{pmatrix}=A^{-1}\begin{pmatrix}1400\\360\\70\end{pmatrix}=\begin{pmatrix}800\\440\\160\end{pmatrix}$. \\
Check: $800+440+160=1400$ and $800-440=360$. \\
The change is $0.08(800)+0.05(440)-0.10(160)=64+22-16=70$. \\
Thus there were 800 carp, 440 tench and 160 pike initially.


@q 9
@marks 9
@question
(a) At an intersection the $y$ values agree: $18-2x^2=12-\frac{1}{2}x^2$. \\
Therefore $6=\frac{3}{2}x^2$, so $x^2=4$. \\
The two $x$ coordinates are $-2$ and $2$. \\
(b) Between these values $C$ lies above $D$ and both curves are above the $x$-axis. \\
Use outer disc minus inner disc: \\
$V=\pi\int_{-2}^{2}[(18-2x^2)^2-(12-\frac{1}{2}x^2)^2]\,dx$. \\
Expand the first square: $324-72x^2+4x^4$. \\
Expand the second: $144-12x^2+\frac{1}{4}x^4$. \\
Subtract to obtain $180-60x^2+\frac{15}{4}x^4$. \\
Integrate: $V=\pi[180x-20x^3+\frac{3}{4}x^5]_{-2}^{2}$. \\
At $x=2$ the bracket is $360-160+24=224$. \\
At $x=-2$ it is $-360+160-24=-224$. \\
Thus $V=\pi(224-(-224))=448\pi\mathrm{\,mm^3}$. \\
Since $1000\mathrm{\,mm^3}=1\mathrm{\,cm^3}$, the mass of one ring is \\
$18(\frac{448\pi}{1000})=8.064\pi\mathrm{\,g}\approx25.33\mathrm{\,g}$. \\
$1000/(8.064\pi)\approx39.47$, so 1 kg makes 39 complete rings.


@q 10
@marks 13
@question
(a) Subtract coordinates: $\text{PQ}=Q-P=(0,-2,-1)$. \\
Also $\text{PR}=R-P=(-3,1,1)$. \\
These independent directions span the plane through $P$, so \\
$\mathbf{r}=(3,2,-1)+\lambda(0,-2,-1)+\mu(-3,1,1)$. \\
(b) Let $\mathbf{n}=(1,-3,6)$. \\
$\text{PQ}\cdot\mathbf{n}=0(1)+(-2)(-3)+(-1)(6)=0$. \\
$\text{PR}\cdot\mathbf{n}=(-3)(1)+1(-3)+1(6)=0$. \\
Thus $\mathbf{n}=\mathbf{i}-3\mathbf{j}+6\mathbf{k}$ is perpendicular to both spanning directions, and so to $\text{Pi}$. \\
(c) Use $\mathbf{n}\cdot(\mathbf{r}-P)=0$. \\
Hence $x-3y+6z=3-3(2)+6(-1)=-9$. \\
(d) $\text{ST}=T-S=(-5-1,7-(-3),1-(-5))=(-6,10,6)$. \\
The model line is $\mathbf{r}=(1,-3,-5)+t(-6,10,6)$. \\
(e) The real lawn may be uneven rather than exactly planar. \\
(f) The bar's middle is the midpoint of $S,T$: \\
$M=(\frac{1-5}{2},\frac{-3+7}{2},\frac{-5+1}{2})=(-2,2,-2)$. \\
The plane is $x-3y+6z+9=0$. \\
Distance from $M$ is $\frac{|-2-3(2)+6(-2)+9|}{\sqrt{1^2+(-3)^2+6^2}}$. \\
$=\frac{11}{\sqrt{46}}\mathrm{\,m}\approx1.62186\mathrm{\,m}$. \\
To the nearest centimetre, this is $1.62\mathrm{\,m}$ or $162\mathrm{\,cm}$. \\
(g) The actual distance, $1.7\mathrm{\,m}$, exceeds the model value by about $0.08\mathrm{\,m}$. \\
This is a fairly small difference, so the model gives a reasonable estimate.
