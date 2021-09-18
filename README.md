# OMEN5_laptop_EFI_hackintosh

MrProphet's EFI for OMEN5 15-dc1060tx(with switched WIFI/BT Broadcom card and extended RAM &amp; HDD)  

# Spec

OC 6.8 & Big Sur 11.5
Laptop OMEN by HP  15-dc1060tx  
**CPU**  intel i5 9300H  
**iGPU** Intel UHD Graphics 630  
**dGPU** nVidia GTX 1650  
**RAM** samsung DDR4 2667MHz 8GB*2  
**SSD** WDC PC SN720 512GB  
**HDD** WD 10SPZX 1TB  
**WIFI & Bluetooth** Broadcom 94352z *(Blocked 3 pins on that chip for Windows Compatibility)* *  

# Curruently working functions

macOS big sur 11.5  
working apple id login*\*: apple store, icloud, apple music  
WIFI/BT card: connectivity features like handoff, airdrop, sidecar  
Hardware acceleration  
CPU power optimization: CPU friend &amp; CPU friendfriend  
HiDPI**\*: Using RDM 1440 * 810 144Hz on 1080p screen  
Trackpad &amp; buttons: Rebulid VoodooPS2controller.kext  
USBPorts**\*\*: made USBPorts.kext using Hackintool

# Note

*: If not blocked: Random freeze in Windows  
**: Some info in _Platforminfo_ part of the config.plist is deleted. Please generate your own!  
***: HiDPI file is not included in this repo. Pls google.  
****: USBPorts.kext are made with my specs. Pls use with caution because my BT port is not the same with the original port after BT card switch.

# Curruent Problem

~~Poor performance every time on fresh boot. After a sleep-wake, performance is back up.~~ Fixed by rebuilding SSDTs.

## HAPPY HACKINTOSHING!
