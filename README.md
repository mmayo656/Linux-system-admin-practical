# Linux System Administration Portfolio

This repository demonstrates hands-on Linux system administration skills using Ubuntu Server virtual machines in a Proxmox lab environment.

The project focuses on practical IT tasks used in help desk, IT support, NOC, junior system administration, and cybersecurity support roles, including troubleshooting, service management, firewall configuration, log analysis, Docker deployment, monitoring, NFS file sharing, RAID storage, backups, and cron automation.

---

## Career Goal

I am transitioning from patient care into IT, system administration, cybersecurity, and healthcare IT roles. This project is part of my hands-on portfolio showing practical technical ability beyond classroom theory.

---

## Key Skills Demonstrated

- Linux command-line administration
- Ubuntu Server management
- Proxmox virtual lab administration
- System troubleshooting and diagnostics
- Service management with systemctl
- Apache web server deployment
- Docker container deployment
- UFW firewall configuration
- SSH and access control hardening
- Log review using journalctl and syslog
- System monitoring with htop, nmon, glances, and Uptime Kuma
- NFS file sharing between Linux systems
- RAID storage configuration with mdadm
- Backup creation and restoration using tar
- Task automation using cron

---

## Environment

- Ubuntu Server virtual machines
- Proxmox virtualization platform
- Linux command-line interface
- Internal lab network
- Docker containers
- Apache HTTP Server
- NFS server/client configuration

---

## Project Sections

### 1. System Troubleshooting and Diagnostics

Used Linux diagnostic tools to inspect system performance, storage, memory, processes, users, disk activity, and kernel messages.

Tools used:

- `top`
- `htop`
- `vmstat`
- `iostat`
- `df`
- `fdisk`
- `dmesg`
- `lsof`
- `w`

Skills shown:

- Identifying running processes
- Reviewing CPU and memory usage
- Checking disk usage and partitions
- Reviewing disk I/O activity
- Viewing kernel and hardware messages
- Identifying logged-in users and active sessions

---

### 2. Security Hardening and Firewall Configuration

Configured Linux security controls using UFW, SSH settings, user account management, and GPG encryption.

Tasks completed:

- Created and managed Linux user accounts
- Reviewed password/shadow file information
- Encrypted files using GPG
- Configured SSH-related settings
- Enabled UFW firewall
- Denied insecure Telnet traffic on port 23
- Allowed required service ports
- Reviewed firewall status and numbered rules

Skills shown:

- Basic Linux hardening
- Firewall rule creation
- Access control awareness
- Secure file handling
- Troubleshooting firewall behavior

---

### 3. Apache Web Server and Docker

Deployed Apache inside a Docker container and configured access to Apache status and information pages.

Tasks completed:

- Installed and tested Docker
- Ran the Docker `hello-world` container
- Deployed Apache HTTP Server using Docker
- Created and served a basic web page
- Modified Apache configuration files
- Enabled server status and server information pages
- Tested restricted and allowed access behavior

Skills shown:

- Container deployment
- Web server configuration
- Apache module/configuration awareness
- Basic web service troubleshooting
- Understanding of host/container networking behavior

---

### 4. Log Management and Analysis

Used Linux logging tools to investigate system events, services, boot history, SSH activity, and application logs.

Tools used:

- `journalctl`
- `tail`
- `grep`
- `logrotate`

Tasks completed:

- Reviewed kernel logs
- Listed system boots
- Viewed logs from the current and previous boot
- Filtered logs by time
- Filtered logs by service
- Searched syslog entries with grep
- Reviewed and edited logrotate configuration

Skills shown:

- Reading system logs
- Filtering events
- Investigating service activity
- Understanding log rotation and retention

---

### 5. System Monitoring

Installed and used multiple monitoring tools to observe Linux system health and service uptime.

Tools used:

- `htop`
- `nmon`
- `glances`
- `Uptime Kuma`

Tasks completed:

- Monitored CPU, memory, disk, and process activity
- Viewed system resource usage in real time
- Deployed Uptime Kuma with Docker
- Added monitored services
- Verified uptime status and service availability

Skills shown:

- Performance monitoring
- Service health checks
- Docker-based monitoring deployment
- Basic infrastructure visibility

---

### 6. NFS File Sharing

Configured Network File System sharing between Linux systems.

Tasks completed:

- Installed NFS client/server components
- Mounted an NFS share from a client system
- Verified mounted file access
- Created and read files across the share

Skills shown:

- Linux file sharing
- Client/server configuration
- Mount testing
- Network storage troubleshooting

---

### 7. RAID Storage Management

Configured Linux software RAID using `mdadm`.

Tasks completed:

- Reviewed disk layout with `lsblk`
- Created a RAID array using two virtual disks
- Formatted the RAID device with ext4
- Mounted the RAID array
- Verified the mounted filesystem

Skills shown:

- Storage administration
- RAID configuration
- Filesystem creation
- Mount point management
- Disk verification

---

### 8. Backups and Cron Automation

Created backups using `tar` and automated tasks using cron.

Tasks completed:

- Created test files
- Created tar backup archives
- Added files to existing archives
- Extracted and restored backup files
- Created user cron jobs
- Created root cron jobs
- Verified scheduled tasks with crontab output

