# 🛰️ Task 5 - Wireshark Packet Analysis

## 🎯 Objective
To capture live network traffic using **Wireshark** and identify different network protocols using filtering techniques. This task improves hands-on skills in protocol analysis and network troubleshooting.

---

## 🛠️ Tools Used

- **Wireshark** (Packet Analyzer)
- **Operating System:** Kali Linux
- **Traffic Generation Commands:**
  - `ping google.com` (ICMP)
  - `curl example.com` (HTTP)
  - `nslookup google.com` (DNS)

---

## 📦 Protocols Identified

### 1️⃣ DNS (Domain Name System)
- **Purpose:** Resolves domain names into IP addresses.
- **Captured Using:** `nslookup google.com`
- **Observed:** DNS Query/Response packets (A, AAAA records).

---

### 2️⃣ HTTP (HyperText Transfer Protocol)
- **Purpose:** Transfers web data between client and server.
- **Captured Using:** `curl example.com`
- **Observed:** HTTP GET request to fetch web page content.

---

### 3️⃣ ARP (Address Resolution Protocol)
- **Purpose:** Resolves IP addresses to MAC addresses in LAN.
- **Captured Automatically:** When traffic flows in LAN.
- **Observed:** ARP Requests & Replies.

---


## 👨‍💻 Submitted by:
**Zeel**  
Task 5 - wireshark (elevate labs)

