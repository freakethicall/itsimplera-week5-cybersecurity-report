# itsimplera-week5-cybersecurity-report
ITSimplera Internship — Week 5: Network Enumeration & Vulnerability Assessment
📌 Overview

This repository documents Week 5 of my Cyber Security Analyst Internship at ITSimplera, focused on network enumeration, service discovery, and vulnerability assessment against a Metasploitable 2 target in an isolated lab environment.

All testing was performed strictly within a controlled, self-hosted virtual lab for educational purposes.

🎯 Objectives
Perform progressive Nmap scanning (default → version detection → OS fingerprinting → aggressive → full port range)
Enumerate and document all discovered services
Research CVEs associated with identified service versions
Compare scan methodologies (speed, depth, applicability)
Conduct a full security analysis with attack scenarios, risk ratings, and remediation mapped to industry standards (CIS/NIST/OWASP)
🧪 Lab Environment
Component	Details
Attacker Machine	Kali Linux (native, dual-boot)
Target Machine	Metasploitable 2 (VMware)
Network Mode	Host-only / NAT (isolated lab subnet)
Tools Used	Nmap 7.99

⚠️ This lab is fully isolated and used solely for authorized educational penetration testing practice.

📂 Repository Structure
ITSimplera_Week5/
├── scans/
│   ├── scan1_default.txt
│   ├── scan2_version.txt
│   ├── scan3_osdetect.txt
│   ├── scan4_aggressive.txt
│   └── scan5_allports.txt
├── screenshots/
│   └── (terminal output screenshots per scan)
├── diagram/
│   └── (attack surface / network diagram)
└── README.md
🔍 Methodology
Task	Description
Task 1	5 Nmap scans — default, -sV, -O, -A, -p-
Task 2	Service enumeration table (port, protocol, service, version, status, purpose)
Task 3	Vulnerability research — CVE ID, CVSS score, severity, description, fix
Task 4	Scan comparison — speed, depth, information gathered, real-world use
Task 5	Security analysis — attack scenarios, risk levels, remediation, hardening, verification
🛠️ Scan Commands Used
bash
nmap $TARGET
nmap -sV $TARGET
sudo nmap -O $TARGET
sudo nmap -A $TARGET
sudo nmap -p- $TARGET
📄 Deliverables
Full professional Word/PDF report (ITSimplera-branded)
Network diagram
Scan output screenshots
Raw Nmap scan logs
👤 Author

Abdul Moiz Zahoor (FREAK) BS Cybersecurity, Semester 5 — Shifa Tameer-e-Millat University, Islamabad Certifications: PNPT | CEH | CCNA | ICIP (OPSWAT)

🔗 LinkedIn 🔗 GitHub

⚠️ Disclaimer

This repository is for educational and authorized lab testing purposes only. All scanning and exploitation activity was performed against a self-hosted, intentionally vulnerable target (Metasploitable 2) within a private, isolated network. No external or unauthorized systems were tested.
