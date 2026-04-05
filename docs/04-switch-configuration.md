# Switch Configuration

The managed switch was configured to support VLAN segmentation and uplink trunking to pfSense.

## Key Concepts
- Port 1 used as uplink/trunk to pfSense
- Port 2 used for the access point
- Port 3 used for management/admin laptop
- Port 5 used for the jump box in the Servers VLAN

## VLAN Membership
- VLAN 1 / Management: untagged on management ports
- VLAN 10 / Users: access ports assigned as needed
- VLAN 20 / Servers: jump box access port
- VLAN 30 / IoT: IoT port mapping
- VLAN 40 / Guest: guest traffic isolation

## Purpose
The switch enforces VLAN separation at Layer 2 and forwards inter-VLAN traffic to pfSense for policy enforcement.