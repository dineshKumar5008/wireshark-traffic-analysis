# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## Objective
The objective of this task is to capture live network traffic and analyze different network protocols using Wireshark in order to understand how data is transmitted over a network.

---

## Tool Used
- Wireshark (Free and Open-Source Network Protocol Analyzer)

---

## Environment Details
- Operating System: Kali Linux
- Network Interface: eth0
- Capture Type: Live network capture
- Capture Duration: Approximately 1 minute

---

## Traffic Generation
Network traffic was generated using the following methods:
- ICMP ping request to `google.com`
- Background system and network communication

---

## Protocols Identified

### 1. ICMP (Internet Control Message Protocol)
- Observed during `ping google.com`
- Echo Request and Echo Reply packets were captured
- Used to test network connectivity between host and destination

### 2. DNS (Domain Name System)
- DNS query packets were captured
- Responsible for resolving domain names (google.com) into IP addresses
- Observed as UDP-based DNS query traffic

### 3. ARP (Address Resolution Protocol)
- ARP packets were captured in the local network
- Used to map IP addresses to MAC addresses

### 4. ICMPv6 (Optional Observation)
- ICMPv6 packets were observed
- Used for IPv6 network control and diagnostics

---

## Packet Analysis Observations
- DNS queries occur before communication with external servers
- ICMP packets confirm successful network reachability
- ARP traffic facilitates local network communication
- Multiple protocols work together for a single network request

---

## Capture File
- File Name: `task5_network_capture.pcap`
- Format: `.pcap / .pcapng`
- Contains live captured packets for analysis

---

## Conclusion
This task provided hands-on experience in capturing and analyzing real-time network traffic using Wireshark. It helped in understanding packet structure, protocol behavior, and how different network protocols interact during normal network communication.

---

## Key Concepts Learned
- Packet capture
- Protocol analysis
- ICMP, DNS, ARP
- TCP/IP fundamentals
- Network troubleshooting basics
