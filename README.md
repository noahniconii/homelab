# Homelab
A collection of documentation, configurations, devices, and projects from my personal homelab.

## Devices
### Synology DS212+ with 4TB + 3TB HDD in RAID
- Files storage
- Google Drive backup
- DDNS (disabled since 30/10/26 due to an unpatched DSM vulnerability)
- Reverse proxy with DDNS
### Minisforum U500-H (i3 5005u + 8GB DDR3 + 128GB SATA M.2 + 1TB HDD)
Zima OS installed
- Jellyfin
- Radarr, Sonarr and Bazarr for media management
- JDownloader2 for managing DDL
- [Homepage](https://gethomepage.dev/) as the homelab dashboard
- Portainer for Docker container management
### Raspberry Pi 3B+
- AdGuard Home for DNS filtering and ad blocking
- Homebridge for integrating devices with Apple Home
- [Statping-ng](https://statping-ng.github.io/) for monitoring my services
<br>

## Networking
- 2.5Gbps TP-Link 5 ports switch
- 1Gbps TP-Link 5 ports switch
- Freebox Ultra (8Gbps symmetrical fiber connection)
<br>

## Other devices
- Apple HomePod 1st gen (iOS 27.2) <br>
Used as a Matter hub, speaker, and HomeKit home hub
- Desktop PC : Ryzen 5 5600 · RTX 3070 · 32GB DDR4 · 6.5TB of storage · 2.5Gbps PCIe card
- HP Probook 440 G9 : Pentium Gold 8505 · 16GB DDR4 · 512GB of storage
<br>

## Homebridge Plugin
- [homebridge-wol](https://github.com/alexgustafsson/homebridge-wol#readme) <br>
Used to turn on my PC
- [homebridge-adguardhome](https://github.com/davidmerrique/homebridge-adguardhome#readme) <br>
Used to turn OFF/ON AdGuard Home
- [homebridge-tuya-platform](https://github.com/0x5e/homebridge-tuya-platform#readme) <br>
Used to make my Tuya devices compatible with Apple Home
