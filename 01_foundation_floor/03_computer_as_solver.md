# Computer as Solver

## Overview

EQ Effects separates the definition of a problem from the mechanics of solving it.

Users define **what** is to be computed.  
The system governs **how** it is computed.

---

## Principle

The computer is responsible for solving.

The system ensures that:
- the problem is correctly defined
- execution is appropriately selected
- results are produced with transparency

---

## User Role

The user defines:
- equations and relationships
- constraints and assumptions
- domain context
- precision requirements

The user does not:
- write solver implementations
- manage execution pipelines
- select low-level compute strategies

---

## System Role

The system:
- constructs a mathematical object
- selects appropriate methods and libraries
- maps computation to available resources
- governs execution

---

## Execution Model

Execution is:
- method-agnostic
- resource-aware
- traceable
- reproducible

---

## Implications

- separation of intent and execution
- consistent behavior across domains
- reduced dependency on programming expertise
- increased trust in computational outcomes

---

## Outcome

The computer becomes the execution engine.

The system ensures that execution aligns with defined intent.
