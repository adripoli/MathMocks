@paper AS Core Pure Specimen

@q 1
@marks 5
@question
(a) First apply $P$, then $Q$, so multiply in the order $M=QP$. \\
Multiplying $Q$ changes the sign of the first row of $P$. \\
$M$ has rows $(-\frac{1}{2},-\frac{\sqrt{3}}{2})$; $(-\frac{\sqrt{3}}{2},\frac{1}{2})$. \\
(b) An invariant point $(x,y)$ satisfies $M(x,y)=(x,y)$. \\
First component: $-\frac{1}{2}x-\frac{\sqrt{3}}{2}y=x$. \\
Multiply by 2: $-x-\sqrt{3}y=2x$. \\
$-\sqrt{3}y=3x$. \\
$y=-\sqrt{3}x$. \\
Second component: $-\frac{\sqrt{3}}{2}x+\frac{1}{2}y=y$. \\
Multiply by 2: $-\sqrt{3}x+y=2y$. \\
$y=-\sqrt{3}x$. \\
Both equations define the same line, so every point on $y=-\sqrt{3}x$ is invariant.


@q 2
@marks 6
@question
(a) $|z-(4+2\mathrm{i})|<3$ is the open disc centred at $(4,2)$ with radius 3. \\
Draw its circle dashed because equality is excluded. \\
The argument range is the sector from the positive real axis up to the ray $y=x$ in the first quadrant. \\
Draw both rays solid, because the inequalities include their boundaries. \\
Shade only the part inside both the open disc and this closed sector. \\
(b) Subtract the centre from $z=5+4\mathrm{i}$: \\
$(5+4\mathrm{i})-(4+2\mathrm{i})=1+2\mathrm{i}$. \\
Its squared modulus is $1^{2}+2^{2}=5<9=3^{2}$. \\
The point is inside the disc. \\
It has positive real and imaginary parts, and $4<5$, so its angle is between 0 and $\frac{\pi}{4}$. \\
Equivalently $\mathrm{arg}(5+4\mathrm{i})=\tan^{-1}(\frac{4}{5})=0.6747...<0.7854...$. \\
It belongs to both sets, hence to $X$.


@q 3
@marks 8
@question
(a) Expand the determinant along the first row. \\
$\mathrm{det}(M)=3[3(2)-(-1)k]-2[2(2)-(-1)(1)]+[2k-3(1)]$. \\
$=3(6+k)-2(5)+(2k-3)$. \\
$=18+3k-10+2k-3$. \\
$=5k+5$. \\
(b)(i) The dot product gives $3x+2y+z=4$. \\
(ii) The plane directions are $(1,-1,-1)$ and $(1,0,2)$. \\
Their cross product is $(-2,-3,1)$, so take the opposite normal $(2,3,-1)$. \\
Use point $(1,2,3)$: $2(x-1)+3(y-2)-(z-3)=0$. \\
$2x-2+3y-6-z+3=0$. \\
$2x+3y-z=5$. \\
(c) A sheaf of three distinct planes shares a line of intersection. \\
Their three normal vectors must be linearly dependent, so the coefficient matrix has zero determinant. \\
$5k+5=0$, hence $k=-1$.


@q 4
@marks 9
@question
(a) Radios sold in year $n$: $500+50(n-1)=450+50n$. \\
Revenue is $(450+50n)(20+\frac{n^{2}}{45})$. \\
Profit is revenue minus cost: \\
$P_{n}=(450+50n)(20+\frac{n^{2}}{45})-(1000+10n^{2})$. \\
Expand: $9000+1000n+10n^{2}+\frac{10}{9}n^{3}-1000-10n^{2}$. \\
$=8000+1000n+\frac{10}{9}n^{3}$. \\
$=\frac{10}{9}(n^{3}+900n+7200)$ as required. \\
(b) Sum from $n=1$ to $N$: \\
$T_{N}=\frac{10}{9}[\sum n^{3}+900\sum n+7200N]$. \\
Use $\sum n^{3}=\frac{N^{2}(N+1)^{2}}{4}$ and $\sum n=\frac{N(N+1)}{2}$. \\
$T_{N}=\frac{10}{9}[\frac{N^{2}(N+1)^{2}}{4}+450N(N+1)+7200N]$. \\
Factor $\frac{5N}{18}$: \\
$T_{N}=\frac{5N}{18}[N(N+1)^{2}+1800(N+1)+28800]$. \\
Expand the bracket: $N^{3}+2N^{2}+N+1800N+1800+28800$. \\
$T_{N}=\frac{5N}{18}(N^{3}+2N^{2}+1801N+30600)$. \\
$a=\frac{5}{18}$, $b=2$, $c=1801$, $d=30600$. \\
(c) Substitute $N=20$: $T_{20}=419000$ pounds. \\
Actual profit just exceeds 500000 pounds, so the model underestimates by over 81000 pounds, more than 16% of the actual profit. It is a poor fit for the full contract.


