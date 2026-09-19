# Pure 1 (June 2026): Solutions

## Question 1

(a) $y = 4f(2x)$: the $x$-coordinate halves and the $y$-coordinate is multiplied by 4, so $P \to (-2,\ 20)$

(b) $y = f(x+3) - 2$: shift left 3 and down 2, so $P \to (-7,\ 3)$

## Question 2

(a) $f(1.1) = e^{1.2} + 3.3 - 7 = -0.380$ and $f(1.2) = e^{1.4} + 3.6 - 7 = 0.655$

There is a change of sign and $f$ is continuous, so $\alpha \in [1.1, 1.2]$

(b)(i) $x_2 = \dfrac{1 + \ln(7 - 3.3)}{2} = \dfrac{1+\ln 3.7}{2} = 1.1542$

(b)(ii) Iterating: $x_3 = 1.1317,\ x_4 = 1.1411,\ x_5 = 1.1372,\ x_6 = 1.1389,\ x_7 = 1.1382,\ x_8 = 1.1385,\ \dots$

$\alpha = 1.1384$ (4 d.p.)

## Question 3

(a) $\dfrac{dy}{dx} = 3x^2 - 4x + 5$

(b) At $x = 2$: $y = 8 - 8 + 10 - 7 = 3$ and $\dfrac{dy}{dx} = 12 - 8 + 5 = 9$

$y - 3 = 9(x - 2) \Rightarrow y = 9x - 15$

## Question 4

(a) $f(x) \ge -2$

(b) $f(2) = 10$, so $gf(2) = g(10) = \dfrac{49}{6}$

(c) Let $y = \dfrac{5x-1}{x-4}$. Then $xy - 4y = 5x - 1$, so $x(y-5) = 4y - 1$ and $x = \dfrac{4y-1}{y-5}$

$g^{-1}(x) = \dfrac{4x-1}{x-5}, \quad x \ne 5$

## Question 5

(a) The maximum of $10\sin\left(\frac{t^2}{4}\right)$ is $10$ m

(b) $10\sin\left(\frac{t^2}{4}\right) = 5 \Rightarrow \sin\left(\frac{t^2}{4}\right) = \frac12 \Rightarrow \frac{t^2}{4} = \frac{\pi}{6},\ \frac{5\pi}{6}$

The second time is $\frac{t^2}{4} = \frac{5\pi}{6}$, giving $t^2 = \frac{10\pi}{3}$ and $t = \sqrt{\frac{10\pi}{3}}$

$x = 100\sqrt{t} = 100\left(\frac{10\pi}{3}\right)^{1/4} \approx 179.9$ m (about 180 m)

## Question 6

(a) $\displaystyle\int \frac{3}{7x+1}\,dx = \frac{3}{7}\ln|7x+1| + c$

(b) $\dfrac{3}{7}\left[\ln(7p+1) - \ln 15\right] = \dfrac{6}{7} \Rightarrow \ln\left(\dfrac{7p+1}{15}\right) = 2$

$7p + 1 = 15e^2 \Rightarrow p = \dfrac{15e^2 - 1}{7}$

## Question 7

(a) Area of $R_1 = \frac12 r^2(\theta - \sin\theta)$

Angle $AOB = \pi - \theta$, so area of $R_2 = \frac12 r^2\left(\pi - \theta - \sin(\pi - \theta)\right) = \frac12 r^2(\pi - \theta - \sin\theta)$

$R_1 = 2R_2$: $\ \theta - \sin\theta = 2\pi - 2\theta - 2\sin\theta$

$\sin\theta + 3\theta - 2\pi = 0$, so $p = 1,\ q = 3$

(b) $f(\theta) = \sin\theta + 3\theta - 2\pi$ and $f'(\theta) = \cos\theta + 3$

$f(1.3) = -1.41963$ and $f'(1.3) = 3.26750$

$\theta_2 = 1.3 - \dfrac{-1.41963}{3.26750} = 1.734$ (3 d.p.)

## Question 8

(a) $\displaystyle\int_0^3 x e^{2x}\,dx$

(b) By parts with $u = x$ and $v' = e^{2x}$:

