# College-Network-System

Introduction
This project focuses on designing a campus-wide network that includes multiple departments, a server room, and labs. It supports services such as file sharing (FTP), web hosting, and domain name resolution (DNS).

Key features:

Dynamic routing using RIP (Routing Information Protocol)

Use of routers, switches, PCs, laptops, and servers

Network segmentation by subnets for better management and security

**Network Overview**

Departments/Subnets: Each department has its own subnet for logical separation.

Servers:

FTP Server: Provides centralized file sharing.

DNS Server: Resolves domain names to IP addresses.

Web Server: Hosts internal websites and applications.

Routers and Switches:

Routers connect different departments using RIP.

Switches connect devices within the same department.

**Working**

Dynamic Routing: Implemented RIP protocol to allow automatic exchange of route information between routers.

Inter-Subnet Communication: Enabled communication between different subnets.

Service Access: FTP, DNS, and Web services are accessible across the network.

**Configuration Details**

Router Configuration
Router0: Handles EE Department and Office Network

Router1: Handles Computer Department

Router2: Manages Server Room

Each router is configured with:

Interface IPs

RIP routing protocol

Server Configuration
FTP Server: IP 1.0.0.4

DNS Server: IP 1.0.0.2 (with domain-to-IP mappings)

Web Server: IP 1.0.0.3 (with HTTP services enabled)

End Devices
Static IP addressing

Default Gateway set to respective router interfaces

**Conclusion**
This project successfully demonstrates the design of a modern, efficient campus network infrastructure.
Technologies like dynamic routing and centralized services ensure seamless communication across departments and administrative units.

While VoIP was not implemented directly in this project, the network is designed to easily support future integration of VoIP services, thus aligning with modern communication needs in educational institutions.

