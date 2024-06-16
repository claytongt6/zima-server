
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

## Notes and Setup Process Overview 
### Intention:
     1. This device is designed to minimize the amount of hardware required to travel with a private LAN containing multiple computing devices,
       an access point, network security measures, a NAS, and optional pentesting equipment. This is achieved by virtualizing machines on
       a type-1 hypervisor (in this case PROXMOX-based).
       
### Conveinience:
     1. To streamline setup time, this system is designed to use only one power cable and combine all units into a single unit.
     2. Due to the curious nature to others of raw motherboards/exposed wires, 3D models have been designed to enclose all components in a compact,
        clean body to avoid unnecessary interactions with security agent, particular airline security.

### Wireless Access:
    1. The hypervisor will be configured for interfacing via one of the ethernet ports. Because of this, internet access will not be universally 
        
### Setup Process Overview:
    1. 3D print enclosure components & assemble hardware.
    2. Install and configure PROXMOX.
    3. Create virtual network security and VPN machines.
    4. Setup access point.
    5. Create and configure NAS.
    6. Create other virtual machines as needed.
