# Enterprise Network Infrastructure

## Overview
This project demonstrates the design, configuration, and verification of a scalable, high-availability enterprise network built entirely on Cisco technologies. The infrastructure spans three sites (Headquarter, Branch Office, Data Center) and implements L2/L3 redundancy, VLAN segmentation, inter-VLAN routing, and comprehensive security features.

## Key Features
- **Scalable IPv4 Addressing** with VLSM
- **First-Hop Redundancy** – HSRP with per-VLAN load balancing  
- **Link Redundancy** – LACP EtherChannel & Rapid PVST+  
- **Inter-VLAN Routing** – SVI (HQ) & Router-on-a-Stick (Branch)  
- **Layer 2 Security** – Port Security, DHCP Snooping, BPDU Guard, DTP disabled  
- **Network Services** – DHCP, DNS, HTTP/HTTPS, SSH  
- **Comprehensive Testing** – End-to-end connectivity, HSRP failover, service validation

## Technologies
IPv4 (VLSM), HSRP, EtherChannel (LACP), Rapid PVST+, PortFast, BPDU Guard  
Inter-VLAN Routing (SVI & Router-on-a-Stick), Static & Floating Routes  
Port Security, DHCP Snooping, DTP Disable, SSHv2, DNS, HTTP/HTTPS

## Contents
- **Enterprise_Network_Project.pdf** – detailed design, configuration steps, verifications, and conclusions
- **Enterprise_Network_Project.pkt** – fully functional simulation
- **Device_configurations/** – folder containing every device configuration in `.txt` format (one file per device)

## How to Use
1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (version 8.2 or later).
2. Clone this repository or download the `.pkt` file.
3. Open the file in Packet Tracer. All configurations are pre-loaded.
4. Refer to the PDF for detailed explanations of each technology and testing instructions.
