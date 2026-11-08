<h2>🚀 Phase 5B: Secure Patch Management & Centralized Authentication: </h2>
<h2>🔧 Windows Server Update Services (WSUS) with SSL Key Implementations:</h2>

- <b>✔️Provisioned dedicated storage for WSUS update content.  </b>
- <b>✔️Configured upstream and downstream WSUS architecture </b>
- <b>✔️Troubleshot DNS resolution issues preventing synchronization with Microsoft Update </b>
- <b>✔️Implemented client-side targeting through Group Policy for automated computer group assignment </b>
- <b>✔️Configured Automatic Updates to deploy approved patches during after-hours maintenance windows </b>
- <b>✔️Created a custom Web Server certificate template through Active Directory Certificate Services </b>
- <b>✔️Issued and deployed SSL certificates to secure WSUS communications and Bound certificates to Internet Information Services (IIS) and configured WSUS to operate over HTTPS on port 8531 </b>
- <b>✔️Updated Group Policy settings and validated secure client communication with the WSUS infrastructure </b>

<h2>🔧 Network Policy & Access Services (NPAS) / RADIUS Key Implementations:</h2>

- <b>✔️Deployed Network Policy and Access Services (NPAS)  </b>
- <b>✔️Integrated RADIUS authentication with Active Directory </b>
- <b>✔️Configured Cisco network infrastructure as RADIUS clients </b>
- <b>✔️Implemented AAA authentication using industry-standard RADIUS ports 1812 and 1813 </b>
- <b>✔️Created role-based Network Policies utilizing Active Directory security groups </b>
- <b>✔️Centralized network device authentication and authorization </b>
- <b>✔️Successfully validated domain-based administrative access to network infrastructure through RADIUS authenticatione </b>

<h2></h2>
<b> Phase 5B Pictures:  </b>


 <p align="center">
Phase 5B - Provisioned dedicated virtual storage (vDisk) for Windows Server Update Services (WSUS) <br/>
<img src="https://i.imgur.com/Ayft8Pc.jpeg" height="80%" width="80%" alt="Phase 5B - Provisioned dedicated virtual storage (vDisk) for Windows Server Update Services (WSUS) "/>
<br />
 <h2></h2>

  <p align="center">
