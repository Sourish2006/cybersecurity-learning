# Linux Basic Commands

## 📚 Introduction

Linux is a powerful and widely used operating system in cybersecurity, system administration, cloud computing, and software development.

Most interactions with Linux are performed through the Command Line Interface (CLI), which allows users to efficiently manage files, directories, and system resources.

Understanding basic Linux commands is essential for anyone pursuing cybersecurity or working with Linux systems.

---

## 📂 pwd

The `pwd` command displays the current working directory.

### Example

```bash
pwd
```

### Output

```text
/home/user/Documents
```

---

## 📁 ls

The `ls` command lists files and directories.

### Example

```bash
ls
```

### Common Options

```bash
ls -l
ls -a
```

* `-l` displays detailed information.
* `-a` shows hidden files.

---

## 📂 cd

The `cd` command is used to change directories.

### Example

```bash
cd Documents
```

Move to the parent directory:

```bash
cd ..
```

Go to the home directory:

```bash
cd ~
```

---

## 📁 mkdir

The `mkdir` command creates a new directory.

### Example

```bash
mkdir test
```

---

## 📄 touch

The `touch` command creates an empty file.

### Example

```bash
touch file.txt
```

---

## 📋 cp

The `cp` command copies files and directories.

### Example

```bash
cp file.txt backup.txt
```

---

## ✏ mv

The `mv` command moves or renames files.

### Example

```bash
mv file.txt newfile.txt
```

---

## 🗑 rm

The `rm` command removes files and directories.

### Example

```bash
rm file.txt
```

Remove directories recursively:

```bash
rm -r folder_name
```

---

## 🔑 Key Takeaways

* Linux commands are executed through the command line interface.
* Basic commands are essential for file and directory management.
* Mastering Linux commands is fundamental for cybersecurity professionals.
* CLI provides greater control and efficiency compared to graphical interfaces.

---

## 🎯 Next Goal

Learn Linux File System and Directory Structure.
