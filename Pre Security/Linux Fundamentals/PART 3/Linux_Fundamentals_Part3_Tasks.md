# Linux Fundamentals Part 3 – Task Overview

This document aggregates the tasks from the TryHackMe room **[Linux Fundamentals Part 3](https://tryhackme.com/room/linuxfundamentalspart3)**.  Each task focuses on a practical Linux utility or concept and provides hands‑on experience with an in‑browser Ubuntu VM.

---

## 📌 Task List

| # | Task Title | Brief Description |
|---|------------|-------------------|
| 1 | **Introduction** | Overview of the module and what will be covered (terminal utilities, automation, logs, etc.). |
| 2 | **Deploy Your Linux Machine** | Deploy the virtual machine and get connected via the provided SSH details. |
| 3 | **Terminal Text Editors** | Learn to create and edit files using editors like `nano` (and optionally `vim`). |
| 4 | **General / Useful Utilities** | Work with common utilities such as Python’s `http.server`, `wget`, and other everyday tools. |
| 5 | **Processes 101** | Identify process IDs, view running processes, and send signals (`kill`, `pkill`). |
| 6 | **Maintaining Your System: Automation** | Explore automation via `cron` jobs and basic scheduling. |
| 7 | **Maintaining Your System: Package Management** | Use `apt` to install, update, and remove packages; understand repositories. |
| 8 | **Maintaining Your System: Logs** | Locate and read log files (`/var/log`), use `tail`, `less`, and log rotation basics. |
| 9 | **Conclusions & Summaries** | Recap of utilities covered and next steps in the Linux Fundamentals series. |

---

## 🔎 Detailed Task Summaries

### 1️⃣ Introduction
- Sets expectations for the module, highlighting the focus on everyday utilities, process management, automation, package handling, and log analysis.

### 2️⃣ Deploy Your Linux Machine
- Walk‑through of pressing **Start Machine**, locating the SSH connection string, and logging in with `ssh`. Emphasises the importance of a stable remote session.

### 3️⃣ Terminal Text Editors
- Demonstrates creating a file with `nano`, editing its contents, saving, and exiting. Optionally covers basic `vim` commands for power users.

### 4️⃣ General / Useful Utilities
- **Python HTTP Server** – `python3 -m http.server` to serve a directory.
- **wget** – download files from the internet.
- Brief mention of other handy tools (`cat`, `head`, `tail`, `date`).

### 5️⃣ Processes 101
- Use `ps aux` / `top` to list processes.
- Find a process ID with `pgrep`.
- Send signals with `kill <PID>` and `pkill <name>`.
- Explain the difference between `SIGTERM` and `SIGKILL`.

### 6️⃣ Maintaining Your System: Automation
- Introduce `cron` syntax.
- Create a simple cron job that runs a script every minute.
- Show how to view existing cron jobs with `crontab -l`.

### 7️⃣ Maintaining Your System: Package Management
- Update package lists: `sudo apt update`.
- Install a package: `sudo apt install <package>`.
- Upgrade installed packages: `sudo apt upgrade`.
- Remove a package: `sudo apt remove <package>`.
- Explain `apt-cache search` for finding packages.

### 8️⃣ Maintaining Your System: Logs
- Locate system logs in `/var/log` (e.g., `syslog`, `auth.log`).
- View recent entries with `tail -f /var/log/syslog`.
- Use `less` for paging through large logs.
- Brief note on log rotation (`logrotate`).

### 9️⃣ Conclusions & Summaries
- Recaps the key utilities and concepts learned.
- Provides a checklist for the learner to verify they can:
  - Deploy and SSH into a VM.
  - Edit files with a terminal editor.
  - Use common utilities (`wget`, `python -m http.server`).
  - Manage processes and signals.
  - Schedule tasks with `cron`.
  - Install/remove packages via `apt`.
  - Read and interpret system logs.
- Points to the next module (**Linux Fundamentals Part 4**) for deeper networking and scripting.

---

## 📂 File Location
The markdown file is saved at:
```
C:\Users\Parth\OneDrive\Desktop\cyberSecPath\Pre Security\Linux Fundamentals\PART 3\Linux_Fundamentals_Part3_Tasks.md
```
Open it with any text editor or markdown viewer.

---

*Generated automatically from the TryHackMe room content on 2025‑11‑23.*
