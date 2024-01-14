# Networking Basics

## OSI Model
The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a communication system into seven layers. It provides a structure for understanding and designing network protocols. The layers of the OSI model are as follows:

1. Physical Layer: Deals with the physical transmission of data bits over the network medium.

2. Data Link Layer: Handles the reliable transmission of data frames between adjacent nodes on a network.

3. Network Layer: Manages the addressing and routing of data packets across multiple networks.

4. Transport Layer: Ensures the reliable delivery of data between hosts and provides end-to-end error recovery.

5. Session Layer: Establishes, manages, and terminates sessions between applications.

6. Presentation Layer: Translates, encrypts, and formats data for presentation to the application layer.

7. Application Layer: Supports network applications and services for end-users.

## LAN (Local Area Network)
A LAN is a network that connects devices within a limited geographical area, such as a home, office building, or campus. It allows for the sharing of resources, such as files, printers, and internet access, among connected devices. LANs are typically privately owned and offer high data transfer rates and low latency.

## WAN (Wide Area Network)
A WAN is a network that spans a large geographical area, connecting multiple LANs and other networks. It utilizes various communication technologies, such as leased lines, satellites, or internet connections, to enable data exchange between distant locations. WANs are commonly used by organizations to connect their branch offices across different cities or countries.

## Internet
The Internet is a global network of interconnected networks that uses the TCP/IP protocol suite to facilitate communication between devices worldwide. It is a decentralized and public network that allows access to a vast amount of information, services, and resources. The Internet enables services like email, web browsing, file transfer, and real-time communication.

## IP Address

An IP (Internet Protocol) address is a unique numerical identifier assigned to each device connected to a network. It enables devices to send and receive data over the internet or a local network. There are two types of IP addresses:

IPv4 (Internet Protocol version 4): It consists of a 32-bit address expressed in four sets of decimal numbers separated by periods (e.g., 192.168.0.1). IPv4 addresses are limited in number and have been widely used but are being gradually replaced by IPv6.

IPv6 (Internet Protocol version 6): It uses a 128-bit address expressed in eight groups of hexadecimal numbers separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334). IPv6 provides a significantly larger address space to accommodate the growing number of devices connected to the internet.

## localhost
"localhost" is a hostname that refers to the current device or loopback address (IP address 127.0.0.1) itself. It is commonly used to access services running on the same device without going through the network. When a program communicates with localhost, it connects to the loopback interface of the device, allowing internal communication.

## Subnet
A subnet is a division of a larger network into smaller logical networks. It helps in efficient network management, security, and addressing. By defining subnets, administrators can group devices based on their geographic location, department, or any other criteria, enabling better control and organization of network resources.

## IPv6 Adoption
IPv6 was created to address the depletion of IPv4 addresses due to the growing number of devices connected to the internet. IPv6 offers a significantly larger address space and improved features, including better security and auto-configuration. Its adoption allows for the continued growth of the internet and ensures the availability of unique IP addresses for future devices.

## TCP/UDP
TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two commonly used transport layer protocols in the TCP/IP protocol suite.

TCP: TCP provides reliable, connection-oriented communication between devices. It ensures that data packets are delivered in order, without loss or duplication. TCP uses acknowledgments and retransmission of lost packets to provide error-free transmission, making it suitable for applications that require guaranteed delivery, such as web browsing, email, and file transfer.

UDP: UDP is a connectionless, unreliable protocol that does not guarantee delivery or order of data packets. It is faster and more efficient but provides no error recovery. UDP is used for real-time applications, such as video streaming, online gaming, and VoIP (Voice over IP), where speed and low latency are crucial.

## Port
A port is a logical construct used to identify specific processes or services running on a device within a network. Ports are numbered and associated with protocols to facilitate the delivery of data to the correct application. The port number is part of the addressing information used in the transport layer header of a network packet.

## SSH, HTTP, and HTTPS Port Numbers
* SSH (Secure Shell): Port 22

* HTTP (Hypertext Transfer Protocol): Port 80

* HTTPS (Hypertext Transfer Protocol Secure): Port 443

## Network Connectivity Checking
The Ping protocol/tool is often used to check if a device is connected to a network. Ping sends a small packet of data (ICMP Echo Request) to a target device and waits for a response (ICMP Echo Reply). If a response is received, it indicates that the device is reachable and connected to the network. Ping is widely used for network troubleshooting and verifying network connectivity.

## Authors
![GitHub Contributors Image](https://contrib.rocks/image?repo=anacardona0220/holbertonschool-higher_level_programming) Ana Maria Cardona Botero - <a href="https://github.com/anacardona0220" target="_blank"> @anacardona0220</a> :genie_woman:![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=anacardona0220&show_icons=true)
