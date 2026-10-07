@paper P31 Shadow June 2024

@q 1
@topic Binomial spinner, approximation
@marks 11
@question
(a) The spinner is fair with 5 equal sections, so the probability of a 5 on each roll is $\frac{1}{5}$ \\
The rolls are independent and there are 12 of them, so $X$ follows $B\left( 12, \frac{1}{5} \right)$ \\
(i) $P(X = 4) = {}^{12}C_{4}\left( \frac{1}{5} \right)^{4}\left( \frac{4}{5} \right)^{8}$ \\
Use the binomial probability function on the calculator: \\
$P(X = 4) = 0.13288$ \\
$P(X = 4) = 0.133$ to 3 significant figures \\
(ii) $P(X < 4) = P(X \leq 3)$ \\
From the cumulative binomial function: \\
$P(X \leq 3) = 0.79457$ \\
$P(X < 4) = 0.795$ to 3 significant figures \\
(b) Let $D$ be the number of days (out of 50) when $X = 4$ \\
Each day independently has probability 0.133 of this, so $D$ follows $B(50, 0.133)$ \\
$P(D \geq 10) = 1 - P(D \leq 9)$ \\
From the cumulative binomial function: $P(D \leq 9) = 0.8797$ \\
$P(D \geq 10) = 1 - 0.8797$ \\
$P(D \geq 10) = 0.120$ \\
(c) 50 days with 12 rolls a day gives $50 \times 12 = 600$ rolls \\
Each roll is a 5 with probability 0.2 \\
Expected number of fives $= 600 \times 0.2$ \\
$= 120$ \\
(d) Let $S$ be the total number of fives in the 600 rolls, so $S$ follows $B(600, 0.2)$ \\
$n$ is large, so approximate with a normal distribution with the same mean and variance \\
Mean: $np = 120$ \\
Variance: $npq = 600 \times 0.2 \times 0.8 = 96$ \\
So $S$ is approximately $N(120, 96)$ \\
More than 135 means 136 or more, so use a continuity correction: \\
$P(S > 135) \approx P(T > 135.5)$ where $T$ follows $N(120, 96)$ \\
$\sqrt{96} = 9.7980$ \\
$z = \frac{135.5 - 120}{9.7980}$ \\
$z = 1.5820$ \\
$P(Z > 1.5820) = 0.05683$ \\
The probability is 0.0568 (0.057 to 2 significant figures)

@q 2
@topic Regression line, correlation test, model
@marks 6
@question
(a) The gradient of $h = 0.3t + 4.3$ is 0.3 \\
$h$ is in thousands of feet and $t$ is in minutes \\
So the height increases by 0.3 thousand feet, which is 300 feet, for each extra minute of the flight \\
(b) The test is for a positive correlation, so it is one tailed \\
$H_{0}: \text{rho} = 0$ \\
$H_{1}: \text{rho} > 0$ \\
The sample size is $n = 8$ and the significance level is 5% \\
From the table of critical values (one tail, 5%, $n = 8$) the critical value is 0.6215 \\
The critical region is $r > 0.6215$ \\
The sample value is $r = 0.548$ \\
$0.548 < 0.6215$, so the value is not in the critical region \\
Do not reject $H_{0}$ \\
There is insufficient evidence, at the 5% level, of a positive correlation between the height above the ground and the time \\
(c) The points on the scatter diagram fall from $t = 1$ to a lowest point at about $t = 4$ and then rise again \\
That is a curve (like a quadratic), not a straight line \\
So the straight regression line is not an appropriate model \\
(d) The curve $h = 0.2(t - k)^{2} + 4.3$ has its lowest point where $t = k$ \\
On the scatter diagram the lowest point is at about $t = 4$, so choose $k = 4$ \\
$h = 0.2(t - 4)^{2} + 4.3$ \\
(Any $k$ from 3.5 to 4.5 is a suitable choice)

