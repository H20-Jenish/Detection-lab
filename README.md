# Virtual Pentest Lab  

## Objective  
To build a virtualized environment replicating enterprise network infrastructure, enabling hands-on learning in penetration testing, cybersecurity defence, threat monitoring, and secure system configurations.  

## Network Layout Overview  
The lab consists of multiple zones, including:  
- Active Directory Zone: Centralized authentication using AD Server for internal client machines.  
- Security Zone: Tools like Wazuh, Security Onion and Kali Purple for threat detection and analysis.  
- DMZ Zone: Isolated IIS, CentOS and TrueNas server for hosting web applications.  
- Guest Zone: Controlled access for external devices.  
- Isolated Zone: Dedicated to offensive operations and vulnerability analysis.  

## Skills Learned  
### 1.1 [Network Security Architecture](https://github.com/H20-Jenish/Detection-lab/blob/main/1.0%20Network_Security_Architecture/1.0%20Network_Security_Architecture.md)
- Designed VLANs and subnets for secure network segmentation.  
- Configured pfSense firewalls with advanced NAT, VPN, and IDS/IPS rules.  
- Implemented SPAN ports for traffic mirroring and analysis.  

### 1.2 [Active Directory Security](https://github.com/H20-Jenish/Detection-lab/blob/main/2.0%20Active%20Directory%20Security/2.0%20Active%20Directory%20Security.md)
- Managed AD configurations, group policies, and user permissions.  
- Secured authentication with RBAC and OU structures.  
- Audited AD for weak configurations and privilege escalation paths.  

### 1.3 [Penetration Testing](https://github.com/H20-Jenish/Detection-lab/blob/main/3.0%20Penetration%20Testing/3.0%20Penetration%20Testing.md)
- Conducted vulnerability scans with Nmap, Nikto, and Nessus.  
- Performed red-team activities using Kali Linux tools, including Metasploit and Hydra.  
- Exploited vulnerabilities to test defences and lateral movement in AD.  

### 1.4 Threat Detection and Response  
- Configured Wazuh and Security Onion for log correlation, intrusion detection, and threat analysis.  
- Analyzed network traffic using Zeek and Suricata.  
- Monitored endpoints for malware using SIEM and HIDS tools.  

### 1.5 Digital Forensics  
- Performed disk and memory forensics using REMux and Flare VM.  
- Captured and analyzed packet data for breach investigation with Wireshark.  

### 1.6 System and Network Hardening  
- Hardened servers by disabling unused services and enforcing strict policies.  
- Secured IIS by implementing HTTPS and mitigating web application vulnerabilities.  
- Shared storage on TrueNAS was protected using encryption and ACLs.  

## Network Topology
![Pentest_lab layout drawio](https://github.com/user-attachments/assets/4082d708-9abf-4e0b-89a5-f43cd9cc7cf3)
<br> <a> Ref. 1: Network Layout for Lab </a></br>
