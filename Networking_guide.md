# Networking Basics

## 1. Introduction
Networking is a crucial part of modern technology, connecting computers and devices to share data and resources. Understanding the basics of networking is essential for anyone working in IT, as it forms the foundation for more advanced topics such
as network security, troubleshooting, and system administration.

## 2. What is a Network?
A network is a system of interconnected computers and end-devices that communicate with each other. The most common type is a Local Area Network (LAN), which connects devices within a limited area, such as an office or home. Wide Area Networks (WANs) extend over a larger 
area, connecting LANs across things such as cities. 

## 3. Basic Networking Components
- **Router**: Connects multiple networks and directs data traffic.
- **Switch**: Connects devices within a LAN and forwards data based on MAC addresses.
- **Modem**: Translates digital signals for internet access.
- **Network Cables**: Used for wired connections; common types include Ethernet (Cat5, Cat6).

## 4. - **OSI Model (Open Systems Interconnection Model)**: Is used to break down complex process of network communication into seven seperate layers. 
##Layer 1 (physical) 
- Uses the hardware, such as cables, and switches to transmit raw data.
## Layer 2 (Data Link)
- Relays how data packets are transfered between devices on a network.
## Layer 3 (Network)
- Routes data between networks using IP Addresses
## Layer 4 (Transport) 
- Provides reliable data transfer by breaking up data into smaller packets.
## Layer 5 (Session) 
- Manages and maintains connections between a device.
## Layer 6 (Presentation) 
- Tranfers data into formats that can be read by the application through encryption.
## Layer 7 (Application)
- Where user interaface is which sends and recives data to the user. 


## 5. IP Addresses
An IP address is a unique identifier assigned to each device on a network, enabling communication. IPv4 addresses are 32-bit and displayed as four decimal numbers separated by dots (e.g., 192.168.1.1), while IPv6 addresses use 128-bit and are displayed in hexadecimal digits. 
(e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

## 6. Subnets and Subnetting
Subnets are a way for network administrators to break a large network into smaller, more manageable parts. This helps make the network run more efficiently and securely by limiting broadcast traffic to just the smaller subnet, instead of the whole network. To create subnets, administrators figure out which parts of an IP address represent the network and which parts represent individual devices, then use this information to set up the subnets.

## 7. DNS (Domain Name System)
DNS, is like the internet's "phonebook." It takes user-friendly domain names like www.google.com and translates them into IP addresses, such as 192.0.1.1. This process allows browsers to find and connect to websites so you can browse the web without needing to remember complex strings of numbers. 

## 8. Basic Networking Protocols
- **TCP/IP (Transmission Control Protocol/Internet Protocol)**: The foundational protocol suite for internet communication.
- **HTTP/HTTPS (HyperText Transfer Protocol/Secure)**: Used for transferring data on the web.
- **FTP (File Transfer Protocol)**: A standard network protocol for transferring files between a client and server.
- **ARP (Adress Resolution Protocol)**: A protocol used to map out IP addresses to a physcial MAC address from a local network.
- ##DHCP (Dynamic Host Configuration Protocol)**: This protocol automatically assigns IP addresses and network configurations to devices on a network

## 9. Conclusion
Understaning the fundamentals of networking opens the door to more advanced studies and professional opportunities in IT or any computer related field. By understanding how data is transferred and managed, you’ll be better suited to tackle network troubleshooting and security challenges.
