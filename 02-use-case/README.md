# #02 – Use Case Registration (EU AI Act)

**Use Case:** Meridian Automated Loan Underwriting System
**Classification:** High Risk
**Applicable Regulation:** EU AI Act

## Summary

Registered the Meridian Automated Loan Underwriting System as a high-risk AI use case under the EU AI Act.

| Field | Value |
|---|---|
| **Use Case** | Meridian Automated Loan Underwriting System |
| **AI Risk Classification** | High Risk |
| **Role** | Deployer |
| **Target Industry** | Financial Services / Small Business Lending |
| **Approval Workflow** | High-Risk AI Use Case Approval Workflow |
| **Applicable Regulation** | EU AI Act |

The system qualifies as high-risk because it affects access to credit and may create financial, legal, fairness, explainability, and consumer harm risks.

---

## Detailed System Profile & Intake Record

### 1. System Overview & Context
* **Operational Scale:** Designed to process incoming credit applications continuously, driving an estimated 94% automation rate for final approve/deny decisions, with only 6% routed to manual human review.
* **Core Model Engine:** CrediSure Credit Decision Engine v2.3 (Third-Party Vendor)

### 2. Regulatory & Risk Context
* **EU AI Act Justification:** The system falls under Annex III classification criteria as an AI system used to evaluate the creditworthiness of natural persons or businesses, directly impacting their access to essential financial resources and credit opportunities.
* **NIST AI RMF Profile:** High Impact (Governance priority driven by potential fairness, transparency, and disparate impact concerns).

### 3. Stakeholder & Data Profile
* **Input Datasets:** Small Business Loan Underwriting Dataset, consisting of historical credit scores, business cash-flow metrics, industry classification codes, geographic operational data, and business age.
* **Affected Stakeholders:** Small business loan applicants whose access to critical capital is determined automatically by the system’s underwriting logic.

### 4. Initial Governance Assessment & Limitations
* **Vendor Dependency:** High reliance on the third-party model vendor for core transparency logs, baseline data drift metrics, and weights validation.
* **Explainability Baseline:** Current system configuration provides sparse denial codes, creating a significant compliance gap under consumer financial protection rules and the EU AI Act’s explanation requirements for high-risk systems.

---

### System Interface Capture
![AI Use Case Profiling](/screenshots/02-use-case.png)