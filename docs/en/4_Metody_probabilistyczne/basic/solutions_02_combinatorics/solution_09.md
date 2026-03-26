# Task 9 — Digit Restrictions

## 1. How many 5-digit numbers exist?

A 5-digit number cannot start with 0.

- First digit: 9 choices \((1–9)\)
- Each of the remaining 4 digits: 10 choices \((0–9)\)

\[
9 \cdot 10^4 = 90000
\]

**Answer:** **90000**

---

## 2. How many of them are even?

A 5-digit number is even if its last digit is one of:

\[
0,2,4,6,8
\]

So there are 5 choices for the last digit.

- First digit: 9 choices
- Middle 3 digits: \(10^3\) choices
- Last digit: 5 choices

\[
9 \cdot 10^3 \cdot 5 = 45000
\]

**Answer:** **45000**

---

## 3. How many contain no repeated digits?

We count 5-digit numbers with all distinct digits.

- First digit: 9 choices \((1–9)\)
- Second digit: 9 choices \((0–9\) except the first digit\()\)
- Third digit: 8 choices
- Fourth digit: 7 choices
- Fifth digit: 6 choices

\[
9 \cdot 9 \cdot 8 \cdot 7 \cdot 6 = 27216
\]

**Answer:** **27216**

---

## 4. How many contain at least one repeated digit?

Use:

\[
\text{all 5-digit numbers} - \text{numbers with no repeated digits}
\]

\[
90000 - 27216 = 62784
\]

**Answer:** **62784**