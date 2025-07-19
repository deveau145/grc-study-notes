# 📅 Risk Register Template

> This template is based on NIST Cybersecurity Framework guidance and is intended for training and demonstration purposes.

## ✨ Overview
A risk register is a document used to track identified risks, their potential impact, likelihood, current controls, and mitigation actions.

---

## 📊 Risk Register Table

| ID | Risk Description | Impact (H/M/L) | Likelihood (H/M/L) | Current Controls | Recommended Actions | Owner | Status |
|----|------------------|----------------|---------------------|------------------|----------------------|--------|--------|
| 1 | Phishing emails may bypass filters and trick users into clicking | High | High | Microsoft Defender + Proofpoint | Launch monthly phishing simulations and user awareness training | Security Team | Open |
| 2 | Unpatched Linux servers may be exploited remotely | High | Medium | Patch management via N-Able | Automate vulnerability scans + patch rollout | SysAdmin | In Progress |
| 3 | Users reuse weak passwords across accounts | Medium | High | M365 MFA Enabled | Enforce password policies + periodic user training | IT/GRC | Open |
| 4 | 3rd-party vendor has access to sensitive data | High | Low | NDA + Manual reviews | Conduct vendor risk assessment and audit logs | GRC Analyst | Open |

---

## 📚 Notes
- Impact = the consequence to the organization if the risk occurs
- Likelihood = how probable the risk is, based on past data or assumptions
- Controls = what's already in place
- Actions = what's needed to reduce likelihood or impact
- Status = Open / In Progress / Mitigated / Accepted

---

## 🔧 Use This Template For:
- Mock audits or tabletop exercises
- Showcasing risk awareness in GRC job interviews
- Class or bootcamp projects

> ⚠️ Replace the sample risks with ones that match your organization's environment or lab simulations.
