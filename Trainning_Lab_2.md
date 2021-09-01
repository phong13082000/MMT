# MMT
## 1. Physical layer
### a. Overview
  + The physical layer is the lowest layer. This layer provides mechanical, electrical and other functional aids available to enable or disable, they maintain and transmit bits about physical connections. This may for example be electrical signals, optical signals (optical fiber, laser), electromagnetic waves (wireless networks) or sound. The techniques used are called technical transmission process. Devices and network components that are associated with the physical layer, for example, the antenna and the amplifier, plug and socket for the network cable, the repeater, the stroke, the transceiver, the T-bar and the terminator are (Terminator).

  + Its physical layer digital bit transfer is accomplished on a wireline or cable-free transmission path. The sharing of a transmission medium can be carried out on this layer by static multiplexing and dynamic multiplexing. This requires not only the specifications of certain transmission media (for example, copper cable, fiber optic cable, power grid) and the definition of connectors further elements. Furthermore, it must be resolved at this level, in what way a single bit to be transmitted.

  + This means the following: In computer networks today information is generally transmitted in the form of bit or symbol sequences. In copper cables and radio transmission, however, are modulated high frequency electromagnetic waves, the information carrier, in the optical waveguide light waves of a certain wavelength or different. The information carrier know no bit strings, but can take a lot more different states than just 0 or 1. For each type of transmission must therefore encoding are defined. That is due to the specification of the physical layer of a network.

  + Typical hardware on this layer: repeaters, hubs, cables, plugs,...
### b. Services
  + Bit-by-bit or symbol-by-symbol delivery
  + Modulation
  + Line coding
  + Bit synchronization
  + Start-stop signalling
  + Circuit switching
  + Multiplexing
  + Carrier sense and collision detection
  + Physical network topology, like bus, ring, mesh or star network
  + ...
## 2. Data link layer
### a. Overview
  + MAC; VLAN; Encapsulation into frames
  
  + The object of the data link layer (also section link layer, connection level, procedure level) is to ensure a reliable, that is largely error-free transmission and to control access to the transmission medium. The purpose of dividing the Bitdatenstromes in blocks - as frames or frame designated - and the addition of checksums as part of the channel coding. So bad blocks are detected by the receiver and either discarded or even corrected; a renewed request discarded blocks sees this layer but not before.
  
  + A "flow control" makes it possible that a receiver dynamically controls the speed with which the other side must send blocks. The international engineering organization IEEE saw the need to regulate for local networks also competing access to a transmission medium, which is not foreseen in the OSI model.
  
  + Common hardware on this layer: Bridge, Switch (Multiport bridge)
### b. Services
  + Encapsulation
  + Frame synchronization
  + Logical link control (Error & Flow control)
  + Media access control (MAC, LAN switching, Physical addressing, QaS, VLAN, ...)
  
## 3. Network layer
### a. Overview
  + IPv4/v6; RIP; QoS

  + The network layer (also packet level) provides a defined benefit services for switching connections and packet-oriented services for the relaying of data packets. The data transmission in both cases will go over the entire communication network and includes the route search (routing) between the network nodes. Because not always a direct communication between the sender and the target is possible, packets must be forwarded by nodes that are on the way. Next mediated packets do not reach the higher layers, but are provided with a new intermediate target and sent to the next node.

  + The main tasks of the network layer is one of providing cross-network addresses, the routing and the construction and updating of routing tables and the fragmentation of data packets. But the negotiation and ensure a certain quality of service falls within the remit of the network layer.
### b. Services
  + Connection model
  + Host addressing
  + Message forwarding
