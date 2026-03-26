# Task 6 – Events and Probabilities in Coin Tossing

## Problem Statement

Refer to Task 1, where the sample spaces for one, two, and three coin tosses were defined.

Assume the coin is fair, so all elementary outcomes are equally likely.

First assign probabilities to all elementary outcomes in the sample spaces:

- $\Omega_1$ for one toss,
- $\Omega_2$ for two tosses,
- $\Omega_3$ for three tosses.

Then describe the following events as subsets of the sample space and compute their probabilities.

For one coin toss:

- $A_1$ – the result is heads,
- $B_1$ – the result is tails,
- $C_1$ – the result is not tails.

For two coin tosses:

- $A_2$ – exactly one head occurs,
- $B_2$ – at least one head occurs,
- $C_2$ – both tosses give the same result.

For three coin tosses:

- $A_3$ – exactly two heads occur,
- $B_3$ – at least one tail occurs,
- $C_3$ – all three tosses give the same result.

Finally, define one additional event on $\Omega_3$ and compute its probability.

## Theory

For a fair coin, each elementary outcome has the same probability.

If a sample space $\Omega$ contains $n$ equally likely elementary outcomes, then each elementary outcome has probability

$$
\frac{1}{n}
$$

If an event $A$ is a subset of the sample space, then its probability is

$$
P(A) = \frac{|A|}{|\Omega|}
$$

where $|A|$ is the number of favorable outcomes and $|\Omega|$ is the total number of outcomes.

We use the notation:

- $H$ = heads,
- $T$ = tails.

## Step-by-Step Solution

### 1. Probabilities of elementary outcomes

For one toss, the sample space is

$$
\Omega_1 = \{H, T\}
$$

There are $2$ elementary outcomes, so each has probability

$$
P(H) = \frac{1}{2}, \qquad P(T) = \frac{1}{2}
$$

For two tosses, the sample space is

$$
\Omega_2 = \{HH, HT, TH, TT\}
$$

There are $4$ elementary outcomes, so each has probability

$$
P(HH) = P(HT) = P(TH) = P(TT) = \frac{1}{4}
$$

For three tosses, the sample space is

$$
\Omega_3 = \{HHH, HHT, HTH, HTT, THH, THT, TTH, TTT\}
$$

There are $8$ elementary outcomes, so each has probability

$$
P(HHH) = P(HHT) = P(HTH) = P(HTT) = P(THH) = P(THT) = P(TTH) = P(TTT) = \frac{1}{8}
$$

### 2. One coin toss

#### Event $A_1$ – the result is heads

The event is

$$
A_1 = \{H\}
$$

It contains $1$ favorable outcome out of $2$, so

$$
P(A_1) = \frac{1}{2}
$$

#### Event $B_1$ – the result is tails

The event is

$$
B_1 = \{T\}
$$

It contains $1$ favorable outcome out of $2$, so

$$
P(B_1) = \frac{1}{2}
$$

#### Event $C_1$ – the result is not tails

Not tails means heads, so

$$
C_1 = \{H\}
$$

Thus

$$
P(C_1) = \frac{1}{2}
$$

### 3. Two coin tosses

#### Event $A_2$ – exactly one head occurs

Exactly one head occurs in the outcomes $HT$ and $TH$, so

$$
A_2 = \{HT, TH\}
$$

This event has $2$ favorable outcomes out of $4$, hence

$$
P(A_2) = \frac{2}{4} = \frac{1}{2}
$$

#### Event $B_2$ – at least one head occurs

At least one head occurs in all outcomes except $TT$, so

$$
B_2 = \{HH, HT, TH\}
$$

This event has $3$ favorable outcomes out of $4$, hence

$$
P(B_2) = \frac{3}{4}
$$

#### Event $C_2$ – both tosses give the same result

The two tosses are the same in the outcomes $HH$ and $TT$, so

$$
C_2 = \{HH, TT\}
$$

This event has $2$ favorable outcomes out of $4$, hence

$$
P(C_2) = \frac{2}{4} = \frac{1}{2}
$$

### 4. Three coin tosses

#### Event $A_3$ – exactly two heads occur

Exactly two heads occur in the outcomes $HHT$, $HTH$, and $THH$, so

$$
A_3 = \{HHT, HTH, THH\}
$$

This event has $3$ favorable outcomes out of $8$, hence

$$
P(A_3) = \frac{3}{8}
$$

#### Event $B_3$ – at least one tail occurs

At least one tail occurs in every outcome except $HHH$, so

$$
B_3 = \{HHT, HTH, HTT, THH, THT, TTH, TTT\}
$$

This event has $7$ favorable outcomes out of $8$, hence

$$
P(B_3) = \frac{7}{8}
$$

#### Event $C_3$ – all three tosses give the same result

All three tosses are the same only in the outcomes $HHH$ and $TTT$, so

$$
C_3 = \{HHH, TTT\}
$$

