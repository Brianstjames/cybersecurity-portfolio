Module 9 Network Configuration. Manage network settings. Network settings are configured manually and dynamically.
Manual configuration users sets IP information on each system one at a time: static.
Dynamic configuration -IP configuration is automatically assigned using Dynamic Host Configuration Protocol (DHCP).
The command ip will allow one to view the current IP addressing information for each NIC. It also shows IP address, subnet mask, broadcast ID, MAC address, basic performance information, and NIC name.
The ip command replaces ifconfig. 
Dynamic IP addressing (DHCP Server) service contains pools of IP addresses and config settings that are leased to client machines. This service saves time/effort by dynamically assigning IP address info.
DHCP Client device lease IP config info from DHCP server. The process is discover, offer, request, and acknowledgement. dhclient manages current dhcp client configuration.
Domain name space maps domain name to an IP address. Fully Qualified Domain Name (FQDN) is hierarchical naming scheme called DNS.
The hostname command displays or set name of local host for current session (not permanent).
The nsloolup command gathers and tests name resolution information.
The dig command is a powerful tool for gathering information and testing name resolution.
The resolvectl command gathers and test name resolution information and manually query name resolution services.
The host command finds the IP address for a domain name.
We also covered the Default Gateway which connects different networks and allow data to flow between them.
