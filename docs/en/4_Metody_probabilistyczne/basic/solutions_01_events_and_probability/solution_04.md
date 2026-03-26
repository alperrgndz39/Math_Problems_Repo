# Task 4 — Weekly Weather Observation

Each day can be in exactly one of 3 states:

- \(S\) = Sunny
- \(C\) = Cloudy
- \(R\) = Rainy

Since the weather is observed day by day, each outcome is an **ordered sequence** of weather states.

---

## 1. Sample space for one day

For one day, the possible outcomes are:

\[
\Omega_1 = \{S, C, R\}
\]

### Number of elementary outcomes

\[
|\Omega_1| = 3
\]

---

## 2. Sample space for two consecutive days

For two days, the sample space consists of all ordered pairs of weather states:

\[
\Omega_2 = \{SS, SC, SR, CS, CC, CR, RS, RC, RR\}
\]

### Number of elementary outcomes

\[
|\Omega_2| = 3^2 = 9
\]

---

## 3. Sample space for seven consecutive days

For seven days, the sample space consists of all ordered sequences of length 7, where each position is one of \(S, C, R\):

\[
\Omega_7 = \{(x_1,x_2,x_3,x_4,x_5,x_6,x_7)\mid x_i \in \{S,C,R\}\}
\]

This means each day independently contributes one of the three possible weather states.

### Number of elementary outcomes

Since each of the 7 days has 3 possible states:

\[
|\Omega_7| = 3^7 = 2187
\]

---

## 4. Summary of the numbers of outcomes

- One day:

\[
|\Omega_1| = 3
\]

- Two consecutive days:

\[
|\Omega_2| = 9
\]

- Seven consecutive days:

\[
|\Omega_7| = 2187
\]

---

## 5. What does an elementary outcome represent in the weekly observation?

An **elementary outcome** is one complete ordered description of the weather over the observed period.

### Examples

- In \(\Omega_1\), an elementary outcome is one day's weather, such as:
  - \(S\)
  - \(C\)
  - \(R\)

- In \(\Omega_2\), an elementary outcome is a 2-day weather sequence, such as:
  - \(SR\): sunny on the first day, rainy on the second
  - \(CC\): cloudy on both days

- In \(\Omega_7\), an elementary outcome is a full 7-day weather pattern, such as:

\[
(S,C,R,R,S,S,C)
\]

This means:

- Day 1: Sunny
- Day 2: Cloudy
- Day 3: Rainy
- Day 4: Rainy
- Day 5: Sunny
- Day 6: Sunny
- Day 7: Cloudy

Because the days are observed in order, two sequences with the same weather states in different positions are treated as different outcomes.

---

## Final remark

The weekly weather experiment uses the model of an **ordered sequence with repetition**, because:

- there are 3 possible states each day,
- the same state may occur on multiple days,
- and the order of days matters.