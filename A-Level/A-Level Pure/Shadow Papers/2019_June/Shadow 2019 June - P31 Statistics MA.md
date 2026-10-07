@paper P31 Shadow June 2019

@q 1
@topic Tree diagram, three boxes of scarves
@marks 8
@question
(a) Box $A$ has 1 red and 7 green scarves, 8 in total \\
$P(\text{red from } A) = \frac{1}{8}$ and $P(\text{green from } A) = \frac{7}{8}$ \\
If she picks red she stops, so there are no more branches after R \\
Box $B$ is the same as box $A$: \\
$P(\text{red from } B) = \frac{1}{8}$ and $P(\text{green from } B) = \frac{7}{8}$ \\
Box $C$ has 1 red and 9 green scarves, 10 in total: \\
$P(\text{red from } C) = \frac{1}{10}$ and $P(\text{green from } C) = \frac{9}{10}$ \\
(Diagram: first stage G $\frac{7}{8}$ and R $\frac{1}{8}$. From G, second stage G $\frac{7}{8}$ and R $\frac{1}{8}$. From the second G, third stage G $\frac{9}{10}$ and R $\frac{1}{10}$. The R branches end.) \\
(b) 3 green scarves means green from $A$, then green from $B$, then green from $C$ \\
Multiply along the branches: \\
$P(GGG) = \frac{7}{8} \times \frac{7}{8} \times \frac{9}{10}$ \\
$\frac{7}{8} \times \frac{7}{8} = \frac{49}{64}$ \\
$\frac{49}{64} \times \frac{9}{10} = \frac{441}{640}$ \\
$P(\text{3 green scarves}) = \frac{441}{640}$ \\
(c) At least 1 scarf of each colour means at least one green and at least one red \\
She picks a red scarf at some stage, and she must have picked at least one green before it \\
Case 1: green from $A$ then red from $B$: \\
$\frac{7}{8} \times \frac{1}{8} = \frac{7}{64}$ \\
Case 2: green from $A$, green from $B$, then red from $C$: \\
$\frac{7}{8} \times \frac{7}{8} \times \frac{1}{10} = \frac{49}{640}$ \\
(Red from $A$ straight away is only one scarf, so it does not count) \\
Add the two cases. Write $\frac{7}{64}$ over the denominator 640: \\
$\frac{7}{64} = \frac{70}{640}$ \\
$\frac{70}{640} + \frac{49}{640} = \frac{119}{640}$ \\
$P(\text{at least one of each colour}) = \frac{119}{640}$ \\
(d) She selects a red scarf in total with probability $1 - P(GGG)$ \\
$1 - \frac{441}{640} = \frac{199}{640}$ \\
She selects the red scarf from $B$ with probability: \\
$P(G \text{ then } R) = \frac{7}{8} \times \frac{1}{8} = \frac{7}{64} = \frac{70}{640}$ \\
Conditional probability: $P(\text{from } B | \text{red}) = \frac{P(\text{red from } B)}{P(\text{red})}$ \\
$= \frac{\frac{70}{640}}{\frac{199}{640}}$ \\
Cancel the 640: \\
$= \frac{70}{199}$

