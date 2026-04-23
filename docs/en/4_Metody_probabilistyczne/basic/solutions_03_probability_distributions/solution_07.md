# Task 07 – Hypergeometric Probability of Defective Bulbs

## Problem Statement

A box contains:

- $12$ working light bulbs
- $3$ defective light bulbs

A sample of $5$ bulbs is drawn without replacement.

Determine the probability that the sample contains exactly $2$ defective bulbs.

---

## Theory

Since the bulbs are drawn **without replacement**, the appropriate model is the hypergeometric distribution.

The probability of obtaining exactly $k$ defective items in a sample of size $n$ is:

$$
P(X=k)=\frac{\binom{D}{k}\binom{W}{n-k}}{\binom{D+W}{n}}
$$

where:

- $D$ = number of defective bulbs
- $W$ = number of working bulbs
- $n$ = sample size
- $k$ = required number of defective bulbs

For this problem:

$$
D=3, \quad W=12, \quad n=5, \quad k=2
$$

---

## Step-by-Step Solution

### Number of Favorable Samples

Choose $2$ defective bulbs from $3$:

$$
\binom{3}{2}=3
$$

Choose the remaining $3$ bulbs from the $12$ working bulbs:

$$
\binom{12}{3}=220
$$

Total favorable selections:

$$
\binom{3}{2}\binom{12}{3}=3 \cdot 220=660
$$

---

### Total Number of Possible Samples

Choose any $5$ bulbs from $15$ total bulbs:

$$
\binom{15}{5}=3003
$$

---

### Required Probability

$$
P(X=2)=\frac{660}{3003}
$$

Simplify:

$$
P(X=2)\approx 0.2198
$$

---

## Final Result

$$
P(\text{exactly 2 defective bulbs})=\frac{660}{3003}\approx 0.2198
$$

---

## Interpretation

The probability that a sample of five bulbs contains exactly two defective bulbs is approximately $21.98\%$.
