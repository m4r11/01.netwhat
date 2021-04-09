# netwhat
Basic network knowledge 📡

"IP addresses can be said to consist of multiple parts, similar to how full street addresses consist of multiple parts. A street address can consist of the increasingly specific parts Country, City, Postal Code, Street and House Number. An IP address consists of two main parts:
🧩 IP network and 🧩 addresses within the IP network. The addresses within the IP network are also called the host 🎙 addresses because different hosts (computers) have different unique addresses within the IP network.

🧩 The IP network corresponds to more general parts of a full street address, such as City, Postal Code and Street name.
🧩 The Host Addresses within the IP network correspond to specific house numbers on a street."

"But how can you tell if two IP addresses belong to same IP network? Unfortunately, it isn’t as easy to tell IP networks apart from one another as it is with street addresses. The answer is within something called a 🤡 Subnet Mask. The Subnet Mask determines how much of the IP address that denominates which IP network the address belongs to. The rest of the IP address can then be used for computers and other hosts on the IP network."

"Both an IP address and a Subnet Mask consists of four parts separated by periods. Each part of an IP address and a Subnet Mask can have a value between 0-255"

"In its simplest form, each part of the Subnet Mask is either the number 255 or the number 0 (zero).

-> 255 means that the corresponding part of the IP address belongs to the IP network.
-> 0 (Zero) means that the corresponding part of the IP address belongs to the Host Addresses."

"In a normal home network, the Subnet Mask is usually “255.255.255.0”. What that means is that the three first parts of the IP address determine which IP network that the IP addresses belong to. The last part of the IP address determines which unique address within that IP network that each individual computer has got.

As we mentioned earlier, each part of an IP address can have a value between 0-255. So the fourth part of the IP address permits for 256 different addresses (zero up to 255) that can be used for computers, IP phones, routers, laptops, printers and other devices. These type of devices are commonly referred to as hosts or clients. In a normal home network, those addresses are always more than enough to cover the devices that are connected to the network."

