<img width="1920" height="1080" alt="n1" src="https://github.com/user-attachments/assets/c66b1247-f493-450d-9ea4-c1bf2111f8d2" /># Networkwalks-B082-WEEK3-CRACKING-PASSWORDS-LABS
Cracked three password-locked PDFs using John the Ripper and Networkwalks' browser-based cracking tool, then pushed further—AI-assisted automation and a patient portal breach. Weak passwords fell in seconds. Week 3 proved credentials remain the weakest link. 🔓💻
Week 3 — Password Cracking

Networkwalks Academy — Cybersecurity & Ethical Hacking Internship

📋 General Steps Taken
1.	Download John & Johnny
2.	Add john.exe file to the Johnny GUI
3.	Download the PDF to be cracked
4.	Save has value, upload file and start new attack
5.	Test the cracked password
Step 1 - Download John & Johnny
   <img width="186" height="173" alt="Screenshot 2026-08-29 224709" src="https://github.com/user-attachments/assets/853e12db-9967-47d7-b8f3-ddbff00532e4" />

Step 2 - Add john.exe file to the Johnny GUI
 
<img width="873" height="663" alt="Screenshot 2026-08-29 225048" src="https://github.com/user-attachments/assets/eb06fd21-5109-47ee-92e0-881dba05e61e" />

Step 3 - Download the PDF to be cracked
 <img width="821" height="205" alt="Screenshot 2026-08-29 224054" src="https://github.com/user-attachments/assets/d20cc961-7226-49f5-b0c5-33941ef24765" />

Step 4 - Save has value, upload file and start new attack
 


<img width="1920" height="1080" alt="number 1" src="https://github.com/user-attachments/assets/929f77fa-754c-4c26-b103-bac6709ef971" />





Step 5 - Test the cracked password
 <img width="1920" height="1080" alt="p3 3" src="https://github.com/user-attachments/assets/ac472af7-9083-43d5-8262-363a502b8bb8" />





Password Cracking with Networkwalks Tools
📋 General Steps Taken
1.	Uplaod locked PDF file to Networkwalks Hash Calculator

 
3.	Copy the PDF hash value into Networkwalks Password Cracker
 
4.	Open the locked PDF file and enter the cracked password
5.	 
Step 1 - Uplaod locked PDF file to Networkwalks Hash Calculator
Step 2 - Copy the PDF hash value into Networkwalks Password Cracker
Access Denied



Access Granted

Step 3 - Open the locked PDF file and enter the cracked password



🧠 What I've learnt
Throughout this lab, I have learnt about different tools that are used together in discovering the passwords for pdf files. There are tools like PDF Hash Extractor that extracts the has value of a pdf. That hash value is then pasted into a tool like John The Ripper GUI version which is connected to the john.exe file from John The Ripper cli version. When the hash file is uploaded to the software it is able to crack the password of the locked pdf file. There are other tools that can help in getting the hash value of a PDF file like https://networkwalks.com/hash-calculator/ . Networkwalks Password Cracker https://networkwalks.com/password-cracker/ is then used to reveal that password for the pdf file by using either its built in ist or through uploading a custom dictionary. It was observed when using the Networks Password Cracker, that the algorithm seemed to be a brute force methodology.
🔐 Copyright Notice
© 2026 Nason kasumpa jr . All Rights Reserved.
This repository, including its documentation, configurations, lab materials, and original content, is the property of Nason kasumpa. Unauthorized copying, reproduction, modification, redistribution, or commercial use of the original content without prior written permission is prohibited.
The materials are provided for educational and cybersecurity lab purposes only. Any third-party software, trademarks, or resources referenced in this repository remain the property of their respective owners.
Project Status
Completed ✅
About
No description, website, or topics provided.
Resources
Readme
Activity


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

Attribute Details
Organization Networkwalks Academy
Program Cybersecurity & Ethical Hacking Internship
Week 03
Project Type Password Cracking & Pentesting Lab

---

This repository is for educational purposes only. All activities were performed in controlled lab environments with proper authorization.
