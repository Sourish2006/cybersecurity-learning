# Linux Package Management

## 📚 Introduction

Package management is the process of installing, updating, removing and maintaining software packages in Linux systems.

Package managers automate software management and help ensure that applications and their dependencies are properly installed.

---

## 🔑 Why Package Management is Important

Package management helps:

* Install software easily
* Update applications
* Remove unwanted programs
* Manage dependencies
* Improve system security

---

## 📦 APT (Advanced Package Tool)

APT is commonly used in Debian-based distributions such as:

* Ubuntu
* Kali Linux
* Debian

---

### Update Package Lists

```bash
sudo apt update
```

Updates information about available packages.

---

### Upgrade Installed Packages

```bash
sudo apt upgrade
```

Installs the latest versions of installed software.

---

### Install a Package

```bash
sudo apt install package_name
```

Example:

```bash
sudo apt install nmap
```

---

### Remove a Package

```bash
sudo apt remove package_name
```

---

## 📦 YUM and DNF

Used in Red Hat-based distributions.

Examples:

* CentOS
* Fedora
* RHEL

Install a package:

```bash
sudo dnf install package_name
```

---

## 🔍 Search for Packages

```bash
apt search package_name
```

Example:

```bash
apt search wireshark
```

---

## 🌐 Real-World Applications

Package management is used in:

* System Administration
* Server Management
* Software Deployment
* Cybersecurity Labs

---

## 🔑 Key Takeaways

* Package managers simplify software installation.
* APT is used in Debian-based systems.
* DNF and YUM are used in Red Hat-based systems.
* Package management helps maintain system security.
* Dependencies are handled automatically.

---

## 🎯 Next Goal

Learn Environment Variables and understand how Linux stores configuration information.
