# Linux-Privilege-escalation
Hello there! Here I will share notes for Linux privilege escalation 

Check my blog -> https://zerodex1.github.io/ You find all tgis things

# Privilege escalation
1-What’s Privilege escalation?

2-Types of Privilege escalation.

## What’s Privilege escalation :
● Privilege escalation is a critical concept in penetration testing and red teaming.

● It refers to the process of gaining elevated access or additional privileges in a computer system or network, typically from a lower-level user to a higher-level user or administrator.

● Privilege escalation involves exploiting vulnerabilities or misconfigurations to gain access to resources that are typically restricted to users with higher privileges.

## Types of Privilege escalation :
Privilege escalation can be divided in two types: vertical and horizontal.

● Vertical: the attacker is able to move from a lower privileged user to a higher privileged user. For example from a low-end user to administrator or root user.

● Horizontal: the attacker keeps the same set or level of privileges, but assumes the identity of a different user (he/she does not gain any further privilege).

## Table of contents :


- Enumeration 
 	 - System and User Enum
	- Files Enum
	- Network Enum
	- Password Enum
- Techniques
-  Kernel Exploit
- Sudo Attacks
	- CVE-2019-14287
	- CVE-2019-18634
	- Shell Escaping
	- LD-PRELOAD
- SUID
	- SUID Attacks
	- Shared Object Injection
	- Binary Symlinks
	- Environment variables
- Scheduled Tasks
	- Scheduled Tasks
	- Cron Jobs
	- Cron wildcards
	- Cron file overwrites
- Capabilities Attacks
- NFS Attack
