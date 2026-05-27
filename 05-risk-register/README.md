# #05 – Risk Register & Mitigation Matrix

**Use Case:** Meridian Automated Loan Underwriting System
**Frameworks:** NIST AI RMF, IBM AI Risk Database, MIT AI Risk Repository

## Summary

This artifact contains the comprehensive risk register and priority mitigation matrix for the automated loan underwriting system, tracking inherent risk, control strategies, and residual risk tiers.

---

## Priority Risk Matrix

The system was assessed against industry risk databases. Six priority risks were identified, with **Lack of Meaningful Human Oversight** presenting the highest exposure due to the system's 94% automated decision rate.

| Risk ID | Risk Description | Inherent Risk | Mitigation Strategy | Residual Risk |
| :--- | :--- | :--- | :--- | :--- |
| **R-01** | Discriminatory lending outcomes / disparate impact | Catastrophic | Implement pre-production demographic parity testing and continuous bias audits. | **Medium-High** |
| **R-02** | Proxy bias through geographic & business variables | Major | Standardize feature drop rules for zip codes and correlated variables. | **Medium** |
| **R-03** | Weak explainability / non-compliant denial codes | Major | Map vendor output codes to compliant adverse action reason codes. | **Medium** |
| **R-04** | Third-party vendor accountability gaps | Major | Enforce strict SLAs and regular vendor model validation reviews. | **Low** |
| **R-05** | Inaccurate automated denials (false negatives) | Major | Create a statistical safety buffer zone for marginal credit scores. | **Medium** |
| **R-06** | Lack of meaningful human oversight (automation bias) | Catastrophic | Define mandatory human review triggers for high-impact segments. | **High** |

---

## Key Recommendations & Controls

*   **Establish a Safety Buffer:** Applications falling within a ±5% margin of the automated denial threshold must be automatically rerouted away from the AI and into the manual underwriting queue.
*   **Continuous Monitoring:** Implement automated telemetry alerts to flag sudden shifts in approval/denial ratios, which could indicate underlying data drift or model instability.

---

### System Interface Capture
![AI Risk Register](../screenshots/05-risk-register.png)
