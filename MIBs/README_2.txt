
3Com Switch 7700 Family MIB Package 
for SW Agent Ver 3.0x Last updated 12th May 2005 


This document provides the following information:

1. 3Com Products and Software Agents compatible with this MIB Package
2. MIB files contained in this Package
3. Additional MIB files obtainable from 3Com Technical Support
4. Changes at this MIB Package
5. Recommendations when Loading MIB Files contained in this Package
6. 3Com's World Wide Web site
_____________________________________________________________________

1. 3Com Products and Software Agents compatible with this MIB package

This MIB package is compatible with the ver 3.0x agent feature
set for those products whose software agent filename is prefixed by
"77". 

  
It provides support for the following Switch 7700 family 
switches: 

Switch 7700 4-slot         3C16870
Switch 7700 7-slot         3C16850
Switch 7700R 8-slot        3C16852

Switch 7700 4-slot Gigabit Ethernet Fabric Module                3C16872
Switch 7700 7-slot Gigabit Ethernet Fabric Module                3C16857
Switch 7700R 8-slot Gigabit Ethernet Redundant Switching Fabric  3C16857R


_____________________________________________________________________


2. MIB Files contained in this package

Both IETF Standards based MIBs (RFCs) and 3Com proprietary MIBs are 
included in this package. MIB files marked with 

    * are not included in this package and you should contact 3Com  
      Technical Support for the latest versions. 
   ** are used to import definitions from, any operational mib items  
      defined within these files are not implemented.

MIB files marked as "Mandatory" contain definitions used by MIB files 
later in the loading sequence and as such should not be omitted. Other 
MIB files may be omitted but the functionality they control will then 
not be accessible via SNMP management.

IETF RFCs
                  RFC1213.mib      MIB II                     Mandatory
                  RFC1215.mib      MIB II Traps
                  RFC1315.mib      Frame Relay DTE Mib
                **RFC2578.mib      SNMPv2-SMI                 Mandatory
                **RFC2579.mib      SNMPv2-TC                  Mandatory
                **ianaiftype.mib                              Mandatory
                **RFC1907.mib      SNMPv2-MIB                 Mandatory
                **RFC2580.mib      SNMPv2-CONF                Mandatory
                **RFC2571.mib      SNMP-Framework-MIB         Mandatory
                **RFC2851.mib      INET-Addresses             Mandatory
                  RFC2572.mib      SNMP-MPD-MIB
                  RFC2273.mib      SNMP-NOTIFICATION-MIB
                  RFC1471-PPP-LCP.mib PPP-LCP-MIB
                  RFC1473-PPP-IP.mib  PPP-IP-NCP-MIB
                  ianaAddressFamilyNumbers.mib
                  RFC2233.mib      If Table Extensions 
                  RFC1493.mib      Bridge MIB                 Mandatory
                  RFC1657.mib      BGP4-MIB
                  RFC1724.mib      RIP V2 Extensions
                  RFC2674.mib      Bridge Mib and Vlan Extensions 
                  RFC2668.mib      802.3 Mau 
                  RFC2665.mib      Etherlike MIB 
                  RFC2618.mib      RADIUS Authentication Client Mib
                  RFC2620.mib      Radius Accounting Client Mib
		  RFC1850.mib      OSPFv2
		  RFC2737.mib      Entity MIB 
		  RFC2925.mib      DISMAN-PING-MIB
		  RFC2573.mib      SNMP-TARGET-MIB
		  RFC2574.mib      SNMP-USER-BASED-SM-MIB
		  RFC2575.mib      SNMP-VIEW-BASED-ACM-MIB
		  RFC2787.mib      VRRP-MIB
		  RFC2819.mib      RMON-MIB
		  RFC2613.mib      SMON-MIB
		  
IEEE MIBS
                 *IEEE802.3adLAG    Link Aggregation MIB
		 *IEEE802.1xPAE.mib Port Access Control MIB
                 

3Com Proprietary MIBs

                  3Com0045.mib     3Com Products MIB,       Mandatory
                  3Com0004.mib     3Com Generic Branches,   Mandatory

                  a3com-huawei-8021x-ext.mib
                  a3com-huawei-acl.mib
                  a3com-huawei-config-man.mib
                  a3com-huawei-device.mib
                  a3com-huawei-dhcpr.mib
                  a3com-huawei-dhcps.mib
                  a3com-huawei-entity-ext.mib
                  a3com-huawei-entity-vendortype-oid.mib
                  a3com-huawei-flash-man.mib
                  a3com-huawei-ftm.mib
                  a3com-huawei-hgmp.mib
                  a3com-huawei-lag.mib
                  a3com-huawei-mlsr.mib
                  a3com-huawei-mpls-ldp.mib
                  a3com-huawei-mpls-lsr.mib
                  a3com-huawei-mpls-vpn.mib
                  a3com-huawei-ndec.mib
                  a3com-huawei-oid.mib
                  a3com-huawei-ping.mib
                  a3com-huawei-qos.mib
                  a3com-huawei-s6506-qacl.mib
                  a3com-huawei-splat-arp.mib
                  a3com-huawei-splat-devm.mib
                  a3com-huawei-splat-dhcp.mib
                  a3com-huawei-splat-igsp.mib
                  a3com-huawei-splat-inf.mib
                  a3com-huawei-splat-mam.mib
                  a3com-huawei-splat-mix.mib
                  a3com-huawei-splat-performance.mib
                  a3com-huawei-splat-qos.mib
                  a3com-huawei-splat-rstp.mib
                  a3com-huawei-splat-smonext.mib
                  a3com-huawei-splat-trap.mib
                  a3com-huawei-splat-vlan.mib
                  a3com-huawei-srm.mib
                  a3com-huawei-sys-man.mib
                  a3com-huawei-trng.mib
                  a3com-huawei-userlog.mib
                  a3com-huawei-vlan.mib
                  a3com-huawei-voice-vlan.mib
_____________________________________________________________________


3. Additional MIB Files obtainable from 3Com Technical Support

 
The definitions of the following 3Com proprietary MIBs are subject to 
change,for the latest version please contact 3Com Technical Support.
                  
 
No Mibs applicable to this package.

IEEE802.3adLAG  can be obtained from the following link
http://www.ieee802.org/3/publication/ad/IEEE8023-LAG-MIB.txt
_____________________________________________________________________

4. Changes at this MIB Package

This is the first release of the Mib package for the Switch 7700 

Note:-

RFC2863 Supercedes RFC2233   "IF-MIB"
RFC3291 Supercedes RFC2851   "INET_ADDRESS-MIB"

_____________________________________________________________________

5. Recommendations when loading MIB Files.

Depending on the MIB browser or Network Management Platform being
used, the MIB files may need to be loaded in the sequence 
listed in Section 2.

If you are using multiple types of 3Com products, make sure  that 

    . The most recent files (3Com004.mib & 3Com045.mib) are loaded 
      from one of the mib packages.

    . Where a mib file supercedes previous files, only use that file. 
      e.g. if 3Com0481 supercedes 3Com0049 only use 3Com0481.

HP Openview users are recommended to use the HP Openview Integration 
pack available from 3Com.   
_____________________________________________________________________

6. 3Com's World Wide Web site

Access the latest networking information on the 3Com Corporation World 
Wide Web site by entering our URL into your Internet browser:

http://www.3com.com/
   
_____________________________________________________________________

(R) means registered trademark.

3Com and SuperStack are registered trademarks of 3Com Corporation.

Other trademarks are the property of their respective owners.

Copyright (c) 2005 3Com Corporation. All Rights Reserved.


