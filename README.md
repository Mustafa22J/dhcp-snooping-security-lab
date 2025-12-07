# DHCP Snooping Security Lab (Cisco Packet Tracer)

This Packet Tracer lab demonstrates how to prevent unauthorized DHCP servers
and protect enterprise LAN environments using Layer 2 security features such as:

- DHCP Snooping
- Trusted interfaces
- VLAN segmentation
- Inter-VLAN routing
- Basic edge/remote routing

The goal is to detect and block a rogue DHCP server that attempts to hand out
incorrect IP addresses to client devices.

---

## Topology

See: **topology-overview.png**

The network simulates an enterprise campus LAN with:
- Edge router
- Core/aggregation switch
- Access switch
- Administrator PC
- Unauthorized DHCP server
- VLAN10 and VLAN20 clients
- Remote router and external network

---

## Key Features

- DHCP snooping enabled globally
- Trusted uplinks only
- Rogue DHCP traffic blocked
- VLAN10 and VLAN20 segmentation
- Inter-VLAN routing on L3 switch
- DHCP validation on untrusted interfaces

---

## Default Lab Credentials
enable secret class
username cisco secret class


> These credentials are only for educational Packet Tracer usage.

---

## Requirements

- Cisco Packet Tracer (any recent version)
- Basic knowledge of VLANs, DHCP behavior, and switching

---

## How We Built It

All configuration steps follow the same instructions used in class,
and we always complete the labs **in person** as well to practice commands,
verification, and troubleshooting hands-on.

---

## Files included
DHCP-Security-Lab.pka
topology-overview.png

---

## Verification Examples
show ip dhcp snooping
show ip dhcp snooping binding
show vlan brief
show ip interface brief

---

## Author

Educational Packet Tracer practice – Routing & Switching security topics (2025)



