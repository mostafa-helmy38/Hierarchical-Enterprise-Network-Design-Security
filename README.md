# Hierarchical Enterprise Network Design & Security (Wired & Wireless)

## Project Overview
This project simulates a secure enterprise campus network designed using Cisco Packet Tracer.
The network follows a hierarchical architecture consisting of Core, Distribution, and Access layers to ensure scalability, high availability, and efficient traffic management.

The design supports both wired and wireless users with strong emphasis on security.
Enterprise wireless architecture is implemented using a centralized WLAN Controller managing lightweight access points.
Layer 2 security mechanisms are applied at the access layer to protect against common LAN-based attacks.
An edge router is deployed with NAT configuration to provide secure external connectivity.

## Network Architecture
- Core Layer: Backbone connectivity and redundancy
- Distribution Layer: Inter-VLAN routing and policy control
- Access Layer: End-user connectivity and Layer 2 security enforcement

## Technologies Used
- Hierarchical Network Design (Core / Distribution / Access)
- VLAN Segmentation
- Inter-VLAN Routing (SVI on Multilayer Switches)
- Trunking (IEEE 802.1Q)
- Wired & Wireless Network Integration
- WLAN Controller (WLC)
- Lightweight Access Points (CAPWAP)
- Layer 2 Security
  - Port Security
  - DHCP Snooping
  - Dynamic ARP Inspection (DAI)
- NAT (PAT) on Edge Router

## Wireless Network Architecture
- Centralized WLAN architecture using a Wireless LAN Controller (WLC)
- Lightweight access points managed via CAPWAP
- SSIDs mapped to VLANs for secure segmentation
- Unified security policies for wired and wireless users

## Edge Router & NAT
- R1 acts as the enterprise edge router
- NAT (PAT) is configured to translate private IP addresses
- Enables secure access to external networks

## Security Features
- VLAN-based segmentation for isolation
- Layer 2 security hardening at the access layer
- Secure perimeter design using NAT

## Skills Demonstrated
- Enterprise hierarchical network design
- Secure wired and wireless integration
- Centralized wireless management (WLC)
- Layer 2 security implementation
- Edge routing and NAT configuration
- Network scalability and security best practices

## How to Run the Project
1. Open the `.pkt` file using Cisco Packet Tracer.
2. Review device configurations and network topology.
3. Test connectivity between VLANs and wireless clients.
4. Verify NAT functionality through the edge router.
