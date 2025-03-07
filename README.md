# HomeServerProject
Documenting my process of setting up a home server

I've started the process of building a cybersecurity homelab, and the first thing I'm doing is setting up a home server. I'm using an old hp laptop with Ubuntu Server LTS as the server.
I'm currently Configuring everything and should have it up and running tomorrow.

Going to add Wireguard VPN.

I'll document the process on this github project to be able to showcase it on my portfolio website.

1/19/2025 10:47 am - Set up Proxmox for virtualization. 

1/19/2025 12:16 pm - Set up Ubuntu Server LTS as a virtual machine and Samba for filesharing

1/19/2025 1:21 pm - Configured the laptop so that when it's shut Proxmox doesn't shut down and neither do the virtual machines.
I also resized the partition on the virtual machine so it'd be more useful for filesharing through Samba, and installed JellyFin 
which is a lightweight video player that's compatible with many operating systems.

1/19/2025 2:07 pm - Set up WireGuard VPN

2/18/2025 N/A - Discovered a cryptojacking virus on my laptop while reorganizing files and checking system resource usage in task manager. The virus went undetected by antivirus scans, but was
remediated fairly easily by factory reseting my laptop and restoring to a secure backup.

3/7/2025 11:30 pm - Set up AdGuard Home on proxmox and configured DNS Block list. 
