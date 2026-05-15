# CCNA Enterprise Network Lab — Cisco Packet Tracer

**Tool:** Cisco Packet Tracer  
**Level:** CCNA  
**Type:** Multi-Site Enterprise Network Simulation

---

## Project Overview

Designed and implemented a complete enterprise network simulating HQ and Branch office environments with full security controls.

---

## Network Design

HQ VLANs:

| VLAN | Department | Network |
|------|-----------|---------|
| VLAN 10 | HR | 192.168.10.0/24 |
| VLAN 20 | IT | 192.168.20.0/24 |
| VLAN 30 | SERVER | 192.168.30.0/24 |

WAN Link: 10.0.0.0/30 — Serial WAN between HQ and Branch routers

---

## What I Built

- VLAN segmentation with trunk ports
- Inter-VLAN routing (Router-on-a-Stick)
- DHCP auto-addressing for all VLANs
- OSPF dynamic routing between sites
- Serial WAN link configuration
- NAT for internet simulation
- ACL security — HR blocked from IT and SERVER
- SSH secure remote management
- Switch port security with MAC sticky addressing

---

## Security Controls

| Control | Implementation |
|---------|---------------|
| ACL | HR blocked from IT and SERVER departments |
| SSH | Encrypted remote management only |
| Port Security | MAC sticky, violation = shutdown |
| NAT | Internal IPs hidden from outside |

---

## Skills Demonstrated

VLANs | Trunking | OSPF | DHCP | NAT | ACL | SSH | Cisco IOS CLI | WAN | Switch Security
