# NAT (Network Address Translation)

## 📚 Introduction

Network Address Translation (NAT) is a technique used by routers to translate private IP addresses into public IP addresses and vice versa. NAT allows multiple devices on a private network to share a single public IP address when accessing the Internet.

NAT helps conserve IPv4 addresses and provides an additional layer of security by hiding internal network addresses from external networks.

---

## 🔑 Why NAT is Important

* Conserves IPv4 addresses
* Allows multiple devices to access the Internet using one public IP address
* Hides internal IP addresses from external networks
* Simplifies network management

---

## 🌐 Public IP vs Private IP

### Public IP Address

A public IP address is globally unique and accessible over the Internet.

Example:

```text
8.8.8.8
```

### Private IP Address

Private IP addresses are used within local networks and are not directly accessible from the Internet.

Examples:

```text
192.168.1.10
10.0.0.5
172.16.1.20
```

---

## 🔄 How NAT Works

1. A device sends a request to the Internet using its private IP address.
2. The router translates the private IP address into a public IP address.
3. The response from the Internet is received by the router.
4. The router translates the public IP back to the private IP address and forwards the data to the correct device.

---

## 📌 Types of NAT

### Static NAT

Maps one private IP address to one public IP address.

Example:

```text
192.168.1.10 → 203.0.113.5
```

---

### Dynamic NAT

Uses a pool of public IP addresses and assigns them dynamically.

---

### PAT (Port Address Translation)

Also known as NAT Overload.

Multiple devices share a single public IP address using different port numbers.

This is the most commonly used type of NAT in home networks.

---

## 🛡 Advantages of NAT

* Efficient use of IPv4 addresses
* Improved security
* Reduced need for multiple public IP addresses
* Supports communication between private and public networks

---

## 🔑 Key Takeaways

* NAT stands for Network Address Translation.
* NAT translates private IP addresses into public IP addresses.
* It helps conserve IPv4 addresses.
* PAT is the most commonly used form of NAT.
* NAT enables multiple devices to share a single public IP address.

---

## 🎯 Next Goal

Learn ARP (Address Resolution Protocol) and understand how IP addresses are mapped to MAC addresses.
