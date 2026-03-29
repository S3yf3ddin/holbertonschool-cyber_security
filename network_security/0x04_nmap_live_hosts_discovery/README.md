# 0x04 Nmap – Live Hosts Discovery

Before scanning ports, a penetration tester must first determine which **hosts are alive** on a network. This project explores the various **ping/sweep techniques** that Nmap offers to discover live hosts: ARP scan, ICMP echo, ICMP timestamp, ICMP address mask, TCP SYN ping, TCP ACK ping, and UDP ping. Each technique has different characteristics in terms of reliability, stealth, and applicability.

---

## 📚 Resources

**Read or watch:**

* [Nmap Host Discovery](https://nmap.org/book/man-host-discovery.html)
* [ARP Scanning Explained](https://www.varonis.com/blog/arp-scan)
* [ICMP Types and Codes](https://www.iana.org/assignments/icmp-parameters/icmp-parameters.xhtml)
* [TCP SYN vs ACK Ping Probes](https://nmap.org/book/host-discovery-techniques.html)
* [UDP Ping Scanning](https://nmap.org/book/host-discovery-techniques.html#host-discovery-UDP)
* [Nmap Reference Guide](https://nmap.org/book/man.html)

**References:**

* [Nmap Official Documentation](https://nmap.org/docs.html)
* [Wireshark – Inspect Discovery Traffic](https://www.wireshark.org/)
* [RFC 792 – ICMP](https://www.rfc-editor.org/rfc/rfc792)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **host discovery** and why does it precede port scanning?
* How does an **ARP scan** work and when is it limited to the local subnet?
* What are the differences between **ICMP echo**, **timestamp**, and **address mask** probes?
* When would you choose a **TCP SYN ping** over a **TCP ACK ping**?
* What is a **UDP ping scan** and what are its limitations?
* How to use Nmap's `-sn` (no port scan) flag for efficient discovery?
* What Nmap flags correspond to each host discovery technique?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Allowed editors:** `vi`, `vim`, `emacs`.
* **Shebang:** The first line of all your Bash scripts must be exactly `#!/bin/bash`.
* **Script Constraints:** You are **not allowed** to use backticks, `&&`, `||`, or `;`.
* All your files must end with a new line.
* All your files must be executable.
* Scripts must accept the target IP range as the first argument `$1`.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-arp_scan.sh` | Discover live hosts using ARP requests |
| `1-icmp_echo_scan.sh` | Discover hosts using ICMP echo (ping) probes |
| `2-icmp_timestamp_scan.sh` | Discover hosts using ICMP timestamp requests |
| `3-icmp_address_mask_scan.sh` | Discover hosts using ICMP address mask requests |
| `4-tcp_syn_ping.sh` | Discover hosts using TCP SYN packets |
| `5-tcp_ack_ping.sh` | Discover hosts using TCP ACK packets |
| `6-udp_ping_scan.sh` | Discover hosts using UDP probes |
| `100-flag.txt` | CTF flag captured during the exercise |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `network_security/0x04_nmap_live_hosts_discovery`