@q 2
@topic Box plot, outliers, normal model
@marks 11
@question
(a) From Figure 1: $Q_{1} = 19.4$ and $Q_{3} = 26.6$ \\
$IQR = Q_{3} - Q_{1}$ \\
$IQR = 26.6 - 19.4$ \\
$IQR = 7.2$ \\
Lower fence: $Q_{1} - 1.5 \times IQR$ \\
$1.5 \times 7.2 = 10.8$ \\
$19.4 - 10.8 = 8.6$ \\
Upper fence: $Q_{3} + 1.5 \times IQR$ \\
$26.6 + 10.8 = 37.4$ \\
A value below 8.6 is an outlier \\
The three lowest values are 7.6, 9.5 and 10.9 \\
$7.6 < 8.6$, so 7.6 is an outlier \\
$9.5 > 8.6$ and $10.9 > 8.6$, so these are not outliers \\
The highest value 31.6 is less than 37.4, so it is not an outlier \\
Draw the box plot: \\
The lower whisker goes down to the lowest value that is not an outlier, 9.5 \\
The upper whisker goes up to the highest value, 31.6 \\
Mark 7.6 with a cross as an outlier \\
(Diagram: the box from 19.4 to 26.6 as given, a whisker from 19.4 down to 9.5, a whisker from 26.6 up to 31.6, and a cross at 7.6) \\
The only outlier is 7.6 degrees C \\
(b) The cold outliers would be the coldest days in the data set \\
The data set for Beijing covers May to October, and October is the coldest of these months \\
So the outlier is most likely from October \\
(c) Standard deviation: $\sigma = \sqrt{\frac{S_{xx}}{n}}$ \\
$\frac{S_{xx}}{n} = \frac{4877.585}{166}$ \\
$= 29.3830$ \\
$\sigma = \sqrt{29.3830}$ \\
$\sigma = 5.4206$ \\
$\sigma = 5.42$ to 3 significant figures as required \\
(d) For $T$ follows $N(25.44, 5.42^{2})$ find the 10th and 90th percentiles \\
The 90th percentile has $z = 1.2816$, and the 10th percentile has $z = -1.2816$ \\
90th percentile: $25.44 + 1.2816 \times 5.42$ \\
$1.2816 \times 5.42 = 6.9463$ \\
$25.44 + 6.9463 = 32.386$ \\
10th percentile: $25.44 - 6.9463 = 18.494$ \\
Interpercentile range $= 32.386 - 18.494$ \\
$= 13.892$ \\
Or: $2 \times 1.2816 \times 5.42 = 13.89$ \\
The 10th to 90th interpercentile range is 13.9 degrees C \\
(e) A normal distribution is symmetric and for continuous numerical data \\
Daily mean wind speed (Beaufort) is not suitable, because it is recorded as a category on a scale (qualitative) rather than a continuous measurement \\
Daily total rainfall is not suitable, because most days have little or no rain and a few have a lot, so the distribution is not symmetric (it is skewed)

@q 3
@topic Correlation hypothesis test, log model
@marks 9
@question
(a) The test is about the population product moment correlation coefficient, $\text{rho}$ \\
Helen wants to know if $\text{rho}$ is greater than zero, so the test is one tailed \\
$H_{0}: \text{rho} = 0$ \\
$H_{1}: \text{rho} > 0$ \\
The sample size is $n = 24$ and the significance level is 5% \\
From the table of critical values for the product moment correlation coefficient (one tail, 5%, $n = 24$): \\
Critical value $= 0.3438$ \\
The sample value is $r = 0.4771$ \\
$0.4771 > 0.3438$ \\
The sample value is in the critical region, so reject $H_{0}$ \\
There is sufficient evidence, at the 5% level, that the product moment correlation coefficient between income and CO$_{2}$ emissions is greater than zero \\
(b) The new correlation coefficient $0.8432$ is closer to 1 than the original 0.4771 \\
So the data are closer to a straight line after coding with logs, which means a non-linear model of the form $y = ax^{n}$ fits better than a linear model \\
(c) Replace $c$ and $m$ by their definitions in $c = -0.47 + 0.92m$: \\
$\log_{10} y = -0.47 + 0.92\log_{10} x$ \\
Raise 10 to the power of each side: \\
$10^{\log_{10} y} = 10^{-0.47 + 0.92\log_{10} x}$ \\
$10^{\log_{10} y} = y$ \\
$y = 10^{-0.47 + 0.92\log_{10} x}$ \\
Use the index law $10^{a + b} = 10^{a} \times 10^{b}$: \\
$y = 10^{-0.47} \times 10^{0.92\log_{10} x}$ \\
Use $a\log x = \log x^{a}$ in the power: $0.92\log_{10} x = \log_{10} x^{0.92}$ \\
$y = 10^{-0.47} \times 10^{\log_{10} x^{0.92}}$ \\
$10^{\log_{10} x^{0.92}} = x^{0.92}$ \\
$y = 10^{-0.47} \times x^{0.92}$ \\
$10^{-0.47} = 0.33884$ \\
$y = 0.34x^{0.92}$ \\
So $a = 0.34$ and $n = 0.92$

