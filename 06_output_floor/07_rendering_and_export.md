# Rendering and Export

## Overview

Rendering and Export define how EQ Effects turns structured outputs into usable external artifacts.

The system does not treat a rendered document as the result itself.

Instead:

> Structured result first.  
> Rendered format second.

---

## Rendering Pipeline

The general output path is:

1. Rich Result Package is produced
2. Output format is selected
3. Renderer transforms structured content into the target format
4. Export artifact is created
5. Export record is attached to the process history

---

## Render Targets

Potential render targets include:

- Markdown reports
- LaTeX / TeX documents
- PDF reports
- JSON or YAML bundles
- notebook-compatible cells or summaries
- interface panels

---

## Report Generation

Reports should include:

- problem statement
- interpreted intent
- mathematical object summary
- equations and variables
- assumptions and constraints
- selected method summary
- validation and warnings
- final results
- replay reference

---

## Rust-Friendly Rendering

For a Rust implementation, rendering should remain simple and controlled.

A practical approach is:

- structured result data represented internally
- templates for report formats
- renderer modules for Markdown, LaTeX, and JSON
- optional PDF generation from LaTeX

This avoids making LaTeX or any external format the core system representation.

---

## Format Projection

Each output format is a projection.

Examples:

- Rich Result Package → Markdown report
- Rich Result Package → LaTeX report
- Rich Result Package → JSON bundle
- Rich Result Package → UI result panel
- Rich Result Package → Jupyter-compatible summary

The same result can be viewed through different formats without changing its identity.

---

## Export Record

Each export should record:

- selected format
- render timestamp
- source result identity
- included sections
- warnings or omissions
- version of the rendering template

---

## Outcome

Rendering and Export allow EQ Effects results to move between people, tools, papers, reports, notebooks, and systems while preserving the structured source of truth.
