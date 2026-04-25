# Linux-system-admin-practical
Practical application of linux system administration 

# Linux System Administration Labs

## Overview

This project demonstrates hands-on Linux system administration skills using Ubuntu Server in a virtualized lab environment. The labs simulate real-world system administration tasks including networking, security, monitoring, troubleshooting, storage management, automation, and containerization.

The environment was built and tested using virtual machines and command-line tools to replicate enterprise Linux administration scenarios.

---

## Skills Demonstrated

- Linux system administration (Ubuntu Server)
- Service and process management (systemctl, ps)
- Bash scripting and automation
- Network configuration (Netplan, DNS, connectivity testing)
- System troubleshooting (hardware, filesystem, performance)
- Security hardening and firewall configuration (UFW, SSH)
- Log management and analysis (journalctl, syslog)
- System monitoring (htop, nmon, glances)
- Containerization using Docker and Apache
- Network file sharing (NFS)
- Storage management (RAID 0 configuration)
- Backup and automation (tar, cron jobs)

---

## Lab Breakdown

### System Troubleshooting (IMPORTANT)
Used Linux diagnostic tools to analyze hardware, performance, and system activity.

- Checked hardware and CPU details using `lshw` and `lscpu`
- Monitored memory and performance using `free`, `top`, and `vmstat`
- Analyzed disk usage and partitions using `df`, `lsblk`, and `fdisk`
- Identified system activity using `w`, `lsof`, and `dmesg`

This lab demonstrates real-world troubleshooting skills used by system administrators. :contentReference[oaicite:0]{index=0}  

---

### Service and Process Management
Managed Linux services using systemctl, including creating and managing a custom daemon. :contentReference[oaicite:1]{index=1}  

---

### Bash Scripting
Created scripts to automate user creation and directory listing. :contentReference[oaicite:2]{index=2}  

---

### Network Configuration and Troubleshooting
Configured static IP addressing using Netplan and verified connectivity. :contentReference[oaicite:3]{index=3}  

---

### Docker and Apache Containerization
Installed Docker and deployed an Apache web server inside a container. :contentReference[oaicite:4]{index=4}  

---

### Security and Firewall Management
Performed system hardening, firewall configuration, and encryption using GPG. :contentReference[oaicite:5]{index=5}  

---

### Logging Management
Used journalctl and syslog tools to analyze system logs. :contentReference[oaicite:6]{index=6}  

---

### Monitoring Management
Used htop, nmon, glances, and Uptime Kuma for system monitoring. :contentReference[oaicite:7]{index=7}  

---

### NFS File Sharing
Configured a Network File System (NFS) server and client. :contentReference[oaicite:8]{index=8}  

---

### Filesystem and RAID Management
Created and mounted a RAID 0 array using mdadm. :contentReference[oaicite:9]{index=9}  

---

### Backups and Cron Jobs
Created backups using tar and automated tasks using cron scheduling. :contentReference[oaicite:10]{index=10}  

---

## Environment

- Ubuntu Server (Virtual Machine)
- Proxmox virtualization platform
- Command-line based administration

---

## Key Takeaways

- Developed practical Linux administration skills in a simulated enterprise environment  
- Gained real-world troubleshooting experience using command-line tools  
- Built foundational knowledge in networking, security, and automation  

---

## Future Improvements

- Add screenshots of lab outputs and configurations  
- Expand automation scripts  
- Integrate monitoring dashboards  
