# Networkwalks-B082-WEEK3-CRACKING-PASSWORDS-LABS
Cracked three password-locked PDFs using John the Ripper and Networkwalks' browser-based cracking tool, then pushed further—AI-assisted automation and a patient portal breach. Weak passwords fell in seconds. Week 3 proved credentials remain the weakest link. 🔓💻
Week 3 — Password Cracking

Networkwalks Academy — Cybersecurity & Ethical Hacking Internship

---

Status: Completed
Internship: Cybersecurity & Ethical Hacking
Tool Category: Password Recovery & Cryptanalysis
Modules: 4
License: Educational Use

---

📖 Overview

This repository documents my Week 3 project deliverables, which focused on recovering passwords from three encrypted PDF files (My Locked PDF1/2/3.pdf) using two mandatory approaches. Additionally, I completed two optional exercises that extended these techniques into real-world attack scenarios.

Module Task Tools
Core John the Ripper John + Johnny GUI
Core Networkwalks Tools Hash Calculator + Password Cracker (browser-based)
Optional 1 AI-Assisted Cracking Claude Desktop + HexStrike MCP + JTR
Optional 2 Mediroza Patient Portal Exploit Burp Suite Intruder + Networkwalks Tools

Note: Both core modules were required with no alternatives. I completed both optional exercises as well.

---

🧠 Background

Password cracking involves recovering a password from stored data or protected files. When a file (PDF, ZIP, Office document) is password-locked, the password isn't stored directly—instead, a cryptographic hash (a scrambled representation) is stored. Recovery follows a two-step process:

1. Extract the hash from the locked file using tools like pdf2john or hash extractors
2. Crack the hash by attempting candidate passwords (dictionary or wordlist attacks) until a match is found

This approach works because many users choose weak, predictable passwords.

---

📂 Repository Structure

```
week3-password-cracking/
├── README.md
├── john-the-ripper/                    # Core Module 1 — JTR + Johnny GUI
│   ├── writeup.md
│   └── 01–06 screenshots
├── networkwalks-tools/                 # Core Module 2 — NW Hash Calculator + Cracker
│   ├── writeup.md
│   └── 01–11 screenshots
├── optional-1-ai-assisted-cracking/    # Claude + HexStrike MCP + JTR Integration
│   ├── writeup.md
│   └── 01–03 screenshots
├── optional-2-mediroza-portal-exploit/ # Burp Suite Login Brute-Force + Report Cracking
│   ├── writeup.md
│   ├── mediroza-patient-records/       # Recovered patient reports from portal
│   └── 01–09 screenshots
└── targets/                            # Locked PDFs provided for the lab
    └── My Locked PDF1/2/3.pdf
```

---

🏆 Results

Target Cracked Password
My Locked PDF1.pdf password1
My Locked PDF2.pdf password1
My Locked PDF3.pdf 1qaz2wsx
Mediroza Portal (Admin) — Optional 2 password123
patient_report_001.pdf — Optional 2 123456
patient_report_002.pdf — Optional 2 iloveyou
patient_report_003.pdf — Optional 2 princess

---

💡 Key Takeaways

· Short, common passwords (≤8 characters, dictionary words, keyboard patterns) can be cracked in seconds to minutes
· Strong passwords (12+ characters, mixed case, symbols, numbers) can take years to crack using brute-force
· Hashing is one-way (used for validation); encryption is two-way (can be reversed with the correct key)
· Wordlist quality is critical — most successful cracks here occurred during the first pass against built-in lists or rockyou.txt
· The same technique scales from a single locked file to real login forms (Optional 2) and can be automated through AI agents (Optional 1)—the core methodology remains consistent throughout

---

🎥 Video Walkthrough

A comprehensive video walkthrough of this lab is available on LinkedIn:
🔗 Watch Here

---

🙏 Acknowledgements

Special thanks to Networkwalks Academy and my instructor Waqas Karim (CCIE) for their guidance and mentorship throughout this lab.

---

👤 Author

Nason Kasumpa
Cybersecurity & Ethical Hacking Intern — Networkwalks Academy
My LinkedIn Accound is 
https://www.linkedin.com/in/nason-kasumpa-9763ba432/
---

📌 Project Information

Attribute Details
Organization Networkwalks Academy
Program Cybersecurity & Ethical Hacking Internship
Week 03
Project Type Password Cracking & Pentesting Lab

---

This repository is for educational purposes only. All activities were performed in controlled lab environments with proper authorization.
