# Network-Walks---Internship-Week-3-Project-
Password Cracking &amp; Hash Extraction Lab Documentation

Welcome to my documentation for Week 3 Project of the Network Walks Cybersecurity Internship. In this module, I performed password cracking and hash extraction on protected PDF documents using both John the Ripper (Johnny GUI) and Network Walks Online Tools.

🛠️ Lab Overview & Objectives

Configure John the Ripper Jumbo with Johnny GUI.

Extract crackable hashes from password-protected PDF files.

Perform dictionary attacks to recover weak passwords.

Unlock secure PDFs and successfully capture flags.

📂 Step-by-Step Implementation & Screenshots

Part 1: John the Ripper & Johnny GUI Setup

First, I downloaded and configured the Johnny GUI interface, linking it with the John the Ripper Jumbo executable (john.exe) to support advanced hash types.

Johnny GUI & JTR Path Configuration:

<img width="882" height="680" alt="ss1 m1" src="https://github.com/user-attachments/assets/f93fffe4-43b4-4d73-82d4-daeab7eaf03d" />

Part 2: Hash Extraction & Dictionary Attack

Next, I extracted the secure hash from the locked PDF file and loaded it into the cracking utility to execute a dictionary attack.

Hash Generation & Extraction:

<img width="1365" height="723" alt="ss2m1" src="https://github.com/user-attachments/assets/29687f59-57d8-41c8-af5e-aa799b5d3523" />

Dictionary Attack Execution:

<img width="882" height="680" alt="ss1 m1" src="https://github.com/user-attachments/assets/eb45f690-3e4c-455c-89cf-18761a0b2316" />

Saving the Hash File (hash1.txt):

<img width="1365" height="718" alt="ss3 m1" src="https://github.com/user-attachments/assets/14443b9a-10b7-440a-881c-56b4248c0b5e" />

Loading Hash into Johnny GUI:

<img width="1345" height="699" alt="ss4 m1" src="https://github.com/user-attachments/assets/7daf9fca-ebeb-452b-88c9-2bfe37b94c16" />

Attack In-Progress:

<img width="1365" height="767" alt="ss5 m1" src="https://github.com/user-attachments/assets/b8bd3bfa-018f-4915-979d-6a4bea92ecd0" />

Part 3: Success & Flag Capture

The dictionary attack successfully matched the password (good-luck), allowing me to unlock the PDF and capture the flag.

Password Successfully Cracked: <img width="1365" height="722" alt="ss6 m1" src="https://github.com/user-attachments/assets/0e0c0de8-3fcc-4acd-8b1e-801c1b4789ea" />




Final Flag Captured (nw{...}):
<img width="1362" height="767" alt="ss7 m1" src="https://github.com/user-attachments/assets/64be6d2c-61ea-475a-9982-1fd1b79d1bd1" />

### Module 2 Screenshots Reference:
Network Walks Hash Calculator displaying the successfully parsed and extracted PDF hash.

<img width="1365" height="673" alt="ss1 m2" src="https://github.com/user-attachments/assets/8f70f4b2-ff01-4a52-ba76-957c74f4f84a" />

Network Walks Password Cracker interface running the dictionary attack and displaying a successful match (`[+] MATCH password1`).

<img width="1365" height="679" alt="ss2m2" src="https://github.com/user-attachments/assets/b9f2e8c2-57cb-435c-a683-ec81f8dd65fb" />

---


📝 Conclusion

This lab provided hands-on experience in understanding how weak passwords can be easily compromised through dictionary attacks using tools like John the Ripper. It highlights the critical importance of implementing strong, complex passwords for document security.

Status: Completed Successfully ✅

Author: Sadia MAzhar | Cybersecurity Intern | Network Walks
