# Reference Review Walkthrough

## Overview

This walkthrough demonstrates how EQ Effects may support a reference-based review workflow.

The example involves a professor introducing students to a probable solution method and asking them to propose novel applications.

Students then compare their proposed uses against scientific or mathematical literature.

---

## Step 1: User Defines the Working Idea

A student begins with a conceptual description:

> I want to apply this solution method to a different class of boundary-condition problems.

The student may also define equations, variables, or constraints through the Formula Builder.

---

## Step 2: Reference Material Is Added

The student provides supporting material such as:

- a journal PDF
- a scanned classroom handout
- a textbook excerpt
- notes from a lecture

The material is treated as reference context, not as the user’s primary problem definition.

---

## Step 3: System Extracts Reference Context

EQ Effects identifies:

- equations
- assumptions
- constraints
- method descriptions
- stated limitations
- domain of application

Extraction confidence is recorded.

---

## Step 4: User Work Is Compared Against the Reference

The system compares:

- assumptions
- equation structure
- boundary conditions
- method selection
- proposed use case

---

## Step 5: Reference Comparison Report Is Produced

The report includes:

- what aligns
- what diverges
- what is missing
- what appears potentially novel
- what requires further review

---

## Step 6: User Refines the Work

The student may update:

- assumptions
- variables
- boundary conditions
- intended application

The system updates the Mathematical Object and comparison report.

---

## Outcome

This workflow helps users move from:

> reading a method

to:

> applying, testing, and comparing mathematical ideas against existing literature

without forcing the user to begin by writing code.
