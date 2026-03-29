# 0x06 IDOR – Insecure Direct Object References

**Insecure Direct Object References (IDOR)** is a type of **Broken Access Control** vulnerability — ranked #1 in the OWASP Top 10 2021. It occurs when an application exposes a reference to an internal object (such as a database record, file, or user account) without validating whether the requesting user is authorised to access it. By simply changing an ID in a URL or request parameter, an attacker can access other users' data.

---

## 📚 Resources

**Read or watch:**

* [IDOR – PortSwigger Web Security Academy](https://portswigger.net/web-security/access-control/idor)
* [Broken Access Control – OWASP Top 10 2021 (A01)](https://owasp.org/Top10/A01_2021-Broken_Access_Control/)
* [IDOR Vulnerability Explained – TryHackMe](https://tryhackme.com/room/idor)
* [Horizontal vs Vertical Privilege Escalation](https://portswigger.net/web-security/access-control#horizontal-privilege-escalation)
* [Testing for IDOR – OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/05-Authorization_Testing/04-Testing_for_Insecure_Direct_Object_References)
* [Burp Suite for IDOR Testing](https://portswigger.net/burp/documentation/desktop/tools/repeater)

**References:**

* [OWASP Access Control Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Access_Control_Cheat_Sheet.html)
* [PayloadsAllTheThings – IDOR](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Insecure%20Direct%20Object%20References)
* [Real-World IDOR Bug Bounty Reports – HackerOne](https://hackerone.com/hacktivity?querystring=IDOR)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **IDOR** and how does it relate to Broken Access Control?
* What is the difference between **horizontal** and **vertical** privilege escalation?
* Where in an HTTP request can object references appear (URL path, query parameters, POST body, cookies)?
* How do you **identify** an IDOR vulnerability during a penetration test?
* What is **parameter tampering** and how does it enable IDOR exploitation?
* What server-side controls prevent IDOR (authorisation checks, indirect references)?
* How to use **Burp Suite** to systematically test for IDOR?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Allowed editors:** `vi`, `vim`, `emacs`.
* All answer files must contain only the answer on a single line.
* All your files must end with a new line.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-flag.txt` | Flag obtained by exploiting an IDOR vulnerability |
| `1-flag.txt` | Flag from horizontal privilege escalation via IDOR |
| `2-flag.txt` | Flag from a more complex IDOR scenario |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `web_application_security/0x06_idor`
