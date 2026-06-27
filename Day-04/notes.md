# Day 04 - Introduction to Linux

## Objective

To understand the fundamentals of Linux, its importance in Cloud Computing and DevOps, explore popular Linux distributions, install Linux using WSL, and practice essential Linux terminal commands.

---

# What is Linux?

Linux is a free and open-source operating system based on the Linux kernel, created by Linus Torvalds in 1991. It is widely used in servers, cloud platforms, embedded systems, and software development due to its stability, security, and flexibility.

### Key Features

* Open Source
* Secure
* Stable
* Multi-user
* Multitasking
* Highly customizable
* Command-line support
* Efficient resource management

---

# Why Linux is Widely Used in the IT Industry

Linux powers most of the world's servers and cloud infrastructure.

### Reasons

* High performance
* Excellent security
* Low resource usage
* Reliable for 24/7 systems
* Preferred by cloud providers
* Strong community support
* Free to use

### Common Uses

* Web Servers
* Database Servers
* Cloud Computing
* DevOps
* Cybersecurity
* Containers (Docker)
* Kubernetes Clusters

---

# Advantages of Linux

| Linux                 | Other Operating Systems    |
| --------------------- | -------------------------- |
| Open Source           | Mostly Proprietary         |
| Free                  | Usually Paid               |
| Highly Secure         | More Vulnerable to Malware |
| Lightweight           | Higher Resource Usage      |
| Ideal for Servers     | Mostly Desktop Focused     |
| Powerful Command Line | GUI Focused                |

---

# Linux Distributions

A Linux Distribution (Distro) is an operating system built using the Linux kernel along with software packages and tools.

### Popular Linux Distributions

### Ubuntu

* Beginner friendly
* Most commonly used in Cloud Computing
* Excellent community support

### Debian

* Stable and secure
* Preferred for production servers

### CentOS

* Enterprise Linux distribution
* Traditionally used in enterprise environments

### Fedora

* Latest Linux technologies
* Community-driven

### Arch Linux

* Lightweight
* Highly customizable
* Advanced users

---

# Installing Linux Using WSL

## What is WSL?

WSL (Windows Subsystem for Linux) allows Linux to run directly on Windows without requiring a virtual machine or dual boot.

### Benefits

* Easy installation
* Native Linux terminal
* Low resource usage
* Perfect for development
* Supports Linux commands on Windows

### Installation Steps

1. Enable WSL.
2. Install Ubuntu from the Microsoft Store.
3. Restart the computer if required.
4. Create a Linux username and password.
5. Open the Ubuntu terminal and start using Linux commands.

---

# Basic Linux Terminal Commands

## 1. Print Working Directory

```bash
pwd
```

Displays the current directory.

---

## 2. List Files and Folders

```bash
ls
```

Shows files and directories in the current location.

---

## 3. Change Directory

```bash
cd folder-name
```

Moves to another directory.

---

## 4. Create a Directory

```bash
mkdir folder-name
```

Creates a new directory.

---

## 5. Remove a Directory

```bash
rmdir folder-name
```

Deletes an empty directory.

---

## 6. Create a File

```bash
touch filename.txt
```

Creates an empty file.

---

## 7. Copy Files

```bash
cp source destination
```

Copies files or folders.

---

## 8. Move or Rename Files

```bash
mv oldname newname
```

Moves or renames files.

---

## 9. Delete Files

```bash
rm filename
```

Deletes files.

---

## 10. Clear Terminal

```bash
clear
```

Clears the terminal screen.

---

## 11. Display File Contents

```bash
cat filename
```

Displays the contents of a file.

---

## 12. Current User

```bash
whoami
```

Shows the currently logged-in user.

---

## 13. System Information

```bash
uname -a
```

Displays detailed information about the Linux system and kernel.

---

# Commands Practiced Today

```bash
pwd
ls
cd
mkdir
rmdir
touch
cp
mv
rm
clear
cat
whoami
uname -a
```

---

# Hands-On Practice

* Installed Ubuntu using WSL
* Opened the Linux terminal
* Navigated directories
* Created folders
* Created files
* Copied files
* Renamed files
* Deleted files
* Displayed file contents
* Checked current user
* Viewed system information

---

# Key Takeaway

Linux is more than an operating system—it is the backbone of modern Cloud Computing and DevOps. Most cloud servers are managed using the command line, making Linux terminal skills essential for deploying, managing, and troubleshooting applications in production environments.

---

# Day 04 Summary

Today I learned the fundamentals of Linux, explored different Linux distributions, installed Ubuntu using WSL, and practiced essential Linux commands. These basics provide the foundation for learning shell scripting, server administration, Docker, Kubernetes, and cloud platforms like AWS in the coming days.

**Status:** ✅ Day 04 Completed
