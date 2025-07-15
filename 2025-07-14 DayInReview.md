Federation - networks under separate admin control/share user accounts. pg 10

Video SoftTech Sharing "Authentication Protocols Every Beginner Should Know | SAML(SSO), OAuth, OpenID, RADIUS Explained"

Admin - identification make a claim

Authentication - prove a claim

Authorization - rights or permissions

Accounting -

Radius then TACAS+, LDAP then Kerberos, MS Active Directory SSO single sign on

- VPN creates tunnel to network as if your on site (internal).

Federation purpose is to Authenticate and Authorize. It has three components -  Priniple, Service Provider(SP), and Identity Provider(IdP).

SSO - 
SAML - provides specific protocols and technologies to user identity assertions.
OpenID does Authentication
OAuth does Authorization

Video by ByteMonk "What is SAML? A Comprehensive Guide with Examples"

Video "Understanding Network Security Zones | Honeypots, Guest Networks, ..."

SDN
Network Segmentation
Security Zones
1. screened Subnet
2. multi-home subnet
3. Bation Host
4. Wireless Network
5. Guest Network
6. "Honey" Net
7. Ad-Hoc

Video "Network Walks What are Security Zones?"

Attack Surface vs. Attck Vector - 

Network Access Control (NAC) -

- 802.1.x - is an IEEE standard dining how devices authenticate before gaining access to wired/wireless Local Area Network (LAN). It's core purpose is to prevent unauthorized devices from connecting to the network port (physical or wireless) until they prove their identity and meet security requirements. It uses EAP (Extensible Authentication Protocol) for flexible credential exchange (EAP-TLS, PEAP, EAP-TTLS, etc.).

Network Access Control (NAC)


- 

Video by Prof. Messer "Port Security" (good short video on subject)

Air gappped (what is air gap) 

What is a Faraday bag -

What is Powerline Communication (PLC) Attack - 

Acceptable Use Policy (AUP) (on test) - 

Lesson 5B Network Security Appliances

Device Attributes - precise way device can be placed in network
Active control uses software (agent)
Passive control - does not use sofware (agentless)

Switched Port Analyzer -- SPAN - sensor attached to special port on switch

Test Access Port - TAP - sensor attached to special port on switch. pg. 4

Network Security Appliances
- "security controls" / "counter measure"
- defense-in-depth
- Agent-based vs Agentless
- TAP vs SPAN

Filter
-"filters"
- stateless - analyzes particular packet at a time (one at a time)
- statefull - analyzes context of packet flow
- host-based firewall runs on individual device vs network-based firewall runs on entire LAN, eg. pfSense.

- IDS/IPS
  NIDS/NIPS
  HIDS/HIPS

What is Zero day?

Firewall
Layer 4 

Unified Threat Management (UTM) pg. 19

pg. 20 Next Generation Firewall (NGFW) Tracks the state of traffic based on layer 2 through 7. NGFW originally designed to fill in performance gap left by UTMs and security gap left by traditonal firewalls.

Load Balancers - Distributes requests across farm or pool of servers (nodes).

Clustering - 2 or more integrated systems working at same time to provide same service - (they know about each other).

