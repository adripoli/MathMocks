@paper P31 Shadow October 2021

@q 1
@topic Sampling, binomial, ski club
@marks 7
@question
(a) Opportunity sampling uses whoever is available at the time \\
One disadvantage: it is not random, so the sample can be biased \\
(b) Each student is either in the ski club or not, with probability 0.12 each, and the students are independent \\
There is a fixed number of students, 42 \\
So a suitable model is a binomial distribution: $X$ follows $B(42, 0.12)$ \\
(i) $P(X = 8) = {}^{42}C_{8}(0.12)^{8}(0.88)^{34}$ \\
Use the binomial probability function on the calculator: \\
$P(X = 8) = 0.065744$ \\
$P(X = 8) = 0.0657$ to 3 significant figures \\
(ii) $P(X \geq 10) = 1 - P(X \leq 9)$ \\
From the cumulative binomial function: $P(X \leq 9) = 0.975662$ \\
$P(X \geq 10) = 1 - 0.975662$ \\
$P(X \geq 10) = 0.024338$ \\
$P(X \geq 10) = 0.0243$ to 3 significant figures \\
(c) 35% of the ski club members can snowboard \\
$P(\text{ski club and snowboard}) = P(\text{ski club}) \times P(\text{snowboard} | \text{ski club})$ \\
$= 0.12 \times 0.35$ \\
$= 0.042$ \\
(d) Let $T$ be the number of the 65 students who are in the ski club and can snowboard \\
Each student has probability 0.042, so $T$ follows $B(65, 0.042)$ \\
Fewer than 4 means $T \leq 3$ \\
$P(T \leq 3) = P(T = 0) + P(T = 1) + P(T = 2) + P(T = 3)$ \\
Use the cumulative binomial function on the calculator: \\
$P(T \leq 3) = 0.70880$ \\
$P(T \leq 3) = 0.709$ to 3 significant figures

@q 2
@topic Scatter diagram, correlation test
@marks 6
@question
(a) The points slope down from the top left to the bottom right \\
As $x$ goes up, $y$ goes down, so the correlation is negative \\
(b) Robert says that the warmer the weather, the fewer hot meals are sold \\
Warmer weather is a bigger $x$, fewer hot meals is a smaller $y$, which is negative correlation \\
So the diagram agrees with Robert's suggestion \\
(c) Enter the 12 pairs $(x, y)$ into the statistics mode of the calculator \\
Product moment correlation coefficient $r = -0.89983$ \\
$r = -0.900$ to 3 significant figures \\
(d) Robert is testing for negative correlation, so the test is one tailed \\
$H_{0}: \text{rho} = 0$ \\
$H_{1}: \text{rho} < 0$ \\
The sample size is $n = 12$ and the significance level is 5% \\
From the table of critical values (one tail, 5%, $n = 12$) the critical value is 0.4973 \\
For a negative correlation test the critical region is $r < -0.4973$ \\
The sample value is $r = -0.900$ \\
$-0.900 < -0.4973$, so the value is in the critical region \\
This is a significant result, so reject $H_{0}$ \\
There is evidence, at the 5% level, of a negative correlation between the number of hot meals sold and the temperature outside

@q 3
@topic Large data set, coding, mean, sd
@marks 8
@question
(a) In the large data set, the Daily Mean Temperature is recorded in degrees Celsius \\
So $x$ is in degrees C \\
(b) The coding is $y = x - 7$, so $x = y + 7$ \\
Mean of $y$: $\text{y-bar} = \frac{\sum y}{n}$ \\
$\text{y-bar} = \frac{199.5}{30}$ \\
$\text{y-bar} = 6.65$ \\
Mean of $x$: $\text{x-bar} = \text{y-bar} + 7$ \\
$\text{x-bar} = 6.65 + 7$ \\
$\text{x-bar} = 13.65$ degrees C \\
(c) Subtracting 7 from every value moves all the values by the same amount, so the spread does not change \\
So the standard deviation of $x$ equals the standard deviation of $y$ \\
$\sigma_{x} = \sigma_{y}$ \\
$\sigma_{y} = \sqrt{\frac{\sum y^{2}}{n} - \text{y-bar}^{2}}$ \\
$\frac{\sum y^{2}}{n} = \frac{5824.648}{30}$ \\
$= 194.15493$ \\
$\text{y-bar}^{2} = 6.65^{2}$ \\
$= 44.2225$ \\
$\sigma_{y} = \sqrt{194.15493 - 44.2225}$ \\
$\sigma_{y} = \sqrt{149.93243}$ \\
$\sigma_{y} = 12.2447$ \\
So the standard deviation of Daily Mean Temperature is 12.2 degrees C \\
(d) Daily mean pressure is measured on a scale and can take any value in a range \\
So it is a continuous variable

