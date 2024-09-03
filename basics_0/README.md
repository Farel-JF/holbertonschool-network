# Networking Basics Project

This project covers fundamental networking concepts and practical skills in networking. Each topic will help you understand different aspects of network communication, including models, addresses, protocols, and commands used to manage and troubleshoot networks.

## Table of Contents

1. [OSI Model](#0-osi-model)
2. [Types of Network](#1-types-of-network)
3. [MAC and IP Address](#2-mac-and-ip-address)
4. [UDP and TCP](#3-udp-and-tcp)
5. [TCP and UDP Ports](#4-tcp-and-udp-ports)
6. [Is the Host on the Network](#5-is-the-host-on-the-network)

---

## 0. OSI Model

The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a telecommunication or computing system into seven distinct layers.

- **Layer 1: Physical** - Deals with the physical connection to the network (e.g., cables, switches).
- **Layer 2: Data Link** - Handles data transfer between adjacent network nodes (e.g., MAC addresses).
- **Layer 3: Network** - Manages data routing between devices across different networks (e.g., IP addresses).
- **Layer 4: Transport** - Ensures reliable data transmission between devices (e.g., TCP/UDP).
- **Layer 5: Session** - Manages sessions and controls dialogues between computers.
- **Layer 6: Presentation** - Translates data between the network and application formats.
- **Layer 7: Application** - Interacts with end-user applications (e.g., HTTP, FTP).

**Key Points:**
- The OSI model helps standardize communication across different systems.
- It separates network functionality into seven layers to isolate issues and enhance interoperability.

## 1. Types of Network

Different network types are categorized based on their geographical scope and purpose:

- **LAN (Local Area Network):** Connects devices within a small geographic area, like a home or office. Example: Connecting computers and printers in a single office.
- **WAN (Wide Area Network):** Connects multiple LANs over larger geographic areas, such as cities or countries. Example: The Internet or a company's regional office network.
- **Internet:** A global network of interconnected networks using the TCP/IP protocol suite.

**Key Points:**
- LANs are local and limited in scope, ideal for small geographical areas.
- WANs cover broader geographical areas and are used to connect LANs.
- The Internet is a worldwide WAN that connects various networks together.

## 2. MAC and IP Address

Addresses in networking uniquely identify devices:

- **MAC Address (Media Access Control):** A hardware identifier that uniquely identifies each device on a network. It operates on the Data Link layer (Layer 2) of the OSI model.
- **IP Address (Internet Protocol Address):** A numerical label assigned to devices connected to a network. It operates on the Network layer (Layer 3) of the OSI model and can be IPv4 or IPv6.

**Key Points:**
- **MAC Address:** Unique to the device's network interface card (NIC) and stays constant.
- **IP Address:** Used for locating and identifying devices on a network and can change based on network configuration.

## 3. UDP and TCP

UDP (User Datagram Protocol) and TCP (Transmission Control Protocol) are key transport layer protocols:

- **TCP:** A connection-oriented protocol that ensures reliable and ordered delivery of data. It is slower but guarantees that packets arrive correctly and in order.
- **UDP:** A connectionless protocol that sends packets without ensuring their delivery. It is faster but does not guarantee packet order or delivery.

**Key Points:**
- **TCP** is used where reliability is crucial (e.g., web browsing, email).
- **UDP** is used where speed is important and occasional loss of packets is acceptable (e.g., streaming, gaming).

## 4. TCP and UDP Ports

Ports are used to identify specific processes or services on a networked device:

- **TCP/UDP Ports:** Numbers used to distinguish different processes or network services. Ports range from 0 to 65535.
- **Common Ports:**
  - **22 (SSH):** Used for secure shell access to servers.
  - **80 (HTTP):** Used for unsecured web traffic.
  - **443 (HTTPS):** Used for secured web traffic.

**Key Points:**
- Ports are essential for directing network traffic to the correct service or application.
- Knowing common ports helps in troubleshooting and securing network services.

## 5. Is the Host on the Network

ICMP (Internet Control Message Protocol) is used for error messages and operational information queries in networking:

- **Ping:** A command that uses ICMP to check if a host is reachable and measures the round-trip time for messages sent from the originating host to a destination computer.

**Key Points:**
- **Ping** helps diagnose network connectivity issues by checking the availability and responsiveness of network devices.
- A successful ping confirms the network path to the destination is operational.

---

By understanding these fundamental networking concepts, you will gain insight into how devices communicate over a network, how data is managed and transferred, and how network services are identified and reached.

