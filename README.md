# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info.
<img width="1909" height="1021" alt="image" src="https://github.com/user-attachments/assets/e6a74d60-5b72-4916-9c71-dd90b12344f9" />
<img width="954" height="1020" alt="image" src="https://github.com/user-attachments/assets/be395bbd-abe2-4a39-88a8-82c337f3b7ed" />
<img width="1919" height="744" alt="image" src="https://github.com/user-attachments/assets/5976ca91-0266-4d15-9283-90c28a9820cf" />

<img width="954" height="1020" alt="image" src="https://github.com/user-attachments/assets/4ec198fb-0cef-44e8-ad42-512bf94643fa" />
<img width="973" height="473" alt="image" src="https://github.com/user-attachments/assets/4c75f1ab-538d-4b9a-b1ae-8c47396ce7ed" />
<img width="1919" height="708" alt="image" src="https://github.com/user-attachments/assets/770a1a3c-708a-40a9-a54f-8c45e63ac485" />
<img width="1919" height="782" alt="image" src="https://github.com/user-attachments/assets/0a8fff65-c490-41b4-ab8e-a33e75a2737c" />
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/5cd84d40-a47c-4b8c-8c73-cb4b0be7c273" />






## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
