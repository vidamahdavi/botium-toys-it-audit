# Controls & Compliance Checklist — Botium Toys Internal IT Audit

This checklist evaluates Botium Toys’ security controls and compliance posture, based on the **NIST Cybersecurity Framework (CSF)** and key regulatory standards (**PCI DSS, GDPR, SOC**).  

---

## ✅ Controls Assessment

| Control | In Place? | Explanation |
|---------|-----------|-------------|
| Least Privilege | ❌ No | All employees have access to customer data; privileges need to be limited to reduce breach risk. |
| Disaster Recovery Plans | ❌ No | No DR plans exist; required to ensure business continuity.
| Password Policies | ❌ No | Minimal requirements; weak policy could allow easier unauthorized access:contentReference.
| Separation of Duties | ❌ No | Not implemented; CEO manages payroll and daily ops, increasing fraud risk:contentReference.
| Firewall | ✅ Yes | Appropriately blocks traffic based on defined rules:contentReference.
| Intrusion Detection System (IDS) | ❌ No | Needed to identify intrusions; currently missing.
| Backups | ❌ No | Critical data not backed up; risks business continuity:contentReference.
| Antivirus Software | ✅ Yes | Installed and monitored regularly:contentReference.
| Legacy Systems Monitoring | ⚠️ Partial | Legacy systems monitored, but not on a schedule; unclear intervention policies:contentReference.
| Encryption | ❌ No | Sensitive data not encrypted; confidentiality risk.
| Password Management System | ❌ No | None in place; impacts security and IT productivity:contentReference.
| Physical Locks | ✅ Yes | Offices, storefront, and warehouse secured with locks:contentReference.
| CCTV Surveillance | ✅ Yes | CCTV system installed and functioning:contentReference.
| Fire Detection/Prevention | ✅ Yes | Fire alarms and prevention systems in place:contentReference.

---

## 💳 PCI DSS Compliance

| Best Practice | In Place? | Explanation |
|---------------|-----------|-------------|
| Only authorized users access cardholder data | ❌ No | All employees currently have access to sensitive data:contentReference.
| Card data processed in a secure environment | ❌ No | No encryption; unrestricted internal access:contentReference.
| Data encryption for transactions | ❌ No | No encryption of financial data:contentReference.
| Secure password management policies | ❌ No | Nominal policies; no password manager in place:contentReference.

---

## 🌍 GDPR Compliance

| Best Practice | In Place? | Explanation |
|---------------|-----------|-------------|
| E.U. customer data kept private/secure | ❌ No | No encryption used to protect customer financial information:contentReference.
| 72-hour breach notification plan | ✅ Yes | Plan in place to notify E.U. customers within 72 hours:contentReference.
| Data classified and inventoried | ⚠️ Partial | Assets inventoried, but not classified.
| Privacy policies/procedures enforced | ✅ Yes | Policies/procedures developed and enforced.

---

## 📊 SOC 1 / SOC 2 Compliance

| Best Practice | In Place? | Explanation |
|---------------|-----------|-------------|
| User access policies established | ❌ No | No least privilege or separation of duties; all employees have access.
| Sensitive data (PII/SPII) confidential/private | ❌ No | Encryption not in use; confidentiality not ensured.
| Data integrity maintained | ✅ Yes | Data is consistent, complete, and validated.
| Data available to authorized users only | ❌ No | Data available to all employees instead of role-based access.

---

## 📌 Recommendations

- Implement **Least Privilege** and **Separation of Duties**  
- Create a **Disaster Recovery Plan** with tested backups  
- Strengthen **Password Policy** and deploy a **Password Manager**  
- Implement **Encryption** for PCI and PII data  
- Deploy an **Intrusion Detection System (IDS)**  
- Schedule **Legacy System Monitoring** and interventions  

These changes will reduce risk, improve compliance posture, and strengthen Botium Toys’ overall security maturity.
