# #04 – Dataset Record & Provenance Registry

**Dataset:** Small Business Loan Underwriting Dataset  
**Version:** 1.0  
**Classification:** Confidential  

## Summary

This registry tracks the baseline dataset used for evaluating fairness, proxy bias, and technical model telemetry within the automated loan underwriting system.

| Field | Value |
|---|---|
| **Version** | 1.0 |
| **Classification** | Confidential |
| **Type** | Training / Validation Baseline |
| **Contains PII** | Yes (Mitigated via internal access tokens) |
| **Status** | Active |

---

## Detailed Data Governance Profile

### 1. Known Biases & Proxy Risks
* **Geographic & Proxy Bias:** Potential proxy bias identified through zip codes and geographic operational variables correlating with historically underserved demographic areas.
* **Feature Volatility:** Cash-flow volatility and "thin" credit histories disproportionately impact early-stage businesses (under 2 years of operation), requiring explicit model guardrails.

### 2. Lineage & Technical Features
* **Core Attributes:** Historical credit scores, business cash-flow metrics, industry classification codes (NAICS), business age, and regional economic indicators.
* **Data Residency:** Fully contained within the secure internal environment to enforce strict data residency and privacy controls.

---

### System Interface Capture
![Dataset Provenance Registry](/screenshots/04-dataset.png)

---

### Raw Data Repository
* 📊 **[Access Raw Telemetry & Baseline Dataset](./Small_business_loan_underwriting_dataset.csv)**