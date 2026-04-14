# WBMUD Enterprise Network & Security Lab

## My information
- Name: Nada Alaiban
- Course: IT 520
- Lab 4.1 – WBMUD Enterprise Network & Security Lab

## Lab Overview
This project focuses on designing and securing a segmented enterprise network for the Winslow Bay Municipal Utility District (WBMUD). The network is divided into IT, OT, Remote Pump Station, and DMZ segments.

The goal of this lab is to apply OSI model concepts, configure Layer 1–3 network connectivity, and analyze protocol security at Layers 4–7.

## Network Design
The network includes the following segments:
- IT Operations (10.1.10.0/24)
- OT Network (192.168.50.0/24)
- Remote Pump Station (172.16.5.0/24)
- DMZ Attacker Node (203.0.113.100)

Routers are connected using serial links, and static routing is configured to allow communication between all segments.

## Evidence Included
This repository contains:
- Full topology screenshot
- MAC address table screenshot
- Router interface configuration (show ip interface brief)
- Routing table (show ip route)
- Connectivity verification (ping tests from IT workstation)
- HTTP and HTTPS access screenshots
- SSH remote access screenshot

## Security Analysis
The lab also includes analysis of:
- TCP vs UDP
- HTTP vs HTTPS
- SSH vs Telnet

These protocols were evaluated based on their security features and their role in protecting enterprise networks.

## Conclusion
This lab helped demonstrate the importance of network segmentation, routing, and secure protocols in critical infrastructure environments. It also improved understanding of OSI layers and real-world network security practices.
