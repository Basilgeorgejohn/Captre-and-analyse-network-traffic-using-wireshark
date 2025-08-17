# Captre-and-analyse-network-traffic-using-wireshark


 ![wireshark](https://github.com/user-attachments/assets/b8b88c5c-1d7c-47ab-932f-c4155981ae00)

 # __what is wireshark?__

## Wireshark is a **network protocol analyzer** used to capture and analyze network traffic in real time. It allows users to inspect packets at a very detailed level.

## **Key Features**

- ### Captures live traffic from network interfaces.
- ### Supports hundreds of protocols (TCP, UDP, HTTP, DNS, etc.).
- ### Provides filtering options for focused analysis.
- ### Useful for troubleshooting, learning, and security analysis.
- ### Saves captures as `.pcap` files for later review.

  ## **Uses**
- ### Network troubleshooting.
- ### Cybersecurity investigations.
- ### Learning how network protocols work.

  

## Objective
 # __Capture and analyze live network packets  using Wireshark.__

## Protocols Identified
- **DNS**: Used for domain name lookups (e.g., resolving google.com).
- **TCP**: Reliable connections (web browsing, HTTP traffic).
- **UDP**: Faster, connectionless (DNS queries, streaming).
- **ICMP**: Ping requests and replies.
- <img width="1920" height="945" alt="Screenshot_2025-08-17_00_34_15" src="https://github.com/user-attachments/assets/1d402407-f389-41df-ae34-a288359f16bb" />
<img width="1920" height="945" alt="Screenshot_2025-08-17_00_32_42" src="https://github.com/user-attachments/assets/228de93c-41a6-420a-b062-727ddc4c8bf6" />
<img width="1920" height="945" alt="Screenshot_2025-08-17_00_32_21" src="https://github.com/user-attachments/assets/2c20e386-76b4-46be-b8d4-c871c00c5c2f" />





## Summary
- Captured traffic on interface **eth0** using Wireshark.
- Browsed websites and pinged google.com to generate traffic.
- Applied filters (`dns`, `http`, `tcp`) to analyze packets.
- Exported capture as `task5.pcap`.

## Outcome
Learned how to:
- Start and stop Wireshark captures
- Apply protocol filters
- Identify multiple protocols in traffic
- Save capture for further analysis
