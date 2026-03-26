# Task 4 — Circular Permutations

## 1. In how many ways can 7 people sit around a round table?

For a circular arrangement of \(n\) distinct people, the number of seatings is:

\[
(n-1)!
\]

So for 7 people:

\[
(7-1)! = 6! = 720
\]

**Answer:** **720**

---

## 2. In how many ways can they sit if two particular people must sit next to each other?

Treat the two particular people as one block.  
Then we have:

- 1 block of 2 people
- 5 other people

So there are **6 objects** to arrange around a circle:

\[
(6-1)! = 5!
\]

Inside the block, the two people can switch places in:

\[
2!
\]

Thus, the total number of arrangements is:

\[
5! \cdot 2 = 120 \cdot 2 = 240
\]

**Answer:** **240**

---

## 3. In how many ways can they sit if those two people must sit opposite each other?

Fix one of the two particular people in a seat.  
Since circular rotations are considered the same, this removes rotational symmetry.

Then the other particular person must sit directly opposite them.  
With 7 people, however, **there is no seat directly opposite** a given person at a round table, because 7 is odd.

So this arrangement is **impossible**.

**Answer:** **0**