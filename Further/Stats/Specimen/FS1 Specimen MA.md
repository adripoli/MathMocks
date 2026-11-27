@paper FS1 Specimen

@q 1
@topic Chi-square uniform goodness of fit
@marks 8
@question
Under $H_0$, the seven days have equal speeding frequencies. \\
Under $H_1$, at least one day has a different probability. \\
Add the observed counts: \\
$35+30+28+24+40+51+37=245$. \\
With seven equally likely days, expected frequency per day is $245/7=35$. \\
No expected frequency is below five. \\
Use the chi-square statistic $\sum\frac{(O-E)^2}{E}$. \\
$=\frac{(35-35)^2}{35}+\frac{(30-35)^2}{35}+\frac{(28-35)^2}{35}$ \\
$+\frac{(24-35)^2}{35}+\frac{(40-35)^2}{35}+\frac{(51-35)^2}{35}+\frac{(37-35)^2}{35}$ \\
$=\frac{0+25+49+121+25+256+4}{35}$ \\
$=\frac{480}{35}=13.7142857\ldots$. \\
There are seven groups and no fitted parameters, so degrees of freedom $=7-1=6$. \\
At 5%, the upper critical value is $12.592$. \\
Since $13.7142857\ldots>12.592$, reject $H_0$. \\
The observations do not support Jeremy's belief that speeding is equally likely on every day.

@q 2
@topic Discrete distribution and variance
@marks 8
@question
(a) Calculate the mean from the probability table. \\
$E(Y)=\frac{1}{2}a+\frac{3}{10}(2)+\frac{1}{5}(7)$. \\
$=\frac{1}{2}a+\frac{3}{5}+\frac{7}{5}$ \\
$=\frac{1}{2}a+2$. \\
Calculate the second moment. \\
$E(Y^2)=\frac{1}{2}a^2+\frac{3}{10}(2^2)+\frac{1}{5}(7^2)$. \\
$=\frac{1}{2}a^2+\frac{6}{5}+\frac{49}{5}$ \\
$=\frac{1}{2}a^2+11$. \\
Use $\mathrm{Var}(Y)=E(Y^2)-[E(Y)]^2=28$. \\
$28=\frac{1}{2}a^2+11-\left(\frac{1}{2}a+2\right)^2$. \\
Expand the square: $\left(\frac{1}{2}a+2\right)^2=\frac{1}{4}a^2+2a+4$. \\
Substitute: $28=\frac{1}{4}a^2-2a+7$. \\
Subtract $28$: $\frac{1}{4}a^2-2a-21=0$. \\
Multiply by 4: $a^2-8a-84=0$. \\
Factor: $(a-14)(a+6)=0$. \\
Thus $a=14$ or $a=-6$. \\
For $a=14$, $E(Y)=9>0$, so reject it. \\
For $a=-6$, $E(Y)=-1<0$. \\
Therefore $a=-6$. \\
(b) Substitute each possible $Y$ into $\frac{1}{3-Y}$. \\
$E\left(\frac{1}{3-Y}\right)=\frac{1}{2}\frac{1}{3-(-6)}+\frac{3}{10}\frac{1}{3-2}+\frac{1}{5}\frac{1}{3-7}$. \\
$=\frac{1}{18}+\frac{3}{10}-\frac{1}{20}$. \\
Combine the last two terms: $\frac{3}{10}-\frac{1}{20}=\frac{1}{4}$. \\
$=\frac{1}{18}+\frac{1}{4}$ \\
$=\frac{2+9}{36}=\frac{11}{36}$.

@q 3
@topic Poisson sum and binomial count
@marks 10
@question
(a) Errors on $n$ of Tim's pages have Poisson mean $0.45n$. \\
The probability of zero errors is $e^{-0.45n}$. \\
Require $e^{-0.45n}<0.05$. \\
Take natural logs: $-0.45n<\ln(0.05)$. \\
Divide by $-0.45$, reversing the inequality: \\
$n>\frac{-\ln(0.05)}{0.45}=6.6571828\ldots$. \\
The smallest integer is $n=7$. \\
(b) Tim's five pages have Poisson mean $5(0.45)=2.25$. \\
Sue's five pages have Poisson mean $5(0.2)=1$. \\
Assume their errors occur independently. \\
Then the combined count $X$ has Poisson mean $2.25+1=3.25$. \\
$P(X=2)=e^{-3.25}\frac{3.25^2}{2!}$ \\
$=0.2047762851\ldots\approx0.205$. \\
(c) For one ten-page sample, the probability of no errors is $q=P(X=0)=e^{-3.25}$. \\
$=0.0387742078\ldots$. \\
Let $Y$ count no-error samples among ten independent samples. \\
$Y$ has a binomial distribution with $n=10$, $p=q$. \\
$P(Y\geq2)=1-P(Y=0)-P(Y=1)$. \\
$=1-(1-q)^{10}-10q(1-q)^9$. \\
$=0.0550031832\ldots\approx0.0550$.

