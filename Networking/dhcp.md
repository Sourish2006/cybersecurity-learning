# Day 8 - DHCP (Dynamic Host Configuration Protocol)

## 📚 Introduction

DHCP (Dynamic Host Configuration Protocol) is a network protocol that automatically assigns IP addresses and other network configuration information to devices connected to a network.

Without DHCP, IP addresses must be configured manually, which is time-consuming and prone to errors.

---

## 🔑 Purpose of DHCP

DHCP automatically provides:

* IP Address
* Subnet Mask
* Default Gateway
* DNS Server Address

This allows devices to communicate with other devices and access the Internet.

---

## 🖥 Example

When a laptop connects to a Wi-Fi network, it automatically receives:

* IP Address: 192.168.1.10
* Subnet Mask: 255.255.255.0
* Default Gateway: 192.168.1.1
* DNS Server: 8.8.8.8

These values are assigned by the DHCP server.

---

## 🔄 DHCP DORA Process

DHCP works using four steps known as the DORA process.

### 1. Discover

The client broadcasts a DHCP Discover message to find available DHCP servers.

### 2. Offer

The DHCP server responds with a DHCP Offer containing an available IP address.

### 3. Request

The client requests the offered IP address.

### 4. Acknowledge

The server confirms the request and assigns the IP address.

---

## 📌 DHCP Ports

DHCP uses UDP protocol.

| Device | Port   |
| ------ | ------ |
| Client | UDP 68 |
| Server | UDP 67 |

---

## ✅ Advantages of DHCP

* Automatic IP address assignment
* Reduces configuration errors
* Simplifies network management
* Efficient use of IP addresses

---

## ⚠ Without DHCP

Without DHCP, administrators must manually configure:

* IP Address
* Subnet Mask
* Gateway
* DNS Server

for every device in the network.

---

## 🔑 Key Takeaways

* DHCP stands for Dynamic Host Configuration Protocol.
* It automatically assigns IP addresses to devices.
* DHCP uses the DORA process:

  * Discover
  * Offer
  * Request
  * Acknowledge
* DHCP uses UDP ports 67 and 68.

---

## 🎯 Next Goal

Learn about NAT (Network Address Translation).
