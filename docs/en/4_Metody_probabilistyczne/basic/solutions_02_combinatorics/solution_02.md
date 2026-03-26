# Task 2 — Permutations

## 1. In how many ways can 8 different books be arranged on a shelf?

Since all 8 books are different, the number of arrangements is:

\[
8! = 40320
\]

**Answer:** **40320**

---

## 2. In how many ways can 8 people sit in a row if two particular people must sit next to each other?

Treat the two particular people as one block.  
Then we have:

- 1 block of 2 people
- 6 other people

So in total, there are **7 objects** to arrange:

\[
7!
\]

Inside the block, the two people can switch places in:

\[
2!
\]

Thus, the total number of arrangements is:

\[
7! \cdot 2! = 5040 \cdot 2 = 10080
\]

**Answer:** **10080**

---

## 3. In how many ways can they sit if those two people must not sit next to each other?

First, count all possible arrangements of 8 people:

\[
8! = 40320
\]

From this, subtract the arrangements where the two particular people sit together:

\[
40320 - 10080 = 30240
\]

**Answer:** **30240**

---

## 4. In how many ways can 10 questions in a test be ordered if the first question is fixed?

Since the first question is already fixed, we only need to arrange the remaining 9 questions:

\[
9! = 362880
\]

**Answer:** **362880**