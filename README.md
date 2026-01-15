# My home Server (Homelab)
A small, low-power home server built from ewaste hardware.
This repo documents my setup and decisions.
## Hardware
ewaste Toshiba SATELLITE C50-B laptop i bought for 25 euro

Intel Core i5-4005U
4gb of ram
120 ssd(cheapest i could find)
### OS
- Debian 13
### Network
- Local LAN only
- Static IP
- Port forwarding: Minecraft only
### Storage
- Single SSD
- No RAID (backup handled via Syncthing)
### Security notes
- SSH key-only login
- UFW enabled
- No services exposed except Minecraft
- Regular updates
## Services
1. Syncthing
2. Samba
3. Minecraft 1.21.10(with low player count and 8 chunks render distance)
## Why this setup
I wanted a low-power home server built from ewaste that can:
- sync files between devices
- act as a basic NAS
- Minecraft server as experiment
### Pictures
- fastfetch
<img width="659" height="263" alt="Screenshot 2026-01-14 172030" src="https://github.com/user-attachments/assets/5ca6a919-9329-440c-afe9-af029e644c59" />
- Samba working
<img width="960" height="514" alt="Screenshot 2026-01-14 172703" src="https://github.com/user-attachments/assets/e7c9260f-4f9c-4a67-b25d-3d4a6c693ee6" />
- syncthing dashboard working
<img width="944" height="443" alt="Screenshot 2026-01-14 172914" src="https://github.com/user-attachments/assets/5de05cfe-ab85-4249-bb6e-9017a52460e1" />
- minecraft server running
<img width="947" height="488" alt="Screenshot 2026-01-14 173135" src="https://github.com/user-attachments/assets/93164eb0-8042-49ed-ac7f-634af4a42252" />
