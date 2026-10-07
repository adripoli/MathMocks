@paper P2 Proof Test 1

@q 1
@topic Prime sequence 2^k + 1, counter example
@marks 4
@question
The sequence is $a_{k} = 2^{k} + 1$, where $k \geq 1$. \\
(a) A prime number has exactly two factors: 1 and itself. \\
Put $k = 1$ into the formula: \\
$a_{1} = 2^{1} + 1$ \\
$= 2 + 1$ \\
$= 3$ \\
3 can only be divided by 1 and 3, so it is prime. \\
Put $k = 2$ into the formula: \\
$a_{2} = 2^{2} + 1$ \\
$= 4 + 1$ \\
$= 5$ \\
5 can only be divided by 1 and 5, so it is prime. \\
Put $k = 4$ into the formula: \\
$a_{4} = 2^{4} + 1$ \\
$= 16 + 1$ \\
$= 17$ \\
Test the primes up to the square root of 17, which is about 4.1. \\
These are 2 and 3. \\
$17 \div 2 = 8.5$, which is not a whole number \\
$17 \div 3 = 5.67$ (3 sf), which is not a whole number \\
So 17 has no factors other than 1 and 17, so it is prime. \\
So $a_{1}$, $a_{2}$ and $a_{4}$ all produce prime numbers. \\
(b) One value of $k$ that gives a non-prime is enough to disprove the claim. \\
Try $k = 3$, which is allowed since $k \geq 1$: \\
$a_{3} = 2^{3} + 1$ \\
$= 8 + 1$ \\
$= 9$ \\
Look for a factor other than 1 and 9: \\
$9 = 3 \times 3$ \\
So 9 has the factor 3 and is not prime. \\
This counter example shows that the sequence does not always produce a prime number.

@q 2
@topic Proof by exhaustion, sum of 1 to n
@marks 3
@question
Proof by exhaustion means checking every case in the stated range, one at a time. \\
Here the cases are $n = 1, 2, 3, 4, 5, 6$. \\
For each, work out the left-hand side by adding, and the right-hand side from the formula $\frac{n(n+1)}{2}$. \\
$n = 1$: \\
Left side: $1$ \\
Right side: $\frac{1 \times 2}{2}$ \\
$= \frac{2}{2}$ \\
$= 1$ \\
Both sides are 1, so it holds. \\
$n = 2$: \\
Left side: $1 + 2 = 3$ \\
Right side: $\frac{2 \times 3}{2}$ \\
$= \frac{6}{2}$ \\
$= 3$ \\
Both sides are 3, so it holds. \\
$n = 3$: \\
Left side: $1 + 2 + 3 = 6$ \\
Right side: $\frac{3 \times 4}{2}$ \\
$= \frac{12}{2}$ \\
$= 6$ \\
Both sides are 6, so it holds. \\
$n = 4$: \\
Left side: $1 + 2 + 3 + 4 = 10$ \\
Right side: $\frac{4 \times 5}{2}$ \\
$= \frac{20}{2}$ \\
$= 10$ \\
Both sides are 10, so it holds. \\
$n = 5$: \\
Left side: $1 + 2 + 3 + 4 + 5 = 15$ \\
Right side: $\frac{5 \times 6}{2}$ \\
$= \frac{30}{2}$ \\
$= 15$ \\
Both sides are 15, so it holds. \\
$n = 6$: \\
Left side: $1 + 2 + 3 + 4 + 5 + 6 = 21$ \\
Right side: $\frac{6 \times 7}{2}$ \\
$= \frac{42}{2}$ \\
$= 21$ \\
Both sides are 21, so it holds. \\
The two sides are equal for every value from 1 to 6. \\
So $1 + 2 + 3 + \ldots + n \equiv \frac{n(n+1)}{2}$ for positive integers from 1 to 6 inclusive.

