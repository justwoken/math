## 🧱 FOUNDATIONAL AXIOMS (ZFC Set Theory)

These aren't theorems per se, but **axioms** — the starting rules of modern set theory (Zermelo–Fraenkel with Choice):

1. **Axiom of Extensionality**  
   Two sets are equal if they have the same elements.

2. **Axiom of Pairing**  
   For any two sets, there exists a set containing exactly those two.

3. **Axiom of Union**  
   For any set of sets, there exists a set that contains all elements of those sets.

4. **Axiom of Power Set**  
   For any set, there exists a set of all its subsets.

5. **Axiom of Infinity**  
   A set containing 0 and closed under successor exists — allowing the natural numbers.

6. **Axiom of Foundation (Regularity)**  
   No infinite descending membership chain; all sets are built from “lower” sets.

7. **Axiom of Replacement**  
   Applying a definable function to a set yields another set.

8. **Axiom of Separation (Specification)**  
   Subsets can be formed by choosing elements that satisfy a property.

9. **Axiom of Choice (AC)**  
   From any collection of nonempty sets, you can choose one element from each.

---

## 📚 CLASSICAL THEOREMS OF SET THEORY

### 1. **Cantor’s Theorem**
> The power set of any set has strictly greater cardinality than the set itself.
- Implies there’s no “largest” infinity.
- Leads to the hierarchy of cardinalities.

### 2. **Cantor’s Diagonal Argument**
> There is no complete list of real numbers — they are uncountable.
- First proof that ℝ is “larger” than ℕ.

### 3. **Schröder–Bernstein Theorem**
> If A injects into B and B injects into A, then A and B have the same cardinality.
- Key for comparing infinite sets without explicit bijections.

### 4. **Zorn’s Lemma**
> Every non-empty partially ordered set with upper bounds has a maximal element.
- Equivalent to the Axiom of Choice.
- Used in algebra, topology, etc.

### 5. **Well-Ordering Theorem**
> Every set can be well-ordered (i.e., every nonempty subset has a least element).
- Also equivalent to the Axiom of Choice.
- Allows ordinals to “index” all sets.

### 6. **Banach–Tarski Paradox**
> A solid ball can be split and reassembled into two identical balls using only rotation and translation.
- Uses the Axiom of Choice.
- Relies on non-measurable sets.

### 7. **Löwenheim–Skolem Theorem**
> Any countable first-order theory with an infinite model has a countable model.
- Implies the “Skolem Paradox” — even set theory has countable models!

### 8. **Mostowski Collapse Lemma**
> Any well-founded extensional relation is isomorphic to membership on a transitive set.
- Connects abstract relations to set-theoretic structure.

### 9. **Reflection Theorem**
> Any property true of the universe is also true in some smaller rank-initial segment.
- Supports the idea that no set “contains all of set theory.”

### 10. **Gödel’s Incompleteness Theorems** (Impact on Set Theory)
> No consistent system can prove all truths about arithmetic; it cannot prove its own consistency.
- Shows ZFC is incomplete — not all truths about sets can be proven.

---

## 🔬 ADVANCED (AND CONTROVERSIAL) RESULTS

### 11. **Continuum Hypothesis (CH)**
> Is there a set with cardinality strictly between ℕ and ℝ?
- **Undecidable** in ZFC — can’t be proven or disproven from standard axioms.
- SCR reinterprets this as a boundary of symbolic definition, not a paradox.

### 12. **Forcing (Cohen, 1963)**
> A method to build alternate models of set theory — used to prove the independence of CH and AC.

### 13. **Easton’s Theorem**
> The power function \( \kappa \mapsto 2^\kappa \) can behave wildly, under certain consistency assumptions.

### 14. **Constructibility (Gödel’s L)**  
> Introduced a model (L) where CH and AC hold.
- Foundation of "constructible universe".

---

## 🧠 Summary Table

| Theorem / Principle         | Significance                                   |
|-----------------------------|------------------------------------------------|
| **Cantor’s Theorem**        | No biggest infinity; power sets are larger     |
| **Diagonal Argument**       | Real numbers are uncountable                   |
| **Zorn’s Lemma**            | Fundamental tool (equiv. to Axiom of Choice)   |
| **Well-Ordering**           | Every set can be totally ordered               |
| **Banach–Tarski**           | Shocking result of AC + non-measurables        |
| **Gödel + Cohen**           | CH is undecidable in ZFC                       |
| **Schröder–Bernstein**      | Comparing infinite sets' size                  |
| **Reflection + Löwenheim–Skolem** | Universe is "unfolding", never fully fixed |

---

Would you like a diagram of how these theorems interconnect or a version rewritten in **SCR style** to show which ones hold, which ones change, and why?