# 0x02 Active Reconnaissance

**Active reconnaissance** involves directly interacting with the target system to gather detailed technical information. While it is more intrusive than passive reconnaissance (and may be detected by the target), it yields far richer data: open ports, running web servers, injectable parameters, backend database types, hidden directories, and more. This project simulates a structured active recon workflow using industry-standard tools.

---

## 📚 Resources

**Read or watch:**

* [Active Reconnaissance Techniques](https://www.eccouncil.org/cybersecurity-exchange/ethical-hacking/passive-vs-active-reconnaissance/)
* [Nmap – Getting Started](https://nmap.org/book/man.html)
* [Nikto Web Server Scanner](https://cirt.net/Nikto2)
* [Gobuster – Directory Brute-Forcing](https://github.com/OJ/gobuster)
* [sqlmap – SQL Injection Detection](https://sqlmap.org/)
* [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload)

**References:**

* [OWASP Testing Guide – Information Gathering](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/01-Information_Gathering/)
* [HTTP Response Headers and Web Fingerprinting](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers)
* [Common Web Server Banners](https://en.wikipedia.org/wiki/Server_(computing)#Software)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **active reconnaissance** and what are its legal implications?
* How to identify **open ports** and services on a target?
* How to **fingerprint a web server** from its HTTP response headers?
* What is a **SQL injection** vulnerability and how can it be detected?
* How to determine the **backend database type** of a web application?
* How to discover **hidden directories and files** on a web server?
* What is the significance of **database table enumeration** during an assessment?

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
| `0-ports.txt` | List of discovered open ports |
| `1-webserver.txt` | Identified web server software and version |
| `2-injectable.txt` | Vulnerable injectable parameter discovered |
| `3-database.txt` | Backend database type identified |
| `4-tables.txt` | Database tables enumerated |
| `5-hidden_dir.txt` | Hidden directory discovered on the web server |
| `100-flag.txt` – `102-flag.txt` | CTF flags captured during the exercise |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `network_security/0x02_active_reconnaissance`
