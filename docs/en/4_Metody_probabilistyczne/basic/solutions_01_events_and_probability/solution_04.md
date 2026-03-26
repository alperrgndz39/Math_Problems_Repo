Task 4 - Weekly Weather Observation

## Problem

The weather on a given day can be classified into exactly one of the following states:

- Sunny ($S$)
- Cloudy ($C$)
- Rainy ($R$)

The weather is observed once per day for seven consecutive days.

1. Define the sample space $\Omega_1$ for the weather observed on one day.
2. Construct the sample space $\Omega_2$ for two consecutive days.
3. Define the sample space $\Omega_7$ describing the weather observed during seven consecutive days.
4. Determine the number of elementary outcomes in each sample space.
5. Briefly describe what an elementary outcome represents in the case of a weekly observation.

## Solution

### One day

The sample space is

$$
\Omega_1 = \{S,C,R\}
$$

The number of elementary outcomes is

$$
|\Omega_1| = 3
$$

### Two consecutive days

The sample space is the set of all ordered pairs:

$$
\Omega_2 = \{(x_1,x_2) \mid x_1,x_2 \in \{S,C,R\}\}
$$

The number of elementary outcomes is

$$
|\Omega_2| = 3^2 = 9
$$

### Seven consecutive days

The sample space is the set of all ordered 7-tuples:

$$
\Omega_7 = \{(x_1,x_2,x_3,x_4,x_5,x_6,x_7) \mid x_i \in \{S,C,R\} \text{ for all } i\}
$$

The number of elementary outcomes is

$$
|\Omega_7| = 3^7 = 2187
$$

### Elementary outcome

An elementary outcome in the weekly observation is one fully specified sequence of weather states over seven consecutive days.

For example, $(S,C,R,R,S,S,C)$ is one elementary outcome.
