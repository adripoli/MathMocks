@paper FS1 Mock Set 1

@q 1
@topic Chi-square independence, sampling error
@marks 7
@question
(a) Under $H_0$, recycling and distance are independent. \\
Under $H_1$, recycling and distance are associated. \\
There are three distance groups and two recycling groups. \\
Degrees of freedom $=(3-1)(2-1)=2$. \\
At 5%, the upper critical value for two degrees of freedom is $5.991$. \\
Use the chi-square statistic $\sum \frac{(O-E)^2}{E}$. \\
$=\frac{(64-58.3)^2}{58.3}+\frac{(42-47.7)^2}{47.7}$ \\
$+\frac{(32-29.7)^2}{29.7}+\frac{(22-24.3)^2}{24.3}$ \\
$+\frac{(14-22)^2}{22}+\frac{(26-18)^2}{18}$ \\
$=8.098878\ldots$. \\
Since $8.098878\ldots>5.991$, reject $H_0$. \\
At the 5% level, the data do not support Barbara's belief that recycling is independent of distance. \\
(b) Both observed and expected frequencies were doubled. \\
For the actual sample, each $O$ and $E$ is half the value used in part (a). \\
Each contribution becomes $\frac{(O/2-E/2)^2}{E/2}=\frac{1}{2}\frac{(O-E)^2}{E}$. \\
The corrected statistic is $8.098878\ldots/2=4.049439\ldots$. \\
The degrees of freedom and critical value remain $2$ and $5.991$. \\
Since $4.049439\ldots<5.991$, do not reject $H_0$. \\
Barbara's original conclusion is no longer valid; this sample does not show an association.

@q 2
@topic Sampling without replacement, variance
@marks 10
@question
(a) Four tokens are removed precisely when the first three are green. \\
$P(X=4)=P(GGG)$ \\
$=\frac{7}{10}\times\frac{6}{9}\times\frac{5}{8}$ \\
$=\frac{210}{720}$ \\
$=\frac{7}{24}$, as required. \\
(b) Use $E(X)=\sum xP(X=x)$. \\
$E(X)=1\frac{3}{10}+2\frac{7}{30}+3\frac{7}{40}+4\frac{7}{24}$ \\
$=\frac{3}{10}+\frac{7}{15}+\frac{21}{40}+\frac{7}{6}$ \\
$=\frac{59}{24}$. \\
Use $E(X^2)=\sum x^2P(X=x)$. \\
$E(X^2)=1^2\frac{3}{10}+2^2\frac{7}{30}+3^2\frac{7}{40}+4^2\frac{7}{24}$ \\
$=\frac{3}{10}+\frac{14}{15}+\frac{63}{40}+\frac{14}{3}$ \\
$=\frac{299}{40}$. \\
Now $\mathrm{Var}(X)=E(X^2)-[E(X)]^2$. \\
$=\frac{299}{40}-\left(\frac{59}{24}\right)^2$ \\
$=\frac{4123}{2880}$ \\
$=1.431597\ldots\approx1.43$. \\
(c) Let $T$ count all draws up to and including the first red token. \\
With replacement, each draw has red probability $p=\frac{3}{10}$. \\
Thus $T$ has a geometric distribution with parameter $p=\frac{3}{10}$. \\
The green draws precede the red draw, so $Y=T-1$. \\
Subtracting a constant does not change variance. \\
$\mathrm{Var}(Y)=\mathrm{Var}(T)=\frac{1-p}{p^2}$ \\
$=\frac{7/10}{(3/10)^2}$ \\
$=\frac{70}{9}$ \\
$=7.777\ldots\approx7.78$.

