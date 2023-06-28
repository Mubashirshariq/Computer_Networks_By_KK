# COMPUTER NETWORKS BY KK

# what is computer network and internet

computers connected to each other is called as computer network and computer networks connected to each other is called internet;

first network was created in USA namely Arpanet which connected the computers of four universities MIT,stanford etc. and the protocol used was TCP protocol.the www was created by tim burner .world wide web is where all the resources web page stuf there.

## Protocols

A protocol is the set of rules and regulation that how data and the all the stuff is tranferred between the networks;

### Types of Network Protocols

- TCP: Transmission control protocol

In this protocol the data  should reach the destination with full security and without loosing a single bit of data

- UDP:User datagram protocol

In this protocol we are not worried about the data whether we are loosing some amount of data or not.e.g,video conferencing

- HTTP:Hypertext Tranfer Protocol

This is used by web browser.when a client sends a request to server and server sends back the response all these things comes in HTTP.

---

### IP ADDRESS

IP Addresses: An Internet Protocol (IP) address is **a unique numerical identifier for every device or network that connects to the internet**. Typically assigned by an internet service provider (ISP), an IP address is an online device address used for communicating across the internet.

1. Local IP Addresses: A local IP address is an identifier assigned to a device connected to a local network. Local IP addresses are typically used for communication within a local network and are not visible outside of the network. Local IP addresses can be assigned manually or automatically using a protocol such as DHCP (Dynamic Host Configuration Protocol).

- On the other hand, a global IP address is a unique identifier assigned to a device that is connected to the internet. This IP address is assigned by the internet service provider (ISP) and is used to communicate with devices outside of the local network. Global IP addresses can be static or dynamic, depending on the service provider. Static IP addresses remain the same over time, while dynamic IP addresses may change periodically.
- for example when a router is connected to various devices it has global ip address and it assigns local ip addresses to the devices connected to it by  protocol and when the response comes back from the  server the now the router decides which device has made this request it does this by NAC(Network Access Translator).

### PORTS

> But the thing is ip address determines which computers requested the data but how does the computer know which application requested the data .Cool there are ports which determine which app made the request.
> 

- All the HTTP stuff happens on port 80.
- 0-123 ports are reserved like  http .
- 124-49152 are also reserved but they are reserved for some specific application like mongo db has a reserved port of 27017 and sql has 1433.

## Types of Network

- LAN(Large Area Network):Small House networks ,offices,campus etc.we can connect to a LAN by wifi,ethernet cables etc.
- MAN(metropolitan area network): Across a city
- WAN(wide area network):Across countries.Optical fibre cables are used.there are two terms associated with WAN
1. SONET

SONET (Synchronous Optical Network) is a high-speed networking technology that is used to transmit data over long distances. It is typically used for connecting WANs and is commonly used by telecommunications companies and Internet service providers.

In SONET, data is transmitted in frames called synchronous transport signals (STSs). Each STS can carry multiple virtual circuits (VCs) and can transmit data at speeds of up to 10 Gbps.

One of the benefits of SONET is its reliability. It is designed to provide high availability and can quickly detect and recover from network failures. However, it can also be an expensive technology to implement and maintain.

### 

1. Frame Relay

Frame Relay is a WAN technology that works by using virtual circuits (VCs) to transmit data between network devices. This technology is widely used for connecting LANs across large areas.

In Frame Relay, data is transmitted in small units called frames. Each frame contains a header, which contains information about the virtual circuit being used and how to route the frame through the network, and a payload, which contains the actual data being transmitted.

One of the benefits of Frame Relay is that it is a cost-effective way to transmit data over long distances. However, it is also a relatively slow technology compared to newer WAN technologies such as MPLS.

## Router/Modem

A router is a device that forwards data packets between computer networks, creating an overlay internetwork. A router is connected to two or more data lines from different networks. When a data packet comes in one of the lines, the router reads the address information in the packet to determine its ultimate destination. Then, using information in its routing table or routing policy, it directs the packet to the next network on its journey. Modems, on the other hand, are devices that modulate and demodulate signals between digital and analog signals that are used for communication between computer devices over telephone lines or other wired or wireless networks.

