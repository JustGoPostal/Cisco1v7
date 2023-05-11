# Cisco1v7
# NOTE THIS FILE IS ONLY FOR STUDY PURPOSES AND IS NOT TO BE USED FOR ANY PURPOSES OTHER THAN STUDYING!
# USE OF THIS FILE FOR ANY OTHER PURPOSE CREATOR WILL NOT BE FOUND LIABLE
# USE AT YOUR OWN RISK / NOT ALL QUESTIONS ARE ANSWERED
# SOME QUESTIONS MAY BE ANSWERED WRONG OR BE OUT OF DATE
# THIS IS A BANK OF QUESTIONS ANSWERED AND IS TO BE USED AS SUCH NO PICTURES INCLUDED.
1. Which two traffic types use the Real-Time Transport Protocol (RTP)? (Choose two.)
video
voice
2. Which wireless technology has low-power and data rate requirements making it popular in home automation applications?

ZigBee
Explanation: ZigBee is an IEEE 802.15.4 wireless standard designed for creating personal-area networks. Low energy, power, and data rate requirements make Zigbee a popular protocol for connecting home automation devices.

3. Which layer of the TCP/IP model provides a route to forward messages through an internetwork?

internet
Explain:
The OSI model network layer corresponds directly to the internet layer of the TCP/IP model and is used to describe protocols that address and route messages through an internetwork.

4. Which type of server relies on record types such as A, NS, AAAA, and MX in order to provide services?

DNS
Explain:
A DNS server stores records that are used to resolve IP addresses to host names. 

5. What are proprietary protocols?

protocols developed by organizations who have control over their definition and operation
Explain:
Proprietary protocols have their definition and operation controlled by one company or vendor. Some of them can be used by different organizations with permission from the owner. The TCP/IP protocol suite is an open standard, not a proprietary protocol.

6. What service is provided by DNS?

Resolves domain names, such as cisco.com, into IP addresses.

7. A client packet is received by a server. The packet has a destination port number of 110. What service is the client requesting?

POP3
8. What command can be used on a Windows PC to see the IP configuration of that computer?

ipconfig
9. A wired laser printer is attached to a home computer. That printer has been shared so that other computers on the home network can also use the printer. What networking model is in use?

peer-to-peer (P2P)
Explanation: Peer-to-peer (P2P) networks have two or more network devices that can share resources such as printers or files without having a dedicated server.

10. What characteristic describes a virus?

malicious software or code running on an end device
11. Three bank employees are using the corporate network. The first employee uses a web browser to view a company web page in order to read some announcements. The second employee accesses the corporate database to perform some financial transactions. The third employee participates in an important live audio conference with other corporate managers in branch offices. If QoS is implemented on this network, what will be the priorities from highest to lowest of the different data types?

audio conference, financial transactions, web page

Explanation: QoS mechanisms enable the establishment of queue management strategies that enforce priorities for different categories of application data. Thus, this queuing enables voice data to have priority over transaction data, which has priority over web data.


13. Refer to the exhibit. If Host1 were to transfer a file to the server, what layers of the TCP/IP model would be used?


application, transport, Internet, and network access layers

Explanation: The TCP/IP model contains the application, transport, internet, and network access layers. A file transfer uses the FTP application layer protocol. The data would move from the application layer through all of the layers of the model and across the network to the file server.

14.
Explanation: A store-and-forward switch always stores the entire frame before forwarding, and checks its CRC and frame length. A cut-through switch can forward frames before receiving the destination address field, thus presenting less latency than a store-and-forward switch. Because the frame can begin to be forwarded before it is completely received, the switch may transmit a corrupt or runt frame. All forwarding methods require a Layer 2 switch to forward broadcast frames.

15. Refer to the exhibit. The IP address of which device interface should be used as the default gateway setting of host H1?


R1: G0/0

Explanation: The default gateway for host H1 is the router interface that is attached to the LAN that H1 is a member of. In this case, that is the G0/0 interface of R1. H1 should be configured with the IP address of that interface in its addressing settings. R1 will provide routing services to packets from H1 that need to be forwarded to remote networks.

16. What service is provided by Internet Messenger?

An application that allows real-time chatting among remote users.

17. Refer to the exhibit. Match the network with the correct IP address and prefix that will satisfy the usable host addressing requirements for each network.

Explanation: Network A needs to use 192.168.0.128 /25, which yields 128 host addresses.
Network B needs to use 192.168.0.0 /26, which yields 64 host addresses.
Network C needs to use 192.168.0.96 /27, which yields 32 host addresses.
Network D needs to use 192.168.0.80/30, which yields 4 host addresses.

18. Refer to the exhibit. Which protocol was responsible for building the table that is shown?

ARP

Explanation: The table that is shown corresponds to the output of the arp -a command, a command that is used on a Windows PC to display the ARP table.

19. A network administrator notices that some newly installed Ethernet cabling is carrying corrupt and distorted data signals. The new cabling was installed in the ceiling close to fluorescent lights and electrical equipment. Which two factors may interfere with the copper cabling and result in signal distortion and data corruption? (Choose two.)

RFI​
EMI
20. A host is trying to send a packet to a device on a remote LAN segment, but there are currently no mappings in its ARP cache. How will the device obtain a destination MAC address?

It will send an ARP request for the MAC address of the default gateway.
22. A client packet is received by a server. The packet has a destination port number of 53. What service is the client requesting?

DNS

23. A network administrator is adding a new LAN to a branch office. The new LAN must support 25 connected devices. What is the smallest network mask that the network administrator can use for the new network?

255.255.255.224

24. What characteristic describes a Trojan horse?

malicious software or code running on an end device

25. What service is provided by HTTPS?

