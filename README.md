# Controls and Compliance Checklist


## Scenario

This scenario is based on a fictional company:

**Botium Toys** is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and a warehouse for their products. However, Botium Toys’ online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide.  

The manager of the IT department has decided that an internal IT audit needs to be conducted. She is worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).  

The IT manager starts by implementing the **National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)**, establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.  

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.

---

## Controls and compliance checklist

To complete the controls assessment checklist, refer to the information provided in the [scope, goals, and risk assessment report](Supporting%20Material/Botium%20Toys_%20Scope,%20goals,%20and%20risk%20assessment%20report.md). For more details about each control, including the type and purpose, refer to the [control categories](Supporting%20Material/Control%20categories.md) document.  

Then, select **“yes” or “no”** to answer the question:  
**Does Botium Toys currently have this control in place?**

---

## Controls Assessment Checklist

| Control                                                   | Yes | No |
|-----------------------------------------------------------|-----|----|
| Least Privilege                                           |     | ❌ |
| Disaster recovery plans                                   |     | ❌ |
| Password policies                                         |     | ❌ |
| Separation of duties                                      |     | ❌ |
| Firewall                                                  | ✔️  |    |
| Intrusion detection system (IDS)                          |     | ❌ |
| Backups                                                   |     | ❌ |
| Antivirus software                                        | ✔️  |    |
| Manual monitoring, maintenance, and intervention for legacy systems |     | ❌ |
| Encryption                                                |     | ❌ |
| Password management system                                |     | ❌ |
| Locks (offices, storefront, warehouse)                    | ✔️  |    |
| Closed-circuit television (CCTV) surveillance             | ✔️  |    |
| Fire detection/prevention (fire alarm, sprinkler system)  | ✔️  |    |

---

## Compliance Checklist

To complete the compliance checklist, refer to the information provided in the [scope, goals, and risk assessment report](Supporting%20Material/Botium%20Toys_%20Scope,%20goals,%20and%20risk%20assessment%20report.md). For more details about each compliance regulation, review the controls, frameworks, and compliance reading.  

Then, select **“yes” or “no”** to answer the question:  
**Does Botium Toys currently adhere to this compliance best practice?**

---

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                                 | Yes | No |
|-------------------------------------------------------------------------------|-----|----|
| Only authorized users have access to customers’ credit card information.      |     | ❌ |
| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |     | ❌ |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. |     | ❌ |
| Adopt secure password management policies.                                    |     | ❌ |

---

### General Data Protection Regulation (GDPR)

| Best Practice                                                                 | Yes | No |
|-------------------------------------------------------------------------------|-----|----|
| E.U. customers’ data is kept private/secured.                                 |     | ❌ |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | ✔️  |    |
| Ensure data is properly classified and inventoried.                           |     | ❌ |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | ✔️  |    |

---

### System and Organizations Controls (SOC Type 1, SOC Type 2)

| Best Practice                                                                 | Yes | No |
|-------------------------------------------------------------------------------|-----|----|
| User access policies are established.                                         |     | ❌ |
| Sensitive data (PII/SPII) is confidential/private.                            |     | ❌ |
| Data integrity ensures the data is consistent, complete, accurate, and validated. | ✔️  |    |
| Data is available to individuals authorized to access it.                     |     | ❌ |

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