## Structure of Network

### OSI Model

The OSI (Open Systems Interconnection) model is a conceptual model that describes the communication functions of a telecommunication or computing system. The model was developed by the International Organization for Standardization (ISO) and provides a framework for understanding how data is transferred between different devices on a network.

The OSI model is divided into seven layers, each of which represents a specific stage in the communication process. These layers are:

1. **Physical layer**: This layer is responsible for the physical transmission of data between devices. It defines the electrical and physical specifications for devices, cables, and [connectors.](http://connectors.it)
2. **Data link layer**: This layer is responsible for the reliable transmission of data between devices over a physical link. It is responsible for error detection and [correction.it](http://correction.it) adds  mac addresses to the data pack calls it like a frame and pushes that frame like transport  that frame.
3. **Network layer**: This layer is responsible for the creation, maintenance, and termination of connections between devices. It is responsible for routing data between different networks.Router lives [here.it](http://here.it) assigns the ip address of sender and reciever to the data packet making it ip packet.
4. **Transport layer**: This layer is responsible for the reliable transmission of data between devices. It is responsible for error detection, correction, and flow [control.](http://control.It)Data segmentation is also done in this [layer.Data](http://layer.Data) is segmented into small chunks with source and destination address and also have sequence numbers.
5. **Session layer**: This layer is responsible for establishing, maintaining, and terminating sessions between devices. It is responsible for managing the communication sessions between devices.
6. **Presentation layer**: This layer is responsible for the presentation of data to the application layer. It is responsible for data translation, encryption, and [decryption.](http://decryption.it)It converts data like pdfs into bits.
7. **Application layer**: This layer is responsible for providing services to applications. It is responsible for managing user interfaces, file transfer, and messaging services.

Each layer of the OSI model interacts with the layer above and below it, providing a framework for the transfer of data between devices on a network.

## TCP/IP Model

The TCP/IP model is a protocol model used in computer networking. It stands for Transmission Control Protocol/Internet Protocol and is made up of four layers:

1. **Application layer**: This layer is responsible for providing services to applications. It is responsible for managing user interfaces, file transfer, and messaging services.
2. **Transport layer**: This layer is responsible for the reliable transmission of data between devices. It is responsible for error detection, correction, and flow control. Data segmentation is also done in this layer. Data is segmented into small chunks with source and destination address and also have sequence numbers.
3. **Internet layer**: This layer is responsible for routing data between different networks. It assigns the IP address of sender and receiver to the data packet making it an IP packet.
4. **Network access layer**: This layer is responsible for the physical transmission of data between devices. It defines the electrical and physical specifications for devices, cables, and connectors.

The TCP/IP model is used in the Internet and other networks to facilitate communication between devices. It is similar to the OSI model but has fewer layers.

### Deep dive into Layers

### Application Layer

- Users interact with this layer.
- whatsapp,browsers etc
- Protocols
- Client server infrastructure

## Client Server architecture

Every website has two parts client and server.clients are us who are using the website and server is where we are sending our [request.](http://request.In)There is data center which consists of lot of servers and to which every computer is connectes.

## Peer To Peer architecture

IN this architecture there is no central server or something in this every computer connects to the other computer so every computer can be called as a client and a server.e.g torrent

## Protocols

### web protocols

- Tcp/iP protocol
    1. HTTP(Hypertext transfer  protocol)HTTP, in full **HyperText Transfer Protocol**, standard application-level protocol used for exchanging files on the World Wide Web.
    2. DHCP(Dynamic hosting control Protocol) it is used assign local ip address to the devices.
    3. FTP(File transfer protocol) it is used to send the files.
    4. SMTP(simple mail transfer protocol) it is used to send the email
    5. POP3(Post Office Protocol) and the imac are the most commonly used protocol for receiving [email](https://www.techtarget.com/whatis/definition/e-mail-electronic-mail-or-email) over the internet.
    6. The SSH protocol (also referred to as Secure Shell) is **a method for secure remote login from one computer to another through terminal**.
    7. VNC  Virtual Network Computing (***VNC***) is a graphical desktop-sharing protocol
- Telnet is **a network protocol used to virtually access a computer and to provide a two-way, collaborative and text-based communication channel between two machines.port 23**
- UDP:User datagram protocol

In this protocol we are not worried about the data whether we are loosing some amount of data or not.e.g,video conferencing

### Program/Process/Thread

### Program/Process/Thread

- A program is a set of instructions that a computer follows to perform a particular task.e.g whatsapp
- A process is an instance of a program that is being executed by the computer. It has its own memory space, system resources, and state.e.g, sending a message like that.
- A thread is a unit of execution within a process. It shares the same memory space and system resources as the process it belongs to, but has its own execution state.

Threads are used to perform multiple tasks simultaneously within a single process. This allows for more efficient use of system resources and can improve the performance of applications that require multitasking.

Processes, on the other hand, are used to run multiple programs simultaneously. Each program runs as a separate process, with its own memory space and system resources.

Programs, processes, and threads are all important concepts in computer science and are used extensively in the development of software and operating systems.

### Sockets

A socket is an endpoint of a two-way communication link between two programs running on a network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number. There are two types of sockets: client sockets and server sockets. A client socket is used to connect to a server socket, while a server socket is used to listen for incoming client connections. Sockets are an important concept in computer networking and are used extensively in the development of network applications.

Ephemeral ports are temporary ports used by the operating system for outbound connections.This is used for identifying multiple instances of  an application like the different tabs. These ports are assigned dynamically and are typically used for short-lived connections. The range of ephemeral ports varies depending on the operating system and can be configured by the system administrator. On most systems, ephemeral ports are assigned from a range of port numbers between 49152 and 65535.

### HTTP

this is client server protocol and it tells us how the client  requests the data from server and how the servers sends the response to the server.This is an application layer protocol and every application layer protocol needs a transport layer [protocol.](http://protocol.so)So Http uses TCP inside it because tcp makes sure that data is transferred and everything. it does not store stata it is  a stateless protocol. 

### Cookies

since we know whenever we login to web application in a web browser when we close it we will not be logged out but we are told that http is stateless protocol that means it does not save any state the answer to that is cookies.

Whenever we login to the web app for the first time a cookie(a unique string) is set and whenever we try to visit the app other time cookie is sent to the server in the request header and server looks in its database and will let you login if u are in its database.

### How Email Works

Application layer protocols

1. SMTP(simple mail transfer protocol): For sending mails.
2. POP3(Post office protocol): For receiving mails.

It uses TCP protocol for transfer layer.

### DNS(Domain Name System)

Basically domain names are mapped to Ip addresses so for example whenever we go to [google.com](http://google.com)

DNS service is used to find the ip addresses of  google servers.

## Transport Layer

It is responsible for transport of data from a network to a device.The transport of data from a network to network is done by network layer.

for exampler a sender is sending an email,video,file to the reciever then there  is  a multiplexer at the sender  end and demultiplexer at the reciever [end.Here](http://end.Here) arises a question how does a file know which application it has come from and to which application it should be send this thing is done by transport layer it assigns the socket port numbers by which it can easily deterime which applciation to go.

Transport also takes care of  congestion control.Congestion control algorithms are written in TCP.

### Checksums:

whenever the data is send by the sender then the checkSum is calculated with this data this checksome remains with the data throughout the network layer and when it reaches the reciever it calculates the checksum again if this checksum didn’t match to the earlier one then there is something wrong in the data.

### Timers

TCP uses a time out timer **for retransmission of lost segments**. Sender starts a time out timer after transmitting a TCP segment to the receiver. If sender receives an ACK before the timer goes off, it stops the timer. If sender does not receives any ACK and the timer goes off, then TCP Retransmission occurs.

## Deep Dive into Transport Control protocols

### UDP(User Datagram Protocol):

1. Data may or may not be delivered.
2. Data may change.
3. Data may not be in order.

### TCP/IP protocol:

1. It is a transport layer protocol
2. Application layer sends lots of raw data.Tcp segments this data divide it into [chunks](http://chunks.it) and headers. It may also collect data(if it is divided into more chunks by network layer)
3. congestion control
4. it takes care of :
1. when data does not arrive and maintains the order of data

## Network Layer

- NOTE🤌  In transport layer data is in the form of segments,in network layer data is in the form of packets and in data link layer data is in the form of frames.

Here we work with routers.

### Routing and Forwarding tables

The routing table contains the path routing information, while the forwarding table contains the port information. The main difference between the routing and forwarding tables is that routing is used for routing the traffic, while forwarding is used for forwarding the data to the appropriate destination port.

### Control Plane

The control plane is **the part of a network that controls how data packets are forwarded** — meaning how data is sent from one place to another. The process of creating a routing table, for example, is considered part of the control plane.

Routers are Nodes and  links are the edges. There are two types of routings

1. Static Routing;In this routing addresses are added manually 
2. Dynamic Routing: This will evolve automatically when there is a change in the network.

It uses shortest path finding algorithms such as dijsktra,bellman ford types of algorithms.

- Protocols in the network layer is IP(internet protocol)

### IP(Internet Protocol)

It defines a device ,network, node uniquely.

IPV4:32 bits ,4 words(2 Pow(32) different numbers possible).

IPV6:128 bits(future)

 

- Subnet Masking

What is subnetting masking?

[https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPywhTfN4pvPGNpmYcEHXIbntffKVLNYBXzZ2sg30yEQ&s](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPywhTfN4pvPGNpmYcEHXIbntffKVLNYBXzZ2sg30yEQ&s)

A subnet mask is **a 32-bit number created by setting host bits to all 0s and setting network bits to all 1s**. In this way, the subnet mask separates the IP address into the network and host addresses.

---

- MIDDLE BOXES:

A middlebox is **a computer networking device that transforms, inspects, filters, and manipulates traffic for purposes other than packet forwarding**. Examples of middleboxes include firewalls, network address translators (NATs), load balancers, and deep packet inspection (DPI) boxes.e.g 

firewalls.

- FireWalls:

There are two types of Firewalls  one is that is connected with global network and other one which is connected to your local network.

it filters the ip packets based on certain rules like port Nos to block,modify packets etc.f

Stateful and stateless firewalls largely differ in that **one type tracks the state between packets while the other does not**. Otherwise, both types of firewalls operate in the same way, inspecting packet headers and using the information they contain to determine whether or not traffic is valid based on predefined rules.

- NAT

**Network address translation** (**NAT**) is a method of mapping an IP [address space](https://en.wikipedia.org/wiki/Address_space) into another by modifying [network address](https://en.wikipedia.org/wiki/Network_address) information in the [IP header](https://en.wikipedia.org/wiki/IP_header) of packets while they are in transit across a traffic [routing device](https://en.wikipedia.org/wiki/Router_(computing)).

## Data Link layer

he data link layer receives the information in the form of packets from the Network layer, it divides packets into frames and sends those frames bit-by-bit to the underlying physical layer.

# Functions of the Data-link Layer:

![https://media.geeksforgeeks.org/wp-content/uploads/20211215152700/DatalinkLayer-660x335.png](https://media.geeksforgeeks.org/wp-content/uploads/20211215152700/DatalinkLayer-660x335.png)

**1. Framing:** The packet received from the **[Network layer](https://www.geeksforgeeks.org/network-layer-services-packetizing-routing-and-forwarding/)** is known as a frame in the Data link layer. At the sender’s side, DLL receives packets from the Network layer and divides them into small frames, then, sends each frame bit-by-bit to the **[physical layer](https://www.geeksforgeeks.org/physical-layer-in-osi-model/)**. It also attaches some special bits (for error control and addressing) at the header and end of the frame. At the receiver’s end, DLL takes bits from the Physical layer organizes them into the frame, and sends them to the Network layer.

**2. Addressing:** The data link layer encapsulates the source and destination’s **[MAC address](https://www.geeksforgeeks.org/introduction-of-mac-address-in-computer-network/)**/ physical address in the header of each frame to ensure node-to-node delivery. MAC address is the unique hardware address that is assigned to the device while manufacturing.

---

                                                                  The End