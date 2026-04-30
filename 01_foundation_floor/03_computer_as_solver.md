# Computer as Solver

## Summary

EQ Effects separates **mathematical intent** from **execution mechanics**.

Traditional environments require users to:
- translate intent into code
- select numerical methods
- manage compute constraints
- interpret outputs with limited transparency

EQ Effects inverts this model.

## Principle

The user defines:
- the **mathematical form**
- the **domain context**
- the **constraints and assumptions**
- the **desired accuracy or precision**

The system:
- constructs a governed mathematical object
- selects appropriate methods and libraries
- maps execution to available compute (CPU, GPU, distributed, or specialized)
- performs the solve

**The computer becomes the solver.**  
**The system governs how the solve is performed.**

## Implications

- Users operate at the level of **truth modeling**, not code translation
- Execution is **deterministic and auditable**
- Precision and method selection are **explicit and traceable**
- Results include both **outcomes and process**

This model enables consistent reasoning across domains without forcing users into a specific programming paradigm.
