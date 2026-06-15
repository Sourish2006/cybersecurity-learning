# Linux Users and Groups

## 📚 Introduction

Linux is a multi-user operating system that allows multiple users to access and share system resources. Users and groups help manage permissions and control access to files and directories.

Understanding users and groups is essential for Linux administration and cybersecurity.

---

## 👤 Users

A user account represents an individual who can log into the system and access resources.

Examples:

* root
* admin
* user1

Each user has a unique User ID (UID).

---

## 👥 Groups

Groups are collections of users that share common permissions.

Examples:

* sudo
* developers
* users

Each group has a unique Group ID (GID).

---

## 📂 Important Files

### /etc/passwd

Stores information about user accounts.

Example:

```text
/etc/passwd
```

This file contains:

* Username
* UID
* GID
* Home directory
* Login shell

---

### /etc/group

Stores information about groups.

Example:

```text
/etc/group
```

---

## 🔑 Types of Groups

### Primary Group

The default group assigned to a user.

### Secondary Group

Additional groups that provide extra permissions.

---

## 🛠 Common Commands

### Create a User

```bash
useradd username
```

---

### Set a Password

```bash
passwd username
```

---

### Create a Group

```bash
groupadd groupname
```

---

### Add a User to a Group

```bash
usermod -aG groupname username
```

---

### View Current User

```bash
whoami
```

---

### Display User ID and Group ID

```bash
id
```

---

## 🛡 Importance of Users and Groups

Users and groups help:

* Control access to resources
* Improve system security
* Simplify administration
* Manage permissions efficiently

---

## 🌐 Real-World Applications

Users and groups are used in:

* System Administration
* Server Management
* Multi-user Environments
* Cybersecurity
* Access Control

---

## 🔑 Key Takeaways

* Linux supports multiple users.
* Groups simplify permission management.
* `/etc/passwd` stores user information.
* `/etc/group` stores group information.
* Users and groups are fundamental to Linux security.

---

## 🎯 Next Goal

Learn Linux Networking Commands and understand how to troubleshoot network connectivity.