Uses encryption to secure the exchange of text, graphic images, sound, and video on the web.

26. A technician with a PC is using multiple applications while connected to the Internet. How is the PC able to keep track of the data flow between multiple application sessions and have each application receive the correct packet flows?


The data flow is being tracked based on the source port number that is used by each application.

Explanation:
The source port number of an application is randomly generated and used to individually keep track of each session connecting out to the Internet. Each application will use a unique source port number to provide simultaneous communication from multiple applications through the Internet.

27. A network administrator is adding a new LAN to a branch office. The new LAN must support 61 connected devices. What is the smallest network mask that the network administrator can use for the new network?

255.255.255.192

28. Refer to the exhibit. Match the network with the correct IP address and prefix that will satisfy the usable host addressing requirements for each network. (Not all options are used.)

Explanation:
Network A needs to use 192.168.0.0 /25 which yields 128 host addresses.
Network B needs to use 192.168.0.128 /26 which yields 64 host addresses.
Network C needs to use 192.168.0.192 /27 which yields 32 host addresses.
Network D needs to use 192.168.0.224 /30 which yields 4 host addresses.

29. What characteristic describes a DoS attack?

an attack that slows or crashes a device or network service
30. Match the application protocols to the correct transport protocols


31. What service is provided by SMTP?

Allows clients to send email to a mail server and the servers to send email to other servers.

32. Which scenario describes a function provided by the transport layer?


A student has two web browser windows open in order to access two web sites. The transport layer ensures the correct web page is delivered to the correct browser window.

Explain:
The source and destination port numbers are used to identify the correct application and window within that application.

33.Refer to the exhibit. Host B on subnet Teachers transmits a packet to host D on subnet Students. Which Layer 2 and Layer 3 addresses are contained in the PDUs that are transmitted from host B to the router?

Layer 2 destination address = 00-00-0c-94-36-ab
Layer 2 source address = 00-00-0c-94-36-bb
Layer 3 destination address = 172.16.20.200
Layer 3 source address = 172.16.10.200

34. What does the term “attenuation” mean in data communication?

loss of signal strength as distance increases
Explanation: Data is transmitted on copper cables as electrical pulses. A detector in the network interface of a destination device must receive a signal that can be successfully decoded to match the signal sent. However, the farther the signal travels, the more it deteriorates. This is referred to as signal attenuation.

35. Refer to the exhibit. An administrator is trying to configure the switch but receives the error message that is displayed in the exhibit. What is the problem?

The administrator must first enter privileged EXEC mode before issuing the command.

36. Which two protocols operate at the top layer of the TCP/IP protocol suite? (Choose two.)


POP
DNS
37. A company has a file server that shares a folder named Public. The network security policy specifies that the Public folder is assigned Read-Only rights to anyone who can log into the server while the Edit rights are assigned only to the network admin group. Which component is addressed in the AAA network service framework?

authorization
After a user is successfully authenticated (logged into the server), the authorization is the process of determining what network resources the user can access and what operations (such as read or edit) the user can perform.

38. What three requirements are defined by the protocols used in network communcations to allow message transmission across a network? (Choose three.)

message size
message encoding
delivery options

39. What are two characteristics of IP? (Choose two.)

does not require a dedicated end-to-end connection
operates independently of the network media

Explain:
The Internet Protocol (IP) is a connectionless, best effort protocol. This means that IP requires no end-to-end connection nor does it guarantee delivery of packets. IP is also media independent, which means it operates independently of the network media carrying the packets.

40. An employee of a large corporation remotely logs into the company using the appropriate username and password. The employee is attending an important video conference with a customer concerning a large sale. It is important for the video quality to be excellent during the meeting. The employee is unaware that after a successful login, the connection to the company ISP failed. The secondary connection, however, activated within seconds. The disruption was not noticed by the employee or other employees.
What three network characteristics are described in this scenario? (Choose three.)

security
quality of service
fault tolerance
41. What are two common causes of signal degradation when using UTP cabling? (Choose two.)

improper termination
low-quality cable or connectors
Explanation: When terminated improperly, each cable is a potential source of physical layer performance degradation.

42. Which subnet would include the address 192.168.1.96 as a usable host address?

192.168.1.64/26
Explanation: For the subnet of 192.168.1.64/26, there are 6 bits for host addresses, yielding 64 possible addresses. However, the first and last subnets are the network and broadcast addresses for this subnet. Therefore, the range of host addresses for this subnet is 192.168.1.65 to 192.168.1.126. The other subnets do not contain the address 192.168.1.96 as a valid host address.

43. Refer to the exhibit. On the basis of the output, which two statements about network connectivity are correct? (Choose two.)



There are 4 hops between this device and the device at 192.168.100.1.
There is connectivity between this device and the device at 192.168.100.1.
Explain:
The output displays a successful Layer 3 connection between a host computer and a host at 19.168.100.1. It can be determined that 4 hops exist between them and the average transmission time is 1 milliseconds. Layer 3 connectivity does not necessarily mean that an application can run between the hosts.

44. Which two statements describe how to assess traffic flow patterns and network traffic types using a protocol analyzer? (Choose two.)

Capture traffic during peak utilization times to get a good representation of the different traffic types.
Perform the capture on different network segments.

Explanation: Traffic flow patterns should be gathered during peak utilization times to get a good representation of the different traffic types. The capture should also be performed on different network segments because some traffic will be local to a particular segment.

45. What is the consequence of configuring a router with the ipv6 unicast-routing global configuration command?​

The IPv6 enabled router interfaces begin sending ICMPv6 Router Advertisement messages.

46. Which three layers of the OSI model map to the application layer of the TCP/IP model? (Choose three.)

