@paper AS Core Pure June 2019

@q 1
@topic Matrix transformations
@marks 6
@question
(a) Find the determinant: \\
$det(M)=4(-7)-(-5)(2)$ \\
$=-28+10$ \\
$=-18$ \\
Since $det(M)\neq0$, the matrix is non-singular \\
(b) The area scale factor is the absolute value of the determinant: \\
$|det(M)|=18$ \\
The transformed area is 18 times the original area: \\
$63=18Area(R)$ \\
$Area(R)=63/18$ \\
$Area(R)=3.5$ square units \\
(c) A direction vector for $y=2x$ is $(1,2)$ \\
Apply the matrix: \\
$M\begin{pmatrix}1\\2\end{pmatrix}=\begin{pmatrix}4&-5\\2&-7\end{pmatrix}\begin{pmatrix}1\\2\end{pmatrix}$ \\
$=\begin{pmatrix}4-10\\2-14\end{pmatrix}$ \\
$=\begin{pmatrix}-6\\-12\end{pmatrix}=-6\begin{pmatrix}1\\2\end{pmatrix}$ \\
The direction is unchanged apart from a scale and reversal \\
Since the line passes through the origin, it maps onto itself

@q 2
@topic Transformation of cubic roots
@marks 5
@question
Let $w=x+3$, so the inverse transformation is $x=w-3$ \\
Substitute $w-3$ for $x$: \\
$2(w-3)^3+6(w-3)^2-3(w-3)+12=0$ \\
Expand the powers: \\
$2(w^3-9w^2+27w-27)+6(w^2-6w+9)-3w+9+12=0$ \\
Distribute: \\
$2w^3-18w^2+54w-54+6w^2-36w+54-3w+9+12=0$ \\
Collect like terms: \\
$2w^3-12w^2+15w+21=0$

@q 3
@topic Induction and telescoping sums
@marks 6
@question
For $n=1$, the left side is $\frac{1}{(1)(3)}=\frac13$ \\
The right side is $\frac{1}{2(1)+1}=\frac13$ \\
So the statement is true for $n=1$ \\
Assume it is true for $n=k$: \\
$\sum_{r=1}^{k}\frac{1}{(2r-1)(2r+1)}=\frac{k}{2k+1}$ \\
Now add the term for $r=k+1$: \\
$\sum_{r=1}^{k+1}\frac{1}{(2r-1)(2r+1)}=\frac{k}{2k+1}+\frac{1}{(2k+1)(2k+3)}$ \\
Use a common denominator: \\
$=\frac{k(2k+3)+1}{(2k+1)(2k+3)}$ \\
Expand the numerator: \\
$=\frac{2k^2+3k+1}{(2k+1)(2k+3)}$ \\
Factor the numerator: \\
$=\frac{(k+1)(2k+1)}{(2k+1)(2k+3)}$ \\
Cancel the common factor: \\
$=\frac{k+1}{2k+3}$ \\
$=\frac{k+1}{2(k+1)+1}$ \\
Thus the statement for $k$ implies the statement for $k+1$ \\
It is true for $n=1$, so by induction it holds for all positive integers $n$

@q 4
@topic Lines and planes in three dimensions
@marks 5
@question
Read a point and direction vector from the symmetric line equation: \\
Point $A=(-2,5,4)$ \\
Direction vector $\mathbf{d}=(1,-1,-3)$ \\
The plane normal is $\mathbf{n}=(1,-2,1)$ \\
Check the direction against the normal: \\
$\mathbf{d}\cdot\mathbf{n}=1(1)+(-1)(-2)+(-3)(1)$ \\
$=1+2-3$ \\
$=0$ \\
So the line direction is parallel to the plane \\
Check whether the point lies on the plane: \\
$(-2)-2(5)+4=-2-10+4$ \\
$=-8$ \\
The plane requires the value $-7$, so $A$ is not on the plane \\
Therefore the line is parallel to the plane and does not intersect it

