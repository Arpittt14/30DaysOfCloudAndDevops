# Day 06 - Mastering Advanced Linux Commands

## Objective

To learn advanced Linux commands for file management, process monitoring, system administration, networking, and productivity. These commands are essential for managing Linux servers in Cloud Computing and DevOps environments.

---

# Advanced File & Directory Management

Linux provides powerful commands to create, move, copy, delete, and organize files efficiently.

### Search for Files

```bash
find /path -name "filename"
```

Example:

```bash
find . -name "*.txt"
```

Searches for all `.txt` files in the current directory and its subdirectories.

---

# Searching File Content

The `grep` command searches for specific words or patterns inside files.

```bash
grep "keyword" filename
```

Example:

```bash
grep "error" logs.txt
```

Useful for:

* Searching log files
* Finding configuration values
* Debugging applications

---

# Viewing Running Processes

Every running program in Linux is represented as a process.

### Display Running Processes

```bash
ps
```

Shows currently running processes.

### Monitor Processes in Real Time

```bash
top
```

Displays:

* CPU Usage
* Memory Usage
* Running Processes
* System Load

---

# File Permissions

Linux uses permissions to control who can read, write, or execute files.

### Change Permissions

```bash
chmod 755 filename
```

Common permission values:

| Permission | Meaning                                            |
| ---------- | -------------------------------------------------- |
| 777        | Full access for everyone                           |
| 755        | Owner has full access, others can read and execute |
| 644        | Owner can read/write, others can only read         |

> **Note:** Avoid using `777` unless absolutely necessary, as it grants unrestricted access.

---

# File Ownership

Every file belongs to a user and a group.

### Change Owner

```bash
sudo chown username filename
```

Example:

```bash
sudo chown arpit notes.txt
```

---

# Disk Usage

### Check Disk Space

```bash
df -h
```

Displays:

* Total disk space
* Used space
* Available space
* Mounted file systems

### Check Directory Size

```bash
du -sh folder-name
```

Displays the total size of a directory in a human-readable format.

---

# Viewing File Contents

### Display First Lines

```bash
head filename
```

### Display Last Lines

```bash
tail filename
```

These commands are especially useful for reading large log files.

---

# Command History

```bash
history
```

Shows previously executed commands, making it easy to repeat or review past work.

---

# Downloading Files

### Using wget

```bash
wget https://example.com/file.zip
```

Downloads files directly from the internet.

### Using curl

```bash
curl https://example.com
```

Common uses:

* Downloading files
* Testing APIs
* Sending HTTP requests
* Troubleshooting web services

---

# Network Connectivity

### Test Network Connection

```bash
ping google.com
```

Displays:

* Connectivity status
* Response time
* Packet loss

Useful for checking whether a server is reachable.

---

# Command Chaining

Linux allows multiple commands to be executed in a single line.

### Execute Sequentially

```bash
mkdir project && cd project
```

The second command runs only if the first command succeeds.

Benefits:

* Faster workflow
* Better automation
* Cleaner shell scripts

---

# Commands Practiced Today

```bash
find
grep
ps
top
chmod
chown
df -h
du -sh
head
tail
history
wget
curl
ping
```

---

# Hands-On Practice

* Searched files using `find`
* Searched text using `grep`
* Viewed running processes with `ps`
* Monitored system performance using `top`
* Changed file permissions using `chmod`
* Changed ownership using `chown`
* Checked disk usage
* Measured directory size
* Viewed file contents with `head` and `tail`
* Reviewed command history
* Downloaded files using `wget` and `curl`
* Tested network connectivity using `ping`

---

# Key Learnings

* Linux provides powerful tools for managing files and directories.
* File permissions and ownership help secure the operating system.
* System monitoring commands help identify performance issues.
* Network utilities are essential for troubleshooting servers.
* Command chaining increases productivity and simplifies repetitive tasks.

---

# Why This Matters for Cloud & DevOps

Cloud and DevOps engineers spend much of their time working in Linux terminals.

These commands are essential for:

* Managing cloud servers
* Monitoring applications
* Debugging production issues
* Configuring permissions
* Checking storage usage
* Automating administrative tasks
* Troubleshooting network connectivity

---

# Interview Questions

1. What is the difference between `find` and `grep`?
2. What does the `top` command display?
3. What is the purpose of `chmod`?
4. How is `chown` different from `chmod`?
5. What is the difference between `df -h` and `du -sh`?
6. When would you use `head` and `tail`?
7. What is the difference between `wget` and `curl`?
8. Why is the `ping` command useful?

---

# Day 06 Summary

Today I explored advanced Linux commands that are commonly used in system administration and DevOps. I learned how to search files, monitor processes, manage permissions, analyze disk usage, test network connectivity, and improve productivity using command chaining. These skills are essential for managing Linux-based cloud infrastructure efficiently.

**Status:** ✅ Day 06 Completed
