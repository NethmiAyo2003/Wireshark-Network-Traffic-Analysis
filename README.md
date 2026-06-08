# Live Network Traffic Analysis using Wireshark

A hands-on cybersecurity project focused on capturing, filtering, and analyzing live network traffic using **Kali Linux** and **Wireshark**. This project demonstrates practical skills in network monitoring, protocol analysis, and reconnaissance detection (specifically focusing on ICMP traffic).

## 🚀 Project Overview
In a Security Operations Center (SOC) environment, network visibility is critical. This project simulates how a security analyst monitors packet-level data to detect active hosts and identify network probing or mapping attempts by attackers.

## 🛠️ Tools & Technologies
* **OS:** Kali Linux 2026.1
* **Tool:** Wireshark (Network Protocol Analyzer)
* **Protocol Analyzed:** ICMP (Internet Control Message Protocol)

## 📝 Implementation Steps

### 1. Traffic Capture
The packet capture was initiated on the primary network interface (`eth0`) inside a virtualized Kali Linux environment to monitor active network streams.

### 2. Live Filtering
Applied a dedicated Wireshark display filter to isolate ICMP traffic from other background noise:
```text
icmp
