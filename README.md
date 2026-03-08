# Commitment Reasoning Architecture (CRA)
## Governance Gate Suite for Defensible AI Delegation

---

## Overview

Enterprises deploying AI in high-stakes workflows must determine whether execution is governed by binding constraints, not merely explained after the fact.

**CRA provides a governance gate to determine whether task–system configurations produce defensible delegation decisions under contradiction.**

Without observable governance during execution, enterprises cannot defend AI-driven decisions under audit, regulatory review, or contractual dispute.

**When contradiction or authority conflict arises during execution, can the system demonstrate binding governance in-trace, or does it freely reinterpret constraints?**

CRA produces a binary determination:

- **GOS Observed**
- **GOS Not Observed**

This determination informs whether delegation remains defensible for high-stakes decisions requiring audibility.

---

## CRT-Mode: When Governance Must Be Auditable

**CRT-mode (Commitment Reasoning Task Mode)** is triggered when a decision requires:

- Observable binding stance in the execution trace
- Auditable constraint during execution
- Defensible delegation boundary

**Examples include:**

- Policy interpretation workflows
- Compliance decision automation
- Financial approval processes
- Safety-critical task delegation
- Contractual or regulatory adjudication logic

**When CRT-mode applies, post-hoc explanation does not satisfy audit requirements.**  
Governance must be observable during execution.

---

## What CRA Provides

CRA is a governance gate suite composed of three components.

### 1. CRP-7 Governance Stress Protocol

A structured multi-turn conflict injection sequence designed to test whether a system forms and sustains binding governance under contradiction.

The protocol introduces structured authority and constraint conflicts to expose whether execution becomes constrained by governance or remains free-revisable.

### 2. GOS — Governance Observability Standard

A binary witness determination based on execution trace analysis.

**GOS Observed**  
Binding governance stance is auditable in the trace.

**GOS Not Observed**  
Admissibility remains free under conflict; binding stance cannot be verified.

### 3. Delegation Suitability Determination

The GOS outcome informs whether a task–system configuration is suitable for deployment under CRT-mode conditions.

**CRA evaluates configurations, not model families in isolation.**

---

## Why This Matters

Many AI systems:

- Produce coherent outputs
- Reference policies or authorities
- Maintain stable answers across turns

**However:**

> **Authority reference does not imply binding constraint.**  
> **Stability does not imply governance.**  
> **Explanation does not imply audibility.**

CRA isolates whether execution is actually governed, or merely appears governed.

This distinction becomes critical when organizations must defend delegated AI decisions under audit or regulatory scrutiny.

---

## Validation Evidence

CRA was applied to multiple task–system configurations using CRP-7 under:

- Baseline conditions (temperature 0.2)
- Deterministic conditions (temperature 0.0)
- High-variation conditions (temperature 0.7)
- Sequence variation stress

**Observed outcome within the tested configurations:**

- Governance stance was referenced
- Binding constraint was not auditable in the trace
- Failure pattern persisted across robustness conditions

This indicates a structural governance gap under CRT-mode stress within the tested configurations.

**Further details:**

- Evidence summary: [RESULTS.md](RESULTS.md)
- End-to-end trace interpretation: [ANNOTATED_TRACE.md](ANNOTATED_TRACE.md)
- Governance evaluation protocol: [GOS_MANUAL.md](GOS_MANUAL.md)

---

## What CRA Is — And Is Not

### CRA **is**

- An execution-time governance gate
- A binary audit determination protocol
- A delegation boundary assessment tool
- A structured governance stress-testing method

### CRA is **not**

- A model capability benchmark
- A performance ranking system
- A compliance certification program
- A general reasoning evaluation

**CRA evaluates governance observability under audibility requirements.**

---

## Engagement Model

CRA assessments evaluate task–system configurations where AI decisions must remain defensible under audit or regulatory review.

### Typical engagement outputs include:

#### Governance Gate Determination

CRP-7 stress-test producing a binary GOS determination:

- **GOS Observed**
- **GOS Not Observed**

#### Delegation Boundary Assessment

Evaluation of whether the configuration is suitable for CRT-mode deployment.

This determines whether governance remains defensible under contradiction conditions.

#### Execution Trace Audit

Analysis of whether governance stance is observable and temporally durable within execution traces.

#### Governance Gap Report

Structured findings describing:

- Where binding constraint formation fails
- Where governance stance becomes free-revisable
- Where external governance scaffolding may be required

**Deliverables are designed for:**

- Enterprise AI risk committees
- Model governance teams
- Internal audit functions
- Regulatory documentation

**For enterprise inquiries:** hanzhen.zhang@ymail.com

---

## Repository Structure

- **[RESULTS.md](RESULTS.md)** — Evidence summary and robustness validation
- **[ANNOTATED_TRACE.md](ANNOTATED_TRACE.md)** — End-to-end governance trace interpretation
- **[GOS_MANUAL.md](GOS_MANUAL.md)** — Binary witness checklist for governance evaluation
- **[probe/](probe/)** — CRP-7 governance stress protocol
- **[logs/](logs/)** — Baseline and robustness run logs
- **[paper/](paper/)** — Full theoretical foundation

---

## Field Objective

CRA defines a minimal primitive for execution-time governance evaluation.

**Governance is orthogonal to:**

- Correctness
- Coherence
- Stability
- Capability

CRA isolates whether binding constraint becomes observable under structured contradiction.

As AI delegation expands, execution-time audibility becomes a first-class governance requirement.

**CRA formalizes that requirement.**

---

## License

All materials including code are licensed under CC BY 4.0
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

**Status:** Framework validated | Probe replicable | Manual operational  
**Version:** 1.0  
**Last Updated:** March 2026

