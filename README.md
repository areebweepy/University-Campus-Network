# 🌐 University Campus Networking Project (Cisco Packet Tracer)

This project demonstrates the design and simulation of a **multi-campus university network** using **Cisco Packet Tracer**. It focuses on creating a scalable, secure, and efficiently routed architecture suitable for real-world educational institutions.

The network includes separate configurations for the **Main Campus** and **Branch Campus**, utilizing VLANs, inter-VLAN routing, OSPF, DHCP, security mechanisms, and WAN connectivity.

---

## 🎯 Objective

Design a complete university network with:
- Logical segmentation using VLANs and subnetting
- Inter-campus connectivity via WAN links
- Efficient routing and IP address management
- Robust security and scalability for future expansion

---

## 🏗️ Network Overview

- 🏛 **Main Campus** and **Branch Campus** simulated in Cisco Packet Tracer
- Each campus includes:
  - **Layer 3 Switches (Cisco 3560)** for inter-VLAN routing and DHCP
  - **2911 Routers** for WAN and internet access
  - **Layer 2 Switches (Cisco 2960)** for end devices
  - **End Devices**: PCs, printers, servers
- WAN connectivity via **Serial Leased-Line**
- Internet access via **NAT (PAT)** and **Default Route**

---

## 📊 Network Features & Configuration

### 🔧 VLANs & Subnetting
- Logical division of departments
- Each VLAN assigned a unique subnet
- Gateways implemented using **Switch Virtual Interfaces (SVIs)**

### 🔁 Inter-VLAN Routing
- Configured on Layer 3 switches
- Enables secure communication between VLANs

### 📡 Dynamic IP Allocation (DHCP)
- DHCP configured on Layer 3 switches
- Assigns IP, gateway, and DNS per VLAN automatically

### 🌍 Routing (OSPF)
- **OSPF** protocol used between routers
- Automatically adapts to changes in topology

### 🔐 Network Security Features
| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **PortFast**        | Reduces port transition delay for faster device connectivity                |
| **BPDU Guard**      | Prevents misconfigured devices from affecting spanning tree                 |
| **Port Security**   | Limits devices per port to prevent unauthorized access                      |
| **DHCP Snooping**   | Protects from rogue DHCP servers                                            |
| **PAT (NAT Overload)** | Allows internal devices to access the internet via one public IP         |
| **Gateway of Last Resort** | Configured for default routing of unknown traffic to the ISP         |

---

## 🧠 Key Takeaways

- Designed a scalable and secure dual-campus infrastructure
- Applied core networking concepts: VLANs, subnetting, routing protocols, NAT
- Implemented real-world security mechanisms to harden the network
- Simulated all functionality in **Cisco Packet Tracer** using industry-standard devices

---

## 📁 Project Structure
```
university-network-project/
├── README.md
├── university-campus.pkt 
├── network-diagrams/ 
   ├── main-campus.png
   ├── sub-campus.png
```
---

## 👨‍💻 Author

**Mirza Areeb Baig**  

Computer Science Student | Cybersecurity Enthusiast  

