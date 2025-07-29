# 🛡️ Day 4 - Cybersecurity Notes

## 📌 Topics Covered
1. **Network**
2. **Subnet**
3. **TCP vs UDP**
4. **IP Address**
5. **Payloads and Backdoors**

---

## 🌐 Network
- A **network** is a collection of devices (computers, servers, routers, etc.) connected together to share resources and data.
- Communication occurs through **protocols** such as TCP/IP.
- Types of Networks:
  - **LAN** (Local Area Network) – Small area (e.g., home, office).
  - **WAN** (Wide Area Network) – Large geographical areas (e.g., Internet).
  - **MAN** (Metropolitan Area Network) – Covers a city or region.

---

## 🧩 Subnet
- **Subnet** (Subnetwork) is a logical subdivision of an IP network.
- Helps:
  - Organize networks efficiently.
  - Improve security by isolating parts of a network.
  - Reduce network congestion.
- Identified using a **Subnet Mask** (e.g., `255.255.255.0`).
- Example:  
  - IP: `192.168.1.25`
  - Subnet Mask: `255.255.255.0`
  - Network Address: `192.168.1.0`

---

## 🔄 TCP vs UDP

| Feature           | **TCP (Transmission Control Protocol)** | **UDP (User Datagram Protocol)** |
|-------------------|-----------------------------------------|-----------------------------------|
| **Connection**    | Connection-oriented                     | Connectionless                   |
| **Reliability**   | Reliable (data is acknowledged & re-sent if lost) | Unreliable (no retransmission)    |
| **Speed**         | Slower (due to error-checking & confirmation) | Faster (less overhead)            |
| **Use Cases**     | Web browsing, Email, File Transfer      | Online gaming, Video streaming, VoIP |
| **Example Ports** | HTTP (80), HTTPS (443)                   | DNS (53), TFTP (69)               |

---

## 📍 IP Address
- **IP Address**: Unique identifier for a device on a network.
- Types:
  - **IPv4**: 32-bit (e.g., `192.168.0.1`).
  - **IPv6**: 128-bit (e.g., `2001:0db8::1`).
- Can be:
  - **Public IP** – Identifies device on the Internet.
  - **Private IP** – Used inside local networks.

---

## 🚀 Payload & Backdoor
- **Payload**:  
  - In cybersecurity, it refers to the part of malware that performs the malicious action.
  - Example: Data theft, remote access, ransomware.
- **Backdoor**:  
  - A method to bypass normal authentication and gain unauthorized access to a system.
- **Analogy**:  
  - Payload = Shuttle delivering the malicious tool.
  - Backdoor = Hidden entrance into the system.
- **Kali Linux in Payload Delivery**:
  - To control a target device, the attacker embeds **their Kali Linux IP address** into the payload.
  - This ensures that once the payload runs, the compromised device connects back to the attacker’s Kali machine.

---

## ⚠️ Important
- These techniques are taught for **educational purposes only**.
- Unauthorized use is **illegal** and can result in severe consequences.

---
