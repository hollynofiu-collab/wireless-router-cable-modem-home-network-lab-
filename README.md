# wireless-router-cable-modem-home-network-lab

## Project Overview

This project demonstrates the design and configuration of a small home/office network using Cisco Packet Tracer. The topology includes a wireless router, wired clients, wireless clients, a server, and a cable modem connected to a simulated ISP network. The objective of the lab was to configure local network connectivity, wireless access, and WAN connectivity while understanding how a home router integrates LAN and Internet services.

## Network Topology

Devices Used

1 Wireless Router (WRT300N)

1 Cable Modem

1 Coaxial Splitter

1 Server

2 PCs

2 Laptops

Simulated ISP connection.

## Network Design.

LAN Network:

The wireless router provides local connectivity to all devices.

WAN Network:

The cable modem connects the router to the ISP through a coaxial link.

All interfaces were verified to be operational (green link status in Packet Tracer).

## Configuration Performed

1. Wireless Router Configuration

The router was configured with a local LAN address and enabled wireless access for client devices.

Example LAN configuration:

Router IP address: 192.168.0.1

Subnet mask: 255.255.255.0

DHCP service was enabled on the router to automatically assign addresses to client devices.

2. DHCP Configuration

The router distributed IP addresses dynamically to connected hosts.

Example DHCP range:

Start IP: 192.168.0.100

End IP: 192.168.0.149

Clients received:

IP address

Subnet mask

Default gateway

DNS server information

3. Wireless Configuration.

The wireless network was enabled and configured with an SSID.

Example settings:

SSID: HomeLab

Security mode: WPA2-PSK

Passphrase: Configured in Packet Tracer

4. Server Configuration

The server was assigned a static IP address.

Example:

IP address: 192.168.0.60

Subnet mask: 255.255.255.0

Default gateway: 192.168.0.1

The server remained reachable by both wired and wireless clients.

5. WAN Configuration

The wireless router was connected to the cable modem using an Ethernet interface. The cable modem connected to the ISP through the coaxial infrastructure.

The WAN interface obtained connectivity from the ISP side, enabling simulated Internet access.

Screenshots of lab (

