<h1>My HomeLab</h1>

<h2>Description</h2>
Welcome to my Home Lab project, where I leverage the power of Proxmox to create a versatile and dynamic environment for testing and experimenting with various technologies. In this project, I've set up a robust home-based laboratory that serves as a playground for honing my skills in virtualization, networking, and system administration.
<br />


<h2>Components</h2>

- <b>Ryzen 5 5600X 6-core Processor</b>
- <b>MSI B550-A Pro Mobo</b>
- <b>128gb DDR4 RAM</b>
- <b>PNY 3060 GPU</b>
- <b>Be Quiet! A240mm AIO</b>

<h2>Software Used </h2>

- <b>ProxMox</b> 

<h2>Set Up and Use</h2>

<p align="center">
</b>ProxMox Dashboard: <br/>
<img src="https://i.imgur.com/vMmtNNH.png/> height="80%" width="80%"
<br />
<br />
  </p>
Current VMs and Containers:  <br/>
<br/>

## Win 10 VM with GPU Passthrough

The Win 10 VM utilizes GPU passthrough (NVIDIA RTX 3060) for coding, gaming, learning, and remote research.

### Purpose

- Go-to VM for coding, gaming, learning, and research.
- GPU passthrough for optimal gaming performance.

### Usage

1. Set up GPU passthrough in Proxmox for the NVIDIA RTX 3060.
2. Install Windows 10 on the VM and configure for remote access.
3. Utilize the VM for coding, gaming, learning, and remote research purposes.

## Kali Linux

Kali Linux is a specialized VM for penetration testing and ethical hacking.

### Purpose

- Provide a secure and controlled environment for ethical hacking and penetration testing.

### Usage

- **Security Auditing:** Identify vulnerabilities in systems and networks through comprehensive security audits.
- **Wireless Network Assessment:** Test and secure wireless networks using tools like Aircrack-ng.
- **Web Application Testing:** Assess and secure web applications by identifying and fixing vulnerabilities.
- **Forensic Analysis:** Utilize forensic tools for digital forensics and incident response.
- **Password Cracking:** Test password strength using tools like John the Ripper and Hashcat.
- **Network Scanning:** Conduct network reconnaissance with tools like Nmap.
  
## PiHole Container

The Pi-hole container serves as a network-wide ad blocker, DNS sinkhole, and DHCP server. It enhances privacy, security, and network performance by blocking unwanted ads and malicious domains at the network level.

### Features and Functionality

- **Ad Blocking:** Pi-hole blocks ads, trackers, and malicious domains at the DNS level, providing an ad-free browsing experience for all devices on the network.
- **Web Interface:** Access the Pi-hole web interface to monitor statistics, manage blacklists/whitelists, and configure settings.
- **DHCP Server:** Optionally, Pi-hole can function as a DHCP server, simplifying IP address management on the network.
- **Logging and Analytics:** Pi-hole logs DNS queries, allowing for detailed analytics on network activity and blocked requests.

## Ubuntu VM

The Ubuntu VM is set up for hands-on learning with Linux.

### Purpose

- Provide a platform to gain familiarity with the Linux operating system.
- **Learning Objectives:** Use this VM to practice Linux command-line operations, file manipulation, and system administration tasks.
- **Software Exploration:** Experiment with installing, updating, and removing software packages using the package manager.
- **Networking Concepts:** Explore networking configurations, IP addressing, and basic network troubleshooting.
- **Security Practices:** Learn about user authentication, firewall configuration, and system updates.

## TrueNAS

TrueNAS is deployed for efficient network-attached storage.

### Purpose

- Centralized storage solution for data management and backups.

### Features

- **Network Storage:** TrueNAS provides centralized and secure storage accessible over the network.
- **Data Management:** Use TrueNAS for efficient data organization, sharing, and backup purposes.
- **Web Interface:** Manage TrueNAS settings and configurations through the user-friendly web interface.

## Portainer with Containers

Portainer is used for container management, providing an easy-to-use interface for Docker.

### Containers

1. **Homarr (Dashboard):** Containerized dashboard for system monitoring and metrics.
2. **Mealie:** Containerized self-hosted recipe manager and meal planner.
3. **Speedtest Tracker:** Containerized tool for tracking and logging internet speed test results.

### Features

- **Container Management:** Use Portainer to easily manage and monitor Docker containers.
- **Dashboard (Homarr):** Monitor system metrics at a glance.
- **Mealie:** Organize and plan meals with this self-hosted solution.
- **Speedtest Tracker:** Log and track internet speed test results.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
