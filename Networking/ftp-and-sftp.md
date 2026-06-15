# FTP and SFTP

## 📚 Introduction

FTP (File Transfer Protocol) and SFTP (SSH File Transfer Protocol) are protocols used to transfer files between systems over a network.

These protocols are widely used for file sharing, backups and remote file management.

---

## 📂 File Transfer Protocol (FTP)

FTP is a standard protocol used to transfer files between a client and a server.

Examples:

* Uploading website files
* Downloading files from servers
* Sharing documents

---

## 🔄 How FTP Works

FTP uses two connections:

### Control Connection

Responsible for sending commands and responses.

Default Port:

```text
21
```

### Data Connection

Used for transferring files.

Default Port:

```text
20
```

---

## ⚠ Limitations of FTP

FTP does not encrypt:

* Usernames
* Passwords
* Data

As a result, attackers may intercept sensitive information.

---

## 🔐 Secure File Transfer Protocol (SFTP)

SFTP provides secure file transfer by using SSH.

Default Port:

```text
22
```

SFTP encrypts:

* Authentication information
* Commands
* File contents

---

## ⚖ FTP vs SFTP

| Feature        | FTP        | SFTP      |
| -------------- | ---------- | --------- |
| Security       | Low        | High      |
| Encryption     | No         | Yes       |
| Port           | 20, 21     | 22        |
| Authentication | Plain Text | Encrypted |
| Protocol       | FTP        | SSH       |

---

## 🌍 Real-World Applications

FTP and SFTP are used in:

* Website administration
* Backup systems
* File sharing
* Server management

---

## 🔑 Key Takeaways

* FTP transfers files without encryption.
* SFTP provides secure file transfer using SSH.
* FTP uses ports 20 and 21.
* SFTP uses port 22.
* SFTP is preferred in modern environments.

---

## 🎯 Next Goal

Learn SSH and understand secure remote access.
