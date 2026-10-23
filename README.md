# Basic-LAN-setup-HomeLab
Cisco Packet Tracer small office LAN with wired and wireless networks
# Basic LAN Setup Homelab

A small office network built in Cisco Packet Tracer.

## Topology
- Three wired PCs and one printer connected through a switch
- One laptop connected over Wi-Fi
- Router-0 provides DHCP for both networks
- WirelessRouter-0 acts as an access point

## Address plan
- Wired network: 192.168.1.0/24, gateway 192.168.1.1
- Wireless network: 192.168.2.0/24, gateway 192.168.2.1
- Printer: 192.168.1.101
- Access point management address: 192.168.2.2

## Verification
- PC-0 reached the wired gateway and printer with 0% packet loss
- Laptop-0 reached the wireless gateway with 0% packet loss

