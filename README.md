# Precompiled Binaries & AD Toolset

Collection of useful tools, scripts and pre-compiled binaries for enumerating and exploiting Active Directory environments or standalone Windows hosts. All binaries listed in this repository have either been downloaded from the official release page or compiled from the official source code using Visual Studio.

## Table of Contents
- [Precompiled Binaries](#precompiled-binaries)
  - [Table of Contents](#table-of-contents)
  - [Disclaimer](#disclaimer)
  - [Contents](#contents)
    - [Enumeration](#enumeration)
    - [Active Directory Exploitation](#active-directory-exploitation)
    - [Credential Gathering](#credential-gathering)
    - [Local Privilege Escalation](#local-privilege-escalation)
    - [GPO Abuse](#gpo-abuse)
    - [Certificate Abuse](#certificate-abuse)
    - [Scripts](#scripts)



## Disclaimer

ONLY use for ethical purposes and against targets that you are permitted to attack!


## Contents

### Enumeration

| | Name | Description | Download |
|---| --- | --- | --- |
|★| [SharpHound](https://github.com/BloodHoundAD/SharpHound) | Active directory enumeration and visualization | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/SharpHound.exe |
|| [Seatbelt](https://github.com/GhostPack/Seatbelt) | Windows host enumeration | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/Seatbelt.exe |
|| [SharpUp](https://github.com/GhostPack/SharpUp) | Privilege Escalation Checks | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/SharpUp.exe |
|| [winPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/winPEAS) | Windows host enumeration | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/winPEAS.exe | 
|| [SharpView](https://github.com/tevora-threat/SharpView) | C# Port of PowerView.ps1 | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/SharpView.exe |
|★| [NoPowerShell](https://github.com/bitsadmin/nopowershell) | Execute PowerShell cmdlets in memory | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/NoPowerShell.exe

### Active Directory Exploitation

| | Name | Description | Download | 
|---| --- | --- | --- |
|★| [Rubeus](https://github.com/GhostPack/Rubeus) | Kerberos ticket attacks and abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Rubeus.exe |
| | [Whisker](https://github.com/eladshamir/Whisker) |  Shadow Credential attacks | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Specific/Whisker.exe |
| | [ADFSDump](https://github.com/mandiant/ADFSDump) | Dump information from ADFS to be used with ADFSpoof | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Specific/ADFSDump.exe | 
|★| [SharpSCCM](https://github.com/Mayyhem/SharpSCCM) | Interaction with SCCM for lateral movement | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Specific/SharpSCCM.exe

### Credential Gathering

| | Name | Description | Download |
| --- | --- | --- | --- |
|| [mimikatz](https://github.com/ParrotSec/mimikatz) | Credential dumping and ticket attacks | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/mimikatz.exe | 
|| [SharpDPAPI](https://github.com/GhostPack/SharpDPAPI) | Credential gathering | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpDPAPI.exe |
|★| [SharpChrome](https://github.com/GhostPack/SharpDPAPI) | Credential gathering (specifically from Chrome) | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpChrome.exe |
|| [SharpKatz](https://github.com/b4rtik/SharpKatz) | C# Port of mimikatz | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpKatz.exe |
|| [SharpLAPS](https://github.com/swisskyrepo/SharpLAPS) | Dump LAPS passwords | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpLAPS.exe | 
|| [BetterSafetyKatz](https://github.com/Flangvik/BetterSafetyKatz) | Run latest mimikatz in memory | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/BetterSafetyKatz.exe |
|| [GMSAPasswordReader](https://github.com/rvazarkar/GMSAPasswordReader) | Dump GMSA passwords | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/GMSAPasswordReader.exe | 


### Local Privilege Escalation

|| Name | Description | Download |
|---| --- | --- | --- |
|| [PrintSpoofer](https://github.com/itm4n/PrintSpoofer) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/PrintSpoofer64.exe |
|| [NetworkServiceExploit](https://github.com/decoder-it/NetworkServiceExploit) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/NetworkServiceExploit.exe |
|| [GodPotato](https://github.com/BeichenDream/GodPotato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/GodPotato.exe |
|| [JuicyPotato](https://github.com/ohpe/juicy-potato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/JuicyPotato.exe |
|★| [SharpEfsPotato](https://github.com/bugch3ck/SharpEfsPotato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/SharpEfsPotato.exe |

### GPO Abuse

|| Name | Description | Download | 
|---| --- | --- | --- |
|| [SharpGPO](https://github.com/Dliv3/SharpGPO)  | Group Policy modification and editing | https://github.com/jakobfriedl/precompiled-binaries/blob/main/GPOAbuse/SharpGPO.exe |
|| [SharpGPOAbuse](https://github.com/FSecureLABS/SharpGPOAbuse) | Group Policy exploitation and abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/GPOAbuse/SharpGPOAbuse.exe |

### Certificate Abuse

|| Name | Description | Download | 
|---| --- | --- | --- |
|| [Certify](https://github.com/GhostPack/Certify) |  Certificate abuse and enumeration | https://github.com/jakobfriedl/precompiled-binaries/raw/main/CertificateAbuse/Certify.exe |
|| [PassTheCert](https://github.com/AlmondOffSec/PassTheCert) | Certificate abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/CertificateAbuse/PassTheCert.exe |
|| [ForgeCert](https://github.com/GhostPack/ForgeCert) | Certificate forging | https://github.com/jakobfriedl/precompiled-binaries/raw/main/CertificateAbuse/ForgeCert.exe |

### Scripts
|| Name | Description | Download | 
|---| --- | --- | --- |
|★| [PowerView](https://github.com/PowerShellMafia/PowerSploit/tree/master/Recon) | Enumeration |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/PowerView.ps1 |
|★| [Powermad](https://github.com/Kevin-Robertson/Powermad) | MachineAccountQuota and DNS Exploitation |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/Powermad.ps1 |
|| [Inveigh](https://github.com/Kevin-Robertson/Inveigh) | MitM Attacks & Spoofing |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/Inveigh.ps1 |
|| [PowerUp](https://github.com/PowerShellMafia/PowerSploit/tree/master/Privesc) | Windows Privilege Escalation |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/PowerUp.ps1 |
|| [PowerUpSQL](https://github.com/NetSPI/PowerUpSQL) | SQL Server Enumeration and Exploitation |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/PowerUpSQL.ps1 |