@q 3
@topic Product of two odd numbers is odd
@marks 5
@question
Assume the opposite, so that we can look for a contradiction: \\
Suppose two odd numbers exist whose product is even. \\
Let the two odd numbers be $a$ and $b$. \\
An odd number is one more than an even number, and an even number is 2 times an integer. \\
So write $a = 2m + 1$ and $b = 2n + 1$, where $m$ and $n$ are integers. \\
Form the product: \\
$ab = (2m + 1)(2n + 1)$ \\
Expand, multiplying each term in the first bracket by each term in the second: \\
$ab = 2m \times 2n + 2m \times 1 + 1 \times 2n + 1 \times 1$ \\
Multiply out each term: \\
$ab = 4mn + 2m + 2n + 1$ \\
Take a factor of 2 out of the first three terms and leave the 1 alone: \\
$ab = 2(2mn + m + n) + 1$ \\
Let $k = 2mn + m + n$. \\
Sums and products of integers are integers, so $k$ is an integer. \\
Then: \\
$ab = 2k + 1$ \\
This is 2 times an integer, plus 1, so $ab$ is odd. \\
But we assumed that $ab$ is even. This is a contradiction. \\
So the assumption is false. \\
Therefore the product of two odd numbers is odd. \\
(Check: $a = 3$ and $b = 5$ give $m = 1$, $n = 2$ and $4(1)(2) + 2 + 4 + 1 = 15 = 3 \times 5$.)

@q 4
@topic If n is odd then n cubed plus 1 is even
@marks 5
@question
Assume the opposite, so that we can look for a contradiction: \\
Suppose $n$ is odd and $n^{3} + 1$ is odd. \\
Since $n$ is odd, write $n = 2m + 1$, where $m$ is an integer. \\
Cube it: \\
$n^{3} = (2m + 1)^{3}$ \\
Write the cube as a square times a bracket: \\
$n^{3} = (2m + 1)^{2}(2m + 1)$ \\
Expand the square first: \\
$(2m + 1)^{2} = (2m + 1)(2m + 1)$ \\
$= 4m^{2} + 2m + 2m + 1$ \\
$= 4m^{2} + 4m + 1$ \\
Now multiply by the remaining bracket: \\
$n^{3} = (4m^{2} + 4m + 1)(2m + 1)$ \\
Multiply each term of the first bracket by $2m$ and then by 1. \\
Times $2m$: $4m^{2} \times 2m = 8m^{3}$ \\
Times $2m$: $4m \times 2m = 8m^{2}$ \\
Times $2m$: $1 \times 2m = 2m$ \\
Times 1: $4m^{2} + 4m + 1$ \\
Add these four results together: \\
$n^{3} = 8m^{3} + 8m^{2} + 2m + 4m^{2} + 4m + 1$ \\
Collect the like terms: \\
$8m^{2} + 4m^{2} = 12m^{2}$ and $2m + 4m = 6m$ \\
$n^{3} = 8m^{3} + 12m^{2} + 6m + 1$ \\
Now add 1 to get $n^{3} + 1$: \\
$n^{3} + 1 = 8m^{3} + 12m^{2} + 6m + 1 + 1$ \\
$= 8m^{3} + 12m^{2} + 6m + 2$ \\
Take out the common factor of 2: \\
$= 2(4m^{3} + 6m^{2} + 3m + 1)$ \\
Let $k = 4m^{3} + 6m^{2} + 3m + 1$. \\
$m$ is an integer, so $k$ is an integer. \\
Then: \\
$n^{3} + 1 = 2k$ \\
This is 2 times an integer, so $n^{3} + 1$ is even. \\
But we assumed that $n^{3} + 1$ is odd. This is a contradiction. \\
So the assumption is false. \\
Therefore if $n$ is odd, $n^{3} + 1$ is even. \\
(Check: $n = 3$ gives $m = 1$ and $2(4 + 6 + 3 + 1) = 28 = 3^{3} + 1$.)

