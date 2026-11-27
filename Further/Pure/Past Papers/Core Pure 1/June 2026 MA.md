@paper CP1 June 2026

@q 1
@topic Rotation about the y-axis
@marks 5
@question
Multiply $M$ by $(k,2,k)$ \\
The image is $(k\cos\theta+k\sin\theta,2,-k\sin\theta+k\cos\theta)$ \\
The plane condition gives $k(\cos\theta+\sin\theta)+k(\cos\theta-\sin\theta)=4$ \\
$2k\cos\theta=4$, so $k=2\sec\theta$ \\
With $k=4$, $4=2\sec\theta$, so $\cos\theta=1/2$ \\
Since $0<\theta<90$ degrees, $\theta=60$ degrees \\
Thus $M$ is a $\pi/3$ radian anticlockwise rotation (equivalently, $60$ degrees) about the $y$-axis

@q 2
@topic Complex numbers and conjugates
@marks 10
@question
$z^*=\lambda+2i$ and $z^2=(\lambda-2i)^2=\lambda^2-4\lambda i-4$ \\
$3z^*+z^2=3\lambda+6i+\lambda^2-4\lambda i-4$ \\
$=(\lambda^2+3\lambda-4)+i(6-4\lambda)$ \\
For this to be imaginary, its real part is zero: $\lambda^2+3\lambda-4=0$ \\
$(\lambda+4)(\lambda-1)=0$; since $\lambda>0$, $\lambda=1$ \\
Then $z=1-2i$, so $|z|=\sqrt{1^2+(-2)^2}=\sqrt{5}$ \\
The argument of $z$ is $-\tan^{-1}(2)\approx-1.11$ radians \\
Plot $z=(1,-2)$, $z^*=(1,2)$ and $3z^*+z^2=2i=(0,2)$

@q 3
@topic Sum of odd cubes
@marks 7
@question
Expand $(2r-1)^3=8r^3-12r^2+6r-1$ \\
Sum using $\sum r^3=n^2(n+1)^2/4$, $\sum r^2=n(n+1)(2n+1)/6$, and $\sum r=n(n+1)/2$ \\
Simplification gives $\sum_{r=1}^{n}(2r-1)^3=n^2(2n^2-1)$ \\
Thus $a=2$ and $b=-1$ \\
The odd numbers from $11$ through $99$ correspond to $r=6$ through $r=50$ \\
Required sum is $50^2(2(50)^2-1)-5^2(2(5)^2-1)$ \\
$=12,497,500-1,225=12,496,275$

@q 4
@topic Mean value of a function
@marks 5
@question
The mean value is $\frac15\int_0^5\frac{x+5}{x^2+25}dx$ \\
Split the integral: $\frac15[\int_0^5\frac{x}{x^2+25}dx+\int_0^5\frac{5}{x^2+25}dx]$ \\
The first integral is $\frac12\ln(x^2+25)|_0^5=\frac12\ln2$ \\
The second integral is $[\tan^{-1}(x/5)]_0^5=\pi/4$ \\
Mean value $=\frac1{10}\ln2+\frac1{20}\pi$ \\
Thus $a=1/10$ and $b=1/20$

@q 5
@topic Cubic roots and Vieta
@marks 5
@question
By Vieta, $\alpha+\beta+\gamma=156/16=39/4$ \\
$\alpha\beta+\alpha\gamma+\beta\gamma=260/16=65/4$ and $\alpha\beta\gamma=-75/16$ \\
Factor: $16x^3-156x^2+260x+75=(4x+1)(2x-5)(2x-15)$ \\
The roots are $-1/4,5/2,15/2$ \\
Since $\beta=3\alpha$, the matching pair is $\alpha=5/2$ and $\beta=15/2$ \\
Therefore $\gamma=-1/4$ and the exact roots are $5/2,15/2,-1/4$

