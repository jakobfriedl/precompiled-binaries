# Precompiled Binaries

Collection of useful pre-compiled binaries for enumerating and exploiting Active Directory environments or standalone Windows hosts. All binaries listed in this repository have either been downloaded from the official release page or compiled from the official source code using Visual Studio.

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

## Disclaimer

ONLY use for ethical purposes and on targets that you are permitted to attack!


## Contents

### Enumeration

| Name | Description | Download |
| --- | --- | --- |
| [SharpHound](https://github.com/BloodHoundAD/SharpHound) | Active directory enumeration and visualization | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/SharpHound.exe |
| [Seatbelt](https://github.com/GhostPack/Seatbelt) | Windows host enumeration | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/Seatbelt.exe |
| [SharpUp](https://github.com/GhostPack/SharpUp) | Privilege Escalation Checks | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/SharpUp.exe |
| [winPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/winPEAS) | Windows host enumeration | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Enumeration/winPEAS.exe | 

### Active Directory Exploitation

| Name | Description | Download | 
| --- | --- | --- |
| [Rubeus](https://github.com/GhostPack/Rubeus) | Kerberos ticket attacks and abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Rubeus.exe |
| [Whisker](https://github.com/eladshamir/Whisker) |  Shadow Credential attacks | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Whisker.exe |

### Credential Gathering

| Name | Description | Download |
| --- | --- | --- |
| [mimikatz](https://github.com/ParrotSec/mimikatz) | Credential dumping and ticket attacks | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/mimikatz.exe | 
| [SharpDPAPI](https://github.com/GhostPack/SharpDPAPI) | Credential gathering | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpDPAPI.exe |
| [SharpChrome](https://github.com/GhostPack/SharpDPAPI) | Credential gathering (specifically from Chrome) | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpChrome.exe |
| [SharpKatz](https://github.com/b4rtik/SharpKatz) | C# Port of mimikatz | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpKatz.exe |
| [SharpLAPS](https://github.com/swisskyrepo/SharpLAPS) | Dump LAPS passwords | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/SharpLAPS.exe | 
| [BetterSafetyKatz](https://github.com/Flangvik/BetterSafetyKatz) | Run latest mimikatz in memory | https://github.com/jakobfriedl/precompiled-binaries/raw/main/Credentials/BetterSafetyKatz.exe


### Local Privilege Escalation

| Name | Description | Download |
| --- | --- | --- |
| [PrintSpoofer](https://github.com/itm4n/PrintSpoofer) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/PrintSpoofer64.exe |
| [NetworkServiceExploit](https://github.com/decoder-it/NetworkServiceExploit) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/NetworkServiceExploit.exe |
| [GodPotato](https://github.com/BeichenDream/GodPotato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/GodPotato.exe |
| [JuicyPotato](https://github.com/ohpe/juicy-potato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/TokenImpersonation/JuicyPotato.exe |


### GPO Abuse

| Name | Description | Download | 
| --- | --- | --- |
| [SharpGPO](https://github.com/Dliv3/SharpGPO)  | Group Policy modification and editing | https://github.com/jakobfriedl/precompiled-binaries/blob/main/GPOAbuse/SharpGPO.exe |
| [SharpGPOAbuse](https://github.com/FSecureLABS/SharpGPOAbuse) | Group Policy exploitation and abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/GPOAbuse/SharpGPOAbuse.exe |

### Certificate Abuse

| Name | Description | Download | 
| --- | --- | --- |
| [Certify](https://github.com/GhostPack/Certify) |  Certificate abuse and enumeration | https://github.com/jakobfriedl/precompiled-binaries/raw/main/CertificateAbuse/Certify.exe |
| [PassTheCert](https://github.com/AlmondOffSec/PassTheCert) | Certificate abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/CertificateAbuse/PassTheCert.exe |
| [ForgeCert](https://github.com/GhostPack/ForgeCert) | Certificate forging | https://github.com/jakobfriedl/precompiled-binaries/raw/main/CertificateAbuse/ForgeCert.exe |