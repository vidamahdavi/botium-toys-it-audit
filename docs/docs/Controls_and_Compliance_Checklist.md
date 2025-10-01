# Controls & Compliance Checklist — Botium Toys Internal IT Audit

This checklist evaluates Botium Toys’ security controls and compliance posture, based on the **NIST Cybersecurity Framework (CSF)** and key regulatory standards (**PCI DSS, GDPR, SOC**).  

---

## ✅ Controls Assessment

| Control | In Place? | Explanation |
|---------|-----------|-------------|
| Least Privilege | ❌ No | All employees have access to customer data; privileges need to be limited to reduce breach risk:contentReference[oaicite:0]{index=0}. |
| Disaster Recovery Plans | ❌ No | No DR plans exist; required to ensure business continuity:contentReference[oaicite:1]{index=1}. |
| Password Policies | ❌ No | Minimal requirements; weak policy could allow easier unauthorized access:contentReference[oaicite:2]{index=2}. |
| Separation of Duties | ❌ No | Not implemented; CEO manages payroll and daily ops, increasing fraud risk:contentReference[oaicite:3]{index=3}. |
| Firewall | ✅ Yes | Appropriately blocks traffic based on defined rules:contentReference[oaicite:4]{index=4}. |
| Intrusion Detection System (IDS) | ❌ No | Needed to identify intrusions; currently missing:contentReference[oaicite:5]{index=5}. |
| Backups | ❌ No | Critical data not backed up; risks business continuity:contentReference[oaicite:6]{index=6}. |
| Antivirus Software | ✅ Yes | Installed and monitored regularly:contentReference[oaicite:7]{index=7}. |
| Legacy Systems Monitoring | ⚠️ Partial | Legacy systems monitored, but not on a schedule; unclear intervention policies:contentReference[oaicite:8]{index=8}. |
| Encryption | ❌ No | Sensitive data not encrypted; confidentiality risk:contentReference[oaicite:9]{index=9}. |
| Password Management System | ❌ No | None in place; impacts security and IT productivity:contentReference[oaicite:10]{index=10}. |
| Physical Locks | ✅ Yes | Offices, storefront, and warehouse secured with locks:contentReference[oaicite:11]{index=11}. |
| CCTV Surveillance | ✅ Yes | CCTV system installed and functioning:contentReference[oaicite:12]{index=12}. |
| Fire Detection/Prevention | ✅ Yes | Fire alarms and prevention systems in place:contentReference[oaicite:13]{index=13}. |

---

## 💳 PCI DSS Compliance

| Best Practice | In Place? | Explanation |
|---------------|-----------|-------------|
| Only authorized users access cardholder data | ❌ No | All employees currently have access to sensitive data:contentReference[oaicite:14]{index=14}. |
| Card data processed in a secure environment | ❌ No | No encryption; unrestricted internal access:contentReference[oaicite:15]{index=15}. |
| Data encryption for transactions | ❌ No | No encryption of financial data:contentReference[oaicite:16]{index=16}. |
| Secure password management policies | ❌ No | Nominal policies; no password manager in place:contentReference[oaicite:17]{index=17}. |

---

## 🌍 GDPR Compliance

| Best Practice | In Place? | Explanation |
|---------------|-----------|-------------|
| E.U. customer data kept private/secure | ❌ No | No encryption used to protect customer financial information:contentReference[oaicite:18]{index=18}. |
| 72-hour breach notification plan | ✅ Yes | Plan in place to notify E.U. customers within 72 hours:contentReference[oaicite:19]{index=19}. |
| Data classified and inventoried | ⚠️ Partial | Assets inventoried, but not classified:contentReference[oaicite:20]{index=20}. |
| Privacy policies/procedures enforced | ✅ Yes | Policies/procedures developed and enforced:contentReference[oaicite:21]{index=21}. |

---

## 📊 SOC 1 / SOC 2 Compliance

| Best Practice | In Place? | Explanation |
|---------------|-----------|-------------|
| User access policies established | ❌ No | No least privilege or separation of duties; all employees have access:contentReference[oaicite:22]{index=22}. |
| Sensitive data (PII/SPII) confidential/private | ❌ No | Encryption not in use; confidentiality not ensured:contentReference[oaicite:23]{index=23}. |
| Data integrity maintained | ✅ Yes | Data is consistent, complete, and validated:contentReference[oaicite:24]{index=24}. |
| Data available to authorized users only | ❌ No | Data available to all employees instead of role-based access:contentReference[oaicite:25]{index=25}. |

---

## 📌 Recommendations

- Implement **Least Privilege** and **Separation of Duties**  
- Create a **Disaster Recovery Plan** with tested backups  
- Strengthen **Password Policy** and deploy a **Password Manager**  
- Implement **Encryption** for PCI and PII data  
- Deploy an **Intrusion Detection System (IDS)**  
- Schedule **Legacy System Monitoring** and interventions  

These changes will reduce risk, improve compliance posture, and strengthen Botium Toys’ overall security maturity.
