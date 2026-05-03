# TryHackMe: lazyadmin

## Room Information

- **Platform:** TryHackMe
- **Room:** LazyAdmin
- **Difficulty:** Easy
- **Category:** Linux / Web Hacking / Privilege Escalation
- **Date Completed:** 2026-05-02
- **Write-up Author:** Jake

## Disclaimer

This write-up is for educational purposes only. The techniques shown here were performed in an authorized TryHackMe lab environment. No flags, passwords, or answer strings are included.

---

# Summary

Briefly explain what the room was about.

Example:

> The direction I took for this room focused on basic enumeration, exploiting a misconfigured web service through a file upload vulnerability as well as a misconfigured sudo enabled binary by the logged in user

---

# Skills Practiced

- Network scanning
- Service enumeration
- Web enumeration
- Source code inspection
- Directory brute forcing
- Credential discovery
- Command execution
- Linux privilege escalation
- File system navigation
- Sudo permissions review

---

# Tools Used

- Nmap
- Gobuster / Feroxbuster
- Netcat
- LinPEAS / manual Linux enumeration
- Python
- Bash
- Other tools used

---

# Lab Setup

Attacker Box: Kali Linux VM, 4GB of Ram, 2 CPUs, running on Virtualbox on Ubuntu LTS 24.04 Desktop host

## Target

```text
Target IP: 