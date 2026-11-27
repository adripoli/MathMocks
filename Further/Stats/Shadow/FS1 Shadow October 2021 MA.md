@paper FS1 Shadow October 2021

@q 1
@topic Chi-square goodness of fit
@marks 7
@question
(a) The expected total for four equal categories is $4(43)=172$ rolls. \\
The three known frequencies add to $46+33+38=117$. \\
Therefore $x=172-117=55$, as required. \\
(b) There are four categories. Their frequencies must sum to the fixed total, leaving $4-1=3$ independent frequencies. \\
No probability parameter is estimated, so degrees of freedom $=3$. \\
(c) Under $H_0$, the tetrahedral die is unbiased. \\
Under $H_1$, it is biased. \\
Each expected frequency is $43$. \\
Use $\sum\frac{(O-E)^2}{E}$. \\
$=\frac{(46-43)^2}{43}+\frac{(33-43)^2}{43}$ \\
$+\frac{(38-43)^2}{43}+\frac{(55-43)^2}{43}$ \\
$=\frac{9+100+25+144}{43}$ \\
$=\frac{278}{43}=6.465116\ldots$. \\
At 5% with three degrees of freedom, the critical value is $7.815$. \\
Since $6.465116\ldots<7.815$, do not reject $H_0$. \\
There is insufficient evidence at the 5% level that the die is biased.

@q 2
@topic Poisson process and approximation
@marks 14
@question
(a) A 60-minute period contains four 15-minute periods. \\
Its Poisson mean is $4(1.2)=4.8$. \\
Let $F$ count faults in 60 minutes. \\
$P(F\geq3)=1-P(F\leq2)$ \\
$=1-e^{-4.8}\left(1+4.8+\frac{4.8^2}{2!}\right)$ \\
$=0.8574607811\ldots$ \\
$=0.857$ to 3 decimal places, as required. \\
(b) Let $A$ count the selected periods with at least three faults. \\
Each independent period has success probability $p=0.8574607811\ldots$. \\
Thus $A$ has a binomial distribution with $n=7$ and this $p$. \\
"Fewer than four" means $A\leq3$. \\
$P(A\leq3)=\sum_{k=0}^{3}7Ck\,p^k(1-p)^{7-k}$ \\
$=0.0100685561\ldots\approx0.0101$. \\
(c) For one period, $q=P(F=10)=e^{-4.8}\frac{4.8^{10}}{10!}$. \\
$=0.0147243397\ldots$. \\
Across 120 periods, the binomial count of exact-tens has mean $120q$. \\
$=120(0.0147243397\ldots)=1.76692076\ldots$. \\
Approximate that count by a Poisson variable $E$ with this mean. \\
$P(E\geq4)=1-P(E\leq3)$ \\
$=1-e^{-1.76692076\ldots}\sum_{k=0}^{3}\frac{(1.76692076\ldots)^k}{k!}$ \\
$=0.1034526025\ldots$ \\
$=0.103$ to 3 significant figures, as required. \\
(d) The event of exactly ten faults has probability about $0.0147$ in each period, which is small, and there are 120 periods. \\
(e) Under $H_0$, the Saturday fault rate equals the weekday rate. \\
The 3.5-hour mean is $\frac{210}{15}(1.2)=16.8$. \\
Under $H_1$, the Saturday rate, hence the 3.5-hour mean, differs from this. \\
(f) Let $X$ count faults in the sampled 3.5 hours. \\
Under $H_0$, $X$ has a Poisson distribution with mean $16.8$. \\
Since the observed count $23$ is high, calculate the upper-tail probability. \\
$P(X\geq23)=1-P(X\leq22)$ \\
$=0.0868734961\ldots$. \\
The 5% two-sided test allocates $0.025$ to the upper tail. \\
Since $0.0868734961\ldots>0.025$, do not reject $H_0$. \\
There is insufficient evidence at 5% that Saturday's fault rate differs from the weekday rate.

@q 3
@topic Binomial sample mean normal approximation
@marks 4
@question
For one day, $E(X)=np=300(0.72)=216$. \\
Its variance is $np(1-p)=300(0.72)(0.28)$. \\
$=60.48$. \\
For 100 independent days, use the central limit theorem. \\
The sample mean is approximately normal with mean $216$. \\
Its variance is $\frac{60.48}{100}=0.6048$. \\
Its standard deviation is $\sqrt{0.6048}=0.777689\ldots$. \\
Standardise $217$: $z=\frac{217-216}{\sqrt{0.6048}}=1.28586\ldots$. \\
$P(\text{sample mean}>217)\approx P(Z>1.28586\ldots)$ \\
$=0.0992457448\ldots\approx0.0992$.

