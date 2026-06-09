# Linux File Permissions

## 📚 Introduction

Linux file permissions determine who can access files and directories and what actions they are allowed to perform.

Permissions play an important role in system security and help prevent unauthorized access.

---

## 🔑 Permission Types

Linux defines three basic permissions:

### Read (r)

Allows viewing the contents of a file.

Value:

```text
4
```

---

### Write (w)

Allows modifying the contents of a file.

Value:

```text
2
```

---

### Execute (x)

Allows executing a file or entering a directory.

Value:

```text
1
```

---

## 👥 Permission Categories

Permissions are assigned to:

* User (Owner)
* Group
* Others

Example:

```text
-rwxr-xr--
```

Meaning:

* User: rwx
* Group: r-x
* Others: r--

---

## 🛠 chmod Command

Used to change file permissions.

Example:

```bash
chmod 755 file.txt
```

Permission breakdown:

* User = 7 (rwx)
* Group = 5 (r-x)
* Others = 5 (r-x)

---

## 🛠 chown Command

Used to change file ownership.

Example:

```bash
chown user file.txt
```

---

## 🔐 Importance of Permissions

Linux permissions help:

* Protect sensitive files
* Prevent unauthorized access
* Maintain system integrity
* Enhance security

---

## 🔑 Key Takeaways

* Linux permissions control file access.
* Three permissions exist: read, write and execute.
* Permissions apply to users, groups and others.
* chmod changes permissions.
* chown changes ownership.

---

## 🎯 Next Goal

Learn Process Management and understand how Linux manages running processes.
