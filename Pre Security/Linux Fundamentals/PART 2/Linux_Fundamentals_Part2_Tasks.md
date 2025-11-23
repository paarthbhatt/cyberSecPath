# Linux Fundamentals Part 2 – Task Overview

This document aggregates the tasks from the TryHackMe room **[Linux Fundamentals Part 2](https://tryhackme.com/room/linuxfundamentalspart2)**.  Each task focuses on a specific Linux concept and provides hands‑on practice with an in‑browser Ubuntu VM.

---

## 📌 Task List

| # | Task Title | Brief Description |
|---|------------|-------------------|
| 1 | **Introduction** | Overview of the module, flags, arguments, advanced filesystem operations, and permissions. |
| 2 | **Accessing Your Linux Machine Using SSH (Deploy)** | Deploy the machine and connect via SSH to a remote Linux instance. |
| 3 | **Introduction to Flags and Switches** | Learn how to extend command functionality with flags/switches (e.g., `man ls`). |
| 4 | **Filesystem Interaction Continued** | Commands for creating, moving, removing, copying, and identifying file types (`touch`, `mkdir`, `rm`, `cp`, `mv`, `file`). |
| 5 | **Permissions 101** | Explore file and directory permissions, list them, and switch users to understand access control. |
| 6 | **Common Directories** | Overview of standard Linux directories such as `/etc`, `/var`, `/root`, `/tmp`. |
| 7 | **Conclusions & Summaries** | Recap of SSH, flags, filesystem interaction, and permissions; next steps in the series. |

---

## 🔎 Detailed Task Summaries

### 1️⃣ Introduction
- Sets expectations for the module and outlines the topics that will be covered: flags, arguments, advanced filesystem commands, and permissions.

### 2️⃣ Accessing Your Linux Machine Using SSH (Deploy)
- Walk‑through of pressing **Start Machine**, locating the SSH connection details, and using `ssh` to log in from the terminal.
- Highlights the importance of secure remote access.

### 3️⃣ Introduction to Flags and Switches
- Demonstrates how to read manual pages (`man <command>`) and use common flags (e.g., `ls -l`, `cat -n`).
- Shows how flags modify command behaviour.

### 4️⃣ Filesystem Interaction Continued
- **`touch`** – create an empty file.
- **`mkdir`** – create a directory.
- **`rm`**, **`rm -r`** – delete files/directories.
- **`cp`**, **`mv`** – copy and move files.
- **`file`** – identify file type.
- Provides example snippets for each command.

### 5️⃣ Permissions 101
- Uses `ls -l` to display permission bits.
- Explains the meaning of `rwx` for owner, group, others.
- Shows `chmod`, `chown`, and `sudo` to change permissions and ownership.

### 6️⃣ Common Directories
- Brief description of key system directories:
  - **`/etc`** – configuration files.
  - **`/var`** – variable data (logs, caches).
  - **`/root`** – root user’s home.
  - **`/tmp`** – temporary files.
- Encourages exploration of their contents with `ls` and `cat`.

### 7️⃣ Conclusions & Summaries
- Recaps the concepts learned and points to the next module (**Linux Fundamentals Part 3**).
- Provides a short checklist for the learner to verify they can:
  - SSH into a remote machine.
  - Use flags to modify commands.
  - Perform basic file operations.
  - Understand and modify permissions.

---

## 📂 File Location
The markdown file is saved at:
```
C:\Users\Parth\OneDrive\Desktop\cyberSecPath\Pre Security\Linux Fundamentals\PART 2\Linux_Fundamentals_Part2_Tasks.md
```
Open it with any text editor or markdown viewer.

---

*Generated automatically from the TryHackMe room content on 2025‑11‑23.*