@q 3
@topic Poisson probabilities and test power
@marks 10
@question
(a)(i) For a Poisson variable with mean $10.8$, $P(X=k)=e^{-10.8}\frac{10.8^k}{k!}$. \\
Put $k=9$: \\
$P(X=9)=e^{-10.8}\frac{10.8^9}{9!}$ \\
$=0.112375\ldots\approx0.112$. \\
(ii) "At least 9" means $X\geq9$. \\
Use the complement $X\leq8$: \\
$P(X\geq9)=1-P(X\leq8)$ \\
$=1-0.250228882\ldots$ \\
$=0.749771\ldots\approx0.750$. \\
(b) Let $X$ be Charlie's number of looks during the one-hour class. \\
Under the parents' claim, the one-hour mean is $2(3)=6$. \\
State $H_0$: the rate is at most $6$ per hour. \\
State $H_1$: the rate is greater than $6$ per hour. \\
Use the boundary value $6$ to find the upper critical region. \\
For a Poisson mean of $6$, $P(X\geq10)=0.083924\ldots>0.05$. \\
$P(X\geq11)=0.0426209\ldots<0.05$. \\
Therefore reject $H_0$ when $X\geq11$. \\
At the actual rate, the one-hour mean is $2(5)=10$. \\
Power is the probability of rejecting $H_0$ when the mean is $10$. \\
$P(X\geq11\text{ when }\mathrm{mean}=10)=1-P(X\leq10\text{ when }\mathrm{mean}=10)$ \\
$=1-0.58303975\ldots$ \\
$=0.41696025\ldots\approx0.417$. \\
(c) Charlie's looks at the phone must occur independently at a constant average rate.

@q 4
@topic Geometric goodness of fit
@marks 13
@question
(a) For a fair die, $P(5\text{ or }6)=\frac{2}{6}=\frac{1}{3}$. \\
Under $H_0$, rolls to the first 5 or 6 have a geometric distribution with $p=\frac{1}{3}$. \\
Under $H_1$, that geometric distribution is unsuitable. \\
For $i=1,\ldots,6$, $P(X=i)=\frac{1}{3}\left(\frac{2}{3}\right)^{i-1}$. \\
Multiply each probability by $100$ for expected frequency. \\
$E_1=100/3=33.333333\ldots$. \\
$E_2=100(1/3)(2/3)=22.222222\ldots$. \\
$E_3=100(1/3)(2/3)^2=14.814815\ldots$. \\
$E_4=100(1/3)(2/3)^3=9.876543\ldots$. \\
$E_5=100(1/3)(2/3)^4=6.584362\ldots$. \\
$E_6=100(1/3)(2/3)^5=4.389575\ldots$. \\
$E_{7+}=100(2/3)^6=8.779150\ldots$. \\
The sixth expected frequency is below $5$; combine groups $6$ and $7+$: \\
$O_{6+}=3+11=14$. \\
$E_{6+}=4.389575\ldots+8.779150\ldots=13.168724\ldots$. \\
There are six groups and no estimated parameters, so degrees of freedom $=6-1=5$. \\
The 5% upper critical value is $11.070$. \\
Use $\sum\frac{(O-E)^2}{E}$ for the six combined groups. \\
$=\frac{(39-33.333333)^2}{33.333333}+\frac{(17-22.222222)^2}{22.222222}$ \\
$+\frac{(17-14.814815)^2}{14.814815}+\frac{(10-9.876543)^2}{9.876543}$ \\
$+\frac{(3-6.584362)^2}{6.584362}+\frac{(14-13.168724)^2}{13.168724}$ \\
$=4.518125\ldots$. \\
Since $4.518125\ldots<11.070$, do not reject $H_0$. \\
There is insufficient evidence at the 5% level that the die is biased. \\
(b)(i) Mai records all six faces, so her test can reveal bias between faces 1 to 4 that Desmond's test misses. \\
Mai knows in advance that she needs exactly 100 rolls; Desmond may need many more. \\
(ii) Desmond's repeated experiment is likely to use more than 100 rolls and hence gather more data.

@q 5
@topic Binomial and Poisson approximation
@marks 10
@question
(a)(i) Each of the $1000$ independent samples tests positive with probability $0.005$. \\
Therefore $X$ has a binomial distribution with $n=1000$ and $p=0.005$. \\
(ii) Use the exact binomial distribution first. \\
$P(X\geq10)=1-P(X\leq9)$ \\
$=1-0.9685347615\ldots$ \\
$=0.0314652385\ldots$. \\
For the Poisson approximation, the mean is $np=1000(0.005)=5$. \\
Let $Y$ have a Poisson distribution with mean $5$. \\
$P(Y\geq10)=1-P(Y\leq9)$ \\
$=1-0.9681719427\ldots$ \\
$=0.0318280573\ldots$. \\
Use the exact probability as the denominator for percentage error. \\
Percentage error $=\frac{0.0318280573-0.0314652385}{0.0314652385}\times100$ \\
$=1.153078\ldots\%$ \\
$\approx1.15\%$. \\
(b) A Type I error is rejection of $H_0$ when $p=0.005$. \\
For Ushma's critical region, test size $=P(X\geq9\text{ when } p=0.005)$. \\
$=1-P(X\leq8\text{ when } p=0.005)$ \\
$=0.067602974\ldots$, or $6.7603\ldots\%$. \\
Javed's size is $8\%$. \\
Since $6.7603\ldots\%<8\%$, Ushma's test has the lower Type I error probability. \\
Advise Chris to use Ushma's test.

