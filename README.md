# NETWORKWALKS – WEEK 3
## Cybersecurity: Password Cracking and Password Security Assessment

**Student Name:** Manpreet Singh  
**Batch:** B084  
**Operating System:** Kali Linux  
**Project Category:** Cybersecurity / Ethical Hacking  
**Modules:** PM1 – John the Ripper | PM2 – Password Security Assessment  
**Project Status:** Completed

---

## 1. Project Overview

The NETWORKWALKS – Week 3 project focuses on understanding password security, password verification mechanisms, password hash extraction, and password-cracking techniques using Kali Linux security tools.

The project provides practical exposure to password security assessment through two modules: John the Ripper (PM1) and Password Security Assessment (PM2).

The activities were designed to demonstrate how password hashes are generated, how password-protected PDF files can be assessed, how dictionary-based attacks work, and why strong password policies and secure password-storage mechanisms are essential.

All practical exercises were conducted within an authorized cybersecurity laboratory environment.

## 2. Project Objectives

The primary objectives of this project were:

- Understand the fundamentals of password security and authentication.
- Learn how password hashing and verification work.
- Understand PDF encryption and password-protection mechanisms.
- Extract password-verification data from protected PDF documents.
- Perform dictionary-based password auditing using John the Ripper.
- Demonstrate SHA-256 hashing using Python.
- Compare password examples and understand password strength.
- Identify security risks associated with weak and predictable passwords.
- Understand secure password-storage and password-management practices.

## 3. Project Modules

### 3.1 PM1 – Password Cracking with John the Ripper

**Objective:** To understand password recovery and dictionary-based password auditing using John the Ripper.

**Activities Performed:**

1. Installed and configured John the Ripper in the Windows environment for the provided PDF recovery exercise.
2. Understood the fundamentals of PDF password protection.
3. Used an online PDF hash extractor supporting the pdf2john format to extract password-verification data.
4. Saved the extracted hash into a text file.
5. Loaded the hash file into Johnny, the graphical interface for John the Ripper.
6. Initiated a dictionary-based password attack.
7. Successfully recovered the PDF password.
8. Verified the recovered password by opening the protected PDF.
9. Captured the assigned challenge flag.

**Tools Used:**
- John the Ripper (Jumbo)
- Johnny
- PDF Hash Extractor
- Notepad
- Microsoft Edge

**Practical Result:**

- Password recovered: `good-luck`
- Challenge flag: `nw{cybersecurity_flag_captured_2608}`
- Password verification: Successful

**Outcome:** Successfully completed the authorized PDF password-recovery exercise.

### 3.2 PM2 – Password Security Assessment

**Objective:** To understand password hashing, password strength, dictionary attacks, and secure password-storage practices.

**Activities Performed:**

1. Studied the fundamentals of password hashing.
2. Explored SHA-256 as a cryptographic hashing algorithm.
3. Demonstrated password hashing using Python.
4. Compared different password examples and their security characteristics.
5. Studied how dictionary-based attacks can identify weak and predictable passwords.
6. Explored the importance of strong and unique passwords.
7. Studied secure password-storage practices and the limitations of using fast general-purpose hashing algorithms for password storage.

**Tools and Technologies:**
- Kali Linux
- Python
- SHA-256
- Terminal
- Password-security assessment techniques

**Outcome:** Developed an understanding of password hashing, password strength, dictionary attacks, and secure password-management practices.

## 4. Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Kali Linux | Cybersecurity laboratory environment |
| John the Ripper | Password auditing and recovery |
| Johnny | Graphical interface for John the Ripper |
| pdf2john | PDF password-verification data extraction |
| qpdf | PDF encryption inspection and management |
| Python | Password-security demonstrations |
| SHA-256 | Cryptographic hashing demonstration |

*Note: Tools are listed according to their project scope; their inclusion does not imply that every tool was used in every module.*

## 5. Repository Structure

The project is organized into separate directories to maintain clear documentation, screenshots, and practical evidence.

```text
NETWORKWALKS-WEEK3/
│
├── README.md
│
├── PM1-John-The-Ripper/
│   ├── reports/
│   │   └── PM1-John-The-Ripper-Report.md
│   │
│   └── screenshots/
│       ├── 1.jpeg
│       ├── 2.jpeg
│       ├── 3.jpeg
│       ├── 4.jpeg
│       ├── 5.jpeg
│       └── 6.jpeg
│
├── PM2-Password-Security/
│   ├── reports/
│   │   └── password-security-assessment.md
│   │
│   └── screenshots/
│
└── documentation/
    └── (Additional project documentation)
```

## 6. Key Learning Outcomes

Through this project, I developed practical and theoretical knowledge in the following areas:

- Understanding password authentication and verification.
- Understanding password hashes and cryptographic hashing.
- Learning PDF password-verification data extraction.
- Performing dictionary-based password auditing.
- Working with John the Ripper.
- Understanding SHA-256 hashing through Python.
- Comparing password strength and identifying weak passwords.
- Understanding the risks associated with predictable passwords.
- Learning the importance of secure password-storage mechanisms.
- Developing practical experience with cybersecurity tools in Kali Linux.

## 7. Security Best Practices

The project highlighted several important password-security recommendations:

1. Use long, complex, and unique passwords for different accounts.
2. Avoid common words, predictable patterns, and easily guessable passwords.
3. Use a password manager to generate and store strong passwords.
4. Implement multi-factor authentication wherever possible.
5. Never store passwords in plaintext.
6. Use dedicated password-hashing algorithms such as Argon2id, scrypt, or bcrypt with appropriate configurations.
7. Use unique salts for password hashing.
8. Regularly review password policies and authentication security.

## 8. Ethical Considerations

All practical activities were conducted for educational purposes within an authorized cybersecurity laboratory environment.

- Only authorized laboratory files and test data were used.
- No unauthorized third-party accounts or password-protected documents were targeted.
- Password-recovery activities were performed within the scope of the assigned exercise.
- Security tools were used responsibly for learning and assessment purposes.

## 9. Overall Project Conclusion

The NETWORKWALKS – Week 3 project provided practical exposure to password cracking, password verification, cryptographic hashing, and password security assessment.

Through PM1, I gained hands-on experience with John the Ripper, PDF hash extraction, and dictionary-based password recovery.

Through PM2, I explored password hashing, SHA-256, password strength, dictionary-attack concepts, and secure password-storage practices.

Overall, this project strengthened my understanding of password-security mechanisms and the importance of implementing effective authentication and password-management practices.

**Final Project Status: Successfully Completed.**

---

**Prepared By:** Manpreet Singh  
**Batch:** B084  
**Project:** NETWORKWALKS – WEEK 3  
**Domain:** Cybersecurity / Ethical Hacking  
**Platform:** Kali Linux
