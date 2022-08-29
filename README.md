# ADMX template for Spectre and Meltdown mitigations

## Note 
The policies provided here are now part of the more general [Security template](https://github.com/Harvester57/Security-ADMX), that you should probably check if you are looking into security-related ADMX templates :)

## Description
This template provide options to enable or disable additional protections for Spectre and Meltdown side-channel vulnerabilities.
The policies modifiy the registry values found in the Microsoft documentation available here: https://support.microsoft.com/en-us/help/4073119/protect-against-speculative-execution-side-channel-vulnerabilities-in

In the Group Policy editor (gpedit.msc), the new policy will be available under Computer Configuration > Administrative Templates > System > Microarchitectural attacks additional mitigations.