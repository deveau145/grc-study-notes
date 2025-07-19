# 📄 Vendor Risk Assessment Template (Sample)

> This document provides a sample framework to assess third-party vendor risk. It helps evaluate how external vendors manage security, privacy, and compliance. Intended for training, demonstration, or lab purposes.

---

## ✏️ Assessment Overview
Vendor risk assessments help ensure that third parties who store, process, or transmit organizational data meet security and compliance standards.

---

## 📈 Vendor Risk Questionnaire Summary

| Category | Assessment Questions | Vendor Response | Risk Level | Notes |
|----------|----------------------|-----------------|------------|-------|
| Data Protection | Do you encrypt sensitive data at rest and in transit? | Yes | Low | AES-256 & TLS 1.2 enforced |
| Access Controls | Do you use MFA for all administrative access? | Yes | Low | Azure AD + MFA required |
| Compliance | Are you compliant with any standards (e.g., SOC 2, HIPAA, ISO 27001)? | SOC 2 Type II | Medium | Certification expires Q4 |
| Incident Response | Do you have a documented IR plan and notification timeline? | Yes (72 hrs) | Low | Reviewed annually |
| Subprocessors | Do you share customer data with subprocessors? | Yes | Medium | Subprocessor list available |

---

## 📆 Scoring & Risk Levels

| Risk Level | Description |
|------------|-------------|
| Low | Sufficient controls in place, minimal exposure |
| Medium | Some gaps identified, requires periodic review or conditional approval |
| High | Significant risk or missing controls, require mitigation or alternative vendor |

---

## 🔐 Review Checklist
- [x] Signed NDA or contract in place
- [x] Most recent SOC 2 / ISO / HIPAA report available
- [x] Incident response plan reviewed
- [x] Security contacts documented
- [ ] Annual reassessment scheduled

---

## 💼 Document Information
- **Owner:** GRC / Procurement
- **Version:** 1.0
- **Last Reviewed:** July 2025
- **Next Review:** July 2026

---

> ⚠️ This is a generic example. Organizations should adjust the questionnaire and scoring system to meet their own regulatory, industry, or contractual requirements.