@q 3
@topic Large data set, summary statistics
@marks 6
@question
(a) The incorrect variable has a mean of 1016 and a small standard deviation of 4.0 \\
Daily Mean Air Temperature is nowhere near 1016 \\
A value of about 1016 is typical of an air pressure in hPa (hectopascals) \\
So Colin selected Daily Mean Pressure \\
(b) Mean $= \frac{\sum x}{n}$ \\
$\text{x-bar} = \frac{4569.4}{184}$ \\
$\text{x-bar} = 24.834$ \\
$\text{x-bar} = 24.8$ degrees C to 3 significant figures \\
Standard deviation $\sigma = \sqrt{\frac{\sum x^{2}}{n} - \text{x-bar}^{2}}$ \\
$\frac{\sum x^{2}}{n} = \frac{114811.5}{184}$ \\
$= 623.976$ \\
$\text{x-bar}^{2} = 24.8337^{2}$ \\
$= 616.712$ \\
$\sigma = \sqrt{623.976 - 616.712}$ \\
$\sigma = \sqrt{7.263}$ \\
$\sigma = 2.695$ \\
$\sigma = 2.70$ degrees C to 3 significant figures \\
(c) The overall mean wind speed for May to October is 5.3 \\
One month had an average of 6.1, which is higher than 5.3 \\
Wind speeds are higher in the autumn and winter months, and October is the latest month in the data \\
So the data may have come from October

@q 4
@topic Two-tailed binomial test, left-handed
@marks 6
@question
(a) Rebecca believes the proportion is different from 20%, which could be higher or lower, so the test is two tailed \\
$H_{0}: p = 0.2$ \\
$H_{1}: p \ne 0.2$ \\
Let $X$ be the number of left-handed adults in the sample of 50 \\
Under $H_{0}$, $X$ follows $B(50, 0.2)$ \\
For a 5% two tailed test each tail has at most 0.025 \\
Lower tail: find the largest $c$ with $P(X \leq c) \leq 0.025$ \\
$P(X \leq 4) = 0.0185$, which is less than 0.025 \\
$P(X \leq 5) = 0.0480$, which is more than 0.025 \\
So the lower critical value is 4 \\
Upper tail: find the smallest $d$ with $P(X \geq d) \leq 0.025$ \\
$P(X \geq 17) = 1 - P(X \leq 16) = 1 - 0.9856 = 0.0144$, which is less than 0.025 \\
$P(X \geq 16) = 1 - P(X \leq 15) = 1 - 0.9692 = 0.0308$, which is more than 0.025 \\
So the upper critical value is 17 \\
The critical region is $X \leq 4$ or $X \geq 17$ \\
The probability in the lower tail is 0.0185 \\
The probability in the upper tail is 0.0144 \\
(b) The actual significance level is the total probability of the critical region: \\
$0.0185 + 0.0144$ \\
$= 0.0329$ \\
So the actual significance level is 3.29% \\
(c) Rebecca's sample has 8 left-handed adults \\
8 is not in the critical region ($X \leq 4$ or $X \geq 17$) \\
So do not reject $H_{0}$: there is insufficient evidence to support Rebecca's belief that the proportion of left-handed adults over 60 is different from 20%

@q 5
@topic Normal distributions, independence, solve
@marks 10
@question
(a) $R$ follows $N(19, 2.1^{2})$ \\
Standardise 18: $z = \frac{18 - 19}{2.1}$ \\
$z = -0.4762$ \\
$P(R < 18) = P(Z < -0.4762)$ \\
$= 0.3170$ \\
The proportion is 0.317 \\
(b) To multiply the two probabilities, the events must be independent \\
So the necessary assumption is that $R$ and $Q$ are independent: the 5km run time does not depend on the 50km cycle time for an athlete \\
(c) Cycling 50km in less than 1.5 hours means less than $1.5 \times 60 = 90$ minutes \\
$Q$ follows $N(96, 8^{2})$ \\
$z = \frac{90 - 96}{8}$ \\
$z = -0.75$ \\
$P(Q < 90) = P(Z < -0.75)$ \\
$= 0.2266$ \\
The two events are independent, so multiply: \\
$P(R < 18 \text{ and } Q < 90) = 0.3170 \times 0.2266$ \\
$= 0.07183$ \\
The Captain's estimate is 0.0718 \\
(d) $T$ follows $N(\mu, \sigma^{2})$ \\
$P(T < 28.5) = 0.2$: the $z$ value with 20% below it is $-0.8416$ \\
Equation 1: $\frac{28.5 - \mu}{\sigma} = -0.8416$ \\
$P(T > 31.8) = 0.15$: so $P(T < 31.8) = 0.85$, and the $z$ value with 85% below it is $1.0364$ \\
Equation 2: $\frac{31.8 - \mu}{\sigma} = 1.0364$ \\
Multiply each equation by $\sigma$: \\
$28.5 - \mu = -0.8416\sigma$ \\
$31.8 - \mu = 1.0364\sigma$ \\
Subtract the first from the second: \\
$(31.8 - \mu) - (28.5 - \mu) = 1.0364\sigma - (-0.8416\sigma)$ \\
$3.3 = 1.8780\sigma$ \\
Divide by 1.8780: \\
$\sigma = 1.7572$ \\
$\sigma = 1.76$ to 3 significant figures \\
Put into $28.5 - \mu = -0.8416\sigma$: \\
$28.5 - \mu = -0.8416 \times 1.7572$ \\
$28.5 - \mu = -1.4789$ \\
Add $\mu$ and add 1.4789 to both sides: \\
$\mu = 28.5 + 1.4789$ \\
$\mu = 29.979$ \\
$\mu = 30.0$ to 3 significant figures

