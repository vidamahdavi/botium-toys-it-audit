# Audit Summary — Botium Toys (Internal IT Audit)

## Executive Summary
Botium Toys’ rapid growth in online operations has outpaced its security controls.  
My review of the IT manager’s scope, goals, and risk assessment revealed significant **gaps in access control, encryption, disaster recovery, and compliance readiness**.  
While physical and basic logical controls (firewall, antivirus, data integrity) are in place, the company faces elevated risks of **data breaches, non-compliance fines, and operational disruption**.

---

## Key Risks
- **Excessive privileges:** All employees can access sensitive customer and payment data:contentReference[oaicite:5]{index=5}  
- **No disaster recovery/backups:** No plan or copies of critical data in case of breach/outage:contentReference[oaicite:6]{index=6}  
- **Weak authentication:** Password requirements minimal; no password manager:contentReference[oaicite:7]{index=7}  
- **No intrusion detection system (IDS):** Limited ability to detect/respond to attacks:contentReference[oaicite:8]{index=8}  
- **Unencrypted sensitive data:** Cardholder and PII/SPII stored without encryption:contentReference[oaicite:9]{index=9}  

---

## Compliance Gaps
- **PCI DSS:** Card data not encrypted, unrestricted access to payment data, no strong password policy  
- **GDPR:** Assets inventoried but not classified; customer data not encrypted  
- **SOC (1/2):** No user access policy or least privilege controls; confidentiality of PII not enforced  

---

## Strengths
- Firewall blocks traffic with defined rules:contentReference[oaicite:10]{index=10}  
- Antivirus software installed and monitored regularly:contentReference[oaicite:11]{index=11}  
- Data integrity controls in place:contentReference[oaicite:12]{index=12}  
- Physical controls (locks, CCTV, fire detection) are sufficient:contentReference[oaicite:13]{index=13}  
- GDPR 72-hour breach notification plan exists:contentReference[oaicite:14]{index=14}  

---

## Recommendations
1. **Access Management**  
   - Enforce **Least Privilege** and **Separation of Duties**  
   - Create formal **user access policies** with quarterly reviews  

2. **Identity & Authentication**  
   - Strengthen password policies (complexity, rotation on compromise)  
   - Implement a **password management system**  

3. **Data Protection**  
   - Encrypt sensitive data (PCI and PII/SPII) at rest and in transit  
   - Classify assets and maintain an updated inventory  

4. **Resilience & Detection**  
   - Implement a **Disaster Recovery & Backup Plan**  
   - Deploy an **IDS/EDR solution**  
   - Establish scheduled monitoring for legacy systems  

5. **Compliance Alignment**  
   - **PCI DSS:** Encrypt cardholder data, restrict access, enforce strong password policy  
   - **GDPR:** Classify assets, strengthen privacy controls, maintain notification procedures  
   - **SOC:** Document access policies, enforce confidentiality, validate data availability  

---

## Outcome
By closing these control and compliance gaps, Botium Toys can significantly **reduce risk exposure, strengthen compliance alignment, and improve resilience** against both cyber and operational threats.
