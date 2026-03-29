# 0x06 Nmap – Advanced Port Scans

This project covers **advanced and stealth port-scanning techniques** available in Nmap. While the SYN scan is the most common choice, certain network environments (e.g., stateless firewalls, IDS evasion) call for alternative methods. Students will implement NULL, FIN, XMAS, Maimon, ACK, and Window scans, as well as custom flag combinations — understanding not only how to use them but also why each technique behaves differently against various target configurations.

---

## 📚 Resources

**Read or watch:**

* [Nmap Port Scanning Techniques](https://nmap.org/book/man-port-scanning-techniques.html)
* [Stealth Scan Types Explained](https://nmap.org/book/synscan.html)
* [TCP RFC and Flag Behaviour](https://www.rfc-editor.org/rfc/rfc793)
* [Firewall and IDS Evasion with Nmap](https://nmap.org/book/man-bypass-firewalls-ids.html)
* [NULL, FIN, XMAS Scans – Limitations](https://nmap.org/book/scan-methods-null-fin-xmas-scan.html)
* [ACK and Window Scans for Firewall Ruleset Mapping](https://nmap.org/book/scan-methods-ack-scan.html)

**References:**

* [Nmap Reference Guide](https://nmap.org/book/man.html)
* [Wireshark – Verifying Scan Traffic](https://www.wireshark.org/)
* [RFC 793 – TCP State Machine](https://www.rfc-editor.org/rfc/rfc793)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is the difference between a **NULL scan**, a **FIN scan**, and an **XMAS scan**?
* Why do these scans **bypass some stateless firewalls**?
* Why do NULL/FIN/XMAS scans **not work reliably against Windows** targets?
* What is a **Maimon scan** and against which systems is it effective?
* What does an **ACK scan** tell you about a target's firewall rules?
* How does the **Window scan** differ from the ACK scan?
* When would you use a **custom scan** with specific TCP flag combinations?
* How can Nmap results differ depending on **firewall state** (open vs. filtered)?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Allowed editors:** `vi`, `vim`, `emacs`.
* **Shebang:** The first line of all your Bash scripts must be exactly `#!/bin/bash`.
* **Script Constraints:** You are **not allowed** to use backticks, `&&`, `||`, or `;`.
* All your files must end with a new line.
* All your files must be executable.
* Scripts must accept the target as the first argument `$1`.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-null_scan.sh` | Perform an Nmap NULL scan (no TCP flags set) |
| `1-fin_scan.sh` | Perform an Nmap FIN scan (only FIN flag set) |
| `2-xmas_scan.sh` | Perform an Nmap XMAS scan (FIN + PSH + URG flags) |
| `3-maimon_scan.sh` | Perform an Nmap Maimon scan (FIN + ACK flags) |
| `4-ask_scan.sh` | Perform an Nmap ACK scan (firewall rule mapping) |
| `5-window_scan.sh` | Perform an Nmap Window scan |
| `6-custom_scan.sh` | Perform an Nmap scan with custom TCP flags |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `network_security/0x06_nmap_advanced_port_scans`