Phase 5B - During the WSUS post-installation configuration process, I encountered a connectivity error: "WebException: The remote name could not be resolved." <br/>
<img src="https://i.imgur.com/4uv1Fu1.jpeg" height="80%" width="80%" alt="Phase 5B - During the WSUS post-installation configuration process, I encountered a connectivity error: "WebException: The remote name could not be resolved."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Connectivity error: "WebException: The remote name could not be resolved: Troubleshooting steps and Resolution." <br/>
<img src="https://i.imgur.com/VopA3b0.jpeg" height="80%" width="80%" alt="Phase 5B - Connectivity error: "WebException: The remote name could not be resolved: Troubleshooting steps and Resolution."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Continuing the WSUS Servers Configuration Wizard for Upstream and Downstream Server. <br/>
<img src="https://i.imgur.com/NBhapuO.jpeg" height="80%" width="80%" alt="Phase 5B - Continuing the WSUS Servers Configuration Wizard for Upstream and Downstream Server. "/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Configured WSUS to utilize client-side targeting with GPOs, allowing domain-joined systems to be automatically assigned to designated update groups through Group Policy. <br/>
<img src="https://i.imgur.com/VBDFspf.jpeg" height="80%" width="80%" alt="Phase 5B - Configured WSUS to utilize client-side targeting with GPOs, allowing domain-joined systems to be automatically assigned to designated update groups through Group Policy "/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Configuring SSL for WSUS: To secure WSUS communications, I created a custom web server certificate template called (WSUS SSL Cert Temp). <br/>
<img src="https://i.imgur.com/R5NuQEW.jpeg" height="80%" width="80%" alt="Phase 5B - Configuring SSL for WSUS: To secure WSUS communications, I created a custom web server certificate template called (WSUS SSL Cert Temp)"/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Configuring SSL for WSUS: The WSUS server successfully enrolled for and was issued the custom (WSUS SSL Cert). <br/>
<img src="https://i.imgur.com/APo6GGg.jpeg" height="80%" width="80%" alt="Phase 5B - Configuring SSL for WSUS: The WSUS server successfully enrolled for and was issued the custom (WSUS SSL Cert)."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Configuring SSL for WSUS: After the WSUS SSL certificate was issued, it was bound to the WSUS website within Internet Information Services (IIS) on port 8531. <br/>
<img src="https://i.imgur.com/uIqInn9.jpeg" height="80%" width="80%" alt="Phase 5B - Configuring SSL for WSUS: After the WSUS SSL certificate was issued, it was bound to the WSUS website within Internet Information Services (IIS) on port 8531."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Configuring SSL for WSUS: Requring the use of SSL For the WSUS website directories shown below. <br/>
<img src="https://i.imgur.com/6VBqSho.jpeg" height="80%" width="80%" alt="Phase 5B - Configuring SSL for WSUS: Requring the use of SSL For the WSUS website directories shown below."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - I updated the Group Policy Configuration used by domain endpoints to point to the secure HTTPS WSUS URL rather than the previous HTTP endpoint, the endpoint successfully received the new configuration. <br/>
<img src="https://i.imgur.com/6MQ63ci.jpeg" height="80%" width="80%" alt="Phase 5B - I updated the Group Policy nfiguration used by domain endpoints to point to the secure HTTPS WSUS URL rather than the previous HTTP endpoint, the endpoint successfully received the new configuration."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - To validate the SSL configuration, I tested connectivity to the WSUS administration interface over HTTPS on port 8531. <br/>
<img src="https://i.imgur.com/qOVp18h.jpeg" height="80%" width="80%" alt="Phase 5B - To validate the SSL configuration, I tested connectivity to the WSUS administration interface over HTTPS on port 8531."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - After registering MAL-RTR1 as a RADIUS client, I created a Network Policy within NPAS called "RADIUS Network Login Policy" to control administrative access to the Cisco router through centralized authentication. <br/>
<img src="https://i.imgur.com/zTGS5Vv.jpeg" height="80%" width="80%" alt="Phase 5B - After registering MAL-RTR1 as a RADIUS client, I created a Network Policy within NPAS called "RADIUS Network Login Policy to control administrative access to the Cisco router through centralized authentication. "/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - Configured Network Policy and Access Services (NPAS) to provide centralized RADIUS authentication and authorization services for network infrastructure devices. <br/>
<img src="https://i.imgur.com/4ANhblT.jpeg" height="80%" width="80%" alt="Phase 5B - Configured Network Policy and Access Services (NPAS) to provide centralized RADIUS authentication and authorization services for network infrastructure devices."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - On the router, AAA and RADIUS were configured to communicate with the NPAS server using the industry-standard RADIUS ports 1812 (Authentication) and 1813 (Accounting). <br/>
<img src="https://i.imgur.com/IHNTSfT.jpeg" height="80%" width="80%" alt="Phase 5B - On the router, AAA and RADIUS were configured to communicate with the NPAS server using the industry-standard RADIUS ports 1812 (Authentication) and 1813 (Accounting)."/>
<br />
 <h2></h2>

   <p align="center">
Phase 5B - To validate the RADIUS and Active Directory integration, I signed out of the router's local administrative account and attempted authentication using my domain credentials. The router CLI output confirms the successful domain-based login, while the corresponding NPAS Event Viewer logs provide evidence. <br/>
<img src="https://i.imgur.com/ponlVYE.jpeg" height="80%" width="80%" alt="Phase 5B - validate the RADIUS and Active Directory integration."/>
<br />
 <h2></h2>

<h2>💼 Phase 5B Skills Demonstrated: </h2>
- <b> WSUS Administration | Patch Management | SSL/TLS | Group Policy | NPAS / NPS | RADIUS | AAA Authentication | Active Directory | Cisco Networking </b>
<h2></h2>

<b> PROJECT BY MALACHI BENTON <br />


