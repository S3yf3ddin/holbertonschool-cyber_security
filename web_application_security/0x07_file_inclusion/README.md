# 0x07 File Inclusion Vulnerabilities

**File Inclusion** is a critical web application vulnerability that arises when user-controlled input is passed to a file-loading function without proper validation. It comes in two main forms: **Local File Inclusion (LFI)**, where the attacker reads files already present on the server, and **Remote File Inclusion (RFI)**, where the attacker causes the server to load and execute a file from an external URL. Both can escalate to **Remote Code Execution (RCE)** and are a frequent target in penetration tests and CTF challenges.

---

## 📚 Resources

**Read or watch:**

* [File Inclusion Vulnerabilities – PortSwigger](https://portswigger.net/web-security/file-path-traversal)
* [Local File Inclusion (LFI) – OWASP](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/11.1-Testing_for_Local_File_Inclusion)
* [Remote File Inclusion (RFI) – OWASP](https://owasp.org/www-community/vulnerabilities/Remote_File_Inclusion)
* [Path Traversal Explained](https://portswigger.net/web-security/file-path-traversal)
* [LFI to RCE via Log Poisoning](https://book.hacktricks.xyz/pentesting-web/file-inclusion/lfi2rce-via-log-poisoning)
* [PHP Wrappers for LFI](https://book.hacktricks.xyz/pentesting-web/file-inclusion#lfi-rfi-using-php-wrappers)

**References:**

* [PayloadsAllTheThings – File Inclusion](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/File%20Inclusion)
* [HackTricks – File Inclusion](https://book.hacktricks.xyz/pentesting-web/file-inclusion)
* [OWASP Testing Guide – Remote File Inclusion](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/11.2-Testing_for_Remote_File_Inclusion)
* [PHP `allow_url_include` Directive](https://www.php.net/manual/en/filesystem.configuration.php#ini.allow-url-include)
* [Burp Suite for LFI Testing](https://portswigger.net/burp)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **Local File Inclusion (LFI)** and how does it occur?
* What is **Remote File Inclusion (RFI)** and what PHP configuration enables it?
* What is **path traversal** (`../`) and how is it used to escape the web root?
* What sensitive Linux files are commonly targeted via LFI (e.g., `/etc/passwd`, `/etc/shadow`, access logs)?
* What are **PHP wrappers** (`php://filter`, `php://input`, `data://`) and how can they be leveraged in LFI attacks?
* How can LFI escalate to **Remote Code Execution** via log poisoning?
* What is **null byte injection** (`%00`) and how was it historically used to bypass extension filters?
* How does **RFI** differ from **Server-Side Request Forgery (SSRF)**?
* What defences prevent file inclusion vulnerabilities (input whitelisting, `open_basedir`, disabling `allow_url_include`)?

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

## 🛠️ Key Concepts Overview

| Attack Type | Description | Precondition |
|-------------|-------------|--------------|
| **LFI** | Read or execute local files on the server | User input passed to `include()` / `require()` without validation |
| **RFI** | Load and execute a file from a remote URL | `allow_url_include = On` in PHP config |
| **Path Traversal** | Navigate outside the intended directory using `../` sequences | Insufficient input sanitisation |
| **Log Poisoning** | Inject PHP code into a log file, then include it via LFI | LFI access to a log file (e.g., Apache access log) |
| **PHP Wrapper (filter)** | Leak base64-encoded source code via `php://filter` | LFI vulnerability present |
| **PHP Wrapper (input)** | Execute arbitrary PHP via POST body with `php://input` | `allow_url_include = On` |
| **Null Byte** | Bypass `.php` extension appending with `%00` (PHP < 5.3.4) | Vulnerable PHP version |

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-flag.txt` | Flag captured via basic Local File Inclusion |
| `1-flag.txt` | Flag obtained using path traversal sequences |
| `2-flag.txt` | Flag retrieved through PHP wrapper exploitation |
| `3-flag.txt` | Flag from log poisoning → RCE via LFI |
| `4-flag.txt` | Flag captured via Remote File Inclusion |
| `5-flag.txt` | Flag from an advanced or chained file inclusion technique |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `web_application_security/0x07_file_inclusion`
