# 🌐 Network Fundamentals

This module introduces the foundational concepts of computer networking, focusing on how devices communicate, what components are needed to build a network, and how Cisco’s hierarchical network design improves scalability and performance.

---

## 🎯 Objectives
- Understand the concept and purpose of computer networking  
- Learn the advantages of networking and its real-world use cases  
- Explore the types of networks and their characteristics  
- Identify key networking devices and their roles  
- Learn about network design models and fiber technologies  

---

## 🧠 Topics Covered

### 🔹 1. What is Networking?
Networking is the process of connecting multiple devices (computers, routers, switches, servers, etc.) to share data, resources and services efficiently.

---

### 🔹 2. Benefits of Networking
- **Resource Sharing** – Printers, files and internet access can be shared  
- **Communication** – Enables email, chat and data transfer  
- **Centralized Management** – Easier control and monitoring  
- **Scalability** – New devices can be added easily  
- **Data Security** – Controlled access and monitoring  

---

### 🔹 3. ARPANET
ARPANET (Advanced Research Projects Agency Network) was the **first operational packet-switching network** and the **precursor to today’s Internet**, developed in the late 1960s by the U.S. Department of Defense.

---

### 🔹 4. Types of Network
| Type | Full Form | Coverage |
|:--|:--|:--|
| **PAN** | Personal Area Network | A few meters (Bluetooth, USB) |
| **LAN** | Local Area Network | Within a building or campus |
| **MAN** | Metropolitan Area Network | Across a city |
| **WAN** | Wide Area Network | Across countries or continents |

---

### 🔹 5. Requirements for Network Configuration
- IP Addressing and Subnetting  
- Networking Devices (Router, Switch, Hub, etc.)  
- Cabling (Ethernet / Fiber)  
- Network Topology Plan  
- Configuration Tools (Cisco Packet Tracer, Console cable, etc.)

---

### 🔹 6. Common Networking Devices
| Device | Description |
|:--|:--|
| **Router** | Connects multiple networks and directs traffic between them |
| **Layer 2 Switch** | Operates at Data Link Layer; forwards frames based on MAC addresses |
| **Layer 3 Switch** | Performs both switching and routing; operates at Network Layer |
| **NGFW (Next Generation Firewall)** | Provides deep packet inspection, IPS and advanced security |
| **IPS (Intrusion Prevention System)** | Detects and blocks malicious network activities |
| **Access Point** | Connects wireless clients to a wired network |
| **Controller** | Centralized management for multiple access points |
| **Endpoints** | Devices such as PCs, laptops and phones used by end users |
| **Server** | Provides centralized services such as file, web or database hosting |
| **PoE (Power over Ethernet)** | Provides both power and data to devices (e.g., APs, IP cameras) through Ethernet cables |

---

### 🔹 7. Cisco Three-Layer Hierarchical Model
Cisco recommends a **modular design** that divides the network into layers for efficiency and scalability.

| Layer | Function |
|:--|:--|
| **Access Layer** | Connects end devices (PCs, printers, etc.) |
| **Distribution Layer** | Controls policies, routing and VLANs |
| **Core Layer** | High-speed backbone connecting distribution switches |

#### Two-Tier Model:
Combines **core** and **distribution** layers into one — used in smaller networks.

#### Spine-Leaf Architecture:
Modern data center design where every **leaf switch** connects to every **spine switch** for high availability and low latency.

---

### 🔹 8. On-Premises vs Cloud
| Type | Description |
|:--|:--|
| **On-Premises** | Network hardware and data are hosted locally within an organization |
| **Cloud** | Network services are hosted and managed remotely via the Internet (e.g., AWS, Azure, Cisco Meraki) |

---

### 🔹 9. Fiber Optic Cable Types
| Type | Core Diameter | Distance | Use Case |
|:--|:--|:--|:--|
| **Single-mode Fiber (SMF)** | ~9 microns | Long distance (up to 100 km) | Backbone connections |
| **Multi-mode Fiber (MMF)** | 50–62.5 microns | Short distance (up to 2 km) | LAN and enterprise networks |

---

## 🧩 Key Takeaway
> Networking is the backbone of modern communication.  
> Understanding devices, models and connections is the first step to becoming a professional network engineer.
