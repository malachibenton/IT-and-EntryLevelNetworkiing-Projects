<h2>🚀 Phase 6A: Windows Server Backup & Recovery: </h2>
<h2>🔧 Key Implementations:</h2>

- <b>✔️Created a dedicated Active Directory service account for backup operations and delegated required permissions through the Backup Operators group.  </b>
- <b>✔️Deployed a centralized backup repository using a secured hidden SMB share (Backups$) </b>
- <b>✔️Configured automated backup schedules using both Windows Server Backup and wbadmin </b>
- <b>✔️Protected critical server components including:
 Bare Metal Recovery (BMR),
System State,
EFI System Partition,
Operating System Volumes,
WSUS Drives,
File Share Drives,
</b>

- <b>✔️Successfully validated backup operations through both graphical and command-line administration tools </b>
- <b>✔️Configured Directory Services Restore Mode (DSRM) for Active Directory recovery scenarios </b>
- <b>✔️Performed a successful System State Recovery using wbadmin and the latest backup versions </b>
- <b>✔️Validated Active Directory disaster recovery procedures by restoring the System State, which contains the NTDS database, SYSVOL, registry settings, and critical domain controller configuration data </b>


<h2></h2>
<b> Phase 6A Pictures:  </b>


 <p align="center">
Phase 6A - Configured a dedicated Windows Server Backup service account called (ADBackup SVC) and delegated membership to the Backup Operators security group. <br/>
<img src="https://i.imgur.com/5nMtqmp.png" height="80%" width="80%" alt="Phase 6A - Configured a dedicated Windows Server Backup service account called (ADBackup SVC) and delegated membership to the Backup Operators security group. "/>
<br />
 <h2></h2>

 <p align="center">
Phase 6A - Created a dedicated hidden SMB share (Backups$) to serve as a centralized backup storage location for server workloads. <br/>
<img src="https://i.imgur.com/f4WyGFd.png" height="80%" width="80%" alt="Phase 6A - Created a dedicated hidden SMB share (Backups$) to serve as a centralized backup storage location for server workloads. "/>
<br />
 <h2></h2>
  
 <p align="center">
Phase 6A - I Configured backups schedules using the "Windows Server Backup" GUI to a dedicated network backup repository. <br/>
<img src="https://i.imgur.com/lBlGTIn.png" height="80%" width="80%" alt="Phase 6A - I Configured backups schedules using the Windows Server Backup GUI to a dedicated network backup repository. "/>
<br />

 <p align="center">
Phase 6A - Configuring & Executing Windows Backups PT2: I also configured backups schedules using the wbadmin.exe (Windows Server Backup Command-Line Utility). <br/>
<img src="https://i.imgur.com/QyEuuaT.png" height="80%" width="80%" alt="Phase 6A - Configuring & Executing Windows Backups PT2: I also configured
backups schedules using the wbadmin.exe (Windows Server Backup Command-Line Utility)"/>
<br />

 <p align="center">
Phase 6A - A Backup job was then successfully executed and validated via the Windows Server Backup utility (wbadmin) CLI using the previously configured backup schedule. <br/>
<img src="https://i.imgur.com/BruxRgZ.png" height="80%" width="80%" alt="Phase 6A - A Backup job was then successfully executed and validated via the Windows Server Backup utility (wbadmin) CLI using the previously configured backup schedule."/>
<br />

 <p align="center">
Phase 6A - Configured the Domain Controller to boot into Safe Mode Directory Services Restore Mode (DSRM).  <br/>
<img src="https://i.imgur.com/TvJdhuB.png" height="80%" width="80%" alt="Phase 6A - Configured the Domain Controller to boot into Safe Mode Directory Services Restore Mode (DSRM)."/>
<br />

 <p align="center">
Phase 6A - A recovery operation was successfully initiated using the wbadmin.exe command-line utility and the most recent available backup version  <br/>
<img src="https://i.imgur.com/elUqWyK.png" height="80%" width="80%" alt="Phase 6A - A recovery operation was successfully initiated using the wbadmin.exe command-line utility and the most recent available backup version."/>
<br />



 <h2></h2>
<h2>💼 Phase 6A Skills Demonstrated: </h2>
- <b> Windows Server Backup | Disaster Recovery | Active Directory Recovery | Directory Services Restore Mode (DSRM) | wbadmin.exe | Backup Administration | Windows Server | Systems Administration </b>
<h2></h2>

<b> PROJECT BY MALACHI BENTON <br />


