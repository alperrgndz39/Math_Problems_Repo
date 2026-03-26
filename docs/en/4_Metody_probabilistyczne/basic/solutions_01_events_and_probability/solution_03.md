 Task 3 - Drawing Cards

## Problem

Consider an experiment consisting of drawing cards from a **standard 52-card deck**.

The order of outcomes matters. Treat each outcome as an **ordered sequence** of drawn cards.

1. Define the sample space $\Omega_1$ for drawing one card.
2. Construct the sample space $\Omega_2$ for two consecutive draws with replacement.
3. Construct the sample space $\Omega_2'$ for two consecutive draws without replacement.
4. Determine the number of elementary outcomes in both cases.
5. Briefly describe what an elementary outcome represents in these experiments.

## Solution

Let $D$ denote the set of all 52 cards in the deck.

### One draw

The sample space is

$$
\Omega_1 = D
$$

The number of elementary outcomes is

$$
|\Omega_1| = 52
$$

### Two consecutive draws with replacement

Since the first card is returned to the deck, the second draw again has 52 possibilities.

The sample space is

$$
\Omega_2 = \{(c_1,c_2) \mid c_1,c_2 \in D\}
$$

The number of elementary outcomes is

$$
|\Omega_2| = 52 \cdot 52 = 2704
$$

### Two consecutive draws without replacement

Since the first card is not returned, the second card must be different from the first.

The sample space is

$$
\Omega_2' = \{(c_1,c_2) \mid c_1,c_2 \in D,\ c_1 \ne c_2\}
$$

The number of elementary outcomes is

$$
|\Omega_2'| = 52 \cdot 51 = 2652
$$

### Elementary outcome

An elementary outcome is one fully specified ordered sequence of drawn cards:

- in $\Omega_1$, one specific card,
- in $\Omega_2$, one ordered pair of cards with replacement allowed,
- in $\Omega_2'$, one ordered pair of distinct cards.