This event has $2$ favorable outcomes out of $8$, hence

$$
P(C_3) = \frac{2}{8} = \frac{1}{4}
$$

### 5. One additional event on $\Omega_3$

Define an additional event $D_3$ as: exactly one head occurs.

Then

$$
D_3 = \{HTT, THT, TTH\}
$$

This event has $3$ favorable outcomes out of $8$, so

$$
P(D_3) = \frac{3}{8}
$$

## Final Result

The probabilities of all elementary outcomes are:

- in $\Omega_1$, each elementary outcome has probability $\frac{1}{2}$,
- in $\Omega_2$, each elementary outcome has probability $\frac{1}{4}$,
- in $\Omega_3$, each elementary outcome has probability $\frac{1}{8}$.

The required event probabilities are:

- $P(A_1) = \frac{1}{2}$,
- $P(B_1) = \frac{1}{2}$,
- $P(C_1) = \frac{1}{2}$,

- $P(A_2) = \frac{1}{2}$,
- $P(B_2) = \frac{3}{4}$,
- $P(C_2) = \frac{1}{2}$,

- $P(A_3) = \frac{3}{8}$,
- $P(B_3) = \frac{7}{8}$,
- $P(C_3) = \frac{1}{4}$,

and for the additional event:

- $P(D_3) = \frac{3}{8}$.

## Interpretation

This task shows how probabilities are computed when all elementary outcomes are equally likely.

The main idea is simple: first identify the sample space, then describe each event as a subset of that sample space, and finally count how many outcomes belong to the event.

For a fair coin, the probability of an event is always the number of favorable outcomes divided by the total number of possible outcomes.

# Task 7 – Events and Probabilities in Die Rolling

## Problem Statement

Refer to Task 2, where the sample spaces for one, two, and three rolls of a fair six-sided die were defined.

Assume the die is fair, so all elementary outcomes are equally likely.

First assign probabilities to all elementary outcomes in the sample spaces:

- $\Omega_1$ for one roll,
- $\Omega_2$ for two rolls,
- $\Omega_3$ for three rolls.

Then describe the following events as subsets of the sample space and compute their probabilities.

For one die roll:

- $A_1$ – the result is even,
- $B_1$ – the result is greater than $4$,
- $C_1$ – the result is at most $3$.

For two die rolls:

- $A_2$ – the sum of the results equals $7$,
- $B_2$ – both results are the same,
- $C_2$ – the sum of the results is at least $10$.

For three die rolls:

- $A_3$ – the sum of the results equals $10$,
- $B_3$ – exactly two rolls give the same number,
- $C_3$ – the outcomes contain two twos and one three, in any order.

Finally, define one additional event on $\Omega_3$ and compute its probability.

## Theory

For a fair six-sided die, each face from $1$ to $6$ has the same probability.

If a sample space $\Omega$ contains $n$ equally likely elementary outcomes, then each elementary outcome has probability

$$
\frac{1}{n}
$$

For any event $A \subseteq \Omega$, the probability is

$$
P(A) = \frac{|A|}{|\Omega|}
$$

We use ordered outcomes, which means that in two rolls, $(1,6)$ and $(6,1)$ are different elementary outcomes.

## Step-by-Step Solution

### 1. Probabilities of elementary outcomes

For one roll, the sample space is

$$
\Omega_1 = \{1,2,3,4,5,6\}
$$

There are $6$ elementary outcomes, so each has probability

$$
\frac{1}{6}
$$

For two rolls, the sample space is

$$
\Omega_2 = \{(i,j) \mid i,j \in \{1,2,3,4,5,6\}\}
$$

There are

$$
6 \cdot 6 = 36
$$

elementary outcomes, so each has probability

$$
\frac{1}{36}
$$

For three rolls, the sample space is

$$
\Omega_3 = \{(i,j,k) \mid i,j,k \in \{1,2,3,4,5,6\}\}
$$

There are

$$
6 \cdot 6 \cdot 6 = 216
$$

elementary outcomes, so each has probability

$$
\frac{1}{216}
$$

### 2. One die roll

#### Event $A_1$ – the result is even

The even outcomes are $2$, $4$, and $6$, so

$$
A_1 = \{2,4,6\}
$$

There are $3$ favorable outcomes out of $6$, hence

$$
P(A_1) = \frac{3}{6} = \frac{1}{2}
$$

#### Event $B_1$ – the result is greater than $4$

The outcomes greater than $4$ are $5$ and $6$, so

$$
B_1 = \{5,6\}
$$

There are $2$ favorable outcomes out of $6$, hence

$$
P(B_1) = \frac{2}{6} = \frac{1}{3}
$$

#### Event $C_1$ – the result is at most $3$

The outcomes at most $3$ are $1$, $2$, and $3$, so

$$
C_1 = \{1,2,3\}
$$

There are $3$ favorable outcomes out of $6$, hence

$$
P(C_1) = \frac{3}{6} = \frac{1}{2}
$$

