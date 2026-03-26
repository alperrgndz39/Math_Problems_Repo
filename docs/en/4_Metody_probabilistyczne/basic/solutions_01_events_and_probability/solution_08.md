# Task 8 — Events and Probabilities in Card Drawing

We refer to the sample spaces from Task 3.

A standard deck has:

- 52 cards
- 13 hearts
- 4 kings
- 4 aces
- 12 face cards \((J,Q,K)\)
- 40 non-face cards

Since the deck is well-shuffled, all elementary outcomes in the relevant sample space are **equally likely**.

---

## 1. Probabilities of Elementary Outcomes

### Sample space \(\Omega_1\) — one card drawn

\[
\Omega_1=\{\text{all 52 cards}\}
\]

So:

\[
|\Omega_1|=52
\]

and each elementary outcome has probability

\[
P(\{\omega\})=\frac{1}{52}
\qquad (\omega\in\Omega_1)
\]

---

### Sample space \(\Omega_2\) — two cards drawn with replacement

\[
\Omega_2=\{(c_1,c_2)\mid c_1,c_2\in D\}
\]

where \(D\) is the set of all 52 cards.

So:

\[
|\Omega_2|=52^2=2704
\]

and each elementary outcome has probability

\[
P(\{(c_1,c_2)\})=\frac{1}{2704}
\qquad ((c_1,c_2)\in\Omega_2)
\]

---

### Sample space \(\Omega_2'\) — two cards drawn without replacement

\[
\Omega_2'=\{(c_1,c_2)\mid c_1,c_2\in D,\ c_1\neq c_2\}
\]

So:

\[
|\Omega_2'|=52\cdot 51=2652
\]

and each elementary outcome has probability

