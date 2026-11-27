@paper FS1 Shadow October 2020

@q 1
@topic Poisson test and Type II error
@marks 13
@question
(a)(i) Scale the rate to 100 bulbs: $100\frac{3}{20}=15$. \\
Let $X$ count faulty bulbs among the 100; it has Poisson mean $15$. \\
Use $P(X=k)=e^{-15}\frac{15^k}{k!}$. \\
$P(X=8)=e^{-15}\frac{15^8}{8!}$ \\
$=0.0194443003\ldots\approx0.0194$. \\
(ii) Use the complement of $X\leq9$. \\
$P(X\geq10)=1-P(X\leq9)$ \\
$=1-0.0698536607\ldots$ \\
$=0.9301463393\ldots\approx0.930$. \\
(b) Let $Y$ count faulty bulbs among 60 after the changes. \\
Under $H_0$, the rate has not decreased: Poisson mean $60\frac{3}{20}=9$. \\
Under $H_1$, the faulty rate is lower than $3$ per $20$ bulbs. \\
For a lower-tail test, use $P(Y\leq5\text{ when mean}=9)$. \\
$=e^{-9}\sum_{k=0}^{5}\frac{9^k}{k!}$ \\
$=0.11569052\ldots$. \\
Since $0.11569052\ldots>0.05$, do not reject $H_0$. \\
There is insufficient evidence at 5% that the faulty rate has decreased. \\
(c) Under $H_0$, $P(Y\leq3)=0.021226\ldots<0.05$. \\
But $P(Y\leq4)=0.054963\ldots>0.05$. \\
Hence the critical region is $Y\leq3$. \\
A Type II error occurs when $Y\geq4$ despite a true decrease. \\
At the true rate of 1 faulty bulb per 12, the mean in 60 bulbs is $60/12=5$. \\
Let $W$ have a Poisson distribution with mean $5$. \\
$P(\text{Type II error})=P(W\geq4)$ \\
$=1-P(W\leq3)$ \\
$=1-0.2650259153\ldots$ \\
$=0.7349740847\ldots\approx0.735$.

@q 2
@topic Poisson sum and binomial variance
@marks 4
@question
(a) The approximation needs many trials and a small event probability. \\
Here $n=8$ is small and $p=0.3$ is not small, so Poisson mean $3$ is not a good approximation. \\
(b) $X$ and $Y$ must be independent for their Poisson means to add. \\
(c) For binomial $W$, use $\mathrm{Var}(W)=np(1-p)$. \\
$=10(0.3)(0.7)$ \\
$=2.1$. \\
By independence, $X+Y$ has Poisson mean $3+6=9$. \\
Since the sum is integer valued, $X+Y<2.1$ means $X+Y\leq2$. \\
$P(X+Y\leq2)=P(0)+P(1)+P(2)$ \\
$=e^{-9}\left(1+9+\frac{9^2}{2!}\right)$ \\
$=0.0062321951\ldots\approx0.00623$.

@q 3
@topic Geometric game and infinite series
@marks 9
@question
(a) Beth's third go is roll 5 overall. \\
For her to win then, the first four rolls are not 2 and roll 5 is 2. \\
$P=\left(\frac{5}{6}\right)^4\left(\frac{1}{6}\right)$ \\
$=\frac{625}{7776}$ \\
$=0.0803755144\ldots\approx0.0804$. \\
(b) Amal's fourth go is roll 8 overall. \\
For the first 2 to occur on roll 8 or later, rolls 1 to 7 must all miss 2. \\
$P=\left(\frac{5}{6}\right)^7$ \\
$=0.2790816472\ldots\approx0.279$. \\
(c) Let $T$ be the number of rolls up to and including the first 2. \\
$T$ has a geometric distribution with $p=\frac{1}{6}$. \\
$E(T)=\frac{1}{p}=6$. \\
$\mathrm{Var}(T)=\frac{1-p}{p^2}$ \\
$=\frac{5/6}{(1/6)^2}=30$. \\
The standard deviation is $\sqrt{30}=5.477225\ldots\approx5.48$. \\
(d) Beth wins if she succeeds on roll 1, 3, 5, and so on. \\
Each further chance requires two unsuccessful rolls. \\
$P(\text{Beth wins})=\frac{1}{6}+\frac{1}{6}\left(\frac{5}{6}\right)^2+\frac{1}{6}\left(\frac{5}{6}\right)^4+\cdots$. \\
This is a geometric series with first term $\frac{1}{6}$ and ratio $\frac{25}{36}$. \\
Its sum is $\frac{1/6}{1-25/36}$. \\
$=\frac{1/6}{11/36}$ \\
$=\frac{6}{11}\approx0.545$.

