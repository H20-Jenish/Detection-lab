# Virtual Pentest Lab  

## Objective  
To build a virtualized environment replicating enterprise network infrastructure, enabling hands-on learning in penetration testing, cybersecurity defence, threat monitoring, and secure system configurations.  

## Network Layout Overview  
The lab consists of multiple zones, including:  
- Active Directory Zone: Centralized authentication using AD Server for internal client machines.  
- Security Zone: Tools like Wazuh, Snort/Suricata and Kali Purple for threat detection and analysis.  
- DMZ Zone: Isolated IIS, CentOS and TrueNas server for hosting web applications.  
- Guest Zone: Controlled access for external devices.  
- Isolated Zone: Dedicated to offensive operations and vulnerability analysis.  

## Skills Learned  
### 1.0 [Network Security Architecture](https://github.com/H20-Jenish/Detection-lab/blob/main/1.0%20Network_Security_Architecture/1.0%20Network_Security_Architecture.md)
- Designed VLANs and subnets for secure network segmentation.  
- Configured pfSense firewalls with advanced NAT, VPN, and IDS/IPS rules.  
- Implemented SPAN ports for traffic mirroring and analysis.  

### 2.0 [Active Directory Security](https://github.com/H20-Jenish/Detection-lab/blob/main/2.0%20Active%20Directory%20Security/2.0%20Active%20Directory%20Security.md)
- Managed AD configurations, group policies, and user permissions.  
- Secured authentication with RBAC and OU structures.  
- Audited AD for weak configurations and privilege escalation paths.  

### 3.0 [Penetration Testing](https://github.com/H20-Jenish/Detection-lab/blob/main/3.0%20Penetration%20Testing/3.0%20Penetration%20Testing.md)
- Conducted vulnerability scans with Nmap and OpenVAS.  
- Performed red-team activities using Kali Linux tools, including Metasploit and Hydra.  
- Exploited vulnerabilities to test defences and lateral movement in AD.  

### 4.0 [Threat Detection and Response](https://github.com/H20-Jenish/Detection-lab/blob/main/4.0%20Threat%20Detection%20and%20Response/4.0%20Threat%20Detection%20and%20Response.md)  
- Configured Wazuh and Elastic Stack for log correlation, intrusion detection, and threat analysis.  
- Analyzed network traffic using Zeek and Suricata.  
- Monitored endpoints for malware using SIEM and HIDS tools.  

### 5.0 [Digital Forensics](https://github.com/H20-Jenish/Detection-lab/blob/main/5.0%20Digital%20Forensics/5.0%20Digital%20Forensics.md)  
- Performed disk and memory forensics using REMux and Flare VM.  
- Captured and analyzed packet data for breach investigation with Wireshark.  

### 6.0 [System and Network Hardening](https://github.com/H20-Jenish/Detection-lab/blob/main/6.0%20System%20and%20Network%20Hardening/6.0%20System%20and%20Network%20Hardening.md)  
- Hardened servers by disabling unused services and enforcing strict policies.  
- Secured IIS by implementing HTTPS and mitigating web application vulnerabilities.  
- Shared storage on TrueNAS was protected using encryption and ACLs.

### 7.0 [File Storage Security](https://github.com/H20-Jenish/Detection-lab/blob/main/7.0%20File%20Storage%20Security/7.0%20File%20Storage%20Security.md)    
- Configure TrueNAS for secure file storage, integrate it with Active Directory for user authentication, and implement encryption techniques to protect data at rest and in transit.
- Establish access control mechanisms with authentication and authorization, and use Wazuh to monitor file storage activities for anomalies or potential threats.
- Identify and address common storage-related risks, such as unauthorized access and data leakage, by applying appropriate security measures.
  
## Network Topology
![Detection lab layout drawio](https://github.com/user-attachments/assets/076afc4e-4f68-49cf-a909-b8a9464ea968)
<br> <a> Ref. 1: Network Layout for Lab </a></br>




