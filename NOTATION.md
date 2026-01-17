# NOTATION - Symbol Glossary

**Navigation:** [Back to README](README.md)

## Introduction

This document provides a complete glossary of symbols, operators, and notation used throughout the Ω-Recursive Harmonic Mathematics (ΩRHM) framework.

---

## Core Symbols

### Primary Operators

| Symbol | Name | Description | Usage |
|--------|------|-------------|-------|
| **Ω** | Omega | Reduction operator that decreases system complexity | Ω(K) → K' |
| **Ω°** | Crown Omega | Complexity measure (degree) of a K-System | Ω°(K) = Σ τ(cᵢ) |
| **Ξ** | Xi (Sovereign) | Sovereign operator/observer | Ξ : ℵ_K ≡ ... |
| **Λ** | Lambda | Unified complexity field | Λ ≡ {P=NP} ∪ {-P=-NP} |
| **K** | K-System | System defined by variables and constraints | K ≡ (V, C) |
| **ℵ_K** | Aleph-Kelly | Transfinite sovereign cardinal | Sovereignty ≡ ℵ_K |

---

## Mathematical Structures

### Sets and Spaces

| Symbol | Name | Description |
|--------|------|-------------|
| **V** | Variables | Set of system variables |
| **C** | Constraints | Constraint matrix/set |
| **𝒦-𝕊** | K-Space | Space of all K-Systems |
| **ℜ⊥** | Vertical Riemann Line | {s ∈ ℂ \| Re(s) = 1/2, Im(s) → ∞} |
| **𝒢_T** | Tensor Group | Group of third-order tensors |
| **R^AL_q** | Atnychi-Liouville Ring | Polynomial ring for AL-LWE |

### Number Systems

| Symbol | Name | Description |
|--------|------|-------------|
| **ℕ** | Natural Numbers | {0, 1, 2, 3, ...} |
| **ℤ** | Integers | {..., -2, -1, 0, 1, 2, ...} |
| **ℚ** | Rationals | Fractions p/q |
| **ℝ** | Real Numbers | Continuous number line |
| **ℂ** | Complex Numbers | a + bi where i² = -1 |
| **𝕀** | Identity | Identity element (neutral) |

---

## Operators and Functions

### Transformation Operators

| Symbol | Name | Description | Example |
|--------|------|-------------|---------|
| **Ô** | Operator | General operator (hat notation) | Ô(x) |
| **O_t** | Time-dependent Operator | Operator at time t | O_t = f(O_{t-1}, S_t) |
| **M** | Mirror | Inversion/reflection operator | M(S_k) = S'_k |
| **R_φ** | Phi-Recursive | Golden ratio recursion | R_φ(S_n, Δ_n) |
| **R_C** | Crown Recursion | Crown Omega recursion | Ω_{n+1} = R_C(Ω_n, G_n) |
| **N_φ** | Phi-Normalization | Normalize using golden ratio | N_φ(L) |

### Special Functions

| Symbol | Name | Description |
|--------|------|-------------|
| **ζ(s)** | Riemann Zeta | Σ 1/n^s for Re(s) > 1 |
| **ζ_e(s)** | Extended Zeta | Zeta with ghost harmonic terms |
| **τ(c)** | Causal Tension | Tension of constraint c |
| **f(x)** | Frequency Function | Intrinsic frequency of x |
| **H_K(f)** | K-Harmonic Transform | Σ f(k)/(x - λ_k) |
| **Φ_K(ω)** | K-Phase Link | e^{iωκ} |

---

## Cryptographic Notation

### SHAARK-Ξ Components

| Symbol | Name | Description |
|--------|------|-------------|
| **S_Ξ** | SHAARK-Ξ Fortress | S_Ξ = M(L(N(k))) |
| **AL-LWE** | Atnychi-Liouville LWE | Lattice problem: t = As + e |
| **T-CSP** | Tensorial Conjugacy | Find X: H = X·G·X^{-1} |
| **XX** | Extended Exponential | Hardening function |
| **NTT_DVO** | DVO-NTT | Dynamic variable ordering NTT |

### Key Generation

