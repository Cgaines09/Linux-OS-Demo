# Linux Operating System Fundamentals

## Overview

This project documents my hands-on experience learning Linux Operating System fundamentals. The training focused on navigating the Linux filesystem, managing files and directories, working with users and permissions, utilizing common command-line tools, and understanding core operating system concepts used in cybersecurity, system administration, and cloud environments.

Linux is one of the most widely used operating systems in enterprise environments, servers, cloud platforms, cybersecurity labs, and penetration testing distributions such as Kali Linux and Parrot OS.

---

# Learning Objectives

* Understand Linux operating system architecture
* Navigate the Linux filesystem
* Manage files and directories
* Work with users and groups
* Understand Linux permissions
* Utilize common Linux commands
* Search and manipulate data
* Monitor system processes
* Manage services and packages
* Apply Linux skills to cybersecurity environments

---

# Linux Filesystem Structure

Linux organizes files using a hierarchical directory structure.

## Common Directories

| Directory | Purpose                     |
| --------- | --------------------------- |
| `/`       | Root directory              |
| `/home`   | User home directories       |
| `/root`   | Root user home directory    |
| `/etc`    | Configuration files         |
| `/var`    | Variable data and logs      |
| `/tmp`    | Temporary files             |
| `/bin`    | Essential user binaries     |
| `/usr`    | User programs and utilities |
| `/opt`    | Optional software packages  |

---

# Navigation Commands

## Display Current Directory

```bash
pwd
```

## List Files and Directories

```bash
ls
```

Detailed listing:

```bash
ls -la
```

## Change Directory

```bash
cd /home/user
```

Return to home directory:

```bash
cd ~
```

---

# File Management

## Create Files

```bash
touch notes.txt
```

## Create Directories

```bash
mkdir projects
```

## Copy Files

```bash
cp file.txt backup.txt
```

## Move or Rename Files

```bash
mv oldfile.txt newfile.txt
```

## Delete Files

```bash
rm file.txt
```

## Delete Directories

```bash
rm -r directory
```

---

# Viewing File Contents

## Display File Contents

```bash
cat file.txt
```

## Read Large Files

```bash
less file.txt
```

## Display Beginning of File

```bash
head file.txt
```

## Display End of File

```bash
tail file.txt
```

---

# User and Group Management

## Display Current User

```bash
whoami
```

## View User Information

```bash
id
```

## Add User

```bash
sudo useradd username
```

## Change Password

```bash
passwd username
```

## View Groups

```bash
groups
```

---

# Linux Permissions

Permissions control access to files and directories.

Example:

```bash
-rwxr-xr--
```

Permission Breakdown:

| Symbol | Meaning |
| ------ | ------- |
| r      | Read    |
| w      | Write   |
| x      | Execute |

## Change Permissions

```bash
chmod 755 script.sh
```

## Change Ownership

```bash
chown user:user file.txt
```

---

# Searching for Files

## Find Files

```bash
find /home -name report.txt
```

## Locate Files

```bash
locate report.txt
```

---

# Text Processing

## Search Text

```bash
grep "password" file.txt
```

## Count Lines

```bash
wc -l file.txt
```

## Sort Data

```bash
sort file.txt
```

## Remove Duplicate Entries

```bash
uniq file.txt
```

---

# Process Management

## View Running Processes

```bash
ps aux
```

## Real-Time Process Monitoring

```bash
top
```

## Kill Process

```bash
kill PID
```

Force kill:

```bash
kill -9 PID
```

---

# Networking Commands

## View IP Address

```bash
ip addr
```

## Display Network Configuration

```bash
ifconfig
```

## Test Connectivity

```bash
ping google.com
```

## View Open Connections

```bash
ss -tulnp
```

---

# Package Management

## Debian / Ubuntu

Update repositories:

```bash
sudo apt update
```

Install packages:

```bash
sudo apt install package-name
```

Remove packages:

```bash
sudo apt remove package-name
```

---

# System Information

## View System Information

```bash
uname -a
```

## Check Disk Usage

```bash
df -h
```

## Check Directory Size

```bash
du -sh directory/
```

## View Memory Usage

```bash
free -h
```

---

# Shell Redirection and Pipelines

## Redirect Output

```bash
ls > output.txt
```

## Append Output

```bash
echo "Hello" >> output.txt
```

## Pipe Commands

```bash
cat file.txt | grep admin
```

---

# Cybersecurity Applications

Linux skills are essential for:

* Penetration Testing
* Incident Response
* Digital Forensics
* Security Operations (SOC)
* Cloud Security
* Network Administration
* Server Management
* Automation and Scripting

Common cybersecurity tools include:

* Nmap
* Wireshark
* Metasploit
* Burp Suite
* tcpdump
* Hydra
* John the Ripper

---

# Skills Demonstrated

* Linux command-line navigation
* File and directory management
* User and group administration
* Permission management
* Process monitoring
* Network troubleshooting
* Package management
* Text processing
* System administration fundamentals
* Cybersecurity-focused Linux operations

---

# Technologies Used

* Linux
* Bash Shell
* Ubuntu
* Debian
* Kali Linux
* Parrot OS
* Command Line Interface (CLI)

---

# Key Takeaways

Linux is the backbone of modern servers, cloud environments, cybersecurity platforms, and enterprise infrastructure. Developing strong Linux skills provides a foundation for system administration, cloud computing, cybersecurity, automation, and software development.

This project demonstrates practical Linux knowledge that can be applied in real-world environments to manage systems, troubleshoot issues, automate tasks, and secure infrastructure.

---

## Author

Created as part of Linux Operating System and cybersecurity training focused on developing practical command-line and system administration skills.
