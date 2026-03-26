# Task 6 — Combinations in Card Problems

A standard deck has:

- **52 cards**
- **13 hearts**
- **39 non-hearts**
- **12 face cards** \((4 \text{ Jacks} + 4 \text{ Queens} + 4 \text{ Kings})\)
- **40 non-face cards**

## 1. In how many ways can 5 cards be drawn so that the hand contains exactly 2 hearts?

Choose:

- 2 hearts from 13
- 3 non-hearts from 39

\[
\binom{13}{2}\binom{39}{3}
\]

Now compute:

\[
\binom{13}{2} = 78
\]

\[
\binom{39}{3} = 9139
\]

\[
78 \cdot 9139 = 712842
\]

**Answer:** **712842**

---

## 2. In how many ways can a 5-card hand contain at least one heart?

First count all possible 5-card hands:

\[
\binom{52}{5} = 2598960
\]

Now subtract the hands with **no hearts**, meaning all 5 cards are chosen from the 39 non-hearts:

\[
\binom{39}{5} = 575757
\]

So the number of hands with **at least one heart** is:

\[
\binom{52}{5} - \binom{39}{5}
\]

\[
2598960 - 575757 = 2023203
\]

**Answer:** **2023203**

---

## 3. In how many ways can a 5-card hand contain no face cards (J, Q, K)?

There are 12 face cards, so the number of non-face cards is:

\[
52 - 12 = 40
\]

We choose all 5 cards from these 40 non-face cards:

\[
\binom{40}{5}
\]

Now compute:

\[
\binom{40}{5} = 658008
\]

**Answer:** **658008**