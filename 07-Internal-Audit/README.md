# Project 7: Mock Internal ISMS & POPIA Audit (Portfolio Capstone)
## MediCare Connect (Pty) Ltd
### ISO/IEC 27001:2022 Clause 9.2 & 10 | ISO 19011 Guidelines | POPIA Section 19 & 55

---

## The Business Problem
After establishing governance policies, risk registers, vendor controls, incident plans, cloud settings, and dashboards (Projects 1–6), MediCare Connect requires independent validation of operating effectiveness prior to an external ISO 27001 certification audit and POPIA regulatory evaluation.

Without an internal audit program aligned to ISO 19011, leadership cannot verify if controls are functioning in practice or merely existing on paper, leaving the enterprise exposed to audit failure and undetected compliance breaches.

---

## 📐 Internal Audit Lifecycle Architecture

```mermaid
flowchart TD
    A[ISO 19011 Audit Program & Charter] --> B[Internal Audit Plan & Scope Definition]
    B --> C[Audit Execution & Evidence Sampling]
    C --> D{Control Testing Evaluation}
    D -->|Compliant| E[Pass & Document Evidence Reference]
    D -->|Deficiency Identified| F[Categorize Finding: Major NC / Minor NC / OFI]
    F --> G[Issue Formal Audit Report to EXCO & CEO]
    G --> H[Corrective Action Plan CAPA Implementation]
    H --> I[Re-Audit & Verification Closure]
