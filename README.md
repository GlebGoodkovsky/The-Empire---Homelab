# The Empire - Homelab

**Builder:** Gleb Goodkovsky

---
## Current Hardware

- Raspberry Pi 4 Model B Rev 1.5
    - 4GB RAM
    - SanDisk 32GB SD Card
    - Raspberry Pi 4 Case, Miuzei Aluminium

- Lenovo ThinkCentre M710S SFF Office Desktop PC
    - i5 6600, 3.20GHz
    - 32GB DDR4 RAM (4x8GB - Upgraded)
    - 256GB Enterprise SSD

- Ethernet Network Switch
    - TP-Link TL-SG105
    - 5 Port Gigabit Unmanaged 

- CyberPower ST625U Standby UPS System
    - 625VA/360W
    - 8 Outlets
    - 2 USB Charging Ports
    - USB-HID Data Port (Connected to ThinkCentre)

- Connectivity & Power Spacing
    - Telus WiFi Booster (Existing hardware)
    - DEWENWILS 1 Foot Extension Cords (10-pack)
    - Random Eithernet Cables I found at the moment

---
## Current Software

- Raspberry Pi 4
    - Raspberry Pi OS Lite (64-bit)
        - Pi-hole
        - Tailscale

- Lenovo ThinkCentre
    - Proxmox VE 9.1 (Hypervisor)
        - **VM 100 (db-mc-server):**
            - Operating System: Debian 13
            - Specs:
                - 8Gb RAM
                - 3 Cores
                - 40Gb Storage

        - **LXC 101 (uptime-kuma):**
            - Operating System: Debian 12
            - Specs:
                - 0.5Gb RAM
                - 1 Cores
                - 4Gb Storage

        - **LXC 102 (syncthing):**
            - Operating System: Debian 12
            - Specs:
                - 0.5Gb RAM
                - 1 Cores
                - 5Gb Storage

        - **LXC 103 (web-static):**
            - Operating System: Debian 12
            - Specs:
                - 0.25Gb RAM
                - 1 Cores
                - 4Gb Storage

        - **LXC 104 (n8n-automation):**
            - Operating System: Debian 12
            - Specs:
                - 1Gb RAM
                - 1 Cores
                - 8Gb Storage

---
