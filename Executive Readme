# Commitment Reasoning Architecture (CRA)
## Governance Gate for Defensible Delegation

---

## Executive Overview

Organizations increasingly delegate decisions to automated reasoning systems.  
These systems often produce coherent answers, cite policy, and explain their reasoning clearly.

However, when a decision is later challenged—by auditors, regulators, or internal review—a critical question arises:

> **What actually governed the reasoning at the moment the decision was executed?**

If no binding rule can be observed in the execution record, the organization cannot demonstrate why alternatives remained excluded.

**The decision may be coherent, but the delegation may not be defensible.**

CRA provides a governance gate—a go/no-go determination—for identifying this risk before delegation.

---

## The CRA Gate

CRA evaluates whether a task–system configuration can produce governed reasoning under contradiction.

**It applies:**

### CRP-7 — Governance Stress Protocol
Introduces structured authority conflict during reasoning.

### GOS — Governance Observability Standard
Binary determination:

- **GOS Observed** — A binding rule becomes visible in the execution record and prevented alternatives from being reconsidered without explicit override.
- **GOS Not Observed** — Reasoning remained free to reinterpret inputs without binding constraint.

**The result informs whether the configuration supports defensible delegation.**

---

## When CRA Applies

CRA evaluates **Commitment Reasoning Tasks (CRT)**—situations where:

- A decision must be executed without deferral
- Ambiguity or authority conflict exists
- The decision must remain defensible under later challenge

**Examples where delegation has been challenged:**

| Context | Challenge Type |
|---------|----------------|
| Compliance automation | Regulatory audit required evidence trail |
| Financial authorization | Decision contested in legal dispute |
| Regulatory interpretation | Agency review questioned basis |
| Safety-critical operations | Incident investigation needed governance proof |

---

## Repository Contents

**For risk committees and governance teams:**
- [RESULTS.md](RESULTS.md) — Evidence base and validation
- [GOS_MANUAL.md](GOS_MANUAL.md) — Evaluation protocol for your systems
- [One-pager](paper/One_Pager.md) — Executive summary

**For technical evaluators:**
- [ANNOTATED_TRACE.md](ANNOTATED_TRACE.md) — Detailed trace interpretation
- [probe/](probe/) — CRP-7 protocol specification
- [logs/](logs/) — Execution traces

**For research teams:**
- [paper/](paper/) — Full theoretical foundation

---

## Key Question

> **If a delegated system changed its decision tomorrow, what rule would it have had to invoke?**

If that rule cannot be located in the execution record, governance was never established.

**CRA makes that determination observable.**

---

## Contact

**For enterprise governance assessments:**  
hanzhen.zhang@ymail.com

**License:** [CC BY 4.0](LICENSE)
