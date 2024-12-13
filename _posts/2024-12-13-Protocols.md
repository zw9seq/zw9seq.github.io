---
title: Network Protocols
date: 2024-12-13 10:38:00 +0800
categories: [Linux_Basics]
tags: [protocols]
description: Review of the most common network protocols.
#media_subpath: /path/to/media/
#pin: true
---

## Transmission Control Protocol (TCP)
- **Description**: Connection-oriented protocol that guarantees packet delivery.
- **Features**:
  - Flow control
  - Error control
  - Data segmentation

## Internet Protocol (IP)
- **Description**: Fundamental protocol for communication in networks.
- **Versions**:
  - IPv4: 32 bits, supports approximately 4.3 billion addresses.
  - IPv6: 128 bits, supports an virtually unlimited number of addresses.
- **Features**:
  - Packet routing
  - Data fragmentation

## User Datagram Protocol (UDP)
- **Description**: Connectionless protocol used for applications that require speed.
- **Features**:
  - No delivery guarantee
  - No flow control or error control
  - Ideal for streaming and online gaming

## Hypertext Transfer Protocol (HTTP/HTTPS)
- **Description**: Protocol used for transferring text and multimedia files on the web.
- **Differences**:
  - HTTP: No encryption
  - HTTPS: Encrypted with TLS/SSL for better security.

## File Transfer Protocol (FTP/SFTP)
- **Description**: Protocol for transferring files between systems.
- **Versions**:
  - FTP: No encryption
  - SFTP: Encrypted with SSH, more secure.

## Simple Mail Transfer Protocol (SMTP)
- **Description**: Protocol used for sending emails.
- **Features**:
  - Text-oriented
  - Works in combination with IMAP or POP3 for receiving emails.

## Post Office Protocol (POP3/IMAP)
- **Description**: Protocols used for receiving emails.
- **Differences**:
  - POP3: Downloads emails and deletes them from the server.
  - IMAP: Syncs emails, allowing access from multiple devices.

## Dynamic Host Configuration Protocol (DHCP)
- **Description**: Protocol that dynamically assigns IP addresses to devices on a network.
- **Features**:
  - Reduces manual configuration
  - Temporary IP address allocation

## Address Resolution Protocol (ARP)
- **Description**: Protocol that translates IP addresses to MAC addresses.
- **Features**:
  - Operates at the data link layer
  - Facilitates communication within a local network.

## Internet Control Message Protocol (ICMP)
- **Description**: Protocol used to send error and operational messages.
- **Features**:
  - Used by tools like `ping`
  - Reports on host availability and network problems.

## Local Area Network Protocol (Ethernet)
- **Description**: Network protocol that defines how data is transmitted over cables in LAN networks.
- **Features**:
  - Supports multiple topologies
  - Uses MAC addresses to identify devices on the network.

## Point-to-Point Tunneling Protocol (PPTP)
- **Description**: Protocol used to create VPN connections.
- **Features**:
  - Easy to configure
  - Less secure than other VPN protocols.

## Layer 2 Tunneling Protocol (L2TP)
- **Description**: Tunneling protocol used in combination with IPsec for enhanced security.
- **Features**:
  - Does not provide encryption by itself
  - Uses multiple layers to improve security.

## Network Congestion Control Protocol (TCP Vegas)
- **Description**: A variation of TCP focused on congestion control.
- **Features**:
  - Detects congestion before it occurs
  - Improves performance in congested networks.

## Generic Routing Encapsulation Protocol (GRE)
- **Description**: Protocol used to encapsulate packets from different protocols.
- **Features**:
  - Facilitates the creation of tunnels in IP networks
  - Does not provide encryption.

## Internet Protocol Security (IPsec)
- **Description**: Protocol used to secure communications in IP networks.
- **Features**:
  - Provides authentication and encryption
  - Can be used in transport or tunnel mode.
