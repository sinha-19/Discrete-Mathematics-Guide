# 11. Discrete Probability

---

## What is Discrete Probability?

Discrete probability deals with the likelihood of outcomes in experiments with a finite or countable set of possible outcomes.

---

## Basic Terminology

- **Experiment:** Process that produces outcomes.
- **Sample Space (S):** Set of all possible outcomes.
- **Event:** Subset of the sample space.
- **Probability of Event A:** P(A) = |A| / |S| (if equally likely).

---

## Probability Rules

- **P(S) = 1** (certainty).
- **0 ≤ P(A) ≤ 1** for any event A.
- **P(A ∪ B) = P(A) + P(B) − P(A ∩ B)**
- **P(A’ ) = 1 − P(A)**

---

## Conditional Probability

- **P(A|B) = P(A ∩ B) / P(B)** if P(B) > 0

---

## Independence

- Events A and B are independent if P(A ∩ B) = P(A)P(B).

---

## Bayes’ Theorem

- **P(A|B) = [P(B|A) P(A)] / P(B)**

---

## Random Variables

- Function from sample space to real numbers.
- **Discrete Random Variable:** Takes countable values (e.g., number of heads).

---

## Probability Distribution

- **Probability Mass Function (PMF):** P(X = x)
- **Cumulative Distribution Function (CDF):** P(X ≤ x)

---

## Expectation and Variance

- **Expected Value (Mean):** E[X] = Σx P(X=x) x
- **Variance:** Var(X) = E[X²] − (E[X])²

---

## Common Discrete Distributions

- **Bernoulli:** Two outcomes (success/failure).
- **Binomial:** Number of successes in n trials.
- **Geometric:** Number of trials until first success.
- **Poisson:** Number of events in fixed interval.

---

## Applications

- Computer algorithms (randomized algorithms)
- Cryptography (key generation)
- Network protocols (collision probability)
- Game theory and AI

---

## Interview Patterns

- Calculate probabilities in card/dice/coin problems.
- Apply conditional probability and Bayes’ theorem.
- Compute expectation and variance for random variables.

---

## Exercises

1. What is the probability of drawing an ace from a deck?
2. In tossing two coins, what is the probability of at least one head?
3. What is the expected value of a fair six-sided die?
4. If A and B are independent, show P(A ∩ B) = P(A)P(B).
5. Apply Bayes’ theorem to a medical test with known false positives.

---

## Key Interview Questions

- What is the difference between independent and mutually exclusive events?
- State and apply Bayes’ theorem.
- How is expectation computed for a discrete random variable?

---

## References

- [Rosen, Discrete Mathematics, Ch. 7](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Discrete Probability](https://www.geeksforgeeks.org/probability-in-discrete-mathematics/)
- [Brilliant - Probability](https://brilliant.org/wiki/probability/)
- [Khan Academy - Probability and Combinatorics](https://www.khanacademy.org/math/statistics-probability/probability-library)

---
