# March 24

## Robert Metcalfe and David R. Boggs. "Ethernet".

### Context
- Robert Metcalfe
  - American 20-21st C. Computer scientist
  - 1969 undergrad @ MIT in EE + Industrial Management
  - PhD @ Harvard, failed defense
  - Worked on ARPANet @ MIT while at Harvard, causing tension w/ faculty
  - Position at Xerox PARC
- Created "Ethernet" at Xerox PARC as a form of communication to resolve difficulty of networking (delivery over failure-prone links, hostlie network nodes, faulty hardware)
- Founded 3Com then worked as a VC

### Paper
- Ethernet is "branching broadcast communication system for carrying digital data packets among locally distributed computing stations"
  - Key characteristic is distributed with no central control
  - Coordination of access is distributed b/w transmitting stations
- Distributed computing varies in distribution, the "loose interconnection of previously isolated... large computing systems"
- Recognizes previous work on remote computer networking + multiprocessing (computer-computer interaction)
- Tapped coaxial cables carrying variable-lengh digital packets
  - Was there a limit on packet length? Who established the contract?
- What is statistical arbitration?
- Recongizes the need to accomodate large buildings of personal computers
- Ethernet to carry "bursty traffic" where multiplexing would be inefficient
- Topology is an unrooted tree (only one path between nodes)
- Broadcast packet is packet with destination of zero
- Ethernet is probabilistic; "best efforts" to transmit packets successfully
  - What use cases exist for ethernet? E.g., stock trades would probably be poor.
- Taps and tranceivers
- Carrier - packet passing through a transceiver
- Discusses error detection, packet filtering, collision consensus, and implementation
- Finishes by discussing growth and the scalability of the network, as well as a probability analysis
- Conclusion with emphasis on distributed computing

## Vinton Cerf and Robert Kahn. "A protocol for packet network intercommunication (1974)"

### Paper
- The paper discusses a protocol for sharing resources in a packet switching network, as well as the many considerations required and implementation issues
- Existence of protocols ensure that terminals and computers (which I think can be thought of in modern day terminology as clients and servers) can communicate with one another
- Key-terms:
  - Gateway - interface between networks
  - IPC - interprocess communication! Woohoo! Yay systems!
  - Hosts
  - Processes
  - Packet switches
  - Packet switching subnets
  - Cyclades
  - Senders / receivers
  - ARPANET
- Discusses TCP (assumes existence), addressing, porting, segmentation, reassembly / sequencing, retransmission / duplicate detection, flow control, I/O handling, connections, associations,
- Incredibly cool to see the origin of something that is taken for granted in everyday life.