application
session
presentation
Explanation: The TCP/IP model consists of four layers: application, transport, internet, and network access. The OSI model consists of seven layers: application, presentation, session, transport, network, data link, and physical. The top three layers of the OSI model: application, presentation, and session map to the application layer of the TCP/IP model.

47. Refer to the exhibit. If PC1 is sending a packet to PC2 and routing has been configured between the two routers, what will R1 do with the Ethernet frame header attached by PC1?

remove the Ethernet header and configure a new Layer 2 header before sending it out S0/0/0
Explanation: When PC1 forms the various headers attached to the data one of those headers is the Layer 2 header. Because PC1 connects to an Ethernet network, an Ethernet header is used. The source MAC address will be the MAC address of PC1 and the destination MAC address will be that of G0/0 on R1. When R1 gets that information, the router removes the Layer 2 header and creates a new one for the type of network the data will be placed onto (the serial link).

48. What will happen if the default gateway address is incorrectly configured on a host?

The host cannot communicate with hosts in other networks.

49. What are two features of ARP? (Choose two.)


If a host is ready to send a packet to a local destination device and it has the IP address but not the MAC address of the destination, it generates an ARP broadcast.
If a device receiving an ARP request has the destination IPv4 address, it responds with an ARP reply.
50. A network administrator is adding a new LAN to a branch office. The new LAN must support 90 connected devices. What is the smallest network mask that the network administrator can use for the new network?

255.255.255.128

51. What are two ICMPv6 messages that are not present in ICMP for IPv4? (Choose two.)

Neighbor Solicitation
Router Advertisement
52. A client packet is received by a server. The packet has a destination port number of 80. What service is the client requesting?

HTTP
53. What is an advantage for small organizations of adopting IMAP instead of POP?

Messages are kept in the mail servers until they are manually deleted from the email client.

Explanation: IMAP and POP are protocols that are used to retrieve email messages. The advantage of using IMAP instead of POP is that when the user connects to an IMAP-capable server, copies of the messages are downloaded to the client application. IMAP then stores the email messages on the server until the user manually deletes those messages.

54. A technician can ping the IP address of the web server of a remote company but cannot successfully ping the URL address of the same web server. Which software utility can the technician use to diagnose the problem?

nslookup
Explain:
Traceroute (tracert) is a utility that generates a list of hops that were successfully reached along the path from source to destination.This list can provide important verification and troubleshooting information. The ipconfig utility is used to display the IP configuration settings on a Windows PC. The Netstat utility is used to identify which active TCP connections are open and running on a networked host. Nslookup is a utility that allows the user to manually query the name servers to resolve a given host name. This utility can also be used to troubleshoot name resolution issues and to verify the current status of the name servers.

55. Which two functions are performed at the LLC sublayer of the OSI Data Link Layer to facilitate Ethernet communication? (Choose two.)

enables IPv4 and IPv6 to utilize the same physical medium
places information in the Ethernet frame that identifies which network layer protocol is being encapsulated by the frame
Other case:

handles communication between upper layer networking software and Ethernet NIC hardware
adds Ethernet control information to network protocol data
Other case:

places information in the Ethernet frame that identifies which network layer protocol is being encapsulated by the frame
adds Ethernet control information to network protocol data
Other case:

enables IPv4 and IPv6 to utilize the same physical medium
adds Ethernet control information to network protocol data
Other case:

enables IPv4 and IPv6 to utilize the same physical medium
handles communication between upper layer networking software and Ethernet NIC hardware
Explanation: The data link layer is actually divided into two sublayers:

+ Logical Link Control (LLC): This upper sublayer defines the software processes that provide services to the network layer protocols. It places information in the frame that identifies which network layer protocol is being used for the frame. This information allows multiple Layer 3 protocols, such as IPv4 and IPv6, to utilize the same network interface and media.
+ Media Access Control (MAC): This lower sublayer defines the media access processes performed by the hardware. It provides data link layer addressing and delimiting of data according to the physical signaling requirements of the medium and the type of data link layer protocol in use.

56. The global configuration command ip default-gateway 172.16.100.1 is applied to a switch. What is the effect of this command?

The switch can be remotely managed from a host on another network.
Explanation: A default gateway address is typically configured on all devices to allow them to communicate beyond just their local network.In a switch this is achieved using the command ip default-gateway <ip address>.

57. What happens when the transport input ssh command is entered on the switch vty lines?

Communication between the switch and remote users is encrypted.
Explanation: The transport input ssh command when entered on the switch vty (virtual terminal lines) will encrypt all inbound controlled telnet connections.

58. Match the type of threat with the cause. (Not all options are used.)


59. A disgruntled employee is using some free wireless networking tools to determine information about the enterprise wireless networks. This person is planning on using this information to hack the wireless network. What type of attack is this?

reconnaissance
Explanation: A reconnaissance attack is the unauthorized discovery and documentation of various computing networks, network systems, resources, applications, services, or vulnerabilities.

60. What service is provided by HTTP?

Uses encryption to secure the exchange of text, graphic images, sound, and video on the web.
Allows for data transfers between a client and a file server.
An application that allows real-time chatting among remote users.
A basic set of rules for exchanging text, graphic images, sound, video, and other multimedia files on the web.
61. A client packet is received by a server. The packet has a destination port number of 67. What service is the client requesting?

DHCP
62. What are two problems that can be caused by a large number of ARP request and reply messages? (Choose two.)

The ARP request is sent as a broadcast, and will flood the entire subnet.
All ARP request messages must be processed by all nodes on the local network.
Explanation: ARP requests are sent as broadcasts:
(1) All nodes will receive them, and they will be processed by software, interrupting the CPU.
(2) The switch forwards (floods) Layer 2 broadcasts to all ports.

