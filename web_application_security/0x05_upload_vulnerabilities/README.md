# 0x05 Upload Vulnerabilities

**File upload functionality** is one of the most dangerous features a web application can expose. When not properly secured, it allows attackers to upload malicious files — including web shells and server-side scripts — that can lead to **Remote Code Execution (RCE)** and complete server compromise. This project explores the various bypass techniques used to circumvent upload restrictions and how to exploit unrestricted file upload vulnerabilities.

---

## 📚 Resources

**Read or watch:**

* [File Upload Vulnerabilities – PortSwigger](https://portswigger.net/web-security/file-upload)
* [Unrestricted File Upload – OWASP](https://owasp.org/www-community/vulnerabilities/Unrestricted_File_Upload)
* [Web Shell Attacks Explained](https://www.crowdstrike.com/cybersecurity-101/malware/web-shell/)
* [Bypassing File Upload Restrictions](https://book.hacktricks.xyz/pentesting-web/file-upload)
* [PHP Web Shells](https://github.com/tennc/webshell)
* [Content-Type and MIME Type Manipulation](https://portswigger.net/web-security/file-upload#exploiting-flawed-validation-of-file-uploads)

**References:**

* [PayloadsAllTheThings – Upload Insecure Files](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Upload%20Insecure%20Files)
* [OWASP Testing Guide – File Upload](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/10-Business_Logic_Testing/09-Test_Upload_of_Malicious_Files)
* [Magic Bytes Reference](https://en.wikipedia.org/wiki/List_of_file_signatures)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is an **unrestricted file upload** vulnerability?
* What is a **web shell** and how is it deployed?
* What validation checks do web applications typically use for file uploads (extension, MIME type, magic bytes)?
* How can each of these checks be **bypassed** by an attacker?
* What is the difference between **client-side** and **server-side** upload validation?
* How does a successful file upload lead to **Remote Code Execution**?
* What defences prevent file upload vulnerabilities (file type whitelisting, storage separation, execution prevention)?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Allowed editors:** `vi`, `vim`, `emacs`.
* **Shebang:** The first line of all your Bash scripts must be exactly `#!/bin/bash`.
* All your files must end with a new line.
* All your files must be executable.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-target.txt` | Target URL for the upload vulnerability |
| `150.sh` | Exploitation script for the upload vulnerability |
| `task4.png` | Image file used/modified during the exercise |
| `1-flag.txt` – `4-flag.txt` | CTF flags captured during the upload vulnerability tasks |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `web_application_security/0x05_upload_vulnerabilities`
