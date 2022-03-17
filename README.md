# Tailscale-LXC

This is a guide on how to install Tailscale within an LXC which is already behind a physical router such as PfSense.

Network Topology:
Internet > WAN > PfSense > LAN > Proxmox > Tailscale LXC

Operating System: Proxmox VE 6.4.x

Container (LXC) Host Operating System: Ubuntu 18.04 Standard
