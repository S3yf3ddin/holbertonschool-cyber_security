# 0x05 Wireshark Basics

**Wireshark** is the world's most widely used network protocol analyser. This project introduces students to capturing and filtering network traffic using Wireshark's powerful **display filters**. Students will construct filters for common scan types (TCP SYN, TCP Connect, FIN, XMAS, UDP, ICMP) as well as for ping sweeps and ARP scanning. Understanding how scans look "on the wire" is invaluable for both attackers and defenders.

---

## 📚 Resources

**Read or watch:**

* [Wireshark User's Guide](https://www.wireshark.org/docs/wsug_html_chunked/)
* [Wireshark Display Filter Reference](https://www.wireshark.org/docs/dfref/)
* [TCP Flags Explained (SYN, ACK, FIN, RST, PSH, URG)](https://www.cloudflare.com/learning/ddos/glossary/tcp-flags/)
* [Nmap Scan Types and Their Packet Signatures](https://nmap.org/book/man-port-scanning-techniques.html)
* [Wireshark – Filtering Packets](https://wiki.wireshark.org/DisplayFilters)
* [ICMP Explained](https://www.cloudflare.com/learning/ddos/glossary/internet-control-message-protocol-icmp/)

**References:**

* [Wireshark Cheat Sheet](https://www.stationx.net/wireshark-cheat-sheet/)
* [tcpdump vs Wireshark](https://www.varonis.com/blog/tcpdump)
* [RFC 793 – Transmission Control Protocol](https://www.rfc-editor.org/rfc/rfc793)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **Wireshark** and how is it used in security analysis?
* How to write a **display filter** to isolate specific traffic?
* What TCP flags are set during an **IP scan**, **SYN scan**, and **Connect scan**?
* What distinguishes a **FIN scan** from an **XMAS scan** at the packet level?
* How does a **TCP ping sweep** appear in a packet capture?
* What are the characteristics of a **UDP port scan** in Wireshark?
* How to identify **ICMP** and **ARP scanning** traffic in a capture file?

---

## ⚙️ Requirements

### General

* **Operating System:** All files will be run on **Kali Linux 2023.2**.
* **Allowed editors:** `vi`, `vim`, `emacs`.
* All answer files must contain only the Wireshark display filter string on a single line.
* All your files must end with a new line.

---

## 📁 Files

| File | Description |
|------|-------------|
| `0-ip_scan.txt` | Wireshark filter to capture a basic IP scan |
| `1-tcp_syn.txt` | Wireshark filter to identify TCP SYN scan traffic |
| `2-tcp_connect_scan.txt` | Wireshark filter for a full TCP Connect scan |
| `3-tcp_fin.txt` | Wireshark filter for a TCP FIN scan |
| `4-tcp_ping_sweep.txt` | Wireshark filter for a TCP-based ping sweep |
| `5-udp_port_scan.txt` | Wireshark filter for a UDP port scan |
| `6-udp_ping_sweep.txt` | Wireshark filter for a UDP ping sweep |
| `7-icmp_ping_sweep.txt` | Wireshark filter for an ICMP ping sweep |
| `8-arp_scanning.txt` | Wireshark filter for ARP-based scanning |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `network_security/0x05_wireshark_basics`
