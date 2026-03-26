Task 10 - Events and Probabilities in Buffon's Needle Experiment

## Problem

Refer to **Task 5**, where the sample space $\Omega$ of Buffon's needle experiment was defined.

A needle of length $L$ is thrown randomly onto a plane with equally spaced parallel lines. The distance between neighboring lines is $d$.

Assume $L \le d$. Let $X \in \left[0,\frac{d}{2}\right]$ be the distance from the needle's center to the nearest line and $\theta \in \left[0,\frac{\pi}{2}\right]$ the angle between the needle and the lines. Assume $X$ and $\theta$ are independent and uniformly distributed on these intervals.

Describe the following events and compute their probabilities.

## Solution

The sample space is

$$
\Omega = \left[0,\frac{d}{2}\right] \times \left[0,\frac{\pi}{2}\right]
$$

Since $X$ and $\theta$ are independent and uniform, probability is proportional to area in this rectangle.

The needle intersects a line exactly when the vertical reach of half the needle is at least the distance to the nearest line:

$$
X \le \frac{L}{2}\sin\theta
$$

### Event $A$

The event "the needle intersects one of the lines" is

$$
A = \left\{(x,\theta) \in \Omega \mid x \le \frac{L}{2}\sin\theta \right\}
$$

Its probability is

$$
P(A) = \frac{1}{\frac{d}{2}\cdot\frac{\pi}{2}} \int_0^{\frac{\pi}{2}} \frac{L}{2}\sin\theta \, d\theta
$$

Since

$$
\int_0^{\frac{\pi}{2}} \sin\theta \, d\theta = 1
$$

we obtain

$$
P(A) = \frac{1}{\frac{\pi d}{4}} \cdot \frac{L}{2} = \frac{2L}{\pi d}
$$

### Event $B$

The event "the needle does not intersect any line" is the complement of $A$:

$$
B = \Omega \setminus A
$$

Hence,

$$
P(B) = 1 - P(A) = 1 - \frac{2L}{\pi d}
$$

### Event $C$

The event "the angle is smaller than $\frac{\pi}{6}$" is

$$
C = \left\{(x,\theta) \in \Omega \mid 0 \le \theta < \frac{\pi}{6}\right\}
$$

Since $\theta$ is uniform on $\left[0,\frac{\pi}{2}\right]$,

$$
P(C) = \frac{\frac{\pi}{6}}{\frac{\pi}{2}} = \frac{1}{3}
$$

### Event $D$

The event "the center falls at a distance less than $\frac{d}{4}$ from the nearest line" is

$$
D = \left\{(x,\theta) \in \Omega \mid 0 \le x < \frac{d}{4}\right\}
$$

Since $X$ is uniform on $\left[0,\frac{d}{2}\right]$,

$$
P(D) = \frac{\frac{d}{4}}{\frac{d}{2}} = \frac{1}{2}
$$

### Event $E$

The event "the needle intersects a line and the angle is greater than $\frac{\pi}{4}$" is

$$
E = \left\{(x,\theta) \in \Omega \mid \theta > \frac{\pi}{4},\ x \le \frac{L}{2}\sin\theta \right\}
$$

Its probability is

$$
P(E) = \frac{1}{\frac{\pi d}{4}} \int_{\frac{\pi}{4}}^{\frac{\pi}{2}} \frac{L}{2}\sin\theta \, d\theta
$$

Now,

$$
\int_{\frac{\pi}{4}}^{\frac{\pi}{2}} \sin\theta \, d\theta
=
\left[-\cos\theta\right]_{\frac{\pi}{4}}^{\frac{\pi}{2}}
=
0 - \left(-\frac{\sqrt{2}}{2}\right)
=
\frac{\sqrt{2}}{2}
$$

Therefore,

$$
P(E) = \frac{1}{\frac{\pi d}{4}} \cdot \frac{L}{2} \cdot \frac{\sqrt{2}}{2}
= \frac{\sqrt{2}L}{\pi d}
$$

### Additional event

Let $F$ be the event "the angle is greater than $\frac{\pi}{3}$":

$$
F = \left\{(x,\theta) \in \Omega \mid \theta > \frac{\pi}{3}\right\}
$$

Since $\theta$ is uniform,

$$
P(F) = \frac{\frac{\pi}{2} - \frac{\pi}{3}}{\frac{\pi}{2}}
= \frac{\frac{\pi}{6}}{\frac{\pi}{2}}
= \frac{1}{3}
$$