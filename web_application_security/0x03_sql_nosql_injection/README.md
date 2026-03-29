# 0x03 SQL & NoSQL Injection

**Injection** is consistently ranked the number one web application vulnerability by OWASP. This project explores both **SQL injection** (targeting relational databases) and **NoSQL injection** (targeting document and key-value stores). Students will identify vulnerable input parameters, extract data, and understand why these vulnerabilities arise from insufficient input sanitisation — and how to prevent them.

---

## 📚 Resources

**Read or watch:**

* [SQL Injection – OWASP](https://owasp.org/www-community/attacks/SQL_Injection)
* [NoSQL Injection – OWASP](https://owasp.org/www-community/attacks/NoSQL_Injection)
* [sqlmap – Automatic SQL Injection Tool](https://sqlmap.org/)
* [SQL Injection Cheat Sheet – PortSwigger](https://portswigger.net/web-security/sql-injection/cheat-sheet)
* [NoSQL Injection Examples (MongoDB)](https://book.hacktricks.xyz/pentesting-web/nosql-injection)
* [Preventing SQL Injection – Prepared Statements](https://owasp.org/www-community/controls/Query_Parameterization_Cheat_Sheet)

**References:**

* [PayloadsAllTheThings – SQL Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/SQL%20Injection)
* [PayloadsAllTheThings – NoSQL Injection](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/NoSQL%20Injection)
* [PortSwigger SQL Injection Labs](https://portswigger.net/web-security/sql-injection)
* [OWASP Testing Guide – SQL Injection](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/05-Testing_for_SQL_Injection)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **SQL injection** and why does it occur?
* What are the main types of SQL injection: **in-band**, **inferential (blind)**, and **out-of-band**?
* How does **UNION-based SQL injection** allow data extraction?
* What is **Boolean-based blind SQL injection** and how is it exploited?
* What is **NoSQL injection** and how does it differ from SQL injection?
* How does **MongoDB** handle authentication and how can it be bypassed?
* How to use **sqlmap** for automated SQL injection testing?
* What defences (prepared statements, ORMs, input validation) prevent injection attacks?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Allowed editors:** `vi`, `vim`, `emacs`.
* All answer files must contain only the answer or payload on a single line.
* All your files must end with a new line.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-vuln.txt` | Identified vulnerable parameter |
| `1-flag.txt` | Flag captured via SQL injection |
| `2-flag.txt` | Flag from UNION-based extraction |
| `3-flag.txt` | Flag from blind SQL injection technique |
| `4-flag.txt` | Flag from database enumeration |
| `5-vuln.txt` | NoSQL injection payload used |
| `6-flag.txt` | Flag from NoSQL injection exploit |
| `7-flag.txt` | Final challenge flag |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `web_application_security/0x03_sql_nosql_injection`
