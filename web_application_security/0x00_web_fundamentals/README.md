# 0x00 Web Fundamentals & Common Vulnerabilities

This project covers the **foundational concepts of web application security**. Students will explore common vulnerabilities including **Host Header Injection**, **Cross-Site Scripting (XSS)**, and **Remote Code Execution (RCE)** — three attacks that exploit weaknesses in how web applications handle user-supplied input. Understanding these fundamentals is a prerequisite for deeper topics such as the OWASP Top 10 and advanced web penetration testing.

---

## 📚 Resources

**Read or watch:**

* [How HTTP Works](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
* [HTTP Headers Reference](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
* [Host Header Injection Explained](https://portswigger.net/web-security/host-header)
* [Cross-Site Scripting (XSS) – PortSwigger](https://portswigger.net/web-security/cross-site-scripting)
* [Remote Code Execution (RCE) Overview](https://owasp.org/www-community/attacks/Code_Injection)
* [Burp Suite – Intercepting HTTP Requests](https://portswigger.net/burp/documentation/desktop/getting-started)

**References:**

* [OWASP XSS Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html)
* [OWASP Testing Guide – Input Validation](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/)
* [PayloadsAllTheThings – XSS Payloads](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/XSS%20Injection)
* [PayloadsAllTheThings – RCE Payloads](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Command%20Injection)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is the **HTTP request/response cycle** and how do web applications process it?
* What is a **Host Header Injection** vulnerability and how can it be exploited?
* What is **Cross-Site Scripting (XSS)** and what are its three types (Reflected, Stored, DOM)?
* How does an **XSS payload** steal cookies or redirect users?
* What is **Remote Code Execution** and how does it differ from other injection attacks?
* Why is **input validation and output encoding** critical for web security?
* What HTTP tools can an attacker use to **manipulate requests** manually?

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
| `1-host_header_injection.sh` | Exploit a Host Header Injection vulnerability |
| `2-flag.txt` | Flag obtained from Host Header Injection |
| `3-xss_payload.txt` | XSS payload used to capture the flag |
| `4-flag.txt` | Flag captured via XSS exploitation |
| `5-ticket.txt` | Support ticket used in the XSS attack vector |
| `6-flag.txt` | Additional flag from the exercise |
| `7-rce_payload.txt` | Remote Code Execution payload |
| `8-flag.txt` | Flag obtained via RCE |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `web_application_security/0x00_web_fundamentals`
