Task 8 - Events and Probabilities in Card Drawing

## Problem

Refer to **Task 3**, where the sample spaces for drawing cards from a standard 52-card deck were defined.

Assume the deck is well-shuffled. In each experiment, every ordered sequence of draws is equally likely.

First assign probabilities to all elementary outcomes in the sample spaces $\Omega_1$, $\Omega_2$, and $\Omega_2'$.

Then describe the events as subsets of the sample space and compute their probabilities.

## Solution

### Elementary outcome probabilities

For one card drawn, each elementary outcome in $\Omega_1$ has probability

$$
\frac{1}{52}
$$

For two draws with replacement, each elementary outcome in $\Omega_2$ has probability

$$
\frac{1}{52^2} = \frac{1}{2704}
$$

For two draws without replacement, each elementary outcome in $\Omega_2'$ has probability

$$
\frac{1}{52 \cdot 51} = \frac{1}{2652}
$$

### One card drawn

#### Event $A_1$

There are 13 hearts, so

$$
A_1 = \{c \in \Omega_1 \mid c \text{ is a heart}\}
$$

Hence,

$$
P(A_1) = \frac{13}{52} = \frac{1}{4}
$$

#### Event $B_1$

There are 4 kings, so

$$
B_1 = \{c \in \Omega_1 \mid c \text{ is a king}\}
$$

Hence,

$$
P(B_1) = \frac{4}{52} = \frac{1}{13}
$$

#### Event $C_1$

Face cards are J, Q, K. There are

$$
3 \cdot 4 = 12
$$

face cards, so the number of non-face cards is

$$
52 - 12 = 40
$$

Hence,

$$
P(C_1) = \frac{40}{52} = \frac{10}{13}
$$

### Two cards drawn with replacement

#### Event $A_2$

The event "both cards are hearts" is

$$
A_2 = \{(c_1,c_2) \in \Omega_2 \mid c_1 \text{ and } c_2 \text{ are hearts}\}
$$

There are

$$
13 \cdot 13 = 169
$$

such ordered pairs. Hence,

$$
P(A_2) = \frac{169}{2704} = \frac{1}{16}
$$

#### Event $B_2$

The event "both cards have the same rank":

- choose the rank in 13 ways,
- choose a suit for the first card in 4 ways,
- choose a suit for the second card in 4 ways.

So the number of ordered pairs is

$$
13 \cdot 4 \cdot 4 = 208
$$

Hence,

$$
P(B_2) = \frac{208}{2704} = \frac{1}{13}
$$

#### Event $C_2$

The event "at least one ace" is easier by complement.

The probability that one draw is not an ace is

$$
\frac{48}{52} = \frac{12}{13}
$$

So the probability that neither card is an ace is

$$
\left(\frac{12}{13}\right)^2 = \frac{144}{169}
$$

Therefore,

$$
P(C_2) = 1 - \frac{144}{169} = \frac{25}{169}
$$

### Two cards drawn without replacement

#### Event $A_3$

The event "both cards are hearts":

- choose the first heart in 13 ways,
- choose the second heart in 12 ways.

So the number of ordered pairs is

$$
13 \cdot 12 = 156
$$

Hence,

$$
P(A_3) = \frac{156}{2652} = \frac{1}{17}
$$

#### Event $B_3$

The event "both cards have the same rank":

- choose the rank in 13 ways,
- choose the first suit in 4 ways,
- choose the second different suit in 3 ways.

So the number of ordered pairs is

$$
13 \cdot 4 \cdot 3 = 156
$$

Hence,

$$
P(B_3) = \frac{156}{2652} = \frac{1}{17}
$$

#### Event $C_3$

The event "one king and one queen in any order":

- first order: king then queen gives $4 \cdot 4 = 16$ outcomes,
- second order: queen then king gives $4 \cdot 4 = 16$ outcomes.

Total:

$$
16 + 16 = 32
$$

Hence,

$$
P(C_3) = \frac{32}{2652} = \frac{8}{663}
$$

### Additional event on $\Omega_2'$

Let $D_3$ be the event "both cards have the same suit".

- choose the suit in 4 ways,
- choose the first card in that suit in 13 ways,
- choose the second different card in that suit in 12 ways.

So the number of ordered pairs is

$$
4 \cdot 13 \cdot 12 = 624
$$

Hence,

$$
P(D_3) = \frac{624}{2652} = \frac{4}{17}
$$