### 3. Two die rolls

#### Event $A_2$ – the sum of the results equals $7$

The ordered pairs whose sum is $7$ are

$$
A_2 = \{(1,6),(2,5),(3,4),(4,3),(5,2),(6,1)\}
$$

There are $6$ favorable outcomes out of $36$, hence

$$
P(A_2) = \frac{6}{36} = \frac{1}{6}
$$

#### Event $B_2$ – both results are the same

The outcomes with equal results are

$$
B_2 = \{(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)\}
$$

There are $6$ favorable outcomes out of $36$, hence

$$
P(B_2) = \frac{6}{36} = \frac{1}{6}
$$

#### Event $C_2$ – the sum of the results is at least $10$

The possible sums are $10$, $11$, and $12$.

For sum $10$, the outcomes are

$$
(4,6),(5,5),(6,4)
$$

For sum $11$, the outcomes are

$$
(5,6),(6,5)
$$

For sum $12$, the outcome is

$$
(6,6)
$$

Therefore

$$
C_2 = \{(4,6),(5,5),(6,4),(5,6),(6,5),(6,6)\}
$$

There are $6$ favorable outcomes out of $36$, hence

$$
P(C_2) = \frac{6}{36} = \frac{1}{6}
$$

### 4. Three die rolls

#### Event $A_3$ – the sum of the results equals $10$

We count all ordered triples $(i,j,k)$ such that

$$
i + j + k = 10
$$

with $i,j,k \in \{1,2,3,4,5,6\}$.

The positive integer solutions not exceeding $6$ are:

- $(1,3,6)$ and all permutations,
- $(1,4,5)$ and all permutations,
- $(2,2,6)$ and all permutations,
- $(2,3,5)$ and all permutations,
- $(2,4,4)$ and all permutations,
- $(3,3,4)$ and all permutations.

Now count them carefully:

- $(1,3,6)$ gives $6$ permutations,
- $(1,4,5)$ gives $6$ permutations,
- $(2,2,6)$ gives $3$ permutations,
- $(2,3,5)$ gives $6$ permutations,
- $(2,4,4)$ gives $3$ permutations,
- $(3,3,4)$ gives $3$ permutations.

So the total number of favorable outcomes is

$$
6 + 6 + 3 + 6 + 3 + 3 = 27
$$

Hence

$$
P(A_3) = \frac{27}{216} = \frac{1}{8}
$$

#### Event $B_3$ – exactly two rolls give the same number

This means one number appears exactly twice and the third number is different.

We count such ordered triples in steps.

First choose the number that is repeated:

$$
6 \text{ choices}
$$

Then choose the different number:

$$
5 \text{ choices}
$$

Then choose the position of the different number in the triple:

$$
3 \text{ choices}
$$

Therefore the number of favorable outcomes is

$$
6 \cdot 5 \cdot 3 = 90
$$

Hence

$$
P(B_3) = \frac{90}{216} = \frac{5}{12}
$$

#### Event $C_3$ – the outcomes contain two twos and one three, in any order

The favorable ordered triples are

$$
C_3 = \{(2,2,3),(2,3,2),(3,2,2)\}
$$

There are $3$ favorable outcomes out of $216$, hence

$$
P(C_3) = \frac{3}{216} = \frac{1}{72}
$$

### 5. One additional event on $\Omega_3$

Define an additional event $D_3$ as: all three rolls are even.

The even numbers are $2$, $4$, and $6$.

For each of the three rolls, there are $3$ even choices, so the number of favorable outcomes is

$$
3 \cdot 3 \cdot 3 = 27
$$

Thus

$$
P(D_3) = \frac{27}{216} = \frac{1}{8}
$$

## Final Result

The probabilities of all elementary outcomes are:

- in $\Omega_1$, each elementary outcome has probability $\frac{1}{6}$,
- in $\Omega_2$, each elementary outcome has probability $\frac{1}{36}$,
- in $\Omega_3$, each elementary outcome has probability $\frac{1}{216}$.

The required event probabilities are:

- $P(A_1) = \frac{1}{2}$,
- $P(B_1) = \frac{1}{3}$,
- $P(C_1) = \frac{1}{2}$,

- $P(A_2) = \frac{1}{6}$,
- $P(B_2) = \frac{1}{6}$,
- $P(C_2) = \frac{1}{6}$,

- $P(A_3) = \frac{1}{8}$,
- $P(B_3) = \frac{5}{12}$,
- $P(C_3) = \frac{1}{72}$,

and for the additional event:

- $P(D_3) = \frac{1}{8}$.

## Interpretation

This task applies the same probability principle as in coin tossing, but now the sample spaces are larger.

For die rolling, the key point is that we work with ordered outcomes. That is why different orders such as $(2,2,3)$ and $(3,2,2)$ count as different elementary outcomes.

The probability of each event is obtained by counting favorable ordered outcomes and dividing by the total number of equally likely outcomes.