@q 5
@marks 8
@question
(a) Since $f$ has real coefficients, complex roots come in conjugate pairs. \\
The other complex root is $\frac{1}{2}+\mathrm{i}\sqrt{3}$. \\
(b) Their quadratic factor is $(z-\frac{1}{2})^{2}+3$. \\
$=z^{2}-z+\frac{1}{4}+3=z^{2}-z+\frac{13}{4}$. \\
Multiply by 4: $4z^{2}-4z+13$. \\
Divide $f(z)$ by this factor: $f(z)=(4z^{2}-4z+13)(2z+5)$. \\
Thus the third root is $z=-\frac{5}{2}$. \\
All roots are $\frac{1}{2}-\mathrm{i}\sqrt{3}$, $\frac{1}{2}+\mathrm{i}\sqrt{3}$ and $-\frac{5}{2}$. \\
(c) Plot points $(\frac{1}{2},-\sqrt{3})$, $(\frac{1}{2},\sqrt{3})$ and $(-\frac{5}{2},0)$. \\
(d) Vertical separation of the conjugates is $2\sqrt{3}$. \\
From the real root to either complex root, horizontal separation is 3 and vertical separation is $\sqrt{3}$. \\
By Pythagoras, the distance is $\sqrt{3^{2}+(\sqrt{3})^{2}}=\sqrt{12}=2\sqrt{3}$. \\
All three side lengths are equal, so the triangle is equilateral.


@q 6
@marks 9
@question
(a) Base case $n=1$: $f(1)=1^{5}+4(1)=5$, divisible by 5. \\
Assume $f(k)=k^{5}+4k$ is divisible by 5. \\
For $k+1$, expand with the binomial theorem: \\
$f(k+1)=(k+1)^{5}+4(k+1)$. \\
$=k^{5}+5k^{4}+10k^{3}+10k^{2}+5k+1+4k+4$. \\
Group the assumed expression: \\
$=(k^{5}+4k)+5(k^{4}+2k^{3}+2k^{2}+k+1)$. \\
$=f(k)+5(k^{4}+2k^{3}+2k^{2}+k+1)$. \\
Both terms are divisible by 5, so $f(k+1)$ is divisible by 5. \\
The base case and induction step establish the result for all positive integers. \\
(b) $f(-x)=(-x)^{5}+4(-x)=-x^{5}-4x=-(x^{5}+4x)=-f(x)$. \\
(c) If $n<0$, then $-n>0$, and part (a) says $f(-n)$ is divisible by 5. \\
Part (b) gives $f(n)=-f(-n)$, also divisible by 5. \\
For $n=0$, $f(0)=0$, divisible by 5. \\
Thus the claim holds for all integers.


@q 7
@marks 13
@question
(a) Adults produce $0.23A_{n}$ million new juveniles. \\
Of surviving juveniles, two thirds remain juveniles. \\
Their number is $\frac{2}{3}(0.87)J_{n}=0.58J_{n}$. \\
$J_{n+1}=0.23A_{n}+0.58J_{n}$. \\
(b) The juvenile population in 2018 was $1.5-1.2=0.30$ million, so $p=0.30$. \\
Combine the adult and juvenile equations. \\
$M$ has first row $(0.97,0.29)$ and second row $(0.23,0.58)$. \\
(c)(i) One year before 2018 corresponds to $n=-1$. \\
Apply the inverse: $(A_{-1},J_{-1})=M^{-1}(1.2,0.3)$. \\
$=(1.228070...,0.030248...)$ million. \\
Add: $1.228070...+0.030248...=1.258318...$ million. \\
To 3 significant figures, total $=1.26$ million. \\
(c)(ii) 2025 is seven years after 2018. \\
$(A_{7},J_{7})=M^{7}(1.2,0.3)$. \\
$=(2.117333...,0.938132...)$ million. \\
Juveniles $=0.938$ million (3 sf). \\
(d) 15000 juveniles are $0.015$ million. \\
Subtract this after applying the annual transition: \\
$(A_{n+1},J_{n+1})=M(A_{n},J_{n})-(0,0.015)$, with $(A_{0},J_{0})=(1.2,0.30)$. \\
(e) The birth and survival rates are assumed fixed, but they may change.


