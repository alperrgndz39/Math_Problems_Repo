# Task 10 — Urn Models

The urn contains:

- 5 red balls
- 4 blue balls
- 3 green balls

So the total number of balls is:

\[
5+4+3=12
\]

## 1. Three balls are drawn without replacement. How many samples are possible if order is ignored?

Since order does **not** matter, we use combinations:

\[
\binom{12}{3}=\frac{12!}{3!9!}=220
\]

**Answer:** **220**

---

## 2. How many samples contain exactly two red balls?

To get exactly two red balls:

- choose 2 red balls from 5
- choose 1 non-red ball from the remaining \(4+3=7\) balls

\[
\binom{5}{2}\binom{7}{1}=10\cdot 7=70
\]

**Answer:** **70**

---

## 3. Three balls are drawn and the order of colors is recorded. How many outcomes are possible?

Now we record only the **sequence of colors**.

For each of the 3 draws, the color can be:

- red
- blue
- green

Since each color is available in sufficient quantity for up to 3 draws, every 3-letter color sequence is possible.

\[
3^3=27
\]

**Answer:** **27**

---

## 4. How many outcomes contain exactly two red balls?

We want 3-draw color sequences with exactly two \(R\)'s.

- Choose the position of the non-red color: \(\binom{3}{1}=3\)
- That non-red color can be either blue or green: \(2\) choices

So:

\[
3 \cdot 2 = 6
\]

The sequences are:

- RRB
- RBR
- BRR
- RRG
- RGR
- GRR

**Answer:** **6**