@q 6
@topic Venn diagram with four events
@marks 11
@question
(a) Mutually exclusive events cannot happen together, so their regions do not overlap \\
$A$ and $C$ do not overlap, so $A$ and $C$ are mutually exclusive \\
(Other pairs: $C$ and $D$, or $B$ and $D$) \\
(b) $A$ and $B$ are independent, so $P(A \text{ and } B) = P(A) \times P(B)$ \\
$P(A \text{ and } B) = 0.12$ \\
$P(B)$ is made up of $A$ with $B$ (0.12), $B$ only (0.09) and $B$ with $C$ (0.04): \\
$P(B) = 0.12 + 0.09 + 0.04 = 0.25$ \\
$P(A)$ is made up of $A$ only (0.27), $D$ ($q$) and $A$ with $B$ (0.12): \\
$P(A) = 0.27 + q + 0.12 = q + 0.39$ \\
$0.12 = (q + 0.39) \times 0.25$ \\
Divide by 0.25: \\
$0.48 = q + 0.39$ \\
Subtract 0.39: \\
$q = 0.09$ \\
(c) $P(C | B') = \frac{P(C \text{ and } B')}{P(B')}$ \\
$C$ and $B'$ is the part of $C$ not in $B$, which is $C$ only: $p$ \\
$P(B') = 1 - 0.25 = 0.75$ \\
$P(C | B') = \frac{p}{0.75}$ \\
The probabilities add up to 1, so find $p + r$: \\
$0.27 + 0.09 + 0.12 + 0.09 + 0.04 + p + r = 1$ \\
The known values add to: $0.27 + 0.09 + 0.12 + 0.09 + 0.04 = 0.61$ \\
$p + r = 1 - 0.61$ \\
$p + r = 0.39$ \\
$r$ is a probability, so $r \geq 0$, and so $p \leq 0.39$ \\
The greatest value of $p$ is 0.39, when $r = 0$ \\
Greatest $P(C | B') = \frac{0.39}{0.75}$ \\
$= 0.52$ \\
(d) $P(B | C) = \frac{P(B \text{ and } C)}{P(C)}$ \\
$P(B \text{ and } C) = 0.04$ \\
$P(C) = 0.04 + p$ \\
$\frac{0.04}{0.04 + p} = 0.25$ \\
Multiply both sides by $(0.04 + p)$: \\
$0.04 = 0.25(0.04 + p)$ \\
Divide by 0.25: \\
$0.16 = 0.04 + p$ \\
Subtract 0.04: \\
$p = 0.12$ \\
Use $p + r = 0.39$: \\
$0.12 + r = 0.39$ \\
$r = 0.27$ \\
(e) $[B \text{ or } C]'$ and $A$ is in $A$ but not in $B$ or $C$: the regions $A$ only (0.27) and $D$ (0.09) \\
$P = 0.27 + 0.09$ \\
$= 0.36$ \\
(f) We want an event without $D$ whose probability is $P(D) = q = 0.09$ \\
The region $B$ only has probability 0.09 \\
$B$ only means in $B$ but not in $A$ and not in $C$ \\
So the event is $B$ and $A'$ and $C'$ \\
(Equivalently, $B$ and $[A \text{ or } C]'$)
