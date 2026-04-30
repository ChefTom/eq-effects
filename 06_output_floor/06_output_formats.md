# Output Formats

## Overview

EQ Effects separates the result from its presentation format.

The system first produces a structured Rich Result Package. Output formats are then generated as projections from that package.

This distinction is important.

The result is the authoritative artifact.  
The format is how that artifact is presented, shared, or reused.

---

## Primary Output

The primary output is a structured result containing:

- final values or symbolic results
- process record
- assumptions and constraints
- validation and warnings
- precision information
- execution context
- replay data

This structured result is the source for all exported formats.

---

## Supported Output Categories

EQ Effects may emit outputs in several categories:

### Human-Readable Reports

- Markdown
- LaTeX / TeX
- PDF generated from LaTeX or another renderer

### Machine-Readable Artifacts

- JSON
- YAML
- structured result bundles

### Interactive Outputs

- interface views
- contextual result panels
- notebook-compatible summaries

### Mathematical Outputs

- symbolic expressions
- rendered equations
- equation graphs
- variable tables

---

## LaTeX and TeX Support

LaTeX or TeX is a primary target for formal mathematical reporting.

It is suitable for:

- academic papers
- technical reports
- reproducible research documents
- formal engineering documentation

However, LaTeX is not the internal truth of the system.

LaTeX is a rendered projection of the structured result.

---

## Design Principle

EQ Effects should not lock results into one presentation format.

A single Rich Result Package may generate:

- a readable report
- a LaTeX document
- a PDF
- a machine-readable result bundle
- a notebook summary
- a user-interface view

---

## Outcome

Output formats make results portable, shareable, publishable, and reusable without changing the underlying result.
