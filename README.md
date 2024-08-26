# Exploring the Seven Domains of a Typical IT Infrastructure

**Author**: Osamudiamen Eweka  
**Course**: CYB-605-Z2 Principles of Cybersecurity  
**Institution**: Utica University

## Overview

This lab report explores the seven domains of a typical IT infrastructure, focusing on fundamental concepts of information systems security. It provides a hands-on demonstration of various tasks, including reviewing security controls on a Windows workstation, exploring devices on a LAN segment, connecting to a router-firewall device, and examining the network perimeter. The lab also includes research-based exercises to identify threats and security controls in the User Domain, as well as recommendations for additional security controls across different IT domains.

## Objectives

- Explore and understand the seven domains of a typical IT infrastructure: Workstation, LAN, LAN-to-WAN, WAN, Remote Access, and System/Application domains.
- Use command-line utilities, remote connections, and network devices to gather relevant system information.
- Identify common server roles and network devices.
- Apply security controls and measures to protect the IT infrastructure.
- Conduct independent research to address real-world security challenges and threats.

## Lab Setup

### Lab Environment Details

The lab environment consists of the following systems and tools:

- **Systems**:
  - vWorkstation (Windows: Server 2022)
  - Switch01 (Linux: Debian 11)
  - FileServer01 (FreeBSD)
  - pfSense-office (FreeBSD)
  - DomainController01 (Windows: Server 2019)
  - WebServer01 (Linux: Ubuntu 20)
  - RemoteWindows01 (Windows: Server 2019)
  - AttackLinux01 (Linux: Kali)

- **Software & Utilities**:
  - PuTTY
  - Ping
  - Open vSwitch
  - TrueNAS
  - pfSense
  - Traceroute
  - Nslookup
  - OpenVPN
  - OWASP Juice Shop

These tools were used to explore various aspects of a typical IT infrastructure, including network connectivity, security controls, and server roles.

## Hands-On Demonstrations

### 1. Exploring the Workstation Domain
Participants operated as a desktop support engineer and explored security controls on a Windows workstation. Key tasks included:

- Logging in as the primary user
- Verifying automatic system updates
- Analyzing Virus & Threat Protection settings
- Testing application installation restrictions
- Evaluating email security solutions

### 2. Exploring the LAN Domain
This segment focused on networking and network security within the LAN Domain. Participants explored the network configuration, reviewed the Address Resolution Protocol (ARP) table, and established remote connections to devices.

### 3. Exploring the LAN-to-WAN Domain
Participants broadened their exploration to include routing functions managed by the pfSense firewall/router software. Tasks included:

- Accessing the pfSense webGUI
- Reviewing NAT and firewall configurations
- Exploring routing configurations and static routes
- Running traceroutes to local and remote hosts

## Applied Learning

### 1. Exploring the WAN Domain
The WAN Domain exploration covered wide-area network connections between remote sites and the simulated public Internet. Key tasks involved inspecting the routing table and analyzing site-to-site VPN configurations.

### 2. Exploring the Remote Access Domain
This segment focused on secure remote access through VPN connections. Participants established secure tunnels, connected to internal resources, and verified DNS lookups.

### 3. Exploring the System/Application Domain
Participants examined critical systems and applications, such as domain controllers, web servers, and file servers. Tasks included:

- Navigating operating systems and executing commands
- Reviewing group policies and DNS entries
- Interacting with the OWASP Juice Shop application
- Exploring NAS configurations for redundancy and data security

## Research and Analysis

### Key Findings
- **User Domain Threats**: Phishing attacks and insider threats.
- **User Domain Security Controls**: User awareness training and access controls.
  
### Security Control Recommendations
- **Workstation Domain**: Endpoint protection software
- **LAN Domain**: Network segmentation
- **LAN-to-WAN Domain**: Intrusion prevention system (IPS)
- **WAN Domain**: Site-to-site VPN
- **Remote Access Domain**: Multi-factor authentication (MFA)
- **System/Application Domain**: Application whitelisting

## Conclusion

This lab provided a comprehensive exploration of IT infrastructure security, covering essential security practices across various domains. Through hands-on experience, participants gained valuable skills in securing an organization's IT assets, making informed decisions on applying security controls, and addressing real-world threats.

## References

- Eldardiry, H., Bart, E., Liu, J., Hanley, J., Price, B., & Brdiczka, O. (2013). Multi-Domain Information Fusion for Insider Threat Detection. IEEE Xplore. https://doi.org/10.1109/SPW.2013.14
- Ruotsalainen, P. (2013). Endpoint Protection Security System for an Enterprise. https://www.theseus.fi/handle/10024/62932
- OWASP. (n.d.). Juice Shop - Insecure Web Application for Training. OWASP. https://owasp.org/www-project-juice-shop/

For a complete list of references, please refer to the full lab report.


## Documentation

For more details, you can refer to the full lab report: [Seven Domains of a Typical IT Infrastructure](https://github.com/user-attachments/files/16739006/lab1.Exploring_the_Seven_Domains_of_a_Typical_IT_Infrastructure_4e_-_Osamudiamen_Eweka.resubmit.docx).

