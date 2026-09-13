# Proxmox
**Proxmox Resources &amp; Guides**

**Virtualization HowTo / Brandon Lee**  
https://www.virtualizationhowto.com/category/proxmox/  

**Awesome Proxmox VE Resources**  
https://github.com/Corsinvest/awesome-proxmox-ve  

**Mr. PlanB**  
https://www.mrplanb.com/proxmox  

**VirtIO Drivers**  
https://github.com/virtio-win/virtio-win-pkg-scripts

**Community Scripts**  
https://community-scripts.org  

**Terminal UI**  
https://github.com/devnullvoid/pvetui  

**ProxCenter**  
https://github.com/adminsyspro/proxcenter-ui  

**PegaProx**  
https://github.com/PegaProx/project-pegaprox  

**ProxLB**  
https://github.com/credativ/ProxLB

**ProxMorph**  
https://github.com/IT-BAER/proxmorph

**ProxMenux**  
https://proxmenux.com/  
https://github.com/MacRimi/ProxMenux  

**ProxSave**  
https://github.com/tis24dev/proxsave  

**Monitoring**  
https://github.com/rcourtman/Pulse  
https://uptimekuma.org/  
https://checkmk.com/  

**Reporting**  
https://pveviewer.com   
https://github.com/Corsinvest/cv4pve-report  
https://github.com/AungThuMyint/ProxmoxReportGenerator  


**Even Number of Nodes - use QDevice for Cluster Quorum**  
https://pve.proxmox.com/wiki/Cluster_Manager#_corosync_external_vote_support  
https://pve.proxmox.com/pve-docs/chapter-pvecm.html#_corosync_external_vote_support  


**Cluster Mgmt - Floating VIP w/KeepAliveD**  
https://www.ilogikal.com/2025/03/how-to-set-up-a-floating-vip-for-proxmox-cluster-management-with-keepalived/  

**Quick Utility Installs**  

**Install ClusterShell**  
apt update  
apt install clustershell -y  
clush --help  
https://clustershell.readthedocs.io/en/latest/tools/clush.html  

**Install LM-Sensors package**  
--Can also be used by Pulse and other monitoring tools  
Install:  apt update && apt install lm-sensors -y  
Run sensor detection/setup:  sensors-detect
Run Sensors: sensors

**Install NVME-CLI**  
apt install nvme-cli -y  
nvme list  

**Install SmartMonTools**  
apt install smartmontools -y  
smartctl -a /dev/sda  
smartctl -t short /dev/sda  
smartctl -t long /dev/sda  

**Install IPERF**  
apt install iperf3 -y  
iperf3 -s  
iperf3 -c 10.10.10.X  

**Install ETHTOOL**  
apt install ethtool -y  
ethtool nic3  *Current NIC settings  
ethtool -i nic3  *Driver & firmware info  
ethtool -k nic3  *Offload information  

**Install UPS Control (NUT)**  
apt install nut -y  


