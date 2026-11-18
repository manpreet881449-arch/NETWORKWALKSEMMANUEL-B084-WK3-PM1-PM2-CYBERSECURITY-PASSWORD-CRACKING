# PM1 – Password Cracking with John the Ripper (JTR)
## Cybersecurity Practical Assessment Report

**Project:** NETWORKWALKSEMMANUEL – Week 3  
**Module:** PM1 – Password Cracking with John the Ripper  
**Student:** Manpreet Singh  
**Platform:** Windows  
**Category:** Password Security and Ethical Hacking  
**Status:** Successfully Completed

---

## 1. Introduction

This practical exercise focused on understanding password security and performing password recovery using John the Ripper (JTR), a widely used password-auditing and recovery tool.

The objective was to recover the password of a provided password-protected PDF document named `My Locked PDF1.pdf`. The exercise involved extracting the password hash, preparing it for analysis, and performing a dictionary-based password attack using John the Ripper through its graphical interface, Johnny.

The activity was conducted within the scope of an authorized cybersecurity training exercise.

## 2. Objectives

The primary objectives of this practical exercise were:

- Understand the fundamentals of password cracking.
- Learn how John the Ripper works.
- Configure Johnny as the graphical interface for John the Ripper.
- Extract password hashes from an encrypted PDF document.
- Perform a dictionary-based password attack.
- Recover and verify the original PDF password.
- Capture the assigned challenge flag as proof of successful completion.

## 3. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| John the Ripper (Jumbo) | Password recovery and auditing engine |
| Johnny | Graphical interface for John the Ripper |
| Online HashCrack – PDF Hash Extractor | Extracting the PDF password hash |
| Notepad | Saving the extracted hash in a text file |
| Microsoft Edge | Opening and verifying the protected PDF |
| Windows | Operating environment |

## 4. Practical Implementation and Methodology

### Step 1: Installation and Configuration

Installed John the Ripper (Jumbo) for Windows along with Johnny, its graphical user interface.

Configured Johnny by specifying the location of `john.exe` inside the John the Ripper `run` directory.

This established the connection between the graphical interface and the password-cracking engine.

### Step 2: Obtaining the Protected PDF

Downloaded the provided password-protected PDF document:

`My Locked PDF1.pdf`

The document was used as the target file for the authorized password-recovery exercise.

### Step 3: Extracting the PDF Password Hash

Used Online HashCrack's PDF Hash Extractor to extract the password hash from the protected PDF.

The extracted output was generated in a format compatible with John the Ripper (`pdf2john` format).

This process converted the PDF's password-protection information into a format that could be analyzed by the password-recovery tool.

### Step 4: Preparing the Hash File

Copied the extracted hash into a text file using Notepad.

Saved the hash in the appropriate format so that Johnny could load and process it.

### Step 5: Loading the Hash into Johnny

Opened Johnny and selected the **Open Password File** option.

Imported the prepared hash text file into the application.

Verified that the hash was successfully loaded before initiating the password-recovery process.

### Step 6: Performing the Password-Cracking Attack

Selected **Start New Attack** in Johnny.

Used the default wordlist-based attack mode to test candidate passwords against the extracted hash.

John the Ripper successfully identified the correct password from its password candidates.

**Recovered Password:** `good-luck`

### Step 7: Password Verification

Opened the original password-protected PDF document using Microsoft Edge.

Entered the recovered password:

`good-luck`

The PDF opened successfully, confirming that the recovered password was correct.

### Step 8: Flag Capture

After successfully opening the protected PDF, located and recorded the challenge flag.

**Captured Flag:**

`nw{cybersecurity_flag_captured_2608}`

This confirmed successful completion of the practical exercise.

## 5. Results and Findings

The practical exercise was successfully completed.

| Assessment Parameter | Result |
|---|---|
| Target File | My Locked PDF1.pdf |
| Hash Extraction | Successful |
| Hash Format | PDF / pdf2john |
| Attack Method | Dictionary / Wordlist |
| Password Recovery | Successful |
| Recovered Password | `good-luck` |
| PDF Verification | Successful |
| Flag Capture | Successful |

## 6. Security Observations

The practical exercise demonstrated several important password-security concepts:

1. Password hashes can be extracted from certain password-protected files for authorized security auditing.
2. Dictionary attacks can successfully recover passwords that appear in the attacker's wordlist.
3. Passwords based on common words or predictable patterns may be vulnerable to automated password attacks.
4. Strong, unique passwords significantly improve resistance to dictionary-based attacks.
5. Password-protected documents should use appropriately strong encryption and secure password-management practices.

## 7. Screenshots and Evidence

The following screenshots document the practical implementation and successful results.

| Screenshot | Evidence Description |
|---|---|
| 1.jpeg | Johnny configuration and John the Ripper executable path |
| 2.jpeg | Uploading the protected PDF to the hash extractor |
| 3.jpeg | Extracted PDF password hash |
| 4.jpeg | Hash saved in a text file using Notepad |
| 5.jpeg | Johnny displaying the recovered password |
| 6.jpeg | PDF password prompt and verification evidence |

## 8. Learning Outcomes

Through this practical exercise, I gained hands-on experience in:

- Understanding password-cracking fundamentals.
- Installing and configuring John the Ripper.
- Working with Johnny's graphical interface.
- Extracting password hashes from protected PDF files.
- Preparing hash files for password auditing.
- Performing dictionary-based password attacks.
- Verifying recovered passwords against the original document.
- Understanding the importance of strong password policies.

## 9. Conclusion

The PM1 practical exercise was successfully completed using John the Ripper and Johnny.

The password hash was extracted from the provided protected PDF, imported into Johnny, and analyzed using a dictionary-based attack. The original password, `good
