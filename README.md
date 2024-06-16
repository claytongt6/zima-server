
                                   _______________________________
                                  |                               |
                                  |          ZIMA-SERVER          |
                                  |_______________________________|
                                  

## Purpose:  Create a compact Type 1 Hypervisor to mobilize security, wireless LAN, VPN connectivity, media, and auxiliary computing.

## Hardware:
  - ZimaBoard 832 x86 computer. (can be substituted for other x86 computers however 3D models will not be compatible and some alterations
    may be required to run PROXMOX)
  - (2) SATA Hard Drives. (dual-drive sata/power cable supplied by Zima will be required) (other storage options available with pcie adapter)
  - Dual-Band WIFI repeater with RJ45 adapter. (suggest USB-powered such as Vonets VAP11AC) *required to eliminate need for travel router
    if wired ethernet unavailable onsite.

## General Overview & Notes
  1. Overview:
     - This device is designed to minimize the amount of hardware required to travel with a private LAN containing multiple computing devices,
       an access point, network security measures, a NAS, and optional pentesting equipment. This is achieved by virtualizing each machine on
       a type-1 hypervisor (in this case PROXMOX-based).
  2. Conveinience:
     a. To streamline setup time, this system is designed to use only one power cable and combine all units into a single unit.
     b. Due to the curious nature to others of raw motherboards/exposed wires, 3D models have been designed to enclose all components in a compact,
        clean body to avoid unnecessary interactions with security agent, particular airline security.
