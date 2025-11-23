# Windows Fundamentals Part 2 – Task Overview

This document aggregates the tasks from the TryHackMe room **[Windows Fundamentals 2](https://tryhackme.com/room/windowsfundamentals2x0x)**. Each task expands on Windows system administration tools and utilities.

---

## 📌 Task List

| # | Task Title | Brief Description |
|---|------------|-------------------|
| 1 | **Introduction** | Sets the stage for the module, building on concepts from Part 1. |
| 2 | **System Configuration (MSConfig)** | Explores the System Configuration utility – General, Boot, Services, Startup, and Tools tabs for troubleshooting startup issues. |
| 3 | **Change UAC Settings** | Guides the learner through locating and modifying User Account Control (UAC) levels. |
| 4 | **Computer Management** | Walk‑through of the Computer Management console (compmgmt.msc) – System Tools, Storage, Services & Applications, and Task Scheduler. |
| 5 | **System Information** | Uses the System Information tool (`msinfo32.exe`) to gather detailed hardware, software, and system component data. |
| 6 | **Resource Monitor** | Introduces Resource Monitor (perfmon) for real‑time performance data and troubleshooting. |
| 7 | **Command Prompt Basics** | Demonstrates useful CMD commands (`hostname`, `whoami`, `ipconfig`, etc.) for gathering system info and basic troubleshooting. |
| 8 | **Registry Editor** | Provides an overview of the Windows Registry, launching `regedit`, and navigating key locations. |
| 9 | **Conclusion** | Summarises the module’s learning outcomes and reminds the user to terminate the VM. |

---

## 🔎 Detailed Task Summaries

### 1️⃣ Introduction
- Brief recap of Part 1 concepts and instructions to launch the Windows VM for this module.

### 2️⃣ System Configuration (MSConfig)
- Open **System Configuration** (`msconfig`).
- Review each tab:
  - **General** – startup mode selection.
  - **Boot** – boot options and advanced settings.
  - **Services** – enable/disable services.
  - **Startup** – manage startup programs (via Task Manager).
  - **Tools** – quick access to system utilities.
- Demonstrates how to apply changes and reboot safely.

### 3️⃣ Change UAC Settings
- Locate the UAC slider in **Control Panel → User Accounts → Change User Account Control settings**.
- Explain the four levels of protection and their impact on prompts.

### 4️⃣ Computer Management
- Launch **Computer Management** (`compmgmt.msc`).
- Explore sections:
  - **System Tools** – Event Viewer, Device Manager, Disk Management.
  - **Storage** – Disk Management, Services.
  - **Services and Applications** – Services, Shared Folders.
  - **Task Scheduler** – creating, editing, and viewing scheduled tasks.

### 5️⃣ System Information
- Run `msinfo32.exe`.
- Highlight key categories: **System Summary**, **Hardware Resources**, **Components**, **Software Environment**.
- Show how to export the report for later analysis.

### 6️⃣ Resource Monitor
- Open **Resource Monitor** (`resmon.exe`).
- Navigate tabs: **CPU**, **Memory**, **Disk**, **Network**.
- Demonstrate filtering by process and interpreting usage graphs.

### 7️⃣ Command Prompt Basics
- Run common commands:
  - `hostname` – display the machine name.
  - `whoami` – show the current user.
  - `ipconfig /all` – detailed network adapter information.
  - `systeminfo` – summary of OS version, uptime, and hardware.
- Emphasise using `/?` for help on any command.

### 8️⃣ Registry Editor
- Launch **Registry Editor** (`regedit`).
- Explain the hierarchy: **HKEY_LOCAL_MACHINE**, **HKEY_CURRENT_USER**, etc.
- Show how to navigate to a common key (e.g., `HKLM\Software\Microsoft\Windows\CurrentVersion`).
- Warn about the risks of editing the registry.

### 9️⃣ Conclusion
- Recap the utilities covered and their practical use‑cases.
- Prompt the learner to shut down the VM.

---

## 📂 File Location
The markdown file is saved at:
```
C:\Users\Parth\OneDrive\Desktop\cyberSecPath\Pre Security\Windows Fundamentals\PART 2\Windows_Fundamentals_Part2_Tasks.md
```
Open it with any text editor or markdown viewer.

---

*Generated automatically from TryHackMe room content on 2025‑11‑23.*
