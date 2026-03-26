# Task 12 — Mixed Counting Problem

For each part, we identify the appropriate counting model and compute the number of outcomes.

---

## 1. Student ID Codes

Each identifier consists of:

- 2 letters chosen from \(\{A,B,C,D,E\}\)
- followed by 3 digits chosen from \(\{0,1,\dots,9\}\)

---

### (a) How many identifiers are possible if letters and digits may repeat?

#### Counting model
- letters: **sequence with repetition**
- digits: **sequence with repetition**

For the letters:

\[
5 \cdot 5 = 5^2 = 25
\]

For the digits:

\[
10^3 = 1000
\]

Total number of identifiers:

\[
5^2 \cdot 10^3 = 25 \cdot 1000 = 25000
\]

**Answer:** **25000**

---

### (b) How many identifiers are possible if letters may not repeat but digits may repeat?

#### Counting model
- letters: **k-permutation without repetition**
- digits: **sequence with repetition**

For the letters:

\[
P(5,2)=5\cdot4=20
\]

For the digits:

\[
10^3=1000
\]

Total:

\[
20 \cdot 1000 = 20000
\]

**Answer:** **20000**

---

### (c) How many identifiers are possible if neither letters nor digits may repeat?

#### Counting model
- letters: **k-permutation without repetition**
- digits: **k-permutation without repetition**

For the letters:

\[
P(5,2)=5\cdot4=20
\]

For the digits:

\[
P(10,3)=10\cdot9\cdot8=720
\]

Total:

\[
20 \cdot 720 = 14400
\]

**Answer:** **14400**

---

## 2. Medal Assignment

There are 12 runners, and medals are awarded for:

- gold
- silver
- bronze

Since the medals are different, order matters.

---

### (a) In how many ways can the medals be assigned?

#### Counting model
**3-permutation** of 12 runners

\[
P(12,3)=12\cdot11\cdot10=1320
\]

**Answer:** **1320**

---

### (b) Suppose two particular runners must both receive medals. In how many ways can the medals be assigned?

Let the two particular runners be \(A\) and \(B\).  
They must both receive medals, so exactly one of the three medals goes to someone else.

#### Method
- Choose which 2 of the 3 medal positions go to \(A\) and \(B\):  
\[
\binom{3}{2}=3
\]
- Arrange \(A\) and \(B\) in those two positions:  
\[
2!=2
\]
- Choose the third medalist from the remaining 10 runners:  
\[
10
\]

Total:

\[
\binom{3}{2}\cdot2!\cdot10 = 3\cdot2\cdot10 = 60
\]

**Answer:** **60**

---

## 3. Committee Selection

A committee of 4 people is chosen from 10 students:

- 6 men
- 4 women

Since a committee is unordered, we use **combinations**.

---

### (a) How many committees are possible?

#### Counting model
**Combination**

\[
\binom{10}{4}=210
\]

**Answer:** **210**

---

### (b) How many committees contain exactly two women?

#### Counting model
**Combination**

Choose:

- 2 women from 4
- 2 men from 6

\[
\binom{4}{2}\binom{6}{2}=6\cdot15=90
\]

**Answer:** **90**

---

### (c) How many committees contain at least one woman?

#### Method
Count all committees and subtract all-male committees.

Total committees:

\[
\binom{10}{4}=210
\]

All-male committees:

\[
\binom{6}{4}=15
\]

Thus:

\[
210-15=195
\]

**Answer:** **195**

---

## 4. Circular Seating

Seven people sit around a round table.

---

### (a) How many different seating arrangements are possible?

#### Counting model
**Circular permutation**

For \(n\) distinct people around a round table:

\[
(n-1)!
\]

So:

\[
(7-1)! = 6! = 720
\]

**Answer:** **720**

---

### (b) In how many arrangements do two particular people sit next to each other?

Treat the two particular people as one block.

Then we have:

- 1 block
- 5 other people

So there are 6 objects around a circle.

#### Counting model
**Circular permutation with a block**

Arrange the 6 objects:

\[
(6-1)! = 5! = 120
\]

Inside the block, the two people can switch places:

\[
2!
\]

Total:

\[
5!\cdot2 = 120\cdot2 = 240
\]

**Answer:** **240**

---

## 5. Passwords

A password consists of 5 characters chosen from:

- 10 digits \((0\text{–}9)\)
- 26 letters \((A\text{–}Z)\)

So there are:

\[
10+26=36
\]

possible characters for each position.

---

### (a) How many passwords are possible if repetition is allowed?

#### Counting model
**Sequence with repetition**

Each of the 5 positions has 36 choices:

\[
36^5
\]

Now compute:

\[
36^5 = 60466176
\]

**Answer:** **60466176**

---

### (b) How many passwords are possible if no character may repeat?

#### Counting model
**k-permutation without repetition**

We choose and arrange 5 distinct characters from 36:

\[
P(36,5)=36\cdot35\cdot34\cdot33\cdot32
\]

Now compute:

\[
36\cdot35\cdot34\cdot33\cdot32 = 45239040
\]

**Answer:** **45239040**

---

### (c) Which counting model is used in each case?

- **Repetition allowed:** **sequence with repetition**
- **No repetition allowed:** **k-permutation (ordered selection without repetition)**

---

# Final Answers Summary

## 1. Student ID Codes
- Repetition allowed: **25000**
- Letters not repeated, digits may repeat: **20000**
- Neither letters nor digits repeated: **14400**

## 2. Medal Assignment
- Any medal assignment: **1320**
- Two particular runners must both receive medals: **60**

## 3. Committee Selection
- Total committees: **210**
- Exactly two women: **90**
- At least one woman: **195**

## 4. Circular Seating
- Total seatings: **720**
- Two particular people sit next to each other: **240**

## 5. Passwords
- Repetition allowed: **60466176**
- No repetition allowed: **45239040**
- Models used: **sequence with repetition**, **k-permutation without repetition**