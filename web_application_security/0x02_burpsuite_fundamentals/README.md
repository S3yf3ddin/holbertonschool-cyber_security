# 0x02 Burp Suite Fundamentals

**Burp Suite** is the industry-standard platform for web application security testing. This project introduces students to Burp Suite's core features: intercepting and modifying HTTP/S requests with the **Proxy**, discovering content and endpoints with the **Scanner/Spider**, replaying and manipulating requests in the **Repeater**, and understanding how the tool integrates into a complete web penetration test workflow.

---

## 📚 Resources

**Read or watch:**

* [Burp Suite Official Documentation](https://portswigger.net/burp/documentation)
* [Getting Started with Burp Suite Community](https://portswigger.net/burp/documentation/desktop/getting-started)
* [Burp Suite Proxy – Intercepting Requests](https://portswigger.net/burp/documentation/desktop/tools/proxy)
* [Burp Repeater – Manual Request Testing](https://portswigger.net/burp/documentation/desktop/tools/repeater)
* [Web Application Penetration Testing Methodology](https://owasp.org/www-project-web-security-testing-guide/)
* [PortSwigger Web Security Academy – Free Labs](https://portswigger.net/web-security)

**References:**

* [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
* [HTTP Request Methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods)
* [Burp Suite Cheat Sheet](https://portswigger.net/burp/documentation/desktop/keyboard-shortcuts)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **Burp Suite** and what problem does it solve in web application testing?
* How to configure a browser to **route traffic through Burp Proxy**?
* How to **intercept, inspect, and modify** an HTTP request in Burp Suite?
* What is the **Burp Repeater** and how is it used to test a single request repeatedly?
* What is **Burp Intruder** and what attack types does it support?
* How to use Burp to **map a web application's attack surface**?
* What is the difference between **active** and **passive** scanning in Burp?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Tool:** Burp Suite Community Edition (pre-installed on Kali Linux).
* **Allowed editors:** `vi`, `vim`, `emacs`.
* All answer files must contain only the answer on a single line.
* All your files must end with a new line.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-flag.txt` | Flag captured using Burp Proxy interception |
| `1-flag.txt` | Flag obtained by modifying an HTTP request |
| `2-flag.txt` | Flag discovered through Burp Repeater |
| `3-flag.txt` | Flag from an Intruder-based attack |
| `4-flag.txt` | Flag from application enumeration |
| `5-flag.txt` | Flag from advanced Burp technique |
| `6-flag.txt` | Final challenge flag |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `web_application_security/0x02_burpsuite_fundamentals`
