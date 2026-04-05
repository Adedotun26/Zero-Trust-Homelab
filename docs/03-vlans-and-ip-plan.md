# VLANs and IP Plan

## VLAN Design

| VLAN | Name | Subnet |
|------|------|--------|
| 10 | Users | 192.168.10.0/24 |
| 20 | Servers | 192.168.20.0/24 |
| 30 | IoT | 192.168.30.0/24 |
| 40 | Guest | 192.168.40.0/24 |
| 55 | Management | 192.168.55.0/24 |

## Management Addresses
- pfSense: 192.168.55.1
- Switch: 192.168.55.151
- Access Point: 192.168.55.11

## VPN Tunnel Network
- OpenVPN tunnel network: 10.99.0.0/24