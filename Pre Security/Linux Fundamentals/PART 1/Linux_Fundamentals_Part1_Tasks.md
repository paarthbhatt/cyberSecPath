# Linux Fundamentals Part 1 – Task Overview

This document consolidates the tasks presented in the TryHackMe room **[Linux Fundamentals Part 1](https://tryhackme.com/room/linuxfundamentalspart1)**. Each task focuses on a core Linux concept and provides hands‑on practice with an in‑browser virtual machine.

---

## 📌 Task List

| # | Task Title | Brief Description |
|---|------------|-------------------|
| 1 | **Introduction** | Overview of the module, learning objectives, and how the room is structured. |
| 2 | **A Bit of Background on Linux** | History, common use‑cases, and the various *flavours* (distributions) of Linux. |
| 3 | **Interacting With Your First Linux Machine (In‑Browser)** | Deploy the Ubuntu VM, locate the IP/expiry timer, and learn how to start/terminate the machine. |
| 4 | **Running Your First Few Commands** | Basic commands such as `echo` and `whoami` to get comfortable with the terminal. |
| 5 | **Interacting With the Filesystem** | Filesystem navigation (`ls`, `cd`, `pwd`) and file content display (`cat`). |
| 6 | **Searching for Files** | Using `find` and `grep` to locate files and search within them. |
| 7 | **An Introduction to Shell Operators** | Operators like `&`, `&&`, `>`, `>>` and how they affect command execution and redirection. |
| 8 | **Conclusions & Summaries** | Recap of the concepts covered and next steps in the series. |

---

## 🔎 Detailed Task Summaries

### 1️⃣ Introduction
- Sets the stage for the series and explains what you’ll learn.
- Links to the *Start Machine* button and the tutorial for managing the VM.

### 2️⃣ A Bit of Background on Linux
- Discusses why Linux is lightweight, where it’s used (websites, cars, POS, critical infra).
- Introduces major distributions – Ubuntu & Debian – and notes that the room uses **Ubuntu**.

### 3️⃣ Interacting With Your First Linux Machine (In‑Browser)
- Walk‑through of pressing **Start Machine**, locating the IP address, and terminating the instance.
- Emphasises the terminal‑only environment (no GUI).

### 4️⃣ Running Your First Few Commands
- `echo` – output text, with/without quotes.
- `whoami` – display the current user.
- Example snippets are provided in the room.

### 5️⃣ Interacting With the Filesystem
- **`ls`** – list directory contents.
- **`cd`** – change directory.
- **`pwd`** – print working directory (found in a separate chunk).
- **`cat`** – display file contents, useful for reading notes, flags, passwords.
- Includes useful *pro‑tips* (e.g., `ls Pictures` without navigating).

### 6️⃣ Searching for Files
- **`find`** – locate files by name or pattern (`*.txt`).
- Demonstrates searching for `passwords.txt` and all `.txt` files.
- Shows how `find` can quickly narrow down files across nested directories.

### 7️⃣ An Introduction to Shell Operators
- `&` – run command in background.
- `&&` – chain commands (run next only if previous succeeds).
- `>` and `>>` – redirect output to a file (overwrite vs append).
- Brief examples illustrate each operator.

### 8️⃣ Conclusions & Summaries
- Recaps key take‑aways and prepares you for **Linux Fundamentals Part 2**.

---

## 📂 Where to Find This File
The markdown file is saved at:
```
C:\Users\Parth\OneDrive\Desktop\cyberSecPath\Pre Security\Linux Fundamentals\PART 1\Linux_Fundamentals_Part1_Tasks.md
```
You can open it with any text editor or markdown viewer.

---

*Generated automatically from the TryHackMe room content on 2025‑11‑23.*
