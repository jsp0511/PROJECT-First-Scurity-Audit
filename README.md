# firstsecurityaudit
First security audit while conducting Cyber Security Professional Certificate on Corsera

# Botium Toys Cybersecurity Audit and Compliance Assessment

## Project Introduction
This project is a comprehensive cybersecurity audit and compliance assessment for Botium Toys, a fictitious company in Googles Play It Safe: Manage Security Risks Module 2 OWASP Security Principles. The audit addresses key security controls, compliance requirements, and risk mitigation strategies needed to improve the company’s security posture. By assessing existing assets and controls, this project identifies crucial areas for improvement and compliance.

## Modeling and Evaluation
The project assessed Botium Toys' cybersecurity maturity through a structured controls and compliance checklist, addressing critical control categories (administrative, technical, and physical) and adherence to industry regulations (PCI DSS, GDPR, SOC). The main models and evaluation metrics include:

- **Controls Assessment Checklist**: A comprehensive checklist assessed whether Botium Toys had implemented essential security controls, such as least privilege, firewalls, antivirus, encryption, and a disaster recovery plan. Controls were evaluated across:
  - **Control Categories**: Administrative (e.g., password policies, access control), Technical (e.g., IDS, encryption, backups), and Physical (e.g., CCTV, locks).
  - **Control Types**: Preventative, corrective, detective, and deterrent controls to ensure a layered defense.

### Controls Assessment Checklist

| Control                                | Implemented? | Comments                                                                                                     |
|----------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------|
| **Least Privilege**                    | No           | All employees have broad access to data, including cardholder and customer information. |
| **Disaster Recovery Plans**            | No           | No formal disaster recovery plan or data backups are currently in place. |
| **Password Policies**                  | No           | The existing password policy lacks complexity and does not meet modern standards. |
| **Separation of Duties**               | No           | Separation of duties has not been enforced, increasing the risk of insider threats. |
| **Firewall**                           | Yes          | A firewall with defined security rules has been configured by IT. |
| **Intrusion Detection System (IDS)**   | No           | No IDS is currently installed, limiting detection of unauthorized access. |
| **Backups**                            | No           | No backup procedures are in place for critical data. |
| **Antivirus Software**                 | Yes          | Antivirus software is installed and regularly monitored by IT. |
| **Manual Monitoring and Maintenance**  | Yes          | Legacy systems are monitored, but without a fixed schedule. |
| **Encryption**                         | No           | Customer credit card data is not encrypted, posing confidentiality risks. |
| **Password Management System**         | No           | No centralized password management system, which complicates secure password handling. |
| **Locks (Offices, Storefront, Warehouse)** | Yes      | Physical locks are in place, securing Botium Toys’ facilities. |
| **Closed-Circuit Television (CCTV)**   | Yes          | CCTV is operational in offices, storefront, and warehouse. |
| **Fire Detection/Prevention (Alarms, Sprinklers)** | Yes  | Fire detection and prevention systems are installed and functional. |

- **Compliance Checklist**: The compliance checklist evaluated adherence to standards for securing payment and personal data, as outlined by:
  - **PCI DSS**: Measures for protecting customer credit card data, including access restrictions, encryption, and password policies.
  - **GDPR**: Privacy controls for protecting E.U. customer data, data breach notification plans, and data inventory and classification.
  - **SOC**: Data integrity, user access policies, and data availability requirements to meet U.S. compliance standards.

### Compliance Checklist

#### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                              | Adherence | Comments                                                                                           |
|------------------------------------------------------------|-----------|----------------------------------------------------------------------------------------------------|
| Only authorized users have access to customers’ credit card information. | No        | All employees currently have broad access to sensitive data. |
| Credit card information is stored, accepted, processed, and transmitted in a secure environment. | No        | Lack of encryption and secure storage for customer payment data. |
| Implement data encryption procedures for credit card data. | No        | Customer credit card data is currently unencrypted. |
| Adopt secure password management policies.                 | No        | Password policy lacks complexity and centralized enforcement. |

#### General Data Protection Regulation (GDPR)

| Best Practice                                              | Adherence | Comments                                                                                           |
|------------------------------------------------------------|-----------|----------------------------------------------------------------------------------------------------|
| E.U. customers’ data is kept private/secured.              | No        | Insufficient access controls and data protection measures. |
| Plan in place to notify E.U. customers within 72 hours of a breach. | Yes       | Incident response plan includes a 72-hour notification requirement. |
| Data is properly classified and inventoried.               | No        | No system for data classification or inventory in place. |
| Enforce privacy policies, procedures, and documentation.   | Yes       | Policies exist, but enforcement needs improvement. |

#### System and Organizations Controls (SOC Type 1, SOC Type 2)

| Best Practice                                              | Adherence | Comments                                                                                           |
|------------------------------------------------------------|-----------|----------------------------------------------------------------------------------------------------|
| User access policies are established.                      | No        | No established access controls or policies to regulate permissions. |
| Sensitive data (PII/SPII) is confidential/private.         | No        | Broad access to sensitive information, compromising confidentiality. |
| Data integrity ensures data is consistent and validated.   | Yes       | Data integrity controls are in place to maintain consistency. |
| Data is available to authorized individuals.               | Yes       | Availability controls ensure access for authorized users. |

The audit findings highlighted several areas for improvement, with missing or weak controls in access management, encryption, password policies, and disaster recovery. Recommendations were provided to strengthen Botium Toys’ security and compliance framework, reducing risks and enhancing data protection.

## Conclusion
Based on the audit results, Botium Toys should implement access control policies, a disaster recovery plan, and a centralized password management system. Additionally, the company should improve data encryption, intrusion detection, and employee access restrictions to meet compliance standards. Future work includes expanding the project to perform a more detailed risk analysis and integrating automation to streamline monitoring and reporting.

