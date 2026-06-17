# Linux Networking Commands

## 📚 Introduction

Linux provides various networking commands that help users monitor, troubleshoot and manage network connections.

These commands are essential for system administrators and cybersecurity professionals.

---

## 📡 ping

The `ping` command is used to test connectivity between systems.

Example:

```bash
ping google.com
```

Purpose:

* Check network connectivity
* Measure response time

---

## 🌐 ip

The `ip` command displays and manages network interfaces.

Example:

```bash
ip addr
```

Purpose:

* View IP addresses
* Manage interfaces
* Display routing information

---

## 🖥 hostname

Displays the hostname of the system.

Example:

```bash
hostname
```

---

## 📋 netstat

Displays network connections and listening ports.

Example:

```bash
netstat -tuln
```

Purpose:

* View active connections
* Display open ports

---

## 📊 ss

A modern replacement for netstat.

Example:

```bash
ss -tuln
```

Purpose:

* Show socket statistics
* Display listening services

---

## 🛣 traceroute

Displays the path packets take to reach a destination.

Example:

```bash
traceroute google.com
```

Purpose:

* Diagnose routing problems
* Analyze packet paths

---

## 🔍 nslookup

Queries DNS servers for domain information.

Example:

```bash
nslookup google.com
```

---

## 🌎 dig

Provides detailed DNS information.

Example:

```bash
dig google.com
```

---

## 🔑 Key Takeaways

* Linux networking commands help diagnose connectivity issues.
* `ping` tests communication between systems.
* `ip` displays interface information.
* `netstat` and `ss` show network connections.
* `nslookup` and `dig` are useful for DNS analysis.

---

## 🎯 Next Goal

Learn Linux Package Management and understand how software is installed and updated.
