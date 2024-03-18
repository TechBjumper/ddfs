######################################################################

DELL(TM) MANAGEMENT INFORMATION BASE 5.3 README 

######################################################################

NOTE: This readme contains updated information for the Dell 
      Management Information Base (MIB) files for Dell PowerEdge(TM)
      systems.

See the Dell Support website at "support.dell.com" for the latest information.

######################################################################
CONTENTS
######################################################################

* CRITICALITY

* MIB DETAILS

* ADDITIONAL INFORMATION

######################################################################
CRITICALITY
######################################################################

3 = Optional

######################################################################
MIB DETAILS
######################################################################

The following chart provides information on the names of the MIBs,
the names of the agent that uses each MIB, and the agent location.


MIB NAME	  AGENT/HARDWARE SUPPORTED	AGENT MIB LOCATION
--------	  ------------------------	------------------	
10892.mib	  Dell OpenManage(TM) 
                  Server Administrator          "Dell Systems                    	        
                  5.3                           Console and agent" 
		                                CD 5.3
                                                "support\mibs" 
                                                directory    

adptinfo.mib*     Broadcom Gigabit NIC		"Dell Systems 
						Console and agent" 
                                                CD 5.3
                                                "support\mibs" 
                                                directory       
                                               
baspCfg.mib*      Broadcom Gigabit NIC		"Dell Systems 
						Console and agent"
                                                CD 5.3
                                                "support\mibs" 
                                                directory 
						
baspStat.mib*	  Broadcom Gigabit NIC		"Dell Systems 
						Console and agent"
                                                CD 5.3
                                                "support\mibs" 
                                                directory 
						
baspTrap.mib*	  Broadcom Gigabit NIC		"Dell Systems 
						Console and agent"
                                                CD 5.3
                                                "support\mibs" 
                                                directory 
						
DcAsfSrv.mib      Baseboard Management          "Dell Systems
                  Controller (BMC)              Console and agent"
                                                CD 5.3
                                                "support\mibs" 
                                                directory 
  
dcs3rmt.mib       Dell Remote Access            "Dell Systems  
		  Controller 5 (DRAC 5)	        Console and agent"
                                                CD 5.3
                                                "support\mibs" 
                                                directory 
                                  
dcstorag.mib      Server Administrator          "Dell Systems       
                  Storage Management            Console and agent"
                  Service 2.1                   CD 5.3
                                                "support\mibs" 
                                                directory 

dellcm.mib        Server Administrator          "Dell Systems 
                  Update Service                Console and agent"
                                                CD 5.3
                                                "support\mibs"
                                                directory   
                                   
INTELLAN.mib 	  PRO 100S, PRO 1000XT,         "Dell Systems    
                  PRO 100+ Dual Port,		Console and agent" 
                  PRO 1000F                     CD 5.3                    
                  PRO PCI-E Gigabit family      "support\mibs" 
                                                directory 


ITassist.mib 	  IT Assistant		 	"Dell Systems  
        		   	 		Console and agent"
                                                CD 5.3
                                                "support\mibs" 
                                                directory  
 

rac_host.mib      Remote access                "Dell Systems                                                                
                  out-of-band agent             Console and agent"                                               "
                                                CD 5.3
                                               "support\mibs" 
                                               directory   
                                                                                           
======================================================================
LEGEND
======================================================================

*   All four MIBs must be loaded for full management of the 
    Broadcom NIC.

NOTE: All MIBs listed above reflect support for the latest agents 
available. All MIBs are backward-compatible with earlier versions 
of the associated agent. For example, the 10892.mib supports Dell
OpenManage Server Agent 4.0-4.5 and Server Administrator 1.0-5.3.

######################################################################
ADDITIONAL INFORMATION
######################################################################

The following information describes the purpose of each previously 
listed MIBs:


10892.mib     -	 Provides detailed information about the systems
	   	 monitored by Server Administrator instrumentation
		 software. The 10892.mib is the primary MIB for
		 PowerEdge systems. 
             
adptinfo.mib  -  Provides information about Broadcom Gigabit network
                 adapters. 

baspCfg.mib   - Collectively these MIBs provide detailed information
baspStat.mib    about Broadcom Gigabit network adapters.
baspTrap.mib  

DcAsfSrv.mib  - Specifies formatting for Dell server Platform Event
		Traps generated by the Baseboard Management 
                Controller 

dcs3rmt.mib   - Provides detailed information about the remote 
                access components monitored by the Server 
                Administrator Remote Access Service.

dcstorag.mib  - Provides detailed information about the storage 
                hardware components and RAID configurations 
                monitored by Server Administrator.

dellcm.mib    - Provides detailed information about the change
		management data monitored by the Server 
                Administrator Update Service.

INTELLAN.mib  - Provides detailed information about the Intel(R) 
                PRO 100S, PRO 1000xT, PRO 100+ Dual Port, and PRO 
                1000F NIC adapters.

ITassist.mib  -	Provides definitions for traps sent by IT Assistant. 

rac_host.mib  - Provides detailed information about the components
                monitored by the remote access out-of-band software
                agent.

======================================================================

Information in this document is subject to change without notice.
(C) 2003-2007 Dell Inc. All rights reserved.

Trademarks used in this text: "Dell," "PowerEdge," and "Dell 
OpenManage" are trademarks of Dell Inc; "Intel" is a registered
trademark of Intel Corporation.

Other trademarks and trade names may be used in this document to refer 
to either the entities claiming the marks and names or their products.  
Dell Inc. disclaims any proprietary interest in trademarks and trade 
names other than its own.

November 2007