# Task 6 — Events and Probabilities in Coin Tossing

Refer to Task 1, where the sample spaces for one, two, and three coin tosses were defined.

We assume that the coin is **fair**, so all elementary outcomes are equally likely.

Let:

- **H** = Heads
- **T** = Tails

---

## 1. Probabilities of elementary outcomes

### Sample space for one toss: Ω₁

\[
\Omega_1 = \{H, T\}
\]

Since the coin is fair, both outcomes are equally likely:

\[
P(H)=\frac{1}{2}, \qquad P(T)=\frac{1}{2}
\]

So each elementary outcome in \(\Omega_1\) has probability:

\[
\frac{1}{2}
\]

---

### Sample space for two tosses: Ω₂

\[
\Omega_2 = \{HH, HT, TH, TT\}
\]

There are 4 elementary outcomes, and all are equally likely. Therefore:

\[
P(HH)=P(HT)=P(TH)=P(TT)=\frac{1}{4}
\]

So each elementary outcome in \(\Omega_2\) has probability:

\[
\frac{1}{4}
\]

---

### Sample space for three tosses: Ω₃

\[
\Omega_3 = \{HHH, HHT, HTH, HTT, THH, THT, TTH, TTT\}
\]

There are 8 elementary outcomes, and all are equally likely. Therefore:

\[
P(HHH)=P(HHT)=P(HTH)=P(HTT)=P(THH)=P(THT)=P(TTH)=P(TTT)=\frac{1}{8}
\]

So each elementary outcome in \(\Omega_3\) has probability:

\[
\frac{1}{8}
\]

---

## 2. Rule for the probability of an event

An event is any subset of the sample space.

Because all elementary outcomes are equally likely, the probability of an event \(A\) is:

\[
P(A)=\frac{|A|}{|\Omega|}
\]

where:

- \(|A|\) = number of favorable outcomes
- \(|\Omega|\) = total number of outcomes in the sample space

---

## 3. Events and their probabilities

## One Coin Toss

### Event \(A_1\) — the result is heads

\[
A_1=\{H\}
\]

\[
P(A_1)=\frac{1}{2}
\]

### Event \(B_1\) — the result is tails

\[
B_1=\{T\}
\]

\[
P(B_1)=\frac{1}{2}
\]

### Event \(C_1\) — the result is not tails

Not tails means heads, so:

\[
C_1=\{H\}
\]

\[
P(C_1)=\frac{1}{2}
\]

---

## Two Coin Tosses

### Event \(A_2\) — exactly one head occurs

\[
A_2=\{HT, TH\}
\]

\[
P(A_2)=\frac{2}{4}=\frac{1}{2}
\]

### Event \(B_2\) — at least one head occurs

\[
B_2=\{HH, HT, TH\}
\]

\[
P(B_2)=\frac{3}{4}
\]

### Event \(C_2\) — both tosses give the same result

\[
C_2=\{HH, TT\}
\]

\[
P(C_2)=\frac{2}{4}=\frac{1}{2}
\]

---

## Three Coin Tosses

### Event \(A_3\) — exactly two heads occur

\[
A_3=\{HHT, HTH, THH\}
\]

\[
P(A_3)=\frac{3}{8}
\]

### Event \(B_3\) — at least one tail occurs

This means all outcomes except \(HHH\):

\[
B_3=\{HHT, HTH, HTT, THH, THT, TTH, TTT\}
\]

\[
P(B_3)=\frac{7}{8}
\]

### Event \(C_3\) — all three tosses give the same result

\[
C_3=\{HHH, TTT\}
\]

\[
P(C_3)=\frac{2}{8}=\frac{1}{4}
\]

---

## 4. One additional event on \(\Omega_3\)

Define the event \(D_3\) as:

### Event \(D_3\) — exactly one head occurs

\[
D_3=\{HTT, THT, TTH\}
\]

\[
P(D_3)=\frac{3}{8}
\]

---

## 5. Conclusion

For a fair coin:

- In \(\Omega_1\), each elementary outcome has probability \(\frac{1}{2}\)
- In \(\Omega_2\), each elementary outcome has probability \(\frac{1}{4}\)
- In \(\Omega_3\), each elementary outcome has probability \(\frac{1}{8}\)

An event is a subset of the sample space, and its probability is found by dividing the number of outcomes in the event by the total number of outcomes in the sample space.

---

## 6. Short presentation explanation

You can explain it like this in class:

A fair coin means that Heads and Tails have equal probability.

For one toss, there are 2 possible outcomes, so each one has probability \(\frac{1}{2}\).

For two tosses, there are 4 possible outcomes, so each one has probability \(\frac{1}{4}\).

For three tosses, there are 8 possible outcomes, so each one has probability \(\frac{1}{8}\).

An event is simply a subset of the sample space.

So, to calculate the probability of an event, we use:

\[
P(A)=\frac{\text{number of favorable outcomes}}{\text{total number of outcomes}}
\]

For example, in two tosses, the event “exactly one Head” is \(\{HT, TH\}\), so its probability is:

\[
\frac{2}{4}=\frac{1}{2}
\]
