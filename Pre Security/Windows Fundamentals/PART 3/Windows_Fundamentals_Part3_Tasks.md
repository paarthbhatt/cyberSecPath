# Windows Fundamentals Part 3 – Task Overview

This document aggregates the tasks from the TryHackMe room **[Windows Fundamentals 3](https://tryhackme.com/room/windowsfundamentals3xzx)**.  The module builds on the previous two parts and focuses on built‑in security tools that keep a Windows device protected.

---

## 📌 Task List

| # | Task Title | Brief Description |
|---|------------|-------------------|
| 1 | **Introduction** | Overview of the module and instruction to launch the Windows VM. |
| 2 | **Windows Updates** | Exploration of Windows Update – how to check for, install, and configure security and feature updates. |
| 3 | **Windows Security** | Walk‑through of the Windows Security dashboard (Virus & threat protection, Account protection, Firewall & network protection, etc.). |
| 4 | **Virus & Threat Protection** | Details on real‑time protection, cloud‑delivered protection, and automatic sample submission settings. |
| 5 | **Firewall & Network Protection** | Explanation of the three firewall profiles (Domain, Private, Public) and how to configure them. |
| 6 | **App & Browser Control** | Overview of SmartScreen, reputation‑based protection, and settings for controlling apps and browsers. |
| 7 | **Device Security** | Discussion of device‑level security features, including TPM status and core isolation. |
| 8 | **BitLocker** | Introduction to BitLocker full‑disk encryption – enabling, managing keys, and recovery options. |
| 9 | **Volume Shadow Copy Service (VSS)** | Explanation of VSS, creating snapshots, and using them for backups or system restores. |
|10 | **Conclusion** | Recap of the security tools covered and reminder to terminate the virtual machine. |

---

## 🔎 Detailed Task Summaries

### 1️⃣ Introduction
- Briefly introduces the security‑focused module and asks the learner to start the provided Windows VM.

### 2️⃣ Windows Updates
- Open **Settings → Update & Security → Windows Update**.
- Show how to **Check for updates**, **View update history**, and configure **Active Hours**.
- Emphasise the importance of keeping the system patched for security.

### 3️⃣ Windows Security
- Launch the **Windows Security** app.
- Overview of the main panes:
  - **Virus & threat protection**
  - **Account protection**
  - **Firewall & network protection**
  - **Device security**
  - **App & browser control**
- Demonstrate navigating between them.

### 4️⃣ Virus & Threat Protection
- Explain **Real‑time protection**, **Cloud‑delivered protection**, and **Automatic sample submission**.
- Show how to run a **Quick scan** and view **Threat history**.

### 5️⃣ Firewall & Network Protection
- Discuss the three firewall profiles (Domain, Private, Public) and their default rules.
- Show how to **Allow an app through firewall** and enable/disable the firewall per profile.

### 6️⃣ App & Browser Control
- Cover **SmartScreen** for Microsoft Edge and Windows Store apps.
- Explain **Reputation‑based protection** for downloaded files.
- Show how to toggle **Potentially unwanted app protection**.

### 7️⃣ Device Security
- Review the **Device security** page – **Core isolation**, **Secure boot**, and **TPM** status.
- Highlight the **Security processor** information.

### 8️⃣ BitLocker
- Open **Control Panel → BitLocker Drive Encryption**.
- Steps to **Turn on BitLocker**, choose **encryption method**, and **save recovery key**.
- Explain **TPM‑only** vs **TPM + PIN** options.

### 9️⃣ Volume Shadow Copy Service (VSS)
- Introduce **VSS** as a snapshot mechanism for creating point‑in‑time copies of volumes.
- Show how to create a **shadow copy** via the **System Protection** tab or using `vssadmin` commands.
- Mention typical use‑cases: backups, system restore points.

### 🔟 Conclusion
- Summarises the security utilities covered and reinforces best practices (regular updates, enable BitLocker, keep Windows Security enabled).
- Reminds the learner to **Terminate** the VM when finished.

---

## 📂 File Location
The markdown file is saved at:
```
C:\Users\Parth\OneDrive\Desktop\cyberSecPath\Pre Security\Windows Fundamentals\PART 3\Windows_Fundamentals_Part3_Tasks.md
```
Open it with any text editor or markdown viewer.

---

*Generated automatically from TryHackMe room content on 2025‑11‑23.*
