# Medi-Tech-Governance-Project
Cloud governance &amp; third-party risk project (CompTIA Security+ Governance &amp; Risk)
# Medi-Tech Cloud Governance & Third-Party Risk Project

A governance and third-party risk management project simulating a healthcare organization outsourcing customer data to a cloud SaaS provider. This scenario aligns with **CompTIA Security+ (SY0-701)** Governance & Risk objectives and demonstrates practical skills in data roles, qualitative risk assessments, contractual controls, and executive risk strategy.

---

## 1. Scenario Overview

**Medi-Tech Solutions** (the **Controller**) is migrating its CRM platform and customer data to **AeroData Cloud Services** (the **Processor**).  
As the Information Security Officer (ISO), you are responsible for ensuring that the outsourcing relationship is governed securely and that data privacy, regulatory compliance, and operational risks are properly mitigated.

---

## 2. My Role

**Role:** Information Security Officer (ISO) for Medi-Tech Solutions  
**Primary Responsibilities:**

- Define accountability roles for data handling  
- Identify and assess new threats introduced by cloud migration  
- Document required third-party contractual controls  
- Recommend a risk treatment strategy aligned with business objectives  

This project demonstrates how an ISO governs cloud third-party relationships in a regulated industry (healthcare).

---

## 3. Project Objective

The goal of this project is to ensure Medi-Tech’s cloud migration maintains:

- **Data security**
- **Regulatory compliance**
- **Operational resilience**
- **Effective third-party oversight**

Medi-Tech aims to scale operations and improve efficiency while maintaining strong governance over its cloud provider.

---

## 4. Vendor & Services

- **Vendor:** AeroData Cloud Services  
- **Service Type:** SaaS CRM + customer data hosting  
- **Data Processed:**  
  - Customer **PII** (Personally Identifiable Information)  
  - Sensitive account and billing data  
- **Vendor Role:** Data Processor & Custodian  
- **Medi-Tech Role:** Data Controller & Owner  

---

## 5. Project Deliverables

This repository includes four governance deliverables:

### **Deliverable 1 — Data Role Matrix (CompTIA Objective 5.1)**
Defines data accountability roles between Medi-Tech and AeroData.

### **Deliverable 2 — Qualitative Risk Assessment**
Identifies high-impact risks introduced by cloud migration and provides mitigation strategies.

### **Deliverable 3 — Third-Party Agreement Requirements**
Lists mandatory contractual clauses to enforce data protection, oversight, and compliance.

### **Deliverable 4 — Risk Strategy Recommendation (CompTIA Objective 5.2)**
Provides an executive-level decision recommendation: avoid, transfer, accept, or mitigate.

Each deliverable is included as a separate file in this repository for clarity.

---

## 6. Deliverable 1: Data Role Matrix

| Role               | Entity                    | Justification                                                                                                   |
|--------------------|---------------------------|-----------------------------------------------------------------------------------------------------------------|
| **Data Owner**     | Medi-Tech Solutions       | The business unit creating and using the data (customer service/sales) owns the data.                          |
| **Data Controller**| Medi-Tech Solutions       | Medi-Tech determines how customer PII is collected and processed; sets policies and high-level decisions.      |
| **Data Processor** | AeroData Cloud Services   | AeroData processes data on behalf of Medi-Tech according to Medi-Tech’s instructions.                          |
| **Data Custodian** | AeroData Cloud Services   | AeroData manages servers, infrastructure, patching, backups, and day-to-day technical controls.                |

This matrix clarifies ownership, control, and operational responsibility for sensitive customer PII.

---

## 7. Deliverable 2: Qualitative Risk Assessment

### **Risk Register**

| Risk ID | Description                                                                                                                                              | Likelihood | Impact | Mitigation Strategy                                                                                                             |
|--------:|----------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|--------|---------------------------------------------------------------------------------------------------------------------------------|
| **R-1** | Insider Threat at AeroData – A privileged AeroData employee misuses access to steal customer PII.                                                        | Medium    | High   | Require annual **SOC 2 Type II** reports proving strong access control, logging, and monitoring for privileged accounts.        |
| **R-2** | Vendor Fails to Patch Critical Vulnerabilities – An unpatched exploit compromises Medi-Tech data (e.g., Log4j).                                         | Medium    | High   | Mandate a **patch management SLA** requiring critical vulnerabilities to be patched within **7 days**.                          |
| **R-3** | Data Sovereignty / Jurisdiction Issue – AeroData stores EU customer data outside the approved region, causing GDPR exposure.                            | Low       | High   | Contractually require all EU/Canadian data to remain in pre-approved jurisdictions only.                                        |

This assessment focuses on **third-party risk**, **supply-chain risk**, and **cloud security governance**.

---

## 8. Deliverable 3: Third-Party Agreement Requirements

Two contractual requirements are mandatory to ensure data protection and risk oversight.

### **1. Data Processing Agreement (DPA)**  
**Purpose:**  
- Defines Medi-Tech as the Controller and AeroData as the Processor  
- Mandates compliance with privacy laws for PII/PHI  
- Requires technical and organizational controls  
- Ensures AeroData processes data only according to Medi-Tech’s instructions  

### **2. Right-to-Audit Clause**  
**Purpose:**  
- Grants Medi-Tech the right to perform independent audits  
- Allows review of SOC 2 reports, penetration tests, and logs  
- Ensures AeroData maintains the required security posture  
- Prevents reliance on blind trust  

These clauses directly reduce risk and provide legal + operational mechanisms for governance.

---

## 9. Deliverable 4: Executive Risk Strategy Recommendation

### **Recommended Strategy: MITIGATE**

**Reasoning:**

- **Avoidance** is not realistic because AeroData is required for scaling business operations.  
- **Acceptance** is too risky due to regulatory fines, customer harm, and reputational damage.  
- **Transfer** (insurance) alone is insufficient for compliance.

### **Mitigation Will Include:**

1. **Contractual Controls**  
   - Data Processing Agreement (DPA)  
   - Right-to-Audit Clause  

2. **Technical Controls**  
   - Encryption at rest and in transit  
   - Strong access control for privileged accounts  
   - Mandatory SOC 2 Type II reports  
   - Aggressive patch management requirements  

Mitigation reduces the **residual risk** to an acceptable level while enabling the business objective.

---

## 10. Key Skills Demonstrated

This project highlights practical hands-on skills in:

- Governance, Risk, and Compliance (GRC)  
- Third-Party Risk Management  
- Cloud governance frameworks  
- Data ownership, accountability, and role definitions  
- Vendor oversight & supply-chain security  
- Contractual security controls (DPA, Right-to-Audit)  
- Qualitative risk assessments  
- Executive-level risk strategy recommendations  
- Alignment with **CompTIA Security+ (SY0-701)** objectives  

---

## 11. How to Navigate This Repository

- Use the README for scenario context and project overview  
- Open each deliverable file to explore the in-depth analysis  
- Review the Data Role Matrix first, then progress to the risk assessment and strategy  

This project serves as a portfolio example demonstrating real-world GRC and cloud security governance capabilities.

---

