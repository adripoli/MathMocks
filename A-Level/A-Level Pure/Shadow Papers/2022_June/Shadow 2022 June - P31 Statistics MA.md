@paper P31 Shadow June 2022

@q 1
@topic Binomial, normal approximation
@marks 6
@question
(a) Each throw is a success (hit) with probability 0.52, the throws are independent, and there are 25 of them \\
So $X$ follows $B(25, 0.52)$ \\
(i) $P(X = 12) = {}^{25}C_{12}(0.52)^{12}(0.48)^{13}$ \\
Use the binomial probability function on the calculator: \\
$P(X = 12) = 0.145950$ \\
$P(X = 12) = 0.146$ to 3 significant figures \\
(ii) $P(X \geq 7) = 1 - P(X \leq 6)$ \\
From the cumulative binomial function: $P(X \leq 6) = 0.004149$ \\
$P(X \geq 7) = 1 - 0.004149$ \\
$P(X \geq 7) = 0.995851$ \\
$P(X \geq 7) = 0.996$ to 3 significant figures \\
(b) For 350 throws, let $Y$ be the number of hits, so $Y$ follows $B(350, 0.52)$ \\
$n$ is large, so approximate with a normal distribution with the same mean and variance \\
Mean: $np = 350 \times 0.52 = 182$ \\
Variance: $npq = 350 \times 0.52 \times 0.48 = 87.36$ \\
So $Y$ is approximately $N(182, 87.36)$ (87.4 to 3 significant figures) \\
More than 210 hits means 211 or more, so use a continuity correction: \\
$P(Y > 210) \approx P(W > 210.5)$ where $W$ follows $N(182, 87.36)$ \\
$\sqrt{87.36} = 9.3466$ \\
$z = \frac{210.5 - 182}{9.3466}$ \\
$z = 3.0492$ \\
$P(Z > 3.0492) = 0.001147$ \\
The probability is 0.00115

@q 2
@topic Normal rods, expected profit, batches
@marks 12
@question
(a) $L$ follows $N(9, x^{2})$ and $P(L < 8.877) = 0.05$ \\
The $z$ value with 5% below it is $-1.6449$ \\
Standardise: $\frac{8.877 - 9}{x} = -1.6449$ \\
$8.877 - 9 = -0.123$ \\
$\frac{-0.123}{x} = -1.6449$ \\
Multiply by $x$ and divide by $-1.6449$: \\
$x = \frac{0.123}{1.6449}$ \\
$x = 0.074777$ \\
$x = 0.075$ to 3 decimal places as required \\
(b) Use $L$ follows $N(9, 0.075^{2})$ and the calculator \\
$P(8.92 \leq L \leq 9.07) = P(L \leq 9.07) - P(L \leq 8.92)$ \\
$P(L \leq 9.07) = 0.82468$ \\
$P(L \leq 8.92) = 0.14306$ \\
$P(8.92 \leq L \leq 9.07) = 0.82468 - 0.14306$ \\
$= 0.68162$ \\
The proportion is 0.682 \\
(c) Find the three probabilities: \\
$P(L < 8.92) = 0.14306$ (scrap) \\
$P(L > 9.07) = 1 - 0.82468 = 0.17532$ (shortened) \\
$P(8.92 \leq L \leq 9.07) = 0.68162$ (sold as it is) \\
(Check: $0.14306 + 0.17532 + 0.68162 = 1$) \\
Now the profit on each rod, in pence (selling price minus costs): \\
Scrap: $6 - 30 = -24$ \\
Sold as it is: $60 - 30 = +30$ \\
Shortened: $60 - 30 - 12 = +18$ \\
Expected profit per rod $= \sum(\text{profit} \times \text{probability})$ \\
$= 30 \times 0.68162 + (-24) \times 0.14306 + 18 \times 0.17532$ \\
$30 \times 0.68162 = 20.4486$ \\
$24 \times 0.14306 = 3.4334$ \\
$18 \times 0.17532 = 3.1558$ \\
$= 20.4486 - 3.4334 + 3.1558$ \\
$= 20.171$ pence \\
Expected profit per 600 rods: $600 \times 20.171 = 12102.6$ pence \\
Change pence to pounds: $12102.6 \div 100 = 121.03$ \\
The expected profit per 600 rods is GBP 121 to the nearest pound \\
(d) Each hinge is faulty with probability 0.02, independently, in a sample of 150 \\
Let $X$ be the number of faulty hinges in the sample, $X$ follows $B(150, 0.02)$ \\
A batch is accepted if fewer than 6 are faulty, which is $X \leq 5$ \\
$P(X \leq 5) = 0.91812$ from the cumulative binomial function \\
So about 91.8% of the batches are accepted \\
The aim is 99% accepted, and $0.918 < 0.99$ \\
So the manufacturer is unlikely to achieve its aim

