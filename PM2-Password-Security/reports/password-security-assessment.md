# PM2 – Password Security Assessment

## 1. Objective
To understand password hashing, password complexity, dictionary attacks, and secure password storage practices.

## 2. Tools Used
- Kali Linux
- SHA-256 utility (sha256sum)
- John the Ripper
- PDF encryption utility

## 3. Practical Activities

### Activity 1: SHA-256 Hash Generation
Generated SHA-256 hashes for three different test strings using the Linux sha256sum utility.

Commands used:

```bash
printf '%s' 'password123' | sha256sum
printf '%s' 'Password123!' | sha256sum
printf '%s' 'CyberSecurity2026!' | sha256sum
```

### Activity 2: Observations
- Each test string produced a SHA-256 hash.
- Different input strings produced different hash values.
- SHA-256 produces a fixed-length 256-bit digest.
- Hashing is a one-way operation; it is not encryption.

### Activity 3: Dictionary Attack Concepts
Studied how dictionary-based password guessing works using candidate password lists and John the Ripper in the controlled PM1 PDF lab.

### Activity 4: Password Security
Compared password examples and reviewed the importance of length, uniqueness, and avoiding predictable passwords.

## 4. Security Findings
- Short and predictable passwords are more vulnerable to guessing.
- Password reuse increases security risk.
- SHA-256 alone is not recommended for password storage.
- Password storage should use dedicated password-hashing algorithms such as Argon2id, bcrypt, or scrypt.

## 5. Recommendations
1. Use long, unique passwords.
2. Avoid common words and predictable patterns.
3. Enable multi-factor authentication.
4. Never reuse passwords across services.
5. Use a password manager.
6. Store passwords using a dedicated password-hashing algorithm with appropriate parameters and salts.

## 6. Conclusion
This practical demonstrated SHA-256 hash generation and basic password-security concepts in Kali Linux. It also highlighted why secure password selection and appropriate password-storage algorithms are important.
