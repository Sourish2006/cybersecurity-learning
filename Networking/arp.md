# ARP (Address Resolution Protocol)

## 📚 Introduction

Address Resolution Protocol (ARP) is a network protocol used to map an IP address to a MAC address within a local area network (LAN).

Since devices communicate using MAC addresses at the Data Link Layer, ARP helps determine the MAC address associated with a specific IP address.

---

## 🔑 Why ARP is Needed

When a device wants to send data to another device on the same network, it knows the destination IP address but not the destination MAC address.

ARP resolves this problem by finding the corresponding MAC address.

---

## 🔄 How ARP Works

Suppose Host A wants to communicate with Host B.

### Step 1: ARP Request

Host A broadcasts an ARP request:

```text
Who has IP address 192.168.1.20?
Tell 192.168.1.10
```

---

### Step 2: ARP Reply

Host B responds with its MAC address:

```text
192.168.1.20 is at AA:BB:CC:DD:EE:FF
```

---

### Step 3: Data Transmission

Host A stores the MAC address and begins sending data frames to Host B.

---

## 🗂 ARP Cache

Devices maintain an ARP cache that stores recently resolved IP-to-MAC mappings.

This reduces the need for repeated ARP requests and improves network efficiency.

---

## 🌐 Example

| Device | IP Address   | MAC Address       |
| ------ | ------------ | ----------------- |
| Host A | 192.168.1.10 | 11:22:33:44:55:66 |
| Host B | 192.168.1.20 | AA:BB:CC:DD:EE:FF |

ARP allows Host A to discover Host B's MAC address before communication begins.

---

## 📌 Characteristics of ARP

* Operates within a LAN.
* Maps IP addresses to MAC addresses.
* Uses broadcast requests.
* Uses unicast replies.
* Works between Layer 2 and Layer 3.

---

## ✅ Advantages

* Enables communication within local networks.
* Automatically resolves MAC addresses.
* Improves network efficiency through ARP caching.

---

## 🔑 Key Takeaways

* ARP stands for Address Resolution Protocol.
* ARP maps IP addresses to MAC addresses.
* ARP requests are broadcast.
* ARP replies are unicast.
* ARP is essential for communication within a LAN.

---

## 🎯 Next Goal

Learn ICMP (Internet Control Message Protocol) and understand how Ping works.
