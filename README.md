# Linux System Administration Portfolio
Practical application of linux system administration 

## Employer Value

This project demonstrates that I can:

- Work in a Linux command-line environment
- Troubleshoot system, storage, performance, and service issues
- Manage services using systemctl
- Review logs using journalctl and syslog
- Configure firewall rules using UFW
- Deploy and manage Docker containers
- Monitor system uptime and performance
- Configure NFS file sharing between systems
- Create RAID storage using mdadm
- Automate backups and scheduled tasks with tar and cron

## Overview

This repository documents a hands-on Linux system administration environment built with Ubuntu Server virtual machines. The project demonstrates practical IT skills including troubleshooting, service management, security hardening, log analysis, Docker container deployment, monitoring, NFS file sharing, RAID storage, backups, and cron automation.

The purpose of this portfolio is to show practical Linux administration ability for entry-level IT support, system administration, NOC, help desk, and cybersecurity roles.

The environment was built and tested using virtual machines and command-line tools to replicate enterprise Linux administration scenarios.

---

## Technologies Used

- Ubuntu Server
- Proxmox virtualization
- Bash
- systemd / systemctl
- journalctl
- UFW firewall
- Docker
- Apache HTTP Server
- Uptime Kuma
- htop
- nmon
- glances
- NFS
- mdadm RAID
- tar
- cron

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


---

## Career Relevance

This portfolio demonstrates practical Linux administration skills that apply directly to IT support, help desk, junior system administration, NOC technician, and cybersecurity support roles. The work shows experience with troubleshooting, service management, system monitoring, security controls, storage, networking, and automation.

## Project Evidence

### System Troubleshooting
![top process monitoring](screenshots/01-troubleshooting/top.png)
![disk usage with df](screenshots/01-troubleshooting/df.png)
![disk I/O with iostat](screenshots/01-troubleshooting/iostat.png)
![kernel messages with dmesg](screenshots/01-troubleshooting/dmesg.png)

### Security Hardening
![UFW firewall status](screenshots/02-security/ufw-status.png)
![GPG encrypted file](screenshots/02-security/gpg-encryption.png)

### Apache and Docker
![Docker hello world](screenshots/03-apache-docker/docker-hello-world.png)
![Apache homepage](screenshots/03-apache-docker/apache-homepage.png)
![Apache server status](screenshots/03-apache-docker/apache-server-status.png)

### Log Analysis
![journalctl boot logs](screenshots/04-logs/journalctl-boot.png)
![syslog grep cups](screenshots/04-logs/syslog-grep-cups.png)
![logrotate config](screenshots/04-logs/logrotate-config.png)

### Monitoring
![htop monitoring](screenshots/05-monitoring/htop.png)
![nmon monitoring](screenshots/05-monitoring/nmon.png)
![glances monitoring](screenshots/05-monitoring/glances.png)
![Uptime Kuma dashboard](screenshots/05-monitoring/uptime-kuma.png)

### NFS File Sharing
![NFS mount test](screenshots/06-nfs/nfs-mount.png)
![NFS file write test](screenshots/06-nfs/nfs-write-test.png)

### RAID Storage
![RAID creation](screenshots/07-raid/mdadm-create.png)
![RAID mounted](screenshots/07-raid/raid-mounted.png)

### Backups and Cron
![tar backup creation](screenshots/08-backups-cron/tar-backup.png)
![files restored](screenshots/08-backups-cron/files-restored.png)
![cron job configured](screenshots/08-backups-cron/cron-config.png)
