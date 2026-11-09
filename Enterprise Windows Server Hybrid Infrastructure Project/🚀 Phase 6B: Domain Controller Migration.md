<h2>🚀 Phase 6B: Domain Controller Migration: </h2>
<h2>🔧 Key Implementations:</h2>

- <b> Conducted preliminary domain controller health checks using dcdiag and documented existing environmental events.</b>
- <b> Prepared the new Windows Server 2025 infrastructure, including static IP configuration, domain joining, and installation of the required RSAT management tools.</b>
- <b> Promoted the new server to an additional domain controller and validated Active Directory replication using repadmin /showrepl.</b>
- <b> Verified the replicated Active Directory organizational structure, Group Policy Objects, and SYSVOL contents.</b>
- <b> Successfully transferred all five FSMO roles from the legacy domain controller to the new Windows Server 2025 domain controller. </b>
- <b> Executed a controlled IP address swap to maintain DNS resolution and core directory services across the environment. </b>
- <b> Properly demoted and decommissioned the legacy domain controller, removed its orphaned Active Directory computer object, and revoked its associated certificate.</b>
- <b> Validated DC locator functionality using nltest /dsgetdc and successfully raised the domain functional level to Windows Server 2025.</b>


<h2></h2>
<h2> Phase 6B Pictures: </h2>



 <p align="center"> 
Phase 6B - Domain Controller Server Migration: Planning Phase: Before beginning the domain controller migration, I verified the current FSMO role holders using the netdom query fsmo command. <br/>
<img src="https://i.imgur.com/l1HWNvp.png" height="80%" width="80%" alt="Phase 6B - Domain Controller Server Migration: Planning Phase: Before beginning the domain controller migration, I verified the current FSMO role holders using the netdom query fsmo command. "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Planning Phase: As part of the migration preparation, I created a full Windows Server Backup of the existing domain controller. <br/>
<img src="https://i.imgur.com/fxMy3FP.png" height="80%" width="80%" alt=Phase 6B - Planning Phase: As part of the migration preparation, I created a full Windows Server Backup of the existing domain controller "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Planning Phase: Next, to prepare for the server migration, I validated Active Directory replication using repadmin /showrepl command in command prompt. <br/>
<img src="https://i.imgur.com/nekuEpF.png" height="80%" width="80%" alt=Phase 6B - Planning Phase: Next, to prepare for the server migration, I validated Active Directory replication using repadmin showrepl command in command prompt."/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Planning Phase: I documented the existing network shares on the server using the net share command before the migration. <br/>
<img src="https://i.imgur.com/shRX4IY.png" height="80%" width="80%" alt=Phase 6B - Planning Phase: I documented the existing network shares on the server using the net share command before the migration."/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Planning Phase: I performed a domain controller health check on both DC's using dcdiag /q before proceeding with the migration. <br/>
<img src="https://i.imgur.com/5xaznYL.png" height="80%" width="80%" alt=Phase 6B - Planning Phase: I performed a domain controller health check on both DCs using dcdiag q before proceeding with the migration."/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Planning Phase: I ensured the Windows Server environment was up to date with the latest updates. <br/>
<img src="https://i.imgur.com/QHF78VA.png" height="80%" width="80%" alt=Phase 6B - Planning Phase: I ensured the Windows Server environment was up to date with the latest updates."/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Planning Phase: I used PowerShell to create a script to install the required Remote Server Administration Tools (RSAT) on the new domain controllers after they have been installed. <br/>
<img src="https://i.imgur.com/DqPpAqN.png" height="80%" width="80%" alt=Phase 6B - Planning Phase: I used PowerShell to create a script to install the required Remote Server Administration Tools (RSAT) on the new domain controllers after they have been installed."/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Upgrade Phase: After creating the new DC and installing the OS, the new server was configured with a static IP address, subnet mask, default gateway, and internal DNS servers. <br/>
<img src="https://i.imgur.com/A9pp3s1.png" height="80%" width="80%" alt=Phase 6B - Upgrade Phase: After creating the new DC and installing the OS, the new server was configured with a static IP address, subnet mask, default gateway, and internal DNS servers. "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Upgrade Phase: Pinging and joining the new servers to the domain. <br/>
<img src="https://i.imgur.com/PlET4ki.png" height="80%" width="80%" alt=Phase 6B - Upgrade Phase: Pinging and joining the new servers to the domain. "/>
<br />
 <h2></h2>
 
 <p align="center"> 