@q 5
@topic Complex numbers and Argand diagrams
@marks 9
@question
(a) Since the coefficients are real, if $z_2=-1+2i$ is a root, its conjugate $-1-2i$ must also be a root \\
If $z_3=1+i$ is a root, its conjugate $1-i$ must also be a root \\
Together with $z_1$, these would be five distinct roots \\
A quartic has at most four roots, so these three cannot all be roots of a real quartic \\
(b) Find the differences: \\
$z_2-z_1=(-1+2i)-(-2)=1+2i$ \\
$z_3-z_1=(1+i)-(-2)=3+i$ \\
Divide and rationalise: \\
$\frac{1+2i}{3+i}=\frac{(1+2i)(3-i)}{(3+i)(3-i)}$ \\
$=\frac{3-i+6i-2i^2}{10}$ \\
$=\frac{5+5i}{10}$ \\
$=\frac{1+i}{2}$ \\
Its real and imaginary parts are equal and positive, so its argument is $\pi/4$ \\
(c) The argument of $z_2-z_1=1+2i$ is $\arctan(2)$ \\
The argument of $z_3-z_1=3+i$ is $\arctan(1/3)$ \\
The argument of the quotient is the difference: \\
The argument of the quotient is $\arctan(2)-\arctan(1/3)$ \\
From part (b), this equals $\pi/4$ \\
(d) Write $z=x+iy$ and square both sides of the inequality: \\
$(x+2)^2+y^2\leq(x-1)^2+(y-1)^2$ \\
Expand: \\
$x^2+4x+4+y^2\leq x^2-2x+1+y^2-2y+1$ \\
Cancel common terms and simplify: \\
$6x+2y+2\leq0$ \\
$3x+y+1\leq0$ \\
Draw the boundary line $3x+y+1=0$ as a solid line \\
Test $z=-2$, giving $3(-2)+0+1=-5\leq0$ \\
Shade the half-plane on the side containing $(-2,0)$

@q 6
@topic Arithmetic sequences and deviation
@marks 9
@question
The masses form an arithmetic sequence with first term 10 and common difference 3 \\
Equivalently, the $r$th mass is $7+3r$ \\
(a) Find the total mass: \\
$\sum_{r=1}^{n}(7+3r)=7n+3\sum_{r=1}^{n}r$ \\
Use $\sum r=n(n+1)/2$: \\
$=7n+\frac32n(n+1)$ \\
Divide by $n$ to obtain the mean mass: \\
$=7+\frac32(n+1)$ \\
$=\frac12(14+3n+3)$ \\
$=\frac12(3n+17)$ \\
(b) For $n=85$, the mean is \\
$\frac12(3(85)+17)=\frac12(272)=136$ \\
Square and sum the masses: \\
$\sum(7+3r)^2=\sum(49+42r+9r^2)$ \\
$=49n+42\sum r+9\sum r^2$ \\
Use $\sum r=\frac{n(n+1)}2$ and $\sum r^2=\frac{n(n+1)(2n+1)}6$ \\
For $n=85$: \\
$\sum(7+3r)^2=49(85)+42\frac{85(86)}2+9\frac{85(86)(171)}6$ \\
$=4165+153510+1875015$ \\
$=2032690$ \\
Divide by 85 to find the mean of the squared masses: \\
$E(X^2)=2032690/85=23914$ \\
Find the variance: \\
$Var(X)=23914-136^2$ \\
$=23914-18496$ \\
$=5418$ \\
Take the square root: \\
$s=\sqrt{5418}$ \\
$s=73.606\ldots$ grams \\
To one decimal place, the standard deviation is 73.6 grams

@q 7
@topic Cubic equations and complex roots
@marks 8
@question
For a monic cubic, the sum of the roots is 8 \\
Use the given three roots: \\
$\alpha+\beta+(\alpha+\frac{12}{\alpha}-\beta)=8$ \\
Cancel $\beta$ and $-\beta$: \\
$2\alpha+\frac{12}{\alpha}=8$ \\
Multiply by $\alpha$: \\
$2\alpha^2+12=8\alpha$ \\
Rearrange and divide by 2: \\
$\alpha^2-4\alpha+6=0$ \\
Solve the quadratic: \\
$\alpha=\frac{4\pm\sqrt{16-24}}{2}$ \\
$=\frac{4\pm\sqrt{-8}}{2}$ \\
$=2\pm\sqrt{2}i$ \\
The coefficients are real, so the conjugate pair $2+\sqrt{2}i$ and $2-\sqrt{2}i$ are roots \\
The sum of all three roots is 8, so the remaining root is \\
$8-(2+\sqrt{2}i)-(2-\sqrt{2}i)=4$ \\
Thus the roots are $2+\sqrt{2}i$, $2-\sqrt{2}i$ and 4 \\
The coefficient $p$ is the sum of pairwise products: \\
$p=4(2+\sqrt{2}i)+4(2-\sqrt{2}i)+(2+\sqrt{2}i)(2-\sqrt{2}i)$ \\
$=8+4\sqrt{2}i+8-4\sqrt{2}i+(4+2)$ \\
$=16+6$ \\
$p=22$

