# Cyber Pros AI Governance Portfolio Project: Automated Loan Underwriting System

**Practitioner:** Ramamurthy R  
**GitHub:** [github.com/ram0516](https://github.com/ram0516)  
**Platform:** [VerifyWise](https://www.verifywise.ai)  
**Training Platform:** [Cyberpros Training](https://maven.com/cyberpros/ai-governance-risk-compliance-practitioner)  
**Frameworks Applied:** EU AI Act · NIST AI RMF · ISO/IEC 42001  
**Status:** Completed — May 2026

---

## Executive Summary

I served as the **AI Governance Lead** for a fictional high-risk AI governance assessment involving Meridian Financial Services, a mid-sized financial services company piloting an automated loan underwriting system.

The system uses a third-party AI model, **CrediSure Credit Decision Engine v2.3**, to evaluate small business loan applications and produce one of three outcomes:

- Auto-approve
- Auto-deny
- Route to manual review

Because approximately **94% of applications are processed automatically** and the system affects access to credit, I classified this as a **high-risk AI use case** requiring governance review before production deployment.

My final recommendation was:

> **Proceed with conditions. Meridian should not approve unrestricted production deployment until fairness testing, proxy-bias review, reason code validation, human oversight triggers, appeal procedures, vendor evidence review, monitoring thresholds, and governance committee approval are completed.**

---

## Frameworks Applied

| EU AI Act | NIST AI Risk Management Framework | ISO/IEC 42001 |
|---|---|---|
| High-risk AI classification | Governance roles and responsibilities | AI management system scope |
| Fundamental Rights Impact Assessment | System context and intended use | Organizational roles and responsibilities |
| Human oversight | Risk measurement and testing evidence | AI risk assessment |
| Logging | Risk prioritization and treatment | AI risk treatment |
| Explanation to affected persons | Human-AI oversight | Management review |
| Appeal and contestability | | AI system lifecycle management |
| Deployment conditions | | Third-party AI risk management |

This portfolio demonstrates my ability to perform practical AI governance work for a high-risk AI system.

Specifically, this project shows that I can:

- Lead an AI governance review for a high-risk AI use case
- Document an AI system profile and governance intake record
- Identify and assess AI risks related to fairness, explainability, automation, vendor risk, and human oversight
- Apply EU AI Act, NIST AI RMF, and ISO/IEC 42001 concepts in a practical way
- Review third-party AI model and vendor governance concerns
- Design human oversight, exception review, and appeal procedures
- Prepare an executive-ready production readiness recommendation
- Use AI governance tooling to organize evidence, risks, policies, and framework assessments

---

## Central Governance Question

This portfolio answers one central question:

> **Should Meridian Financial Services approve production deployment of a 94% automated AI loan underwriting system?**

My answer:

> **Not for unrestricted production deployment. The system may proceed only with conditions because the current governance evidence does not fully support safe, fair, explainable, accountable, and well-monitored deployment.**

---

## Portfolio Artifacts

| Artifact | Purpose | Link |
|---|---|---|
| AI Governance Intake Record | Documents system purpose, users, affected groups, data, vendor, and risk classification | [Read (.md)](assets/documents/1.AI_Governance_Intake_Record.md) · [Download (.docx)](assets/documents/1.AI_Governance_Intake_Record.docx) |
| AI Risk Register and Mitigation Summary | Documents key AI risks, severity, controls, residual risk, and recommendations | [Read (.md)](assets/documents/3.AI_Risk_Register_Mitigation_Summary.md) · [Download (.docx)](assets/documents/3.AI_Risk_Register_Mitigation_Summary.docx) |
| Vendor and Model Governance Review | Evaluates CrediSure AI vendor risk, model limitations, and required evidence | [Read (.md)](assets/documents/2.Vendor_Model_Governance_Review.md) · [Download (.docx)](assets/documents/2.Vendor_Model_Governance_Review.docx) |
| Human Oversight and Appeal Procedure | Defines human review triggers, override authority, escalation, and applicant appeal process | [Read (.md)](assets/documents/4.Human_Oversight_Appeal_Procedure.md) · [Download (.docx)](assets/documents/4.Human_Oversight_Appeal_Procedure.docx) |
| Production Readiness Decision Memo | Provides final executive recommendation | [Read (.md)](assets/documents/5.AI-Governance-Portfolio-Decision-Memo.md) · [Download (.docx)](assets/documents/5.AI-Governance-Portfolio-Project-Automated-Loan-Underwriting-System-Decision-Memo.docx) |

---

## Practical AI Governance Skill Proof

### 1. Organizational Framework Setup

| Field | Value |
|---|---|
| Goal | Establish the three-framework governance structure before beginning any assessment work |
| Frameworks Configured | EU AI Act · NIST AI RMF · ISO/IEC 42001 |
| Platform | VerifyWise |
| EU AI Act Scope | High-risk AI system under Annex III — automated credit decisioning |
| NIST AI RMF Scope | Full four-function assessment — Govern · Map · Measure · Manage |
| ISO/IEC 42001 Scope | AI management system across all clauses (4–10) |
| Applicable Regulations | EU AI Act Art. 9 (risk management) · ISO/IEC 42001 Clause 6 (planning) · NIST AI RMF Govern function |
| Setup Status | Complete — all three frameworks active in VerifyWise |

[View Screenshot](assets/screenshots/01-framework.png)

---

### 2. Use Case Registration

| Field | Value |
|---|---|
| Goal | Register and classify the AI system to establish governance scope and risk tier |
| Use Case Name | Meridian Automated Loan Underwriting System |
| Risk Classification | High-risk |
| Deployment Scope | Small business loan applications |
| Automation Rate | 94% automated decisions |
| Outcome Types | Auto-approve · Auto-deny · Manual review |
| Applicable Regulations | EU AI Act Annex III (high-risk classification) · NIST AI RMF MAP function · ISO/IEC 42001 Clause 4 (organizational context) |
| Governance Status | Under review — conditional approval required |

[View Screenshot](assets/screenshots/02-use-case.png)

---

### 3. Model Inventory

| Field | Value |
|---|---|
| Goal | Document the AI model to establish accountability, traceability, and risk awareness |
| Model Name | CrediSure Credit Decision Engine |
| Version | v2.3 |
| Provider | Third-party vendor (CrediSure) |
| Model Type | Credit decision / scoring |
| Input Data | Small business loan application data |
| Deployment Mode | API-integrated, automated decisioning |
| Model Capabilities | Evaluates creditworthiness · Produces risk score · Generates reason codes · Routes to auto-approve, auto-deny, or manual review |
| Known Limitations | Model internals not fully disclosed · Fairness testing results not yet provided · Reason code completeness unverified |
| Applicable Regulations | EU AI Act Art. 13 (transparency) · EU AI Act Art. 9 (risk management) · NIST AI RMF MAP 1.5 (third-party risk) · ISO/IEC 42001 Clause 8.4 (AI system lifecycle) |
| Inventory Status | Documented |

[View Screenshot](assets/screenshots/03-model-inventory.png)

---

### 4. Dataset Record

| Field | Value |
|---|---|
| Goal | Document the training dataset to surface data quality, bias, and privacy risks |
| Dataset Name | Small Business Loan Underwriting Dataset |
| Data Purpose | Train and operate credit decisioning model |
| Source | Historical loan application records |
| Data Types | Financial statements · Credit history · Business age · Industry · Geography · Cash-flow data |
| PII Status | Contains PII — business owner personal and financial data included |
| Known Bias Concerns | Geographic concentration · Industry correlation · Business age proxy · Thin credit file bias |
| Model Capabilities Enabled | Risk scoring · Automated decisioning · Reason code generation |
| Bias Mitigation Approach | Fairness testing and disparate impact analysis planned |
| Applicable Regulations | EU AI Act Art. 10 (data governance) · NIST AI RMF MEASURE 2.5 (bias testing) · ISO/IEC 42001 Clause 8.3 (data for AI systems) |
| Data Governance Status | Documented — fairness review required before production |

[View Screenshot](assets/screenshots/04-dataset.png)

---

### 5. Risk Register

| Risk | Severity | Control | Residual Risk |
|---|---|---|---|
| Discriminatory lending outcomes | High | Fairness testing and disparate impact analysis | High — testing not yet complete |
| Proxy bias through credit and business variables | High | Proxy-bias review across geography, industry, age | High — review not yet complete |
| Weak explainability and incomplete reason codes | High | Reason code validation and denial explanation audit | High — validation outstanding |
| Accountability gaps in third-party AI deployment | Medium | Vendor documentation review and contractual obligations | Medium — vendor evidence pending |
| Inaccurate automated denials | Medium | Threshold review and model accuracy testing | Medium — testing not yet complete |
| Lack of meaningful human oversight | High | Define mandatory human review triggers and escalation | High — triggers not yet defined |

**Why Each Risk Matters**

| Risk | Why It Matters |
|---|---|
| Discriminatory lending outcomes | The system may unfairly approve or deny applicants based on biased data, proxy variables, or historical lending patterns |
| Proxy bias through credit and business variables | Variables such as geography, business age, industry, or thin credit files may create unfair outcomes for protected groups |
| Weak explainability and incomplete reason codes | Meridian may be unable to explain automated denials, support appeals, or demonstrate compliance under the EU AI Act |
| Accountability gaps in third-party AI deployment | Meridian remains legally responsible for deployment even if the vendor controls key model details |
| Inaccurate automated denials | Qualified applicants may be incorrectly denied credit due to model error, incomplete data, or overly strict thresholds |
| Lack of meaningful human oversight | Routing only 6% of applications to human review may be insufficient for a high-risk credit decision system |

Applicable Regulations: EU AI Act Art. 9 (risk management) · NIST AI RMF MEASURE function · ISO/IEC 42001 Clause 6.1 (risk assessment)

[View Screenshot](assets/screenshots/05-risk-register.png)

---

### 6. Training Registry

| Field | Value |
|---|---|
| Goal | Record governance training to demonstrate practitioner competency and satisfy framework requirements |
| Training Program | Cyber Pros AI Governance, Risk & Compliance Practitioner |
| Training Source | Cyberpros Training (Maven platform) |
| Roles Covered | AI Governance Lead |
| Number of People Trained | 12 |
| Training Platform | Maven.com |
| Completion Status | Completed |
| Completion Date | May 2026 |
| Frameworks Covered | EU AI Act · NIST AI RMF · ISO/IEC 42001 |
| Tooling Covered | VerifyWise |
| Applicable Regulations | EU AI Act Art. 4 (AI literacy) · ISO/IEC 42001 Clause 7.2 (competence) · NIST AI RMF GOVERN 6.1 (workforce training) |

[View Screenshot](assets/screenshots/06-training-registry.png)

---

### 7. Evidence Documents

| Document | Type | Purpose | Owner | Status |
|---|---|---|---|---|
| AI Governance Intake Record | Governance | System profile, scope, and risk classification | AI Governance Lead | Complete |
| AI Risk Register and Mitigation Summary | Risk | Risk identification, rating, controls, and residual risk | AI Governance Lead | Complete |
| Vendor and Model Governance Review | Vendor | Third-party AI risk, model limitations, and evidence requirements | AI Governance Lead | Complete |
| Human Oversight and Appeal Procedure | Oversight | Human review triggers, escalation, and applicant appeal process | AI Governance Lead | Complete |
| Production Readiness Decision Memo | Decision | Executive recommendation and deployment conditions | AI Governance Lead | Complete |
| VerifyWise Portfolio Report | Consolidated | Full governance evidence package across all framework areas | AI Governance Lead | Complete |

Applicable Regulations: EU AI Act Art. 11 (technical documentation) · EU AI Act Art. 12 (record-keeping) · ISO/IEC 42001 Clause 7.5 (documented information) · NIST AI RMF GOVERN 1.7 (documentation)

[View Screenshot](assets/screenshots/07-evidence-documents.png)

---

### 8. Vendor Management

| Field | Value |
|---|---|
| Goal | Evaluate third-party AI vendor risk and establish accountability for model governance |
| Vendor Name | CrediSure |
| Product | Credit Decision Engine v2.3 |
| Vendor Role | Third-party AI model provider — primary decision engine |
| Risk Level | High — vendor controls key model logic, training data, and scoring methodology |
| Model Transparency | Limited — model internals, training data, and weights not fully disclosed |
| Contractual Coverage | Under review — AI-specific obligations not yet confirmed |
| Fairness Evidence | Not yet provided — disparate impact testing results outstanding |
| Model Card | Not yet provided |
| Accuracy Benchmarks | Not yet provided |
| Explainability | Reason codes generated — completeness and sufficiency not yet validated |
| SLA Terms | Under review |
| Data Sharing Terms | Under review — PII handling and retention policies not yet confirmed |
| Vendor Review Outcome | Evidence collection in progress — deployment conditional on vendor documentation |
| Applicable Regulations | EU AI Act Art. 25 (obligations for deployers of third-party AI) · EU AI Act Art. 9 (risk management for third-party models) · NIST AI RMF MAP 1.5 (third-party risk) · ISO/IEC 42001 Clause 8.4 (external AI providers) |

[View Screenshot](assets/screenshots/08-vendor-management.png)

---

### 9. Policy Manager

| Policy Area | Applicability | Status | Owner |
|---|---|---|---|
| High-risk AI use case policy | Meridian loan underwriting system | Applicable | AI Governance Lead |
| Human oversight and intervention policy | All automated credit decisions | Applicable — triggers to be defined | Risk & Compliance |
| Explainability and reason code policy | All automated denials | Applicable — validation outstanding | AI Governance Lead |
| Appeal and reconsideration policy | Affected loan applicants | Applicable — procedure to be established | Operations |
| Third-party AI vendor governance policy | CrediSure vendor relationship | Applicable — evidence pending | Vendor Management |
| Monitoring and incident escalation policy | Production deployment (when approved) | Applicable — thresholds to be defined | AI Governance Lead |

Applicable Regulations: EU AI Act Art. 9 · ISO/IEC 42001 Clause 5.2 (policy) · NIST AI RMF GOVERN 1.1

[View Screenshot](assets/screenshots/09-policy-manager.png)

---

### 10. Incident Management

| Incident Type | Trigger Condition | Escalation Path | Resolution Approach |
|---|---|---|---|
| Automated denial — potential discrimination | Denial rate disparity across protected groups | AI Governance Lead → Risk Committee | Pause automated decisions · Conduct fairness audit |
| Model accuracy failure | Denial or approval error rate exceeds threshold | AI Governance Lead → Technology · Risk | Suspend model · Initiate vendor review |
| Unexplainable denial | Reason codes absent or insufficient | Operations → AI Governance Lead | Manual review override · Reason code audit |
| Appeal escalation | Applicant disputes automated decision | Operations → Human reviewer → Governance | Human review · Decision override if warranted |
| Vendor system outage | CrediSure API unavailable | Technology → Operations | Route all applications to manual review |
| Governance breach | Deployment outside approved conditions | AI Governance Lead → Risk Committee | Halt deployment · Conduct root cause review |

Applicable Regulations: EU AI Act Art. 26 (deployer obligations) · ISO/IEC 42001 Clause 10.1 (nonconformity and corrective action) · NIST AI RMF MANAGE 4.1 (incident response)

[View Screenshot](assets/screenshots/10-incident-management.png)

---

### 11. ISO/IEC 42001 Assessment

| Clause | Control Area | Requirement | Assessment Status | Notes |
|---|---|---|---|---|
| 4 | Organizational context | Define AI management system scope | Met | Scope defined for loan underwriting use case |
| 4 | Organizational context | Identify internal and external stakeholders | Partially met | Internal roles identified — external stakeholders (applicants) not formally consulted |
| 5 | Leadership | Assign AI governance roles and responsibilities | Partially met | AI Governance Lead assigned — committee approval pending |
| 5 | Leadership | Establish AI policy | Partially met | Policy areas mapped — formal policy document not yet adopted |
| 6 | Planning | Conduct AI risk assessment | Partially met | Risks identified — treatment plan in progress |
| 6 | Planning | Establish AI risk treatment plan | Partially met | Controls defined — implementation outstanding |
| 6 | Planning | Set AI objectives | Partially met | Governance objective defined — measurable targets not yet set |
| 7 | Support | Maintain AI governance documentation | Met | Intake record, risk register, vendor review complete |
| 7 | Support | Ensure staff competency and training | Met | Practitioner training completed and recorded |
| 8 | Operation | Manage AI system lifecycle | Partially met | Pre-deployment review complete — production controls pending |
| 8 | Operation | Third-party AI risk management | Partially met | Vendor documented — evidence collection in progress |
| 8 | Operation | Data governance for AI | Partially met | Dataset documented — fairness review outstanding |
| 9 | Performance evaluation | Monitor AI system outcomes | Not yet met | Monitoring thresholds not yet defined |
| 9 | Performance evaluation | Management review | Not yet met | Governance committee approval outstanding |
| 10 | Improvement | Incident and nonconformity management | Partially met | Incident types defined — escalation procedures to be formalized |

[View Screenshot](assets/screenshots/11-iso-42001.png)

---

### 12. NIST AI RMF Assessment

| Function | Sub-function | Category | Requirement | Assessment Status | Evidence |
|---|---|---|---|---|---|
| GOVERN | 1 | Policies and culture | Establish AI governance roles and accountability | Partially met | AI Governance Lead assigned — committee not yet convened |
| GOVERN | 1 | Organizational practices | Define AI risk tolerance and governance policy | Partially met | Risk register complete — formal policy under development |
| GOVERN | 2 | Accountability | Assign accountability for AI risk outcomes | Partially met | Governance Lead accountable — deployer obligations not yet fully documented |
| GOVERN | 6 | Workforce | AI literacy and training for relevant roles | Met | Practitioner training completed — recorded in training registry |
| MAP | 1 | System context | Document intended use, affected groups, and system scope | Met | Governance intake record complete |
| MAP | 1 | Risk identification | Identify AI risks across fairness, explainability, oversight | Met | Six priority risks documented in risk register |
| MAP | 2 | Impact assessment | Assess potential harms to affected persons | Partially met | Risk register addresses harms — FRIA completed |
| MAP | 5 | Third-party risk | Evaluate vendor and model risks | Partially met | Vendor review complete — evidence collection in progress |
| MEASURE | 1 | Risk analysis | Rate and prioritize AI risks | Met | Severity and residual risk documented for all six risks |
| MEASURE | 2 | Testing and evaluation | Conduct fairness testing and disparate impact analysis | Not yet met | Fairness testing outstanding — required before deployment |
| MEASURE | 2 | Explainability | Validate reason codes and denial explanations | Not yet met | Reason code validation outstanding |
| MEASURE | 4 | Human-AI oversight | Define human oversight triggers and review authority | Not yet met | Human review triggers not yet defined |
| MANAGE | 1 | Risk treatment | Apply controls and mitigations | Partially met | Controls defined — implementation outstanding |
| MANAGE | 3 | Residual risk | Track and document residual risk | Partially met | Residual risk documented — post-control verification pending |
| MANAGE | 4 | Incident response | Define escalation and response procedures | Partially met | Incident types identified — procedures to be formalized |
| IMPROVE | 1 | Monitoring | Define outcome monitoring and feedback loops | Not yet met | Monitoring thresholds not yet established |
| IMPROVE | 2 | Continuous improvement | Track governance maturity and update risk register | Not yet met | Post-deployment review process to be defined |

[View Screenshot](assets/screenshots/12-nist-ai-rmf.png)

---

### 13. EU AI Act Assessment — Fundamental Rights Impact Assessment (FRIA)

| FRIA Area | EU AI Act Reference | Requirement | Finding | Risk Level | Recommendation |
|---|---|---|---|---|---|
| High-risk AI classification | Annex III · Art. 6 | Determine if system is high-risk | Classified as high-risk — automated credit decision system | High | Full compliance review required before deployment |
| Affected persons | Art. 9 · Art. 13 | Identify groups affected by AI decisions | Small business loan applicants — includes protected groups | High | Bias and fairness testing required |
| Non-discrimination | Art. 10 · Art. 9 | Ensure decisions do not produce discriminatory outcomes | Proxy bias risk identified across geography, industry, business age | High | Disparate impact analysis required |
| Transparency | Art. 13 | Require explainable decisions and reason codes for affected persons | Reason code completeness unverified | High | Reason code validation required |
| Human oversight | Art. 14 | Mandate meaningful human review for high-risk decisions | Human review triggers undefined — 6% routing insufficient | High | Mandatory human oversight triggers required |
| Right to explanation | Art. 86 | Affected persons must receive explanation of automated decisions | Denial explanation process not yet defined | High | Explanation and appeal procedure required |
| Right to contestability | Art. 85 · Art. 86 | Applicants must be able to appeal automated decisions | Appeal procedure not yet established | High | Formal appeal and reconsideration process required |
| Logging and audit trail | Art. 12 | System must log decisions for post-market monitoring | Audit logging not confirmed with CrediSure | Medium | Decision-level logging must be confirmed |
| Data governance | Art. 10 | Training data must be fit for purpose and free from bias | Dataset bias concerns documented — fairness review outstanding | High | Fairness testing required before deployment |
| Stakeholder consultation | Art. 9 · FRIA guidance | Affected groups must be considered in FRIA process | Consultation status incomplete | Medium | Consultation to be documented |
| Technical documentation | Art. 11 | Maintain documentation supporting conformity assessment | Governance artifacts complete — vendor documentation gaps remain | Medium | Vendor documentation to be completed |
| Deployment conditions | Art. 9 · Art. 14 | Production deployment requires governance committee approval | Governance committee approval outstanding | High | Do not deploy until all conditions are met |

[View Screenshot](assets/screenshots/13-eu-ai-act-fria.png)

---

### 14. VerifyWise Dashboard

| Component | Description | Completion |
|---|---|---|
| Organizational Framework Setup | EU AI Act, NIST AI RMF, and ISO/IEC 42001 configured | Complete |
| Use Case Registration | Meridian Automated Loan Underwriting System registered as high-risk | Complete |
| Model Inventory | CrediSure Credit Decision Engine v2.3 documented | Complete |
| Dataset Record | Small Business Loan Underwriting Dataset documented with bias flags | Complete |
| Risk Register | Six priority risks identified, rated, and mitigated | Complete |
| Training Registry | Cyberpros AI Governance practitioner training recorded | Complete |
| Evidence Documents | All governance artifacts linked and organized | Complete |
| Vendor Management | CrediSure vendor record and full risk assessment documented | Complete |
| Policy Manager | Applicable policies mapped to use case | Complete |
| Incident Management | Incident types and escalation paths defined | Complete |
| ISO/IEC 42001 Assessment | Controls assessed across all clauses (4–10) | Complete |
| NIST AI RMF Assessment | All four functions assessed with evidence mapping | Complete |
| EU AI Act / FRIA | Fundamental Rights Impact Assessment completed | Complete |
| Portfolio Report | Consolidated VerifyWise report generated | Complete |

[View Screenshot](assets/screenshots/00-verifywise-dashboard.png)

---

## 15. Final Report

![Final Report Cover](assets/screenshots/14-portfolio-report-cover.png)

[View Portfolio Report (PDF)](assets/documents/AI-Governance-Portfolio-Report.pdf)

### Final Recommendation

My final recommendation is:

> **Proceed with conditions.**

Meridian should not approve unrestricted production deployment at this time. The system may move forward only if the following conditions are completed:

- Complete fairness testing and disparate impact analysis
- Complete proxy-bias review
- Validate denial reason codes
- Define mandatory human review triggers
- Establish appeal and reconsideration procedures
- Complete vendor documentation review
- Complete security and privacy review
- Define model and outcome monitoring thresholds
- Implement decision-level audit logging
- Establish incident escalation procedures
- Obtain governance committee approval

### Portfolio Conclusion

This project demonstrates my ability to evaluate a high-risk AI system from an AI governance, risk, and compliance perspective.

The Meridian Automated Loan Underwriting System offers business benefits, including faster decisions, improved consistency, and operational efficiency. However, because it affects access to credit and automates most decisions, it requires strong governance before deployment.

As AI Governance Lead, my assessment found that the system should not receive unrestricted production approval until Meridian completes required fairness, explainability, human oversight, vendor, monitoring, privacy, and governance controls.

This project reflects how I would support responsible AI deployment in a real organization.

---

## Disclaimer

This is a fictional educational portfolio project created for AI governance, risk, and compliance training. It does not represent legal advice, regulatory certification, credit decisioning advice, or an actual assessment of a real financial institution.
