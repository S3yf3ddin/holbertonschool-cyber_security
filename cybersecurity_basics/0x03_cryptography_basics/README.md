# 0x03 Cryptography Basics

This project explores the fundamentals of **cryptography** — the science of securing information. Students will work hands-on with cryptographic hash functions (MD5, SHA-1, SHA-256), password hashing, and popular password-cracking tools such as **John the Ripper** and **Hashcat**. Understanding how these tools work is essential for both offensive security assessments and building robust password policies.

---

## 📚 Resources

**Read or watch:**

* [What is Cryptography?](https://www.cloudflare.com/learning/ssl/what-is-cryptography/)
* [Hash Functions Explained](https://en.wikipedia.org/wiki/Cryptographic_hash_function)
* [MD5, SHA-1, SHA-256 – Differences](https://www.ssl2buy.com/wiki/sha-256-vs-sha-1-vs-md5)
* [John the Ripper – Official Site](https://www.openwall.com/john/)
* [Hashcat – Advanced Password Recovery](https://hashcat.net/hashcat/)
* [Password Cracking Techniques](https://www.varonis.com/blog/password-cracking-techniques)

**References:**

* [RockYou Wordlist](https://github.com/brannondorsey/naive-hashcat/releases/download/data/rockyou.txt)
* [Hashcat Wiki](https://hashcat.net/wiki/)
* [OpenSSL `dgst` manual](https://www.openssl.org/docs/man3.0/man1/openssl-dgst.html)
* [NIST Password Guidelines (SP 800-63B)](https://pages.nist.gov/800-63-3/sp800-63b.html)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is a **cryptographic hash function** and what properties make it secure?
* What are the differences between **MD5**, **SHA-1**, and **SHA-256**?
* Why are MD5 and SHA-1 considered **broken** for security purposes?
* How does **password hashing** differ from encryption?
* How does **John the Ripper** crack password hashes?
* What attack modes does **Hashcat** support (dictionary, brute-force, combination, rule-based)?
* What is a **wordlist** and why is `rockyou.txt` commonly used?
* How can you **generate and verify** file hashes from the command line?

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
| `0-sha1.sh` | Compute SHA-1 hash of a file |
| `1-sha256.sh` | Compute SHA-256 hash of a file |
| `2-md5.sh` | Compute MD5 hash of a file |
| `3-password_hash.sh` | Generate a hashed password |
| `4-wordlist_john.sh` | Crack password hash using John the Ripper with a wordlist |
| `5-windows_john.sh` | Crack a Windows-format hash using John the Ripper |
| `6-crack_john.sh` | General-purpose John the Ripper password cracking |
| `7-crack_hashcat.sh` | Crack a hash using Hashcat |
| `8-combination_hashcat.sh` | Hashcat combination attack |
| `9-attack_hashcat.sh` | Hashcat rule-based / advanced attack |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `cybersecurity_basics/0x03_cryptography_basics`