@q 8
@topic Lines, planes and shortest distances
@marks 12
@question
(a) Find a direction vector from $P$ to $Q$: \\
$Q-P=(300-(-300),300-400,-50-(-150))$ \\
$=(600,-100,100)=100(6,-1,1)$ \\
Thus one vector equation is \\
$\mathbf{r}=(-300,400,-150)+\lambda(6,-1,1)$ \\
(b) Use $M=(100,k,100)$ in the plane equation: \\
$2(100)+3k-5(100)=300$ \\
$200+3k-500=300$ \\
$3k=600$ \\
$k=200$, so $M=(100,200,100)$ \\
Let $\mathbf{d}=(6,-1,1)$ and project $M-P=(400,-200,250)$ onto the line: \\
$\lambda=\frac{(M-P)\cdot\mathbf{d}}{\mathbf{d}\cdot\mathbf{d}}$ \\
$=\frac{400(6)+(-200)(-1)+250(1)}{6^2+(-1)^2+1^2}$ \\
$=\frac{2400+200+250}{38}$ \\
$=\frac{2850}{38}=75$ \\
Substitute into the line equation: \\
$P+75\mathbf{d}=(-300,400,-150)+(450,-75,75)$ \\
$=(150,325,-75)$ \\
The vector from this point to $M$ is \\
$(100,200,100)-(150,325,-75)=(-50,-125,175)$ \\
Its length is \\
$\sqrt{(-50)^2+(-125)^2+175^2}$ \\
$=\sqrt{2500+15625+30625}$ \\
$=\sqrt{48750}=25\sqrt{78}$ m \\
(c) Compare with the existing accessways: \\
$OP=\sqrt{(-300)^2+400^2+(-150)^2}=\sqrt{272500}$ m \\
$OQ=\sqrt{300^2+300^2+(-50)^2}=\sqrt{182500}$ m \\
Both existing distances are much greater than $25\sqrt{78}$ m \\
Therefore the new accessway is significantly shorter and should be built \\
(d) One limitation is that the pipeline may not be perfectly straight in reality

@q 9
@topic Integration and volume of revolution
@marks 8
@question
For a full revolution, volume is $\pi\int y^2\,dx$ \\
An angle of $\theta$ radians is the fraction $\theta/(2\pi)$ of a full turn \\
Therefore $V=\frac{\theta}{2}\int_{1/8}^{8}y^2\,dx$ \\
Square the curve equation: \\
$y^2=(2x^{1/3}+x^{-2/3})^2$ \\
$=4x^{2/3}+4x^{-1/3}+x^{-4/3}$ \\
Integrate each term: \\
$\int y^2\,dx=\frac{12}{5}x^{5/3}+6x^{2/3}-3x^{-1/3}$ \\
Evaluate at $x=8$: \\
$\frac{12}{5}(32)+6(4)-3(\frac12)=\frac{384}{5}+24-\frac32=\frac{993}{10}$ \\
Evaluate at $x=\frac18$: \\
$\frac{12}{5}(\frac1{32})+6(\frac14)-3(2)=\frac3{40}+\frac32-6=-\frac{177}{40}$ \\
Subtract the lower value from the upper: \\
$\frac{993}{10}-(-\frac{177}{40})=\frac{3972+177}{40}=\frac{4149}{40}$ \\
Substitute the given volume: \\
$\frac{\theta}{2}\cdot\frac{4149}{40}=\frac{461}{2}$ \\
$\theta=\frac{461}{2}\cdot\frac{80}{4149}$ \\
Since $4149=9(461)$, \\
$\theta=\frac{40}{9}$ radians

@q 10
@topic Matrices and population models
@marks 12
@question
(a) The coefficient $a$ multiplies the current juvenile population in the equation for next year's juveniles \\
It represents the proportion of juveniles that remain juvenile the following year \\
(b)(i) The transition matrix is $T=[a,0.15;0.08,0.82]$ \\
Its determinant is \\
$det(T)=0.82a-(0.15)(0.08)=0.82a-0.012$ \\
Use the inverse formula for a $2$ by $2$ matrix: \\
$T^{-1}=\frac{1}{0.82a-0.012}[0.82,-0.15;-0.08,a]$ \\
(ii) The one-year population vector is $(15360,43008)^T$ \\
Apply the inverse to find the starting population: \\
$J_0=\frac{0.82(15360)-0.15(43008)}{0.82a-0.012}=\frac{6144}{0.82a-0.012}$ \\
$A_0=\frac{-0.08(15360)+a(43008)}{0.82a-0.012}=\frac{43008a-1228.8}{0.82a-0.012}$ \\
The starting total is 64000: \\
$\frac{43008a+4915.2}{0.82a-0.012}=64000$ \\
$43008a+4915.2=52480a-768$ \\
$5683.2=9472a$ \\
$a=0.6$ \\
(iii) Find the starting number of juveniles: \\
$J_0=\frac{6144}{0.82(0.6)-0.012}$ \\
$=\frac{6144}{0.48}=12800$ \\
The change in the first year is \\
$15360-12800=2560$ \\
So juvenile numbers increase by 2560 \\
(c) The model predicts an increase, but juvenile numbers are known to decline \\
Therefore it is unsuitable even in the short term \\
(d) Separate adults into breeding adults under 40 and non-breeding adults aged 40 or over \\
Only the under-40 adult group should contribute to the juvenile births term, with the known coefficient 0.15 \\
This reflects that adults aged 40 and over no longer reproduce
