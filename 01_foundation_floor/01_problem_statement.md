# Problem Statement

## Overview

Current computational systems impose structural constraints on how mathematical problems are expressed and solved.

These constraints affect both usability and correctness.

---

## Core Problem

Users must translate mathematical intent into:
- programming languages
- solver-specific syntax
- execution pipelines

This translation introduces friction and loss of fidelity.

---

## Key Issues

### 1. Abstraction Loss

Mathematical reasoning is expressed in:
- equations
- conceptual relationships
- domain-specific language

Programming environments require:
- procedural constructs
- data structures
- implementation detail

The result is a loss of alignment between intent and execution.

---

### 2. Forced Modality

Users must adopt:
- specific languages (e.g., Python, MATLAB)
- specific tools or frameworks
- specific solver interfaces

This restricts flexibility and accessibility.

---

### 3. Hidden Execution

Execution details are often:
- implicit
- difficult to trace
- not fully documented in outputs

This reduces transparency and reproducibility.

---

### 4. Fragmented Workflow

Users must manage:
- input definition
- method selection
- execution control
- result interpretation

These steps are disconnected and require manual coordination.

---

## Consequences

- increased complexity in modeling
- reduced accessibility for domain experts
- difficulty validating results
- limited reproducibility

---

## Problem Definition

There is no unified system that allows users to:

- express mathematical intent directly
- preserve that intent through execution
- obtain transparent, structured results

---

## Outcome

The problem is not computational capability.

The problem is **how computation is defined, governed, and understood**.