$\displaystyle\int x e^{2x}\,dx = \frac{x}{2}e^{2x} - \int \frac12 e^{2x}\,dx = \frac{x}{2}e^{2x} - \frac14 e^{2x}$

$\displaystyle\left[\frac{x}{2}e^{2x} - \frac14 e^{2x}\right]_0^3 = \left(\frac32 e^6 - \frac14 e^6\right) - \left(0 - \frac14\right) = \frac54 e^6 + \frac14$

$A = \frac54,\ B = \frac14$

## Question 9

(a)
$$(\cos\theta + \sin\theta)\left(\frac{1}{\sin\theta} - \frac{1}{\cos\theta}\right) = \frac{(\cos\theta+\sin\theta)(\cos\theta - \sin\theta)}{\sin\theta\cos\theta} = \frac{\cos^2\theta - \sin^2\theta}{\sin\theta\cos\theta} = \frac{\cos 2\theta}{\frac12\sin 2\theta} = 2\cot 2\theta$$

$k = 2$

(b) $10\cot 2x = 4\,\text{cosec}^2 2x = 4(1 + \cot^2 2x)$

$4\cot^2 2x - 10\cot 2x + 4 = 0 \Rightarrow 2\cot^2 2x - 5\cot 2x + 2 = 0 \Rightarrow (2\cot 2x - 1)(\cot 2x - 2) = 0$

So $\tan 2x = 2$ or $\tan 2x = \frac12$, with $-180^\circ < 2x < 180^\circ$

$\tan 2x = 2$: $2x = 63.43^\circ, -116.57^\circ$ so $x = 31.7^\circ, -58.3^\circ$

$\tan 2x = \frac12$: $2x = 26.57^\circ, -153.43^\circ$ so $x = 13.3^\circ, -76.7^\circ$

$x = -76.7^\circ,\ -58.3^\circ,\ 13.3^\circ,\ 31.7^\circ$

## Question 10

(a) $y = 7x(3x^2+4)^{-1/2}$

$$\frac{dy}{dx} = 7(3x^2+4)^{-1/2} - 21x^2(3x^2+4)^{-3/2} = \frac{7(3x^2+4) - 21x^2}{(3x^2+4)^{3/2}} = \frac{28}{(3x^2+4)^{3/2}}$$

At $x = 2$: $y = \dfrac{14}{4} = \dfrac72$ and $\dfrac{dy}{dx} = \dfrac{28}{16^{3/2}} = \dfrac{28}{64} = \dfrac{7}{16}$

The normal gradient is $-\dfrac{16}{7}$, so $y - \dfrac72 = -\dfrac{16}{7}(x - 2)$

Multiplying by 14: $14y - 49 = -32x + 64$

$32x + 14y - 113 = 0$

(b) $x = 0 \Rightarrow y = \dfrac{113}{14}$

(c) Area under $l$ from $0$ to $2$ (trapezium): $\frac12 \times 2 \times \left(\frac{113}{14} + \frac{49}{14}\right) = \frac{81}{7}$

Area under $C$: $\displaystyle\int_0^2 \frac{7x}{\sqrt{3x^2+4}}\,dx = \left[\frac73\sqrt{3x^2+4}\right]_0^2 = \frac73(4 - 2) = \frac{14}{3}$

Area of $R = \dfrac{81}{7} - \dfrac{14}{3} = \dfrac{145}{21}$

## Question 11

(a) $R = \sqrt{4^2 + 13^2} = \sqrt{185}$ and $\tan\alpha = \dfrac{13}{4} \Rightarrow \alpha = 1.272$

$4\cos x - 13\sin x = \sqrt{185}\cos(x + 1.272)$

(b)(i) $D = 30 + \sqrt{185}\cos\left(\dfrac{\pi t}{12} + 0.2 + 1.2723\right)$

Minimum demand $= 30 - \sqrt{185} \approx 16.4$ GW

(b)(ii) The minimum occurs when $\dfrac{\pi t}{12} + 1.4723 = \pi$, so $t = \dfrac{12(\pi - 1.4723)}{\pi} = 6.376$

This is about 6:23 am

(c) $\dfrac{dD}{dt} = -\dfrac{\pi\sqrt{185}}{12}\sin\left(\dfrac{\pi t}{12} + 1.4723\right)$

