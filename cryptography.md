# Cryptography Concepts

## 📚 Introduction

Cryptography is the practice of securing information and communication by converting readable data into an unreadable form. It helps protect sensitive information from unauthorized access and ensures confidentiality, integrity, and authenticity of data.

---

## 🔤 Plaintext and Ciphertext

* **Plaintext** is the original readable message or data.
* **Ciphertext** is the encrypted form of the plaintext that cannot be understood without decryption.

Example:

Plaintext:

```
HELLO
```

Ciphertext:

```
XJH92L
```

---

## 🔐 Encryption and Decryption

### Encryption

Encryption is the process of converting plaintext into ciphertext using an algorithm and a key.

### Decryption

Decryption is the process of converting ciphertext back into plaintext using the appropriate key.

---

## 🔑 Symmetric Encryption

Symmetric encryption uses the same key for both encryption and decryption.

### Characteristics

* Fast and efficient.
* Suitable for encrypting large amounts of data.
* Requires secure key sharing.

### Examples

* AES (Advanced Encryption Standard)
* DES (Data Encryption Standard)

---

## 🔑 Asymmetric Encryption

Asymmetric encryption uses two different keys:

* Public Key
* Private Key

Data encrypted with the public key can only be decrypted using the private key.

### Characteristics

* More secure for communication.
* Used in digital signatures and secure connections.

### Examples

* RSA
* ECC (Elliptic Curve Cryptography)

---

## #️⃣ Hashing

Hashing converts data into a fixed-length value called a hash.

### Features

* One-way process.
* Cannot be reversed.
* Used to verify data integrity.

### Examples

* SHA-256
* SHA-1
* MD5

### Applications

* Password storage
* File integrity verification
* Digital signatures

---

## ✍️ Digital Signatures

Digital signatures are used to verify the authenticity and integrity of data.

### Benefits

* Authentication
* Integrity
* Non-repudiation

Digital signatures commonly use asymmetric cryptography.

---

## 🛡 Importance of Cryptography

Cryptography helps achieve:

1. Confidentiality
2. Integrity
3. Authentication
4. Non-repudiation

These principles are essential for secure communication and cybersecurity.

---

## 🔑 Key Takeaways

* Encryption protects confidentiality.
* Hashing ensures data integrity.
* Symmetric encryption uses a single key.
* Asymmetric encryption uses public and private keys.
* Digital signatures verify authenticity and integrity.

---

## 🎯 Next Goal

* Learn SSL/TLS
* Understand Public Key Infrastructure (PKI)
* Explore Certificates and HTTPS
* Study Caesar Cipher and Modern Encryption Algorithms
