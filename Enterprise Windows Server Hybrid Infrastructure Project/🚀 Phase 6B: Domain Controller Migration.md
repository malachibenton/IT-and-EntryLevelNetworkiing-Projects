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
<b> Phase 6B Pictures:  </b>


 <p align="center">
Phase 6B - Domain Controller Server Migration: Planning Phase: Before beginning the domain controller migration, I verified the current FSMO role holders using the netdom query fsmo command. <br/>
<img src="https://i.imgur.com/l1HWNvp.png" height="80%" width="80%" alt="Phase 6B - Domain Controller Server Migration: Planning Phase: Before beginning the domain controller migration, I verified the current FSMO role holders using the netdom query fsmo command. "/>
<br />
 <h2></h2>




 <h2></h2>
<h2> Final Result: </h2>
<b> Successfully migrated and modernized my Active Directory domain controller infrastructure, transitioned operational responsibilities from Windows Server 2022 to Windows Server 2025, and completed the legacy server decommissioning process. </b>
 
<h2>💼 Phase 6A Skills Demonstrated: </h2>
- <b> Windows Server Backup | Disaster Recovery | Active Directory Recovery | Directory Services Restore Mode (DSRM) | wbadmin.exe | Backup Administration | Windows Server | Systems Administration </b>
<h2></h2>

<b> PROJECT BY MALACHI BENTON <br />