@q 4
@topic Generating functions and second moments
@marks 14
@question
(a) The binomial generating function is $(1-p+pt)^n$. \\
Compare $(0.4+0.6t)^2$: $n=2$ and $p=0.6$. \\
(b)(i) Expand the square: \\
$G_X(t)=(0.4)^2+2(0.4)(0.6)t+(0.6)^2t^2$. \\
$=0.16+0.48t+0.36t^2$. \\
The coefficient of $t^1$ is $P(X=1)=0.48$. \\
(ii) Use $E(X)=G'_X(1)$. \\
Differentiate with the chain rule: \\
$G'_X(t)=2(0.4+0.6t)(0.6)$. \\
Put $t=1$: $G'_X(1)=2(1)(0.6)=1.2$. \\
Therefore $E(X)=1.2$. \\
(c) Independence gives $G_Y(t)=G_{X_1}(t)G_{X_2}(t)$. \\
$=(0.4+0.6t)^2(0.4+0.6t)^2$ \\
$=(0.4+0.6t)^4$. \\
Differentiate: \\
$G'_Y(t)=4(0.4+0.6t)^3(0.6)$. \\
$=2.4(0.4+0.6t)^3$. \\
At $t=1$, $G'_Y(1)=2.4(1)^3=2.4$. \\
Differentiate again: \\
$G''_Y(t)=2.4(3)(0.4+0.6t)^2(0.6)$. \\
$=4.32(0.4+0.6t)^2$. \\
At $t=1$, $G''_Y(1)=4.32$. \\
Since $G''_Y(1)=E[Y(Y-1)]=E(Y^2)-E(Y)$, \\
$E(Y^2)=G''_Y(1)+G'_Y(1)$. \\
$=4.32+2.4$ \\
$=6.72$, as required.

@q 5
@topic Geometric critical region and size
@marks 9
@question
(a) Let $p$ be a visitor's purchase probability. \\
Use $H_0:p=0.03$ and $H_1:p<0.03$. \\
Let $X$ count visits up to and including the first purchase. \\
Under $H_0$, $X$ is geometric with $p=0.03$. \\
A lower purchase probability makes longer waits more likely, so use $X\geq c$. \\
The geometric upper tail is $P(X\geq c)=(1-p)^{c-1}$. \\
Under $H_0$, $P(X\geq c)=0.97^{c-1}$. \\
Require $0.97^{c-1}<0.05$. \\
Take logs: $(c-1)\log(0.97)<\log(0.05)$. \\
Divide by the negative $\log(0.97)$ and reverse the inequality: \\
$c-1>\frac{\log(0.05)}{\log(0.97)}=98.352\ldots$. \\
Thus $c>99.352\ldots$ and the smallest integer is $100$. \\
Check $c=99$: $0.97^{98}=0.05054\ldots>0.05$. \\
Check $c=100$: $0.97^{99}=0.0490232\ldots<0.05$. \\
The critical region is $X\geq100$. \\
(b) Under $H_0$, the actual Type I error probability is the critical tail. \\
$P(X\geq100)=0.97^{99}$ \\
$=0.0490232040\ldots\approx0.0490$, or about $4.90\%$. \\
(c) The observed first purchase was at $X=94$. \\
Since $94<100$, it is outside the critical region. \\
Do not reject $H_0$; there is insufficient evidence at 5% that the purchase proportion is below $0.03$.