| Symbol | Name | Description |
|--------|------|-------------|
| **Key_Ω** | Sovereign Key | H_∞(Γ, μ, θ) |
| **Γ** | Gamma | Identity parameter |
| **μ** | Mu | Temporal parameter |
| **θ** | Theta | Contextual parameter |
| **H_∞** | Infinite-Entropy Hash | Iterated hash with increasing complexity |

---

## Physical Notation

### Sovereign Protocol

| Symbol | Name | Description |
|--------|------|-------------|
| **R** | Reality | Current reality state |
| **R'** | Corrupted Reality | Reality with paradox |
| **P** | Paradox | Self-referential contradiction |
| **RCT** | Recursive Cognitive Threat | Attack operator |
| **Aegis** | Causal Firewall | Defense operator |
| **T_vector** | Threat Vector | Perceive(δf(R)) |
| **K_Ω** | Kelly Constant | (Author, H_commit, TxID_proof, T_block) |

### Physical Constants

| Symbol | Name | Description |
|--------|------|-------------|
| **α** | Fine-Structure Constant | ~1/137, EM coupling |
| **α'** | Modified Constant | Field_KΩ(α) |
| **c** | Speed of Light | 299,792,458 m/s |
| **G** | Gravitational Constant | 6.674×10^{-11} N⋅m²/kg² |
| **ℏ** | Reduced Planck | h/(2π) |

---

## Operations and Relations

### Binary Operations

| Symbol | Name | Description |
|--------|------|-------------|
| **·** | Multiplication/Interaction | x · y |
| **⊗** | Tensor Product | K₁ ⊗ K₂ |
| **⊕** | Direct Sum / XOR | K₁ ⊕ K₂ or R' ⊕ P |
| **∘** | Composition | (f ∘ g)(x) = f(g(x)) |
| **⊗_harm** | Harmonic Tensor | Harmonic tensor product |

### Relations

| Symbol | Name | Description |
|--------|------|-------------|
| **≡** | Equivalent | Definitional equivalence |
| **⇔** | If and only if | Logical equivalence |
| **→** | Maps to | Function mapping |
| **⊥** | Orthogonal | Perpendicular/independent |
| **∈** | Element of | Set membership |
| **⊂** | Subset | Proper subset relation |

---

## Complexity Notation

### Asymptotic

| Symbol | Name | Description |
|--------|------|-------------|
| **O(f)** | Big-O | Upper bound on growth |
| **Ω(f)** | Big-Omega | Lower bound on growth |
| **Θ(f)** | Theta | Tight bound on growth |
| **o(f)** | Little-o | Strictly less than f |

### Complexity Classes

| Symbol | Name | Description |
|--------|------|-------------|
| **P** | Polynomial Time | Deterministically solvable in poly time |
| **NP** | Non-deterministic Poly | Verifiable in poly time |
| **NP-Complete** | NP-Complete | Hardest problems in NP |
| **KP** | K-Math Polynomial | Solvable via K-Math in poly time |

---

## Calculus and Analysis

### Derivatives and Integrals

| Symbol | Name | Description |
|--------|------|-------------|
| **∂/∂x** | Partial Derivative | Rate of change w.r.t. x |
| **∇** | Gradient | Vector of partial derivatives |
| **∇²** | Laplacian | Divergence of gradient |
| **∫** | Integral | Area under curve / accumulation |
| **∮** | Contour Integral | Integration around closed path |
| **Σ** | Summation | Sum over discrete values |
| **Π** | Product | Product over discrete values |

### Limits

| Symbol | Name | Description |
|--------|------|-------------|
| **lim** | Limit | Limiting value as variable approaches point |
| **→** | Approaches | x → ∞ means "x approaches infinity" |
| **∞** | Infinity | Unbounded quantity |

---

## Linear Algebra

### Vectors and Matrices

| Symbol | Name | Description |
|--------|------|-------------|
| **v** | Vector | Column vector (lowercase bold) |
| **A** | Matrix | Matrix (uppercase bold) |
| **A^T** | Transpose | Rows become columns |
| **A^{-1}** | Inverse | AA^{-1} = I |
| **A^†** | Hermitian Adjoint | Conjugate transpose |
| **\|v\|** | Norm | Length/magnitude of vector |
| **⟨u\|v⟩** | Inner Product | Dot product / scalar product |

