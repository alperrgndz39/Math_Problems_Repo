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