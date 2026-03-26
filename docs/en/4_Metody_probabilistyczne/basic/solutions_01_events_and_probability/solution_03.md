# Task 3 — Drawing Cards

Consider a standard deck of **52 cards**.

Since the order of outcomes matters, each elementary outcome is an **ordered sequence of drawn cards**.

---

## 1. Sample space for drawing one card

For one draw, the sample space consists of all 52 cards in the deck:

\[
\Omega_1 = \{\text{all 52 distinct cards}\}
\]

For example, some elements are:

\[
\text{Ace of Spades},\ \text{7 of Hearts},\ \text{King of Clubs},\ \text{2 of Diamonds}
\]

### Number of elementary outcomes

\[
|\Omega_1| = 52
\]

---

## 2. Sample space for two consecutive draws **with replacement**

With replacement, after the first card is drawn, it is returned to the deck before the second draw.

So each draw has **52 possible cards**, and the same card may appear again.

The sample space is:

\[
\Omega_2 = \{(c_1,c_2)\mid c_1,c_2 \in D\}
\]

where \(D\) is the set of all 52 cards.

So \(\Omega_2\) consists of all ordered pairs of cards, including pairs such as:

\[
(\text{Ace of Spades}, \text{Ace of Spades})
\]

\[
(\text{10 of Hearts}, \text{3 of Clubs})
\]

\[
(\text{Queen of Diamonds}, \text{5 of Spades})
\]

### Number of elementary outcomes

Since there are 52 choices for the first draw and 52 choices for the second draw:

\[
|\Omega_2| = 52 \cdot 52 = 52^2 = 2704
\]

---

## 3. Sample space for two consecutive draws **without replacement**

Without replacement, the first drawn card is **not** returned to the deck.

So:

- first draw: 52 choices
- second draw: 51 choices

The sample space is:

\[
\Omega_2' = \{(c_1,c_2)\mid c_1,c_2 \in D,\ c_1 \neq c_2\}
\]

So \(\Omega_2'\) consists of all ordered pairs of **different** cards.

Examples:

\[
(\text{Ace of Spades}, \text{King of Hearts})
\]

\[
(\text{4 of Clubs}, \text{4 of Diamonds})
\]

but **not**

\[
(\text{7 of Hearts}, \text{7 of Hearts})
\]

because the same physical card cannot be drawn twice without replacement.

### Number of elementary outcomes

\[
|\Omega_2'| = 52 \cdot 51 = 2652
\]

---

## 4. What does an elementary outcome represent?

An **elementary outcome** is one complete ordered description of the result of the experiment.

### In \(\Omega_1\)

An elementary outcome is **one specific card**.

Example:

\[
\text{Jack of Spades}
\]

---

### In \(\Omega_2\) (with replacement)

An elementary outcome is an **ordered pair of cards**:

\[
(c_1,c_2)
\]

where repetition is allowed.

Example:

\[
(\text{9 of Clubs}, \text{9 of Clubs})
\]

means:

- first draw: 9 of Clubs
- second draw: 9 of Clubs

---

### In \(\Omega_2'\) (without replacement)

An elementary outcome is an **ordered pair of distinct cards**:

\[
(c_1,c_2)
\]

Example:

\[
(\text{Ace of Hearts}, \text{3 of Spades})
\]

means:

- first draw: Ace of Hearts
- second draw: 3 of Spades

Because order matters, outcomes such as

\[
(\text{Ace of Hearts}, \text{3 of Spades})
\quad \text{and} \quad
(\text{3 of Spades}, \text{Ace of Hearts})
\]

are different.

---

## 5. Summary

### One draw

\[
|\Omega_1| = 52
\]

### Two draws with replacement

\[
\Omega_2 = \{(c_1,c_2)\mid c_1,c_2 \in D\}
\]

\[
|\Omega_2| = 52^2 = 2704
\]

### Two draws without replacement

\[
\Omega_2' = \{(c_1,c_2)\mid c_1,c_2 \in D,\ c_1 \neq c_2\}
\]

\[
|\Omega_2'| = 52 \cdot 51 = 2652
\]

---

## Final remark

The difference between \(\Omega_2\) and \(\Omega_2'\) comes from whether the first card is returned to the deck:

- **with replacement** → the second draw still has 52 possibilities
- **without replacement** → the second draw has only 51 possibilities

Since order matters, all outcomes are counted as **ordered sequences**.