# 0x00 Linux Security Basics

This project covers the **fundamentals of securing a Linux system**. Students will learn how to audit login activity, monitor network connections, manage firewall rules with `iptables`, identify exposed network services, perform system audits, capture and analyse network packets, and run basic scans. These skills form the core toolkit of a Linux system administrator focused on security hardening.

---

## 📚 Resources

**Read or watch:**

* [Linux Security Overview](https://www.linux.com/training-tutorials/linux-security-overview/)
* [iptables Tutorial](https://www.frozentux.net/iptables-tutorial/iptables-tutorial.html)
* [Netstat / ss – Network Connection Monitoring](https://man7.org/linux/man-pages/man8/ss.8.html)
* [tcpdump – Network Packet Analyser](https://www.tcpdump.org/manpages/tcpdump.1.html)
* [auditd – Linux Audit System](https://linux.die.net/man/8/auditd)
* [Nmap – Network Scanning](https://nmap.org/book/man.html)

**References:**

* [CIS Linux Benchmarks](https://www.cisecurity.org/benchmark/distribution_independent_linux)
* [Linux Hardening Guide – DigitalOcean](https://www.digitalocean.com/community/tutorials/an-introduction-to-securing-your-linux-vps)
* [last / lastb Manual](https://man7.org/linux/man-pages/man1/last.1.html)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* How to **audit user login history** on a Linux system?
* How to list **active network connections** and what they reveal?
* How to monitor **incoming connections** in real time?
* How to view and manage **iptables firewall rules**?
* How to identify **listening network services** and their associated ports?
* What is the Linux **audit system** and how is it configured?
* How to **capture and analyse network packets** using `tcpdump`?
* How to perform a basic **port scan** with Nmap?

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
| `0-login.sh` | Display user login history |
| `1-active-connections.sh` | List currently active network connections |
| `2-incoming_connections.sh` | Monitor incoming network connections |
| `3-firewall_rules.sh` | Display current iptables firewall rules |
| `4-network_services.sh` | List running network services and their ports |
| `5-audit_system.sh` | Run a basic system security audit |
| `6-capture_analyze.sh` | Capture and display live network packets |
| `7-scan.sh` | Perform a basic network scan |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `linux_security/0x00_linux_security_basics`
