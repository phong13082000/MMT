# MMT
## 1. Computer Network overview
  
  + Personal Area Network (PAN) is the smallest and the most basic type of network. A PAN is usually made up of a wireless modem, one or several computers, phones, tablets, etc., and resolves around one person in one building. This type of network is typically found in small offices or residences, managed by one person or organization from a single device.

  + Local Area Network (LAN) is one of the most common and simple type of network. LANs connects groups of computers and devices together across short distances, for example within a building or a group of two, three buildings in close proximity, in order to share information and resources. Enterprises typically manage and maintain LANs.

  + Metropolitan Area Network (MAN) is a type of network which is larger than LAN but smaller than WAN, incorporating elements from both types of networks. MANs span an entire geographic area (typically a town or city). Ownership and maintenance is handled by either a singal person or company.

  + Wide Area Network (WAN) connects computers together across longer physical distances, allowing computers and devices to be remotely interconnected over one large network. The Internet is the most basic example of WAN, connecting all computers together around the globe. Due to WAN's vast reach, it is maintained by multiple administrators or the public over one large network.
## 2. OSI
  + Open Systems Interconnection (OSI) model is a conceptual, reference model used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software.
  ![image](https://user-images.githubusercontent.com/84502367/131661582-a5aef6c2-cdfb-4458-9538-36a73e7a820d.png)
### Physical Layer:

The lowest layer of the OSI Model is concerned with electrically or optically transmitting raw unstructured data bits across the network from the physical layer of the sending device to the physical layer of the receiving device. It can include specifications such as voltages, pin layout, cabling, and radio frequencies. At the physical layer, one might find “physical” resources such as network hubs, cabling, repeaters, network adapters or modems.

### Data Link Layer

At the data link layer, directly connected nodes are used to perform node-to-node data transfer where data is packaged into frames. The data link layer also corrects errors that may have occurred at the physical layer.

The data link layer encompasses two sub-layers of its own. The first, media access control (MAC), provides flow control and multiplexing for device transmissions over a network. The second, the logical link control (LLC), provides flow and error control over the physical medium as well as identifies line protocols.

### Network Layer

The network layer is responsible for receiving frames from the data link layer, and delivering them to their intended destinations among based on the addresses contained inside the frame. The network layer finds the destination by using logical addresses, such as IP (internet protocol). At this layer, routers are a crucial component used to quite literally route information where it needs to go between networks.

### Transport Layer

The transport layer manages the delivery and error checking of data packets. It regulates the size, sequencing, and ultimately the transfer of data between systems and hosts. One of the most common examples of the transport layer is TCP or the Transmission Control Protocol.

### Session Layer

The session layer controls the conversations between different computers. A session or connection between machines is set up, managed, and termined at layer 5. Session layer services also include authentication and reconnections.

### Presentation Layer

The presentation layer formats or translates data for the application layer based on the syntax or semantics that the application accepts. Because of this, it at times also called the syntax layer. This layer can also handle the encryption and decryption required by the application layer.

### Application Layer

At this layer, both the end user and the application layer interact directly with the software application. This layer sees network services provided to end-user applications such as a web browser or Office 365. The application layer identifies communication partners, resource availability, and synchronizes communication.

## 2. TCP/IP
![image](https://user-images.githubusercontent.com/84502367/131662330-86e3e011-52e8-4d3e-89dc-6aac13ac69a9.png)
  + The application layer is the scope within which applications, or processes, create user data and communicate this data to other applications on another or the same host. The applications make use of the services provided by the underlying lower layers, especially the transport layer which provides reliable or unreliable pipes to other processes. The communications partners are characterized by the application architecture, such as the client–server model and peer-to-peer networking. This is the layer in which all application protocols, such as SMTP, FTP, SSH, HTTP, operate. Processes are addressed via ports which essentially represent services.
  + The transport layer performs host-to-host communications on either the local network or remote networks separated by routers.[33] It provides a channel for the communication needs of applications. UDP is the basic transport layer protocol, providing an unreliable connectionless datagram service. The Transmission Control Protocol provides flow-control, connection establishment, and reliable transmission of data.
  + The internet layer exchanges datagrams across network boundaries. It provides a uniform networking interface that hides the actual topology (layout) of the underlying network connections. It is therefore also the layer that establishes internetworking. Indeed, it defines and establishes the Internet. This layer defines the addressing and routing structures used for the TCP/IP protocol suite. The primary protocol in this scope is the Internet Protocol, which defines IP addresses. Its function in routing is to transport datagrams to the next host, functioning as an IP router, that has the connectivity to a network closer to the final data destination.
  + The link layer defines the networking methods within the scope of the local network link on which hosts communicate without intervening routers. This layer includes the protocols used to describe the local network topology and the interfaces needed to affect the transmission of Internet layer datagrams to next-neighbor hosts.
Link layer
