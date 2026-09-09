# Project 3: Third-Party Vendor Risk Assessment & POPIA Operator Governance
## MediCare Connect (Pty) Ltd
### ISO 27001:2022 Controls A.5.19 – A.5.22 | POPIA Section 20 & 21 | Healthcare Sector
## 📐 Third-Party Risk Management (TPRM) Governance Workflow

```mermaid
graph TD
    A[New Vendor Request] --> B[Criticality Screening: Tier 1, 2, or 3]
    B --> C[Issue 25-Question VSAQ & Evidence Request]
    C --> D[Evaluate 5 Security Domains]
    D --> E{Overall Score Benchmark}
    E -->|Score < 70%| F[Conditional Approval + Corrective Action Plan]
    E -->|Score >= 70%| G[Standard Onboarding]
    F --> H[Execute Mandatory POPIA Section 21 Operator Agreement]
    G --> H
    H --> I[24-Hour Breach Alert Clause Activated]

---

## The Business Problem
Risk Register item RSK-007 identified that MediCare Connect shares special personal information (patient health records and lab results) with third-party SaaS vendors and clinical partners without formal security due diligence or POPIA Section 21 Operator Agreements. 

Under South African law, a breach at a vendor's facility exposes MediCare Connect to joint liability, regulatory enforcement, and administrative fines up to R10 million under POPIA.

---

## What This Project Delivers
A complete Third-Party Risk Management (TPRM) framework including:
- Vendor Security Risk Management Policy & Classification Matrix
- 25-Question Vendor Security Assessment Questionnaire (VSAQ) with weighted scoring
- Legal POPIA Section 21 Operator Agreement (Data Processing Agreement) Template
- Full Security Assessment & Risk Scorecard for a critical vendor (*PathLab SA (Pty) Ltd*)
- Remediation Plan for high-risk vendor deficiencies

---

## Vendor Ecosystem Assessed
| Vendor Name | Service Provided | Data Shared | Risk Tier | POPIA Operator Agreement Status |
|-------------|------------------|-------------|-----------|---------------------------------|
| **PathLab SA (Pty) Ltd** | Pathology Integration API | Patient Blood & Lab Diagnostic Results | **Tier 1 (Critical)** | ❌ Missing (Remediated in Project) |
| **CloudMed Systems** | SaaS Patient Record System | Full Patient Medical History & Billing | **Tier 1 (Critical)** | ✅ Executed |
| **PharmaLink SA** | Digital e-Prescriptions | Patient Names, ID Numbers, Medications | **Tier 2 (High)** | 🔄 Under Review |

---

## Framework Alignment
- **ISO/IEC 27001:2022 Controls:**
  - `A.5.19` Information security in supplier relationships
  - `A.5.20` Addressing information security within supplier agreements
  - `A.5.21` Managing information security in the ICT supply chain
  - `A.5.22` Monitoring, review and change management of supplier services
- **POPIA (Act 4 of 2013):**
  - `Section 20` Authorization of Operator & confidentiality duties
  - `Section 21` Mandatory written contract requiring security safeguards
  - `Section 22` Mandatory notification of security compromises by Operator to Responsible Party

---

## Project Documents
| File | Format | Description |
|------|--------|-------------|
| `01-Vendor-Risk-Management-Policy` | Google Doc / PDF | Governance policy, tiering model, and evaluation workflow |
| `02-POPIA-Section-21-Operator-Agreement` | Google Doc / PDF | Legal DPA template mandating security controls & breach reporting |
| `03-Vendor-Assessment-Report-PathLab` | Google Doc / PDF | Executive assessment report for PathLab SA API integration |
| `04-Vendor-Risk-Workbook` | Google Sheet / XLSX | Live Vendor Inventory, 25-Q VSAQ, and Vendor Scorecard |

---

## Key Outcome
Remediated **RSK-007** by establishing mandatory security evaluations and POPIA Section 21 contracts across all Tier 1 vendors, reducing third-party risk exposure from **HIGH (Score 15)** to **MEDIUM (Score 8)**.

---
*Portfolio project by Patrick Mohlala*  
*GRC Analyst | Johannesburg, South Africa*
