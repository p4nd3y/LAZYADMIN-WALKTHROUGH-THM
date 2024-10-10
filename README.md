# LazyAdmin Walkthrough - TryHackMe

This repository contains a detailed walkthrough of the **LazyAdmin** room from TryHackMe. The room focuses on exploiting a misconfigured web server, identifying weak credentials, and gaining root access on a Linux machine.

## Room Info

- **Difficulty**: Easy
- **Target OS**: Linux
- **Skills Required**:
  - Basic Linux knowledge
  - Web vulnerability exploitation
  - Brute-forcing credentials
- **Tools used**: `nmap`, `gobuster`, `hydra`, `John the Ripper`, `Burp Suite`

## Objectives

The goal of the LazyAdmin room is to exploit a misconfigured web server and escalate privileges to obtain two keys:

1. **User Flag** - Gained after initial exploitation of the web server.
2. **Root Flag** - Obtained by escalating privileges to the root user.

