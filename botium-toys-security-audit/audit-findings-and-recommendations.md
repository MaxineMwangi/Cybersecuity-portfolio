# Audit Findings

Based on the risk assessment and controls and compliance checklist, the following key findings were identified:

## 1. Weak Access Control Practices
- Least privilege and separation of duties are not implemented.
- All employees have access to sensitive internal data, including customer PII and cardholder data.
- This increases the risk of insider threats and unauthorized data exposure.

## 2. Lack of Data Protection Mechanisms
- Customer credit card information is stored and processed without encryption.
- Sensitive data confidentiality requirements under PCI DSS and GDPR are not fully met.

## 3. Insufficient Monitoring and Detection
- No intrusion detection system (IDS) is in place.
- Limited visibility into potential malicious activity within the network.

## 4. Business Continuity Gaps
- No disaster recovery plan or data backups exist.
- A system failure or cyber incident could result in prolonged downtime and data loss.

## 5. Weak Password and Identity Management
- Password policies do not meet current complexity requirements.
- No centralized password management system exists, leading to inconsistent enforcement.

## 6. Asset Management and Legacy System Risks
- Assets are not fully inventoried or classified.
- Legacy systems are monitored without a defined maintenance schedule.

# Recommendations

To reduce risk and improve Botium Toys’ security posture, the following recommendations are proposed:

## 1. Implement Access Control Best Practices
- Enforce least privilege and role-based access control (RBAC).
- Introduce separation of duties for systems handling sensitive data.

## 2. Strengthen Data Protection
- Implement encryption for data at rest and in transit, particularly for cardholder and PII data.
- Limit access to sensitive data to authorized personnel only.

## 3. Improve Monitoring and Detection
- Deploy an intrusion detection system (IDS) to enhance visibility into network activity.
- Establish regular security monitoring procedures.

## 4. Establish Business Continuity Planning
- Develop and document a disaster recovery plan.
- Implement regular backups of critical systems and data.

## 5. Enhance Identity and Password Management
- Update password policies to meet modern complexity standards.
- Deploy a centralized password management solution.

## 6. Formalize Asset and Legacy System Management
- Create and maintain an asset inventory and classification system.
- Define scheduled maintenance and intervention procedures for legacy systems.

