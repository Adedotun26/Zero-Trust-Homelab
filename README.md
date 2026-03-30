# Zero Trust Homelab
Zero-trust home lab with pfSense VLAN segmentation, OpenVPN MFA, jump-box-only access, and Azure private VM extension.

This project documents the design and implementation of a zero-trust home lab using pfSense, VLAN segmentation, managed switching, multi-SSID Wi-Fi, OpenVPN with RADIUS-based MFA, and a controlled jump-box access model. The project also includes an Azure private VM extension using Azure Bastion.
## Core Features
- VLAN-based network segmentation
- Centralized routing and firewall policy with pfSense
- Managed switch VLAN tagging and access port design
- Multi-SSID access point mapped to VLANs
- Centralized DHCP and DNS through pfSense
- OpenVPN remote access with FreeRADIUS + TOTP MFA
- Jump-box-only access model for least privilege
- Azure private jump box with no public VM exposure
![ChatGPT Image Mar 29, 2026, 11_19_14 PM](https://github.com/user-attachments/assets/1e80a3e2-0191-4334-8e87-cee913e55a44)
