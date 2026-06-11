<h1>🖧 Enterprise Network Infrastructure (CCNA) Project 🌐:</h1> 

<h2>Description</h2>
 <b> I engineered a redundant enterprise network featuring: <br />
- <b> Centralized DHCP <br />
- <b> SSH and Console authentication via AAA (RADIUS) <br />
- <b> Redundant routing (HSRP) <br />
- <b> Dynamic routing (OSPF w/ MD5) <br />
- <b> NAT and basic security controls<br />
  <h2></h2>
 <b> Project Execution Timeline: 05/20/2025 - 05/27/2025 <br />
  <b> Project Status: CLOSED <br />
<h2></h2>

<p align="center">
Fully Detailed Topology of The Network Im Building  <br/>
<img src="https://i.imgur.com/67R9Ak9.png" height="80%" width="80%" alt="Fully Detailed Topology of The Network Im Building-CCNA "/>
<br />
 <h2></h2>

<p align="center">
OSPF & HSRP: The R3 output confirms OSPF neighbor adjacency with R2. It also verifies HSRP status, showing R3 in Standby mode with R2 as the Active router.  <br/>
<img src="https://i.imgur.com/0zYVWJl.png" height="80%" width="80%" alt="OSPF and HSRP PIC-CCNA "/>
<br />
 <h2></h2>

<p align="center">
AAA with RADIUS PIC 1: This configuration shows the AAA RADIUS setup using NPS on Windows Server. I have defined the routers as RADIUS clients (Authenticators) using their "Friendly Names."  <br/>
<img src="https://i.imgur.com/DmU99Bv.png" height="80%" width="80%" alt="RADIUS-CCNA "/>
<br />
 <h2></h2>

<p align="center">
AAA with RADIUS PIC 2:This NPS log on the Windows Server confirms that RADIUS is operational, showing a successful authentication for the user "Test."  <br/>
<img src="https://i.imgur.com/3Z3MoW6.png" height="80%" width="80%" alt="RADIUS- PIC2-CCNA "/>
<br />
 <h2></h2>

 <p align="center">
NAT/PAT & ACL: The R1 CLI output verifies the NAT/PAT translation table and the 'LAB_ACL' extended access list. Hits on the OSPF, ICMP, and IP permit rules confirm the policy is actively processing traffic.  <br/>
<img src="https://i.imgur.com/sDnO7xo.png" height="80%" width="80%" alt="NAT/PAT & ACL-CCNA "/>
<br />
 <h2></h2>

  <p align="center">
DHCP PIC 1: The Windows Server 2025 DHCP configuration is active. The image displays the "CCNA ULTIMATE LAB" scope (192.168.50.0), confirming the server is ready to lease IP addresses.  <br/>
<img src="https://i.imgur.com/xFjRifp.png" height="80%" width="80%" alt="DHCP PIC1-CCNA "/>
<br />
 <h2></h2>

   <p align="center">
DHCP PIC 2: This second part of the Windows Server 2025 DHCP configuration verifies the Scope Options. Specifically, it confirms the assignment of the Default Gateway (Option 003), DNS Servers (Option 006), and the parent Domain Name (Option 015).  <br/>
<img src="https://i.imgur.com/haUmRyt.png" height="80%" width="80%" alt="DHCP PIC2-CCNA "/>
<br />
 <h2></h2>

  <p align="center">
DHCP PIC 3: This confirms the DHCP relay configuration on R2 and R3. The ip helper-address 192.168.100.5 command has been applied to the LAN interfaces to forward client requests to the Windows DHCP server. <br/>
<img src="https://i.imgur.com/mjSqc26.png" height="80%" width="80%" alt="DHCP PIC3-CCNA "/>
<br />
 <h2></h2>

   <p align="center">
DHCP PIC 4: The DHCP Address Leases console verifies successful connectivity. The 'Test PC' virtual machine has been dynamically assigned an IP address, confirming the end-to-end functionality of the relay and scope <br/>
<img src="https://i.imgur.com/Y2atnpp.png" height="80%" width="80%" alt="DHCP PIC3-CCNA "/>
<br />
 <h2></h2>

<h2>💼 Skills Demonstrated: </h2>
- <b> Enterprise Routing & Switching | High Availability (HSRP) | Dynamic Routing (OSPF) | AAA Security (RADIUS) | NAT & ACL Enforcement | Windows Server (DHCP & NPAS) </b>
<h2></h2>

 <b> LAB BY MALACHI BENTON<br />
