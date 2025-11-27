# Logic

The principles of valid reasoning and proof.

## Core Concepts

### Propositional Logic

#### Propositions
A statement that is either true or false.

#### Logical Connectives
| Symbol | Name | Meaning |
|--------|------|---------|
| ¬ | Negation | not P |
| ∧ | Conjunction | P and Q |
| ∨ | Disjunction | P or Q |
| → | Implication | if P then Q |
| ↔ | Biconditional | P if and only if Q |

#### Truth Tables
| P | Q | P ∧ Q | P ∨ Q | P → Q | P ↔ Q |
|---|---|-------|-------|-------|-------|
| T | T | T | T | T | T |
| T | F | F | T | F | F |
| F | T | F | T | T | F |
| F | F | F | F | T | T |

### Predicate Logic

#### Quantifiers
- **Universal quantifier (∀)**: "for all"
- **Existential quantifier (∃)**: "there exists"

#### Examples
- ∀x ∈ ℝ: x² ≥ 0 (all real numbers squared are non-negative)
- ∃x ∈ ℕ: x is prime and x is even (there exists such an x: namely 2)

### Important Logical Equivalences

1. **De Morgan's Laws**:
   - ¬(P ∧ Q) ≡ (¬P) ∨ (¬Q)
   - ¬(P ∨ Q) ≡ (¬P) ∧ (¬Q)

2. **Contrapositive**: (P → Q) ≡ (¬Q → ¬P)

3. **Negation of quantifiers**:
   - ¬(∀x: P(x)) ≡ ∃x: ¬P(x)
   - ¬(∃x: P(x)) ≡ ∀x: ¬P(x)

### Common Fallacies

- **Affirming the consequent**: P → Q, Q, therefore P (INVALID)
- **Denying the antecedent**: P → Q, ¬P, therefore ¬Q (INVALID)

## Topics to Explore

- [ ] Tautologies and contradictions
- [ ] Logical equivalence
- [ ] Argument validity
- [ ] First-order logic
- [ ] Higher-order logic
- [ ] Modal logic

## Practice Problems

1. Construct a truth table for (P → Q) ∧ (Q → R) → (P → R)
2. Prove that the contrapositive is logically equivalent to the original implication
3. Negate: ∀ε > 0, ∃δ > 0: |x - a| < δ → |f(x) - L| < ε
