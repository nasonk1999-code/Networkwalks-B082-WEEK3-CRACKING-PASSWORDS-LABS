WEEK 3-PASSWORD CRACKING
Cracked three password-locked PDFs using John the Ripper and Networkwalks' browser-based cracking tool, then pushed further—AI-assisted automation and a patient portal breach. Weak passwords fell in seconds. Week 3 proved credentials remain the weakest link. 🔓💻

networkwalks-B082-week1-Week-3-Password-Cracking
Tech Stack • Networking • Credits
🛠️ Tech Stack
  
🌐 Networking
  
🤝 Credits
  
📌 Overview
Crack the password of attached PDF file (My Locked PDF1.pdf) using JTR JOHN and JTR JOHNNY tools on my Windows PC.
🖥️ Lab Environment
Component	Configuration
Host OS	Windows
Attack Machine	Windows 11
Project	Week 3 – Module 1 & 2
Focus	Password Cracking
Primary Tool	John the Ripper (JTR) & Network Walks Tools
GUI Tool	Johnny
Program	Network Walks
Files Used
•	John The Ripper : https://www.openwall.com/john/
•	Johnny [GUI] : https://openwall.info/wiki/john/johnny
•	Network Walks Hash Calculator : https://networkwalks.com/hash-calculator/
•	Network Walks Password Cracker : https://networkwalks.com/password-cracker
📋 General Steps Taken
1.	Download John & Johnny
<img width="186" height="173" alt="Screenshot 2026-08-29 224709" src="https://github.com/user-attachments/assets/23fd4910-e04c-4716-955f-ff25ae049ed1" />

2.	Add john.exe file to the Johnny GUI
3.	<img width="873" height="663" alt="Screenshot 2026-08-29 225048" src="https://github.com/user-attachments/assets/37f3a273-4fe0-4bae-82af-a312eeb5a1fc" />

4.	Download the PDF to be cracked
<img width="821" height="205" alt="Screenshot 2026-08-29 224054" src="https://github.com/user-attachments/assets/4dd320bd-6a76-4a20-8e86-2a61cb5cc1d1" />


5.	Save has value, upload file and start new attack
   <img width="1920" height="1080" alt="number 1" src="https://github.com/user-attachments/assets/bbbc2182-b0d2-4a8d-a63b-cf124b31b264" />
   

6. Save the copied words on a notepad
<img width="1655" height="908" alt="p1 (2)" src="https://github.com/user-attachments/assets/1d992b86-8c82-461a-8f48-82776799a7bc" />


7. Use the copied word from notepad and run the saved value upload it on john the ripper
   <img width="997" height="750" alt="p1 1" src="https://github.com/user-attachments/assets/52479169-3b09-47ae-b8b0-20ee21c0018a" />


9.	Test the cracked password

 <img width="1920" height="1080" alt="p2 cracked" src="https://github.com/user-attachments/assets/1c449e7e-43ed-44e3-9758-d50dbf8f2eac" />





THE OTHER TOOL I TESTED THE STEPS ARE AS FOLLOWS 

Password Cracking with Networkwalks Tools
📋 General Steps Taken
1.	Uplaod locked PDF file to Networkwalks Hash Calculator
 <img width="1920" height="1080" alt="n1" src="https://github.com/user-attachments/assets/58c8b57b-14c3-4fa4-9414-aab86e60b685" />

2.	Copy the PDF hash value into Networkwalks Password Cracker
   
<img width="1920" height="1080" alt="n3" src="https://github.com/user-attachments/assets/58acaa20-9da6-465e-9380-500619bab6b4" />

3.	Open the locked PDF file and enter the cracked password
	 <img width="1920" height="1080" alt="Screenshot 2026-08-27 220913" src="https://github.com/user-attachments/assets/8e4a7184-30e2-4521-8758-040d166bc186" />


Access Granted


<img width="1920" height="1080" alt="n2" src="https://github.com/user-attachments/assets/db5501b1-0602-4eef-8118-896e46048d1e" />



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

