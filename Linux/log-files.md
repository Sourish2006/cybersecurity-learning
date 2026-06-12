# Linux Log Files

## 📚 Introduction

Linux systems maintain log files to record system events, user activities and application messages.

Log files are essential for troubleshooting, monitoring and security analysis.

---

## 🔑 Why Log Files are Important

Log files help:

* Monitor system activity
* Troubleshoot problems
* Detect security incidents
* Analyze application behavior
* Maintain system reliability

---

## 📂 Common Log Locations

### /var/log

Stores most system log files.

Example:

```text
/var/log
```

---

### syslog

Contains general system messages and events.

Example:

```text
/var/log/syslog
```

---

### auth.log

Records authentication events.

Examples:

* User logins
* SSH access attempts
* sudo commands

Location:

```text
/var/log/auth.log
```

---

### kern.log

Contains kernel-related messages.

Location:

```text
/var/log/kern.log
```

---

## 🛠 journalctl Command

Used to view logs managed by systemd.

Example:

```bash
journalctl
```

View recent logs:

```bash
journalctl -n 20
```

---

## 🌐 Real-World Applications

Log files are used in:

* Security monitoring
* Incident response
* Troubleshooting
* System administration
* Malware investigation

---

## 🔑 Key Takeaways

* Log files record system events.
* `/var/log` stores important logs.
* `auth.log` records authentication activities.
* `journalctl` helps view system logs.
* Log analysis is essential in cybersecurity.

---

## 🎯 Next Goal

Learn Linux Users and Groups and understand user management and access control.
