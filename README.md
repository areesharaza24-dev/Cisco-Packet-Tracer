# Cisco Packet Tracer — Networking Labs

> A collection of hands-on Cisco Packet Tracer labs built to reinforce CCNA-level networking concepts through practical simulation and experimentation.

---

## 📁 Lab Included

| File | Description |
|------|-------------|
| `peer to peer network.pkt` | Basic peer-to-peer network simulation between two end devices |

---

## 🎯 Objective

The goal of this lab is to demonstrate how two computers can communicate directly with each other without the need for an intermediary device such as a switch or router. This lab establishes the foundation for understanding data transmission, IP addressing, and basic connectivity in a network environment.

---

## 🗺️ Topology Overview

![Peer to Peer Network Topology](images/topology.png)

Two PCs — **Hassan** (`192.168.1.1`) and **Hussain** (`192.168.1.2`) — are connected directly using a crossover cable. Each device is assigned a static IP address within the same subnet (`192.168.1.0/24`), allowing them to ping and communicate with one another. The simulation panel on the right confirms live packet exchange between both devices.

---

## 🧠 Concepts Practiced

- Understanding peer-to-peer (P2P) network architecture
- Assigning and configuring static IP addresses
- Subnet mask configuration and same-network communication
- Using the `ping` command to verify connectivity
- Introduction to OSI Layer 1 (Physical) and Layer 3 (Network) concepts
- Reading and interpreting Packet Tracer simulation results

---

## 🛠️ Tools Used

| Tool | Version / Notes |
|------|-----------------|
| Cisco Packet Tracer | 8.x (recommended) |
| Operating System | Windows / macOS / Linux |

---

## 🚀 How to Open the Lab

1. **Download Cisco Packet Tracer**
   - Visit the [Cisco NetAcad website](https://www.netacad.com/) and create a free account.
   - Download and install Packet Tracer for your operating system.

2. **Clone or Download this Repository**
   ```bash
   git clone https://github.com/your-username/Cisco-Packet-Tracer.git
   ```
   Or click **Code → Download ZIP** and extract it.

3. **Open the Lab File**
   - Launch Cisco Packet Tracer.
   - Go to **File → Open**.
   - Navigate to the downloaded folder and select `peer to peer network.pkt`.

4. **Explore the Lab**
   - Click on any device to view its configuration.
   - Use the **Simulation Mode** (bottom-right) to observe packet flow step by step.
   - Open the **Command Prompt** of a PC and run:
     ```
     ping <IP address of the other PC>
     ```

---

## Author

**Areesha Raza**
## email: areesharaza_24@gmail.com

---

## 📄 License

This repository is intended for educational purposes. Feel free to use or reference these labs for your own learning journey.

---

*Built with curiosity and a lot of `ping` commands.*
