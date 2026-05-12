# Home Networking Lab — Day 3 Progress
## Wireshark Packet Analysis + Network Troubleshooting

## Overview
Day 3 focused on packet analysis, protocol inspection, and real-world network troubleshooting using Wireshark. The objective was to understand how network communication behaves at the packet level and develop practical troubleshooting skills by analyzing live traffic, failed connections, DNS queries, TCP handshakes, and DHCP communication.

This lab simulated real IT support and network troubleshooting workflows commonly used in:
- Help Desk
- IT Support
- System Administration
- Network Administration

---

# Skills Practiced

## Packet Capture & Analysis
- Installed and configured Wireshark
- Captured live network traffic
- Filtered traffic by protocol
- Followed TCP streams
- Inspected packet details and headers

---

## Protocol Analysis
### DNS
- Inspected DNS queries and responses
- Verified successful and failed DNS resolution
- Analyzed domain name lookups

### TCP
- Identified TCP handshakes
- Analyzed SYN, SYN/ACK, and ACK packets
- Observed retransmissions and failed connections

### UDP
- Inspected connectionless UDP traffic
- Compared UDP behavior to TCP

### DHCP
- Captured DHCP lease assignment traffic
- Analyzed the DHCP DORA process:
  - Discover
  - Offer
  - Request
  - ACK

### ARP
- Captured ARP traffic
- Analyzed MAC address resolution behavior
- Observed local network device discovery

### ICMP
- Captured ping traffic
- Inspected Echo Requests and Echo Replies

---

# Troubleshooting Skills Developed

## DNS Troubleshooting
- Identified failed DNS responses
- Differentiated DNS failures from connectivity failures

## Connectivity Troubleshooting
- Analyzed failed TCP connections
- Investigated retransmissions and unreachable hosts
- Diagnosed packet-level communication failures

## Adapter Troubleshooting
- Identified active vs disconnected adapters
- Understood “Media Disconnected” states
- Differentiated Wi-Fi and Ethernet adapter behavior

---

# Tools Used
- Wireshark
- Windows Command Prompt
- Web Browser Traffic Generation
- Ping / ICMP Testing
- DHCP Release & Renew Commands

---

# Important Networking Concepts Learned

## TCP vs UDP
| TCP | UDP |
|---|---|
| Reliable | Faster |
| Connection-oriented | Connectionless |
| Ordered delivery | No guaranteed delivery |
| Used for websites and downloads | Used for DNS and streaming |

---

## Common Ports
| Port | Protocol | Purpose |
|---|---|---|
| 53 | DNS | Name resolution |
| 80 | HTTP | Web traffic |
| 443 | HTTPS | Secure web traffic |
| 22 | SSH | Remote Linux access |
| 3389 | RDP | Remote Desktop |

---

## DHCP DORA Process
1. Discover
2. Offer
3. Request
4. ACK

---

## TCP Handshake
1. SYN
2. SYN/ACK
3. ACK

---

# Real-World Troubleshooting Scenarios Practiced
- DNS failures
- Failed TCP handshakes
- Packet retransmissions
- Connectivity timeouts
- DHCP lease renewal
- Adapter connectivity issues

---

# Key Takeaways
- Packet analysis provides direct visibility into network communication.
- DNS failures can be identified through missing DNS responses.
- TCP retransmissions often indicate connectivity instability.
- ARP is responsible for local IP-to-MAC resolution.
- DHCP automatically assigns network configuration using the DORA process.
- Wireshark is a critical tool for diagnosing real-world network issues.

---

# Outcome
By the end of Day 3, I gained practical experience capturing and analyzing live network traffic, diagnosing connectivity issues, and understanding how common network protocols behave in real-world environments.