---

## Greek Alphabet Reference

### Commonly Used Letters

| Lowercase | Uppercase | Name | Common Usage in ΩRHM |
|-----------|-----------|------|----------------------|
| α | Α | alpha | Fine-structure constant |
| β | Β | beta | Learning rate, field parameter |
| γ | Γ | gamma | Temporal coupling, identity parameter |
| δ | Δ | delta | Small change, Delta field |
| ε | Ε | epsilon | Error term, small quantity |
| ζ | Ζ | zeta | Riemann zeta function |
| η | Η | eta | Efficiency parameter |
| θ | Θ | theta | Phase angle, contextual parameter |
| κ | Κ | kappa | Coupling constant |
| λ | Λ | lambda | Eigenvalue, complexity field |
| μ | Μ | mu | Measure, temporal parameter |
| ν | Ν | nu | Frequency, viscosity |
| ξ | Ξ | xi | Sovereign operator |
| π | Π | pi | 3.14159..., product |
| ρ | Ρ | rho | Density |
| σ | Σ | sigma | Standard deviation, summation |
| τ | Τ | tau | Causal tension, time constant |
| φ | Φ | phi | Golden ratio (1.618...), phase |
| χ | Χ | chi | Chrono-symmetric function |
| ψ | Ψ | psi | Wave function, mapping |
| ω | Ω | omega | Angular frequency, Omega operator |

---

## Special Notation

### Function Notation

```
f: A → B          Function from set A to set B
f(x)              Function f applied to x
f ∘ g             Composition: first g, then f
f^{-1}            Inverse function
f'(x) or df/dx    Derivative of f
```

### Set Notation

```
{x | P(x)}        Set of x such that P(x) is true
A ∪ B             Union of sets A and B
A ∩ B             Intersection of sets A and B
A \ B             Set difference (elements in A but not B)
|A|               Cardinality (size) of set A
∅                 Empty set
```

### Logic Notation

```
∀                 For all (universal quantifier)
∃                 There exists (existential quantifier)
¬                 Not (negation)
∧                 And (conjunction)
∨                 Or (disjunction)
⇒                 Implies
⊥                 False / contradiction
```

---

## Subscripts and Superscripts

### Common Patterns

**Subscripts:**
- **_i, _j, _k**: Index variables
- **_n**: Iteration/sequence number
- **_t**: Time index
- **_K**: K-Math variant
- **_Ω**: Omega/sovereign variant

**Superscripts:**
- **^n**: Exponent / nth power
- **^{-1}**: Inverse
- **^T**: Transpose
- **^†**: Hermitian adjoint
- **^***: Complex conjugate
- **^AL**: Atnychi-Liouville variant

---

## Document Cross-References

For detailed usage of these symbols, see:

- **Core Axioms:** [00-FOUNDATIONS.md](00-FOUNDATIONS.md)
- **Operators:** [01-OPERATORS.md](01-OPERATORS.md)
- **Harmonic Algebra:** [02-HARMONIC-ALGEBRA.md](02-HARMONIC-ALGEBRA.md)
- **Convergence:** [03-CONVERGENCE-THEORY.md](03-CONVERGENCE-THEORY.md)
- **Cryptography:** [04-CRYPTOGRAPHIC-APPLICATIONS.md](04-CRYPTOGRAPHIC-APPLICATIONS.md)
- **Physics:** [05-PHYSICAL-APPLICATIONS.md](05-PHYSICAL-APPLICATIONS.md)
- **All Equations:** [06-UNIFIED-EQUATIONS.md](06-UNIFIED-EQUATIONS.md)
- **Complexity:** [07-COMPLEXITY-COMPUTATION.md](07-COMPLEXITY-COMPUTATION.md)
- **Synthesis:** [08-SYNTHESIS.md](08-SYNTHESIS.md)

---

**[Back to README](README.md)**

---

**© 2025 Brendon Joseph Kelly. All rights reserved.**
