# 0x00 Introduction to Cybersecurity

This project provides a foundational introduction to the field of **cybersecurity**. It covers core concepts such as the CIA Triad (Confidentiality, Integrity, Availability), threat landscapes, password security, cryptographic hashing, key generation, and identifying privileged system processes. By the end of this module, students should have a solid baseline understanding of what cybersecurity is and why it matters.

---

## 📚 Resources

**Read or watch:**

* [What is Cybersecurity?](https://www.cisco.com/c/en/us/products/security/what-is-cybersecurity.html)
* [CIA Triad – Confidentiality, Integrity, Availability](https://www.fortinet.com/resources/cyberglossary/cia-triad)
* [Introduction to Cybersecurity – NIST](https://www.nist.gov/cybersecurity)
* [Password Security Best Practices](https://www.cisa.gov/tips/st04-002)
* [SHA-256 Hashing Explained](https://en.wikipedia.org/wiki/SHA-2)
* [Public Key Cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)

**References:**

* [OpenSSL Documentation](https://www.openssl.org/docs/)
* [Linux `passwd` and `shadow` files](https://man7.org/linux/man-pages/man5/passwd.5.html)
* [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **cybersecurity** and why is it important?
* What does the **CIA Triad** stand for and what does each component mean?
* How to **generate a strong password** from the command line?
* What is **SHA-256** and how is it used for data integrity validation?
* How to **generate asymmetric key pairs** using standard tools?
* How to **identify processes running as root** on a Linux system?
* What is the difference between **authentication** and **authorization**?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Allowed editors:** `vi`, `vim`, `emacs`.
* **Shebang:** The first line of all your Bash scripts must be exactly `#!/bin/bash`.
* **Script Constraints:** You are **not allowed** to use backticks, `&&`, `||`, or `;`.
* All your files must end with a new line.
* All your files must be executable.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-release.sh` | Display OS release information |
| `1-gen_password.sh` | Generate a strong random password |
| `2-sha256_validator.sh` | Validate a file using SHA-256 checksum |
| `3-gen_key.sh` | Generate a cryptographic key pair |
| `4-root_process.sh` | List all processes running as root |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `cybersecurity_basics/0x00_introduction_cybersecurity`
