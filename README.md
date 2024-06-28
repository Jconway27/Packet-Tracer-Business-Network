<h1>Cisco Packet Tracer: Business Network</h1>


<h2>Description</h2>
Design and implementation of a large to medium sized business system network. Approximately 600 employees on three floors (120 employees per floor). Three floors with eight departments (Sales/marketing and human resources/logistics, finance/accounts and administration/public relations, and an IT department and server room for around 12 employees). 
<br />

<h2>Environments Used</h2>

- <b>Cisco Packet Tracer v8.2.2</b>

<h2>Homelab walk-through</h2>

<br />
<br />
<p align="center">
1. Two (2) 2811 series Cisco routers (ISP), two (2) 2911 series Cisco routers (Core), two (2) 3650-24PS Cisco Catalyst multi-switches (Layer 3), six (6) 2960-24TT Cisco Catalyst switches (Layer 2) added to a hierarchical network topology design:  <br/>
<img src="https://imgur.com/Mbjt8vH.png" height="80%" width="80%"/>
<br />
<br />
2. Each router and switch named on topology: <br/>
<img src="https://imgur.com/yLuQjVI.png" height="80%" width="80%"/>
<br />
<br />
3. HWIC-2T Cisco Router High-Speed WAN Interface card added to slot one in each router:  <br/>
<img src="https://imgur.com/OceUsQn.png" height="80%" width="80%"/>
<br />
<br />
4. ISP routers connected to Core routers via serial DCE cable (serial ports), Core routers connected to multi-switches via copper straight-through cable (gigabit ports) and multi-switches connected to layer two switches via copper cross-over cable (fast ethernet ports):  <br/>
<img src="https://imgur.com/6ByeQNK.png" height="80%" width="80%"/>
<br />
<br />
5. PCs, printers, access point devices, laptops, tablets and three servers (DNS, DHCP, Email) added to the topology:  <br/>
<img src="https://imgur.com/44HEhva.png" height="80%" width="80%"/>
<br />
<br />
7. PCs, printers and access point devices connected via copper straight-through cable:  <br/>
<img src="https://imgur.com/4DibITs.png" height="80%" width="80%"/>
<br />
<br />
8. Distinguished borders encapsulate each department and floor:  <br/>
<img src="https://imgur.com/T6sXnsr.png" height="80%" width="80%"/>
<br />
<br />
9. Sales VLAN configured:  <br/>
<img src="https://imgur.com/9DmJuWm.png" height="80%" width="80%"/>
<br />
<br />
10. Human Resources VLAN configured:  <br/>
<img src="https://imgur.com/WUte67Y.png" height="80%" width="80%"/>
<br />
<br />
11. Finance VLAN configured:  <br/>
<img src="https://imgur.com/l6IPkHi.png" height="80%" width="80%"/>
<br />
<br />
12. Administration VLAN configured:  <br/>
<img src="https://imgur.com/ZhMmdJC.png" height="80%" width="80%"/>
<br />
<br />
13. ICT VLAN configured:  <br/>
<img src="https://imgur.com/0QMbNUt.png" height="80%" width="80%"/>
<br />
<br />
14. Server room VLAN configured:  <br/>
<img src="https://imgur.com/ElsCqsA.png" height="80%" width="80%"/>
<br />
<br />
15. Switchport security configured for the Finance department:  <br/>
<img src="https://imgur.com/hAVJOsI.png" height="80%" width="80%"/>
<br />
<br />
16. IP and subnet addressing:  <br/>
<img src="https://imgur.com/OOMGW7J.png" height="80%" width="80%"/>
<br />
<br />
17. IP and subnet addressing:  <br/>
<img src="https://imgur.com/hBAZNrQ.png" height="80%" width="80%"/>
<br />
<br />
18. IP and subnet addressing:  <br/>
<img src="https://imgur.com/sXh3EdA.png" height="80%" width="80%"/>
<br />
<br />
19. IP and subnet addressing:  <br/>
<img src="https://imgur.com/X2gXzlX.png" height="80%" width="80%"/>
<br />
<br />
20. IP and subnet addressing:  <br/>
<img src="https://imgur.com/1DQf0JN.png" height="80%" width="80%"/>
<br />
<br />
21. IP and subnet addressing:  <br/>
<img src="https://imgur.com/V7mOYQC.png" height="80%" width="80%"/>
<br />
<br />
22. IP and subnet addressing:  <br/>
<img src="https://imgur.com/i8XKgV2.png" height="80%" width="80%"/>
<br />
<br />
23. IP and subnet addressing:  <br/>
<img src="https://imgur.com/cvIRLyd.png" height="80%" width="80%"/>
<br />
<br />
24. OSPF configured Multi-Switch 1:  <br/>
<img src="https://imgur.com/sN51pCm.png" height="80%" width="80%"/>
<br />
<br />
25. OSPF configured Multi-Switch 1:  <br/>
<img src="https://imgur.com/3z8Fqd8.png" height="80%" width="80%"/>
<br />
<br />
26. OSPF configured Multi-Switch 2:  <br/>
<img src="https://imgur.com/L5R18Wt.png" height="80%" width="80%"/>
<br />
<br />
27. OSPF configured Multi-Switch 2:  <br/>
<img src="https://imgur.com/OezCuNj.png" height="80%" width="80%"/>
<br />
<br />
28. OSPF configured on Router 1:  <br/>
<img src="https://imgur.com/SYspOm0.png" height="80%" width="80%"/>
<br />
<br />
29. OSPF configured on Router 1:  <br/>
<img src="https://imgur.com/vkXV0IW.png" height="80%" width="80%"/>
<br />
<br />
30. OSPF configured on Router 2:  <br/>
<img src="https://imgur.com/WpM9nW0.png" height="80%" width="80%"/>
<br />
<br />
31. OSPF configured on Router 2:  <br/>
<img src="https://imgur.com/fk6OpNz.png" height="80%" width="80%"/>
<br />
<br />
32. OSPF configured on ISP 1:  <br/>
<img src="https://imgur.com/O4fZWSI.png" height="80%" width="80%"/>
<br />
<br />
33. OSPF configured on ISP 1:  <br/>
<img src="https://imgur.com/PtVkZW3.png" height="80%" width="80%"/>
<br />
<br />
34. OSPF configured on ISP 2:  <br/>
<img src="https://imgur.com/IztFIfS.png" height="80%" width="80%"/>
<br />
<br />
35. OSPF configured on ISP 2:  <br/>
<img src="https://imgur.com/4JKjPSE.png" height="80%" width="80%"/>
<br />
<br />
36. IP configured on DHCP Server:  <br/>
<img src="https://imgur.com/1r7GCAw.png" height="80%" width="80%"/>
<br />
<br />
37. DHCP services configured on DHCP server:  <br/>
<img src="https://imgur.com/1OsQ3CW.png" height="80%" width="80%"/>
<br />
<br />
38. DHCP services configured on DHCP server:  <br/>
<img src="https://imgur.com/6cxFUQ1.png" height="80%" width="80%"/>
<br />
<br />
39. DHCP services configured on DHCP server:  <br/>
<img src="https://imgur.com/dn31qvO.png" height="80%" width="80%"/>
<br />
<br />
40. DHCP services configured on DHCP server:  <br/>
<img src="https://imgur.com/ziIzXBk.png" height="80%" width="80%"/>
<br />
<br />
41. DHCP services configured on DHCP server:  <br/>
<img src="https://imgur.com/uKOOMzC.png" height="80%" width="80%"/>
<br />
<br />
42. DHCP services configured on DHCP server:  <br/>
<img src="https://imgur.com/7XwePFG.png" height="80%" width="80%"/>
<br />
<br />
43. The domain name www.ciscopktlab.com created on the DNS Server:  <br/>
<img src="https://imgur.com/ib3S3AF.png" height="80%" width="80%"/>
<br />
<br />
44. Inter-VLAN routing on Layer 3 multi-switches configured :  <br/>
<img src="https://imgur.com/zi0zVEk.png" height="80%" width="80%"/>
<br />
<br />
45. Inter-VLAN routing on Layer 3 multi-switches configured :  <br/>
<img src="https://imgur.com/TciXQfa.png" height="80%" width="80%"/>
<br />
<br />
46. Wireless network configurations:  <br/>
<img src="https://imgur.com/VjR1DTB.png" height="80%" width="80%"/>
<br />
<br />
47. Wireless network configurations:  <br/>
<img src="https://imgur.com/qCllgMD.png" height="80%" width="80%"/>
<br />
<br />
48. Wireless network configurations:  <br/>
<img src="https://imgur.com/O000nQk.png" height="80%" width="80%"/>
<br />
<br />
49. Wireless network configurations:  <br/>
<img src="https://imgur.com/cpQRRVl.png" height="80%" width="80%"/>
<br />
<br />
50. Wireless network configurations:  <br/>
<img src="https://imgur.com/fzcMdmt.png" height="80%" width="80%"/>
<br />
<br />
51. Sales laptop successfully connected via wireless connection:  <br/>
<img src="https://imgur.com/XAIxplE.png" height="80%" width="80%"/>
<br />
<br />
52. Sales tablet successfully connected via wireless connection:  <br/>
<img src="https://imgur.com/MUSuLSI.png" height="80%" width="80%"/>
<br />
<br />
53. Topology showing Sales, HR, Finance, Administration, and ICT departments Laptop and Tablets successfully connected via wireless connection:  <br/>
<img src="https://imgur.com/TzUjTDb.png" height="80%" width="80%"/>
<br />
<br />
54. Successful pings from Sales PC to HR PC:  <br/>
<img src="https://imgur.com/pic8nGC.png" height="80%" width="80%"/>
<br />
<br />
55. Successful pings from System Administrators PC to Sales PC:  <br/>
<img src="https://imgur.com/N7qDouy.png" height="80%" width="80%"/>
<br />
<br />
56. Final network topology:  <br/>
<img src="https://imgur.com/cUQXzYF.png" height="80%" width="80%"/>
<br />
<br />
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