@q 5
@topic No integers with 25a + 15b = 1
@marks 4
@question
Assume the opposite, so that we can look for a contradiction: \\
Suppose there are integers $a$ and $b$ such that: \\
$25a + 15b = 1$ \\
Both 25 and 15 are multiples of 5, so write each as 5 times something: \\
$25a + 15b = 5 \times 5a + 5 \times 3b$ \\
Take out the common factor of 5: \\
$25a + 15b = 5(5a + 3b)$ \\
So the equation becomes: \\
$5(5a + 3b) = 1$ \\
Let $k = 5a + 3b$. \\
$a$ and $b$ are integers, so $k$ is an integer. \\
Then: \\
$5k = 1$ \\
Divide both sides by 5: \\
$k = \frac{1}{5}$ \\
But $k$ is an integer and $\frac{1}{5}$ is not an integer. This is a contradiction. \\
So the assumption is false. \\
Therefore there are no integers $a$ and $b$ such that $25a + 15b = 1$.

@q 6
@topic No greatest positive rational number
@marks 4
@question
Assume the opposite, so that we can look for a contradiction: \\
Suppose there is a greatest positive rational number. Call it $x$. \\
A rational number is a fraction of two integers. \\
$x$ is positive, so write: \\
$x = \frac{p}{q}$ \\
where $p$ and $q$ are positive integers. \\
Now make a new number $y$ by adding 1 to $x$: \\
$y = x + 1$ \\
Replace $x$ by $\frac{p}{q}$: \\
$y = \frac{p}{q} + 1$ \\
Write 1 as $\frac{q}{q}$ to get a common denominator: \\
$y = \frac{p}{q} + \frac{q}{q}$ \\
Add the fractions: \\
$y = \frac{p + q}{q}$ \\
$p + q$ is a positive integer and $q$ is a positive integer. \\
So $y$ is a fraction of two positive integers. \\
That means $y$ is a positive rational number. \\
Subtract $x$ from both sides of $y = x + 1$: \\
$y - x = 1$ \\
$1 > 0$, so $y > x$. \\
So $y$ is a positive rational number that is greater than $x$. \\
But $x$ was supposed to be the greatest. This is a contradiction. \\
So the assumption is false. \\
Therefore there is no greatest positive rational number.

@q 7
@topic Rational minus irrational is irrational
@marks 4
@question
Assume the opposite, so that we can look for a contradiction: \\
Suppose $a - b$ is rational. \\
$a$ is rational, so write: \\
$a = \frac{p}{q}$ \\
where $p$ and $q$ are integers and $q \ne 0$. \\
$a - b$ is rational, so write: \\
$a - b = \frac{r}{s}$ \\
where $r$ and $s$ are integers and $s \ne 0$. \\
Replace $a$ by $\frac{p}{q}$: \\
$\frac{p}{q} - b = \frac{r}{s}$ \\
Add $b$ to both sides: \\
$\frac{p}{q} = \frac{r}{s} + b$ \\
Subtract $\frac{r}{s}$ from both sides: \\
$\frac{p}{q} - \frac{r}{s} = b$ \\
So: \\
$b = \frac{p}{q} - \frac{r}{s}$ \\
Write both fractions over the common denominator $qs$: \\
$b = \frac{ps}{qs} - \frac{rq}{qs}$ \\
Subtract the numerators: \\
$b = \frac{ps - rq}{qs}$ \\
$p$, $q$, $r$ and $s$ are integers, so $ps - rq$ is an integer. \\
$qs$ is an integer, and $qs \ne 0$ because $q \ne 0$ and $s \ne 0$. \\
So $b$ is a fraction of two integers. That means $b$ is rational. \\
But $b$ is irrational. This is a contradiction. \\
So the assumption is false. \\
Therefore $a - b$ is irrational.

@q 8
@topic No positive integer solutions x^2-y^2=1
@marks 5
@question
Assume the opposite, so that we can look for a contradiction: \\
Suppose there are positive integers $x$ and $y$ such that: \\
$x^{2} - y^{2} = 1$ \\
Factorise the left side, using the difference of two squares: \\
$(x - y)(x + y) = 1$ \\
$x$ and $y$ are integers, so $x - y$ and $x + y$ are integers. \\
Two integers multiply to give 1 only if they are $1$ and $1$, or $-1$ and $-1$. \\
$x$ and $y$ are positive, so $x + y > 0$. \\
So $x + y$ cannot be $-1$, which rules out the second case. \\
Therefore: \\
$x + y = 1$ \\
$x - y = 1$ \\
Add the two equations: \\
$2x = 2$ \\
Divide both sides by 2: \\
$x = 1$ \\
Substitute $x = 1$ into $x + y = 1$: \\
$1 + y = 1$ \\
Subtract 1 from both sides: \\
$y = 0$ \\
But $y$ is a positive integer, and 0 is not positive. This is a contradiction. \\
So the assumption is false. \\
Therefore $x^{2} - y^{2} = 1$ has no positive integer solutions.

