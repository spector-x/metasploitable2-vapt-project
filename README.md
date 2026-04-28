⭐ Metasploitable 2 VAPT Project (Real-World Lab)


📌 Project Overview

Performed a full Vulnerability Assessment and Penetration Testing (VAPT) on Metasploitable 2 in a controlled lab environment using Kali Linux.

This project simulates real-world attack scenarios including reconnaissance, exploitation, and post-exploitation.

🎯 Objectives
- Discover live hosts using ARP scan
- Perform full port scanning using Nmap
- Enumerate services (FTP, SMB, NetBIOS)
- Exploit critical vulnerabilities
- Gain system-level access


## 🛠️ Tools & Technologies
- Nmap  
- arp-scan  
- Metasploit Framework  
- enum4linux  
- smbclient

  
## 🔍 Methodology

1. **Reconnaissance**
   - ARP scan for network discovery  
   - Ping for connectivity  

2. **Scanning**
   - Full Nmap scan (`-A -p-`)  

3. **Enumeration**
   - SMB shares  
   - NetBIOS info  
   - Service versions  

4. **Exploitation**
   - vsftpd backdoor  
   - Samba usermap script  
   - UnrealIRCd backdoor  
   - DistCC RCE
  
     
## 💣 Exploits & Results

| Service | Vulnerability | Result |
|--------|-------------|--------|
| FTP | vsftpd Backdoor | Shell Access |
| SMB | Samba Exploit | Remote Access |
| IRC | UnrealIRCd Backdoor | Shell Access |
| DistCC | RCE | Command Execution |


## 📄 Full Report
📂 Available in `/report` folder

## ⭐ Key Highlights
- Hands-on VAPT project  
- Real exploitation performed  
- Multiple critical vulnerabilities identified  
