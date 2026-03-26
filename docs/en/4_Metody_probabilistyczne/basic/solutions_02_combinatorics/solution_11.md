# Task 11 — Modeling Outcomes

## 1. Distinguishable vs Indistinguishable Objects

A box contains:

- 4 red balls
- 4 blue balls
- 3 green balls

So there are **11 balls** in total.

### (a) How many linear arrangements are possible if balls of the same color are treated as indistinguishable?

If balls of the same color are indistinguishable, then we only arrange the color pattern:

- 4 identical red balls
- 4 identical blue balls
- 3 identical green balls

So the number of distinct linear arrangements is

\[
\frac{11!}{4!\,4!\,3!}
\]

Now compute:

\[
11! = 39916800,\qquad 4! = 24,\qquad 3! = 6
\]

\[
\frac{39916800}{24\cdot24\cdot6}
=
\frac{39916800}{3456}
=
11550
\]

**Answer:** **11550**

---

### (b) How many arrangements are possible if every ball is individually labeled?

If every ball is labeled, then all 11 balls are distinct:

\[
R_1,R_2,R_3,R_4,B_1,B_2,B_3,B_4,G_1,G_2,G_3
\]

The number of linear arrangements of 11 distinct objects is

\[
11! = 39916800
\]

**Answer:** **39916800**

---

### (c) Why are the answers different?

The answers are different because in part (a), balls of the same color are treated as **identical**, so swapping two red balls does **not** create a new arrangement.

In part (b), every ball is **distinguishable**, so swapping \(R_1\) and \(R_2\) creates a different arrangement.

So:

- **indistinguishable objects** → use **permutations with repeated elements**
- **distinguishable objects** → use **ordinary permutations**

---

## 2. Recording Order vs Ignoring Order

Three balls are drawn **without replacement** from the same box.

The box has balls of 3 colors:

- red
- blue
- green

Since there are at least 3 balls of each color except green has exactly 3, every color pattern of length 3 that uses at most 3 greens is possible. Here all listed patterns are possible.

---

### (a) How many outcomes are possible if only the set of colors is recorded (order ignored)?

If order is ignored, then we only care about the **multiset of colors** drawn.

Possible unordered color outcomes:

1. RRR
2. BBB
3. GGG
4. RRB
5. RRG
6. BBR
7. BBG
8. GGR
9. GGB
10. RBG

So there are **10** possible outcomes.

**Answer:** **10**

---

### (b) How many outcomes are possible if the sequence of colors is recorded?

Now order matters, so each 3-position sequence counts separately.

Each draw can produce one of 3 colors, and each color has enough balls available for any 3-draw color sequence, so all sequences of length 3 are possible:

\[
3^3 = 27
\]

**Answer:** **27**

---

### (c) Why does recording the order change the counting model?

When order is ignored, outcomes like

- RBG
- RGB
- BRG

are all treated as the **same** result because they contain the same colors.

When order is recorded, these become **different** outcomes because the positions matter.

So:

- **order ignored** → unordered samples / combinations by type
- **order recorded** → sequences / ordered outcomes

---

## 3. PIN Code vs Number

A security system uses 4-digit PIN codes with digits from 0 to 9.

---

### (a) How many different PIN codes are possible if repetition is allowed?

A PIN code has 4 positions, and each position can be any digit from 0 to 9.

So the number of possible PIN codes is

\[
10^4 = 10000
\]

**Answer:** **10000**

---

### (b) How many 4-digit numbers exist if the first digit cannot be zero?

For a 4-digit number:

- the first digit has 9 choices \((1\text{ to }9)\)
- each of the remaining 3 digits has 10 choices

So the total number is

\[
9\cdot10\cdot10\cdot10 = 9000
\]

**Answer:** **9000**

---

### (c) Why are a PIN code and a 4-digit number counted using different rules?

A PIN code is treated as a **sequence of digits**, not as a numerical value.

That means leading zeros are allowed in PIN codes:

- 0047
- 0123

are valid PIN codes.

But a 4-digit number cannot begin with 0, because then it would no longer be a 4-digit number.

So:

- **PIN code** → any 4-digit sequence from 0–9
- **4-digit number** → first digit must be nonzero

---

### (d) Why must the codes `1234` and `4321` be treated as different outcomes?

Because a PIN code records digits in **specific positions**.

The first code is:

- 1st digit = 1
- 2nd digit = 2
- 3rd digit = 3
- 4th digit = 4

The second code is:

- 1st digit = 4
- 2nd digit = 3
- 3rd digit = 2
- 4th digit = 1

Although they use the same digits, the **order is different**, so they are different codes.

This means PIN codes are counted as **ordered sequences**, not unordered sets of digits.