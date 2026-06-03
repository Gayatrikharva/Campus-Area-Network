# 🏫 Campus Area Network (CAN) — Cisco Packet Tracer

> A Campus Area Network simulation built in Cisco Packet Tracer featuring hierarchical topology, VLAN segmentation, inter-VLAN routing, DHCP, DNS, and OSPF. Includes subnetting, ACLs, and port security to connect multiple campus buildings efficiently and securely.

---

## 📌 Overview

This project simulates a fully functional **Campus Area Network (CAN)** designed using **Cisco Packet Tracer**. It models a real-world multi-building campus environment where departments, labs, offices, and administrative units are interconnected under a unified, scalable, and secure network infrastructure.

The design follows the **three-tier hierarchical network model** — Core, Distribution, and Access layers — ensuring high availability, efficient traffic flow, and ease of management.

---

## 🗂️ Project File

| File | Description |
|------|-------------|
| `Campus_Area_Network.pkt` | Cisco Packet Tracer simulation file |

> **Requirement:** [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) 7.x or later

---

## 🌐 Network Features

### 🏗️ Topology
- **Hierarchical Design** — Core, Distribution, and Access layers
- Multi-building campus layout with dedicated network segments per department

### 🔀 Switching
- **VLANs** — Logical segmentation by department (e.g., Admin, Library, Labs, Hostel)
- **Trunk Links** — IEEE 802.1Q trunking between switches
- **Inter-VLAN Routing** — Via Layer 3 switch or Router-on-a-Stick

### 🌍 Routing
- **OSPF / RIP** — Dynamic routing between campus buildings/segments
- **Static Routes** — For specific gateway configurations

### 🖥️ Services
- **DHCP** — Automatic IP address allocation per VLAN
- **DNS** — Hostname resolution for internal resources
- **HTTP/FTP Server** — Simulated campus web and file services

### 🔒 Security
- **ACLs (Access Control Lists)** — Restrict traffic between sensitive network zones
- **Port Security** — Prevent unauthorized devices on access ports
- **Password Protection** — Console, VTY, and enable passwords on all devices

### 📡 IP Addressing
- Structured subnetting using private IP ranges (e.g., `192.168.x.x` / `10.x.x.x`)
- Each VLAN/department assigned a unique subnet

---

## 🛠️ Technologies Used

- **Cisco Packet Tracer** — Network simulation
- **Cisco Routers** (e.g., 1941, 2911)
- **Cisco Switches** (e.g., 2960, 3650 Layer 3)
- **End Devices** — PCs, Laptops, Servers, Printers

---

## 🚀 Getting Started

1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/campus-area-network.git
   ```
3. Open `Campus_Area_Network.pkt` in Cisco Packet Tracer.
4. Explore the topology, run simulations, and test connectivity using the **Ping** and **Traceroute** tools.

---

## 📚 Concepts Demonstrated

- OSI Model layers in practice
- IP addressing and subnetting (VLSM)
- VLAN design and trunking
- Dynamic routing protocols
- Network security fundamentals
- Campus network design best practices

---

## 👤 Author

**Your Name**  
[GitHub](https://github.com/your-username) • [LinkedIn](https://linkedin.com/in/your-profile)

---

## 📄 License

This project is open for educational use. Feel free to fork, modify, and learn from it.
