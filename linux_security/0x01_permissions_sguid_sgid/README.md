# 0x01 Permissions, SUID & SGID

This project focuses on **Linux file permissions** and the special permission bits **SUID** (Set User ID) and **SGID** (Set Group ID). Students will learn how to manage users and groups, configure `sudo` without password prompts, locate files by their permission bits, and understand the security implications of SUID/SGID binaries. Misconfigured permissions are one of the most common vectors for local privilege escalation.

---

## 📚 Resources

**Read or watch:**

* [Linux File Permissions Explained](https://linuxize.com/post/understanding-linux-file-permissions/)
* [SUID, SGID, and Sticky Bit](https://www.redhat.com/sysadmin/suid-sgid-sticky-bit)
* [sudo Configuration](https://www.sudo.ws/docs/man/sudoers.man/)
* [find command – Search by Permissions](https://man7.org/linux/man-pages/man1/find.1.html)
* [Linux Privilege Escalation via SUID Binaries](https://gtfobins.github.io/)
* [useradd / groupadd Manual](https://man7.org/linux/man-pages/man8/useradd.8.html)

**References:**

* [GTFOBins – Unix Binaries for Privilege Escalation](https://gtfobins.github.io/)
* [chmod Manual](https://man7.org/linux/man-pages/man1/chmod.1.html)
* [chown / chgrp Manual](https://man7.org/linux/man-pages/man1/chown.1.html)

---

## 🎯 Learning Objectives

At the end of this project, you are expected to be able to explain the following to anyone, **without the help of Google**:

* How are **Linux file permissions** structured (owner, group, others)?
* What is the **SUID bit** and what security risk does it introduce?
* What is the **SGID bit** and when is it legitimately used?
* How to **add users and groups** from the command line?
* How to configure **passwordless sudo** for specific commands?
* How to use `find` to **locate files by permission bits**?
* Why are world-writable or SUID files a **privilege escalation risk**?
* How to **change file ownership** and permissions safely?

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
| `0-add_user.sh` | Add a new user to the system |
| `1-add_group.sh` | Add a new group to the system |
| `2-sudo_nopass.sh` | Configure a user to run a command without a password via sudo |
| `3-find_files.sh` | Find files matching a specific permission pattern |
| `4-find_suid.sh` | Find all SUID-enabled files on the system |
| `5-find_sgid.sh` | Find all SGID-enabled files on the system |
| `6-check_files.sh` | Check permissions on sensitive system files |
| `7-file_read.sh` | Display read permissions of a specified file |
| `8-change_user.sh` | Switch to a different user context |
| `9-empty_file.sh` | Create and manage an empty file with specific permissions |

---

## 📋 Repository Information

* **GitHub repository:** `holbertonschool-cyber_security`
* **Directory:** `linux_security/0x01_permissions_sguid_sgid`
