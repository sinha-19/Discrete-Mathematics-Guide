# 04. Proof Techniques: Induction and Contradiction

---

## Mathematical Proof

A **proof** is a logical argument establishing the truth of a mathematical statement using deductive reasoning.

---

## Types of Proofs

- **Direct Proof:** Prove p ⇒ q by logical steps from p to q.
- **Indirect Proof:** Prove p ⇒ q by showing that ¬q ⇒ ¬p.
- **Contrapositive:** Equivalent to indirect proof.
- **Contradiction:** Assume statement is false, derive contradiction.
- **Proof by Cases:** Consider all possible cases.
- **Exhaustive Proof:** Check all possibilities (finite).

---

## Mathematical Induction

A technique for proving statements about integers (or recursively defined structures).

### Steps

1. **Base Case:** Prove statement for initial value (usually n=0 or n=1).
2. **Inductive Hypothesis:** Assume statement is true for n = k.
3. **Inductive Step:** Prove statement for n = k+1 using hypothesis.

**If both steps succeed, statement holds for all n.**

### Example

Prove: 1 + 2 + ... + n = n(n+1)/2 for all n ≥ 1.

- Base case: n=1 ⇒ 1 = 1(2)/2 = 1 (holds)
- Inductive hypothesis: Assume true for k
- Inductive step: Show true for k+1

---

## Strong Induction

Assume true for all values ≤ k to prove for k+1.

---

## Proof by Contradiction

Assume the negation of what you want to prove, derive a contradiction.

### Example

Prove √2 is irrational.

- Assume √2 is rational ⇒ √2 = a/b, a & b coprime...
- Eventually get contradiction.

---

## Proof by Contrapositive

Prove p ⇒ q by proving ¬q ⇒ ¬p.

---

## Common Mistakes

- Assuming what you want to prove (circular reasoning).
- Failing to establish base case in induction.
- Misapplying induction (e.g., not covering all cases).

---

## Applications

- Proving algorithm correctness
- Proving properties of recursive structures
- Establishing mathematical identities

---

## Interview Patterns

- Use induction to prove statements about sums, divisibility, or recurrences.
- Apply contradiction to prove impossibility results.
- Prove set identities by contrapositive.

---

## Exercises

1. Prove by induction: 2ⁿ > n for all n ≥ 1.
2. Use contradiction to show there are infinitely many primes.
3. Prove that if n² is even, then n is even (contrapositive).
4. Prove by strong induction: Every integer ≥ 2 is a product of primes.
5. Use cases to prove: If n is odd, then n² is odd.

---

## Key Interview Questions

- What is the principle of mathematical induction?
- How is proof by contradiction used in number theory?
- When is strong induction preferable to simple induction?

---

## References

- [Rosen, Discrete Mathematics, Ch. 1.7, 5.1](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Proof Techniques](https://www.geeksforgeeks.org/proof-techniques-in-mathematics/)
- [Brilliant - Induction Proofs](https://brilliant.org/wiki/induction/)
- [Khan Academy - Mathematical Proofs](https://www.khanacademy.org/math/math-for-fun-and-glory/logic)

---