@q 9b
@topic Root 2 is irrational
@marks 6
@question
Assume the opposite, so that we can look for a contradiction: \\
Suppose $\sqrt{2}$ is rational. \\
Then: \\
$\sqrt{2} = \frac{p}{q}$ \\
where $p$ and $q$ are positive integers with no common factor. (The fraction is in its lowest terms.) \\
Square both sides: \\
$2 = \frac{p^{2}}{q^{2}}$ \\
Multiply both sides by $q^{2}$: \\
$p^{2} = 2q^{2}$ \\
$p^{2}$ is 2 times an integer, so $p^{2}$ is even. \\
Now show that $p$ must be even. \\
Suppose $p^{2}$ is even but $p$ is odd. \\
Write $p = 2m + 1$, where $m$ is an integer. \\
$p^{2} = (2m + 1)^{2}$ \\
Expand the bracket: \\
$p^{2} = 4m^{2} + 2m + 2m + 1$ \\
Collect the like terms: \\
$p^{2} = 4m^{2} + 4m + 1$ \\
Take a factor of 2 out of the first two terms: \\
$p^{2} = 2(2m^{2} + 2m) + 1$ \\
This is 2 times an integer, plus 1, so $p^{2}$ is odd. \\
That contradicts $p^{2}$ being even. \\
So if $p^{2}$ is even then $p$ is even. \\
Write $p = 2r$, where $r$ is an integer. \\
Substitute $p = 2r$ into $p^{2} = 2q^{2}$: \\
$(2r)^{2} = 2q^{2}$ \\
Square the bracket: \\
$4r^{2} = 2q^{2}$ \\
Divide both sides by 2: \\
$2r^{2} = q^{2}$ \\
$q^{2}$ is 2 times an integer, so $q^{2}$ is even. \\
By the same result as before, $q$ is even. \\
So $p$ and $q$ are both even. \\
That means 2 is a common factor of $p$ and $q$. \\
But $p$ and $q$ have no common factor. This is a contradiction. \\
So the assumption is false. \\
Therefore $\sqrt{2}$ is irrational.

@q 10
@topic Infinitely many primes
@marks 6
@question
Begin by assuming the opposite is true: \\
Assumption: there is a finite number of prime numbers. \\
Write down what this means by listing them all: \\
Let the prime numbers be $p_{1}, p_{2}, p_{3}, \ldots, p_{n}$ \\
Make a new number: one more than the product of all the primes. \\
Let $N = (p_{1} \times p_{2} \times p_{3} \times \ldots \times p_{n}) + 1$ \\
Now see whether any listed prime divides $N$. \\
Take any prime from the list, $p_{i}$. \\
The product of all the primes has $p_{i}$ as a factor, so: \\
$N = p_{i} \times (\text{product of the other primes}) + 1$ \\
So $N \div p_{i}$ leaves a remainder of 1. \\
This is true for every $p_{i}$ in the list. \\
So none of the primes in the list is a factor of $N$. \\
$N$ is bigger than 1, so there are two cases. \\
Case 1: $N$ is prime. \\
$N$ is bigger than the product of the primes. \\
So $N$ is bigger than every prime in the list. \\
So $N$ is a prime that is not in the list. \\
Case 2: $N$ is not prime. \\
Then $N$ has a prime factor. \\
That prime factor cannot be in the list, as none of them divide $N$. \\
So $N$ has a prime factor that is not in the list. \\
Either $N$ is prime or $N$ has a prime factor that is not listed. \\
Both cases give a prime that is not in our list. \\
But we said the list contained ALL the primes. \\
Either way, this is a contradiction. \\
So the assumption is false. \\
Therefore there is an infinite number of prime numbers.
