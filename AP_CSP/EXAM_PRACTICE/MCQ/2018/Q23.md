### The figures represent different ways of configuring a network of physically linked computers labeled P, Q, R, and S. A line between two computers indicates that the computers can communicate directly with each other

### In which configuration is it NOT possible to have redundant routing between computers P and S?

### A) ![](https://assets.learnosity.com/organisations/537/2e4198d8-f2ce-45d2-ae94-e0c208a14f61.jpg)
### B) ![](https://assets.learnosity.com/organisations/537/8c1fce67-65d4-4c32-a019-6697d38e81ae.jpg)
### C) ![](https://assets.learnosity.com/organisations/537/19f05636-abdf-40a9-9e89-ca00607a821a.jpg)
### D) ![](https://assets.learnosity.com/organisations/537/ae6cbb61-5da3-49b6-ba9b-db4c452c3a47.jpg)

### Answer B
This option is correct. Redundant routing is impossible if there is only one possible path from one device to another. There is only one possible path from P to S (P to R to Q to S).

_____

**Research**

**Redundant Routing Overview**  
Redundant routing in the internet ensures network reliability by providing multiple paths for data packets to travel between sources and destinations. If a primary route fails due to link outages, hardware issues, or congestion, dynamic protocols like BGP, OSPF, or VRRP automatically detect the problem and reroute traffic through backup paths, minimizing downtime. [synchronet](https://synchronet.net/redundant-routing/)

**Key Benefits**  
This design enhances fault tolerance and load balancing, distributing traffic to prevent bottlenecks and support high availability. For instance, BGP enables diverse ISP connections for failover, while OSPF recalculates optimal paths in real time. [zenarmor](https://www.zenarmor.com/docs/network-basics/what-is-redundant-routing)

**Implementation Examples**  
Networks often use physical redundancies like extra cables or geographically dispersed points of presence, combined with protocols for seamless failover in seconds. Studies show this approach can reduce outages by up to 50% and boost productivity. [axclusive.com](https://www.axclusive.com.sg/what-is-redundant-routing/)
