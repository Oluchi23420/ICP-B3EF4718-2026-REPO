# Week 2 - Reconnaissance, Scanning and Enumeration
## Project 7: Penetration Testing Lab
## Objective
Perform reconnaissance, network scanning and service enumeration against the Metasploitable 2 target in the controlled penetration testing laboratory.
## Target
- Metasploitable 2
- Target IP Address: 10.0.2.4
## Attacker Machine
- Kali Linux
- IP Address: 10.0.2.3
## Tasks Completed
- Confirmed communication between Kali Linux and Metasploitable 2.
- Identified the target IP address.
- Performed network reconnaissance and service enumeration.
- Identified FTP running on port 21.
- Identified the VSFTPD 2.3.4 service.
- Identified the VSFTPD 2.3.4 service as a potential vulnerability requiring further investigation.
## Tools Used
- Kali Linux
- Nmap
## Findings
The scan identified an FTP service running on port 21. Further enumeration revealed that the target was running VSFTPD version 2.3.4.
The identified service was considered a potential security weakness and was selected for further vulnerability assessment and controlled exploitation.
## Conclusion
The reconnaissance and enumeration phase successfully identified the target's FTP service and the VSFTPD 2.3.4 version. The findings provided the basis for the exploitation phase in Week 3.
