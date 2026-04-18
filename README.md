# Conducting a Security Audit | Google Cybersecurity Professional Certificate

## Overview
This project demonstrates the process of conducting a cybersecurity audit for a simulated organization, Botium Toys. The audit evaluates the organization’s current security posture, identifies risks, and provides recommendations to improve security controls and compliance.

## 📊 Key Result
**Risk Level: High (8/10)** due to lack of access controls, encryption, and security monitoring.

---

## 📄 Audit Scope & Objectives
- Assess the organization’s overall security program
- Identify assets, risks, and vulnerabilities
- Evaluate existing controls and compliance practices
- Recommend improvements to reduce risk and strengthen security posture

---

## 🏢 Botium Toys Environment

<img width="468" height="545" alt="image" src="https://github.com/user-attachments/assets/2aea8242-db9f-441e-bdef-5769394ca090" />

---

## My Controls Assessment Checklist

| Control | Status |
|--------|--------|
| Least Privilege | ❌ |
| Disaster Recovery Plans | ❌ |
| Password Policies | ❌ |
| Separation of Duties | ❌ |
| Firewall | ✅ |
| Intrusion Detection System (IDS) | ❌ |
| Backups | ❌ |
| Antivirus Software | ✅ |
| Manual monitoring, maintenance, and intervention for legacy systems | ❌ |
| Encryption | ❌ |
| Password Management System | ❌ |
| Physical Locks | ✅ |
| CCTV Surveillance | ✅ |
| Fire Detection/Prevention | ✅ |

---

## 📋 Compliance Assessment

### PCI DSS (Payment Card Industry Data Security Standard)

| Best Practice | Status |
|--------------|--------|
| Only authorized users have access to customers’ credit card information. | ❌ |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. | ❌ |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. | ❌ |
| Adopt secure password management policies. | ❌ |

---

### GDPR (General Data Protection Regulation)

| Best Practice | Status |
|--------------|--------|
| E.U. customers’ data is kept private/secured. | ❌ |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | ✅ |
| Ensure data is properly classified and inventoried. | ❌ |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | ✅ |

---

### SOC 1 / SOC 2

| Best Practice | Status |
|--------------|--------|
| User access policies are established. | ❌ |
| Sensitive data (PII/SPII) is confidential/private. | ❌ |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated. | ✅ |
| Data is available to individuals authorized to access it. | ❌ |

---

## 🔍 Key Findings
- Lack of access control (all employees have access to sensitive data)
- No encryption for customer credit card data
- Weak password policies and no centralized password management
- No intrusion detection system (IDS)
- No disaster recovery plan or backups
- Limited asset management and visibility

---

## My Recommendations:
-	Implement least privilege and role-based access controls so only authorized personnel can access sensitive data. Right now, all employees have access to PII/SPII — this significantly increases risk from internal bad actors.
-	Encrypt confidential data, especially customer credit card information and PII/SPII. This is a foundational step toward ensuring confidentiality.
-	Enforce stricter password policies aligned with current standards (minimum eight characters, mix of letters, numbers, and special characters) and implement a centralized password management system.
-	Deploy an intrusion detection system (IDS) to monitor network traffic and detect potential threats.
-	Develop and implement a disaster recovery plan to ensure business continuity in the event of a breach or system failure.
-	Establish proper backups for critical data so the company can restore and recover from an incident.

## My Summary:
For Botium Toys the biggest concern to me is that none of their sensitive data (PII, SPII, cardholder information) is kept private or secure. Without encryption, access controls, or strict password policies, the risk of unauthorized access is high - both from external threats and internal bad actors. Prioritizing encryption and least privilege controls will immediately reduce exposure. A disaster recovery plan and reliable backups are also critical to maintain business continuity, and an IDS will strengthen the company's ability to detect and respond to threats before they escalate.

---

## 📁 Project Files

- [Audit Scope, Goals, and Risk Assessment](./Botium-Toys-Scope-goals-and-risk-assessment-report.docx)
- [Controls and Compliance Checklist](./Connor%20Tarpey’s%20Controls%20and%20compliance%20checklist.docx)

---

## 💡 Key Skills Demonstrated
- Security auditing
- Risk assessment
- Control evaluation
- Compliance awareness (PCI DSS, GDPR, SOC)
- Security documentation and reporting

---

## 📌 🧠 Summary of Project & What I Learned

This project highlights my ability to analyze an organization’s security posture, identify critical vulnerabilities, and recommend actionable improvements to reduce risk and enhance overall security.

I learned : 
- The importance of asset visibility in risk management
- How missing basic controls significantly increases risk
- How frameworks like NIST CSF guide security audits
