# Hospital Management System - Cisco Network Architecture

This project provides a secure, highly available Cisco network infrastructure designed specifically for a hospital environment. The architecture ensures reliable data transmission, strict departmental isolation, and robust security protocols for critical medical and administrative operations.

## Network Architecture

* **Hierarchical Design:** Built using Core Routers, Multilayer Switches, and Access Switches to manage traffic efficiently.
* **Redundancy:** Implemented hardware and path redundancy strategies to ensure continuous network availability and eliminate single points of failure.
* **Dynamic Routing:** Deployed **OSPF** (Open Shortest Path First) for dynamic routing, ensuring fast convergence and efficient data transmission across the network.

## Segmentation and Traffic Management

* **VLAN Allocation:** Configured dedicated VLANs to segregate traffic between distinct hospital departments (e.g., ICU, Emergency, Administration, Pharmacy).
* **Subnetting:** Applied structured IP subnetting to support VLAN routing and secure traffic management between isolated network zones.

## Security Measures

* **Access Control Lists (ACLs):** Configured strict ACLs to control user access and restrict unauthorized communication between sensitive medical systems and public networks.
* **VPN Solutions:** Implemented Virtual Private Networks (VPNs) to provide secure, encrypted remote access for off-site doctors and administrators.
* **Port Security:** Enforced port-security policies at the access switch level to prevent unauthorized physical devices from connecting to the network.

## IP Address Management

* **DHCP Servers:** Set up centralized DHCP configuration for dynamic IP allocation to mobile medical carts, staff devices, and guest networks.
* **Static IP Allocation:** Assigned static IP addresses for critical infrastructure, including internal servers, networking hardware, and essential medical equipment to ensure absolute stability.
