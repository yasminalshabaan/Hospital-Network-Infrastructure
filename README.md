# Hospital Network Infrastructure

## Project Overview

This project focuses on designing and managing the network infrastructure of a small hospital spanning three floors.

The network was implemented using Cisco Packet Tracer and was designed to provide reliable communication, efficient routing, wireless connectivity, and scalable network architecture.

## Objectives

- Design a reliable network infrastructure for a multi-floor hospital.
- Configure network devices and IP addressing.
- Implement VLANs for department segmentation.
- Configure wireless connectivity using a Wireless LAN Controller (WLC).
- Assign dynamic IP addresses using DHCP.
- Configure and verify RIPv2 and OSPF routing protocols.
- Implement route redistribution between RIP and OSPF.
- Verify network connectivity and routing.

## Network Components

The topology includes:

- 6 PCs
- 2 Laptops
- 1 Tablet
- 4 IP Printers
- 4 Cisco Switches
- 3 Cisco Routers
- 1 Wireless LAN Controller (WLC)
- 1 Lightweight Access Point
- 1 Server
- UTP Cables
- Serial Cables
- Console Cable

## VLAN Configuration

Three VLANs were configured for different hospital departments:

| VLAN | Department |
|------|------------|
| VLAN 10 | Pharma |
| VLAN 20 | Clinics |
| VLAN 30 | ER |

VLANs were created and switch ports were assigned to the appropriate VLANs.

## Wireless LAN Controller (WLC)

A Wireless LAN Controller was configured to manage wireless connectivity within the network.

The project includes:

- WLC IP configuration
- DHCP configuration
- Wireless LAN configuration
- Lightweight Access Point connection
- Tablet connection to the wireless network

## Routing Protocols

Two routing protocols were implemented:

### OSPF

OSPF was configured on Router0 and Router1 to provide dynamic routing between the required networks.

### RIPv2

RIPv2 was configured on Router1 and Router2 to enable routing between the corresponding networks.

## Route Redistribution

Route redistribution was configured on Router1 to allow routes learned through RIP to be advertised through OSPF and vice versa.

This enables communication between the two different routing domains.

## DHCP

DHCP was configured on the server to provide dynamic IP addressing for network devices. The tablet was configured to obtain its IP address automatically using DHCP.

## Network Verification

The routing configuration was verified using the `show ip route` command on the routers.

Connectivity was also tested using successful ping operations between devices.

## Results

The hospital network successfully met the specified requirements. Routing, VLANs, wireless connectivity, and network communication were implemented and verified.

## Technologies Used

- Cisco Packet Tracer
- VLAN
- DHCP
- Wireless LAN Controller (WLC)
- RIPv2
- OSPF
- Route Redistribution
- IP Addressing
- Network Routing

## Project Files

- `IT Project G51.docx` – Project report and documentation.
- `ITPROJECT1 2.pkt` – Cisco Packet Tracer network topology and configuration.

## Team Members

- Fatima Ahmed Alhanfoosh
- Lojain Talib Alghareeb
- Farah Isa Aljokam
- Yasmin Khalid Alshabaan
- Eman Yassen

## Course Information

**Course:** CIS326 – IT Infrastructure Management  
**Section:** 6F02  
**Group:** 5  
**Topology:** No. 15  
**Supervisor:** Ms. Ruba Mahmoud Ahmed Al-salah  
**Academic Year:** 2024/2025
