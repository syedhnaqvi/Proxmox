# Proxmox VE
Installing Proxmox Baremetal HV VE
![Proxmox](https://img.shields.io/badge/Proxmox-virtualization-orange)


## Hardware Requirements

<h3>Recommended Hardware</h3>
<ul>
<li>Intel 64 or AMD64 with Intel VT/AMD-V CPU flag.
<li>Memory, minimum 2 GB for OS and Proxmox VE services. Plus designated memory for guests. For Ceph or ZFS additional memory is required, approximately 1 GB memory for every TB used storage.
<li>Fast and redundant storage, best results with SSD disks.
<li>OS storage: Hardware RAID with batteries protected write cache (“BBU”) or non-RAID with ZFS and SSD cache.
<li>VM storage: For local storage use a hardware RAID with battery backed write cache (BBU) or non-RAID for ZFS. Neither ZFS nor Ceph are compatible with a hardware RAID controller. Shared and distributed storage is also possible.
<li>Redundant Gbit NICs, additional NICs depending on the preferred storage technology and cluster setup – 10 Gbit and higher is also supported.
<li>For PCI(e) passthrough a CPU with VT-d/AMD-d CPU flag is needed.
</li>
</ui>

<h2>For Evaluation</h2>

<h3>Minimum Hardware (for testing only)</h3>
<ui>
<li>
<li>CPU: 64bit (Intel 64 or AMD64)
<li>Intel VT/AMD-V capable CPU/Mainboard (for KVM full virtualization support)
<li>Minimum 1 GB RAM
<li>Hard drive
<li>One NIC
</li>
</ui>

<h2>Objective</h2>
This lab includes steps for installing Proxmox for leanring and educational purpose . Not meant for any production environments

### Skills Learned

- What is Proxmox
- Installing Proxmox
- Setting up Proxmox.

### What is Proxmox ?
<p>Proxmox Virtual Environment is a complete open-source platform for enterprise virtualization. With the built-in web interface you can easily manage VMs and containers, software-defined storage and networking, high-availability clustering, and multiple out-of-the-box tools using a single solution.</p>

<a href="https://www.proxmox.com/en/">About Proxmox</a>

<a href="https://www.proxmox.com/en/downloads">Download</a>


### Project Hardware Used

- AMD Ryzen 7 processor 12 Core 
- USB Drive 16 GB
- 32 Gb RAM

### Proxmox Installation & Setup Videos
<p>These vidoes were used this project to install and steup proxmox</p>

<a href="https://youtu.be/xD9Xyt2mdSI?si=LBJspiWpWnq34VAY">Proxmox Installation</a>

<a href="https://www.youtube.com/watch?v=_u8qTN3cCnQ">Proxmox Disk Partition Setup</a>

<a href="https://youtu.be/TA0gZs0X_7o">Promox Networking</a>

<h1>Other Links to learn mmore about Proxmox</h1>
<a href="https://www.youtube.com/watch?v=LCjuiIswXGs&t=344s">Complete Proxmox Course Series Videos</a>

