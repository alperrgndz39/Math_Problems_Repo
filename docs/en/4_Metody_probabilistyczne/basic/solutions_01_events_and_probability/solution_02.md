# Task 2 - Rolling a Die

## Problem

Consider an experiment consisting of rolling a **fair six-sided die**.

The order of outcomes matters.

1. Define the sample space $\Omega_1$ for one roll of the die.
2. Construct the sample space $\Omega_2$ for two consecutive rolls.
3. Construct the sample space $\Omega_3$ for three consecutive rolls.
4. Determine the number of elementary outcomes in each sample space.
5. Briefly describe what an elementary outcome represents in this experiment.

## Solution

### One roll

The sample space is

$$
\Omega_1 = \{1,2,3,4,5,6\}
$$

The number of elementary outcomes is

$$
|\Omega_1| = 6
$$

### Two consecutive rolls

The sample space is the set of all ordered pairs:

$$
\Omega_2 = \{(i,j) \mid i,j \in \{1,2,3,4,5,6\}\}
$$

The number of elementary outcomes is

$$
|\Omega_2| = 6 \cdot 6 = 36
$$

### Three consecutive rolls

The sample space is the set of all ordered triples:

$$
\Omega_3 = \{(i,j,k) \mid i,j,k \in \{1,2,3,4,5,6\}\}
$$

The number of elementary outcomes is

$$
|\Omega_3| = 6 \cdot 6 \cdot 6 = 216
$$

### Elementary outcome

An elementary outcome is one fully specified ordered result of the experiment:

- in $\Omega_1$, one number,
- in $\Omega_2$, one ordered pair,
- in $\Omega_3$, one ordered triple.
