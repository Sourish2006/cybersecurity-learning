# Linux File System and Directory Structure

## 📚 Introduction

The Linux file system organizes files and directories in a hierarchical structure. Everything in Linux is represented as a file, including hardware devices and processes.

The root directory (`/`) is the top-level directory from which all other directories originate.

---

## 🌳 Root Directory (/)

The root directory is the starting point of the Linux file system.

Example:

```text
/
```

All files and directories are organized under this root directory.

---

## 📂 Important Directories

### /home

Contains personal files and directories of users.

Example:

```text
/home/user
```

---

### /bin

Contains essential user commands and executable files.

Examples:

* ls
* cp
* mv
* cat

---

### /etc

Stores system configuration files.

Examples:

* passwd
* hosts
* ssh configuration files

---

### /var

Contains variable data such as:

* Log files
* Mail files
* Cache files

Example:

```text
/var/log
```

---

### /tmp

Stores temporary files created by applications and users.

---

### /usr

Contains installed applications and user utilities.

---

### /dev

Contains device files representing hardware devices.

Examples:

* Hard disks
* USB devices
* Printers

---

## 📌 Absolute Path vs Relative Path

### Absolute Path

Starts from the root directory.

Example:

```text
/home/user/Documents
```

### Relative Path

Specified relative to the current directory.

Example:

```text
Documents
```

---

## 🔑 Key Takeaways

* Linux follows a hierarchical file system structure.
* The root directory (`/`) is the top-level directory.
* Directories such as `/home`, `/etc`, and `/var` have specific purposes.
* Understanding the file system is essential for Linux administration and cybersecurity.

---

## 🎯 Next Goal

Learn Linux Permissions and understand file ownership and access control.
