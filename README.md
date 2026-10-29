
# Kali Linux Pentesting Lab Setup

## Overview
This project documents my penetration testing lab setup using Kali Linux and Oracle VirtualBox. The lab provides a virtual environment for learning cybersecurity and practicing ethical hacking.

## Tools Used
- **Kali Linux:** Operating system for penetration testing.
- **Oracle VirtualBox:** Software used to run Kali Linux in a virtual machine.

## Network Configuration
- **Network Mode:** NAT Network
- **Network Name:** NatNetwork
- **IPv4 Network:** `10.0.0.0/24`
- **DHCP:** Enabled
- **IPv6:** Disabled
- **Virtual Cable:** Connected

## Setup Steps
1. Install Oracle VirtualBox.
2. Download and import the Kali Linux VirtualBox image.
3. Open the virtual machine settings.
4. Go to **Network → Adapter 1**.
5. Enable the network adapter.
6. Select **NAT Network**.
7. Choose `NatNetwork` and save the settings.
8. Start Kali Linux and test the network connection.

## Purpose
The purpose of this lab is to learn virtual machine configuration, network setup, and basic penetration testing in a controlled environment.

## Disclaimer
This lab is for educational purposes and authorized security testing only.