@q 4
@topic Binomial model of cloud cover
@marks 9
@question
(a) The number of days with cloud cover 7 is 59 and with cover 8 is 31 \\
Days with 7 or greater: $59 + 31 = 90$ \\
$P(7 \text{ or greater}) = \frac{90}{195}$ \\
$= 0.4615$ \\
$= 0.462$ \\
(b)(i) $X$ follows $B(8, 0.78)$ \\
$P(X \geq 7) = 1 - P(X \leq 6)$ \\
Find $P(X \leq 6)$ from the cumulative binomial function on the calculator: \\
$P(X \leq 6) = 0.5538$ \\
$P(X \geq 7) = 1 - 0.5538$ \\
$P(X \geq 7) = 0.4462$ \\
$P(X \geq 7) = 0.45$ to 2 decimal places (the scheme shows 0.446, which is the same value to 3 decimal places) \\
(Check by adding: $P(X = 7) + P(X = 8) = 0.3092 + 0.78^{8} = 0.3092 + 0.1370 = 0.4462$) \\
(ii) $P(X = 7) = {}^{8}C_{7}(0.78)^{7}(0.22)^{1}$ \\
${}^{8}C_{7} = 8$ \\
$0.78^{7} = 0.175656$ \\
$8 \times 0.175656 = 1.405245$ \\
$1.405245 \times 0.22 = 0.309154$ \\
So $P(X = 7) = 0.3092$ \\
Expected number of days $= 195 \times P(X = 7)$ \\
$= 195 \times 0.3092$ \\
$= 60.29$ \\
The expected number of days is 60.3 \\
(c) From the data, the proportion of days with 7 or more is 0.462, and the model gives $P(X \geq 7) = 0.446$, which is very similar \\
From the data, 59 days had cover 7, and the model expects 60.3 days, which is very close \\
So these answers support the use of Chen's model \\
(d) Of the 31 days after a cover of 8, the days with cover 7 or more are $9 + 11 = 20$ \\
Proportion $= \frac{20}{31}$ \\
$= 0.6452$ \\
$= 0.645$ \\
(e) After a day with cover 8, the proportion with cover 7 or greater is 0.645 \\
This is much more than 0.462, the proportion for any day \\
So the cloud cover on one day depends on the previous day: a cloudy day is more likely to be followed by a cloudy day \\
A binomial model needs the trials to be independent, so the independence assumption fails \\
So the binomial model might not be suitable

@q 5
@topic Normal distribution, approximation, test
@marks 13
@question
(a) $D$ follows $N(28, \sigma^{2})$ and $P(D < 27.29) = 0.05$ \\
Find the $z$ value with 5% below it: $z = -1.6449$ \\
Standardise: $\frac{27.29 - 28}{\sigma} = -1.6449$ \\
$27.29 - 28 = -0.71$ \\
$\frac{-0.71}{\sigma} = -1.6449$ \\
Multiply both sides by $\sigma$ and divide by $-1.6449$: \\
$\sigma = \frac{0.71}{1.6449}$ \\
$\sigma = 0.4316$ \\
We have $P(27.29 < D < k) = 0.55$ \\
$P(D < 27.29) = 0.05$, so \\
$P(D < k) = 0.05 + 0.55$ \\
$P(D < k) = 0.60$ \\
Find the $z$ value with 60% below it: $z = 0.2533$ \\
$\frac{k - 28}{0.4316} = 0.2533$ \\
Multiply by 0.4316: \\
$k - 28 = 0.2533 \times 0.4316$ \\
$k - 28 = 0.10932$ \\
Add 28: \\
$k = 28.109$ \\
$k = 28.11$ to 2 decimal places \\
(b) Each bottle is between 27.29 ml and $k$ ml with probability 0.55 \\
Let $Y$ be the number of these bottles in a sample of 200 \\
$Y$ follows $B(200, 0.55)$ \\
Mean: $np = 200 \times 0.55 = 110$ \\
Variance: $npq = 200 \times 0.55 \times 0.45 = 49.5$ \\
Normal approximation: $W$ follows $N(110, 49.5)$ \\
Fewer than half of 200 bottles means $Y < 100$, that is $Y \leq 99$ \\
Use a continuity correction: $P(Y \leq 99) \approx P(W < 99.5)$ \\
$\sqrt{49.5} = 7.0356$ \\
$z = \frac{99.5 - 110}{7.0356}$ \\
$z = -1.4924$ \\
$P(Z < -1.4924) = 0.0678$ \\
The probability is 0.0678 \\
(c) Hannah believes the mean is less than 28, so the test is one tailed \\
$H_{0}: \mu = 28$ \\
$H_{1}: \mu < 28$ \\
Under $H_{0}$, $D$ follows $N(28, 0.7^{2})$ and the sample mean of 20 bottles is: \\
$\text{D-bar}$ follows $N\left( 28, \frac{0.7^{2}}{20} \right)$ \\
Standard error: $\frac{0.7}{\sqrt{20}} = 0.15652$ \\
Find the probability of a sample mean of 27.72 or less: \\
$P(\text{D-bar} < 27.72)$ \\
$z = \frac{27.72 - 28}{0.15652}$ \\
$z = -1.7889$ \\
$P(Z < -1.7889) = 0.0368$ \\
The $p$-value is 0.0368 \\
$0.0368 < 0.05$, so the result is significant: reject $H_{0}$ \\
There is sufficient evidence, at the 5% level, to support Hannah's belief that the mean amount of liquid put in each bottle is less than 28 ml
