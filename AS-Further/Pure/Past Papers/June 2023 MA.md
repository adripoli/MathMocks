@paper AS Core Pure June 2023

@q 1
@topic Matrix equations
@marks 4
@question
The off-diagonal entries of $kI$ are zero \\
$9-3y=0$, so $y=3$ \\
$y-3z=0$, so $z=1$ \\
The two diagonal entries must be equal: $x-3z=z-3y$ \\
$x-3=1-9=-8$, so $x=-5$

@q 2
@topic Complex roots and transformations
@marks 7
@question
Because the coefficients are real, the conjugate $-3-4i$ is a root too \\
Let the third root be $r$ \\
The product of the roots is $-175$: \\
$(-3+4i)(-3-4i)r=-175$ \\
$25r=-175$, so $r=-7$ \\
Form the factors: \\
$f(z)=(z+3-4i)(z+3+4i)(z+7)$ \\
$=(z^2+6z+25)(z+7)$ \\
$=z^3+13z^2+67z+175$ \\
Thus $a=13$ and $b=67$ \\
(b) Plot the roots at $(-3,4)$, $(-3,-4)$ and $(-7,0)$ \\
(c) For $f(z+2)=0$, $z+2$ must be an original root \\
Subtract $2$ from each root: $-5+4i$, $-5-4i$, and $-9$

@q 3
@topic 3D rotations and matrix composition
@marks 4
@question
The $yz$ block of $A$ is the rotation matrix with $\cos\theta=\sqrt3/2$ and $\sin\theta=1/2$ \\
Thus $A$ is a $30$ degree anticlockwise rotation about the $x$-axis \\
For A followed by B, the combined matrix is $BA$, not $AB$ \\
Multiply: $BA=\begin{pmatrix}1&3&0\\sqrt3&0&5\sqrt3\\1&2&0\end{pmatrix}\begin{pmatrix}1&0&0\\0&\sqrt3/2&-1/2\\0&1/2&\sqrt3/2\end{pmatrix}$ \\
$C=\begin{pmatrix}1&3\sqrt3/2&-3/2\\sqrt3&5\sqrt3/2&15/2\\1&\sqrt3&-1\end{pmatrix}$

@q 4
@topic Complex numbers and powers
@marks 8
@question
(i)(a) Multiply top and bottom by the conjugate $5-i$: \\
$\\frac{2+3i}{5+i}=\\frac{(2+3i)(5-i)}{(5+i)(5-i)}$ \\
$=\\frac{10-2i+15i-3i^2}{26}$ \\
$=\\frac{13+13i}{26}=\\frac12(1+i)$ \\
Thus $k=1/2$ \\
(i)(b) The argument of $1+i$ is $\pi/4$ \\
The power is real when $n\pi/4$ is an integer multiple of $\pi$ \\
The least positive such integer is $n=4$ \\
(ii) $|z|^{10}=59049=3^{10}$, so $|z|=3$ \\
The argument condition gives $10argument of z=-5\pi/3+2m\pi$ \\
$argument of z=-\pi/6+m\pi/5$ \\
Equivalently, the ten roots have arguments $\\theta=\pi/30+k\pi/5$ for $k=0,1,\\ldots,9$ \\
For each root, $a=3\cos\\theta$ and $b=3\sin\\theta$ \\
For example, $k=0$ gives $a=3\cos(\pi/30)$ and $b=3\sin(\pi/30)$

@q 5
@topic Volume of revolution and modelling
@marks 8
@question
Rearrange the curve to express the squared radius in terms of $y$: \\
$x^2=2-y$ \\
The region runs from $y=0$ to $y=2$ \\
Rotate about the $y$-axis, so $V=\pi\int_0^2x^2\\,dy$ \\
$V=\pi\int_0^2(2-y)\\,dy$ \\
$=\pi[2y-y^2/2]_0^2$ \\
$=\pi(4-2)=2\pi\text{ m}^3$ \\
Mass is density times volume: \\
$m=900(2\pi)=1800\pi\\approx5655$ kg \\
To 2 significant figures, the estimated mass is $5700$ kg \\
(b) The actual pile may not be rotationally symmetric or have a smooth surface \\
(c) The estimate differs from $5500$ kg by about $200$ kg, only a few percent, so it is a reasonable model estimate

