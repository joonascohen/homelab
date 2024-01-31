# Homelab Documentation
## Purpose
My homelab is both my hobby and source of learning in a test environment. Testing technologies with no consequence, and documenting the process along the way.

## Monitoring
**Grafana**  
Hardware performance monitoring displayed through a dashboard to track things like:
  * CPU Load
  * Memory Load
  * Swap Memory
  * Individual VM Load

**Netdata**  
Another performance monitoring tool, but mainly used to send email notifications if my server gets to a critical level

Uptime Kuma  
Dashboard used to monitor if something is up or down through:
* IP
* Open Ports
* DNS
* Docker Containers
* etc

## Automation
> Still very entry level in these technologies

**Ansible**  
**Python**  
**Splunk**  
## Hardware
### New Server PC
> Currently building in a 2u form factor to go in my network rack. This is going to replace my Dell because using Linux as my daily driver is fun and efficient.
- Specs:
  - *CPU*: Ryzen 7 5000G
  - *RAM*: 32GB
  - *STORAGE*: 512GB SSD + 8TB HDD
  - *GPU*: RX6650XT
### Proxmox VE Server
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

### Dell Desktop
> Old recycled business computer. I use this as my main Linux machine and to SSH into my Proxmox VMs.
- Specs:
    - *CPU:* Intel Pentium G3220
    - *RAM:* 4GB
    - *STORAGE:* 1TB
    - *GPU:* Intel HD Graphics

## Other Documentation
I keep a collection of other notes in my personal files, written in Markdown. Some of these things include:
* IPs & Hostnames
* VM Info
* Specific program documentation
