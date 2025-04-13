On the 24th of March we covered Lesson 8 Numbering Systems.
Hexadecimal numbering system has 16 symbols, 1-9 and A-F. Binary numbering systems can only have two values typically, 0 and 1: base 2.
Then we reviewed the Binary Numbering system where every digit is represented by Base 2 with different powers from 0 thru 7, e.g., 1(2^0), 2(2^1), 4(2^2), 8(2^3), 16(2^4), 32(2^5), 64(2^6), and 128(2^7).
Then we were introduced to the open systems interconnection reference model.
Network fundamentals: Network protocol is a set of rules. Their functions are addressing(where data messages should go), encapsulation[how data messages are packaged(envelope), network has many different types protocols.
Potocol Data Unit (PDA) are Headers and Payload/dat
The OSI reference model consists of 7 layers. The first layer is the physical layer. Transmission media types are twisted pair, fiber, and coax. Wireless are wavelengths in the air moves data across cables or via wireless frequencies. Devices working at layer 1 are transceiver, repeater, hub, media converter, and modem.
Layer 2 Devices are network interface card (NIC), bridge, switch, wireless access point (WAP). Also, on this layer is the Media Access Control (MAC). Hardware address of source and destination NICs.
Layer 3 is the Network layer responsible for routing messages from one node to another until they reach the destination. Also forwards packets via routers using logical network addresses. Device working at layer 3 is the router.
Layer 4 is the Transport layer which indentifies application data via port numbers. Responsible for transporting payloads from one applicatin to another. Two main protocols are Transmission Control Protocol (TCP) and User Datagram Potocol (UDP). TCP makes a connection with the end host, checks whether data was received, "connection-oriented protocol", and flow control ("windowing"), sequencing, error detect and correction. UDP does not guarantee delivery, will not connect and check whether data is received and connectionless protocol.
Devices working at layer 4 are the load balancer, advanced firewall, intrusion detection system (IDS).
Then we review then remaining 3 layers which are layer 5 (the Session layer), layer 6 (the Presentation layer), and layer 7 (the Application layer).
