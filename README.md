# CiscoPacketTracer-project-19-Secured-Three-Subnet-Network-Router-on-a-Stick-with-Password-Protection
I’m excited to share my latest Cisco Packet Tracer project – a three‑subnet routed network featuring a router (with interfaces on 192.168.1.0/24, 192.168.2.0/24, 192.168.3.0/24), a 2960 switch, two client PCs (Client02 – 192.168.1.200, PC1 – 192.168.1.10/24), and a server (Server3 – 192.168.3.254).

![image alt](https://github.com/Sameera54321/CiscoPacketTracer-project-19-Secured-Three-Subnet-Network-Router-on-a-Stick-with-Password-Protection/blob/main/8.jpg?raw=true)

## 📌 Summary

### Three‑Subnet Secured Network is a Cisco Packet Tracer simulation that models a small office network with three IP subnets, interconnected via a single router (router‑on‑a‑stick or multi‑interface design). The topology includes:

    Router (unnamed, but with interfaces Fa0/1, G0/1, S0/0, S1/1)

    Switch – 2960-24TT SW1 connecting the 192.168.1.0/24 subnet

    Clients – Client02 (192.168.1.200) and PC1 (192.168.1.10/24)

    Server – Server3 (192.168.3.254) on a separate subnet

    Additional subnet – 192.168.2.0/24 (likely for future expansion or another segment)

### The project focuses on:

    Routing between 192.168.1.0/24, 192.168.2.0/24, and 192.168.3.0/24 (static routes or dynamic routing)

    Password security – chamodi1234 applied to console and VTY lines on the router

    Switch configuration – VLANs, access/trunk ports, port security

    Server services – DHCP to assign IPs to clients, DNS, or web server

    Verification – ping, traceroute, show ip route, show running-config

## ✨ Features

    ✅ 3 subnets – 192.168.1.0/24, 192.168.2.0/24, 192.168.3.0/24

    ✅ Router – inter‑subnet routing with static routes or default gateway

    ✅ Switch (2960-24TT) – VLAN capable, trunking to router

    ✅ Client PCs – static or DHCP IP assignment

    ✅ Server3 – network services (HTTP, DNS, FTP, DHCP)

    ✅ Password protection – chamodi1234 on console/aux/VTY lines

    ✅ Full Packet Tracer file (.pkt) – ready to open and practice

    ✅ Documentation – IP plan, password list, config snippets, topology diagram

### IP addressing :

| Device | Interface | IP Address | Subnet |
| :--- | :--- | :--- | :--- |
| Router (Fa0/1) | Fa0/1 | (implied gateway) | 192.168.1.0/24 |
| Router (G0/1) | G0/1 | (implied gateway) | 192.168.2.0/24 |
| Router (S0/0) | S0/0 | (serial link) | (unknown) |
| Router (S1/1) | S1/1 | (serial link) | (unknown) |
| Client02 | Fa0 | 192.168.1.200 | 192.168.1.0/24 |
| PC1 | Fa0 | 192.168.1.10/24 | 192.168.1.0/24 |
| Server3 | Fa0 | 192.168.3.254 | 192.168.3.0/24 |

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – router, switch, and end‑device configurations

    (Optional) Text editor – for documenting configs

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add dynamic routing (OSPF/EIGRP) between multiple routers.

    Implement ACLs to filter traffic between subnets.

    Add more VLANs or a wireless access point.

    Improve security (SSH instead of telnet, enable secret, banner).

    Update the documentation with new features.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
