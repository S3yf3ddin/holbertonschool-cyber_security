# 0x02 Mandatory Access Control (SELinux)

This project introduces **Mandatory Access Control (MAC)** through **SELinux** (Security-Enhanced Linux). Unlike traditional Discretionary Access Control (DAC) where users control permissions, MAC enforces system-wide policies that even the root user cannot override. Students will learn how to inspect SELinux modes, manage security contexts, add ports to policies, and configure SELinux booleans for services such as HTTP and Sendmail.

---

## 📚 Resources

**Read or watch:**

* [Introduction to SELinux](https://www.redhat.com/en/topics/linux/what-is-selinux)
* [SELinux User's and Administrator's Guide – Red Hat](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/using_selinux/index)
* [Discretionary vs Mandatory Access Control](https://www.beyondtrust.com/resources/glossary/mandatory-access-control-mac)
* [semanage – SELinux Policy Management Tool](https://linux.die.net/man/8/semanage)
* [getsebool / setsebool Manual](https://linux.die.net/man/8/setsebool)
* [SELinux Contexts Explained](https://wiki.gentoo.org/wiki/SELinux/Contexts)

**References:**

* [SELinux Project Wiki](https://selinuxproject.org/page/Main_Page)
* [sestatus – SELinux Status Tool](https://linux.die.net/man/8/sestatus)
* [chcon – Change SELinux Context](https://man7.org/linux/man-pages/man1/chcon.1.html)
* [audit2allow – Generate SELinux Policy from Audit Logs](https://linux.die.net/man/1/audit2allow)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* What is **Mandatory Access Control** and how does it differ from DAC?
* What are the three **SELinux operating modes** (Enforcing, Permissive, Disabled)?
* How to check the **current SELinux mode** and status?
* What is an **SELinux security context** and what do its fields mean?
* How to **list and modify security contexts** for files and processes?
* How to **add a port** to an SELinux policy?
* What are **SELinux booleans** and how do they tune policy behaviour?
* How to configure **Sendmail** (or HTTP) within an SELinux policy?

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
| `0-analyse_mode.sh` | Display the current SELinux enforcement mode |
| `1-security_match.sh` | Check whether a security context matches a policy rule |
| `2-list_http.sh` | List all SELinux contexts related to HTTP |
| `3-add_port.sh` | Add a TCP/UDP port to an SELinux policy |
| `4-list_user.sh` | List SELinux user mappings |
| `5-add_selinux.sh` | Add a custom SELinux rule |
| `6-list_booleans.sh` | List all SELinux policy booleans |
| `7-set_sendmail.sh` | Configure an SELinux boolean for Sendmail |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `linux_security/0x02_mandatory_access_control`
