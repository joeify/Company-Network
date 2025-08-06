# Company Network-Cisco Packet Tracer

## Objective
The objective of this project is to create an efficient, connected company network that allows connections between different sectors of a company with access to the web.

This project demonstrates a small-to-medium business architecture with inter-site routing using RIP, dedicated DNS and HTTP services, DHCP-enabled LANs, and hierarchical switching.

### Skills Learned

- Routing Protocols – Implementing and troubleshooting RIP across multiple routers
- Network Design – Creating scalable, modular, and hierarchical topologies
- IP Addressing & Subnetting – Planning and applying consistent IP addressing schemes
- Switch Configuration – Understanding the role of multi-layer and distribution switches
- End-to-End Connectivity – Verifying and simulating traffic between clients and servers
- DHCP Configuration – Automating IP address management across sites
- DNS & HTTP Simulation – Hosting and resolving internal network services
- Troubleshooting – Using simulation mode for diagnostic and connectivity checks

### Tools Used

- Cisco Packet Tracer

## Network Topology Summary

### Site 1 – Main Office
IP Scheme: 192.168.4.0/24

Devices:
- 1 Router
- 2 Multi-layer Switches
- 4 Distribution Switches
- 1 DHCP Server
- 16 PCs

Purpose: Central office infrastructure with Layer 3 switching and dynamic IP allocation.

### Site 2 – Server Farm
IP Scheme: 192.168.5.0/24

Devices:
- 1 Router
- 1 DNS Server (bing.com)
- 1 HTTP Server (google.com)

Purpose: Provides name resolution and web services to the network.

### Site 3 – Branch Office
IP Scheme: 192.168.3.0/24

Devices:
- 1 Router
- 1 Multi-layer Switch
- 2 Distribution Switches
- 1 DHCP Server
- 4 PCs

Purpose: Smaller remote office with DHCP and switching.

*Ref 1: Network Diagram*
<img width="1770" height="701" alt="Screenshot 2025-08-05 200237" src="https://github.com/user-attachments/assets/64236030-73d2-4010-9615-9a6924f50723" />

*Ref 2: RIP Routing Protocol SITE 1*

<img width="698" height="612" alt="Screenshot 2025-08-05 200336" src="https://github.com/user-attachments/assets/9209916c-775c-4b3a-9a12-a2063b03a97e" />

*Ref 3: RIP Routing Protocol SITE 2*

<img width="699" height="614" alt="Screenshot 2025-08-05 200526" src="https://github.com/user-attachments/assets/e6c31a12-7940-43e6-bbb2-d9582159d312" />

*Ref 4: RIP Routing Protocol SITE 3*

<img width="700" height="586" alt="Screenshot 2025-08-05 200545" src="https://github.com/user-attachments/assets/954ea34b-800e-4d4c-8975-6907fb9e8134" />
