# 0x01 Passive Reconnaissance

**Passive reconnaissance** is the first phase of any security assessment. Unlike active reconnaissance, it gathers information about a target **without directly interacting with it**, making it undetectable by the target. Students will use tools such as WHOIS, `dig`, and `subfinder` to collect DNS records, identify mail servers, discover subdomains, and build a comprehensive report about a target domain — all without generating suspicious traffic.

---

## 📚 Resources

**Read or watch:**

* [What is Passive Reconnaissance?](https://www.eccouncil.org/cybersecurity-exchange/ethical-hacking/passive-vs-active-reconnaissance/)
* [WHOIS Lookup Explained](https://www.icann.org/resources/pages/whois-2012-02-25-en)
* [DNS Record Types (A, MX, TXT, NS)](https://www.cloudflare.com/learning/dns/dns-records/)
* [subfinder – Subdomain Discovery Tool](https://github.com/projectdiscovery/subfinder)
* [dig Command Guide](https://linux.die.net/man/1/dig)
* [Google Hacking / Google Dorks](https://www.exploit-db.com/google-hacking-database)

**References:**

* [Shodan – Search Engine for Internet-Connected Devices](https://www.shodan.io/)
* [DNS Dumpster](https://dnsdumpster.com/)
* [VirusTotal Passive DNS](https://www.virustotal.com/)
* [SecurityTrails](https://securitytrails.com/)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is the difference between **passive** and **active** reconnaissance?
* What information can **WHOIS** reveal about a domain?
* How do **A, MX, and TXT DNS records** differ and what do they reveal?
* How to perform a **full DNS enumeration** with `dig`?
* What is **subdomain enumeration** and why is it important in reconnaissance?
* How to use **subfinder** to automate subdomain discovery?
* How to compile a structured **reconnaissance report**?

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
| `0-whois.sh` | Run a WHOIS query against a target domain |
| `1-a_record.sh` | Query the A (IPv4 address) DNS record |
| `2-mx_record.sh` | Query the MX (mail exchange) DNS record |
| `3-txt_record.sh` | Query TXT DNS records (SPF, DMARC, verification tokens) |
| `4-dig_all.sh` | Retrieve all available DNS records for a domain |
| `5-subfinder.sh` | Enumerate subdomains using subfinder |
| `holbertonschool_report.md` | Example passive reconnaissance report |
| `100-flag.txt` – `102-flag.txt` | CTF flags captured during the exercise |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `network_security/0x01_passive_reconnaissance`