A switch does not change its MAC table based on ARP request or reply messages. The switch populates the MAC table using the source MAC address of all frames. The ARP payload is very small and does not overload the switch.

63. A group of Windows PCs in a new subnet has been added to an Ethernet network. When testing the connectivity, a technician finds that these PCs can access local network resources but not the Internet resources. To troubleshoot the problem, the technician wants to initially confirm the IP address and DNS configurations on the PCs, and also verify connectivity to the local router. Which three Windows CLI commands and utilities will provide the necessary information? (Choose three.)

ping
ipconfig
nslookup

64. During the process of forwarding traffic, what will the router do immediately after matching the destination IP address to a network on a directly connected routing table entry?

switch the packet to the directly connected interface
Explanation: A router receives a packet on an interface and looks at the destination IP address. It consults its routing table and matches the destination IP address to a routing table entry. The router then discovers that it has to send the packet to the next-hop address or out to a directly connected interface. When the destination address is on a directly connected interface, the packet is switched over to that interface.

65. What characteristic describes antispyware?

applications that protect end devices from becoming infected with malicious software

66. A network administrator needs to keep the user ID, password, and session contents private when establishing remote CLI connectivity with a switch to manage it. Which access method should be chosen?

SSH
67. What are the two most effective ways to defend against malware? (Choose two.)

Update the operating system and other application software.
Install and update antivirus software.
Explanation: A cybersecurity specialist must be aware of the technologies and measures that are used as countermeasures to protect the organization from threats and vulnerabilities.

68. Which type of security threat would be responsible if a spreadsheet add-on disables the local software firewall?

Trojan horse
Explanation: A Trojan horse is software that does something harmful, but is hidden in legitimate software code. A denial of service (DoS) attack results in interruption of network services to users, network devices, or applications. A brute-force attack commonly involves trying to access a network device. A buffer overflow occurs when a program attempts to store more data in a memory location than it can hold.

69. Which frame field is created by a source node and used by a destination node to ensure that a transmitted data signal has not been altered by interference, distortion, or signal loss?

frame check sequence field
70. A network administrator is adding a new LAN to a branch office. The new LAN must support 4 connected devices. What is the smallest network mask that the network administrator can use for the new network?

255.255.255.248
71. What service is provided by POP3?

Retrieves email from the server by downloading the email to the local mail application of the client.
72. What two security solutions are most likely to be used only in a corporate environment? (Choose two.)

virtual private networks
intrusion prevention systems
73. What characteristic describes antivirus software?

applications that protect end devices from becoming infected with malicious software

74. What mechanism is used by a router to prevent a received IPv4 packet from traveling endlessly on a network?

It decrements the value of the TTL field by 1 and if the result is 0, it discards the packet and sends a Time Exceeded message to the source host.

75. A client packet is received by a server. The packet has a destination port number of 69. What service is the client requesting?

TFTP
76. An administrator defined a local user account with a secret password on router R1 for use with SSH. Which three additional steps are required to configure R1 to accept only encrypted SSH connections? (Choose three.)

Configure the IP domain name on the router.
Generate the SSH keys.
Enable inbound vty SSH sessions.
77. Which two functions are performed at the MAC sublayer of the OSI Data Link Layer to facilitate Ethernet communication? (Choose two.)

implements trailer with frame check sequence for error detection
implements a process to delimit fields within an Ethernet 2 frame
Case 2:

responsible for internal structure of Ethernet frame
implements trailer with frame check sequence for error detection
Case 3:

integrates Layer 2 flows between 10 Gigabit Ethernet over fiber and 1 Gigabit Ethernet over copper
implements CSMA/CD over legacy shared half-duplex media
Case 4:

applies delimiting of Ethernet frame fields to synchronize communication between nodes
implements trailer with frame check sequence for error detection
78. An IPv6 enabled device sends a data packet with the destination address of FF02::2. What is the target of this packet?​

all IPv6 configured routers on the local link​
79. What are the three parts of an IPv6 global unicast address? (Choose three.)

subnet ID
global routing prefix
interface ID
Explanation: The general format for IPv6 global unicast addresses includes a global routing prefix, a subnet ID, and an interface ID. The global routing prefix is the network portion of the address. A typical global routing prefix is /48 assigned by the Internet provider. The subnet ID portion can be used by an organization to create multiple subnetwork numbers. The interface ID is similar to the host portion of an IPv4 address.

80. A network administrator is designing the layout of a new wireless network. Which three areas of concern should be accounted for when building a wireless network? (Choose three.)

interference
security
coverage area
Explanation: The three areas of concern for wireless networks focus on the size of the coverage area, any nearby interference, and providing network security. Extensive cabling is not a concern for wireless networks, as a wireless network will require minimal cabling for providing wireless access to hosts. Mobility options are not a component of the areas of concern for wireless networks.

81. A new network administrator has been asked to enter a banner message on a Cisco device. What is the fastest way a network administrator could test whether the banner is properly configured?

Exit privileged EXEC mode and press Enter .
82. What method is used to manage contention-based access on a wireless network?

CSMA/CA
83. What is a function of the data link layer?

provides for the exchange of frames over a common local media
84. What is the purpose of the TCP sliding window?

to request that a source decrease the rate at which it transmits data
Explanation: The TCP sliding window allows a destination device to inform a source to slow down the rate of transmission. To do this, the destination device reduces the value contained in the window field of the segment. It is acknowledgment numbers that are used to specify retransmission from a specific point forward. It is sequence numbers that are used to ensure segments arrive in order. Finally, it is a FIN control bit that is used to end a communication session.

85. What characteristic describes spyware?

software that is installed on a user device and collects information about the user
86. Which switching method drops frames that fail the FCS check?

