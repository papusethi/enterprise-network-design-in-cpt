## ENTERPRISE NETWORK DESIGN AND IMPLEMENTATION IN CISCO PACKET TRACER
Thus an enterprise network was built successfully with Cisco Packet Tracer implementing various network protocols and output was tested successfully.

## NETWORK REQUIREMENT
1.	An ISP granted a block of IP address starting with 202.195.32.0/24 to an enterprise. Enterprise having 2 virtual subnet, 2 physical subnet and 4 links. Number of hosts required in different subnets are: 
**  Network A = 30 host
**  Network B = 30 host 
**  Network C = 60 host
**  Network D = 12 host
2.	Distribute the IP address to different subnets and links by subnetting IP block granted by ISP. Use a different IP for link between Enterprise Router and ISP Router (e.g. 200.10.10.0/30).
3.	Create 2 Virtual Network A and B. Implement Inter VLAN Routing between VLANs.
4.	Connect a DHCP server in Network A and configure DHCP relay in router to allow automatic IP configuration in Network B. Connect another DHCP server in Network C. Use static IP in Network D.
5.	Implement Dynamic routing protocol for routing within enterprise network and default routing to connect with ISP.
6.	Implement webserver, FTP server and DNS Server in network D.
7.	Restrict host of Network A from exiting the network. Host of Network C should not able to access web server but can connect with internet. Hosts of Network B should not able to access internet.

