# Linux Command Handbook

A personal collection of Linux commands, notes, and practical examples created during my journey of learning **Linux, Cyber Security, and Ethical Hacking**.

This repository is a structured reference where I document the commands I practice, understand their purpose, and build my command-line skills step by step.

---

## About This Handbook

Linux plays a fundamental role in Cyber Security. Understanding the Linux terminal, file system, permissions, networking, and system operations is essential for security professionals.

The purpose of this handbook is to:

- Build strong Linux fundamentals
- Understand command usage and practical applications
- Improve terminal skills through regular practice
- Maintain a personal reference for future cybersecurity labs

---

##  Practice Environment

- OS: Kali Linux
- Virtual Environment: VMware Workstation
- Learning Focus: Linux Fundamentals & Cyber Security

---
---


#  Package Management

Package management commands are used to update and maintain software packages in Linux systems.

| Command | Description | Example |
|---|---|---|
| `sudo apt update` | Update package list from repositories | `sudo apt update` |
| `sudo apt upgrade` | Upgrade installed packages to the latest version | `sudo apt upgrade` |

---

#  File & Directory Management Commands

These commands are used to create, copy, move, and delete files and directories.

| Command | Description | Example |
|---|---|---|
| `mkdir <folder_name>` | Create a new folder | `mkdir Invoice` |
| `touch <file_name>` | Create an empty file | `touch new01.txt` |
| `cp <file_name> <location>` | Copy a file to another location | `cp new01.txt /home/kali/Desktop` |
| `cp -r <folder_name> <location>` | Copy a folder with all contents | `cp -r Invoice /home/kali/Desktop` |
| `mv <file_name> <location> or <rename>` | Move or rename a file | `mv new01.txt new001.txt` |
| `rm <file_name>` | Delete a file | `rm new02.txt` |
| `rm -rf <folder_name>` | Force delete a folder and its contents | `rm -rf Invoice` |

---

# Navigation Commands

Navigation commands are used to move between directories and explore the Linux file system.

| Command | Description | Example |
|---|---|---|
| `pwd` | Shows the current working directory path | `pwd` |
| `ls` | Lists files and folders in the current directory | `ls` |
| `ls -la` | Lists all files including hidden files with detailed information | `ls -la` |
| `cd` | Go to the home directory | `cd` |
| `cd <folder_name>` | Go to a specific folder | `cd Desktop` |
| `cd ../` | Go to the parent directory | `cd ../` |
| `../` | Represents the parent directory | `../` |
| `cd /usr/bin` | Navigate to the system binary directory | `cd /usr/bin` |
| `ls /mnt/hgfs` | View VMware shared folder contents | `ls /mnt/hgfs` |

---

# File Viewing & Editing Commands

These commands are used to view and edit files from the Linux terminal.

| Command | Description | Example |
|---|---|---|
| `cat <file_name>` | Displays the contents of a file | `cat new02.txt` |
| `nano <file_name>` | Opens or creates a file using Nano editor | `nano new02.txt` |
| `mousepad <file_name>` | Opens or creates a file using Mousepad editor | `mousepad new03.txt` |

---

# User & Permission Management Commands

These commands are used to manage users, view user information, and control file permissions in Linux.

| Command | Description | Example |
|---|---|---|
| `whoami` | Shows the current logged-in username | `whoami` |
| `id` | Shows user ID, group ID, and group information | `id` |
| `passwd` | Change the user password | `passwd` |
| `chmod` | Change file or directory permissions | `chmod 755 file.sh` |
| `chmod +x <file_name>` | Make a file executable | `chmod +x zpshisher.sh` |

---

# Search & Filter Commands

These commands are used to find files and search for specific information inside files.

| Command | Description | Example |
|---|---|---|
| `find / -name "<file_name>" 2>/dev/null` | Search for a file by name from the root directory | `find / -name "test.txt" 2>/dev/null` |
| `find / -name "*.<extension>" 2>/dev/null` | Search files by extension | `find / -name "*.txt" 2>/dev/null` |
| `grep <text>` | Search for specific text or patterns | `grep "password" file.txt` |

---

# Directory Structure Commands

These commands help to view and understand the structure of directories and folders in Linux.

| Command | Description | Example |
|---|---|---|
| `tree` | Shows the directory structure in a tree format | `tree` |
| `tree -L 2` | Shows directory structure up to 2 levels | `tree -L 2` |

---

# Networking Commands

These commands are used to view network information, check connectivity, and troubleshoot network-related issues.

| Command | Description | Example |
|---|---|---|
| `ifconfig` | Shows network interface information and IP details | `ifconfig` |
| `ip addr` | Displays IP address and network interface details | `ip addr` |
| `ping <host>` | Tests network connectivity between your system and a host | `ping google.com` |

---
---

# Git Commands

Git commands are used to manage repositories and work with GitHub projects.

| Command | Description | Example |
|---|---|---|
| `git clone <URL>` | Downloads a repository from GitHub to your local system | `git clone https://github.com/user/repository.git` |

---

# Security Script Execution Commands

These commands are used to give execution permission to scripts and run executable files in Linux.

| Command | Description | Example |
|---|---|---|
| `chmod +x <file_name>` | Gives execute permission to a script file | `chmod +x zpshisher.sh` |
| `./<file_name>` | Runs an executable script from the current directory | `./zpshisher.sh` |

---

# Terminal Utility Commands

These commands are commonly used for managing and working efficiently with the Linux terminal.

| Command | Description | Example |
|---|---|---|
| `history` | Shows previously executed commands | `history` |
| `clear` | Clears the terminal screen | `clear` |
| `exit` | Closes the terminal session | `exit` |

---

# Responsible Use

The commands and security-related information in this repository are collected for educational purposes and personal practice.

Always use Linux commands, security tools, and techniques only on systems where you have proper authorization.

---

# Updates

This repository will be updated regularly with new commands, examples, and cybersecurity learning notes.

# Learning • Practicing • Improving
