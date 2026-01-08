# 🛡️ Secure Personal Workstation Lab

[![BitLocker](https://img.shields.io/badge/BitLocker-Enabled-green)](https://learn.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-overview) 
[![Firewall](https://img.shields.io/badge/Firewall-Configured-blue)](https://www.pfsense.org/) 
[![Antivirus](https://img.shields.io/badge/Antivirus-Secured-yellow)](https://www.microsoft.com/en-us/windows/comprehensive-security) 
[![Backup](https://img.shields.io/badge/Backup-Implemented-brightgreen)](https://www.veracrypt.fr/en/Home.html) 
[![2FA](https://img.shields.io/badge/2FA-Enabled-blueviolet)](https://www.yubico.com/)

A **home lab project** demonstrating **layered security practices** on a personal workstation. Focus areas include full-disk encryption, firewall configuration, malware defense, backups, and application-level encryption.

---

## 🌟 Features
- **Full-disk encryption** with BitLocker  
- **Firewall setup & configuration** (Windows Defender / pfSense VM)  
- **Antivirus & anti-malware protection**  
- **Malware simulation** with EICAR test file in isolated VM  
- **Backup strategies**: external drive + cloud storage  
- **Application-level encryption**: VeraCrypt / 7-Zip AES  
- **Two-factor authentication (2FA)** and safe browsing  
- **Security documentation** with screenshots & diagrams  

---

## 🛠️ Tools & Skills

| Category                | Tools / Skills Used                                |
|-------------------------|--------------------------------------------------|
| **Endpoint Security**    | Windows 10/11, BitLocker, Antivirus, Malware Defense |
| **Network Security**     | Windows Defender Firewall, pfSense VM           |
| **Data Encryption**      | VeraCrypt, 7-Zip AES                            |
| **Backup & Recovery**    | External Drives, Cloud Storage (OneDrive / Google Drive) |
| **Monitoring & Logging** | Splunk, Wireshark (optional)                     |
| **Account Security**     | 2FA, Safe Browsing Practices, Password Manager   |
| **Documentation**        | Screenshots, Diagrams, Markdown / Draw.io        |

---

## ⚙️ Lab Setup Steps
1. Enable **BitLocker** with TPM & configure recovery key  
2. Install & configure **firewall rules** (Windows Defender / pfSense VM)  
3. Install antivirus / anti-malware software and perform scans  
4. Safely simulate malware with **EICAR test file** in an isolated VM  
5. Implement **backup strategy** with external drive and cloud storage  
6. *(Optional)* Encrypt sensitive files using **VeraCrypt** or **7-Zip AES**  
7. Enable **safe browsing practices** and **2FA** for personal accounts  
8. Document the lab with **screenshots & diagrams**  

---

## 📊 Lab Diagram

            Internet / Wi-Fi
                 │
         ┌───────┴───────┐
         │ Firewall /     │
         │ Router         │
         └───────┬───────┘
                 │
       ┌─────────┴─────────┐
       │  Secured Workstation│
       │-------------------│
       │ • BitLocker FDE    │
       │ • Antivirus / Malware │
       │ • App Encryption (VeraCrypt) │
       │ • 2FA & Password Manager │
       │ • Safe Browsing    │
       └─────────┬─────────┘
                 │
         Backup: External Drive / Cloud


Secured Workstation
- BitLocker FDE
- Antivirus & Malware
- Application-level Encryption (VeraCrypt)
- 2FA & Password Manager
- Safe Browsing
  

---

## 🖼️ Screenshots
Include images of:  
- BitLocker status  
- Firewall rules configuration  
- Antivirus / malware scan results  

---

## ✅ Outcome
A **fully secured personal workstation** demonstrating **layered security practices**, suitable for a **professional cybersecurity portfolio**. Highlights skills in **endpoint protection, network security, encryption, backups, and documentation**.

---

## 💡 Optional Enhancements
- Integrate **Windows Defender Exploit Guard**  
- Test **ransomware protection strategies**  
- Automate backups with **PowerShell scripts**  
- Add **network monitoring & logs** with **Splunk / Wireshark**  

---

## 📈 Demo / GIF (Optional)
> Add a short GIF or images showing BitLocker enabled, firewall rules, and malware simulation in VM.  
> Example: `![Demo](path/to/demo.gif)`  

---

## ⚡ Tips for Recruiters Viewing This Repo
- Shows practical **endpoint & network security skills**  
- Demonstrates **data protection & disaster recovery** knowledge  
- Includes **hands-on simulation & documentation**, not just theory  
- Highlights **cloud storage & 2FA security awareness**  



