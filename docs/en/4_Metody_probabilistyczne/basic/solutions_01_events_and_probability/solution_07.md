Task 7 - Events and Probabilities in Die Rolling

## Problem

Refer to **Task 2**, where the sample spaces for one, two, and three rolls of a fair six-sided die were defined.

Assume the die is fair, so all elementary outcomes are equally likely.

First assign probabilities to all elementary outcomes in the sample spaces $\Omega_1$, $\Omega_2$, and $\Omega_3$.

Then describe the events as subsets of the sample space and compute their probabilities.

## Solution

### Elementary outcome probabilities

For one roll, each elementary outcome in $\Omega_1$ has probability

$$
\frac{1}{6}
$$

For two rolls, each elementary outcome in $\Omega_2$ has probability

$$
\frac{1}{36}
$$

For three rolls, each elementary outcome in $\Omega_3$ has probability

$$
\frac{1}{216}
$$

### One die roll

#### Event $A_1$

The event "even result" is

$$
A_1 = \{2,4,6\}
$$

Therefore,

$$
P(A_1) = \frac{3}{6} = \frac{1}{2}
$$

#### Event $B_1$

The event "greater than 4" is

$$
B_1 = \{5,6\}
$$

Therefore,

$$
P(B_1) = \frac{2}{6} = \frac{1}{3}
$$

#### Event $C_1$

The event "at most 3" is

$$
C_1 = \{1,2,3\}
$$

Therefore,

$$
P(C_1) = \frac{3}{6} = \frac{1}{2}
$$

### Two die rolls

#### Event $A_2$

The event "sum equals 7" is

$$
A_2 = \{(1,6),(2,5),(3,4),(4,3),(5,2),(6,1)\}
$$

Therefore,

$$
P(A_2) = \frac{6}{36} = \frac{1}{6}
$$

#### Event $B_2$

The event "both results are the same" is

$$
B_2 = \{(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)\}
$$

Therefore,

$$
P(B_2) = \frac{6}{36} = \frac{1}{6}
$$

#### Event $C_2$

The event "sum is at least 10" includes sums 10, 11, and 12:

$$
C_2 = \{(4,6),(5,5),(6,4),(5,6),(6,5),(6,6)\}
$$

Therefore,

$$
P(C_2) = \frac{6}{36} = \frac{1}{6}
$$

### Three die rolls

#### Event $A_3$

We count ordered triples $(i,j,k)$ such that

$$
i+j+k = 10
$$

The positive integer solutions with each variable at most 6 give the following ordered outcomes:

$$
(1,3,6),(1,4,5),(1,5,4),(1,6,3),
$$

$$
(2,2,6),(2,3,5),(2,4,4),(2,5,3),(2,6,2),
$$

$$
(3,1,6),(3,2,5),(3,3,4),(3,4,3),(3,5,2),(3,6,1),
$$

$$
(4,1,5),(4,2,4),(4,3,3),(4,4,2),(4,5,1),
$$

$$
(5,1,4),(5,2,3),(5,3,2),(5,4,1),
$$

$$
(6,1,3),(6,2,2),(6,3,1)
$$

There are 27 such outcomes, so

$$
P(A_3) = \frac{27}{216} = \frac{1}{8}
$$

#### Event $B_3$

The event "exactly two rolls give the same number" means one pair and one different number.

Choose:

- the repeated value in 6 ways,
- the different value in 5 ways,
- the position of the different value in 3 ways.

So the number of outcomes is

$$
6 \cdot 5 \cdot 3 = 90
$$

Hence,

$$
P(B_3) = \frac{90}{216} = \frac{5}{12}
$$

#### Event $C_3$

The event "two twos and one three" is

$$
C_3 = \{(2,2,3),(2,3,2),(3,2,2)\}
$$

Therefore,

$$
P(C_3) = \frac{3}{216} = \frac{1}{72}
$$

### Additional event on $\Omega_3$

Let

$$
D_3 = \{(i,j,k) \in \Omega_3 \mid i,j,k \text{ are all even}\}
$$

Each roll must be one of $\{2,4,6\}$, so there are

$$
3^3 = 27
$$

such outcomes. Therefore,

$$
P(D_3) = \frac{27}{216} = \frac{1}{8}
$$

---
