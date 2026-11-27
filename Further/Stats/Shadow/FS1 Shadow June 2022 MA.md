@paper FS1 Shadow June 2022

@q 1
@topic Binomial chi-square goodness of fit
@marks 9
@question
(a) Under the proposed binomial model, each litter has five cubs and female probability $0.5$. \\
For $k$ females, $P(X=k)=5Ck(0.5)^k(0.5)^{5-k}=5Ck(0.5)^5$. \\
Multiply by 200 litters for expected frequencies. \\
$r=200P(X=0)=200(5C0)(0.5)^5$. \\
$=200/32=6.25$. \\
$s=200P(X=2)=200(5C2)(0.5)^5$. \\
$=200(10)/32=62.5$. \\
Symmetry gives the same values for five and three females. \\
(b) Under $H_0$, the binomial model with $n=5$, $p=0.5$ is suitable. \\
Under $H_1$, it is unsuitable. \\
The expected counts are $6.25,31.25,62.5,62.5,31.25,6.25$; all exceed five. \\
Use the chi-square statistic $\sum\frac{(O-E)^2}{E}$. \\
$=\frac{(11-6.25)^2}{6.25}+\frac{(22-31.25)^2}{31.25}$ \\
$+\frac{(60-62.5)^2}{62.5}+\frac{(72-62.5)^2}{62.5}$ \\
$+\frac{(19-31.25)^2}{31.25}+\frac{(16-6.25)^2}{6.25}$ \\
$=3.61+2.738+0.1+1.444+4.802+15.21$ \\
$=27.904$. \\
There are six groups and no fitted parameter, so degrees of freedom $=6-1=5$. \\
The 5% upper critical value is $11.070$. \\
Since $27.904>11.070$, reject $H_0$. \\
There is significant evidence at 5% that the proposed binomial model is unsuitable.

@q 2
@topic Discrete variance and quadratic inequality
@marks 9
@question
(a) Multiply each value by its probability. \\
$E(X)=(-7)(0.4)+(-2)(0.15)+0(0.2)+7(0.15)+b(0.1)$. \\
$=-2.8-0.3+1.05+0.1b$. \\
$=0.1b-2.05$. \\
(b) Use $E(X^2)=\sum x^2P(X=x)$. \\
$E(X^2)=49(0.4)+4(0.15)+0+49(0.15)+0.1b^2$. \\
$=19.6+0.6+7.35+0.1b^2$. \\
$=27.55+0.1b^2$. \\
Use $\mathrm{Var}(X)=E(X^2)-[E(X)]^2$. \\
$43.8875=27.55+0.1b^2-(0.1b-2.05)^2$. \\
Expand the square: $(0.1b-2.05)^2=0.01b^2-0.41b+4.2025$. \\
Substitute and collect terms: \\
$43.8875=23.3475+0.09b^2+0.41b$. \\
Subtract $43.8875$: $0.09b^2+0.41b-20.54=0$. \\
Multiply by 100: $9b^2+41b-2054=0$. \\
Factor: $(b-13)(9b+158)=0$. \\
Thus $b=13$ or $b=-158/9$. \\
Reject the negative root because $b>7$. \\
Hence $b=13$. \\
(c) Rearrange $X^2<4-5X$ as $X^2+5X-4<0$. \\
Check each support value. \\
For $x=-7$, $49-35-4=10>0$: exclude. \\
For $x=-2$, $4-10-4=-10<0$: include. \\
For $x=0$, $-4<0$: include. \\
For $x=7$, $49+35-4=80>0$: exclude. \\
For $x=13$, $169+65-4=230>0$: exclude. \\
Add the included probabilities: $P(X=-2)+P(X=0)=0.15+0.2=0.35$.