@q 4
@topic Venn diagram, three drinks
@marks 11
@question
(a) Exactly one drink means in only one circle: $T$ only, $M$ only or $C$ only \\
$0.07 + 0.18 + 0.05 = 0.30$ \\
The proportion is 0.3 \\
(b)(i) No person likes all three drinks, so the middle region has probability 0 \\
$r = 0$ \\
(ii) $T$ is made of four regions: $T$ only (0.07), $T$ and $M$ only (0.2), $T$ and $C$ only ($s$), and all three ($r$) \\
$P(T) = 0.07 + 0.2 + s + r = 0.41$ \\
$0.07 + 0.2 + s + 0 = 0.41$ \\
$0.27 + s = 0.41$ \\
Subtract 0.27: \\
$s = 0.14$ \\
(c)(i) $P(M | C) = \frac{P(M \text{ and } C)}{P(C)}$ \\
$M$ and $C$ is the regions $q$ and $r$, so $P(M \text{ and } C) = q + r = q$ \\
$C$ is the regions $s$, $r$, $q$ and $C$ only: $P(C) = 0.14 + 0 + q + 0.05 = q + 0.19$ \\
$\frac{q}{q + 0.19} = \frac{30}{49}$ \\
Cross multiply: \\
$49q = 30(q + 0.19)$ \\
Expand the bracket: \\
$49q = 30q + 5.7$ \\
Subtract $30q$: \\
$19q = 5.7$ \\
Divide by 19: \\
$q = 0.3$ \\
(ii) The probabilities of all the regions add up to 1: \\
$0.07 + 0.2 + 0.14 + 0 + 0.18 + 0.3 + 0.05 + p = 1$ \\
Add the numbers: $0.07 + 0.2 + 0.14 + 0.18 + 0.3 + 0.05 = 0.94$ \\
$0.94 + p = 1$ \\
Subtract 0.94: \\
$p = 0.06$ \\
(d) For events $A$ and $B$ to be independent, $P(A \text{ and } B) = P(A) \times P(B)$ \\
Here $A$ is ($T$ and $M'$) and $B$ is $C$ \\
$T$ and $M'$ means in $T$ but not in $M$: the regions $T$ only (0.07) and $T$ and $C$ only ($s$) \\
$P(T \text{ and } M') = 0.07 + 0.14 = 0.21$ \\
$P(C) = 0.14 + 0 + 0.3 + 0.05 = 0.49$ \\
$P(T \text{ and } M' \text{ and } C)$ is the region $s$ only: $0.14$ \\
Multiply the two probabilities: \\
$P(T \text{ and } M') \times P(C) = 0.21 \times 0.49$ \\
$= 0.1029$ \\
$0.1029 \ne 0.14$ \\
So $P(T \text{ and } M') \times P(C) \ne P(T \text{ and } M' \text{ and } C)$ \\
The events ($T$ and $M'$) and $C$ are not independent

@q 5
@topic Normal distribution, truncated, test
@marks 11
@question
(a) Let $F$ be the height, $F$ follows $N(180.5, 6.7^{2})$ \\
$P(F < k) = 0.01$ \\
The $z$ value with 1% below it is $-2.3263$ \\
Standardise: $\frac{k - 180.5}{6.7} = -2.3263$ \\
Multiply by 6.7: \\
$k - 180.5 = -15.5865$ \\
Add 180.5: \\
$k = 164.91$ \\
$k = 165$ cm to 3 significant figures \\
(b) $P(170 < F < 185) = P(F < 185) - P(F < 170)$ \\
Use the normal cumulative distribution on the calculator: \\
$P(F < 185) = 0.74909$ \\
$P(F < 170) = 0.05854$ \\
$P(170 < F < 185) = 0.74909 - 0.05854$ \\
$= 0.69056$ \\
The proportion is 0.691 \\
(c) We want $P(F > 177 | 170 < F < 185)$ \\
The condition 170 to 185 limits the range, so the height is between 177 and 185 \\
$P(F > 177 | 170 < F < 185) = \frac{P(177 < F < 185)}{P(170 < F < 185)}$ \\
$P(F < 177) = 0.30070$ \\
$P(177 < F < 185) = 0.74909 - 0.30070$ \\
$= 0.44839$ \\
$\frac{0.44839}{0.69056}$ \\
$= 0.64932$ \\
The probability is 0.649 \\
(d) Mia believes the mean is less than 180.5, so the test is one tailed \\
$H_{0}: \mu = 180.5$ \\
$H_{1}: \mu < 180.5$ \\
Let $X$ be the height of a male from the second country, with standard deviation 7.5 \\
Under $H_{0}$ the mean of a sample of 60 follows: \\
$\text{X-bar}$ follows $N\left( 180.5, \left( \frac{7.5}{\sqrt{60}} \right)^{2} \right)$ \\
Standard error: $\frac{7.5}{\sqrt{60}} = 0.96825$ \\
Find the probability of a sample mean of 178.8 or less: \\
$z = \frac{178.8 - 180.5}{0.96825}$ \\
$z = -1.7558$ \\
$P(\text{X-bar} < 178.8) = P(Z < -1.7558)$ \\
$= 0.0396$ \\
The $p$-value is 0.0396 \\
$0.0396 < 0.05$, so the result is significant: reject $H_{0}$ \\
There is evidence, at the 5% level, to support Mia's belief that the mean height of males from this country is less than 180.5 cm

@q 6
@topic Logs as probabilities, find a, b, c
@marks 7
@question
(a) The probabilities of a discrete random variable add up to 1: \\
$\log_{30} a + \log_{30} b + \log_{30} c = 1$ \\
Use the log law $\log x + \log y = \log xy$: \\
$\log_{30}(abc) = 1$ \\
Change from a log to a power: $abc = 30^{1}$ \\
$abc = 30$ \\
All the probabilities are greater than zero, so $\log_{30} a > 0$, which means $a > 1$ \\
The same holds for $b$ and $c$: $b > 1$ and $c > 1$ \\
So $a$, $b$, $c$ are integers greater than 1 whose product is 30 \\
Write 30 as a product of primes: $30 = 2 \times 3 \times 5$ \\
Three distinct integers greater than 1 that multiply to 30 must be 2, 3 and 5 \\
(Other factorisations like $1 \times 5 \times 6$ use 1, which is not allowed) \\
With $a < b < c$: \\
(i) $a = 2$ \\
(ii) $b = 3$ \\
(iii) $c = 5$ \\
(Check: $\log_{30} 2 + \log_{30} 3 + \log_{30} 5 = \log_{30} 30 = 1$) \\
(b) $X_{1} = X_{2}$ means both take the same value \\
$P(X_{1} = X_{2}) = P(X_{1} = 2)P(X_{2} = 2) + P(X_{1} = 3)P(X_{2} = 3) + P(X_{1} = 5)P(X_{2} = 5)$ \\
$= (\log_{30} 2)^{2} + (\log_{30} 3)^{2} + (\log_{30} 5)^{2}$ \\
$\log_{30} 2 = 0.20380$ and $0.20380^{2} = 0.04153$ \\
$\log_{30} 3 = 0.32301$ and $0.32301^{2} = 0.10433$ \\
$\log_{30} 5 = 0.47320$ and $0.47320^{2} = 0.22392$ \\
$P(X_{1} = X_{2}) = 0.04153 + 0.10433 + 0.22392$ \\
$= 0.36978$ \\
$P(X_{1} = X_{2}) = 0.370$ to 3 significant figures
