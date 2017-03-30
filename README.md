# aggressor_scripts
A collection of useful scripts for Cobalt Strike

This repository will contain all the aggressor scripts that I feel are useful enough to warrant making public.

**powershell.cna** is a script to import and run some commonly used Powershell tools via a Beacon menu or from the Beacon console.

**bot.cna** is a little chat bot for the Cobalt Strike event log. Commands include !ping, !beacons, !listeners, !elevate, !screenshot, !downloadstring and !psexec. NOTE: This is intended to be run headless (with ./agscript).

**dcom_lateral_movement.cna** is an implementation of enigma0x3's research into code execution via DCOM.
https://enigma0x3.net/2017/01/05/lateral-movement-using-the-mmc20-application-com-object/
https://enigma0x3.net/2017/01/23/lateral-movement-via-dcom-round-2/

**ElevateKit** is forked from rsmudge, and I've added right click menu options for the privilege escalation techniques included in ElevateKit.