Phase 6B - Upgrade Phase: Installing AD DS For Domain Controller Promotion. <br/>
<img src="https://i.imgur.com/yjNveiq.png" height="80%" width="80%" alt=Phase 6B - Upgrade Phase: Installing AD DS For Domain Controller Promotion. "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Upgrade Phase: Upon promoting the new servers to Domain Controllers, I performed an Active Directory replication health check. <br/>
<img src="https://i.imgur.com/rnJ7PMz.png" height="80%" width="80%" alt=Phase 6B - Upgrade Phase: Upon promoting the new servers to Domain Controllers, I performed an Active Directory replication health check. "/>
<br />
 <h2></h2>


 <p align="center"> 
Phase 6B - Upgrade Phase: Replication verification via Active Directory Users & Computers (ADUC) & Group Policy Management Console <br/>
<img src="https://i.imgur.com/vpyLXsa.png" height="80%" width="80%" alt=Phase 6B - Upgrade Phase: Replication verification via Active Directory Users & Computers (ADUC) & Group Policy Management Console "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Decommissioning Phase: Transferring the FSMO Roles from the Legacy MAL-DC1 (Server 2022) to the new Domain Controller MAL-DC1-25 (Server 2025). <br/>
<img src="https://i.imgur.com/1qBYXUP.png" height="80%" width="80%" alt=Phase 6B - Upgrade Phase: Transferring the FSMO Roles from the Legacy MAL-DC1 (Server 2022) to the new Domain Controller MAL-DC1-25 (Server 2025). "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Decommissioning Phase: IP Address Swap: Before demoting the legacy DC, its primary IP address was reassigned to the new Domain Controller to maintain seamless DNS resolution and core directory services across the network. <br/>
<img src="https://i.imgur.com/RtGQCtu.png" height="80%" width="80%" alt=Phase 6B - Decommissioning Phase: IP Address Swap: Before demoting the legacy DC, its primary IP address was reassigned to the new Domain Controller to maintain seamless DNS resolution and core directory services across the network. "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Demoting the Old DC, then the server was officially removed from the domain and joined to a local 'DECOM' (Decommission) workgroup. <br/>
<img src="https://i.imgur.com/4Ghx80i.png" height="80%" width="80%" alt=Phase 6B - Demoting the Old DC, then the server was officially removed from the domain and joined to a local DECOM (Decommission) workgroup.  "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B -  Decommissioning Phase: Post-demotion, the orphaned MAL-DC1 computer object is manually deleted from AD. Then, the digital certificate for MAL-DC1 legacy was revoked in Active cannot be canceled. Directory Certificate Services (AD CS). <br/>
<img src="https://i.imgur.com/Pk3Ccmn.png" height="80%" width="80%" alt=Phase 6B -  Decommissioning Phase: Post-demotion, the orphaned MAL-DC1 computer object is manually deleted from AD. Then, the digital certificate for MAL-DC1 legacy was revoked in Active cannot be canceled. Directory Certificate Services (AD CS). "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - Post-Production Integration: Verification of DC Locator. <br/>
<img src="https://i.imgur.com/dOU1XNc.png" height="80%" width="80%" alt=Phase 6B - Post-Production Integration: Verification of DC Locator. "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - RSAT Script successfully executed on the new domain controller MAL-DC1-25. <br/>
<img src="https://i.imgur.com/2O3yvrm.png" height="80%" width="80%" alt=Phase 6B - RSAT Script successfully executed on the new domain controller MAL-DC1-25. "/>
<br />
 <h2></h2>

 <p align="center"> 
Phase 6B - The domain functional level has been successfully raised to Windows Server 2025. <br/>
<img src="https://i.imgur.com/Cbouxbj.png" height="80%" width="80%" alt=Phase 6B - The domain functional level has been successfully raised to Windows Server 2025.  "/>
<br />
 <h2></h2>

  
 <h2></h2>
<h2> Final Result: </h2>
<b> Successfully migrated and modernized my Active Directory domain controller infrastructure, transitioned operational responsibilities from Windows Server 2022 to Windows Server 2025, and completed the legacy server decommissioning process. </b>

<b> PROJECT BY MALACHI BENTON <br />
