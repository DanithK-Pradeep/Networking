# Enterprise Network Infrastructure Simulation

A professional-grade network topology designed in **Cisco Packet Tracer**. This project simulates a corporate environment with multiple departments, focusing on security, scalability, and efficient traffic management through VLAN segmentation and inter-VLAN routing.

## 🚀 Key Features
* **Departmental Segmentation**: Isolated networks for Finance, IT, HR, and Sales using VLANs.
* **Inter-VLAN Routing**: Configured using a Multilayer Switch (SVI) to allow controlled communication between departments.
* **Centralized Services**: Implementation of a Server Farm providing DHCP for automatic IP addressing and DNS for domain resolution.
* **Network Security**: Basic security protocols implemented to ensure data integrity between sensitive departments.

## 🛠️ Technologies Used
* **Cisco Packet Tracer**
* **VLAN (Virtual Local Area Network)**
* **Layer 3 Switching**
* **DHCP & DNS Protocols**
* **IPv4 Subnetting**

## 📂 Project Structure
* `Networking.pkt`: The main Cisco Packet Tracer file containing the full topology and configurations.
* `Documentation/`: (Optional) Add your IP addressing scheme table here.

## ⚙️ Setup Instructions
1. Download and install **Cisco Packet Tracer** (v8.0 or higher recommended).
2. Clone this repository or download the `Networking.pkt` file.
3. Open the file in Packet Tracer.
4. Use the **Simulation Mode** or **Command Line Interface (CLI)** to inspect the routing tables and VLAN configurations.

## 📋 Network Topology Overview
The network uses a core multilayer switch connected to departmental access switches. Each department is assigned a specific VLAN ID and Subnet to reduce broadcast traffic and improve security.