\[
P(\{(c_1,c_2)\})=\frac{1}{2652}
\qquad ((c_1,c_2)\in\Omega_2')
\]

---

# 2. One Card Drawn

## Event \(A_1\) — the card is a heart

There are 13 hearts, so

\[
A_1=\{\text{all hearts}\}
\]

and

\[
P(A_1)=\frac{13}{52}=\frac{1}{4}
\]

---

## Event \(B_1\) — the card is a king

There are 4 kings, so

\[
B_1=\{\text{all kings}\}
\]

and

\[
P(B_1)=\frac{4}{52}=\frac{1}{13}
\]

---

## Event \(C_1\) — the card is not a face card

Face cards are \(J,Q,K\), so there are:

\[
3\cdot 4 = 12
\]

face cards, hence:

\[
52-12=40
\]

non-face cards.

Thus

\[
C_1=\{\text{all non-face cards}\}
\]

and

\[
P(C_1)=\frac{40}{52}=\frac{10}{13}
\]

---

# 3. Two Cards Drawn With Replacement

## Event \(A_2\) — both cards are hearts

For each draw, the probability of a heart is:

\[
\frac{13}{52}=\frac{1}{4}
\]

So:

\[
P(A_2)=\frac{1}{4}\cdot \frac{1}{4}=\frac{1}{16}
\]

As a subset,

\[
A_2=\{(c_1,c_2)\in\Omega_2\mid c_1\text{ and }c_2\text{ are hearts}\}
\]

---

## Event \(B_2\) — both cards have the same rank

The first card can be anything.  
Once the first card is fixed, there are 4 cards of that rank in the deck, and with replacement the second draw has probability

\[
\frac{4}{52}=\frac{1}{13}
\]

of matching the same rank.

So:

\[
P(B_2)=\frac{1}{13}
\]

As a count check:

- choose the first card: 52 ways
- choose the second card with the same rank: 4 ways

So favorable ordered pairs:

\[
52\cdot 4 = 208
\]

Hence:

\[
P(B_2)=\frac{208}{2704}=\frac{1}{13}
\]

---

## Event \(C_2\) — at least one card is an ace

Use the complement.

Let \(C_2^c\) be the event that neither card is an ace.

There are 48 non-aces, so:

\[
P(C_2^c)=\left(\frac{48}{52}\right)^2=\left(\frac{12}{13}\right)^2=\frac{144}{169}
\]

Therefore:

\[
P(C_2)=1-\frac{144}{169}=\frac{25}{169}
\]

As a subset,

\[
C_2=\{(c_1,c_2)\in\Omega_2\mid \text{at least one of }c_1,c_2\text{ is an ace}\}
\]

---

# 4. Two Cards Drawn Without Replacement

## Event \(A_3\) — both cards are hearts

Without replacement:

- first card is a heart: \(\frac{13}{52}\)
- second card is a heart given the first was a heart: \(\frac{12}{51}\)

So:

\[
P(A_3)=\frac{13}{52}\cdot\frac{12}{51}
=\frac{1}{4}\cdot\frac{12}{51}
=\frac{12}{204}
=\frac{1}{17}
\]

As a subset,

\[
A_3=\{(c_1,c_2)\in\Omega_2' \mid c_1\text{ and }c_2\text{ are hearts}\}
\]

---

## Event \(B_3\) — both cards have the same rank

After drawing the first card, there are only 3 remaining cards of the same rank among the remaining 51 cards.

So:

\[
P(B_3)=\frac{3}{51}=\frac{1}{17}
\]

As a count check:

- first card: 52 choices
- second card of same rank: 3 choices

Favorable outcomes:

\[
52\cdot 3=156
\]

Hence:

\[
P(B_3)=\frac{156}{2652}=\frac{1}{17}
\]

---

## Event \(C_3\) — one card is a king and the other is a queen (in any order)

We count ordered pairs:

- first a king, then a queen: \(4\cdot 4=16\)
- first a queen, then a king: \(4\cdot 4=16\)

Total favorable outcomes:

\[
16+16=32
\]

Thus:

\[
P(C_3)=\frac{32}{2652}
\]

Simplify:

\[
\frac{32}{2652}=\frac{8}{663}
\]

So:

\[
P(C_3)=\frac{8}{663}
\]

As a subset,

\[
C_3=\{(c_1,c_2)\in\Omega_2' \mid (c_1\text{ is a king and }c_2\text{ is a queen}) \text{ or } (c_1\text{ is a queen and }c_2\text{ is a king})\}
\]

---

# 5. One Additional Event on \(\Omega_2'\)

Define the event

\[
D_3=\{\text{the two cards have different suits}\}
\]

We compute its probability.

After the first card is drawn, there are 51 cards left.  
Among them, 12 have the same suit as the first card, so:

\[
51-12=39
\]

have a different suit.

Therefore:

\[
P(D_3)=\frac{39}{51}=\frac{13}{17}
\]

---

# Final Answers Summary

## Elementary outcome probabilities

- On \(\Omega_1\): each elementary outcome has probability  
\[
\frac{1}{52}
\]

- On \(\Omega_2\): each elementary outcome has probability  
\[
\frac{1}{2704}
\]

- On \(\Omega_2'\): each elementary outcome has probability  
\[
\frac{1}{2652}
\]

---

## One card drawn

\[
P(A_1)=\frac{1}{4}
\]

\[
P(B_1)=\frac{1}{13}
\]

\[
P(C_1)=\frac{10}{13}
\]

---

## Two cards drawn with replacement

\[
P(A_2)=\frac{1}{16}
\]

\[
P(B_2)=\frac{1}{13}
\]

\[
P(C_2)=\frac{25}{169}
\]

---

## Two cards drawn without replacement

\[
P(A_3)=\frac{1}{17}
\]

\[
P(B_3)=\frac{1}{17}
\]

\[
P(C_3)=\frac{8}{663}
\]

---

## Additional event

For

\[
D_3=\{\text{the two cards have different suits}\}
\]

we get

\[
P(D_3)=\frac{13}{17}
\]