store-and-forward switching
87. Which range of link-local addresses can be assigned to an IPv6-enabled interface?

FE80::/10
Explain:
Link-local addresses are in the range of FE80::/10 to FEBF::/10. The original IPv6 specification defined site-local addresses and used the prefix range FEC0::/10, but these addresses were deprecated by the IETF in favor of unique local addresses. FDEE::/7 is a unique local address because it is in the range of FC00::/7 to FDFF::/7. IPv6 multicast addresses have the prefix FF00::/8.

88. What service is provided by FTP?

Allows for data transfers between a client and a file server.
89. A user is attempting to access http://www.cisco.com/ without success. Which two configuration values must be set on the host to allow this access? (Choose two.)

DNS server
default gateway
90. Which two statements accurately describe an advantage or a disadvantage when deploying NAT for IPv4 in a network? (Choose two.)

NAT introduces problems for some applications that require end-to-end connectivity.
NAT provides a solution to slow down the IPv4 address depletion.
Explanation: Network Address Translation (NAT) is a technology that is implemented within IPv4 networks. One application of NAT is to use private IP addresses inside a network and use NAT to share a few public IP addresses for many internal hosts. In this way it provides a solution to slow down the IPv4 address depletion. However, since NAT hides the actual IP addresses that are used by end devices, it may cause problems for some applications that require end-to-end connectivity.

91. What would be the interface ID of an IPv6 enabled interface with a MAC address of 1C-6F-65-C2-BD-F8 when the interface ID is generated by using the EUI-64 process?

1E6F:65FF:FEC2:BDF8
Explanation: To derive the EUI-64 interface ID by using the MAC address 1C-6F-65-C2-BD-F8, three steps are taken.

Change the seventh bit of the MAC address from a binary 0 to a binary 1 which changes the hex C, into a hex E.
Insert hex digits FFFE into the middle of the address.
Rewrite the address in IPv6 format.
The three steps, when complete, give the interface ID of 1E6F:65FF:FEC2:BDF8.

92. Refer to the exhibit. PC1 issues an ARP request because it needs to send a packet to PC2. In this scenario, what will happen next?

PC2 will send an ARP reply with the PC2 MAC address.
Explain: When a network device wants to communicate with another device on the same network, it sends a broadcast ARP request. In this case, the request will contain the IP address of PC2. The destination device (PC2) sends an ARP reply with its MAC address.

93. What service is provided by BOOTP?

Legacy application that enables a diskless workstation to discover its own IP address and find a BOOTP server on the network.
94. What characteristic describes adware?

software that is installed on a user device and collects information about the user
95. When a switch configuration includes a user-defined error threshold on a per-port basis, to which switching method will the switch revert when the error threshold is reached?

store-and-forward
96. Match a statement to the related network model. (Not all options are used.)

ITN (Version 7.00) - ITNv7 Final Exam
ITN (Version 7.00) – ITNv7 Final Exam

