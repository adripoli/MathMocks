@paper FS1 Mock Set 2

@q 1
@topic Binomial Poisson approximation error
@marks 4
@question
For the exact calculation, $X$ has a binomial distribution with $n=120$, $p=0.1$. \\
$P(X<10)=P(X\leq9)$ \\
$=\sum_{k=0}^{9}120Ck(0.1)^k(0.9)^{120-k}$ \\
$=0.2285916228\ldots$. \\
For the Poisson approximation, use mean $np=120(0.1)=12$. \\
Let $Y$ have a Poisson distribution of mean $12$. \\
$P(Y<10)=P(Y\leq9)$ \\
$=\sum_{k=0}^{9}e^{-12}\frac{12^k}{k!}$ \\
$=0.2423921617\ldots$. \\
Take the absolute difference: \\
$0.2423921617\ldots-0.2285916228\ldots$ \\
$=0.0138005388\ldots$ \\
$=0.0138$ to 3 significant figures, as required.

@q 2
@topic Probability generating function
@marks 8
@question
(a) A probability generating function has $G_X(1)=1$. \\
Substitute $t=1$: \\
$\frac{1}{k}((1+1)^2+2(1)^4)=1$. \\
Evaluate the bracket: $\frac{4+2}{k}=1$. \\
Thus $\frac{6}{k}=1$ and $k=6$. \\
(b) Substitute $k=6$ and expand the square: \\
$G_X(t)=\frac{t^3}{6}(1+2t+t^2+2t^4)$. \\
Multiply by $t^3$: \\
$G_X(t)=\frac{t^3}{6}+\frac{2t^4}{6}+\frac{t^5}{6}+\frac{2t^7}{6}$. \\
Simplify coefficients: \\
$G_X(t)=\frac{t^3}{6}+\frac{t^4}{3}+\frac{t^5}{6}+\frac{t^7}{3}$. \\
The coefficient of $t^x$ is $P(X=x)$. \\
The values in $4\leq X\leq6.6$ are $4$, $5$, and $6$. \\
$P(X=4)=\frac{1}{3}$, $P(X=5)=\frac{1}{6}$, $P(X=6)=0$. \\
Add them: $\frac{1}{3}+\frac{1}{6}+0=\frac{1}{2}$. \\
(c) Independent sums have the product of their generating functions. \\
$G_W(t)=G_{X_1}(t)G_{X_2}(t)$ \\
$=[G_X(t)]^2$ \\
$=\frac{t^6}{36}((1+t)^2+2t^4)^2$.

@q 3
@topic Independent binomial and Poisson
@marks 8
@question
(a) Jack succeeds on a journey with probability $1-0.4=0.6$. \\
Let $X$ count Jack's successes in three independent journeys. \\
$X$ has a binomial distribution with $n=3$, $p=0.6$. \\
$P(X=3)=(0.6)^3=0.216$. \\
Gill's count $Y$ has Poisson mean $2.1$. \\
$P(Y=3)=e^{-2.1}\frac{2.1^3}{3!}$ \\
$=0.189011\ldots$. \\
The counts are independent, so multiply: \\
$P(X=3\text{ and }Y=3)=0.216(0.189011\ldots)$ \\
$=0.04082648\ldots\approx0.0408$. \\
(b) Jack can bring back at most three buckets. \\
List the cases where Jack has more: $(X,Y)=(1,0)$, $X=2$ with $Y\leq1$, or $X=3$ with $Y\leq2$. \\
$P(X=1)=3(0.6)(0.4)^2=0.288$. \\
$P(X=2)=3(0.6)^2(0.4)=0.432$. \\
$P(X=3)=(0.6)^3=0.216$. \\
$P(Y=0)=e^{-2.1}=0.122456\ldots$. \\
$P(Y\leq1)=e^{-2.1}(1+2.1)=0.379615\ldots$. \\
$P(Y\leq2)=e^{-2.1}(1+2.1+\frac{2.1^2}{2})=0.649631\ldots$. \\
Use independence in each case and add: \\
$P(X>Y)=0.288(0.122456\ldots)+0.432(0.379615\ldots)$ \\
$+0.216(0.649631\ldots)$ \\
$=0.33958147\ldots\approx0.340$. \\
(c) Gill may tire while climbing the hill, so her rate of successful journeys may fall during the hour.