@q 3
@topic Independent Poisson processes
@marks 14
@question
(a) Let $X$ count calls to team A over 26 summer days. \\
The Poisson mean is $26(0.6)=15.6$. \\
$P(X\geq21)=1-P(X\leq20)$ \\
$=0.1105898915\ldots\approx0.111$. \\
(b) Let $S$ count calls to A in a single summer day, with Poisson mean $0.6$. \\
The chance of more than two calls is $q=P(S>2)$. \\
$=1-e^{-0.6}\left(1+0.6+\frac{0.6^2}{2!}\right)$ \\
$=0.0231152878\ldots$. \\
Let $D$ count these days among the 200 independent days. \\
$D$ has a binomial distribution with $n=200$, $p=q$. \\
Since $q$ is small, approximate $D$ by Poisson with mean $200q$. \\
$=200(0.0231152878\ldots)=4.62305755\ldots$. \\
$P(D\geq10)\approx1-P(D\leq9)$ \\
$=0.0201226664\ldots\approx0.0201$. \\
(c) Under $H_0$, the winter call rate remains $0.6$ per day. \\
Under $H_1$, it is below $0.6$ per day. \\
For 35 days under $H_0$, the Poisson mean is $35(0.6)=21$. \\
The lower-tail probability of the observed 11 calls is $P(X\leq11)$. \\
$=0.0129047670\ldots$. \\
Since $0.0129047670\ldots<0.05$, reject $H_0$. \\
There is significant evidence at 5% that team A receives fewer calls per day in winter. \\
(d) Teams A and B have independent Poisson call processes. \\
Their combined daily rate is $0.6+0.3=0.9$. \\
Over the next $n$ days, $C$ has Poisson mean $0.9n$. \\
The calls on the preceding Monday do not change the independent future count. \\
$P(C=0)=e^{-0.9n}<0.002$. \\
Take natural logs: $-0.9n<\ln(0.002)$. \\
Divide by $-0.9$ and reverse the inequality: \\
$n>\frac{-\ln(0.002)}{0.9}=6.905120\ldots$. \\
The minimum whole number is $n=7$. \\
(e) The rates of calls to each team must stay constant over the modelled days.

@q 4
@topic Geometric, binomial and negative binomial
@marks 13
@question
(a)(i) First blue on spin 5 means four non-blue spins, then blue. \\
Non-blue probability is $1-0.22=0.78$. \\
$P=(0.78)^4(0.22)$ \\
$=0.0814331232\ldots\approx0.0814$. \\
(ii) "Before the 5th" means within spins 1 to 4. \\
Use the complement of four non-blue spins: \\
$P=1-(0.78)^4$ \\
$=0.62984944\ldots\approx0.630$. \\
(iii) Let $X$ count blues among the first five spins. \\
$X$ has a binomial distribution with $n=5$, $p=0.22$. \\
$P(X=3)=5C3(0.22)^3(0.78)^2$ \\
$=10(0.22)^3(0.78)^2$ \\
$=0.064782432\ldots\approx0.0648$. \\
(iv) Let $Y$ be the spin number of the third blue. \\
The third blue can occur on spin 3, 4 or 5. \\
$P(Y=3)=(0.22)^3$. \\
$P(Y=4)=3C2(0.22)^3(0.78)$. \\
$P(Y=5)=4C2(0.22)^3(0.78)^2$. \\
Add the disjoint cases: \\
$P(Y\leq5)=(0.22)^3+3(0.22)^3(0.78)+6(0.22)^3(0.78)^2$ \\
$=0.0744337792\ldots\approx0.0744$. \\
(b) Izana must miss, then Zac hit, for Zac to win in the first pair of turns. \\
That has probability $(0.78)(0.22)$. \\
For each later pair, both players must miss first, adding a factor $(0.78)^2$. \\
$P(\text{Zac wins})=(0.78)(0.22)[1+(0.78)^2+(0.78)^4+\cdots]$. \\
The bracket is an infinite geometric series with ratio $(0.78)^2$. \\
$P(\text{Zac wins})=\frac{(0.78)(0.22)}{1-(0.78)^2}$ \\
$=0.4382022472\ldots$ \\
$=0.438$ to 3 significant figures, as required.

@q 5
@topic Geometric sample mean approximation
@marks 5
@question
For a geometric variable with $p=0.4$, use $E(X)=\frac{1}{p}$. \\
$E(X)=\frac{1}{0.4}=2.5$. \\
Use $\mathrm{Var}(X)=\frac{1-p}{p^2}$. \\
$=\frac{0.6}{(0.4)^2}$ \\
$=\frac{0.6}{0.16}=3.75$. \\
For 250 independent observations, use the central limit theorem. \\
The sample mean is approximately normal with mean $2.5$. \\
Its variance is $\frac{3.75}{250}=0.015$. \\
Its standard deviation is $\sqrt{0.015}=0.122474\ldots$. \\
Standardise $2.65$: $z=\frac{2.65-2.5}{\sqrt{0.015}}$. \\
$=\frac{0.15}{0.122474\ldots}=1.224745\ldots$. \\
$P(\text{sample mean}<2.65)\approx P(Z<1.224745\ldots)$ \\
$=0.8896643190\ldots\approx0.890$.