[IP Address](https://www.homenethowto.com/basics/ip-addresses/)

"What DHCP protocol does it use at the transport layer level?"

User Datagram Protocol (UDP)
DHCP uses User Datagram Protocol (UDP), RFC 768, as its transport protocol.

"Which of the following IP addresses is a private address?"

"Private (internal) addresses are not routed on the Internet and no traffic can be sent to them from the Internet, they only supposed to work within the local network.
Private addresses include IP addresses from the following subnets:

Range from 10.0.0.0 to 10.255.255.255 — a 10.0.0.0 network with a 255.0.0.0 or /8 (an 8-bit) mask
Range from 172.16.0.0 to 172.31.255.255 — a 172.16.0.0 network with a 255.240.0.0 or /12
A 192.168.0.0 to 192.168.255.255 range, which is a 192.168.0.0 network masked by 255.255.0.0 or /16
A special range 100.64.0.0 to 100.127.255.255 with a 255.192.0.0 or /10 network mask; this subnet is recommended according to rfc6598 for use as an address pool for CGN (Carrier-Grade NAT)"

[PrivateIp] (https://help.keenetic.com/hc/en-us/articles/213965789-What-is-the-difference-between-a-public-and-private-IP-address-)

"Which IP address class has more host addresses available by default?"

"Class A addressing
Which class of IP address has the most host addresses available by default? Explanation: Class A addressing provides 24 bits for host addressing."

"Which protocol does Ping use?"

"ICMP
The program ping is one program that uses ICMP to determine whether a system is connected to the Internet (it uses the ICMP messages Echo Request and Echo Reply)."

[Ping] (https://www.sciencedirect.com/topics/computer-science/internet-control-message-protocol)

Domain name system is the way the internet domain names are stored and translated to IP addresses. The domain names systems matches the name of website to ip addresses of the website.

"You have an interface on a router with the IP address of 124.144.156.248/21. Including the router interface, how many hosts can have IP addresses on the local network connected to the router interface?"

2046

[Calculator+more] (https://www.calculator.net/ip-subnet-calculator.html)

"Which of the following propositions is not true?"


   UDP is faster, simpler and more efficient than TCP ✅
   UDP only has the basic error control mechanism ✅
   UDP is a datagram oriented protocol ✅
   UDP does not support broadcasting ❌

"Which of the following propositions is not true?"


   UDP is faster, simpler and more efficient than TCP  ✅
   UDP provides extended error checking mechanisms. ❌
   UDP is a datagram oriented protocol cknowledgement ✅
   UDP supports broadcasting  ✅

"What is the network address of a host with an IP address of 107.212.146.212/25?"

   107.212.146.208
   107.128.0.0
   0.0.0.0
   64.0.0.0
   107.212.128.0
   107.212.146.128 ✅
   107.212.0.0 
   107.208.0.0
   107.212.146.192

(107.212.146.212) & (255.255.255.128) = 107.212.146.128

"What is the network address of a host with an IP address of 45.195.37.187/16?"

   45.194.37.187
   45.0.0.0
   45.194.0.0
   45.195.0.0  ✅

(45.195.37.187) & (255.255.0.0) = 45.195.0.0

"What is the network address of a host with an IP address of 116.45.224.50/8?"


   116.0.1.0
   116.0.0.0 ✅
   116.255.255.0
   116.255.255.255

"What is the broadcast address of a host with an IP address of 51,254,122,100/24?"


   51.254.122.0
   51.254.122.1
   51.254.122.254
   51.254.122.255 ✅

[Calculater++] (http://jodies.de/ipcalc?host=51.254.122.100&mask1=24&mask2=)

You want to implement a mechanism that automates IP configuration, including IP address, subnet mask, default gateway and DNS information. What protocol will you use to achieve this?


   SNMP
   DHCP ✅
   SMTP
   ARP

DHCP is connectionless, which means it uses User Datagram Protocol (UDP) at the Transport layer, also called the Host-to-Host layer. You want to implement a mechanism that automates the IP configuration, including IP address, subnet mask, default gateway, and DNS information.

"What is the size of an IPV6 address?"

128 bits ✅

IPv6 uses 128-bit (2128) addresses, allowing 3.4 x 1038 unique IP addresses. This is equal to 340 trillion trillion trillion IP addresses. IPv6 is written in hexadecimal notation, separated into 8 groups of 16 bits by the colons, thus (8 x 16 = 128) bits in total.

"Which of the following proposals is the valid host range for the subnet on which the IP address 158.167.18.156/15 resides?"

   158.166.0.1- 158.167.255.253
   158.165.255.253- 158.167.255.254
   158.166.0.1- 158.167.255.254 ✅
   158.166.0.2- 158.168.0.2

158.166.0.1- 158.167.255.254
(Network)158.166.0.0 (Broadcast) 158.167.255.255

"What is the default IP address class available?"

C ✅

"Which of the following IP addresses is a private address?"

   108.246.233.231
   146.227.105.173
   59.155.254.18 
   253.29.133.220
   192.168.20.253 ✅
   94.152.104.99

"What is the CIDR notation of the 255.255.128.0 subnet mask?"

   /8
   /16
   /9
   /17 ✅

"You have an interface on a router with the IP address of 240.19.3.205/12. Including the router interface, how many hosts can have IP addresses on the local network connected to the router interface?"


   1048576
   2097154
   1048574 ✅
   524284
   1048578 
   2097148
   1048572

"which of the following proposals is a private IP address?"

   57.195.242.245
   172.27.217.52 ✅
   249.204.256.26
   249.204.156.26
   4.137.228.63
   176.37.230.43
   218.106.207.158


"The Internet Assigned Numbers Authority (IANA) has reserved the following three blocks private IP address ranges for private networks:

Class A — 10.0.0.0 — 10.255.255.255 (16,777,216 total hosts)
Class B — 172.16.0.0 — 172.31.255.255 (1,048,576 total hosts)
Class C — 192.168.0.0 — 192.168.255.255 (65,536 total hosts)
"

"What is the maximum number of IP addresses that can be assigned to hosts on a local subnet using the 255.255.128.0 subnet mask?"

   65536
   65532
   16380
   32768
   32770
   65530
   32766 ✅
   16382
   32764

"If the IP address 123.48.189.194/21 is assigned to an Ethernet port of a router, what host address could communicate with it?"

   101.219.223.235
   75.153.38.143
   5.200.165.154
   13.28.168.153
   172.1.223.196
   43.241.96.42
   123.48.189.109 ✅
   253.99.227.186

 Host range: 123.48.184.1 - 123.48.191.254

 "What is the size of an IPV4 address?"

   128 bits
   32 bits ✅
   64 miles
   16 bits
   8 bits
   64 bytes
   128 bytes

IPv4 addresses are 32-bit numbers that are typically displayed in dotted decimal notation. A 32-bit address contains two primary parts: the network prefix and the host number. All hosts within a single network share the same network address. Each host also has an address that uniquely identifies it.

"What are the different layers of the OSI model?"

 Application - Presentation - Session - Transport - Network - Data Link - Physical ✅

Physical Layer.
Data Link Layer. ...
Network Layer. ...
Transport Layer. ...
Session Layer. ...
Presentation Layer. The presentation layer prepares data for the application layer. ...
Application Layer. The application layer is used by end-user software such as web browsers and email clients.

[Osi] (https://www.imperva.com/learn/application-security/osi-model/)

"What is the CIDR notation of the 255.255.192.0 subnet mask?"

   /5
   /31
   /18 ✅
   /14

"Which of the following IP addresses is a private address?"

   169.153.119.123
   24.23.102.151
   255.62.136.173
   10.166.25.20 ✅
   46.244.138.171
   27.147.158.251

"Which of the following propositions is not true?"

   TCP is a datagram oriented protocol ✅
   TCP does not support broadcasting
   TCP provides extended error checking mechanisms. This is because it provides flow control and data ac   Data sequencing is a TCP feature (this means that packets arrive in order in the recipient)
   TCP is reliable because it guarantees the delivery of data to the router of the destination
   TCP is comparatively slower than UDP

"What type of address is supported by DHCP?"

   IPV4
   IPV6
   IPV4 and IPV6 ✅
   None of them

[DHCP] (https://www.efficientip.com/what-is-dhcp-and-why-is-it-important/)

"Which of the following proposals is the valid host range for the subnet on which the IP address 233.249.146.36/21 resides?"

   233.249.143.255-233.249.151.250
   233.249.144.4-233.249.152.0
   233.249.144.1-233.249.151.254 ✅
   233.249.144.6-233.249.152.1
   233.249.144.0-233.249.151.249
   
Host range: 233.249.144.1 - 233.249.151.254

"Which of the following propositions is not true?"

   TCP is a connection-oriented protocol
   TCP does not support broadcasting
   TCP provides extended error checking mechanisms. This is because it provides flow control and data acknowledgement
   Data sequencing is a TCP feature (this means that packets arrive in order in the recipient)
   The delivery of data to the destination cannot be guaranteed in TCP ❌
   TCP is reliable because it guarantees the delivery of data to the router of the destination

[TCP] (https://www.geeksforgeeks.org/differences-between-tcp-and-udp/)

