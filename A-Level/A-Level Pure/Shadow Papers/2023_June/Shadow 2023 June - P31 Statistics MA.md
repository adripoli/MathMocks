@paper P31 Shadow June 2023

@q 1
@topic Venn diagram, independent events
@marks 6
@question
(a) $A$ is made up of two regions: $A$ only (0.11) and $A$ with $B$ (0.2) \\
$P(A) = 0.11 + 0.2$ \\
$P(A) = 0.31$ \\
(b) $B$ and $C$ are independent, so $P(B \text{ and } C) = P(B) \times P(C)$ \\
$P(B \text{ and } C) = 0.15$ \\
$P(B)$ is made up of $A$ with $B$ (0.2), $B$ only (0.25) and $B$ with $C$ (0.15): \\
$P(B) = 0.2 + 0.25 + 0.15 = 0.6$ \\
$P(C)$ is made up of $B$ with $C$ (0.15) and $C$ only ($p$): \\
$P(C) = 0.15 + p$ \\
$0.15 = 0.6 \times (0.15 + p)$ \\
Divide both sides by 0.6: \\
$0.25 = 0.15 + p$ \\
Subtract 0.15: \\
$p = 0.1$ \\
All the probabilities add up to 1: \\
$0.11 + 0.2 + 0.25 + 0.15 + p + q = 1$ \\
$0.11 + 0.2 + 0.25 + 0.15 + 0.1 = 0.81$ \\
$0.81 + q = 1$ \\
Subtract 0.81: \\
$q = 0.19$ \\
(c) $P(B | A') = \frac{P(B \text{ and } A')}{P(A')}$ \\
$B$ and $A'$ is the part of $B$ not in $A$: $B$ only (0.25) and $B$ with $C$ (0.15) \\
$P(B \text{ and } A') = 0.25 + 0.15 = 0.4$ \\
$P(A') = 1 - P(A) = 1 - 0.31 = 0.69$ \\
$P(B | A') = \frac{0.4}{0.69}$ \\
$= 0.5797$ \\
$P(B | A') = 0.580$ to 3 significant figures

@q 2
@topic Binomial, boxes of sweets, test
@marks 9
@question
(a) For a binomial model the trials must be independent and the probability must be constant \\
A condition in context: the prizes must be put in the packets independently of each other, at random (or: the probability that a packet contains a prize is the same, $\frac{1}{9}$, for every packet) \\
(b)(i) $T$ follows $B\left( 60, \frac{1}{9} \right)$ \\
$P(T = 4) = {}^{60}C_{4}\left( \frac{1}{9} \right)^{4}\left( \frac{8}{9} \right)^{56}$ \\
Use the binomial probability function on the calculator: \\
$P(T = 4) = 0.10153$ \\
$P(T = 4) = 0.102$ to 3 significant figures \\
(ii) Fewer than 6 means $T \leq 5$ \\
From the cumulative binomial function: \\
$P(T \leq 5) = 0.33150$ \\
$P(T < 6) = 0.331$ to 3 significant figures \\
(c) Let $K$ be the number of the 7 boxes that have fewer than 6 packets with a prize \\
Each box independently has probability 0.3315 of this \\
So $K$ follows $B(7, 0.3315)$ \\
$P(K = 3) = {}^{7}C_{3}(0.3315)^{3}(0.6685)^{4}$ \\
${}^{7}C_{3} = 35$ \\
$P(K = 3) = 0.25464$ \\
$P(K = 3) = 0.255$ to 3 significant figures \\
(Using 0.331 instead of 0.3315 gives 0.2542, which rounds the same) \\
(d) Vineet claims the proportion is less than $\frac{1}{9}$, so the test is one tailed \\
$H_{0}: p = \frac{1}{9}$ \\
$H_{1}: p < \frac{1}{9}$ \\
Let $X$ be the number of packets with a prize in a sample of 200 \\
Under $H_{0}$, $X$ follows $B\left( 200, \frac{1}{9} \right)$ \\
The sample has 17 prizes, so find $P(X \leq 17)$ \\
$P(X \leq 17) = 0.14276$ \\
$0.14276 > 0.10$, so the result is not significant: do not reject $H_{0}$ \\
There is insufficient evidence, at the 10% level, to support Vineet's claim that the proportion of packets containing a prize is less than $\frac{1}{9}$

@q 3
@topic Large data set, cleaning, mean, sd
@marks 7
@question
(a) The entry "tr" (trace) is not a number, so it cannot be put into a mean or standard deviation calculation \\
Replace "tr" with a number \\
A trace means a value between 0 and 0.05, so use a value in that range, for example 0.025 (or 0, or 0.05) \\
(b)(i) Mean $= \frac{\sum x}{n}$ \\
There are 184 values \\
$\text{x-bar} = \frac{423}{184}$ \\
$\text{x-bar} = 2.2989$ \\
$\text{x-bar} = 2.30$ mm to 3 significant figures \\
(ii) Standard deviation $\sigma = \sqrt{\frac{\sum x^{2}}{n} - \text{x-bar}^{2}}$ \\
$\frac{\sum x^{2}}{n} = \frac{4373}{184}$ \\
$= 23.7663$ \\
$\text{x-bar}^{2} = 2.2989^{2}$ \\
$= 5.2850$ \\
$\sigma = \sqrt{23.7663 - 5.2850}$ \\
$\sigma = \sqrt{18.4813}$ \\
$\sigma = 4.2990$ \\
$\sigma = 4.30$ mm to 3 significant figures \\
(c)(i) The large data set for Leuchars only covers May to October \\
So it is only half of the year, and so it is not a suitable sample for the whole of 1987 \\
(ii) The winter months (November to April) are missing, and winter is likely to have more rain \\
So the mean from May to October is likely to be smaller than the true annual mean: the estimate would be an underestimate

@q 4
@topic Normal distribution, two tailed test
@marks 6
@question
(a) Let $N$ be the height of a woman from region $A$, $N$ follows $N(155.2, 4.2^{2})$ \\
Standardise 158: $z = \frac{158 - 155.2}{4.2}$ \\
$z = 0.6667$ \\
$P(N > 158) = P(Z > 0.6667)$ \\
$= 0.2525$ \\
The proportion is 0.252 \\
(b) The claim is that the mean is different from region $A$, which could be higher or lower, so the test is two tailed \\
$H_{0}: \mu = 155.2$ \\
$H_{1}: \mu \ne 155.2$ \\
Let $S$ be the height of a woman from region $B$, with standard deviation 4.2 \\
Under $H_{0}$, the mean of a sample of 60 follows: \\
$\text{S-bar}$ follows $N\left( 155.2, \frac{4.2^{2}}{60} \right)$ \\
Variance: $\frac{4.2^{2}}{60} = 0.294$ \\
Standard error: $\frac{4.2}{\sqrt{60}} = 0.54222$ \\
The sample mean is 156.3, above 155.2, so find the upper tail: \\
$z = \frac{156.3 - 155.2}{0.54222}$ \\
$z = 2.0287$ \\
$P(\text{S-bar} > 156.3) = P(Z > 2.0287)$ \\
$= 0.02124$ \\
For a two tailed test at the 5% level, each tail has 2.5%, which is 0.025 \\
$0.02124 < 0.025$, so the result is significant: reject $H_{0}$ \\
There is sufficient evidence, at the 5% level, to support the claim that the mean height of adult women from region $B$ is different from region $A$ \\
(c) The $p$-value for a two tailed test is twice the one tail probability: \\
$p = 2 \times 0.02124$ \\
$p = 0.04249$ \\
$p = 0.0425$ (this is 4.2 percent)

@q 5
@topic Probability distribution, conditional
@marks 8
@question
(a) $P(S | \{X = x\}) = kx^{-1} = \frac{k}{x}$ \\
$P(S \text{ and } \{X = x\}) = P(S | \{X = x\}) \times P(X = x)$ \\
For $x = 70$: $P(S \text{ and } \{X = 70\}) = \frac{k}{70} \times c$ \\
For $x = 100$: $P(S \text{ and } \{X = 100\}) = \frac{k}{100} \times d$ \\
These are equal, as the question says this is the same for every value of $x$: \\
$\frac{k}{70}c = \frac{k}{100}d$ \\
Divide both sides by $k$: \\
$\frac{c}{70} = \frac{d}{100}$ \\
Multiply both sides by 100: \\
$d = \frac{100}{70}c$ \\
$d = \frac{10}{7}c$ as required \\
(b) Let the common value of $P(S \text{ and } \{X = x\})$ be $V$ \\
$\frac{k}{10}a = \frac{k}{40}b = \frac{k}{70}c = \frac{k}{100}d = V$ \\
Dividing each by $k$ and multiplying by the number: \\
$a = \frac{10V}{k}$ \\
$b = \frac{40V}{k}$ \\
$c = \frac{70V}{k}$ \\
$d = \frac{100V}{k}$ \\
Let $a = \frac{10V}{k}$; then $b = 4a$, $c = 7a$, $d = 10a$ \\
(Check: $d = \frac{10}{7}c = \frac{10}{7} \times 7a = 10a$) \\
The probabilities add up to 1: \\
$a + b + c + d = 1$ \\
$a + 4a + 7a + 10a = 1$ \\
$22a = 1$ \\
$a = \frac{1}{22}$ \\
$b = 4a = \frac{4}{22}$ \\
$c = 7a = \frac{7}{22}$ \\
$d = 10a = \frac{10}{22}$ \\
Table of values: $x$ = 10, 40, 70, 100 and $P(X = x)$ = $\frac{1}{22}$, $\frac{4}{22}$, $\frac{7}{22}$, $\frac{10}{22}$ \\
(c) Matt gets the ball in the cup 25% of the time from 70 cm \\
$P(S | \{X = 70\}) = 0.25$ \\
In the model $P(S | \{X = 70\}) = \frac{k}{70}$ \\
$\frac{k}{70} = 0.25$ \\
$k = 17.5$ \\
Now check $x = 10$: $P(S | \{X = 10\}) = \frac{k}{10} = \frac{17.5}{10} = 1.75$ \\
A probability cannot be more than 1 \\
So Elina's model does not work for Matt at $x = 10$ (and so not for all values of $X$)

@q 6
@topic Histogram, frequency curve, integration
@marks 14
@question
(a) Frequency $=$ frequency density $\times$ class width \\
$P(20 < T < 40)$ covers part of the bar from 14 to 24, and the bars from 24 to 32 and from 32 to 40 \\
Part of the bar 14 to 24: from 20 to 24 is width 4, height 2.1: $4 \times 2.1 = 8.4$ \\
Bar 24 to 32: width 8, height 2: $8 \times 2 = 16$ \\
Bar 32 to 40: width 8, height 1.75: $8 \times 1.75 = 14$ \\
Number of patients: $8.4 + 16 + 14 = 38.4$ \\
$P(20 < T < 40) = \frac{38.4}{100}$ \\
$= 0.384$ \\
(b) The histogram is not symmetric: it rises, peaks and then has a long tail to the right (it is positively skewed) \\
A normal distribution is symmetric about its mean \\
So Tim's model is not suitable \\
(c) Use integration by parts on $\int (x + 1)e^{-x+1} dx$ \\
Let $u = x + 1$ and $\frac{dv}{dx} = e^{-x+1}$ \\
$\frac{du}{dx} = 1$ \\
$v = -e^{-x+1}$ \\
$\int (x + 1)e^{-x+1} dx = -(x + 1)e^{-x+1} - \int (-e^{-x+1}) dx$ \\
$= -(x + 1)e^{-x+1} + \int e^{-x+1} dx$ \\
$= -(x + 1)e^{-x+1} - e^{-x+1}$ \\
Apply the limits 0 and $n$: \\
Upper limit $x = n$: $-(n + 1)e^{-n+1} - e^{-n+1}$ \\
Combine the two terms: $-(n + 1 + 1)e^{-n+1} = -(n + 2)e^{-n+1}$ \\
Lower limit $x = 0$: $-(1)e^{1} - e^{1} = -e - e = -2e$ \\
$\int_{0}^{n}(x + 1)e^{-x+1} dx = -(n + 2)e^{-n+1} - (-2e)$ \\
$= 2e - (n + 2)e^{-n+1}$ as required \\
(d) The area under Xi's curve is the total frequency, 100 patients, from $x = 0$ to $x = 8$ \\
$\int_{0}^{8} k(x + 1)e^{-x+1} dx = 100$ \\
Take out the constant $k$: \\
$k\int_{0}^{8}(x + 1)e^{-x+1} dx = 100$ \\
Use part (c) with $n = 8$: \\
$k\left[ 2e - (8 + 2)e^{-8+1} \right] = 100$ \\
$k\left[ 2e - 10e^{-7} \right] = 100$ \\
$2e = 5.43656$ \\
$10e^{-7} = 0.00912$ \\
$2e - 10e^{-7} = 5.42744$ \\
$k \times 5.42744 = 100$ \\
Divide by 5.42744: \\
$k = 18.4249$ \\
$k = 18$ to the nearest integer as required \\
(e)(i) Use $T$ follows $N(32.9, 19.8^{2})$ and the calculator: \\
$P(T < 40) = 0.64005$ \\
$P(T < 20) = 0.25736$ \\
$P(20 < T < 40) = 0.64005 - 0.25736$ \\
$= 0.38269$ \\
$P(20 < T < 40) = 0.383$ \\
(ii) The times 20 hours and 40 hours are $x = 2$ and $x = 4$ in tens of hours \\
The number of patients is the area under the curve from $x = 2$ to $x = 4$: \\
$18\int_{2}^{4}(x + 1)e^{-x+1} dx$ \\
Use the result of part (c) at $n = 4$ and at $n = 2$: \\
$n = 4$: $2e - 6e^{-3}$ \\
$n = 2$: $2e - 4e^{-1}$ \\
Subtract: $\left( 2e - 6e^{-3} \right) - \left( 2e - 4e^{-1} \right) = 4e^{-1} - 6e^{-3}$ \\
$4e^{-1} = 1.47152$ \\
$6e^{-3} = 0.29872$ \\
$4e^{-1} - 6e^{-3} = 1.17280$ \\
Number of patients $= 18 \times 1.17280$ \\
$= 21.110$ \\
Probability $= \frac{21.110}{100}$ \\
$= 0.2111$ \\
$P(20 < T < 40) = 0.211$ \\
(f) One limitation: the model only runs to 80 hours ($x = 8$), but some patients might stay longer than 80 hours
