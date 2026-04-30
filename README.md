# EQ Effects

**EQ Effects** is a documentation-first architecture for a governed mathematical execution environment.

It defines a system where:
- scientists and engineers express intent in their own conceptual language
- formal mathematics is constructed alongside that intent
- the computer performs the solve across available compute resources
- the system returns a **rich, auditable result package**—not just an answer

This repository contains **no implementation code**.  
It is a **public, non-proprietary reading path** describing the system’s structure, terminology, and behavior.

## What This Is

A structured specification for:
- flexible, multipath input (conversation + structured math)
- contextual understanding (assumptions, units, constraints)
- governed mathematical objects
- execution across heterogeneous compute
- rich outputs with process transparency and replayability

## What EQ Effects Is Not
EQ Effects is not a numerical solver, not a programming language, and not an implementation repository. It does not contain proprietary internals.

## Core Principle
The software is not the solver. The computer is the solver. EQ Effects governs the path from intent to execution-ready form and transparent outcomes.

# Reading Path

EQ Effects is organized as a layered system (“floors”).  
Each floor builds on the previous to move from **intent → form → execution → result**.

Recommended order:
1. `00_overview/00_reading_path.md`
2. `01_foundation_floor/00_foundation_floor.md`
3. `02_intake_floor/00_intake_floor.md`
4. `03_context_floor/00_context_floor.md`
5. `04_form_floor/00_form_floor.md`
6. `05_execution_floor/00_execution_floor.md`
7. `06_output_floor/00_output_floor.md`
8. `07_interface_floor/00_interface_floor.md`
9. `08_governance_floor/00_governance_floor.md`
10. `09_examples/00_examples_index.md`

The system is designed to be read linearly, but each floor stands on its own.

## Documentation Boundary
This is a no-code, public-documentation repository. It is designed for scientists, mathematicians, engineers, academic partners, funding stakeholders, and compute or hardware collaborators.
