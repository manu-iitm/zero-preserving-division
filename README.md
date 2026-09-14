A Zero-Preserving, Singularity-Sensitive Division Calculus

Research preprint — not peer reviewed.

This repository develops a proposed mathematical framework for extending division to expressions involving zero while preserving ordinary multiplication by zero.

Core idea

Introduce a distinguished idempotent element I, associated with division by zero:

[
I := 1/0
]

with

[
I^2=I,
\qquad
0I=I0=0,
\qquad
a/0:=aI.
]

In particular,

[
0/0=0.
]

The definition of I does not imply that I is an ordinary multiplicative inverse of zero. In particular,

[
I\cdot0=0,
]

not 1.

The key idea: syntax-sensitive division

The proposed calculus treats a denominator as a structured product before ordinary algebraic simplification is performed.

For example, for c\ne0,

[
\frac{x}{0c}:=\frac{xI}{c}.
]

Thus

[
\frac{x}{0\cdot0\cdot c}

\frac{xI^2}{c}

\frac{xI}{c}.
]

Zero factors contribute a singular factor I, while nonzero factors continue to behave as ordinary divisors.

This means that

[
\frac{x}{0c}
]

and

[
\frac{x}{0}
]

may have different meanings, even though ordinary multiplication gives

[
0c=0.
]

Consequently, division cannot be treated simply as an ordinary binary operation on algebraic values while retaining unrestricted substitution of equal expressions.

Underlying algebra

The algebraic carrier can be modeled as

[
A=\mathbb R[I]/(I^2-I).
]

Every element has the form

[
a+bI.
]

It is isomorphic to

[
\mathbb R\times\mathbb R,
]

with

[
a+bI\mapsto(a,a+b).
]

The nonstandard aspect of the proposal is therefore not merely the existence of an idempotent element, but the syntax-sensitive division calculus built on top of this algebraic carrier.

Research questions

The project investigates whether this framework can be given a rigorous formal foundation, including:

- a precise syntax for structured division;
- a well-defined notion of equality;
- terminating and confluent rewrite rules;
- canonical normal forms;
- treatment of nested division;
- characterization of valid algebraic identities;
- and comparison with wheels, meadows, non-involutive meadows, and related systems.

Repository structure

zero-preserving-division/
│
├── README.md
├── LICENSE
│
├── paper/
│   ├── zero-preserving-division.md
│   └── references.md
│
└── formal/
    └── rules.md

Status

This is an ongoing mathematical research project.

The framework is currently a research proposal / preprint and has not been peer reviewed.

The project does not claim that idempotent extensions or division-by-zero systems are themselves new. The intended research question is whether the particular combination of a zero-preserving algebra with a syntax-sensitive division calculus provides a coherent and useful mathematical framework.

See ""paper/zero-preserving-division.md"" (paper/zero-preserving-division.md) for the mathematical development and ""formal/rules.md"" (formal/rules.md) for the proposed formal specification.

Related work

The project is being developed in the context of existing work on:

- Wheels — Carlström
- Meadows — Bergstra, Hirshfeld & Tucker
- Non-involutive meadows — Bergstra & Middelburg
- Common meadows — Bergstra & Ponse
- Other algebraic approaches to division by zero and idempotent extensions.

See ""paper/references.md"" (paper/references.md).

Citation

Until an archival version is available, please cite this repository and its associated preprint.