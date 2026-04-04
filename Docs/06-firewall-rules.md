# Firewall Rules

pfSense was used to enforce inter-VLAN access control and least-privilege policy.

## Key Security Goals
- Management network isolated
- IoT and Guest networks restricted
- Servers VLAN protected
- VPN users restricted after authentication

## Policy Model
- Allow only required traffic
- Deny unnecessary east-west movement
- Restrict management access to the MGMT VLAN

## Zero-Trust Principle
Authentication alone does not grant trust. Access is still controlled by firewall policy after VPN login.