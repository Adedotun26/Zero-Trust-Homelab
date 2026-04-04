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
- https://github.com/Adedotun26/Zero-Trust-Homelab/blob/main/40325a9a-e897-4769-859a-fef200dfb1ef.png
- 
