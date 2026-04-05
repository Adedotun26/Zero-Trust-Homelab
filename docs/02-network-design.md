# Network Design

The home lab was designed around a zero-trust model where network segments are separated by function and access is granted only when explicitly required.

## Core Components
- ISP router providing upstream internet connectivity
- pfSense firewall as the central routing and security device
- Managed switch for VLAN tagging and access port assignment
- Multi-SSID access point for wireless VLAN mapping
- Jump box inside the Servers VLAN for controlled administrative access

## Design Principles
- No flat network
- Explicit firewall policy
- Least privilege after authentication
- Centralized DHCP and DNS through pfSense