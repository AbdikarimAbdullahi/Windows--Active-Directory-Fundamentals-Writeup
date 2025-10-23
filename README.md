# Windows Fundamentals — TryHackMe Write-Up

## Introduction
This write-up covers my progress through the TryHackMe "Windows ADs Fundamentals" room.  
It includes key notes, commands, and insights from each task.

---

## Task 1: Introduction
Learned what the course covers and how Windows works at the system level.

## Task 2: Windows Domains
- Windows domains centralize management for users and computers.
- Active Directory and Domain Controllers handle authentication.

## Task 3: Active Directory
- AD DS stores objects like users, computers, and groups.
- Organizational Units (OUs) organize users for policy management.

## Task 4: Managing Users in AD
- Used "Active Directory Users and Computers" to add or modify users.
- Learned to reset passwords and assign users to OUs.

## Task 5: Managing Computers in AD
- Domain-joined computers appear automatically in AD.
- Moved computers into the correct OUs for easier policy application.

## Task 6: Group Policies
- GPOs enforce security and configuration settings across the domain.
- Linked specific policies to department OUs.

## Task 7: Authentication Methods
- Windows supports Kerberos and NTLM.
- AD authenticates users centrally through the Domain Controller.

## Task 8: Trees, Forests, and Trusts
- Multiple domains can form a tree.
- Trees form a forest, connected by trust relationships.

## Task 9: Conclusion
Completed the Windows Fundamentals course.  
Gained practical knowledge of Active Directory, Group Policy, and Windows network management.

---

## Key Commands and Tools
| Tool | Command | Purpose |
|------|----------|----------|
| ADUC | `dsa.msc` | Manage users and computers |
| Group Policy | `gpedit.msc` | Local group policy editor |

---

## Summary
This write-up documents how Windows domains are managed in enterprise environments.  
Centralized control through Active Directory simplifies security, authentication, and user management.
