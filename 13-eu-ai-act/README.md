# 13 — EU AI Act Assessment

**Regulation:** EU AI Act (Regulation (EU) 2024/1689)  
**Platform:** [VerifyWise](https://cyberpros.verifywise.ai/)  
**System:** Meridian Automated Loan Underwriting System

## Summary

Assessment of the Meridian Automated Loan Underwriting System against EU AI Act requirements, including CE Marking readiness and Fundamental Rights Impact Assessment (FRIA).

## Classification

| Field | Value |
|---|---|
| **Risk Classification** | High Risk |
| **Annex** | Annex III — High-Risk AI Systems |
| **Category** | AI systems used to evaluate creditworthiness or establish credit scores |
| **Role** | Deployer |

## Requirements Assessment

| Requirement | Status |
|---|---|
| Risk Management System | In Progress |
| Data and Data Governance | In Progress |
| Technical Documentation | Pending (vendor) |
| Record-Keeping and Logging | Not Started |
| Transparency and User Information | In Progress |
| Human Oversight Measures | In Progress |
| Accuracy, Robustness, Cybersecurity | Pending (vendor) |

## CE Marking Readiness

CE Marking is the responsibility of the provider (CrediSure AI) as the entity that placed the model on the market. As deployer, Meridian must ensure the system is used in accordance with the provider's instructions for use and must implement supplementary human oversight, monitoring, and applicant appeal procedures.

**Current Status:** CE Marking documentation not yet received from CrediSure AI. Requested as part of vendor review.

## Fundamental Rights Impact Assessment (FRIA)

As a deployer of a high-risk AI system in the credit assessment domain, Meridian is required to conduct a FRIA prior to deployment.

| Area | Finding |
|---|---|
| Non-discrimination | Risk of proxy bias through geographic, industry, and credit history variables — mitigation required |
| Right to explanation | Denial reason codes not yet independently validated — remediation required |
| Access to justice | Applicant appeal and reconsideration process not yet established — required before deployment |
| Data protection | PII handling under GDPR requires review in conjunction with CrediSure data processing terms |

**FRIA Status:** In Progress — pending vendor documentation and internal procedure formalization.

*VerifyWise screenshot to be added.*
