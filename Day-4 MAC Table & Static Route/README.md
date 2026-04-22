# 🔀 MAC Table & Static Routing

This module focuses on switching and routing fundamentals, explaining how switches forward frames using MAC addresses and how routers direct traffic using static routes.

---

## 🎯 Objectives
- Understand different types of switches
- Learn how MAC address tables work
- Explore port security concepts
- Understand basic routing and static route configuration

---

## 🧠 Topics Covered

### 1️⃣ Types of Switches

#### 🔹 Based on OSI Layers
- **Layer 2 Switch** – Works with MAC addresses (Data Link Layer)
- **Layer 3 Switch** – Supports routing (Network Layer)

#### 🔹 Based on Manageability
- **Unmanaged Switch** – Plug and play, no configuration
- **Managed Switch** – Supports VLANs, security and configuration

---

### 2️⃣ MAC Address Table

- Stores MAC addresses of connected devices
- Used by switches to forward frames
- Command:
  ```
  show mac address-table
  ```
- Default VLAN: VLAN 1
- Static MAC entry configuration
- Command:
  ```
  mac-address-table static <MAC Address> vlan1 interface fastethernet <port-no.>
  ```

---

### 3️⃣ Port Security

Port security helps prevent unauthorized access to the network.

#### 🔹 Violation Modes
- **Shutdown** – Disables the port
- **Restrict** – Drops packets and logs the violation
- **Protect** – Drops packets silently

---

### 4️⃣ Routing Basics

- Introduction to routing concepts
- Understanding how routers forward packets between networks

---

### 5️⃣ Static Routing

Static routing is a manual method of defining network paths.

#### 🔹 Syntax
```
ip route <destination-network> <subnet-mask> <next-hop-ip>
```

#### 🔹 Example
```
ip route 10.0.0.0 255.0.0.0 172.16.0.2
```

---

## 🛠 Tools Used
- Conceptual understanding of switching and routing
- Cisco CLI commands (basic)
- No advanced lab configuration performed

---

## 🧩 Key Takeaway
Switches use MAC address tables to efficiently forward frames, while static routing allows manual control over how packets travel between networks. These concepts are essential for building a strong networking foundation.