@q 6
@topic Second-order differential equation
@marks 9
@question
The auxiliary equation is $m^2+4m+148=0$ \\
$m=(-4\pm\sqrt{16-592})/2=-2\pm12i$ \\
A constant particular solution satisfies $148x=4440$, so $x=30$ \\
Thus $x=30+e^{-2t}(A\cos12t+B\sin12t)$ \\
At $t=0$, $28=30+A$, so $A=-2$ \\
Differentiate: $x'=e^{-2t}[-2(A\cos12t+B\sin12t)-12A\sin12t+12B\cos12t]$ \\
At $t=0$, $47=-2A+12B=4+12B$, so $B=43/12$ \\
The particular solution is $x=30+e^{-2t}(-2\cos12t+(43/12)\sin12t)$

@q 7
@topic Complex geometric series
@marks 7
@question
(i) This is a geometric series with first term $e^{i\theta}$, common ratio $e^{2i\theta}$ and $10$ terms \\
$S=e^{i\theta}(1-e^{20i\theta})/(1-e^{2i\theta})$ \\
Use $1-e^{2iu}=-2ie^{iu}\sin u$ in numerator and denominator \\
Therefore $S=e^{10i\theta}\sin(10\theta)/\sin\theta$ \\
(ii) Combine the two real series: $P+iQ=\frac12e^{i\theta}+\frac14e^{3i\theta}+\frac18e^{5i\theta}+\cdots$ \\
This has first term $e^{i\theta}/2$ and common ratio $e^{2i\theta}/2$ \\
$P+iQ=(e^{i\theta}/2)/(1-e^{2i\theta}/2)$ \\
$=1/(2e^{-i\theta}-e^{i\theta})$

@q 8
@topic Trigonometry and volume of revolution
@marks 12
@question
Set $z=e^{i\theta}$, so $2\cos\theta=z+z^{-1}$ \\
$64\cos^7\theta=(z+z^{-1})^7$ \\
Expand and group conjugate powers: $(z^7+z^{-7})+7(z^5+z^{-5})+21(z^3+z^{-3})+35(z+z^{-1})$ \\
Therefore $a=1$, $b=7$, $c=21$, $d=35$ \\
(b) The base radius of the dome equals the cylinder radius, $16/2=8$ cm; at $y=0$, $x=k$ \\
Thus $k=8$ \\
(c) Cylinder volume is $\pi(8)^2(2)=128\pi$ cubic centimetres \\
Since $0\leq y\leq\pi/2$, $\sqrt{\cos^2y}=\cos y$ \\
Dome volume is $\pi\int_0^{\pi/2}(8\cos y)^2dy=64\pi[y/2+\sin2y/4]_0^{\pi/2}=16\pi^2$ \\
Total volume $=128\pi+16\pi^2\approx560$ cubic centimetres \\
(d) The actual object may not be rotationally symmetric or follow the model curve exactly

@q 9
@topic Coupled differential equations
@marks 15
@question
Differentiate $x'=-5x+y$: $x''=-5x'+y'$ \\
Use $y'=-2x-2y$ and $y=x'+5x$ \\
$x''=-5x'-2x-2(x'+5x)=-7x'-12x$ \\
Thus $x''+7x'+12x=0$ \\
The auxiliary roots are $-3$ and $-4$, so $x=Ae^{-3t}+Be^{-4t}$ \\
At $t=0$, $A+B=3$ \\
Initially $x'=-5(3)+1=-14$, so $-3A-4B=-14$ \\
Solving gives $A=-2$ and $B=5$, hence $x=-2e^{-3t}+5e^{-4t}$ \\
Use $y=x'+5x$ to get $y=-4e^{-3t}+5e^{-4t}$ \\
(d)(i) At $t=1/4$, $x=-2e^{-3/4}+5e^{-1}\approx0.895$ mg \\
(ii) Set $y=4x$: $-4e^{-3t}+5e^{-4t}=-8e^{-3t}+20e^{-4t}$ \\
$4e^t=15$, so $t=\ln(15/4)$ hours \\
(e) The model predicts $\ln(15/4)\approx1.32$ hours, not $2$ hours, so it is not accurate for this observation
