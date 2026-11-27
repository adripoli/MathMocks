@paper AS Core Pure June 2024

@q 1
@topic Roots and symmetric expressions
@marks 9
@question
For the monic cubic, the sum of roots is $3/2$, the pair sum is $5/2$, and the product is $-7/2$ \\
(i) Use $\sum\alpha^2=(\sum\alpha)^2-2\sum\alpha\beta$ \\
$=(3/2)^2-2(5/2)=9/4-5=-11/4$ \\
(ii) Use $1/\alpha+1/\beta+1/\gamma=(\alpha\beta+\alpha\gamma+\beta\gamma)/(\alpha\beta\gamma)$ \\
$3\sum1/\alpha=3(5/2)/(-7/2)=-15/7$ \\
(iii) $f(5)=2(5-\alpha)(5-\beta)(5-\gamma)$ \\
$f(5)=2(125)-3(25)+5(5)+7=207$ \\
Thus $(5-\alpha)(5-\beta)(5-\gamma)=207/2$

@q 2
@topic Rotations, reflections and vectors
@marks 10
@question
Compare the top-left block of $M$ with the rotation matrix: $\cos\\alpha=-\\sqrt3/2$ and $\sin\\alpha=-1/2$ \\
Thus $\alpha=210$ degrees \\
For $M^k=I$, require $210k$ to be a multiple of $360$ \\
The least positive integer satisfying this is $k=12$ \\
(c) Reflection in $y=0$ changes the sign of the $y$ coordinate: $N=\\operatorname{diag}(1,-1,1)$ \\
(d) Apply $M$ to $A$: \\
$MA=(-2-\\sqrt3,1-2\\sqrt3,3)$ \\
Then apply $N$: \\
$B=(-2-\\sqrt3,-(1-2\\sqrt3),3)=(2+\\sqrt3,2\\sqrt3-1,3)$ \\
(e) $OA^2=OB^2=29$ \\
$OA\\cdot OB=(-2)(2+\\sqrt3)+4(2\\sqrt3-1)+9=1+6\\sqrt3$ \\
$\\cos\\theta=(1+6\\sqrt3)/29$, so $\theta=66.9$ degrees to 3 s.f. \\
(f) Area $=\\frac12OA\\,OB\\sin\\theta=\\frac{29}{2}\\sin(66.9\\text{ degrees})\\approx13.3$

@q 3
@topic Summations and algebra
@marks 10
@question
(a) Expand $r^2(r+1)=r^3+r^2$ \\
$\\sum r^3+\\sum r^2=\\frac{n^2(n+1)^2}{4}+\\frac{n(n+1)(2n+1)}6$ \\
Factor $\\frac1{12}n(n+1)$: \\
$=\\frac1{12}n(n+1)[3n(n+1)+2(2n+1)]$ \\
$=\\frac1{12}n(n+1)(3n^2+7n+2)$ \\
$=\\frac1{12}n(n+1)(n+2)(3n+1)$, so $a=3,b=1$ \\
(b) Use $S(3k)-S(k)$: \\
$=\\frac1{12}(3k)(3k+1)(3k+2)(9k+1)-\\frac1{12}k(k+1)(k+2)(3k+1)$ \\
Factor $\\frac1{12}k(3k+1)$: \\
$=\\frac1{12}k(3k+1)[3(3k+2)(9k+1)-(k+1)(k+2)]$ \\
$=\\frac13k(3k+1)(20k^2+15k+1)$ \\
Thus $A=20,B=15,C=1$ \\
(c) Substitute the formula: \\
$\\frac{25}{3}k(3k+1)(20k^2+15k+1)=192k^3(3k+1)$ \\
Cancel the positive factors $k(3k+1)$ and multiply by $3$: \\
$25(20k^2+15k+1)=576k^2$ \\
$76k^2-375k-25=0$ \\
Solve: $k=5$ or a negative non-integer root \\
The positive integer solution is $k=5$

@q 4
@topic Matrices and simultaneous equations
@marks 8
@question
(a) Multiply $A$ and $B$; the diagonal entries simplify to $3k+1$ and off-diagonal entries to zero \\
Thus $AB=(3k+1)I$, so $c=1$ \\
(b) The determinant is $3k+1$ because $AB=(3k+1)I$ and $B$ is the adjugate \\
It is singular when $3k+1=0$, giving $k=-1/3$ \\
(c) Since $AB=(3k+1)I$, $A^{-1}=B/(3k+1)$ \\
(d) In matrix form, $A(x,y,z)^T=(10,3,1)^T$ \\
Multiply by the inverse: \\
$(x,y,z)^T=\\frac1{3k+1}B(10,3,1)^T$ \\
The components are $47k-21$, $-110$, and $33-11k$ \\
Therefore $x=(47k-21)/(3k+1)$, $y=-110/(3k+1)$, $z=(33-11k)/(3k+1)$