@q 6
@topic Negative binomial and central limit
@marks 10
@question
(a)(i) A hit has probability $p=1-0.8=0.2$. \\
Let $T$ be the number of throws needed for $r=3$ hits. \\
$T$ has a negative binomial distribution with $r=3$ and $p=0.2$. \\
Its mean is $E(T)=\frac{r}{p}$. \\
$=\frac{3}{0.2}$ \\
$=15$ throws. \\
(ii) The throws must be independent. \\
The probability of a hit must remain $0.2$ on every throw. \\
(b) For the same negative binomial variable, $\mathrm{Var}(T)=\frac{r(1-p)}{p^2}$. \\
$=\frac{3(0.8)}{0.2^2}$ \\
$=\frac{2.4}{0.04}$ \\
$=60$. \\
For $100$ independent rehearsals, use the central limit theorem. \\
The sample mean is approximately normal with mean $15$. \\
Its variance is $\frac{60}{100}=0.6$. \\
Its standard deviation is $\sqrt{0.6}=0.774596\ldots$. \\
Standardise $16$: $z=\frac{16-15}{\sqrt{0.6}}=1.290994\ldots$. \\
$P(\text{sample mean}\geq16)\approx P(Z\geq1.290994\ldots)$ \\
$=0.0983528\ldots$ \\
$\approx0.0984$.

@q 7
@topic Probability generating functions
@marks 15
@question
(a) For a probability generating function, $E(X)=G'_X(1)$. \\
Differentiate $G_X(t)=e^{\lambda(t-1)}$ by the chain rule. \\
The derivative of the exponent is $\lambda$. \\
$G'_X(t)=\lambda e^{\lambda(t-1)}$. \\
Put $t=1$: $G'_X(1)=\lambda e^{\lambda(1-1)}$. \\
$=\lambda e^0$ \\
$=\lambda$. \\
Therefore $E(X)=\lambda$, as required. \\
(b) Every probability generating function satisfies $G_Y(1)=1$. \\
Thus $\left(\frac{1}{a}+b\right)^n=1$. \\
As $a>0$, $b>0$ and $n$ is positive, the base is positive. \\
Taking the positive $n$th root gives $\frac{1}{a}+b=1$. \\
Subtract $\frac{1}{a}$ from both sides: \\
$b=1-\frac{1}{a}$, as required. \\
(c) Since $b>0$, $1-\frac{1}{a}>0$. \\
Thus $1>\frac{1}{a}$. \\
Multiply by $a>0$: $a>1$. \\
The range is $a>1$. \\
(d) Put $n=4$ and let $u=\frac{t^2}{a}+b$. \\
Then $G_Y(t)=u^4$ and $u'=\frac{2t}{a}$. \\
Use the chain rule: $G'_Y(t)=4u^3u'$. \\
$=\frac{8t}{a}\left(\frac{t^2}{a}+b\right)^3$. \\
By part (b), $\frac{1}{a}+b=1$. \\
So $E(Y)=G'_Y(1)=\frac{8}{a}(1)^3=\frac{8}{a}$. \\
Differentiate $G'_Y(t)$ with the product and chain rules: \\
$G''_Y(t)=\frac{8}{a}u^3+\frac{8t}{a}(3u^2)\frac{2t}{a}$. \\
$=\frac{8}{a}u^3+\frac{48t^2}{a^2}u^2$. \\
Put $t=1$ and $u=1$: \\
$G''_Y(1)=\frac{8}{a}+\frac{48}{a^2}$. \\
Use $G''_Y(1)=E[Y(Y-1)]=E(Y^2)-E(Y)$. \\
Hence $\mathrm{Var}(Y)=G''_Y(1)+E(Y)-[E(Y)]^2$. \\
$=\frac{8}{a}+\frac{48}{a^2}+\frac{8}{a}-\left(\frac{8}{a}\right)^2$ \\
$=\frac{16}{a}+\frac{48}{a^2}-\frac{64}{a^2}$ \\
$=\frac{16}{a}-\frac{16}{a^2}$ \\
$=\frac{16}{a^2}(a-1)$, as required.
