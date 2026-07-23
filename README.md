# password-security-assessment
Password security assessment demonstrating dictionary attacks, brute-force attacks, custom wordlists, and password auditing using John the Ripper and Python.
# Password Security Assessment: Dictionary and Brute-Force Attack Analysis

## Overview

This project demonstrates a password security assessment using controlled dictionary and brute-force attack simulations against encrypted ZIP files. The objective was to evaluate how password complexity influences resistance to password-cracking techniques while identifying common authentication weaknesses and recommending effective defensive controls.

The assessment compares weak and strong passwords across multiple categories using **John the Ripper**, standard password wordlists, and a custom Python-generated wordlist. An advanced password recovery scenario demonstrates how customized attack techniques can recover credentials when traditional wordlists are unsuccessful.

---

## Project Objectives

- Evaluate password strength against dictionary attacks.
- Assess resistance to brute-force attacks.
- Compare weak and strong password security.
- Demonstrate password auditing using John the Ripper.
- Develop a custom password wordlist using Python.
- Analyze common password vulnerabilities.
- Recommend authentication security best practices.

---

## Technologies & Tools

- Kali Linux
- John the Ripper
- RockYou Wordlist
- Large Password Wordlist
- Python
- ZIP Encryption
- Password Hash Extraction
- Dictionary Attacks
- Brute-Force Attacks

---

## Lab Environment

The password security assessment was conducted in a controlled laboratory environment using encrypted ZIP files protected with passwords of varying complexity.

### Environment Components

- Kali Linux
- John the Ripper
- RockYou Password Wordlist
- Large Password Wordlist
- Python
- Encrypted ZIP Files

# Assessment Workflow

The assessment followed the stages below:

1. Create encrypted ZIP files.
2. Extract password hashes.
3. Perform dictionary attacks.
4. Execute brute-force attacks.
5. Compare password recovery results.
6. Generate a custom Python wordlist.
7. Recover protected passwords.
8. Analyze password vulnerabilities.
9. Recommend defensive security controls.

---

# Password Categories Tested

Four password categories were evaluated.

### Only Letters

- Weak Password
- Strong Password

### Only Numbers

- Weak Password
- Strong Password

### Letters and Numbers

- Weak Password
- Strong Password

### Letters, Numbers, and Special Characters

- Weak Password
- Strong Password

---

# Dictionary Attack

Dictionary attacks were performed using John the Ripper together with the RockYou wordlist and a large password database.

The assessment demonstrated that commonly used passwords and predictable words can be recovered quickly when they exist within publicly available password lists.

---

# Brute-Force Attack

Brute-force attacks generated password combinations until the correct password was identified.

The results demonstrated that increasing password length and character complexity significantly increases the time required to recover credentials.

---

# Custom Wordlist Development

An advanced password recovery scenario was completed using Python.

The project involved:

- Extracting password hashes from encrypted ZIP files.
- Identifying a Caesar cipher hint.
- Developing a Python script to generate all possible Caesar cipher shifts.
- Creating a custom password wordlist.
- Successfully recovering the encrypted password using the generated wordlist.

This demonstrates how customized password-cracking techniques can be used when conventional wordlists fail.

---

# Results Summary

| Password Category | Dictionary Attack | Brute-Force Attack |
|-------------------|------------------|--------------------|
| Letters (Weak) | Cracked | Cracked |
| Letters (Strong) | Not Found | Time Intensive |
| Numbers (Weak) | Cracked | Cracked |
| Numbers (Strong) | Not Found | Time Intensive |
| Letters + Numbers (Weak) | Not Found | Cracked |
| Letters + Numbers (Strong) | Not Found | Time Intensive |
| Letters + Numbers + Special Characters (Weak) | Not Found | Time Intensive |
| Letters + Numbers + Special Characters (Strong) | Not Found | Time Intensive |

The assessment demonstrates that password length, randomness, and character diversity significantly improve resistance to password-cracking attacks.

---

# Password Vulnerability Analysis

The assessment identified several common password weaknesses, including:

- Short password length
- Common dictionary words
- Predictable character patterns
- Limited character diversity
- Weak password composition

These weaknesses substantially increase the likelihood of successful password compromise.

---

# Security Recommendations

### Authentication

- Use passwords containing at least 12 characters.
- Include uppercase letters, lowercase letters, numbers, and special characters.
- Avoid predictable words and common password patterns.

### Password Storage

- Store passwords using secure hashing algorithms.
- Use bcrypt, Argon2, or PBKDF2.
- Never store passwords in plaintext.

### Account Protection

- Enable Multi-Factor Authentication (MFA).
- Configure account lockout policies.
- Monitor failed authentication attempts.

---

## Skills Demonstrated

- Password Security
- Password Auditing
- Cryptography Fundamentals
- John the Ripper
- Dictionary Attacks
- Brute-Force Attacks
- Password Hash Analysis
- Python Scripting
- Custom Wordlist Development
- Authentication Security
- Cybersecurity Analysis

---

## Practical Applications

The techniques demonstrated in this project are widely used during:

- Password Security Audits
- Penetration Testing
- Security Assessments
- Digital Forensics
- Incident Response
- Authentication Testing

Understanding password-cracking methodologies enables organizations to strengthen password policies, implement secure authentication mechanisms, and reduce the risk of credential-based attacks.

---

## Documentation

The complete project documentation includes:

- Lab environment
- Password testing methodology
- Dictionary attack simulation
- Brute-force attack simulation
- Custom Python wordlist development
- Password vulnerability analysis
- Security recommendations
- Results comparison

The complete report is available in the **documentation** folder.

---

## Future Improvements

- Compare John the Ripper with Hashcat.
- Evaluate GPU-accelerated password cracking.
- Test additional password hashing algorithms.
- Benchmark password recovery performance.
- Automate password auditing and reporting.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Password security assessment
- Password auditing
- Dictionary attacks
- Brute-force attacks
- Password hash analysis
- Python scripting
- Custom wordlist generation
- Authentication security
- Cybersecurity reporting

---

## Author

**Sakshi Teli**

