# Virtual Pentest Lab  

## Objective  
To build a virtualized environment replicating enterprise network infrastructure, enabling hands-on learning in penetration testing, cybersecurity defense, threat monitoring, and secure system configurations.  

## Network Layout Overview  
The lab consists of multiple zones, including:  
- Active Directory Zone: Centralized authentication using Windows Server 22.  
- Security Zone: Tools like Wazuh and Security Onion for threat detection and analysis.  
- DMZ Zone: Isolated IIS server for hosting web applications.  
- Guest Zone: Controlled access for external devices.  
- Isolated Zone: Dedicated for offensive operations and vulnerability analysis.  

## Skills Learned  
### 1. Network Security Architecture  
- Designed VLANs and subnets for secure network segmentation.  
- Configured pfSense firewalls with advanced NAT, VPN, and IDS/IPS rules.  
- Implemented SPAN ports for traffic mirroring and analysis.  

### 2. Active Directory Security  
- Managed AD configurations, group policies, and user permissions.  
- Secured authentication with RBAC and OU structures.  
- Audited AD for weak configurations and privilege escalation paths.  

### 3. Penetration Testing  
- Conducted vulnerability scans with Nmap, Nikto, and Nessus.  
- Performed red-team activities using Kali Linux tools, including Metasploit and Hydra.  
- Exploited vulnerabilities to test defenses and lateral movement in AD.  

### 4. Threat Detection and Response  
- Configured Wazuh and Security Onion for log correlation, intrusion detection, and threat analysis.  
- Analyzed network traffic using Zeek and Suricata.  
- Monitored endpoints for malware using SIEM and HIDS tools.  

### 5. Digital Forensics  
- Performed disk and memory forensics using REMux and Flare VM.  
- Captured and analyzed packet data for breach investigation with Wireshark.  

### 6. System and Network Hardening  
- Hardened servers by disabling unused services and enforcing strict policies.  
- Secured IIS by implementing HTTPS and mitigating web application vulnerabilities.  
- Protected shared storage on TrueNAS using encryption and ACLs.  

## Tools and Technologies  
- Network Security: pfSense, Wireshark, Elastic XDR.  
- Operating Systems: Windows Server 22, Windows 11 Pro, Windows 10 Pro, CentOS, TrueNAS.  
- Penetration Testing: Kali Linux, Burp Suite, Nikto, Nmap, Hydra.  
- Threat Monitoring: Wazuh, Security Onion, Zeek, Suricata, snort.  
- Digital Forensics: REMux, Flare VM, Autopsy.  
- Web Services: IIS and phpmyadmin for secure web application hosting.  
- Virtualization: VMware Workstation.  

## Network Topology
![Pentest_lab layout drawio](https://github.com/user-attachments/assets/74d8703c-a61b-43f4-b63f-99a016debf44)
<br> <a> Ref. 1: Network Layout for Lab </a></br>
