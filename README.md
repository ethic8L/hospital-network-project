# Techlead Innovation Network Design Project

## Project Overview
A comprehensive network design for a hospital environment, developed using Cisco Packet Tracer. This project demonstrates secure network architecture, efficient segmentation, and access control specifically for a healthcare setting.

---

## Cisco Packet Tracer Project

You can download or view the full project from the following link:

- [Download Packet Tracer Project]([Company Network Project (EN).pdf](https://github.com/ethic8L/hospital-network-project/blob/402b35a64eaa58f521c4f434dac753577d43c5e8/Company%20Network%20Project%20(EN).pdf))

### Project for: Techlead Innovation (fictional company)

### Part 1: Objective
The goal of this project was to design and implement a scalable, secure, and efficient network infrastructure for the new building of Techlead Innovation, a company specializing in innovative cloud solutions. This project aims to:
- Ensure seamless connectivity
- Efficiently manage IT resources
- Protect against internal and external threats

The network meets requirements for availability, redundancy, and data protection, enabling communication across various departments using advanced technologies such as VLAN, VoIP, DMZ, OSPF, DHCP, EtherChannel, and Cisco ASA firewalls. This hierarchical network model includes VLAN segmentation, inter-VLAN routing, centralized wireless management, redundancy, and IP resource allocation across designated subnets. The result is a comprehensive network environment that supports business operations, data protection, and further expansion.

### Part 2: Addressing Plan

| Category       | Network Address / Subnet Mask | Host Address Range             | Default Gateway | Broadcast Address  |
|----------------|-------------------------------|--------------------------------|-----------------|--------------------|
| **Management** | 192.168.20.0/24               | 192.168.20.1 - 192.168.20.254  | 192.168.20.1    | 192.168.20.255     |
| **WLAN**       | 10.20.0.0/16                  | 10.20.0.1 - 10.20.255.254      | 10.20.0.1       | 10.20.255.254      |
| **LAN**        | 172.16.0.0/16                 | 172.16.0.1 - 172.16.255.254    | 172.16.0.1      | 172.16.255.255     |
| **VoIP**       | 172.30.0.0/16                 | 172.30.0.1 - 172.30.255.254    | 172.30.0.1      | 172.30.255.255     |
| **DMZ**        | 10.11.11.0/27                 | 10.11.11.1 - 10.11.11.30       | 10.11.11.1      | 10.11.11.31        |
| **Inside Servers** | 10.11.11.32/27           | 10.11.11.33 - 10.11.11.62      | 10.11.11.33     | 10.11.11.63        |

### Part 3: Equipment Used
- **Routers**: Two routers with OSPF support for ISP connections and inter-VLAN routing
- **Firewalls**: Cisco ASA 5500-X series for network security and access control
- **Layer 3 Switches**: Catalyst 3850 (48-port) for distribution layer and VLAN routing
- **Layer 2 Switches**: Catalyst 2960 (48-port) for network segmentation and host connections
- **Wireless Controllers (WLC)**: Two Cisco WLCs for centralized wireless management
- **Access Points (WAP)**: Lightweight access points deployed on each floor
- **Servers**: Physical servers for virtualization, supporting DHCP, DNS, Radius, FTP, Web, Email, NAS services
- **VoIP Phones**: Cisco voice gateway and IP phones across departments for VoIP communication
- **End-Devices**: Computers, laptops, and mobile devices for LAN and WLAN connections


### Part 4: Network Testing


The network was tested extensively to ensure it met all specified requirements, focusing on scalability, segmentation, and security. Testing included:

Connectivity Testing: Verified connectivity across VLANs and subnetworks using ICMP and traceroute.
Redundancy Testing: Simulated link and device failures to confirm the high availability and failover configurations.
Security Testing: Tested firewalls, access control lists (ACLs), and VLAN segmentation to prevent unauthorized access.
Performance Testing: Evaluated network performance, ensuring minimal latency and optimal data flow under simulated network loads.
VoIP Functionality: Confirmed voice communication across departments using IP phones.
Conclusion
This project successfully established a secure and efficient network infrastructure for Techlead Innovation sp. z o.o. The design facilitates operational efficiency, data protection, and is adaptable for future expansion. Future enhancements could include:

Advanced Monitoring: Implementing network monitoring tools to detect and prevent potential issues.
Automation: Utilizing network automation tools to streamline network management and reduce manual interventions.


## Tags
- `Cisco Packet Tracer`
- `Network Design`
- `Healthcare IT`
- `VLAN`
- `VoIP`
- `Firewall`
- `Network Security`
- `Network Testing`
- `Redundancy`
- `Scalability`



