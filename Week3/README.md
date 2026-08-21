# Week 3 - Vulnerability Exploitation and Access Verification
## Project 7: Penetration Testing Lab
## Objective
Test the identified VSFTPD 2.3.4 vulnerability in the controlled penetration testing environment and verify the level of access obtained on the target system.
## Target
- Metasploitable 2
- Target IP Address: 10.0.2.4
- Vulnerable Service: VSFTPD 2.3.4
- Service Port: 21/TCP
## Attacker Machine
- Kali Linux
- IP Address: 10.0.2.3
## Tools Used
- Metasploit Framework
- Kali Linux
## Exploitation
The VSFTPD 2.3.4 service identified during the reconnaissance and enumeration phase was investigated for exploitation.
The Metasploit Framework was used within the isolated penetration testing laboratory to test the identified vulnerability.
The exploitation was successful and resulted in a command shell on the Metasploitable 2 target.
## Access Verification
After obtaining the command shell, basic commands were used to verify the level of access and collect system information.
Commands used included:
- whoami
- id
- hostname
- uname -a
- pwd
- ls -la
## Results
The verification showed that:
- The current user was root.
- The user ID was uid=0(root).
- The hostname was metasploitable.
- The operating system was Linux.
- The kernel was 2.6.24-16-server.
The results confirmed that the obtained shell had root-level privileges.
## Security Impact
Successful exploitation of the vulnerable service resulted in unauthorized command-line access with root-level privileges.
Root-level access could allow an attacker to access, modify, or delete system resources and potentially compromise the entire target system.
## Evidence Collected
Evidence from the exploitation and verification phase included:
- Metasploit exploitation output
- Successful command shell session
- whoami output
- id output
- hostname output
- uname -a output
- pwd output
- ls -la output
## Conclusion
The identified VSFTPD 2.3.4 vulnerability was successfully exploited in the controlled penetration testing laboratory.
The resulting root-level command shell demonstrated the significant security impact of the vulnerable service.
The findings will be used in the subsequent penetration testing report.
