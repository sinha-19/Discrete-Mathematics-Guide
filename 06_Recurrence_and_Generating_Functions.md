# 06. Recurrence Relations and Generating Functions

---

## Recurrence Relations

A **recurrence relation** defines each term of a sequence in terms of previous terms.

### Examples

- **Fibonacci:** F(n) = F(n−1) + F(n−2), F(0)=0, F(1)=1
- **Factorial:** n! = n × (n−1)!, 0! = 1

### Types

- **Linear:** Each term is a linear combination of previous terms.
- **Homogeneous:** No term is a function of n alone (e.g., F(n) = 2F(n−1)).
- **Non-homogeneous:** Has additional terms (e.g., F(n) = 2F(n−1) + n).

---

## Solving Recurrence Relations

### 1. Iteration (Unfolding)

Expand the recurrence to identify a pattern and solve.

### 2. Characteristic Equation

For linear homogeneous relations:
- F(n) = aF(n−1) + bF(n−2)
- Characteristic equation: r^2 − ar − b = 0

Solve for r, general solution is combination of r^n.

### 3. Particular Solution

For non-homogeneous: Find particular solution and add to homogeneous solution.

### 4. Initial Conditions

Determine constants using initial terms.

---

## Generating Functions

A **generating function** is a formal power series whose coefficients encode a sequence:

- For sequence {a₀, a₁, a₂, ...}, generating function G(x) = a₀ + a₁x + a₂x^2 + ...

### Use Cases

- Solve recurrences
- Count combinatorial objects
- Derive closed formulas

---

## Examples

- Fibonacci: G(x) = x/(1 − x − x^2)
- Binomial: (1 + x)^n

---

## Applications

- Analyzing algorithms (recurrence for runtime)
- Counting problems
- Computer science (divide and conquer recurrences)
- Discrete probability distributions

---

## Interview Patterns

- Solve recurrences using iteration and characteristic equations.
- Use generating functions for closed-form solutions.
- Model algorithm runtimes with recurrences.

---

## Exercises

1. Solve F(n) = 2F(n−1), F(0) = 1.
2. Find a closed formula for T(n) = T(n−1) + n, T(1) = 1.
3. Use a generating function to solve a recurrence for arithmetic progression.
4. Find the nth term of F(n) = F(n−1) + 3F(n−2), F(0)=1, F(1)=2.
5. Model the runtime of Merge Sort with a recurrence and solve.

---

## Key Interview Questions

- What is a recurrence relation? Give examples.
- How do you solve linear homogeneous recurrences?
- What is a generating function and why is it useful?

---

## References

- [Rosen, Discrete Mathematics, Ch. 8](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Recurrence Relations](https://www.geeksforgeeks.org/recurrence-relation/)
- [Brilliant - Generating Functions](https://brilliant.org/wiki/generating-functions/)
- [Khan Academy - Intro to Recursion](https://www.khanacademy.org/computing/computer-science/algorithms/recursive-algorithms/a/recursion)

---
