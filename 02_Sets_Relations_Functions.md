# 02. Sets, Relations, and Functions

---

## Sets

### Definition

A **set** is a collection of distinct objects, called elements or members.

### Notation

- Set: {a, b, c}
- a ∈ S: a is an element of S.
- Empty set: ∅

### Types of Sets

- **Finite/Infinite:** Number of elements.
- **Subset:** A ⊆ B.
- **Proper Subset:** A ⊂ B (A ≠ B).
- **Universal Set (U):** Contains all elements under consideration.
- **Power Set:** Set of all subsets.

### Set Operations

- **Union (A ∪ B):** Elements in A or B.
- **Intersection (A ∩ B):** Elements in both A and B.
- **Difference (A \ B):** Elements in A not in B.
- **Complement (A’):** Elements not in A.
- **Cartesian Product (A × B):** Set of ordered pairs (a, b).

### Venn Diagrams

Visual representations of set operations.

---

## Relations

### Definition

A **relation** R from set A to B is a subset of A × B.

### Properties

- **Reflexive:** (a, a) ∈ R ∀ a ∈ A.
- **Symmetric:** (a, b) ∈ R ⇒ (b, a) ∈ R.
- **Antisymmetric:** (a, b) ∈ R & (b, a) ∈ R ⇒ a = b.
- **Transitive:** (a, b), (b, c) ∈ R ⇒ (a, c) ∈ R.

### Types

- **Equivalence Relation:** Reflexive, symmetric, transitive.
- **Partial Order:** Reflexive, antisymmetric, transitive.

### Matrix Representation

Relations can be represented with zero-one matrices.

### Digraphs

Directed graphs visualize relations.

---

## Functions

### Definition

A **function** f: A → B assigns to each element of A exactly one element of B.

### Types

- **One-to-one (Injective):** Different inputs map to different outputs.
- **Onto (Surjective):** Every element of B is mapped.
- **Bijective:** Both one-to-one and onto.

### Composition

If f: A → B, g: B → C, then g∘f: A → C.

### Inverse Functions

Exists if and only if function is bijective.

---

## Applications

- Databases (relations, keys)
- Programming (functions, mappings)
- Network models (relations)
- Formal languages (set operations)

---

## Interview Patterns

- Prove or disprove properties of a relation.
- Identify equivalence classes for a relation.
- Determine injectivity/surjectivity of functions.
- Draw Venn diagrams for set operations.

---

## Exercises

1. List all subsets of {1, 2, 3}.
2. Prove that the relation “is a sibling of” is symmetric but not transitive.
3. Give an example of a bijective function from Z to Z.
4. Compute (A ∪ B)’ given A, B subsets of U.
5. Represent a relation as a zero-one matrix and digraph.

---

## Key Interview Questions

- What is an equivalence relation? Give an example.
- How are set operations used in databases?
- Define and distinguish injective, surjective, bijective functions.

---

## References

- [Rosen, Discrete Mathematics, Ch. 2](https://www.mheducation.com/highered/product/discrete-mathematics-its-applications-rosen/M9780073383095.html)
- [GeeksforGeeks - Sets, Relations, and Functions](https://www.geeksforgeeks.org/sets-in-discrete-mathematics/)
- [Brilliant - Set Theory](https://brilliant.org/wiki/set-theory/)
- [Khan Academy - Relations and Functions](https://www.khanacademy.org/math/algebra/x2f8bb11595b61c86:relations-and-functions)

---
