# 0x04 Content Discovery

**Content discovery** is the process of finding hidden or unlinked files, directories, and endpoints on a web application that are not meant to be publicly accessible. Attackers (and penetration testers) use automated tools to brute-force web paths and uncover admin panels, backup files, configuration files, API endpoints, and more. This project covers the tools, wordlists, and methodology used in professional content discovery assessments.

---

## 📚 Resources

**Read or watch:**

* [Content Discovery – TryHackMe](https://tryhackme.com/room/contentdiscovery)
* [Gobuster – Directory/File Enumeration](https://github.com/OJ/gobuster)
* [Feroxbuster – Fast Content Discovery](https://github.com/epi052/feroxbuster)
* [ffuf – Fuzz Faster U Fool](https://github.com/ffuf/ffuf)
* [Dirb – URL Brute Forcer](https://tools.kali.org/web-applications/dirb)
* [SecLists – Wordlist Collection](https://github.com/danielmiessler/SecLists)

**References:**

* [OWASP Testing Guide – Enumerate Web Server Information](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/02-Configuration_and_Deployment_Management_Testing/)
* [Common Sensitive Files to Discover](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/02-Configuration_and_Deployment_Management_Testing/04-Review_Old_Backup_and_Unreferenced_Files_for_Sensitive_Information)
* [robots.txt and sitemap.xml](https://developers.google.com/search/docs/crawling-indexing/robots/intro)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **content discovery** and why is it part of the reconnaissance phase?
* What is the difference between **manual** and **automated** content discovery?
* How does **directory brute-forcing** work and which tools are used?
* What is a **wordlist** and which ones are most effective for content discovery?
* What types of sensitive files are commonly discovered (`.bak`, `admin/`, `config.php`)?
* How can `robots.txt` and `sitemap.xml` **reveal hidden paths**?
* What HTTP response codes help identify **existing vs. non-existing** paths?
* How do tools like **gobuster** and **ffuf** differ in their approach?

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
| `list` | Custom wordlist used for content discovery |
| `unidencom.txt` | Unidentified or unusual content discovered |
| `2-vendor.txt` | Vendor or framework identified from discovered content |
| `3-senior.txt` | Sensitive resource discovered (e.g., senior-level path) |
| `0-flag.txt` – `8-flag.txt` | CTF flags captured during content discovery tasks |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `web_application_security/0x04_content_discovery`
