# Conducting-a-security-audit
# Controls and Compliance Checklist

To complete the controls assessment checklist, refer to the information provided in the scope, goals, and risk assessment report. For more details about each control, including the type and purpose, refer to the control categories document.  

Then, select **“yes” or “no”** to answer the question:  
**Does Botium Toys currently have this control in place?**

---

## Controls Assessment Checklist

| Control                                                   | Yes | No |
|-----------------------------------------------------------|-----|----|
| Least Privilege                                           |     |  x |
| Disaster recovery plans                                   |     |  x |
| Password policies                                         |     |  x |
| Separation of duties                                      |     |  x |
| Firewall                                                  |  x  |    |
| Intrusion detection system (IDS)                          |     |  x |
| Backups                                                   |     |  x |
| Antivirus software                                        |   x  |    |
| Manual monitoring, maintenance, and intervention for legacy systems |     |  x  |
| Encryption                                                |     |  x  |
| Password management system                                |     |  x  |
| Locks (offices, storefront, warehouse)                    |   x  |    |
| Closed-circuit television (CCTV) surveillance             |    x |    |
| Fire detection/prevention (fire alarm, sprinkler system)  |   x  |    |

---

## Compliance Checklist

To complete the compliance checklist, refer to the information provided in the scope, goals, and risk assessment report. For more details about each compliance regulation, review the controls, frameworks, and compliance reading.  

Then, select **“yes” or “no”** to answer the question:  
**Does Botium Toys currently adhere to this compliance best practice?**

---

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                                 | Yes | No |
|-------------------------------------------------------------------------------|-----|----|
| Only authorized users have access to customers’ credit card information.      |     |  x  |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |     | x   |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. |     | x   |
| Adopt secure password management policies.                                    |     |  x  |

---

### General Data Protection Regulation (GDPR)

| Best Practice                                                                 | Yes | No |
|-------------------------------------------------------------------------------|-----|----|
| E.U. customers’ data is kept private/secured.                                 |     |  x  |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |   x  |    |
| Ensure data is properly classified and inventoried.                           |     |    x|
| Enforce privacy policies, procedures, and processes to properly document and maintain data. |    x |    |

---

### System and Organizations Controls (SOC Type 1, SOC Type 2)

| Best Practice                                                                 | Yes | No |
|-------------------------------------------------------------------------------|-----|----|
| User access policies are established.                                         |     |   x |
| Sensitive data (PII/SPII) is confidential/private.                            |     |  x  |
| Data integrity ensures the data is consistent, complete, accurate, and validated. |  x   |    |
| Data is available to individuals authorized to access it.                     |     |  x  |

---

## Recommendations

Based on the assessment, **Botium Toys has a high-risk score of 8**, indicating significant vulnerabilities. The following recommendations are crucial to reduce risk and improve the company's security posture.

### High-Priority Recommendations
- **Implement Access Control**: Establish least privilege and separation of duties. Restrict access to sensitive data, especially customer credit card information and PII/SPII, to only authorized employees who require it for their job functions. Critical for PCI DSS and GDPR compliance.  
- **Deploy Encryption**: Immediately implement encryption for all sensitive data, both at rest and in transit. This is fundamental for protecting customer data and meeting compliance standards.  
- **Establish a Disaster Recovery Plan (DRP) and Backups**: The absence of a DRP and data backups poses a severe threat to business continuity. Develop a formal DRP, test it regularly, and implement a robust backup strategy to ensure recovery from data loss events.  

### Medium-Priority Recommendations
- **Strengthen Password Security**: Update the password policy to enforce strong complexity requirements (length, character types) and implement a password management system to enforce these policies and reduce support tickets.  
- **Install an Intrusion Detection System (IDS)**: An IDS provides early warnings of malicious activity, enabling faster incident response.  
- **Conduct an Asset Management and Classification Project**: Inventory and classify all assets to understand what needs protection and apply the appropriate controls.  

---