@q 4
@topic Conditional probability and moments
@marks 10
@question
(a) Use linearity of expectation: $E(2N+5)=2E(N)+5$. \\
$9.6=2E(N)+5$. \\
Subtract 5: $4.6=2E(N)$. \\
Divide by 2: $E(N)=2.3$. \\
The conditional probability is $\frac{P(N=1)}{P(N<3)}=\frac{6}{13}$. \\
$\frac{a}{0.1+a+0.25}=\frac{6}{13}$. \\
Combine constants: $\frac{a}{a+0.35}=\frac{6}{13}$. \\
Cross multiply: $13a=6a+2.1$. \\
Subtract $6a$: $7a=2.1$. \\
$a=0.3$. \\
The conditions give $b=2c$. \\
Probabilities sum to one: $0.1+0.3+0.25+b+c+0.2=1$. \\
Thus $b+c=0.15$. \\
Substitute $b=2c$: $3c=0.15$. \\
$c=0.05$ and $b=0.1$. \\
Compute the first moment to check: \\
$E(N)=1(0.3)+2(0.25)+3(0.1)+4(0.05)+5(0.2)=2.3$. \\
Compute $E(N^2)$: \\
$E(N^2)=1^2(0.3)+2^2(0.25)+3^2(0.1)+4^2(0.05)+5^2(0.2)$ \\
$=0.3+1+0.9+0.8+5$ \\
$=8$. \\
Use $\mathrm{Var}(N)=E(N^2)-[E(N)]^2$. \\
$=8-(2.3)^2$ \\
$=8-5.29$ \\
$=2.71$, as required. \\
(b) The chance of winning 10p is $0.1+0.3+0.25=0.65$. \\
The chance of winning 20p is $0.1+0.05+0.2=0.35$. \\
Expected winnings in pounds $=0.10(0.65)+0.20(0.35)$. \\
$=0.065+0.070$ \\
$=0.135$ pounds, or 13.5p per player. \\
(c) A Poisson variable can take many nonnegative integer values, while winnings here can only be 10p or 20p.

@q 5
@topic Geometric and negative binomial tests
@marks 18
@question
(a) The source says "red", but defines only yellow and green marbles. The intended event in the scheme is three green draws before the first yellow. \\
Each green draw has probability $1-0.04=0.96$. \\
The first three must all be green: \\
$P=(0.96)^3$ \\
$=0.884736\approx0.885$. \\
(b) For the second yellow to be on draw 10, exactly one of the first nine draws must be yellow and draw 10 yellow. \\
Choose the first yellow's place in $9$ ways. \\
The other eight draws are green. \\
$P=9(0.04)(0.96)^8(0.04)$ \\
$=9(0.96)^8(0.04)^2$ \\
$=0.0103880099\ldots\approx0.0104$. \\
(c) Let $D$ count draws to the $n$th yellow; each yellow has probability $p$. \\
For a negative binomial count, $E(D)=\frac{n}{p}$. \\
The variance is $\mathrm{Var}(D)=\frac{n(1-p)}{p^2}$. \\
The given standard deviation is $300$, so variance $=300^2=90000$. \\
Divide variance by mean to remove $n$: \\
$\frac{\mathrm{Var}(D)}{E(D)}=\frac{1-p}{p}$. \\
$\frac{90000}{22500}=\frac{1-p}{p}$. \\
$4=\frac{1-p}{p}$. \\
Multiply by $p$: $4p=1-p$. \\
Add $p$: $5p=1$. \\
$p=0.2$. \\
(d) Let $p$ be bag C's yellow proportion. \\
Use $H_0:p=0.04$ and $H_1:p<0.04$. \\
Under $H_0$, $J$ has a geometric distribution with $p=0.04$. \\
Smaller $p$ makes longer waits more likely, so use $J\geq c$. \\
The upper-tail probability is $P(J\geq c)=(1-p)^{c-1}$. \\
Under $H_0$, this is $(0.96)^{c-1}$. \\
Set $(0.96)^{c-1}<0.05$. \\
Take logs: $(c-1)\log(0.96)<\log(0.05)$. \\
Since $\log(0.96)<0$, dividing reverses the inequality: \\
$c-1>\frac{\log(0.05)}{\log(0.96)}=73.38525\ldots$. \\
Hence $c>74.38525\ldots$ and the smallest integer is $75$. \\
Check: $P(J\geq74)=0.96^{73}=0.0507925\ldots>0.05$. \\
$P(J\geq75)=0.96^{74}=0.0487608\ldots<0.05$. \\
The critical region is $J\geq75$. \\
(e) Tom observed $J=24$, which is below $75$. \\
Do not reject $H_0$; there is insufficient evidence at 5% of a smaller yellow proportion in bag C. \\
(f) At the true bag C proportion $p=0.013$, power is the probability of the critical region. \\
$P(J\geq75)=(1-0.013)^{75-1}$ \\
$=(0.987)^{74}$ \\
$=0.379725093\ldots$ \\
$=0.380$ to 3 significant figures, as required.

