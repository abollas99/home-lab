# home-lab
This repository is to describe my home lab. It will highlight what i currently accomplished and describe what more i want to achieve.

<br>

![Server Rack](labrack.jpg)


# Current

### ThinkCentre
- Proxmox: Proxmox, a tier 1 hypervisor, is the platform I selected to host virtual machines on this device. The virtual machines I’ve set up include Windows Server 2025, Windows 11 Pro, and Ubuntu. My primary objective is to experiment and gain knowledge.
- Active Directory: The three virtual machines are intended for me to experiment with Active Directory and its ability to manage other devices, whether they are running Windows or Linux.
- Windows Server 2025: Beyond Active Directory, I plan to dive deeper into its enterprise applications and familiarize myself with its tools.

### Mac Mini (M1)
- NAS: I intend to set up a NAS to familiarize myself with its usage, configurations, and potential reasons for failure. 
- Media Center (PLEX): The Media Center, primarily used for entertainment, allows me to access and watch movies and TV shows from my library.

### Omada ER605 V2 Router
- VPN: I want to set up a VPN so that I can log into my network from anywhere and access my PLEX server without having to pay for the subscription.
- VLAN: I set up a VLAN to segregate my printer and IoT devices, thereby enhancing the security of my network.
- Router: Currently, I’m using a lab network, so I have to deal with the inconvenience of a dual NAT. Once I’ve perfected my network setup, it will replace the main router. This device allows me to create VLANs, works with Omada, and operates at Gigabit speeds.

### TP-Ling SG608E Switch
- VLAN: As a smart managed switch, this one allows me to set up VLANs.
###### Unfortunately, this is not an Omada switch, so it won’t be managed by an Omada controller. Consequently, it’s likely to be replaced in the future.

### Raspberry pi 3 B+
- DNS Server: I currently have it set up running as the primary and secondary DNS Server
- Pi-Hole:
- Future Plan: 

# Whats to Come

### Raspberry pi 5 (8gb)
- Primary DNS
- Maybe move VPN here

### Maybe Firewall Hardware

### Drive Bay

### Omada capable switch

### Omada controller

### Omada Access Point
