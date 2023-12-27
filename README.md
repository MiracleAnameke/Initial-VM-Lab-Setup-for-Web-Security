# Initial VM Lab Setup for Web Security

## Lab Overview

This lab involves the setup and verification of various virtual machines (VMs) essential for web security practices, including Kali Linux, Windows 10, Windows Server 2016, Ubuntu 18.04 LTS, and Metasploitable2. Students will perform tasks related to downloading, verifying, and configuring these environments.

## Preparation

- Ensure internet connectivity & VMware Workstation version 15.5.7 or above.
- Install 7zip on your host machine.
- Download required VMs: Kali Linux, Windows 10, Ubuntu 18.04 LTS, Windows Server 2016, and Metasploitable2.

## Lab Tasks and Screenshots

### Part 01: Download Client VM zip files and verify SHA1 checksums

- **Task**: Download the specified VMs and verify the SHA1 checksums.
- **Slide 01**: Screenshot showing the downloaded VM files.
  <img src="https://i.imgur.com/VFrsUX3.png" height="400px" width="auto" alt="downloaded VM files"/>
- **Slide 02**: Screenshot showing the SHA1 checksum results for each downloaded VM file.
  <img src="https://i.imgur.com/fFA8uHO.png" height="400px" width="auto" alt="SHA1 Checksum Verification"/>

### Part 02: Kali Linux VM Prep

- **Task**: Unzip Kali Linux VM, power on, login with provided credentials, ensure internet connectivity, update hostname and hosts file.
- **Slide 03**: Screenshot showing the Kali Linux VM login prompt, ping results confirming internet connectivity, updated hostname, and changes to the /etc/hosts file.
  <img src="https://i.imgur.com/57OCtj5.png" height="400px" width="auto" alt="Kali Linux VM Prep"/>

### Part 03: Windows 10 VM Prep

- **Task**: Set up and configure Windows 10 VM including network settings and computer name changes.
- **Slide 04**: Screenshot showing ipconfig results, ping to Kali Linux, updated computer name, and date.
  <img src="https://i.imgur.com/SMjk3ob.png" height="400px" width="auto" alt="Windows 10 VM Prep"/>

### Part 04: Windows Server 2016 Prep

- **Task**: Prepare Windows Server 2016 VM with specific IP and disable firewall settings.
- **Slide 05**: Screenshot showing successful pings from Kali Linux to the Windows Server using hostname and disabled firewall settings.
  <img src="https://i.imgur.com/e7YWn6n.png" height="400px" width="auto" alt="Windows Server 2016 Prep"/>

### Part 05: Metasploitable2 Server Prep

- **Task**: Prepare Metasploitable2 VM, adjust network settings and ensure connectivity.
- **Slide 06**: Screenshot showing successful pings from Kali Linux to Metasploitable2 using the hostname.
  <img src="https://i.imgur.com/nVIaC47.png" height="400px" width="auto" alt="Metasploitable2 Server Prep"/>

### Part 06: Ubuntu 18.04 LTS Web Server Prep

- **Task**: Set up Ubuntu 18.04 LTS as a web server, configure network settings, and test connectivity.
- **Slide 07**: Screenshot showing successful pings to the Ubuntu web server from Kali Linux, along with the output of the `uname -a` and `date` commands.
  <img src="https://i.imgur.com/OvwFxyB.png" height="400px" width="auto" alt="Ubuntu Web Server Prep"/>

### Part 07: LAMP Stack/Mutillidae Installation on Ubuntu Web Server

- **Task**: Install LAMP stack and Mutillidae on the Ubuntu server, and navigate to the Mutillidae page from Kali.
- **Slide 08**: Screenshot showing Mutillidae running on the Ubuntu server, accessed from Kali Linux.
  <img src="https://i.imgur.com/MtjhIxn.png" height="400px" width="auto" alt="LAMP Stack/Mutillidae Installation"/>