@q 6
@topic Generating functions under transformations
@marks 14
@question
(a) A probability generating function has value $1$ at $t=1$. \\
$G_X(1)=k(2+1)^4=1$. \\
$81k=1$. \\
Divide by $81$: $k=\frac{1}{81}$, as required. \\
(b) Expand with the binomial theorem: \\
$(2+t)^4=2^4+4(2^3)t+6(2^2)t^2+4(2)t^3+t^4$. \\
$=16+32t+24t^2+8t^3+t^4$. \\
Divide by $81$: $G_X(t)=\frac{16+32t+24t^2+8t^3+t^4}{81}$. \\
The coefficient of $t^2$ is $P(X=2)=\frac{24}{81}=\frac{8}{27}$. \\
(c) Use $W=3X+2$. \\
$G_W(t)=E(t^W)=E(t^{3X+2})$. \\
$=t^2E((t^3)^X)$ \\
$=t^2G_X(t^3)$ \\
$=\frac{t^2(2+t^3)^4}{81}$. \\
(d) For independent $X$ and $Y$, the generating function of their sum is the product. \\
$G_U(t)=G_X(t)G_Y(t)$ \\
$=\frac{(2+t)^4}{81}\frac{t(2+t)^2}{9}$ \\
$=\frac{t(2+t)^6}{729}$. \\
(e) Use the product rule on $G_U(t)=\frac{t(2+t)^6}{729}$. \\
$G'_U(t)=\frac{(2+t)^6}{729}+\frac{6t(2+t)^5}{729}$. \\
At $t=1$, $G'_U(1)=\frac{3^6+6(3^5)}{729}$. \\
$=\frac{729+1458}{729}=3$. \\
Differentiate each term again: \\
$G''_U(t)=\frac{6(2+t)^5}{729}+\frac{6(2+t)^5+30t(2+t)^4}{729}$. \\
$=\frac{12(2+t)^5+30t(2+t)^4}{729}$. \\
At $t=1$, $G''_U(1)=\frac{12(3^5)+30(3^4)}{729}$. \\
$=\frac{2916+2430}{729}$ \\
$=\frac{5346}{729}=\frac{22}{3}$. \\
Use $G''_U(1)=E[U(U-1)]$ and $G'_U(1)=E(U)$. \\
$\mathrm{Var}(U)=G''_U(1)+G'_U(1)-[G'_U(1)]^2$. \\
$=\frac{22}{3}+3-3^2$ \\
$=\frac{22}{3}-6$ \\
$=\frac{4}{3}$.

@q 7
@topic Normal test sample size and Type II
@marks 8
@question
(a) Test size is the probability of a Type I error under $H_0$. \\
At a 1% significance level, the size is $0.01$. \\
(b)(i) Let the critical rule be sample mean $<k$. \\
For size $0.01$ under $H_0:\mu=22$, use the lower standard normal quantile $z=-2.3263479\ldots$. \\
$\frac{k-22}{0.15/\sqrt{n}}=-2.3263479\ldots$. \\
Multiply by $0.15/\sqrt{n}$: \\
$k-22=-\frac{0.3489522\ldots}{\sqrt{n}}$. \\
$k=22-\frac{0.3489522\ldots}{\sqrt{n}}$. \\
At the true mean $21.8$, Type II error means the sample mean is at least $k$. \\
To make that upper-tail probability less than $0.05$, require \\
$\frac{k-21.8}{0.15/\sqrt{n}}>1.6448536\ldots$. \\
Substitute the expression for $k$: \\
$\frac{0.2-0.3489522\ldots/\sqrt{n}}{0.15/\sqrt{n}}>1.6448536\ldots$. \\
Multiply by $0.15$: $0.2\sqrt{n}-0.3489522\ldots>0.2467280\ldots$. \\
Add $0.3489522\ldots$: $0.2\sqrt{n}>0.5956802\ldots$. \\
Divide by $0.2$: $\sqrt{n}>2.978401\ldots$. \\
Square: $n>8.870873\ldots$. \\
The minimum integer is $n=9$. \\
Check: Type II probability at $n=8$ is $0.07424\ldots$, and at $n=9$ it is $0.04710\ldots<0.05$. \\
(ii) With a 5% significance level, the rejection region grows for the same $n$. \\
Failing to reject at true mean $21.8$ becomes less likely, so the Type II error probability decreases.