Place the options in the following order:peer-to-peer network
[+] no dedicated server is required
[+] client and server roles are set on a per request basis
peer-to-peer aplication
[#] requires a specific user interface
[#] a background service is required

Explain:
Peer-to-peer networks do not require the use of a dedicated server, and devices can assume both client and server roles simultaneously on a per request basis. Because they do not require formalized accounts or permissions, they are best used in limited situations. Peer-to-peer applications require a user interface and background service to be running, and can be used in more diverse situations.

97. What are two primary responsibilities of the Ethernet MAC sublayer? (Choose two.)

accessing the media
data encapsulation

98. Refer to the exhibit. What three facts can be determined from the viewable output of the show ip interface brief command? (Choose three.)

The switch can be remotely managed.
One device is attached to a physical interface.
The default SVI has been configured.
Explain:
Vlan1 is the default SVI. Because an SVI has been configured, the switch can be configured and managed remotely. FastEthernet0/0 is showing up and up, so a device is connected.


99. Match each type of frame field to its function. (Not all options are used.)


100. What is the subnet ID associated with the IPv6 address 2001:DA48:FC5:A4:3D1B::1/64?

2001:DA48:FC5:A4::/64​
101. Match the firewall function to the type of threat protection it provides to the network. (Not all options are used.)


packet filtering – prevents access based on IP or MAC address
URL filtering – prevents access to websites
network address translator – (none)
stateful packet inspection – prevents unsolicited incoming sessions
application filtering – prevents access by port number
Explain:Firewall products come packaged in various forms. These products use different techniques for determining what will be permitted or denied access to a network. They include the following:

+ Packet filtering – Prevents or allows access based on IP or MAC addresses
+ Application filtering – Prevents or allows access by specific application types based on port numbers
+ URL filtering – Prevents or allows access to websites based on specific URLs or keywords
+ Stateful packet inspection (SPI) – Incoming packets must be legitimate responses to requests from internal hosts. Unsolicited packets are blocked unless permitted specifically. SPI can also include the capability to recognize and filter out specific types of attacks, such as denial of service (DoS)

102. Users are reporting longer delays in authentication and in accessing network resources during certain time periods of the week. What kind of information should network engineers check to find out if this situation is part of a normal network behavior?

the network performance baseline
103. How does the service password-encryption command enhance password security on Cisco routers and switches?

It encrypts passwords that are stored in router or switch configuration files.
Explain: The service password-encryption command encrypts plaintext passwords in the configuration file so that they cannot be viewed by unauthorized users.

104. Which two statements are correct in a comparison of IPv4 and IPv6 packet headers? (Choose two.)

The Source Address field name from IPv4 is kept in IPv6.
The Time-to-Live field from IPv4 has been replaced by the Hop Limit field in IPv6.
Explanation: The IPv6 packet header fields are as follows: Version, Traffic Class, Flow Label, Payload Length, Next Header, Hop Limit, Source Address, and Destination Address. The IPv4 packet header fields include the following: Version, Differentiated Services, Time-to-Live, Protocol, Source IP Address, and Destination IP Address. Both versions have a 4-bit Version field. Both versions have a Source (IP) Address field. IPv4 addresses are 32 bits; IPv6 addresses are 128 bits. The Time-to-Live or TTL field in IPv4 is now called Hop Limit in IPv6, but this field serves the same purpose in both versions. The value in this 8-bit field decrements each time a packet passes through any router. When this value is 0, the packet is discarded and is not forwarded to any other router.

105. A network administrator wants to have the same network mask for all networks at a particular small site. The site has the following networks and number of devices:
IP phones – 22 addresses
PCs – 20 addresses needed
Printers – 2 addresses needed
Scanners – 2 addresses needed

The network administrator has deemed that 192.168.10.0/24 is to be the network used at this site. Which single subnet mask would make the most efficient use of the available addresses to use for the four subnetworks?

255.255.255.224
106. What characteristic describes identity theft?

the use of stolen credentials to access private data
107. A network administrator is adding a new LAN to a branch office. The new LAN must support 200 connected devices. What is the smallest network mask that the network administrator can use for the new network?

255.255.255.0

108. What are three commonly followed standards for constructing and installing cabling? (Choose three.)

cable lengths
pinouts
connector types
109. Refer to the exhibit. What is wrong with the displayed termination?

The untwisted length of each wire is too long.
Explanation: When a cable to an RJ-45 connector is terminated, it is important to ensure that the untwisted wires are not too long and that the flexible plastic sheath surrounding the wires is crimped down and not the bare wires. None of the colored wires should be visible from the bottom of the jack.


111. A client packet is received by a server. The packet has a destination port number of 143. What service is the client requesting?

IMAP
112. What are two characteristics shared by TCP and UDP? (Choose two.)

port numbering
use of checksum
Explain:
Both TCP and UDP use source and destination port numbers to distinguish different data streams and to forward the right data segments to the right applications. Error checking the header and data is done by both protocols by using a checksum calculation to determine the integrity of the data that is received. TCP is connection-oriented and uses a 3-way handshake to establish an initial connection. TCP also uses window to regulate the amount of traffic sent before receiving an acknowledgment. UDP is connectionless and is the best protocol for carry digitized VoIP signals.

113. Refer to the exhibit. Which two network addresses can be assigned to the network containing 10 hosts? Your answers should waste the fewest addresses, not reuse addresses that are already assigned, and stay within the 10.18.10.0/24 range of addresses. (Choose two.)

10.18.10.208/28
10.18.10.224/28
Explanation: Addresses 10.18.10.0 through 10.18.10.63 are taken for the leftmost network. Addresses 192 through 199 are used by the center network. Because 4 host bits are needed to accommodate 10 hosts, a /28 mask is needed. 10.18.10.200/28 is not a valid network number. Two subnets that can be used are 10.18.10.208/28 and 10.18.10.224/28.

114. A client packet is received by a server. The packet has a destination port number of 21. What service is the client requesting?

FTP
115. What attribute of a NIC would place it at the data link layer of the OSI model?

MAC address
116. A network administrator is adding a new LAN to a branch office. The new LAN must support 10 connected devices. What is the smallest network mask that the network administrator can use for the new network?

255.255.255.240
117. What technique is used with UTP cable to help protect against signal interference from crosstalk?

twisting the wires together into pairs
Explanation: To help prevent the effects of crosstalk, UTP cable wires are twisted together into pairs. Twisting the wires together causes the magnetic fields of each wire to cancel each other out.


118. Refer to the exhibit. The network administrator has assigned the LAN of LBMISS an address range of 192.168.10.0. This address range has been subnetted using a /29 prefix. In order to accommodate a new building, the technician has decided to use the fifth subnet for configuring the new network (subnet zero is the first subnet). By company policies, the router interface is always assigned the first usable host address and the workgroup server is given the last usable host address. Which configuration should be entered into the properties of the workgroup server to allow connectivity to the Internet?

IP address: 192.168.10.38 subnet mask: 255.255.255.248, default gateway: 192.168.10.33
Explain:
Using a /29 prefix to subnet 192.168.10.0 results in subnets that increment by 8:
192.168.10.0 (1)
192.168.10.8 (2)
192.168.10.16 (3)
192.168.10.24 (4)
192.168.10.32 (5)

119. Refer to the exhibit. The switches are in their default configuration. Host A needs to communicate with host D, but host A does not have the MAC address for its default gateway. Which network hosts will receive the ARP request sent by host A?

only hosts B, C, and router R1
Explain:
Since host A does not have the MAC address of the default gateway in its ARP table, host A sends an ARP broadcast. The ARP broadcast would be sent to every device on the local network. Hosts B, C, and router R1 would receive the broadcast. Router R1 would not forward the message.

120. Match a statement to the related network model. (Not all options are used.)

Place the options in the following order:peer-to-peer network
[+] no dedicated server is required
[+] client and server roles are set on a per request basis
peer-to-peer aplication
[#] requires a specific user interface
[#] a background service is required

Explain:
Peer-to-peer networks do not require the use of a dedicated server, and devices can assume both client and server roles simultaneously on a per request basis. Because they do not require formalized accounts or permissions, they are best used in limited situations. Peer-to-peer applications require a user interface and background service to be running, and can be used in more diverse situations.

121. Refer to the exhibit. A network engineer has been given the network address of 192.168.99.0 and a subnet mask of 255.255.255.192 to subnet across the four networks shown. How many total host addresses are unused across all four subnets?

200
122. Which connector is used with twisted-pair cabling in an Ethernet LAN?

LC conector

SC conector

BNC

RJ 11

True Answer:

RJ 45
RJ 45 (true answer)

123. A client packet is received by a server. The packet has a destination port number of 22. What service is the client requesting?

SSH
124. What characteristic describes an IPS?

a network device that filters access and traffic coming into a network
Explanation: IPS – An intrusion prevention system (IPS) monitors incoming and outgoing traffic looking for malware, network attack signatures, and more. If it recognizes a threat, it can immediately stop it.

125. What service is provided by DHCP?

Dynamically assigns IP addresses to end and intermediary devices.

127. Refer to the exhibit. The switches have a default configuration. Host A needs to communicate with host D, but host A does not have the MAC address for the default gateway. Which network devices will receive the ARP request sent by host A?

only hosts B, C, and router R1
Explanation: Because host A does not have the MAC address of the default gateway in the ARP table, host A sends an ARP broadcast. The ARP broadcast would be sent to every device on the local network. Hosts B, C, and router R1 would receive the broadcast. Router R1 would not forward the message.

128. Which wireless technology has low-power and low-data rate requirements making it popular in IoT environments?

Zigbee
Explanation: Zigbee is a specification used for low-data rate, low-power communications. It is intended for applications that require short-range, low data-rates and long battery life. Zigbee is typically used for industrial and Internet of Things (IoT) environments such as wireless light switches and medical device data collection.

129. What two ICMPv6 message types must be permitted through IPv6 access control lists to allow resolution of Layer 3 addresses to Layer 2 MAC addresses? (Choose two.)

neighbor solicitations
neighbor advertisements
130. A client is using SLAAC to obtain an IPv6 address for its interface. After an address has been generated and applied to the interface, what must the client do before it can begin to use this IPv6 address?

It must send an ICMPv6 Neighbor Solicitation message to ensure that the address is not already in use on the network.
131. Two pings were issued from a host on a local network. The first ping was issued to the IP address of the default gateway of the host and it failed. The second ping was issued to the IP address of a host outside the local network and it was successful. What is a possible cause for the failed ping?

Security rules are applied to the default gateway device, preventing it from processing ping requests.
132. An organization is assigned an IPv6 address block of 2001:db8:0:ca00::/56. How many subnets can be created without using bits in the interface ID space?

256
133. What subnet mask is needed if an IPv4 network has 40 devices that need IP addresses and address space is not to be wasted?

255.255.255.192

Explanation: In order to accommodate 40 devices, 6 host bits are needed. With 6 bits, 64 addresses are possible, but one address is for the subnet number and one address is for a broadcast. This leaves 62 addresses that can be assigned to network devices. The mask associated with leaving 6 host bits for addressing is 255.255.255.192.

134. Refer to the exhibit. If host A sends an IP packet to host B, what will the destination address be in the frame when it leaves host A?

BB:BB:BB:BB:BB:BB
Explain:
When a host sends information to a distant network, the Layer 2 frame header will contain a source and destination MAC address. The source address will be the originating host device. The destination address will be the router interface that connects to the same network. In the case of host A sending information to host B, the source address is AA:AA:AA:AA:AA:AA and the destination address is the MAC address assigned to the R2 Ethernet interface, BB:BB:BB:BB:BB:BB.

135. What is a benefit of using cloud computing in networking?

Network capabilities are extended without requiring investment in new infrastructure, personnel, or software.
Explanation: Cloud computing extends IT’s capabilities without requiring investment in new infrastructure, training new personnel, or licensing new software. These services are available on-demand and delivered economically to any device anywhere in the world without compromising security or function. BYOD is about end users having the freedom to use personal tools to access information and communicate across a business or campus network. Smart home technology is integrated into every-day appliances allowing them to interconnect with other devices, making them more ‘smart’ or automated. Powerline networking is a trend for home networking that uses existing electrical wiring to connect devices to the network wherever there is an electrical outlet, saving the cost of installing data cables.

136. Which two statements are correct about MAC and IP addresses during data transmission if NAT is not involved? (Choose two.)

Destination IP addresses in a packet header remain constant along the entire path to a target host.
Destination and source MAC addresses have local significance and change every time a frame goes from one LAN to another.
137. What is one main characteristic of the data link layer?

It shields the upper layer protocol from being aware of the physical medium to be used in the communication.
138. What are three characteristics of the CSMA/CD process? (Choose three.)

A device listens and waits until the media is not busy before transmitting.
After detecting a collision, hosts can attempt to resume transmission after a random time delay has expired.
All of the devices on a segment see data that passes on the network medium.
Explanation: The Carrier Sense Multiple Access/Collision Detection (CSMA/CD) process is a contention-based media access control mechanism used on shared media access networks, such as Ethernet. When a device needs to transmit data, it listens and waits until the media is available (quiet), then it will send data. If two devices transmit at the same time, a collision will occur. Both devices will detect the collision on the network. When a device detects a collision, it will stop the data transmission process, wait for a random amount of time, then try again.

139. Which information does the show startup-config command display?

the contents of the saved configuration file in the NVRAM
Explain:
The show startup-config command displays the saved configuration located in NVRAM. The show running-config command displays the contents of the currently running configuration file located in RAM.​

140. Which two commands can be used on a Windows host to display the routing table? (Choose two.)

route print
netstat -r
Explain:
On a Windows host, the route print or netstat -r commands can be used to display the host routing table. Both commands generate the same output. On a router, the show ip route command is used to display the routing table. The netstat –s command is used to display per-protocol statistics. The tracert command is used to display the path that a packet travels to its destination.

141. What are two functions that are provided by the network layer? (Choose two.)

directing data packets to destination hosts on other networks
providing end devices with a unique network identifier
Explanation: The network layer is primarily concerned with passing data from a source to a destination on another network. IP addresses supply unique identifiers for the source and destination. The network layer provides connectionless, best-effort delivery. Devices rely on higher layers to supply services to processes.

142. Which two statements describe features of an IPv4 routing table on a router? (Choose two.)​

It stores information about routes derived from the active router interfaces.
If a default static route is configured in the router, an entry will be included in the routing table with source code S .
Explanation: The show ip route command is used to display the routing table of the router. In IPv4, directly connected interfaces will have one source code:C. The routing table stores information about directly connected routes and remote routes. An entry in the routing table with a source code of S is included if a default static route is configured on the router.

143. What characteristic describes a VPN?

a tunneling protocol that provides remote users with secure access into the network of an organization
144. Why would a Layer 2 switch need an IP address?

to enable the switch to be managed remotely
Explanation: A switch, as a Layer 2 device, does not need an IP address to transmit frames to attached devices. However, when a switch is accessed remotely through the network, it must have a Layer 3 address. The IP address must be applied to a virtual interface rather than to a physical interface. Routers, not switches, function as default gateways.

146. A user sends an HTTP request to a web server on a remote network. During encapsulation for this request, what information is added to the address field of a frame to indicate the destination?

the MAC address of the default gateway
Explanation: A frame is encapsulated with source and destination MAC addresses. The source device will not know the MAC address of the remote host. An ARP request will be sent by the source and will be responded to by the router. The router will respond with the MAC address of its interface, the one which is connected to the same network as the source.

147. What is an advantage to using a protocol that is defined by an open standard?

It encourages competition and promotes choices.
Explain:
A monopoly by one company is not a good idea from a user point of view. If a protocol can only be run on one brand, it makes it difficult to have mixed equipment in a network. A proprietary protocol is not free to use. An open standard protocol will in general be implemented by a wide range of vendors.

148. Data is being sent from a source PC to a destination server. Which three statements correctly describe the function of TCP or UDP in this situation? (Choose three.)

The source port field identifies the running application or service that will handle data returning to the PC.
UDP segments are encapsulated within IP packets for transport across the network.
The UDP destination port number identifies the application or service on the server which will handle the data.
Explanation: Layer 4 port numbers identify the application or service which will handle the data. The source port number is added by the sending device and will be the destination port number when the requested information is returned. Layer 4 segments are encapsulated within IP packets. UDP, not TCP, is used when low overhead is needed. A source IP address, not a TCP source port number, identifies the sending host on the network. Destination port numbers are specific ports that a server application or service monitors for requests.

150. Refer to the exhibit. A company uses the address block of 128.107.0.0/16 for its network. What subnet mask would provide the maximum number of equal size subnets while providing enough host addresses for each subnet in the exhibit?

255.255.255.128
Explanation: The largest subnet in the topology has 100 hosts in it so the subnet mask must have at least 7 host bits in it (27-2=126). 255.255.255.0 has 8 hosts bits, but this does not meet the requirement of providing the maximum number of subnets.

151. A network administrator wants to have the same subnet mask for three subnetworks at a small site. The site has the following networks and numbers of devices:

Subnetwork A: IP phones – 10 addresses
Subnetwork B: PCs – 8 addresses
Subnetwork C: Printers – 2 addresses
What single subnet mask would be appropriate to use for the three subnetworks?

255.255.255.240
Explain:
If the same mask is to be used, then the network with the most hosts must be examined for number of hosts. Because this is 10 hosts, 4 host bits are needed. The /28 or 255.255.255.240 subnet mask would be appropriate to use for these networks. ​

153. What two pieces of information are displayed in the output of the show ip interface brief command? (Choose two.)

IP addresses
Layer 1 statuses
Explanation: The command show ip interface brief shows the IP address of each interface, as well as the operational status of the interfaces at both Layer 1 and Layer 2. In order to see interface descriptions and speed and duplex settings, use the command show running-config interface. Next-hop addresses are displayed in the routing table with the command show ip route, and the MAC address of an interface can be seen with the command show interfaces.

154. A user is complaining that an external web page is taking longer than normal to load.The web page does eventually load on the user machine. Which tool should the technician use with administrator privileges in order to locate where the issue is in the network?

tracert
Explanation: The Command Prompt command tracert will map the path from the PC to the web server and measure transit delays of packets across the network.

155. Which value, that is contained in an IPv4 header field, is decremented by each router that receives a packet?

Time-to-Live
Explanation: When a router receives a packet, the router will decrement the Time-to-Live (TTL) field by one. When the field reaches zero, the receiving router will discard the packet and will send an ICMP Time Exceeded message to the sender.

156. A network technician is researching the use of fiber optic cabling in a new technology center. Which two issues should be considered before implementing fiber optic media? (Choose two.)

Fiber optic cabling requires different termination and splicing expertise from what copper cabling requires.
Fiber optic provides higher data capacity but is more expensive than copper cabling.

158. A user is executing a tracert to a remote device. At what point would a router, which is in the path to the destination device, stop forwarding the packet?

when the value in the TTL field reaches zero
Explain:
When a router receives a traceroute packet, the value in the TTL field is decremented by 1. When the value in the field reaches zero, the receiving router will not forward the packet, and will send an ICMP Time Exceeded message back to the source.

159. Users report that the network access is slow. After questioning the employees, the network administrator learned that one employee downloaded a third-party scanning program for the printer. What type of malware might be introduced that causes slow performance of the network?

worm
Explanation: A cybersecurity specialist needs to be familiar with the characteristics of the different types of malware and attacks that threaten an organization.
