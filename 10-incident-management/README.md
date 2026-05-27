# 10 — Incident Management

**Record Type:** Pre-Production Incident Record  
**System:** Meridian Automated Loan Underwriting System  
**Platform:** [VerifyWise](https://cyberpros.verifywise.ai/)

## Summary

Documents a pre-production incident identified during governance review of the Meridian Automated Loan Underwriting System, prior to production deployment approval.

| Field | Value |
|---|---|
| **Incident Type** | Pre-Production Governance Finding |
| **System** | Meridian Automated Loan Underwriting System |
| **Status** | Open |

## Incident Description

During pre-production governance review, it was identified that the CrediSure Credit Decision Engine v2.3 lacked documented denial reason codes that could be independently validated against actual model outputs. This creates a compliance gap under EU AI Act transparency obligations and fair lending requirements, where applicants have a right to meaningful explanation of adverse credit decisions.

## Impact

Without validated reason codes, Meridian cannot fulfill its obligation to provide meaningful, accurate explanations to denied applicants, exposing the organization to regulatory risk and potential consumer harm.

## Resolution Status

Pending vendor response. CrediSure AI has been asked to provide full documentation of reason code generation logic and sample validation evidence before production approval is granted.

*VerifyWise screenshot to be added.*

### System Interface Capture
![Incident Response Runbook](../screenshots/10-incident-management.png)
