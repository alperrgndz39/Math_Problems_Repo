# Task 7 — Events and Probabilities in Die Rolling

We refer to the sample spaces from Task 2.

Since the die is **fair**, all elementary outcomes are **equally likely**.

---

## 1. Probabilities of Elementary Outcomes

### Sample space \(\Omega_1\) — one roll

\[
\Omega_1=\{1,2,3,4,5,6\}
\]

There are:

\[
|\Omega_1|=6
\]

elementary outcomes, so for every \(\omega \in \Omega_1\),

\[
P(\{\omega\})=\frac{1}{6}
\]

---

### Sample space \(\Omega_2\) — two rolls

\[
\Omega_2=\{(i,j)\mid i,j\in\{1,2,3,4,5,6\}\}
\]

There are:

\[
|\Omega_2|=6^2=36
\]

elementary outcomes, so for every \((i,j)\in\Omega_2\),

\[
P(\{(i,j)\})=\frac{1}{36}
\]

---

### Sample space \(\Omega_3\) — three rolls

\[
\Omega_3=\{(i,j,k)\mid i,j,k\in\{1,2,3,4,5,6\}\}
\]

There are:

\[
|\Omega_3|=6^3=216
\]

elementary outcomes, so for every \((i,j,k)\in\Omega_3\),

\[
P(\{(i,j,k)\})=\frac{1}{216}
\]

---

# 2. One Die Roll

## Event \(A_1\) — the result is even

\[
A_1=\{2,4,6\}
\]

So:

\[
P(A_1)=\frac{3}{6}=\frac{1}{2}
\]

---

## Event \(B_1\) — the result is greater than 4

\[
B_1=\{5,6\}
\]

So:

\[
P(B_1)=\frac{2}{6}=\frac{1}{3}
\]

---

## Event \(C_1\) — the result is at most 3

\[
C_1=\{1,2,3\}
\]

So:

\[
P(C_1)=\frac{3}{6}=\frac{1}{2}
\]

---

# 3. Two Die Rolls

## Event \(A_2\) — the sum of the results equals 7

\[
A_2=\{(1,6),(2,5),(3,4),(4,3),(5,2),(6,1)\}
\]

There are 6 such outcomes, so:

\[
P(A_2)=\frac{6}{36}=\frac{1}{6}
\]

---

## Event \(B_2\) — both results are the same

\[
B_2=\{(1,1),(2,2),(3,3),(4,4),(5,5),(6,6)\}
\]

There are 6 such outcomes, so:

\[
P(B_2)=\frac{6}{36}=\frac{1}{6}
\]

---

## Event \(C_2\) — the sum of the results is at least 10

Possible sums are 10, 11, and 12.

### Sum = 10

\[
(4,6),(5,5),(6,4)
\]

### Sum = 11

\[
(5,6),(6,5)
\]

### Sum = 12

\[
(6,6)
\]

So:

\[
C_2=\{(4,6),(5,5),(6,4),(5,6),(6,5),(6,6)\}
\]

There are 6 outcomes, so:

\[
P(C_2)=\frac{6}{36}=\frac{1}{6}
\]

---

# 4. Three Die Rolls

## Event \(A_3\) — the sum of the results equals 10

We count all ordered triples \((i,j,k)\) with

\[
i+j+k=10
\]

where \(1\le i,j,k\le 6\).

The possible unordered patterns are:

- \(1,3,6\)
- \(1,4,5\)
- \(2,2,6\)
- \(2,3,5\)
- \(2,4,4\)
- \(3,3,4\)

Now count permutations of each:

- \(1,3,6\): \(3!=6\)
- \(1,4,5\): \(3!=6\)
- \(2,2,6\): \(\frac{3!}{2!}=3\)
- \(2,3,5\): \(3!=6\)
- \(2,4,4\): \(\frac{3!}{2!}=3\)
- \(3,3,4\): \(\frac{3!}{2!}=3\)

Total:

\[
6+6+3+6+3+3=27
\]

Therefore:

\[
P(A_3)=\frac{27}{216}=\frac{1}{8}
\]

---

## Event \(B_3\) — exactly two rolls give the same number

This means the pattern is:

- one value appears exactly twice,
- another different value appears once.

### Counting method

- choose the repeated value: \(6\) ways
- choose the different value: \(5\) ways
- choose the position of the different value: \(3\) ways

So the number of outcomes is:

\[
6\cdot 5\cdot 3=90
\]

Thus:

\[
P(B_3)=\frac{90}{216}=\frac{5}{12}
\]

---

## Event \(C_3\) — the outcomes contain two twos and one three (in any order)

The possible ordered triples are:

\[
C_3=\{(2,2,3),(2,3,2),(3,2,2)\}
\]

There are 3 outcomes, so:

\[
P(C_3)=\frac{3}{216}=\frac{1}{72}
\]

---

# 5. One Additional Event on \(\Omega_3\)

Define:

\[
D_3 = \{\text{at least one roll is a 6}\}
\]

We compute its probability using the complement.

The complementary event is:

\[
D_3^c=\{\text{no roll is a 6}\}
\]

For each roll, the probability of not getting a 6 is:

\[
\frac{5}{6}
\]

So:

\[
P(D_3^c)=\left(\frac{5}{6}\right)^3=\frac{125}{216}
\]

Hence:

\[
P(D_3)=1-\frac{125}{216}=\frac{91}{216}
\]

---

# Final Answers Summary

## Elementary outcome probabilities

- On \(\Omega_1\): each elementary outcome has probability  
\[
\frac{1}{6}
\]

- On \(\Omega_2\): each elementary outcome has probability  
\[
\frac{1}{36}
\]

- On \(\Omega_3\): each elementary outcome has probability  
\[
\frac{1}{216}
\]

---

## One roll

\[
P(A_1)=\frac{1}{2}
\]

\[
P(B_1)=\frac{1}{3}
\]

\[
P(C_1)=\frac{1}{2}
\]

---

## Two rolls

\[
P(A_2)=\frac{1}{6}
\]

\[
P(B_2)=\frac{1}{6}
\]

\[
P(C_2)=\frac{1}{6}
\]

---

## Three rolls

\[
P(A_3)=\frac{1}{8}
\]

\[
P(B_3)=\frac{5}{12}
\]

\[
P(C_3)=\frac{1}{72}
\]

---

## Additional event

For

\[
D_3=\{\text{at least one roll is a 6}\}
\]

we get

\[
P(D_3)=\frac{91}{216}
\]