# wsdd2
WSD/LLMNR Discovery/Name Service Daemon

With Microsoft turning off SMB1 feature completely on Windwos 10, any Samba shares on the 
local network become invisible to Windwos 10 computers. That's due to the fact that SMB1 is 
required for Computer Browser service to function.

Newer Windows systems can use WSD (Web Services for Devices) to discover shares hosted on 
other Windows computers while Linux systems normally utilize mNDS/DNS-SD for service discovery. 
Microsoft is moving to support mDNS/DNS-SD, but not yet there.

The primary purpose of this project is to enable WSD on OpenMediaVault so that network shares
hosted on a OMV3 box can appear in Windows File Explorer / Network.

The original source code was taken from Netgear ReadyNAS OS v6.8.0 published at https://kb.netgear.com/2649/NETGEAR-Open-Source-Code-for-Programmers-GPL.

So far only minimum changes have been made to let it run on my OMV3 box.

