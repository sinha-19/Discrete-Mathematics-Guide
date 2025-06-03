# 05. Combinatorics: Counting, Permutations, and Combinations

---

## What is Combinatorics?

**Combinatorics** is the study of counting, arranging, and selecting objects. It answers questions like “How many ways?” and underpins probability, algorithms, and complexity.

---

## Basic Counting Principles

- **Addition Rule:** If tasks A and B are mutually exclusive, total ways = ways(A) + ways(B).
- **Multiplication Rule:** If tasks A and B are independent, total ways = ways(A) × ways(B).

---

## Permutations

- **Permutation:** Ordered arrangement of objects.
  - n distinct objects: n!
  - r-permutation (arrange r out of n): P(n, r) = n!/(n−r)!
- **With Repetition:** n^r ways to fill r spots from n choices.

---

## Combinations

- **Combination:** Selection of objects, order doesn’t matter.
  - n choose r: C(n, r) = n! / (r!(n−r)!)
- **With Repetition:** C(n+r−1, r)

---

## Binomial Theorem

- (x + y)^n = Σ C(n, k) x^{n−k} y^k

---

## Inclusion-Exclusion Principle

- For sets A, B: |A ∪ B| = |A| + |B| − |A ∩ B|
- For more sets, alternate adding and subtracting intersections.

---

## Pigeonhole Principle

- If n+1 objects are placed into n boxes, at least one box contains ≥2 objects.

---

## Catalan Numbers

- Count certain combinatorial structures (e.g., valid parentheses, binary trees).

---

## Applications

- Arrangements of passwords, seating
- Counting paths in a grid
- Scheduling and resource allocation
- Probability problems

---

## Interview Patterns

- Count arrangements under restrictions (e.g., no two vowels together).
- Apply inclusion-exclusion for overlapping groups.
- Use pigeonhole principle for existence proofs.

---

## Exercises

1. How many ways to arrange 5 books on a shelf?
2. In how many ways can 3 balls be placed in 4 boxes?
3. How many 5-letter “words” can be formed from A, B, C if repetition is allowed?
4. In a group of 13 people, prove at least two have birthdays in the same month.
5. How many ways to select a committee of 3 from 10 people?

---

## Key Interview Questions

- What is the difference between permutation and combination?
- When do you use inclusion-exclusion?
- Explain the pigeonhole principle with an example.

---

## References

- [Rosen, Discrete Mathematics, Ch. 6](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Combinatorics](https://www.geeksforgeeks.org/combinatorics-in-mathematics/)
- [Brilliant - Counting and Combinatorics](https://brilliant.org/wiki/counting/)
- [Khan Academy - Counting Principles](https://www.khanacademy.org/math/statistics-probability/probability-library/basic-counting/v/basic-counting-principle)

---
