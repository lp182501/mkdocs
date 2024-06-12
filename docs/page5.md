# Load Balancers
## Kemp LoadMaster
This document describes the installation of the freeware version of the Kemp LoadMaster Load Balancer on a Proxmox VE.
It also describes how to migrate the management interface, a two-arm deployment and how to configure http and https.

!!! note "Note"
    The freeware version of LoadMaster is limited to 20Mbps.

??? warning "Upgrading LoadMaster"
    It is not possible to upgrade the freeware version of LoadMaster without doing a complete re-install.<br>
    This means backing up the old version, installing a new version and restoring the backup.

=== "Kemp"
    Loadmaster

=== "F5"
    F5 BIG IP 3600

=== "Traefik"
    Traefik



### Installation
First register and download the **VMWare OVF** version at [Kemp](https://freeloadbalancer.com).

=== "Proxmox VE"
    Upload the zip-file to the proxmox server using **scp**.<br>
    `scp Free-VLM-VMWare-OVF-64bit.zip <user>@<proxmox-ip>:/<directory>`
    ### with pip <small>recommended</small> { #with-pip data-toc-label="with pip" }

=== "VMWare"
    Text

## F5
F5 Big IP 3600

## Traefik
Docker container
