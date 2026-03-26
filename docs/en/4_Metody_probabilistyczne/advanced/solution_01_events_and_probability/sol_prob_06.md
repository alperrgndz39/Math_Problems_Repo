# Task 6 — Events and Probabilities in Coin Tossing

In Task 1, the sample spaces for one, two, and three coin tosses were defined.  
We assume that the coin is **fair**, so all elementary outcomes are **equally likely**.

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
P(H) = \frac{1}{2}, \qquad P(T) = \frac{1}{2}
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

An **event** is any subset of the sample space.

Because all elementary outcomes are equally likely, the probability of an event \(A\) is:

\[
P(A)=\frac{|A|}{|\Omega|}
\]

where:

- \(|A|\) = number of favorable outcomes
- \(|\Omega|\) = total number of outcomes in the sample space

---

## 3. Example events and their probabilities

Since the exact list of events is not provided here, the following are standard examples.

---

## A. Events in one toss

### Event: getting Heads

\[
A=\{H\}
\]

\[
P(A)=\frac{1}{2}
\]

---

### Event: getting Tails

\[
B=\{T\}
\]

\[
P(B)=\frac{1}{2}
\]

---

## B. Events in two tosses

### Event: getting exactly one Head

\[
A=\{HT, TH\}
\]

\[
P(A)=\frac{2}{4}=\frac{1}{2}
\]

---

### Event: getting two Heads

\[
B=\{HH\}
\]

\[
P(B)=\frac{1}{4}
\]

---

### Event: getting at least one Head

\[
C=\{HH, HT, TH\}
\]

\[
P(C)=\frac{3}{4}
\]

---

### Event: getting no Heads

\[
D=\{TT\}
\]

\[
P(D)=\frac{1}{4}
\]

---

### Event: both tosses are the same

\[
E=\{HH, TT\}
\]

\[
P(E)=\frac{2}{4}=\frac{1}{2}
\]

---

## C. Events in three tosses

### Event: getting exactly one Head

\[
A=\{HTT, THT, TTH\}
\]

\[
P(A)=\frac{3}{8}
\]

---

### Event: getting exactly two Heads

\[
B=\{HHT, HTH, THH\}
\]

\[
P(B)=\frac{3}{8}
\]

---

### Event: getting three Heads

\[
C=\{HHH\}
\]

\[
P(C)=\frac{1}{8}
\]

---

### Event: getting at least one Head

\[
D=\{HHH, HHT, HTH, HTT, THH, THT, TTH\}
\]

\[
P(D)=\frac{7}{8}
\]

---

### Event: getting at most one Head

This means 0 or 1 Head:

\[
E=\{TTT, HTT, THT, TTH\}
\]

\[
P(E)=\frac{4}{8}=\frac{1}{2}
\]

---

### Event: all tosses are the same

\[
F=\{HHH, TTT\}
\]

\[
P(F)=\frac{2}{8}=\frac{1}{4}
\]

---

## 4. Conclusion

For a fair coin:

- In \(\Omega_1\), each elementary outcome has probability \(\frac{1}{2}\)
- In \(\Omega_2\), each elementary outcome has probability \(\frac{1}{4}\)
- In \(\Omega_3\), each elementary outcome has probability \(\frac{1}{8}\)

An event is a subset of the sample space, and its probability is found by dividing the number of outcomes in the event by the total number of outcomes in the sample space.

---

## 5. Short presentation explanation

You can explain it like this in class:

A fair coin means that Heads and Tails have equal probability.  
For one toss, there are 2 possible outcomes, so each one has probability \(1/2\).  
For two tosses, there are 4 possible outcomes, so each one has probability \(1/4\).  
For three tosses, there are 8 possible outcomes, so each one has probability \(1/8\).  
An event is simply a subset of the sample space.  
So, to calculate the probability of an event, we use:

\[
P(A)=\frac{\text{number of favorable outcomes}}{\text{total number of outcomes}}
\]

For example, in two tosses, the event “exactly one Head” is \(\{HT, TH\}\), so its probability is:

\[
\frac{2}{4}=\frac{1}{2}
\]

---
