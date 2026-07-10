# Enterprise Network Design Using Cisco Packet Tracer

## Overview
This project demonstrates the design and implementation of a small enterprise network using Cisco Packet Tracer. The network was configured with VLAN segmentation, inter-VLAN routing, DHCP, DNS and an internal web server to simulate a real business environment.

## Technologies Used
- Cisco Packet Tracer
- VLANs
- Router-on-a-Stick
- DHCP
- DNS
- HTTP Web Server
- TCP/IP

## Network Design
Three departments were separated using VLANs:
| VLAN | Department | Network |
|------|------------|----------------|
| 10 | HR | 192.168.10.0/24 |
| 20 | Admin | 192.168.20.0/24 |
| 30 | Staff | 192.168.30.0/24 |

Inter-VLAN communication was achieved using Router-on-a-Stick with a trunk link between the router and switch.

## Features
- Configured VLAN segmentation for three departments
- Implemented inter-VLAN routing using Router-on-a-Stick
- Configured DHCP pools for automatic IP address allocation
- Implemented DHCP Relay using 'ip-helper address'
- Configured DNS hostname resolution
- Hosted an internal company website
- Verified connectivity and network services through testing

## Learning Outcomes
This project strengthened my understanding of:
- Enterprise network design
- VLAN configuration
- Inter-VLAN routing
- DHCP and DNS implementation
- TCP/IP networking
- Network troubleshooting using Cisco IOS

## Contents
- Cisco Packet Tracer (.pkt) file
- Project Report (PDF) containing the network design, configurations, testing and screenshots