Skills shown:

- Backup creation
- Backup verification
- File restoration
- Task scheduling
- Automation basics

---

## Project Evidence

The following screenshots show real command output and system configurations performed during this project.

### System Troubleshooting


![Process monitoring using top](screenshots/01-troubleshooting/lab06ss1.png)

![Disk usage using df](screenshots/01-troubleshooting/lab06ss2.png)

![Disk I/O using iostat](screenshots/01-troubleshooting/lab06ss3.png)

![Kernel messages using dmesg](screenshots/01-troubleshooting/lab06ss4.png)

![Open files using lsof](screenshots/01-troubleshooting/lab06ss5.png)

![Active users using w](screenshots/01-troubleshooting/lab06ss6.png)


### Security Hardening

![UFW firewall status](screenshots/02-security/lab08firewallenabled.png)

![UFW firewall status](screenshots/02-security/lab08fwstatusverbose.png)

![UFW firewall status](screenshots/02-security/lab08ufwloggingon.png)

![UFW firewall status](screenshots/02-security/lab08ufwdeny23.png)

![UFW firewall status](screenshots/02-security/lab08ufwport8080.png)

![UFW firewall status](screenshots/02-security/lab08allowip.png)

![UFW firewall status](screenshots/02-security/lab08redteam.png)


### Apache and Docker

![Docker hello world](screenshots/03-apache-docker/lab07urlSS.png)

![Docker hello world](screenshots/03-apache-docker/lab07serverstatusSS.png)

![Docker hello world](screenshots/03-apache-docker/lab07serverinfoSS.png)

![Docker hello world](screenshots/03-apache-docker/lab07nanobottomSS.png)

![Docker hello world](screenshots/03-apache-docker/lab07nanouncommentSS.png)

![Docker hello world](screenshots/03-apache-docker/lab07serverstatusforb.png)

![Docker hello world](screenshots/03-apache-docker/lab07serverinfoforb.png)

![Docker hello world](screenshots/03-apache-docker/lab07containerSS.png)



### Log Analysis

![journalctl boot logs](screenshots/04-logs/lab09-pcrit.png)

![journalctl boot logs](screenshots/04-logs/lab09-ussh.png)

![journalctl boot logs](screenshots/04-logs/lab09mcben1UID-FUID.png)

![journalctl boot logs](screenshots/04-logs/lab09-k.png)

![journalctl boot logs](screenshots/04-logs/lab09daemonfix.png)


### Monitoring

![htop monitoring](screenshots/05-monitoring/lab10htop-run.png)

![htop monitoring](screenshots/05-monitoring/lab10htop-f6.png)

![htop monitoring](screenshots/05-monitoring/lab10htop-search.png)

![htop monitoring](screenshots/05-monitoring/lab10htop-f9.png)

![htop monitoring](screenshots/05-monitoring/lab10nmon-tools.png)

![htop monitoring](screenshots/05-monitoring/lab10glances.png)

![htop monitoring](screenshots/05-monitoring/lab10deploy-kuma.png)

![htop monitoring](screenshots/05-monitoring/lab10docker-test.png)

![htop monitoring](screenshots/05-monitoring/lab10kuma-uptime.png)


### NFS File Sharing

![NFS mount test](screenshots/06-nfs/lab11mount-work.png)

![NFS mount test](screenshots/06-nfs/lab11hello-write.png)




### RAID Storage

![RAID creation](screenshots/07-raid/lab12ext4.png)

![RAID creation](screenshots/07-raid/lab12raid1-2.png)

![RAID creation](screenshots/07-raid/lab12raid-mounted.png)




### Backups and Cron

![tar backup creation](screenshots/08-backups-cron/lab13files.png)

![tar backup creation](screenshots/08-backups-cron/lab13files-restored.png)

![tar backup creation](screenshots/08-backups-cron/lab13student-cron-nano.png)

![tar backup creation](screenshots/08-backups-cron/lab13root-cron-nano.png)

![tar backup creation](screenshots/08-backups-cron/lab13student-verify-cron.png)



---

## Real-World Application

This project shows practical skills used in entry-level IT and system administration work:

- Troubleshooting slow or unstable Linux systems
- Checking running processes and system resource usage
- Reviewing system and application logs
- Managing firewall rules and service access
- Deploying and validating Docker containers
- Monitoring service availability
- Sharing files between Linux systems
- Managing disks, filesystems, and RAID storage
- Creating backups and automating scheduled tasks

---

## Resume Relevance

This project supports my transition from healthcare/patient care into IT by showing practical Linux administration skills alongside my existing healthcare technology background, PACS troubleshooting experience, Windows administration labs, and cybersecurity education.

---

## Career Relevance

This portfolio is relevant to roles such as:

- Help Desk Technician
- IT Support Specialist
- Desktop Support Technician
- NOC Technician
- Junior Linux Administrator
- Junior System Administrator
- Healthcare IT Support Specialist
- PACS Support Analyst
- Cybersecurity Support Technician

---

## Next Improvements

Planned future improvements include:

- Adding more Bash automation scripts
- Expanding service troubleshooting examples
- Adding a networking-focused lab section
- Adding security auditing examples
- Linking this project with Windows Server and Active Directory portfolio work
