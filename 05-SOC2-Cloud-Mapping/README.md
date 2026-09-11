# Project 5: SOC 2 Cloud Control Mapping
## MediCare Connect (Pty) Ltd
### AWS Free Tier × SOC 2 TSC × ISO 27001:2022 × POPIA

## The Business Problem
Policies and risk registers are not enough. Auditors and customers ask for technical proof that cloud controls operate.

## Architecture

```mermaid
flowchart TD
    A[AWS Free Tier Sandbox] --> B[Configure MFA Logging Encryption Network Controls]
    B --> C[Capture Evidence Screenshots]
    C --> D[Map to SOC 2 ISO 27001 POPIA]
    D --> E[Control Matrix and Implementation Report]
