# Jupyter Connector

## Overview

The Jupyter Connector enables integration between EQ Effects and existing notebook-based environments.

---

## Purpose

To allow users to:

- interact with EQ Effects from familiar tools
- leverage existing workflows where appropriate
- transition between systems without disruption

---

## Scope

The connector supports:

- input of mathematical definitions
- retrieval of results
- interaction with structured outputs

---

## Design Principle

The connector is an integration layer, not a core dependency.

EQ Effects operates independently of notebook environments.

---

## Interaction Model

- users may initiate tasks from a notebook
- EQ Effects processes and executes the task
- results are returned in structured form

---

## Limitations

The notebook environment:

- does not replicate the full interface model
- does not replace the three-pane interaction

---

## Role in the System

The Jupyter Connector extends accessibility without altering core system behavior.

---

## Outcome

Users can integrate EQ Effects into existing workflows while maintaining the advantages of governed mathematical execution.