@q 4
@topic Geometric distribution and CLT
@marks 14
@question
(a) Each find must have the same $0.1$ probability of being interesting, with finds independent; for example, interesting objects are evenly spread through a large field. \\
(b) Let $X$ count the finds up to and including the first interesting object. \\
$X$ has a geometric distribution with success probability $p=0.1$. \\
To have $X=7$, the first six finds are rubbish and the seventh interesting. \\
$P(X=7)=(0.9)^6(0.1)$ \\
$=0.0531441\approx0.0531$. \\
(c) More than seven means the first seven finds are rubbish. \\
$P(X>7)=(0.9)^7$ \\
$=0.4782969\approx0.478$. \\
(d) Fewer than seven means $X\leq6$. \\
$q=P(X\leq6)=1-P(X>6)$ \\
$=1-(0.9)^6$ \\
$=0.468559$. \\
Let $D$ count such days among five independent days. \\
$D$ has a binomial distribution with $n=5$, $p=0.468559$. \\
$P(D=3)=5C3(0.468559)^3(1-0.468559)^2$ \\
$=10(0.468559)^3(0.531441)^2$ \\
$=0.2905380\ldots\approx0.291$. \\
(e) For one day, $E(X)=\frac{1}{p}=\frac{1}{0.1}=10$. \\
Its variance is $\mathrm{Var}(X)=\frac{1-p}{p^2}$. \\
$=\frac{0.9}{(0.1)^2}=90$. \\
For 80 independent days, use the central limit theorem. \\
The sample mean is approximately normal with mean $10$ and variance $\frac{90}{80}=1.125$. \\
Its standard deviation is $\sqrt{1.125}=1.060660\ldots$. \\
Standardise $9$: $z=\frac{9-10}{\sqrt{1.125}}=-0.942809\ldots$. \\
$P(\text{sample mean}<9)\approx P(Z<-0.942809\ldots)$ \\
$=0.172889\ldots\approx0.173$.

@q 5
@topic Biased random walk variance
@marks 11
@question
(a) To end at position $1$ after three moves, exactly two moves are $+1$ and one is $-1$. \\
There are $3C1=3$ possible orders for the $-1$ move. \\
$P(Y=1)=3\left(\frac{2}{3}\right)^2\left(\frac{1}{3}\right)$ \\
$=3\frac{4}{9}\frac{1}{3}$ \\
$=\frac{12}{27}=\frac{4}{9}$, as required. \\
(b) The possible positions are $-3,-1,1,3$. \\
$P(Y=-3)=(1/3)^3=1/27$. \\
$P(Y=-1)=3(2/3)(1/3)^2=6/27$. \\
$P(Y=1)=12/27$ from part (a). \\
$P(Y=3)=(2/3)^3=8/27$. \\
Check: $(1+6+12+8)/27=1$. \\
Use $E(Y)=\sum yP(Y=y)$. \\
$E(Y)=(-3)\frac{1}{27}+(-1)\frac{6}{27}+1\frac{12}{27}+3\frac{8}{27}$ \\
$=\frac{-3-6+12+24}{27}$ \\
$=1$. \\
Use $E(Y^2)=\sum y^2P(Y=y)$. \\
$E(Y^2)=9\frac{1}{27}+1\frac{6}{27}+1\frac{12}{27}+9\frac{8}{27}$ \\
$=\frac{9+6+12+72}{27}$ \\
$=\frac{99}{27}=\frac{11}{3}$. \\
Now $\mathrm{Var}(Y)=E(Y^2)-[E(Y)]^2$. \\
$=\frac{11}{3}-1^2$ \\
$=\frac{8}{3}$. \\
(c) Distance is $D=|Y|$. \\
$P(D=1)=P(Y=-1)+P(Y=1)=\frac{18}{27}=\frac{2}{3}$. \\
$P(D=3)=P(Y=-3)+P(Y=3)=\frac{9}{27}=\frac{1}{3}$. \\
$E(D)=1\frac{2}{3}+3\frac{1}{3}=\frac{5}{3}$. \\
$E(D^2)=1^2\frac{2}{3}+3^2\frac{1}{3}=\frac{11}{3}$. \\
$\mathrm{Var}(D)=\frac{11}{3}-\left(\frac{5}{3}\right)^2$ \\
$=\frac{8}{9}$. \\
Since $\frac{8}{9}<\frac{8}{3}$, the variance of $D$ is less.