@q 3
@topic Large data set, rainfall, mean, sd
@marks 7
@question
(a) In the large data set, a Daily Total Rainfall between 0 and 0.05 mm is too small to measure and is recorded as tr (for "trace") \\
(b)(i) Mean $= \frac{\sum r}{n}$ \\
$\mu = \frac{61.4}{31}$ \\
$\mu = 1.9806$ \\
$\mu = 1.98$ mm to 3 significant figures \\
(ii) Standard deviation $\sigma = \sqrt{\frac{\sum r^{2}}{n} - \mu^{2}}$ \\
$\frac{\sum r^{2}}{n} = \frac{463.88}{31}$ \\
$= 14.9639$ \\
$\mu^{2} = 1.98065^{2}$ \\
$= 3.9230$ \\
$\sigma = \sqrt{14.9639 - 3.9230}$ \\
$\sigma = \sqrt{11.0409}$ \\
$\sigma = 3.3228$ \\
$\sigma = 3.32$ mm to 3 significant figures \\
(c) Dian believes the mean rainfall in July 1987 was lower in the South of the UK than the North \\
Leuchars is in the North of the UK (Scotland) and Camborne is in the South of the UK (Cornwall) \\
Mean for Leuchars is 1.98 mm and mean for Camborne is 1.22 mm \\
$1.22 < 1.98$, so the mean is smaller in the South \\
So this may support Dian's belief, but it is only one place in each area, so it is not strong evidence \\
(d) $B(10, 0.20)$ assumes the probability of a day without rain is a constant 0.20, and that the days are independent \\
But the probability of no rain in summer is not likely to be the same as the yearly average, and one day's weather depends on the previous day's weather \\
So $p = 0.20$ is unlikely to be constant

@q 4
@topic Two-tailed binomial test, critical region
@marks 6
@question
(a) No change means the proportion who arrive late is still 0.15 \\
$H_{0}: p = 0.15$ \\
The manager believes there has been a change, which could be up or down, so the test is two tailed \\
$H_{1}: p \neq 0.15$ \\
(b) Let $X$ be the number of late customers in a sample of 60 \\
Under $H_{0}$, $X$ follows $B(60, 0.15)$ \\
Each tail has at most 5% (0.05) for a 10% two tailed test \\
Lower tail: find the largest $c$ with $P(X \leq c) < 0.05$ \\
$P(X \leq 4) = 0.04237$, which is less than 0.05 \\
$P(X \leq 5) = 0.09680$, which is more than 0.05 \\
So the lower critical value is 4 \\
Upper tail: find the smallest $d$ with $P(X \geq d) < 0.05$ \\
$P(X \geq 15) = 1 - P(X \leq 14) = 1 - 0.97087 = 0.02913$, which is less than 0.05 \\
$P(X \geq 14) = 1 - P(X \leq 13) = 1 - 0.94218 = 0.05782$, which is more than 0.05 \\
So the upper critical value is 15 \\
The critical region is $X \leq 4$ or $X \geq 15$ \\
The probability of rejection in the lower tail is 0.04237 \\
The probability of rejection in the upper tail is 0.02913 \\
(c) The actual level of significance is the total probability of the critical region: \\
$0.04237 + 0.02913$ \\
$= 0.0715$ \\
So the actual level of significance is 7.15% \\
(d) The manager observes $X = 14$ \\
14 is not in the critical region ($X \leq 4$ or $X \geq 15$) \\
So do not reject $H_{0}$: there is insufficient evidence to support the manager's belief that the proportion of late customers has changed

