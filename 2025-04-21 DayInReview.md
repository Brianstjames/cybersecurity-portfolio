New subject today is routing. Lesson 5.1 Routing Technologies. All activity is located in leyer 3 and 2. 
Data link layer has mac address, ethernet, nic switch , access point, ethernet, "Frame(s)".
layer 3 ipv4 and 6, routing router, info called packets.
APIPA kicks in (169.254.x.x) if DHCP server doesn't work.
How does one router know about the other (R1 to R2)? This happens at layer 3 network. Out-of-band configuration is manual and static.
Router rules for dynamism is audtomatic which occurs at the network layer. In the TCP/IP worl we use the MAC and IP addresses. Mac addrss in glabalyy uique id for your device.
Ip adresses can change. Mac address tells who you are, Ip addreess tells where.
Routers have routing tables which is key. The most specific route wins.
Route entries and codes. First hop redundancy protocal (FHRP).
Storage: magnetic, ssd, hybrid and interfaces are pata scii, sata, nvme/m.2, and usb.
Sunny video static vs dynamic routing & routing metrics. 
Router has at least 2 network interface cards. Routers communicate using routing packets via dynamic configuration.
Static routing is used where security is high because the administator has more control and is reliable.
dynamic routing is using algorithms to automatically determine the best path but complex and is more flexible and resilient.
Routing metrics are values ised by routers to dertmine the bes path to a destination: hop count, bandwith/cost, etc.
Classification of Routing Protocols = classification of routing protocols. BGP = internet and routing. Main one we are focused on right now.
Defining how a packet gets to its destination via routers by taking off the source and destination mac header and trailer bc they stay local.
Address Resolution protocol maps an IP address (logical/layer 3) to a MAC address (physical/layer 2) on a local network
Packet forwarding: receive the packet, examine the packet, consult the routing table, make a forwarding decision.
Sunny classroom video about classification of routing protocols and distance vector protocols.
Routers using Link-state protocol sends router packets to every router for their tables to build its table.
Distance vector protocol sends router packets to neighbor only to build routing table.
Border gateway protocol BGP. Routing protocol: Distance Vector=RIP, IGRP neighbor, rumor, second hand, hop. Link-state: metrics are full, actual, not rumor, hop, delay,. Hybrid example EIGRP.


