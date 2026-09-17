# Multi-Site Enterprise Network Architecture

An end-to-end Cisco Packet Tracer network simulation implementing multi-site dynamic routing, WAN connections, security features, and essential IP services.

## 📌 Technical Features & Configurations
- **Subnetting & Addressing**: Custom IPv4 subnetting scheme starting from `192.168.5.0` applied across all LANs and WAN links.
- **Dynamic Routing**: Configured **OSPF** across core routers for dynamic routing and topology mapping.
- **Default Routing**: Default static routes implemented towards the simulated ISP interface.
- **Core Network Services**: Configured **DHCP** on routers for dynamic address allocation, alongside **HTTP, DNS, FTP, and Email** on the server.
- **Network Security & ACLs**:
  - Enforced **Port Security** on switch interfaces (`Fa0/2`).
  - Configured extended **Access Control Lists (ACLs)** (Permitted FTP for PC2, restricted other services).
  - Configured **Telnet** on `Switch 1` for remote switch management.

## 📂 Repository Contents
- `project (C).pkt`: Complete Cisco Packet Tracer simulation file.
