# Offensive Security Intro – Task Overview

This document aggregates the tasks from the TryHackMe room **[Offensive Security Intro](https://tryhackme.com/room/offensivesecurityintro)**. The module provides a beginner-friendly introduction to ethical hacking by simulating an attack on a fake banking application.

---

## 📌 Task List

| # | Task Title | Brief Description |
|---|------------|-------------------|
| 1 | **What is Offensive Security?** | Introduction to ethical hacking, Red Teams, and legal boundaries. |
| 2 | **Hacking Your First Machine** | Hands-on: Discovering hidden pages using tools like Gobuster. |
| 3 | **Force a Bank Transfer** | Hands-on: Exploiting a vulnerability to perform an unauthorized action. |
| 4 | **Careers in Cyber Security** | Overview of roles like Penetration Tester and Red Teamer. |

---

## 🔎 Detailed Task Summaries

### 1️⃣ What is Offensive Security?
- Defines "Offensive Security" as the proactive approach to security: breaking in to find fixes.
- **Ethical Hacking**: Testing with permission.
- **Red Teaming**: Simulating a full-scope adversary attack.
- **Penetration Testing**: Focused testing of specific systems or apps.

### 2️⃣ Hacking Your First Machine
- **Scenario**: You are auditing "FakeBank".
- **Tool**: Using a command-line tool (like `gobuster` or a simplified in-browser equivalent) to find hidden directories.
- **Goal**: Discover the `/bank-transfer` or `/admin` page that isn't linked from the homepage.
- **Concept**: Security through obscurity is not security.

### 3️⃣ Force a Bank Transfer
- **Exploit**: Accessing the hidden admin portal discovered in the previous task.
- **Action**: Transferring funds from a target account to your own (simulated).
- **Outcome**: Retrieving a "flag" to prove the exploit worked.
- **Lesson**: Broken Access Control – just hiding a page doesn't protect it; proper authentication is needed.

### 4️⃣ Careers in Cyber Security
- Discusses the professional landscape.
- **Penetration Tester**: Finds bugs for clients.
- **Red Teamer**: Tests the Blue Team's detection capabilities.
- **Security Engineer**: Builds secure systems (Purple Team).

---

## 📂 File Location
The markdown file is saved at:
```
C:\Users\Parth\OneDrive\Desktop\cyberSecPath\Cyber Security 101\Start Journey\Offensive Security Intro.md
```
Open it with any text editor or markdown viewer.

---

*Generated automatically from TryHackMe room content on 2025‑11‑24.*