@q 8
@marks 11
@question
(a) Rotating $R_{1}$ about the $x$-axis gives discs of radius $y=x^{2/3}$. \\
$V_{1}=\pi\int_{0}^{8}(x^{2/3})^{2}\,dx$. \\
$=\pi\int_{0}^{8}x^{4/3}\,dx$. \\
Use the power rule: $\int x^{4/3}dx=\frac{3}{7}x^{7/3}$. \\
$V_{1}=\pi[\frac{3}{7}x^{7/3}]_{0}^{8}$. \\
At 8: $8^{7/3}=(\sqrt[3]{8})^{7}=2^{7}=128$. \\
At 0: the antiderivative is 0. \\
$V_{1}=\pi\frac{3\cdot128}{7}=\frac{384\pi}{7}$ as required. \\
(b) At $x=8$, $y=8^{2/3}=4$. \\
For rotation about the $y$-axis, write $x=y^{3/2}$, so $x^{2}=y^{3}$. \\
$V_{2}=\pi\int_{0}^{4}y^{3}\,dy=\pi[\frac{y^{4}}{4}]_{0}^{4}$. \\
$=\pi\frac{4^{4}}{4}=64\pi$. \\
Probability of $V_{2}$ on one draw: \\
$p=\frac{V_{2}}{V_{1}+V_{2}}=\frac{64}{64+384/7}$. \\
$=\frac{448}{832}=\frac{7}{13}$. \\
Replacement makes 10 independent draws with the same $p$. \\
Use the binomial formula: \\
$P(X=8)=10C8(\frac{7}{13})^{8}(\frac{6}{13})^{2}$. \\
$=0.0677432...=0.0677$ (4 dp).


@q 9
@marks 11
@question
(a) Let $t$ be hours after monitoring starts. \\
$\text{OC}(t)=(146-21t,234-33t,-85+13t)$ in thousands of km. \\
The closest point on the line has position vector perpendicular to its direction. \\
$\text{OC}(t)\cdot(-21,-33,13)=0$. \\
Expand: $-21(146-21t)-33(234-33t)+13(-85+13t)=0$. \\
$-3066+441t-7722+1089t-1105+169t=0$. \\
$1699t-11893=0$, so $t=7$ hours. \\
Substitute: $\text{OC}(7)=(146-147,234-231,-85+91)=(-1,3,6)$. \\
Minimum distance $=\sqrt{(-1)^{2}+3^{2}+6^{2}}=\sqrt{46}=6.7823...$ thousand km. \\
The planet radius is $13000/2=6500$ km $=6.5$ thousand km. \\
Since $6.7823...>6.5$, the comet misses the planet under the model. \\
(b) After 4 hours $C=(146-84,234-132,-85+52)=(62,102,-33)$. \\
From $C$ to $A$: $\text{CA}=(5,0,12)-(62,102,-33)=(-57,-102,45)$. \\
From $C$ to $B$: $\text{CB}=(4,12,-3)-(62,102,-33)=(-58,-90,30)$. \\
Scalar product $\text{CA}\cdot\text{CB}=(-57)(-58)+(-102)(-90)+45(30)=13836$. \\
$|\text{CA}|=\sqrt{15678}$ and $|\text{CB}|=\sqrt{12364}$. \\
$\cos \theta=\frac{13836}{\sqrt{15678}\sqrt{12364}}$, where $\theta$ is angle $ACB$. \\
$\theta=6.3991...$ degrees. \\
To nearest 0.1 degree, $6.4$ degrees. \\
(c) The comet may be deflected by the planet's gravity, so its real position after 4 hours may differ.
