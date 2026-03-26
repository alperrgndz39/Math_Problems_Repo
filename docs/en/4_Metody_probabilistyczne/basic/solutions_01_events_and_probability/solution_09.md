Task 9 - Events and Probabilities in Weekly Weather Observation

## Problem

Refer to **Task 4**, where the sample space $\Omega_7$ describing the weather during seven consecutive days was defined.

Each day can be in exactly one of the following states:

- Sunny ($S$)
- Cloudy ($C$)
- Rainy ($R$)

Model the weather as 7 independent days, where each of the three states occurs with probability $\frac{1}{3}$.

Describe the following events as subsets of $\Omega_7$ and compute their probabilities.

## Solution

Since each day is independent and each state has probability $\frac{1}{3}$, every specific 7-day sequence has probability

$$
\left(\frac{1}{3}\right)^7
$$

### Event $A$

The event "the entire weekend is sunny" means Saturday and Sunday are both $S$.

As a subset,

$$
A = \{(x_1,x_2,x_3,x_4,x_5,x_6,x_7) \in \Omega_7 \mid x_6 = S,\ x_7 = S\}
$$

The other 5 days are unrestricted. Therefore,

$$
P(A) = \frac{1}{3} \cdot \frac{1}{3} = \frac{1}{9}
$$

### Event $B$

The event "Wednesday, Thursday, and Friday are all rainy" means days 3, 4, and 5 are $R$.

As a subset,

$$
B = \{(x_1,\dots,x_7) \in \Omega_7 \mid x_3 = R,\ x_4 = R,\ x_5 = R\}
$$

Therefore,

$$
P(B) = \left(\frac{1}{3}\right)^3 = \frac{1}{27}
$$

### Event $C$

The event "at least one day is sunny" is the complement of "no day is sunny".

The probability that one day is not sunny is

$$
\frac{2}{3}
$$

So the probability that no day is sunny is

$$
\left(\frac{2}{3}\right)^7
$$

Therefore,

$$
P(C) = 1 - \left(\frac{2}{3}\right)^7 = 1 - \frac{128}{2187} = \frac{2059}{2187}
$$

### Event $D$

The event "no rainy day occurs" means each day is either $S$ or $C$.

For one day, that probability is

$$
\frac{2}{3}
$$

So for all 7 days,

$$
P(D) = \left(\frac{2}{3}\right)^7 = \frac{128}{2187}
$$

### Event $E$

The event "exactly two days are sunny":

- choose which 2 of the 7 days are sunny in $\binom{7}{2}$ ways,
- each chosen sunny day has probability $\frac{1}{3}$,
- each remaining non-sunny day has probability $\frac{2}{3}$.

Hence,

$$
P(E) = \binom{7}{2}\left(\frac{1}{3}\right)^2\left(\frac{2}{3}\right)^5
$$

Since

$$
\binom{7}{2} = 21
$$

we get

$$
P(E) = 21 \cdot \frac{1}{9} \cdot \frac{32}{243} = \frac{672}{2187}
$$

### Additional event on $\Omega_7$

Let $F$ be the event "all 7 days are different from the previous day", meaning no two consecutive days are equal.

- the first day can be chosen in 3 ways,
- each next day has 2 choices, because it must differ from the previous day.

So the number of valid sequences is

$$
3 \cdot 2^6
$$

Out of all

$$
3^7
$$

possible sequences, the probability is

$$
P(F) = \frac{3 \cdot 2^6}{3^7} = \frac{2^6}{3^6} = \frac{64}{729}
$$