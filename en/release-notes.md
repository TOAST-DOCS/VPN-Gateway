<!-- machine_translated: true -->

<!-- pre-align:aligned sig=e5874fb903db -->

## Network > VPN Gateway(Site-to-Site VPN) > Release Notes

### November 25, 2025

#### Added Features

* When a Transit Hub is connected to a VPC that has a VPN connection, VPN communication with the On-premises network is also supported from VPCs in other projects connected via the Transit Hub. (An additional VPN connection must be created for the connected subnet range.)

### August 26, 2025

#### Added Features

* v2 has been released.
* When a VPN gateway is created, a local gateway address is assigned and can be viewed in the Console.
* Multiple peer gateway connections can be configured from a single VPC.
* Within the same project, connections from multiple VPCs to a single peer gateway can be configured.
* IKE v2 connections are supported.
* VPN connections between regions where the VPN gateway service is available are supported (the device must be set to Fortinet - Fortigate Series).
* With the release of v2, creation of new v1 VPN gateways is restricted.

### August 27, 2024

#### Added Features

* Added support for Diffie-Hellman groups 14, 15, 16, 17, 18, 19, 20, 21, 27, and 28.

### May 28, 2024

#### Added Features

* Added Cisco - Firepower 1000 Series to the supported peer gateway devices.

### August 29, 2023

#### Added Features

* Added the VPN Gateway feature to the Korea (Pangyo) region.

### May 24, 2022

#### Added Features

* [Korea Pyeongchon Region] Added the VPN Gateway feature.