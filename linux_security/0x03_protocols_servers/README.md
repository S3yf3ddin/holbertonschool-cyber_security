# 0x03 Protocols & Server Hardening

This project focuses on **securing network protocols and server services** on a Linux system. Students will use `iptables` to enforce firewall policies, audit running services, harden server configurations, secure protocols such as NFS, SNMP, and SMTP, and implement defences against Denial-of-Service attacks. Server hardening is a critical step in reducing the attack surface of any production environment.

---

## 📚 Resources

**Read or watch:**

* [iptables Tutorial – Frozentux](https://www.frozentux.net/iptables-tutorial/iptables-tutorial.html)
* [Securing NFS](https://www.redhat.com/sysadmin/nfs-security)
* [SNMP Security Best Practices](https://www.cisco.com/c/en/us/support/docs/ip/simple-network-management-protocol-snmp/13736-snmpv3.html)
* [Postfix / Sendmail Hardening](https://www.postfix.org/SMTPD_ACCESS_README.html)
* [Linux DoS Protection with iptables](https://javapipe.com/blog/iptables-ddos-protection/)
* [SSL/TLS Cipher Suites](https://www.ssl.com/guide/ssl-best-practices/)

**References:**

* [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks/)
* [NIST SP 800-123 – Guide to General Server Security](https://csrc.nist.gov/publications/detail/sp/800-123/final)
* [iptables man page](https://man7.org/linux/man-pages/man8/iptables.8.html)
* [OpenSSL Cipher List Format](https://www.openssl.org/docs/man3.0/man1/openssl-ciphers.html)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* How to create and manage **iptables rules** for traffic control?
* How to **audit running services** and determine which are necessary?
* What steps are involved in **server hardening** (SSH, web, mail)?
* How to identify and document **exposed network services**?
* What are the security risks of **NFS** and how to mitigate them?
* How to secure **SNMP** (community strings, SNMPv3)?
* What hardening steps should be applied to an **SMTP server**?
* How to use iptables to limit **DoS/DDoS attack impact**?
* How to restrict **cipher suites** to approved, strong algorithms?

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
| `0-iptables.sh` | Configure a baseline iptables ruleset |
| `1-audit.sh` | Audit running protocols and services |
| `2-harden.sh` | Apply server hardening configurations |
| `3-identify.sh` | Identify active services and open ports |
| `4-nfs.sh` | Secure NFS exports and mounts |
| `5-snmp.sh` | Harden SNMP configuration |
| `6-smtp.sh` | Apply SMTP security settings |
| `7-dos.sh` | Add iptables rules to mitigate DoS attacks |
| `8-cipher.sh` | Restrict SSL/TLS to strong cipher suites |
| `9-firewall.sh` | Build a comprehensive firewall ruleset |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `linux_security/0x03_protocols_servers`