At $t = 15$: $\dfrac{dD}{dt} = -\dfrac{\pi\sqrt{185}}{12}\sin(5.3993) = 2.75$

$k = 2.75$

(d) Demand varies throughout the year (e.g. more heating and lighting is used in winter than in summer, and weekends differ from weekdays), so one equation would not fit every day.

## Question 12

(a) Sketch description: a V-shaped graph lying on or above the $x$-axis, with its vertex touching the $x$-axis at $\left(\dfrac{q}{p}, 0\right)$. The left branch has gradient $-p$ and crosses the $y$-axis at $(0, q)$. The right branch has gradient $p$ and rises to the right.

(b) For $x < 0$, $\dfrac{k}{x} < 0 \le |px - q|$, so there are no intersections.

For $x > \dfrac{q}{p}$, $y = px - q$ is increasing from 0 and $\dfrac{k}{x}$ is decreasing and positive, so there is always exactly one intersection.

So there must be two distinct intersections for $0 < x < \dfrac{q}{p}$:

$\dfrac{k}{x} = q - px \Rightarrow px^2 - qx + k = 0$

Distinct roots need $q^2 - 4pk > 0$, so $k < \dfrac{q^2}{4p}$. The roots have sum $\dfrac{q}{p}$ and product $\dfrac{k}{p} > 0$, so both lie in $\left(0, \dfrac{q}{p}\right)$.

$0 < k < \dfrac{q^2}{4p}$

## Question 13

(a) For a geometric sequence, $u_4^2 = u_3 u_5$:

$2\cos^2\theta = \sin\theta \cdot \sqrt3\dfrac{\cos\theta}{\sin\theta} = \sqrt3\cos\theta$

Since $\cos\theta \ne 0$: $\cos\theta = \dfrac{\sqrt3}{2} \Rightarrow \theta = \dfrac{\pi}{6}$

Terms: $u_3 = \frac12$, $u_4 = \sqrt2 \cdot \frac{\sqrt3}{2} = \frac{\sqrt6}{2}$, $u_5 = \sqrt3 \cdot \sqrt3 = 3$

$r = \dfrac{\sqrt6/2}{1/2} = \sqrt6$

(b) $ar^2 = \frac12 \Rightarrow 6a = \frac12 \Rightarrow a = \frac{1}{12}$

$S_3 = a(1 + r + r^2) = \dfrac{1}{12}(1 + \sqrt6 + 6) = \dfrac{7 + \sqrt6}{12}$

## Question 14

(a) $\displaystyle\int \frac{1}{x}\,dx = \int (A - t)\,dt \Rightarrow \ln x = At - \frac{t^2}{2} + c$

$t = 0,\ x = 0.3$: $c = \ln 0.3$, so $x = 0.3\,e^{At - t^2/2}$

$t = 4,\ x = 21$: $e^{4A - 8} = 70 \Rightarrow A = 2 + \dfrac14\ln 70$

$x = 0.3\,e^{\left(2 + \frac14\ln 70\right)t - \frac12 t^2}$

(b) $\dfrac{dx}{dt} = 0$ when $t = A = 3.0621\ldots$

$x_{\max} = 0.3\,e^{A^2/2} = 0.3\,e^{4.6883} \approx 32.6$ mg L$^{-1}$

(c) $0.1 = 0.3\,e^{AT - T^2/2} \Rightarrow AT - \dfrac{T^2}{2} = \ln\dfrac13$

$T^2 - 2AT - 2\ln 3 = 0 \Rightarrow T = A + \sqrt{A^2 + 2\ln 3}$ (taking the positive root)

$T = 3.0621 + \sqrt{11.5738} \approx 6.46$

## Question 15

$a^2 + b^2 = (2m+1)^2 + (2n+1)^2 = 4m^2 + 4m + 4n^2 + 4n + 2 = 4(m^2 + m + n^2 + n) + 2$

This is even, so $c^2$ is even and hence $c$ is even. Let $c = 2k$, so $c^2 = 4k^2$.

Then $4k^2 = 4(m^2 + m + n^2 + n) + 2$, so $2k^2 = 2(m^2 + m + n^2 + n) + 1$

The left side is even and the right side is odd, which is a contradiction.

Hence $a$ and $b$ cannot both be odd.
