Today we are starting with a powercert video on Subnet Mask. 
If you see /30 pertaining to subnet mask two devices (as in servers) are talking to each per Mr. Darryl.
The classless inter-domain routing (/20) is a shorthand way to write the subnet mask. This is where it completely disregards the callful class system of A 255.x.x.x etc.
127.x.x.x is for trouble shooting because it is the host.
169.254.x.x means you don't have internet access because DHCP is not working.
Network Address Translation (NAT) is a service used in routers, translates a set of IP addresses to another set of IP addresses. It helps preserve the limited amount of IPv4 public IP addresses available the world over.
Address Resolution Protocol (ARP) maps ip address to a MAC address on a local network (LAN).
Routers route packets frames are forwarded.
DNS maps domain names to IP addresses
DHCP server issues IP addresses to DNS, Gateway, and IPv4.
arp -a command to view arp table
All Fs FF:FF ... for MAC address is always a BCast/Broadcast
ARP resides in Layer 2 and 3 of the OSI model because it works with MAC addresses and IP addresses.
DHCP server issues IP addresses to DNS, Gateway, and IPv4.
Unicast is 1 to 1, broadcast is to all, multicast is to a group. Streaming is a good example of using multicast/group.
Ping command syntax: ping (ip address or domain name).
IPv6 does not use broadcast. It uses multicast one to many (or group) which looks for FF00::/8 and is equivalent to IPv4 multicast address 224.0.0.0/4
224.0.0.0/4 is group D which we have not dicussed. 
IPv6 uses unicast, multicast, and anycast ( uses one to nearest used by routers). IPv4 uses unicast, broadcast,
Watched Sunny Classroom Video multicast, unicast and anycast video.
Multicast address can never be source address. 
Watched powercert video ipv4(32-bit) vs IPv6 (128-bit hexadecimal address 8 sets of 16 bits).