@q 6
@topic Generating functions and binomial moments
@marks 14
@question
(a) A generating function sums each probability times $t$ to its value. \\
$G_V(t)=\frac{36}{121}t^4+\frac{60}{121}t^5+\frac{25}{121}t^6$. \\
Factor out $t^4$: \\
$=t^4\left(\frac{36}{121}+\frac{60}{121}t+\frac{25}{121}t^2\right)$. \\
The bracket is a perfect square: \\
$=t^4\left(\frac{6}{11}+\frac{5}{11}t\right)^2$, as required. \\
(b)(i) Let $u=\frac{5}{11}t+\frac{6}{11}$. \\
Then $G_W(t)=tu^{11}$ and $u'=\frac{5}{11}$. \\
Use the product and chain rules: \\
$G'_W(t)=u^{11}+t(11u^{10})\frac{5}{11}$. \\
$=u^{11}+5tu^{10}$. \\
At $t=1$, $u=1$, so $E(W)=G'_W(1)=1+5=6$. \\
(ii) Differentiate $G'_W(t)=u^{11}+5tu^{10}$: \\
$G''_W(t)=11u^{10}\frac{5}{11}+5u^{10}+5t(10u^9)\frac{5}{11}$. \\
$=10u^{10}+\frac{250t}{11}u^9$. \\
At $t=1$, $G''_W(1)=10+\frac{250}{11}=\frac{360}{11}$. \\
Use $\mathrm{Var}(W)=G''_W(1)+G'_W(1)-[G'_W(1)]^2$. \\
$=\frac{360}{11}+6-6^2$ \\
$=\frac{360}{11}-30$ \\
$=\frac{30}{11}$. \\
(c) Independence makes the generating functions multiply. \\
$G_X(t)=t^4u^2\cdot tu^{11}$ \\
$=t^5u^{13}$ \\
$=t^5\left(\frac{5}{11}t+\frac{6}{11}\right)^{13}$. \\
(d) Use $Y=4X+5$: \\
$G_Y(t)=E(t^{4X+5})$ \\
$=t^5G_X(t^4)$ \\
$=t^5(t^4)^5\left(\frac{5}{11}t^4+\frac{6}{11}\right)^{13}$ \\
$=t^{25}\left(\frac{5}{11}t^4+\frac{6}{11}\right)^{13}$. \\
(e) To get $t^{33}$ from $t^{25}$, choose two of the thirteen $t^4$ factors. \\
$P(Y=33)=13C2\left(\frac{5}{11}\right)^2\left(\frac{6}{11}\right)^{11}$ \\
$=0.0204924299\ldots\approx0.0205$.

@q 7
@topic Normal mean test and Type II error
@marks 11
@question
(a) Under $H_0$, each bag has mean $900$ grams and standard deviation $40$ grams. \\
For $20$ independent bags, the sample mean has mean $900$. \\
Its variance is $\frac{40^2}{20}=80$ and standard deviation $\sqrt{80}=8.944272\ldots$. \\
Standardise the observed sample mean $920$: \\
$z=\frac{920-900}{\sqrt{80}}=2.236068\ldots$. \\
The upper-tail probability is $P(Z>2.236068\ldots)=0.0126736593\ldots$. \\
For a two-sided 10% test, compare this with $0.05$ in the upper tail. \\
Since $0.0126736593\ldots<0.05$, reject $H_0$. \\
There is evidence at 10% that the mean bag weight differs from 900 grams. \\
(b) Under $H_0$, the second sample mean has standard deviation $40/\sqrt{n}$. \\
An upper 10% region starts at standard normal $z=1.2815516\ldots$. \\
Thus $\frac{c-900}{40/\sqrt{n}}=1.2815516\ldots$. \\
Multiply through: $c-900=\frac{40(1.2815516\ldots)}{\sqrt{n}}$. \\
$c=900+\frac{51.2620626\ldots}{\sqrt{n}}$. \\
(c) At the true mean $920$, Type II error means sample mean $\leq c$. \\
To have lower-tail probability about $0.0010$, its standard normal value is $-3.0902323\ldots$. \\
$\frac{c-920}{40/\sqrt{n}}\approx-3.0902323\ldots$. \\
Substitute the expression for $c$: \\
$\frac{-20+51.2620626\ldots/\sqrt{n}}{40/\sqrt{n}}\approx-3.0902323\ldots$. \\
Multiply by $40$: $-20\sqrt{n}+51.2620626\ldots\approx-123.609292\ldots$. \\
$20\sqrt{n}\approx174.871355\ldots$. \\
$\sqrt{n}\approx8.743568\ldots$, so $n\approx76.45$. \\
Check the nearby integer sample sizes against the required 2 significant figures. \\
For $n=75$, the Type II probability is $0.00114965\ldots$, or $0.0011$ to 2 significant figures. \\
For $n=76$, it is $0.00104426\ldots$, or $0.0010$ to 2 significant figures. \\
Therefore use $n=76$. \\
$c=900+\frac{51.2620626\ldots}{\sqrt{76}}$ \\
$=905.880162\ldots$ grams, about $905.88$ grams.