@q 4
@topic Discrete transformation and moments
@marks 8
@question
(a) Use $E(X)=\sum xP(X=x)$. \\
$E(X)=(-3)\frac{2}{5}+(-1)\frac{1}{3}+3\frac{1}{15}+9\frac{1}{5}$ \\
$=-\frac{6}{5}-\frac{1}{3}+\frac{1}{5}+\frac{9}{5}$ \\
$=\frac{7}{15}$. \\
Use $E(X^2)=\sum x^2P(X=x)$. \\
$E(X^2)=9\frac{2}{5}+1\frac{1}{3}+9\frac{1}{15}+81\frac{1}{5}$ \\
$=\frac{18}{5}+\frac{1}{3}+\frac{3}{5}+\frac{81}{5}$ \\
$=\frac{311}{15}$. \\
$\mathrm{Var}(X)=E(X^2)-[E(X)]^2$ \\
$=\frac{311}{15}-\left(\frac{7}{15}\right)^2$ \\
$=\frac{4665-49}{225}$ \\
$=\frac{4616}{225}=20.5155\ldots$. \\
(b) Map each possible $X$ to $Y$. \\
For $X=-3$, $Y=2(-3)^2=18$. \\
For $X=-1$, $Y=2(-1)^2=2$. \\
For $X=3$, $Y=3+4=7$. \\
For $X=9$, $Y=9+4=13$. \\
Thus $Y\geq8$ when $X=-3$ or $X=9$. \\
$P(Y\geq8)=\frac{2}{5}+\frac{1}{5}=\frac{3}{5}$. \\
(c) Use $E(XY)=\sum xyP(X=x)$. \\
$=(-3)(18)\frac{2}{5}+(-1)(2)\frac{1}{3}+3(7)\frac{1}{15}+9(13)\frac{1}{5}$ \\
$=-\frac{108}{5}-\frac{2}{3}+\frac{7}{5}+\frac{117}{5}$ \\
$=\frac{16}{5}-\frac{2}{3}$ \\
$=\frac{48-10}{15}$ \\
$=\frac{38}{15}$.

@q 5
@topic Binomial goodness of fit
@marks 14
@question
(a) Each sample contains a fixed number, seven, of items. \\
Each item has just two outcomes, faulty or not faulty, with a constant probability. \\
The binomial model also assumes independence between items. \\
(b) Count faulty items across the 120 samples: \\
$0(2)+1(6)+2(11)+3(19)+4(25)+5(32)+6(16)+7(9)$ \\
$=0+6+22+57+100+160+96+63$ \\
$=504$. \\
There are $120(7)=840$ inspected items. \\
The observed faulty proportion is $\frac{504}{840}=\frac{3}{5}=0.6$, as required. \\
(c) For $Z$ binomial with $n=7$, $p=0.6$, use $P(Z=k)=7Ck(0.6)^k(0.4)^{7-k}$. \\
$s=120P(Z=2)$ \\
$=120(7C2)(0.6)^2(0.4)^5$ \\
$=9.289728\ldots=9.29$. \\
$t=120P(Z=4)$ \\
$=120(7C4)(0.6)^4(0.4)^3$ \\
$=34.83648\ldots=34.84$. \\
(d) Under $H_0$, the binomial distribution with $n=7$, $p=0.6$ is suitable. \\
Under $H_1$, it is not suitable. \\
Combine groups with expected counts under five. \\
For $0$ to $2$, $O=2+6+11=19$ and $E=0.20+2.06+9.29=11.55$. \\
For $6$ to $7$, $O=16+9=25$ and $E=15.68+3.36=19.04$. \\
The five combined $(O,E)$ pairs are $(19,11.55)$, $(19,23.22)$, $(25,34.84)$, $(32,31.35)$, $(25,19.04)$. \\
Since $p$ was estimated from the data, degrees of freedom $=5-1-1=3$. \\
The 1% upper critical value is $11.345$. \\
Compute $\sum\frac{(O-E)^2}{E}$: \\
$\frac{(19-11.55)^2}{11.55}+\frac{(19-23.22)^2}{23.22}+\frac{(25-34.84)^2}{34.84}$ \\
$+\frac{(32-31.35)^2}{31.35}+\frac{(25-19.04)^2}{19.04}$ \\
$=10.230611\ldots$. \\
Since $10.230611\ldots<11.345$, do not reject $H_0$. \\
At 1%, the data are consistent with the proposed binomial model.

