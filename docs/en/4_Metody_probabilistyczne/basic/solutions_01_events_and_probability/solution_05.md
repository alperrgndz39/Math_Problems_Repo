 Task 5 - Buffon's Needle Experiment

## Problem

Consider an experiment in which a needle of length $L$ is thrown randomly onto a floor with equally spaced parallel lines. The distance between neighboring lines is $d$.

1. Describe the sample space $\Omega$ of this experiment.
2. Identify the parameters that determine the outcome of a single throw.
3. Represent an elementary outcome using appropriate variables describing:
   - the position of the needle relative to the nearest line,
   - the orientation angle of the needle.
4. Express the sample space $\Omega$ as a set of possible values of these variables.
5. Briefly explain why the sample space in this experiment is continuous, unlike the sample spaces in the previous tasks.

## Solution

A single throw is determined by:

- the distance $x$ from the center of the needle to the nearest line,
- the angle $\theta$ between the needle and the lines.

Using symmetry, we may restrict these variables to

$$
x \in \left[0,\frac{d}{2}\right]
$$

and

$$
\theta \in \left[0,\frac{\pi}{2}\right]
$$

Therefore, an elementary outcome is represented by the ordered pair

$$
(x,\theta)
$$

where $x$ and $\theta$ lie in the intervals above.

Hence the sample space is

$$
\Omega = \left\{(x,\theta) \,\middle|\, x \in \left[0,\frac{d}{2}\right],\ \theta \in \left[0,\frac{\pi}{2}\right]\right\}
$$

Equivalently,

$$
\Omega = \left[0,\frac{d}{2}\right] \times \left[0,\frac{\pi}{2}\right]
$$

This sample space is continuous because both $x$ and $\theta$ can take infinitely many real values in intervals, unlike coin tosses, die rolls, or card draws, where the outcomes form finite discrete sets.
