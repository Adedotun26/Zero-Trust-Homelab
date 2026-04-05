# Project Overview

This project documents the design and implementation of a zero-trust home lab using pfSense, VLAN segmentation, a managed switch, a multi-SSID wireless access point, OpenVPN with RADIUS-based MFA, and a jump-box-only access model.

## Objectives
- Segment the network into security zones
- Enforce least-privilege communication between VLANs
- Centralize DHCP and DNS on pfSense
- Provide secure remote access with OpenVPN + MFA
- Restrict VPN users to a controlled jump box

## Technologies Used
- pfSense
- Netgear managed switch
- TP-Link access point
- OpenVPN
- FreeRADIUS
- Google Authenticator