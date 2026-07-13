# Enterprise-Company-Network-Design-Cisco-Packet-Tracer
Enterprise Network Infrastructure Design using Cisco Packet Tracer with VLANs, Inter-VLAN Routing, DHCP, Dual ISP Redundancy, and Three-Tier Hierarchical Architecture.
Enterprise Network Infrastructure Design using Cisco Packet Tracer
📌 Project Overview

This project demonstrates the design and implementation of a highly available enterprise network for a company with approximately 600 employees distributed across three floors. The network is built using the Cisco Three-Tier Hierarchical Network Model, incorporating redundancy, VLAN segmentation, inter-VLAN routing, wireless connectivity, dynamic IP allocation, and dual ISP connectivity to ensure scalability, performance, and fault tolerance. The project follows the enterprise networking requirements described in the design brief.

🏢 Network Architecture
Core Layer
2 Cisco 2911 Core Routers
Dual ISP Connectivity for Internet Redundancy
Redundant Router-to-Router Links
Public IP Address Configuration
Static Routing
Distribution Layer
2 Cisco 3650 Multilayer Switches
Layer 3 Routing
Inter-VLAN Routing
Default Gateway Configuration
Redundant Links
Access Layer
Cisco 2960 Access Switches
Department-wise Network Segmentation
Wireless Access Points
PCs
Printers
Laptops
Tablets
🏢 Department Layout
First Floor
Sales Department
Human Resources (HR)
Second Floor
Finance Department
Administration Department
Third Floor
ICT Department
Server Room
🌐 VLAN Configuration
VLAN	Department	Network
VLAN 10	Sales	172.16.1.0/25
VLAN 20	HR	172.16.1.128/25
VLAN 30	Finance	172.16.2.0/25
VLAN 40	Administration	172.16.2.128/25
VLAN 50	ICT	172.16.3.0/25
VLAN 60	Server Room	172.16.3.128/25
⚙️ Technologies Used
Cisco Packet Tracer
Cisco 2911 Routers
Cisco 3650 Multilayer Switches
Cisco 2960 Switches
VLAN
Inter-VLAN Routing
Static Routing
DHCP
DNS Server
Email Server
Wireless Networking
IPv4 Addressing
Subnetting (VLSM)
Redundant Network Design
🚀 Key Features

✅ Three-Tier Hierarchical Network Design

✅ Dual ISP Redundancy

✅ Router Redundancy

✅ Distribution Layer Redundancy

✅ Inter-VLAN Routing

✅ Department-wise VLAN Segmentation

✅ Dynamic IP Allocation using DHCP

✅ Static IP Configuration for Servers

✅ DNS Server

✅ Email Server

✅ Wireless Connectivity for Every Department

✅ Scalable Enterprise Architecture

🖥️ Devices Used
Routers
Cisco 2911 ×2
Multilayer Switches
Cisco 3650 ×2
Access Switches
Cisco 2960 ×6
Servers
DHCP Server
DNS Server
Email Server
End Devices
Desktop PCs
Laptops
Tablets
Network Printers
Wireless
Access Points

🌍 IP Addressing
Public WAN Links
195.136.17.0/30
195.136.17.4/30
195.136.17.8/30
195.136.17.12/30
Private Network

Base Network:
172.16.1.0/16
Subnetting was performed using VLSM to allocate individual subnetworks for each department.

📡 Network Services
DHCP
DNS
Email Service
Wireless Access
Inter-VLAN Communication
Internet Connectivity
🔒 Security Configuration
Hostname Configuration
Console Password
Enable Secret Password
Banner Message
Disable DNS Lookup
Department Isolation using VLANs
📊 Project Objectives
Design a scalable enterprise network.
Implement VLAN segmentation.
Configure Inter-VLAN Routing.
Provide Internet redundancy using dual ISPs.
Enable wireless connectivity for every department.
Configure DHCP for automatic IP assignment.
Configure DNS and Email services.
Build a fault-tolerant network using redundant devices.
Improve network scalability and availability.
🎯 Learning Outcomes

Through this project, I gained practical experience in:

Enterprise Network Design
Cisco Packet Tracer
VLAN Configuration
Inter-VLAN Routing
Static Routing
Layer 2 & Layer 3 Switching
DHCP Configuration
DNS Configuration
Email Server Configuration
Wireless Network Deployment
Enterprise Network Redundancy
IPv4 Addressing & Subnetting
Network Troubleshooting

📷 Network Topology:-
Enterprise network.png

🛠️ Future Improvements
OSPF Dynamic Routing
HSRP Gateway Redundancy
EtherChannel
STP Optimization
ACL-based Network Security
NAT/PAT Configuration
SSH Remote Management
Network Monitoring using SNMP
Syslog Server
Cloud Integration (AWS/Azure)

📂 Project File
Fourth comapny network project.pkt

👨‍💻 Author:-
Prajwal K

Aspiring Cloud & DevOps Engineer

☁️ AWS | Networking | Linux | Git | Python
💼 Building Real-World Cloud & Enterprise Networking Projects
🔗 GitHub: (Add your GitHub profile link)
🔗 LinkedIn: (Add your LinkedIn profile link)
