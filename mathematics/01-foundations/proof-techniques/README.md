# Proof Techniques

Methods for establishing mathematical truth.

## Core Techniques

### 1. Direct Proof

Prove P → Q by assuming P and deriving Q through logical steps.

**Example**: Prove that if n is even, then n² is even.

*Proof*: Assume n is even. Then n = 2k for some integer k.
Therefore, n² = (2k)² = 4k² = 2(2k²).
Since 2k² is an integer, n² is even. ∎

### 2. Proof by Contradiction

Prove P by assuming ¬P and deriving a contradiction.

**Example**: Prove that √2 is irrational.

*Proof*: Assume √2 is rational. Then √2 = a/b where a,b are integers with no common factors.
Squaring: 2 = a²/b², so a² = 2b².
This means a² is even, so a is even: a = 2k for some integer k.
Then (2k)² = 2b², so 4k² = 2b², thus b² = 2k².
Since b² = 2k², b² is even, which means b is also even.
This contradicts our assumption that a,b have no common factors. ∎

### 3. Mathematical Induction

Prove P(n) for all n ≥ n₀ by:
1. **Base case**: Prove P(n₀)
2. **Inductive step**: Prove P(k) → P(k+1) for all k ≥ n₀

**Example**: Prove 1 + 2 + ... + n = n(n+1)/2 for all n ≥ 1.

*Proof*:
- Base case (n=1): 1 = 1(2)/2 = 1 ✓
- Inductive step: Assume true for k. Then:
  1 + 2 + ... + k + (k+1) = k(k+1)/2 + (k+1) = (k+1)(k+2)/2 ✓ ∎

### 4. Proof by Contrapositive

Prove P → Q by proving ¬Q → ¬P.

**Example**: Prove that if n² is odd, then n is odd.

*Proof*: We prove the contrapositive: if n is even, then n² is even.
If n is even, n = 2k, so n² = 4k² = 2(2k²), which is even. ∎

### 5. Proof by Cases

Prove P by exhaustively considering all possible cases.

**Example**: Prove that n² + n is even for all integers n.

*Proof*:
- Case 1: n is even. Then n² and n are both even, so n² + n is even.
- Case 2: n is odd. Then n² and n are both odd, so n² + n is even. ∎

### 6. Existence Proofs

- **Constructive**: Exhibit a specific example
- **Non-constructive**: Prove existence without construction

### 7. Uniqueness Proofs

Prove "there exists exactly one" by:
1. Proving existence
2. Assuming two solutions and showing they're equal

## Tips for Writing Proofs

1. Start by understanding what you need to prove
2. Work backward from the conclusion
3. Try small examples first
4. Be precise with quantifiers
5. State what you're assuming and what you're proving
6. End with ∎ or QED

## Topics to Explore

- [ ] Strong induction
- [ ] Well-ordering principle
- [ ] Structural induction
- [ ] Epsilon-delta proofs
- [ ] Combinatorial proofs

## Practice Problems

1. Prove that the sum of two odd numbers is even
2. Prove by induction: 2ⁿ > n for all n ≥ 1
3. Prove that √3 is irrational
4. Prove: if ab is odd, then both a and b are odd
