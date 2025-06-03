# 03. Logic, Propositional Calculus, and Predicate Logic

---

## What is Logic in Discrete Mathematics?

Logic is the study of reasoning. In discrete mathematics, it formalizes how statements (propositions) can be combined, manipulated, and analyzed to determine truth, validity, and inference.

---

## Propositions

- **Proposition:** A declarative statement that is either true (T) or false (F), but not both.
  - Examples: “2 + 2 = 4” (T), “Paris is in Germany” (F).
- **Non-examples:** “How are you?” (question), “x > 2” (not definite until x is known).

---

## Logical Connectives

- **Negation (¬p):** Not p
- **Conjunction (p ∧ q):** p and q
- **Disjunction (p ∨ q):** p or q
- **Exclusive OR (p ⊕ q):** p or q but not both
- **Implication (p → q):** If p then q
- **Biconditional (p ↔ q):** p if and only if q

---

## Truth Tables

- Show all possible truth values for compound statements.

| p | q | ¬p | p ∧ q | p ∨ q | p → q | p ↔ q |
|---|---|----|-------|-------|-------|-------|
| T | T | F  |  T    |   T   |   T   |   T   |
| T | F | F  |  F    |   T   |   F   |   F   |
| F | T | T  |  F    |   T   |   T   |   F   |
| F | F | T  |  F    |   F   |   T   |   T   |

---

## Tautology, Contradiction, Contingency

- **Tautology:** Always true (e.g., p ∨ ¬p)
- **Contradiction:** Always false (e.g., p ∧ ¬p)
- **Contingency:** Sometimes true, sometimes false

---

## Logical Equivalence

- Two statements are logically equivalent if they have the same truth table.
- Common equivalences:
  - **DeMorgan’s Laws:** ¬(p ∧ q) ≡ ¬p ∨ ¬q ; ¬(p ∨ q) ≡ ¬p ∧ ¬q
  - **Implication:** p → q ≡ ¬p ∨ q

---

## Arguments and Inference

- **Argument:** Sequence of propositions (premises) leading to a conclusion.
- **Valid Argument:** If premises are true, conclusion is true.

---

## Rules of Inference

- **Modus Ponens:** p → q, p ⟹ q
- **Modus Tollens:** p → q, ¬q ⟹ ¬p
- **Hypothetical Syllogism:** p → q, q → r ⟹ p → r
- **Disjunctive Syllogism:** p ∨ q, ¬p ⟹ q

---

## Predicate Logic

- Extends propositional logic by including variables and quantifiers.
- **Predicate:** P(x): “x is prime”
- **Quantifiers:**
  - **Universal (∀):** For all x, P(x)
  - **Existential (∃):** There exists x, P(x)

---

## Bound and Free Variables

- **Bound:** Inside scope of quantifier (e.g., ∀x P(x))
- **Free:** Not bound

---

## Logical Equivalences in Predicate Logic

- ∀x (P(x) ∧ Q(x)) ≡ ∀x P(x) ∧ ∀x Q(x)
- ¬∀x P(x) ≡ ∃x ¬P(x)

---

## Applications

- Program verification
- Database queries (SQL logic)
- Automated theorem proving
- AI and knowledge representation

---

## Interview Patterns

- Construct truth tables for logical expressions.
- Prove logical equivalences.
- Formalize English statements into logic (e.g., “All humans are mortal”).
- Use inference rules to derive conclusions.

---

## Exercises

1. Write the truth table for (p → q) ∧ (q → p).
2. Express “Every student passed the exam” using quantifiers.
3. Show that ¬(p → q) ≡ p ∧ ¬q.
4. Prove DeMorgan’s laws with truth tables.
5. Formalize “Some cats are black” using predicate logic.

---

## Key Interview Questions

- What is the difference between propositional and predicate logic?
- State and prove DeMorgan’s laws.
- What is a tautology? Give an example.
- How are quantifiers used in logic?

---

## References

- [Rosen, Discrete Mathematics, Ch. 1 & 3](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Propositional and Predicate Logic](https://www.geeksforgeeks.org/logic-in-mathematics/)
- [Brilliant - Logic](https://brilliant.org/wiki/logic/)
- [Khan Academy - Propositional Logic](https://www.khanacademy.org/computing/computer-science/cryptography/logic/a/logic-statements)

---