@q 6
@topic Probability generating function moments
@marks 12
@question
(a) The coefficient of $t^3$ in $G_X(t)$ is zero. \\
Therefore $P(X=3)=0$. \\
(b)(i) A generating function satisfies $G_X(1)=1$. \\
Substitute $t=1$: $a+a+b=1$. \\
Thus $2a+b=1$. \\
Differentiate: $G'_X(t)=a+6bt^5$. \\
Use $E(X)=G'_X(1)=4$: $a+6b=4$. \\
Multiply the second equation by $2$: $2a+12b=8$. \\
Subtract $2a+b=1$: $11b=7$. \\
$b=\frac{7}{11}$. \\
Substitute into $2a+b=1$: $2a+\frac{7}{11}=1$. \\
$2a=\frac{4}{11}$. \\
$a=\frac{2}{11}$. \\
(ii) Differentiate $G'_X(t)=a+6bt^5$ again: \\
$G''_X(t)=30bt^4$. \\
At $t=1$, $G''_X(1)=30b=30\frac{7}{11}=\frac{210}{11}$. \\
Use $G''_X(1)=E[X(X-1)]$. \\
Hence $\mathrm{Var}(X)=G''_X(1)+E(X)-[E(X)]^2$. \\
$=\frac{210}{11}+4-4^2$ \\
$=\frac{210}{11}-12$ \\
$=\frac{210-132}{11}$ \\
$=\frac{78}{11}=7.090909\ldots$.

@q 7
@topic Central limit theorem and test power
@marks 15
@question
(a) For a fair spinner, each of $1,2,3,4,5$ has probability $\frac{1}{5}$. \\
Use $E(S)=\sum sP(S=s)$. \\
$E(S)=\frac{1+2+3+4+5}{5}$ \\
$=\frac{15}{5}=3$. \\
Use $E(S^2)=\sum s^2P(S=s)$. \\
$E(S^2)=\frac{1^2+2^2+3^2+4^2+5^2}{5}$ \\
$=\frac{1+4+9+16+25}{5}$ \\
$=\frac{55}{5}=11$. \\
$\mathrm{Var}(S)=E(S^2)-[E(S)]^2$ \\
$=11-3^2=2$. \\
For 50 independent spins, the central limit theorem gives an approximately normal sample mean. \\
Its mean is $3$ and its variance is $\frac{2}{50}=0.04$. \\
Its standard deviation is $\sqrt{0.04}=0.2$. \\
The 5% lower standard normal quantile is $z=-1.6448536\ldots$. \\
Standardise $k$: $\frac{k-3}{0.2}=-1.6448536\ldots$. \\
Multiply by $0.2$: $k-3=-0.3289707\ldots$. \\
$k=2.6710293\ldots$. \\
So $k=2.67$ to 3 significant figures. \\
(b) The individual score $S$ is discrete uniform, not normal. \\
With 50 independent spins, the Central Limit Theorem makes the sample mean approximately normal, so the normal quantile in part (a) can be used. \\
(c) Under the true distribution, $E(S)=3.2$ and $\mathrm{Var}(S)=2.5$. \\
For 50 spins, the sample mean has approximate mean $3.2$ and variance $\frac{2.5}{50}=0.05$. \\
Its standard deviation is $\sqrt{0.05}=0.2236068\ldots$. \\
The test rejects when the sample mean is below $2.5$ or above $3.1$. \\
For the lower region, $z=\frac{2.5-3.2}{\sqrt{0.05}}=-3.130495\ldots$. \\
Thus $P(\text{mean score}<2.5)=0.000872559\ldots$. \\
For the upper region, $z=\frac{3.1-3.2}{\sqrt{0.05}}=-0.4472136\ldots$. \\
Thus $P(\text{mean score}>3.1)=0.672639577\ldots$. \\
Add the disjoint rejection probabilities: \\
Power $=0.000872559\ldots+0.672639577\ldots$ \\
$=0.673512136\ldots\approx0.674$. \\
(d) If Helen increases the number of spins to $n$, the sample mean's variance becomes $2.5/n$. \\
As $n$ increases, the sample mean concentrates around the true mean $3.2$. \\
Since $3.2>3.1$, rejection becomes more likely and the power increases.
