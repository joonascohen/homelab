# Homelab Documentation
## Proxmox VE Server
> Old gaming laptop
- Specs:
    - *CPU:* Ryzen 9 4900 3GHz
    - *RAM:* 16GB
    - *STORAGE:* 1TB
    - *GPU:* GeForce RTX 2060
- VMs
    - Arch Linux
    - Ubuntu
    - Pop!_OS
    - GNS3VM
- LXC Containers
    - pihole
    - docker
        - Grafana
        - Netdata
        - Uptime Kuma
        - Portainer
        - InfluxDB

## Dell Desktop
> Old recycled business computer. I use this as my main Linux machine and to SSH into my Proxmox VMs.
- Specs:
    - *CPU:* Intel Pentium G3220
    - *RAM:* 4GB
    - *STORAGE:* 1TB
    - *GPU:* Intel HD Graphics

## Home Network
- Tailscale VPN
    - Peer-to-Peer wireguard VPN
    - Subnet router configuration to SSH to my whole home network while remote
- Syncthing
    - File synchronization
- Plans
    - Unifi Dream Router
    - 12u Network Rack
