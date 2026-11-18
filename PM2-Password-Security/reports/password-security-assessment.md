# NETWORKWALKS – WEEK 3
## Module 2: Password Cracking Using Networkwalks Online Tools

**Student:** Manpreet Singh  
**Batch:** B084  
**Platform:** Microsoft Edge / Web Browser  
**Lab Environment:** Networkwalks Cybersecurity Lab

---

## 1. Project Overview

This practical demonstrates password recovery of a password-protected PDF file named **My Locked PDF1.pdf** using two free, browser-based tools provided by Networkwalks: the **Hash Calculator** and the **Password Cracker**.

Unlike Module 1, which involved installing and configuring John the Ripper and Johnny on Kali Linux, this module was completed entirely through a web browser without requiring any local software installation.

The exercise focused on PDF hash extraction, dictionary-based password cracking, password verification, and understanding the fundamentals of password security.

## 2. Objectives

The primary objectives of this practical were:

- To understand how password-protected PDF files store password-verification information.
- To extract a compatible password hash from an encrypted PDF.
- To perform a dictionary attack using an online password-cracking tool.
- To identify the correct password from a predefined wordlist.
- To verify the recovered password by opening the protected PDF.
- To understand the similarities between browser-based password-cracking tools and John the Ripper.

## 3. Tools and Technologies Used

| Tool | Purpose |
|---|---|
| Networkwalks Hash Calculator | Extracted a PDF password hash compatible with pdf2john/hashcat-style formats. |
| Networkwalks Password Cracker | Performed a dictionary-based password attack using a built-in wordlist. |
| Microsoft Edge | Accessed the online tools and verified the recovered PDF password. |
| My Locked PDF1.pdf | Password-protected test document used for the practical. |

**Online resources:**
- Hash Calculator: https://networkwalks.com/hash-calculator
- Password Cracker: https://networkwalks.com/password-cracker

## 4. Practical Implementation

### Step 1: Downloading the Protected PDF

Downloaded the encrypted PDF file named **My Locked PDF1.pdf** from the Networkwalks laboratory page.

The document was password-protected and required password recovery to access its contents.

### Step 2: Extracting the PDF Hash

Opened the Networkwalks Hash Calculator in Microsoft Edge.

The following procedure was performed:

1. Navigated to the Hash Calculator website.
2. Selected the PDF tab.
3. Uploaded the protected PDF file.
4. Allowed the browser-based tool to process the document.
5. Extracted the PDF password hash in a format compatible with pdf2john/hashcat-style workflows.

The extracted hash began with the `$pdf$` identifier.

### Step 3: Preparing the Password-Cracking Process

Opened the Networkwalks Password Cracker in a separate browser tab.

This tool provides a dictionary-attack laboratory in which candidate passwords from a predefined wordlist are tested against the supplied hash.

Copied the extracted PDF hash from the Hash Calculator and pasted it into the Password Cracker.

### Step 4: Executing the Dictionary Attack

Started the password-cracking process using the built-in wordlist containing 100 password candidates.

The tool tested the candidate passwords sequentially and compared the results against the supplied PDF hash.

During the process, a matching password was identified at position **91 out of 100**.

### Step 5: Recovering the Password

The dictionary attack successfully identified the matching password:

**Recovered Password:** `password1`

This demonstrated how predictable and commonly used passwords can be discovered through dictionary-based password attacks.

### Step 6: Verifying the Recovered Password

Opened the protected PDF using Microsoft Edge and entered the recovered password.

The document opened successfully, confirming that the recovered password was correct.

### Step 7: Capturing the Lab Flag

After successfully accessing the protected document, captured the following laboratory flag:

**Flag 1:** `nw{networkwalks_flag1_jtr_270521_1}`

This confirmed successful completion of the practical exercise.

## 5. Practical Results

| Assessment Item | Result |
|---|---|
| Protected PDF | My Locked PDF1.pdf |
| Hash extraction | Successful |
| Extracted hash format | `$pdf$` |
| Wordlist size | 100 password candidates |
| Matching position | 91 out of 100 |
| Recovered password | `password1` |
| PDF password verification | Successful |
| Lab flag captured | Successful |

## 6. Module 1 vs Module 2 Comparison

Both modules demonstrated password recovery through hash extraction and dictionary-based password guessing. However, they used different tools and execution environments.

| Comparison | Module 1: John the Ripper / Johnny | Module 2: Networkwalks Online Tools |
|---|---|---|
| Execution environment | Kali Linux | Web browser |
| Software installation | John the Ripper and Johnny installed locally | No local installation required |
| Hash extraction | Online HashCrack website | Networkwalks Hash Calculator |
| Cracking engine | John the Ripper running locally | Networkwalks Password Cracker |
| Attack method | Dictionary attack | Dictionary attack |
| Recovered password | `good-luck` | `password1` |
| Password verification | Opened the protected PDF | Opened the protected PDF in Microsoft Edge |

## 7. Security Observations and Findings

The practical provided the following observations:

1. Password-protected PDF documents contain information that can be used to perform offline password-guessing attempts.
2. Hash extraction is an important preliminary step in a password-security assessment.
3. Dictionary attacks test candidate passwords against extracted password-verification data.
4. Common and predictable passwords, such as `password1`, may be discovered when included in a wordlist.
5. Browser-based tools can demonstrate password-cracking concepts without requiring locally installed software.
6. Successful password recovery depends on whether the correct password is included in the candidate wordlist and whether the tool supports the relevant PDF encryption format.

## 8. Security Recommendations

Based on the practical findings, the following security recommendations are suggested:

- Avoid common passwords and predictable combinations.
- Use long, unique, and complex passwords.
- Avoid reusing passwords across different accounts and documents.
- Use a reputable password manager to generate and store strong passwords.
- Apply appropriate encryption when protecting confidential PDF documents.
- Never share extracted password hashes or recovered credentials publicly.
- Perform password-security assessments only on files for which authorization has been granted.

## 9. Learning Outcomes

Through this exercise, I gained practical understanding of:

- PDF password-hash extraction.
- Browser-based cybersecurity tools.
- Dictionary-based password-cracking techniques.
- Password recovery and verification.
- The relationship between extracted hashes and candidate password testing.
- Differences between locally installed password-cracking tools and browser-based alternatives.

## 10. Conclusion

This practical successfully demonstrated password recovery using Networkwalks' browser-based Hash Calculator and Password Cracker.

The exercise involved extracting a PDF-compatible password hash, performing a dictionary attack using a predefined list of 100 password candidates, recovering the password `password1` at position 91, and verifying access to the protected PDF.

The laboratory exercise also provided a useful comparison between Module 1, which used John the Ripper and Johnny on Kali Linux, and Module 2, which used browser-based Networkwalks tools.

Overall, this practical strengthened my understanding of PDF hash extraction, dictionary attacks, password recovery, and the importance of strong password practices.

---

**Project:** Networkwalks – Week 3  
**Module:** 2 – Password Cracking Using Networkwalks Online Tools  
**Student:** Manpreet Singh  
**Batch:** B084
