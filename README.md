# 🦈 Task 5 – Network Traffic Capture & Analysis using Wireshark

> “If you can see the packets, you can understand the network.”

---

## 🎯 Objective
Capture live network traffic and analyze different protocols to understand how data flows across a network in real time.

This task focuses on **packet capture, protocol identification, and basic traffic analysis** using Wireshark.

---

## 🛠️ Tool Used
- **Wireshark** (Free & Open-Source Network Protocol Analyzer)

---

## ⚡ Environment
- OS: Kali Linux
- Network Interface: eth0
- Capture Type: Live packet capture

---

## 🚀 What I Did
- Started live packet capture on the active network interface
- Generated traffic using:
  - `ping google.com`
  - Web requests
- Applied protocol-based filters
- Analyzed packet-level details
- Exported the capture as a `.pcap` file
- Documented findings clearly

---

## 📡 Protocols Identified

### 🔹 ICMP (Internet Control Message Protocol)
- Observed during `ping google.com`
- Echo Request and Echo Reply packets captured
- Used for network connectivity testing

### 🔹 DNS (Domain Name System)
- DNS query packets captured
- Translates domain names (google.com) into IP addresses

### 🔹 TCP (Transmission Control Protocol)
- Reliable, connection-oriented protocol
- Observed during background and web traffic

### 🔹 ARP (Address Resolution Protocol)
- Maps IP addresses to MAC addresses
- Local network communication observed

---

## 🔍 Key Observations
- DNS queries occur before accessing any website
- ICMP packets confirm network reachability
- Multiple protocols work together for a single network request
- Even simple actions generate multiple packets

---

## 📁 Repository Structure

│
├──  task5_network_capture.pcap
├── report.md
└── README.md
