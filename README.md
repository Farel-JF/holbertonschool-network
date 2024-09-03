# holbertonschool-network

In this project, you will learn about basic networking concepts, including the OSI model, different types of networks (LAN, WAN), the Internet, IP addresses, TCP/UDP protocols, and tools/protocols used for network connectivity checks. The knowledge gained will help you understand how devices communicate over networks and the Internet.

Learning Objectives
By the end of this project, you should be able to explain the following concepts:

1. OSI Model
What it is: The OSI (Open Systems Interconnection) model is a conceptual framework used to understand network interactions in seven layers. It helps standardize networking protocols to allow diverse communication systems to interact.

How many layers it has: The OSI model has 7 layers.

How it is organized: The OSI model layers are:

Physical Layer: Deals with the physical connection between devices (cables, switches).
Data Link Layer: Handles the reliable transmission of data across a physical network link.
Network Layer: Manages the delivery of packets, including routing through different routers.
Transport Layer: Provides reliable data transfer services to the upper layers.
Session Layer: Manages and controls the connections between computers.
Presentation Layer: Translates data between the application layer and the network format (encryption, compression).
Application Layer: Closest to the end-user, facilitating network services like email, file transfer, and web browsing.
2. LAN (Local Area Network)
Typical usage: LAN is used to connect computers within a limited area like a home, school, or office building.

Typical geographical size: A LAN typically covers a small geographical area, usually within a single building or campus.

3. WAN (Wide Area Network)
Typical usage: WAN is used to connect computers over large geographical areas, such as cities, countries, or even continents.

Typical geographical size: A WAN covers a large geographical area, often spanning multiple cities, regions, or countries.

4. The Internet
What it is: The Internet is a global network of interconnected computers that communicate via standardized protocols to exchange information.
5. IP Address
What it is: An IP (Internet Protocol) address is a unique identifier assigned to each device connected to a network that uses the Internet Protocol for communication.

What are the 2 types of IP address:

IPv4: A 32-bit address scheme allowing for over 4 billion unique addresses (e.g., 192.168.1.1).
IPv6: A 128-bit address scheme designed to accommodate the growing number of devices on the Internet, allowing for a significantly larger number of unique addresses (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).
6. Localhost
What it is: localhost refers to the standard hostname given to the address of the loopback network interface, typically used to refer to the local computer. Its IP address is 127.0.0.1 for IPv4 and ::1 for IPv6.
7. Subnet
What it is: A subnet (short for "subnetwork") is a logically visible subdivision of an IP network. The practice of dividing a network into two or more networks is called subnetting.
8. Why IPv6 was created
Reason: IPv6 was created to address the exhaustion of IPv4 addresses and to introduce improved features such as simplified packet headers, better support for multicasting, and enhanced security.
9. TCP/UDP
What are the 2 mainly used data transfer protocols for IP: TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).

What is the main difference between TCP and UDP: TCP is connection-oriented, meaning it establishes a connection before transmitting data, ensuring reliable and ordered delivery. UDP is connectionless, meaning it sends data without establishing a connection and does not guarantee reliable delivery.

10. Port
What it is: A port is a logical endpoint in a network that is used for communication between devices. It is associated with an IP address of a host and the type of protocol used for communication.

Memorize these port numbers:

SSH: 22
HTTP: 80
HTTPS: 443
11. Tool/protocol used to check if a device is connected to a network
Tool/protocol: ping is commonly used to check the connectivity between devices on a network. It sends ICMP (Internet Control Message Protocol) Echo Request messages to the target host and listens for Echo Reply messages.
Requirements
To complete this project, ensure that you adhere to the following requirements:

Use allowed text editors: vi, vim, emacs.
Bash script files should be interpreted on Ubuntu 20.04 LTS.
End all your files with a new line.
Include a mandatory README.md file at the root of the project folder.
Ensure all Bash script files are executable.
Your Bash scripts must pass shellcheck without errors.
The first line of all Bash scripts should be #!/usr/bin/env bash.
The second line of all Bash scripts should be a comment explaining what the script does.
