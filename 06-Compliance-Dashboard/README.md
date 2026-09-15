# Project 6: Executive Compliance Dashboard
## MediCare Connect (Pty) Ltd
### ISO 27001 · POPIA · Risk · TPRM · IR · SOC 2 Cloud Evidence

---

## The Business Problem
After completing ISMS scoping, risk assessment, vendor governance,
incident response, and cloud control evidence, management still lacked
a single view of compliance posture.

Executives do not read control matrices for status.
They need a dashboard that answers:
- What is red right now?
- What improved this month?
- What blocks audit readiness?

---

## 📐 Dashboard Architecture

```mermaid
flowchart LR
    A[Project 1 Controls] --> E[Executive Dashboard]
    B[Project 2 Risks] --> E
    C[Project 3 Vendors] --> E
    D[Project 4 Incidents] --> E
    F[Project 5 Cloud Evidence] --> E
    E --> G[CEO / IO / Audit Decisions]
