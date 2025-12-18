# Resilient Multi-Site Enterprise WAN

## 📌 Project Overview
This project simulates a resilient Wide Area Network (WAN) backbone connecting three major enterprise sites in Sri Lanka: Colombo (HQ), Kandy, and Galle. The network is engineered to ensure High Availability (HA) and continuous uptime using dynamic routing protocols.

[Network Topology](Enterprise_Topology.PNG)


## 🛠️ Technologies & Tools
* Simulator: Cisco Packet Tracer
* Routing Protocol: OSPF (Open Shortest Path First)
* Hardware Emulated: Cisco 2911 Routers, Cisco 2960 Switches
* Key Concepts: WAN Design, Failover Redundancy, Link Cost Optimization, VLANs, NAT.

## ⚙️ Key Features
* Dynamic Failover: Implemented OSPF to automatically reroute traffic if a primary link between sites fails.
* OSPF Optimization: Adjusted link costs to prioritize higher bandwidth paths.
* Inter-Site Connectivity: Successful ping verification between end devices in Colombo, Kandy, and Galle.
* Scalability: The OSPF design allows for easy addition of new branch sites without major reconfiguration.