@q 6
@topic Lines and planes in 3D
@marks 11
@question
(a) Direction vectors are $(3,0,1)$ and $(1,2,-3)$ \\
Their dot product is $3-3=0$, so the lines are perpendicular \\
(b) The plane's normal is $(1,2,-3)$ and it passes through $(-2,2,0)$ \\
$x+2y-3z=-2+4=2$ \\
(c) Substitute $(3,1,1)$: $3+2-3=2$, so $A$ lies on the plane \\
(d) Parameterise $l_2$ from its intersection with the plane: \\
$B=(2+t,3+2t,2-3t)$ \\
Use the distance condition from $A=(3,1,1)$: \\
$AB^2=(t-1)^2+(2+2t)^2+(1-3t)^2$ \\
$=t^2-2t+1+4+8t+4t^2+1-6t+9t^2$ \\
$=14t^2+6$ \\
$14t^2+6=(2\sqrt5)^2=20$, so $t^2=1$ \\
If $t=1$, $B=(3,5,-1)$, not all coordinates positive \\
If $t=-1$, $B=(1,1,5)$, which satisfies the conditions

@q 7
@topic Argand loci and arguments
@marks 9
@question
Write $z=x+iy$ and square the distance inequality: \\
$(x-3)^2+y^2\leq x^2+(y+6)^2$ \\
Cancel common terms and simplify: \\
$-6x+9\leq12y+36$ \\
$2x+4y+9\\geq0$ \\
Shade the half-plane above the line; the origin satisfies the inequality \\
(ii) Let $w=x+iy$ \\
From $argument of(w-2)=\pi/3$, $y=\sqrt3(x-2)$ \\
From $argument of(w+1)=\pi/6$, $y=(x+1)/\sqrt3$ \\
Equate: $\sqrt3(x-2)=(x+1)/\sqrt3$ \\
$3x-6=x+1$, so $x=7/2$ \\
$y=\sqrt3(7/2-2)=3\sqrt3/2$ \\
Therefore $w=7/2+(3\sqrt3/2)i$

@q 8
@topic Summation of odd squares
@marks 8
@question
(a) Expand the summand: \\
$(2r+1)^2=4r^2+4r+1$ \\
Sum term by term: \\
$4\\sum r^2+4\\sum r+\\sum1$ \\
$=4\\frac{n(n+1)(2n+1)}6+4\\frac{n(n+1)}2+n$ \\
Factor $n/3$: \\
$=\\frac n3[2(n+1)(2n+1)+6(n+1)+3]$ \\
$=\\frac n3(4n^2+12n+11)$ \\
(b) The odd three-digit numbers are $2r+1$ for $50\leq r\leq499$ \\
Subtract the first 49 terms from the first 499 terms: \\
$S_{499}-S_{49}$, where $S_n=\\frac n3(4n^2+12n+11)$ \\
$=166499850$

@q 9
@topic Determinants and transformations
@marks 9
@question
(i) Expand the determinant along the first row: \\
$det(P)=k((-5)(4)-2k)-(-2)((-3)(4)-2k)+7((-3)k-(-5)k)$ \\
$=-20k-2k^2-24-4k+14k$ \\
$=-2k^2-10k-24$ \\
Complete the square: \\
$det(P)=-2(k^2+5k+12)$ \\
$=-2[(k+5/2)^2+23/4]$ \\
The bracket is positive for every real $k$, so the determinant is never zero \\
(ii) Transform each point using $Q$: \\
$A'=Q(a,2)=(2a-2,-3a)$ \\
$B'=Q(4,-a)=(8+a,-12)$ \\
Apply the distance condition: \\
$[(2a-2)-(8+a)]^2+[-3a-(-12)]^2=58$ \\
$(a-10)^2+(12-3a)^2=58$ \\
$a^2-20a+100+9a^2-72a+144=58$ \\
$10a^2-92a+186=0$ \\
$5a^2-46a+93=0$ \\
$(a-3)(5a-31)=0$ \\
$a=3$ or $a=31/5$

@q 10
@topic Polynomial transformations and roots
@marks 12
@question
(i) Let $w=3z-1$, so $z=(w+1)/3$ \\
Substitute into the original equation: \\
$((w+1)/3)^4+5((w+1)/3)^2-30=0$ \\
Multiply by $81$: \\
$(w+1)^4+45(w+1)^2-2430=0$ \\
Expand: \\
$w^4+4w^3+6w^2+4w+1+45w^2+90w+45-2430=0$ \\
$w^4+4w^3+51w^2+94w-2384=0$ \\
(ii)(a) The sum of roots is zero: $\alpha+2\alpha+(\alpha-\beta)=0$ \\
$4\alpha-\beta=0$, hence $\beta=4\alpha$ \\
The product of roots is $-81/4$: \\
$\alpha(2\alpha)(\alpha-4\alpha)=-6\alpha^3=-81/4$ \\
$\alpha^3=27/8$, so $\alpha=3/2$ \\
The roots are $3/2$, $3$, and $-9/2$ \\
(ii)(b) The sum of pairwise products is $n/4$: \\
$(3/2)(3)+(3/2)(-9/2)+3(-9/2)=9/2-27/4-27/2=-63/4$ \\
Thus $n/4=-63/4$, so $n=-63$
