# Botium Toys: Scope, Goals, and Risk Assessment Report

## Scope and Goals of the Audit

### Scope
The scope of this audit covers the entire security program at Botium Toys. This includes:
- Employee equipment and devices
- Internal networks
- Organizational systems and data

The audit reviews existing assets, security controls, and compliance practices currently in place at Botium Toys.

### Goals
The goals of this audit are to:
- Assess existing assets managed by the organization
- Complete the controls and compliance checklist
- Identify missing or weak controls
- Determine which security and compliance best practices should be implemented to improve Botium Toys’ overall security posture

---

## Current Assets

Assets managed by the IT department include:
- On-premises equipment for in-office business needs
- Employee equipment, including:
  - End-user devices (desktops, laptops, smartphones)
  - Remote workstations
  - Headsets, cables, keyboards, mice, docking stations
  - Surveillance cameras
- Storefront products available for retail sale on-site and online, stored in the adjoining warehouse
- Management of systems, software, and services, including:
  - Accounting systems
  - Telecommunication systems
  - Databases
  - Security systems
  - E-commerce and inventory management systems
- Internet access
- Internal network infrastructure
- Data retention and storage systems
- Legacy system maintenance, including end-of-life systems requiring human monitoring

---

## Risk Assessment

### Risk Description
Botium Toys currently has inadequate asset management practices. In addition, the organization does not have all required security controls in place and may not be fully compliant with U.S. and international regulations and standards. These gaps increase the likelihood of data exposure, system compromise, and regulatory penalties.

---

### Control Best Practices
According to the NIST Cybersecurity Framework (CSF), the first core function is **Identify**. Botium Toys needs to:
- Identify and inventory all assets
- Classify assets based on sensitivity and criticality
- Determine the potential impact of asset loss on business continuity

Without proper identification and classification, security controls cannot be effectively implemented or prioritized.

---

### Risk Score
On a scale of 1 to 10, the overall risk score is **8**, indicating a **high-risk posture**. This score reflects the lack of security controls and insufficient adherence to compliance best practices.

---

### Additional Comments

The potential impact from the loss of an asset is rated as **medium**, as the IT department does not have full visibility into which assets are most critical. However, the overall risk to assets and the likelihood of regulatory fines are **high** due to weak controls and incomplete compliance with data protection regulations.

Key findings include:
- All employees currently have access to internally stored data, including potential access to cardholder data and customer PII/SPII.
- Encryption is not used to ensure the confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the internal database.
- Access controls enforcing least privilege and separation of duties have not been implemented.
- Availability and data integrity controls are in place and managed by the IT department.
- A firewall is deployed and blocks traffic based on defined security rules.
- Antivirus software is installed and regularly monitored by the IT department.
- An intrusion detection system (IDS) has not been implemented.
- No disaster recovery plans exist, and critical data backups are not maintained.
- A breach notification plan exists to notify E.U. customers within 72 hours, and privacy policies and procedures are documented and enforced.
- Password policies exist but do not meet modern complexity requirements.
- There is no centralized password management system, resulting in productivity issues during password recovery and reset processes.
- Legacy systems are monitored, but there is no defined maintenance schedule or documented intervention procedures.
- Physical security controls at the offices, storefront, and warehouse are adequate and include locks, up-to-date CCTV surveillance, and functioning fire detection and prevention systems.
