# Secure-Personal-Workstation-Lab
Home lab project demonstrating full-disk encryption, firewall, antivirus, malware defense, and layered security best practices.
- Full-disk encryption (BitLocker)
- Firewall configuration
- Antivirus / Anti-malware setup
- Malware simulation and response
- Backup strategies (offline and cloud)
- Layered security with application-level encryption and 2FA

## Skills Demonstrated
- Endpoint security and malware defense
- Network security and firewall configuration
- Data encryption and recovery
- Backup and disaster recovery planning
- Security documentation and visualization

## Lab Setup Steps
1. Enable BitLocker and configure TPM + recovery key.
2. Install and configure firewall rules (Windows Defender or pfSense VM).
3. Install antivirus / anti-malware software and run scans.
4. Safely simulate malware (EICAR test file) in an isolated VM.
5. Implement backup strategy with external drive and cloud storage.
6. (Optional) Encrypt sensitive files using VeraCrypt or 7-Zip AES.
7. Enable safe browsing and 2FA for personal accounts.
8. Document lab with screenshots and diagrams.

## Diagram

       +------------------------+
       |   Internet / Wi-Fi     |
       +------------------------+
                 |
         [Firewall / Router]
                 |
   +-----------------------------+
   |      Secured Workstation    |
   |-----------------------------|
   | - BitLocker FDE             |
   | - Antivirus & Malware       |
   | - Application-level Encryption (VeraCrypt) |
   | - 2FA & Password Manager    |
   | - Safe Browsing             |
   +-----------------------------+
                 |
         [Backup: External Drive / Cloud]


## Screenshots
- Include images of BitLocker status, firewall rules, and antivirus scans.

## Outcome
- A fully secured personal workstation demonstrating layered security practices suitable for professional cybersecurity portfolios.
