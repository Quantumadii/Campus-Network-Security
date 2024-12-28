# Campus-Network-Security
Cisco Packet Tracer:Project

In this project I have created a network topology of our College campus,which is GCOEN campus.In the network I used all the neccessary componenets such as switches,routers,PC's and server.I configured all the components with the IP's of it.So,the first task was to conduct an attack surface mapping to identify potential vulnerabilities and weakness within the network.So they were as follows:
1)Unauthorized access to systems
2)Firewall protection

So to find a solution I did the following steps:
-Configured the switches and router by enabling the secret password as password 
-configured the switches and router by having username and password which were:
  >usernames:
   1.Admin-office=Admin123
   2.Main-Building=Mainbuild123
   3.Annex-Building=Annexbuild123
   4.Faculty=Faculty123
   5.Student=Student123
  >password:
   1.Admin-office=Admin@123
   2.Main-Building=Mainbuild@123
   3.Annex-Building=Annexbuild@123
   4.Faculty=Faculty@123
   5.Student=Student@123

-Then a firewall was set up for each PC and server to protect the network from outside attackers.So I allowed the IP access and Denied the ICMP by giving the remote IP as 0.0.0.0 and remote wildcard mask as 255.255.255.255.Thus the firewall was set to have a more secured network in the topology.

Thus problem of creating network topology of college campus and making it a secured by configuring the switch and router with username & password for unauthorized access and firewall to protect from outside attacks.