@q 6
@topic Poisson goodness of fit, modelling
@marks 11
@question
(a) Let $X$ count whale sightings on one four-hour trip. \\
Under $H_0$, $X$ has a Poisson distribution with mean $2.4$. \\
Under $H_1$, that distribution is not a suitable model. \\
For $i=0,\ldots,5$, $E_i=60P(X=i)=60e^{-2.4}\frac{2.4^i}{i!}$. \\
$E_0=60e^{-2.4}=5.443077\ldots$. \\
$E_1=60e^{-2.4}(2.4)=13.063385\ldots$. \\
$E_2=60e^{-2.4}\frac{2.4^2}{2!}=15.676062\ldots$. \\
$E_3=60e^{-2.4}\frac{2.4^3}{3!}=12.540850\ldots$. \\
$E_4=60e^{-2.4}\frac{2.4^4}{4!}=7.524510\ldots$. \\
$E_5=60e^{-2.4}\frac{2.4^5}{5!}=3.611765\ldots$. \\
$E_{6+}=60-\sum_{i=0}^{5}E_i=2.140350\ldots$. \\
Combine the last two groups because their expected frequencies are below $5$. \\
For $5+$, $O=3+1=4$ and $E=3.611765\ldots+2.140350\ldots=5.752115\ldots$. \\
There are six groups and no estimated parameter, so degrees of freedom $=6-1=5$. \\
At 10%, the upper critical value is $9.236$. \\
Use the chi-square statistic $\sum\frac{(O-E)^2}{E}$. \\
$=\frac{(4-5.443077)^2}{5.443077}+\frac{(18-13.063385)^2}{13.063385}$ \\
$+\frac{(20-15.676062)^2}{15.676062}+\frac{(8-12.540850)^2}{12.540850}$ \\
$+\frac{(6-7.524510)^2}{7.524510}+\frac{(4-5.752115)^2}{5.752115}$ \\
$=5.927545\ldots$. \\
Since $5.927545\ldots<9.236$, do not reject $H_0$. \\
There is no significant evidence at 10% against the owner's claim. \\
(b) Record the group of eight whales as one sighting. \\
The Poisson model counts a sighting as one event; whales arriving together are not eight separate independent sightings.

@q 7
@topic Geometric critical region, Type II error
@marks 10
@question
(a) A smaller $p$ makes long waits more likely, so use an upper-tail region $X\geq c$. \\
Under $H_0$, $p=0.4$ and $1-p=0.6$. \\
The size is $P(X\geq c\text{ when } p=0.4)$. \\
By the geometric probability formula, \\
$P(X\geq c)=\sum_{i=c}^{\infty}0.4(0.6)^{i-1}$. \\
Sum the geometric series: \\
$P(X\geq c)=\frac{0.4(0.6)^{c-1}}{1-0.6}$ \\
$=(0.6)^{c-1}$. \\
Set this equal to $0.05$ to locate $c$: \\
$(0.6)^{c-1}=0.05$. \\
Take logarithms: $(c-1)\log(0.6)=\log(0.05)$. \\
Divide by $\log(0.6)$: $c-1=5.864\ldots$. \\
Thus $c=6.864\ldots$ lies between $6$ and $7$. \\
Check $c=6$: $P(X\geq6)=0.6^5=0.07776$. \\
Check $c=7$: $P(X\geq7)=0.6^6=0.046656$. \\
Since $0.046656$ is closer to $0.05$, the critical region is $X\geq7$. \\
(b) A Type II error means not rejecting $H_0$ when $p=\beta$. \\
Thus $P(X<7\text{ when } p=\beta)=0.5$. \\
For geometric $X$, $P(X\geq7)=(1-\beta)^6$. \\
Use the complement: $1-(1-\beta)^6=0.5$. \\
Subtract $1$: $-(1-\beta)^6=-0.5$. \\
Therefore $(1-\beta)^6=0.5$. \\
Take the positive sixth root: $1-\beta=(0.5)^{1/6}$. \\
$\beta=1-(0.5)^{1/6}$ \\
$=0.10910128\ldots$ \\
$=0.109$ to 3 significant figures.

@q 8
@topic Negative binomial and geometric
@marks 9
@question
(a) $Y$ counts draws to the first green counter with replacement, so it has a geometric distribution. \\
(b) Let $p$ be the probability of green on a draw. \\
For the negative binomial count to two greens, $E(X)=\frac{2}{p}$. \\
Its variance is $\mathrm{Var}(X)=\frac{2(1-p)}{p^2}$. \\
Suppose $\mathrm{Var}(X)=[E(X)]^2$. \\
Then $\frac{2(1-p)}{p^2}=\frac{4}{p^2}$. \\
Multiply by $p^2>0$: $2(1-p)=4$. \\
Divide by $2$: $1-p=2$. \\
So $p=-1$, which cannot be a probability. \\
Therefore Jo's proposed equality cannot hold. \\
(c) For geometric $Y$, $\mathrm{Var}(Y)=\frac{1-p}{p^2}$. \\
Set the estimated variance to $20$: $\frac{1-p}{p^2}=20$. \\
Multiply by $p^2$: $1-p=20p^2$. \\
Rearrange: $20p^2+p-1=0$. \\
Factor: $(5p-1)(4p+1)=0$. \\
Thus $p=\frac{1}{5}=0.2$ or $p=-\frac{1}{4}$. \\
Reject $-\frac{1}{4}$ because a probability cannot be negative. \\
The estimated green proportion is $0.2$, or $20\%$. \\
(d) Replacement makes each later draw independent of the first two. \\
After the first green on draw 2, draws 3 and 4 must be red and draw 5 green. \\
$P=(0.6)(0.6)(0.4)$ \\
$=0.144$.