@q 5
@topic Employees table and Venn diagram
@marks 10
@question
(a) Skilled employees: $270 + 120 = 390$ \\
$P(\text{skilled}) = \frac{390}{1670}$ \\
$= 0.23353$ \\
$= 0.234$ \\
(b) Lives in area $B$ and is not a professional means skilled or elementary in $B$: \\
$120 + 60 = 180$ \\
$P = \frac{180}{1670}$ \\
$= \frac{18}{167}$ \\
$= 0.1078$ \\
(c) $F$ is professional, $H$ works from home, $R$ is area $A$ \\
Professionals in area $A$: 625, and 60% of them work from home: \\
$0.6 \times 625 = 375$ \\
So $H$ and $R$ and $F$ together has 375 \\
The other 40% of area $A$ professionals do not work from home: \\
$0.4 \times 625 = 250$ \\
So $R$ and $F$ only (not $H$) has 250 \\
Professionals in total: $625 + 345 = 970$ \\
60% of all the professionals work from home: $0.6 \times 970 = 582$ \\
Those in $H$ and $F$ but not $R$ (professionals in area $B$ who work from home): $582 - 375 = 207$ \\
This matches the 207 on the diagram \\
Professionals in $F$ only: $345 - 207 = 138$, which matches the 138 on the diagram \\
Skilled and elementary employees in $H$ only (area $B$): \\
Skilled in $B$: $0.3 \times 120 = 36$ \\
Elementary in $B$: $0.1 \times 60 = 6$ \\
$H$ only $= 36 + 6 = 42$ \\
Check the region $H$ and $R$ only (area $A$, not professional): $0.3 \times 270 + 0.1 \times 250 = 81 + 25 = 106$, which matches \\
Outside all the circles: not $H$, not $R$, not $F$, which is area $B$, not professional, not at home: \\
$(120 - 36) + (60 - 6) = 84 + 54 = 138$ \\
(Check the total: $42 + 106 + 414 + 375 + 207 + 250 + 138 + 138 = 1670$) \\
(Diagram: the Venn diagram with 42 in $H$ only, 106 in $H$ and $R$ only, 414 in $R$ only, 375 in all three, 207 in $H$ and $F$ only, 250 in $R$ and $F$ only, 138 in $F$ only, and 138 outside) \\
(d) $R'$ and $F$ is a professional who is not in area $A$, so a professional in area $B$ \\
$P(R' \text{ and } F) = \frac{345}{1670}$ \\
$= \frac{69}{334}$ \\
$= 0.2066$ \\
$= 0.207$ \\
(e) $[H \text{ or } R]'$ is neither working from home nor in area $A$ \\
That is the regions $F$ only (138) and outside (138): \\
$138 + 138 = 276$ \\
$P = \frac{276}{1670}$ \\
$= \frac{138}{835}$ \\
$= 0.1653$ \\
$= 0.165$ \\
(f) $P(F | H) = \frac{P(F \text{ and } H)}{P(H)}$ \\
$F$ and $H$: the regions $H$, $F$ and $R$ (375) and $H$ and $F$ only (207): $375 + 207 = 582$ \\
$H$: all the regions in $H$: $42 + 106 + 375 + 207 = 730$ \\
$P(F | H) = \frac{582}{730}$ \\
Divide the top and bottom by 2: \\
$= \frac{291}{365}$ \\
$= 0.7973$ \\
$= 0.797$

@q 6
@topic Scatter, correlation test, coded model
@marks 9
@question
(a) The scatter diagram shows $h$ decreasing as $m$ increases, but the points drop steeply at first and then flatten out \\
As the number of minutes exercised per week increases, the resting heart rate decreases \\
Each extra minute of exercise has a smaller effect, which is a diminishing effect \\
(b) The test is for a negative correlation, so it is one tailed \\
$H_{0}: \text{rho} = 0$ \\
$H_{1}: \text{rho} < 0$ \\
The sample size is $n = 21$ and the significance level is 2.5% \\
From the table of critical values (one tail, 2.5%, $n = 21$) the critical value is 0.4329 \\
For a negative correlation test the critical region is $r < -0.4329$ \\
The sample value is $r = -0.901$ \\
$-0.901 < -0.4329$, so the value is in the critical region \\
Reject $H_{0}$ \\
There is evidence, at the 2.5% level, of a negative correlation between $x$ and $y$ \\
(c) The line is $y = -0.03x + 1.95$ \\
Put back $x = \log_{10} m$ and $y = \log_{10} h$: \\
$\log_{10} h = -0.03\log_{10} m + 1.95$ \\
We want $h = am^{k}$ \\
Take logs (base 10) of $h = am^{k}$: \\
$\log_{10} h = \log_{10}(am^{k})$ \\
Use $\log xy = \log x + \log y$: \\
$\log_{10} h = \log_{10} a + \log_{10} m^{k}$ \\
Use $\log x^{n} = n\log x$: \\
$\log_{10} h = \log_{10} a + k\log_{10} m$ \\
Compare this with $\log_{10} h = 1.95 - 0.03\log_{10} m$ \\
The constant terms match: $\log_{10} a = 1.95$ \\
The coefficients of $\log_{10} m$ match: $k = -0.03$ \\
Find $a$: raise 10 to the power of each side: \\
$a = 10^{1.95}$ \\
$a = 89.125$ \\
$a = 89.1$ to 3 significant figures \\
$h = 89.1m^{-0.03}$ \\
(or $h = 10^{1.95}m^{-0.03}$)