@q 5
@topic Complex loci and circular segments
@marks 10
@question
(a) $|z+5-12i|=|z-(-5+12i)|$, so the centre is $(-5,12)$ and radius is $10$ \\
(b) Shade the closed disk, including its circumference \\
(c) The centre is $\\sqrt{(-5)^2+12^2}=13$ from the origin \\
The greatest possible modulus is $13+10=23$ \\
(d) The argument condition selects the half-plane $y\\geq20$ \\
The chord is 8 units above the centre, and the half-chord is $\\sqrt{10^2-8^2}=6$ \\
The central angle is $\\theta=2\\cos^{-1}(8/10)=1.287\\ldots$ radians \\
The segment area is sector minus triangle: \\
$\\frac12(10^2)\\theta-\\frac12(12)(8)=16.35\\ldots$ \\
To 3 significant figures, area is $16.4$ square units

@q 6
@topic Lines and shortest distance in 3D
@marks 12
@question
(a) A direction vector is $B-A=(-5,-12,-1)$; reverse it to $(5,12,1)$ \\
$\\mathbf r=(3,4,-2)+\\lambda(5,12,1)$ \\
(b) The $z$ coordinate is $-2+\\lambda$ \\
Set it to zero: $\\lambda=2$ \\
Then $(x,y,z)=(3+10,4+24,0)=(13,28,0)$ \\
(c) Directions are $d_1=(5,12,1)$ and $d_2=(2,4,-2)$ \\
$d_1\\cdot d_2=10+48-2=56$ \\
$|d_1|=\\sqrt{170}$ and $|d_2|=\\sqrt{24}$ \\
$\\cos\\theta=56/(\\sqrt{170}\\sqrt{24})$, so the acute angle is $28.8$ degrees \\
(d) Let points on the lines be $P=(3,4,-2)+\\lambda d_1$ and $Q=(1,3,-1)+\\mu d_2$ \\
At the shortest segment, $P-Q$ is perpendicular to both directions \\
Solving the two dot-product equations gives a common perpendicular of length $10/\\sqrt{59}$ \\
Thus the shortest distance is approximately $1.30$ m

@q 7
@topic Induction and divisibility
@marks 10
@question
(i) At $n=1$, the left side is $1/(1\\cdot2)=1/2$, equal to $1/(1+1)$ \\
Assume $\\sum_{r=1}^k1/[r(r+1)]=k/(k+1)$ \\
Add the next term: \\
$\\sum_{r=1}^{k+1}1/[r(r+1)]=k/(k+1)+1/((k+1)(k+2))$ \\
$=[k(k+2)+1]/((k+1)(k+2))$ \\
$=(k+1)^2/((k+1)(k+2))=(k+1)/(k+2)$ \\
This is the formula with $n=k+1$; induction proves it for all positive integers \\
(ii) $f(1)=3^6-2^2=729-4=725$, divisible by $5$ \\
Assume $f(k)=3^{2k+4}-2^{2k}$ is divisible by $5$ \\
$f(k+1)=3^{2k+6}-2^{2k+2}$ \\
$=9(3^{2k+4})-4(2^{2k})$ \\
$=9(3^{2k+4}-2^{2k})+5(2^{2k})$ \\
$=9f(k)+5(2^{2k})$ \\
Both terms are divisible by $5$, so $f(k+1)$ is divisible by $5$ \\
By induction, $f(n)$ is divisible by $5$ for every positive integer $n$

@q 8
@topic Volumes of revolution and modelling
@marks 11
@question
(a) Substitute $(x,y)=(0.4,4)$: \\
$0.4=16k+\\sqrt4=16k+2$ \\
$16k=-1.6$, so $k=-0.1$ \\
(b) The section from $y=4$ to $4.5$ is a cylinder of radius $0.4$ and height $0.5$ \\
$V_c=\\pi(0.4)^2(0.5)=0.08\\pi=2\\pi/25$ \\
For $0\\leq y\\leq4$, $x=\\sqrt y-0.1y^2$ \\
$x^2=y-0.2y^{5/2}+0.01y^4$ \\
$V_r=\\pi\\int_0^4x^2dy$ \\
$=\\pi[y^2/2-(2/35)y^{7/2}+y^5/500]_0^4$ \\
$=\\pi(8-256/35+256/125)$ \\
Add the cylinder: $V=\\pi(8-256/35+256/125+2/25)$ \\
$V=2462\\pi/875\\text{ cm}^3$ \\
(c) The real glass may have imperfections, bubbles, or a non-smooth surface \\
(d) $2462\\pi/875\\approx8.84\\text{ cm}^3$, only about $0.16\\text{ cm}^3$ below the actual $9$ \\
This is a close prediction, so the model is suitable for this volume estimate