@q 6
@topic Normal test power and sample size
@marks 15
@question
(a) A Type I error rejects a true $H_0$. \\
The 5% test has Type I error probability $0.05$. \\
(b) Under $H_0$, the sample mean of ten bars is normal with mean $120$ and standard deviation $\frac{3}{\sqrt{10}}$. \\
Let the critical rule be sample mean $>c$. \\
For an upper 5% tail, the standard normal critical value is $1.6448536\ldots$. \\
$\frac{c-120}{3/\sqrt{10}}=1.6448536\ldots$. \\
Multiply by $3/\sqrt{10}$: \\
$c=120+1.6448536\ldots\frac{3}{\sqrt{10}}$ \\
$=121.560445\ldots$. \\
At true mean $122$, the sample mean still has standard deviation $3/\sqrt{10}$. \\
Power is $P(\text{sample mean}>121.560445\ldots)$. \\
Standardise under the true mean: \\
$z=\frac{121.560445\ldots-122}{3/\sqrt{10}}=-0.46334\ldots$. \\
$P(Z>-0.46334\ldots)=0.6784366\ldots$. \\
Therefore the power is $0.68$ to 2 significant figures. \\
(c) Reducing significance from 5% to 1% raises the upper critical value. \\
That makes rejection less likely at true mean $122$, so Alex's test has lower power. \\
(d) For $n$ bars under $H_0$, the sample mean has standard deviation $3/\sqrt{n}$. \\
At 5%, the upper critical value is $c_n=120+1.6448536\ldots\frac{3}{\sqrt{n}}$. \\
Under true mean $122$, power is $P(\text{sample mean}>c_n)$. \\
For power at least $0.9$, require the lower-tail probability at $c_n$ to be at most $0.1$. \\
The 10% lower standard normal quantile is $-1.2815516\ldots$. \\
$\frac{c_n-122}{3/\sqrt{n}}\leq-1.2815516\ldots$. \\
Substitute $c_n$: $\frac{-2+1.6448536\ldots(3/\sqrt{n})}{3/\sqrt{n}}\leq-1.2815516\ldots$. \\
Rearrange: $\frac{2\sqrt{n}}{3}\geq1.6448536\ldots+1.2815516\ldots$. \\
$\sqrt{n}\geq4.3896078\ldots$. \\
Square: $n\geq19.26865\ldots$. \\
The smallest integer is $n=20$. \\
Check: at $n=19$, power is below $0.9$; at $n=20$, it is $0.9093185\ldots$. \\
(e) Both Gizel's and Joseph's tests have size 5%, but Joseph's larger sample reaches power above $0.9$. \\
Use Joseph's test, because it is less likely to miss a true mean of 122 grams.

@q 7
@topic Negative binomial count and CLT
@marks 11
@question
Let $X$ be the number of calls up to and including the 12th correct answer in a day. \\
Each call succeeds independently with $p=\frac{3}{4}$, so $X$ has a negative binomial distribution with $r=12$. \\
(a) To finish on call 15, exactly 11 of the first 14 calls succeed, and call 15 succeeds. \\
Choose the 11 successful places among the first 14 in $14C11$ ways. \\
$P(X=15)=14C11\left(\frac{3}{4}\right)^{11}\left(\frac{1}{4}\right)^3\left(\frac{3}{4}\right)$. \\
$=14C11\left(\frac{3}{4}\right)^{12}\left(\frac{1}{4}\right)^3$. \\
$=0.1801592521\ldots\approx0.180$. \\
(b) Use the complement of finishing on call 12 or 13. \\
$P(X=12)=\left(\frac{3}{4}\right)^{12}$. \\
For $X=13$, one of the first 12 calls fails, then call 13 succeeds. \\
$P(X=13)=12\left(\frac{3}{4}\right)^{12}\left(\frac{1}{4}\right)$. \\
$P(X>13)=1-P(X=12)-P(X=13)$. \\
$=1-\left(\frac{3}{4}\right)^{12}-12\left(\frac{3}{4}\right)^{12}\left(\frac{1}{4}\right)$. \\
$=0.8732945919\ldots\approx0.873$. \\
(c) For a negative binomial count to $r$ successes, $E(X)=r/p$. \\
$E(X)=\frac{12}{3/4}=16$. \\
Use $\mathrm{Var}(X)=\frac{r(1-p)}{p^2}$. \\
$=\frac{12(1/4)}{(3/4)^2}$ \\
$=\frac{3}{9/16}=\frac{16}{3}$. \\
For 30 independent days, use the central limit theorem. \\
The sample mean is approximately normal with mean $16$. \\
Its variance is $\frac{16/3}{30}=\frac{8}{45}$. \\
Its standard deviation is $\sqrt{8/45}=0.421637\ldots$. \\
Standardise $15.5$: $z=\frac{15.5-16}{\sqrt{8/45}}=-1.185854\ldots$. \\
$P(\text{sample mean}>15.5)\approx P(Z>-1.185854\ldots)$ \\
$=0.8821600433\ldots\approx0.882$.
