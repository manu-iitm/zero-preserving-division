# A Zero-Preserving, Singularity-Sensitive Division Calculus

**Research preprint — not peer reviewed**

This repository develops a proposed mathematical framework for extending division to expressions involving zero while preserving ordinary multiplication by zero.

## Core idea

The framework introduces a distinguished singular element `I` associated with division by zero:

- `I² = I`
- `0I = I0 = 0`
- `a / 0 = aI`

Therefore:

- `0 / 0 = 0`
- division by a nonzero denominator behaves normally
- multiplication by zero remains ordinary

The key feature is that **division is syntax-sensitive**.

For example, when `c ≠ 0`:

```text
x / (0c) = xI / c