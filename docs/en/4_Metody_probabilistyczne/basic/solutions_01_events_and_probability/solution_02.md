# Task 2 — Rolling a Die

Since the order of outcomes matters, each elementary outcome is an **ordered sequence** of die results.

---

## 1. Sample space for one roll

For one roll of a fair six-sided die, the possible outcomes are:

\[
\Omega_1 = \{1,2,3,4,5,6\}
\]

### Number of elementary outcomes

\[
|\Omega_1| = 6
\]

---

## 2. Sample space for two consecutive rolls

For two rolls, the sample space consists of all ordered pairs \((a,b)\), where each entry is one of \(1,2,3,4,5,6\):

\[
\Omega_2 = \{
(1,1),(1,2),(1,3),(1,4),(1,5),(1,6),
\]
\[
(2,1),(2,2),(2,3),(2,4),(2,5),(2,6),
\]
\[
(3,1),(3,2),(3,3),(3,4),(3,5),(3,6),
\]
\[
(4,1),(4,2),(4,3),(4,4),(4,5),(4,6),
\]
\[
(5,1),(5,2),(5,3),(5,4),(5,5),(5,6),
\]
\[
(6,1),(6,2),(6,3),(6,4),(6,5),(6,6)
\}
\]

### Number of elementary outcomes

\[
|\Omega_2| = 6^2 = 36
\]

---

## 3. Sample space for three consecutive rolls

For three rolls, the sample space consists of all ordered triples \((a,b,c)\), where each entry is one of \(1,2,3,4,5,6\):

\[
\Omega_3 = \{(a,b,c)\mid a,b,c \in \{1,2,3,4,5,6\}\}
\]

Listing all 216 triples explicitly would be very long, so it is more convenient to describe the sample space in set-builder form.

Examples of elementary outcomes are:

\[
(1,1,1),\ (1,2,3),\ (4,6,2),\ (6,6,6)
\]

### Number of elementary outcomes

\[
|\Omega_3| = 6^3 = 216
\]

---

## 4. What does an elementary outcome represent?

An **elementary outcome** is one complete ordered description of the results of the experiment.

- In \(\Omega_1\), an elementary outcome is a single number, such as \(4\).
- In \(\Omega_2\), an elementary outcome is an ordered pair, such as \((2,5)\), meaning:
  - first roll = 2
  - second roll = 5
- In \(\Omega_3\), an elementary outcome is an ordered triple, such as \((6,1,3)\), meaning:
  - first roll = 6
  - second roll = 1
  - third roll = 3

Because order matters, outcomes like \((2,5)\) and \((5,2)\) are different.

---

## 5. Summary

\[
\Omega_1 = \{1,2,3,4,5,6\}, \qquad |\Omega_1|=6
\]

\[
|\Omega_2|=36
\]

\[
|\Omega_3|=216
\]

In general, for \(n\) consecutive rolls of a six-sided die:

\[
|\Omega_n| = 6^n
\]

because each roll has 6 possible outcomes.