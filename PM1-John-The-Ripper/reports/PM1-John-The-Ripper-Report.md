# PM1 – PDF Password Auditing Using John the Ripper

## Objective
To understand PDF password auditing using John the Ripper in an authorized local lab environment.

## Tools Used
- Kali Linux
- John the Ripper
- pdf2john.py
- qpdf
- Custom wordlist

## Practical Steps
1. Created an original test PDF.
2. Encrypted the PDF using AES-256 encryption.
3. Extracted the PDF password hash using pdf2john.py.
4. Used John the Ripper with a custom wordlist.
5. Successfully recovered the test PDF password.
6. Used John the Ripper's show option to verify the result.

## Result
John the Ripper successfully loaded one PDF password hash and recovered the password from the custom lab wordlist.

- Hashes loaded: 1
- Hashes cracked: 1
- Hashes remaining: 0
- PDF encryption revision: 6
- Key length: 256 bits

## Security Observation
A password included in a wordlist can be recovered through dictionary-based password auditing. Strong, unique passwords reduce this risk. Organizations should use approved password policies and secure storage practices.

## Conclusion
The practical demonstrated PDF hash extraction and password auditing using John the Ripper in a controlled lab environment.
