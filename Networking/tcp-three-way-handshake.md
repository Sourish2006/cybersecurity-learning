# TCP Three-Way Handshake

## 📚 Introduction

TCP (Transmission Control Protocol) is a connection-oriented protocol. Before data transmission begins, TCP establishes a reliable connection between two devices using a process known as the Three-Way Handshake.

This mechanism ensures that both devices are ready to communicate.

---

## 🔑 Purpose of the Three-Way Handshake

The TCP handshake helps:

* Establish a connection
* Synchronize sequence numbers
* Ensure reliable communication
* Confirm that both devices are ready for data transfer

---

## 🔄 Steps of the Three-Way Handshake

### Step 1: SYN

The client sends a SYN (Synchronize) packet to the server to initiate communication.

```text
Client -------- SYN --------> Server
```

---

### Step 2: SYN-ACK

The server responds with a SYN-ACK packet.

```text
Client <----- SYN-ACK ------- Server
```

This indicates that the server received the request and is ready to communicate.

---

### Step 3: ACK

The client sends an ACK packet to acknowledge the server's response.

```text
Client -------- ACK --------> Server
```

At this point, the connection is established and data transfer can begin.

---

## 🌐 Real-World Example

When a web browser connects to a website, TCP first performs the three-way handshake before transferring data.

Examples:

* HTTP
* HTTPS
* FTP
* SSH

---

## 🛡 Advantages

* Reliable communication
* Error detection
* Sequence number synchronization
* Connection establishment confirmation

---

## 🔑 Key Takeaways

* TCP uses a three-way handshake to establish connections.
* The process involves SYN, SYN-ACK and ACK packets.
* TCP provides reliable communication.
* Data transfer begins only after the connection is established.

---


