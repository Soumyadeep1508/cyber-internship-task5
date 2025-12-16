# cyber-internship-task5
Capture live network traffic and identify at least 3 protocols using Wireshark.
# 🌐 Task 5 — Capture and Analyze Network Traffic Using Wireshark
**Elevate Labs — Cyber Security Internship**

---

## 📌 Objective
Capture live network packets using Wireshark and analyze basic network protocols to understand how data flows across a network.

---

## 🛠 Tools Used
- **Wireshark (Free)**
- Windows 10
- Active Network Interface: Wi-Fi

---

## 🚀 Steps Performed

1. Installed Wireshark along with Npcap.
2. Started packet capture on the active Wi-Fi interface.
3. Generated network traffic by:
   - Browsing multiple websites
   - Performing DNS lookups
   - Sending ICMP ping requests
4. Captured live packets for approximately one minute.
5. Stopped the capture and saved it as a `.pcap` file.
6. Applied protocol filters to analyze different traffic types.
7. Identified and documented multiple network protocols.

---

## 🔍 Protocols Identified

### 1️⃣ DNS (Domain Name System)
**Filter used:**
dns

DNS packets were observed when resolving domain names such as `google.com` and `github.com`.  
These packets translate human-readable domain names into IP addresses.

---

### 2️⃣ TCP (Transmission Control Protocol)
**Filter used:**
tcp

TCP traffic was observed during website browsing.  
It ensures reliable, ordered, and error-checked delivery of data.

---

### 3️⃣ HTTP / TLS
**Filter used:**
http and tls

TLS packets were observed for encrypted web traffic (HTTPS).  
These packets protect data confidentiality during web communication.

---

## 📁 Files Included
├── README.md

├── task5-network-capture.pcap

└── screenshots/

├── dns.png

├── tcp.png

├── http.png

└── tls.png


---

## 🧠 Key Learnings
- How packet capture works in real time
- How to identify protocols using Wireshark filters
- Differences between TCP, DNS, and encrypted HTTPS traffic
- Importance of packet analysis in network troubleshooting and security monitoring

---

## 📝 Conclusion
This task provided hands-on experience with packet capturing and protocol analysis.  
By analyzing real network traffic, I gained practical insight into how different protocols operate within a network and how tools like Wireshark help security professionals monitor and troubleshoot network activity.

