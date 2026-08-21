# Week 4 - Vulnerability Findings, Impact and Remediation
## Project 7: Penetration Testing Lab
## Objective
Analyze the vulnerability identified and exploited during the penetration testing exercise, document its security impact, and provide appropriate remediation recommendations.
## Vulnerability Identified
- Vulnerable Service: VSFTPD 2.3.4
- Service: FTP
- Port: 21/TCP
- Target: Metasploitable 2
- Vulnerability Type: Backdoor vulnerability
## Finding
The target system was running VSFTPD 2.3.4, a vulnerable version of the FTP service.
Testing in the controlled laboratory environment demonstrated that the vulnerable service could be exploited to obtain unauthorized command-line access to the target system.
## Impact
Successful exploitation resulted in root-level access to the target system.
An attacker with this level of access could potentially:
- Access sensitive files and system resources.
- Modify or delete files.
- Execute commands with administrative privileges.
- Compromise the confidentiality, integrity and availability of the system.
## Risk Assessment
Severity: Critical
The vulnerability is considered critical because successful exploitation resulted in root-level access to the target system.
## Remediation Recommendations
- Upgrade or replace the vulnerable VSFTPD version with a secure, supported version.
- Remove unnecessary FTP services where they are not required.
- Use secure file-transfer protocols such as SFTP where appropriate.
- Restrict access to FTP services using firewall rules and network segmentation.
- Monitor authentication and FTP activity for suspicious behavior.
- Regularly scan systems for outdated and vulnerable services.
## Evidence
Evidence collected during the assessment includes:
- Service enumeration results.
- VSFTPD 2.3.4 identification.
- Metasploit exploitation results.
- Command shell access.
- Root privilege verification.
- System information collected from the target.
## Conclusion
The assessment demonstrated that the vulnerable VSFTPD 2.3.4 service presented a critical security risk.
The successful exploitation and resulting root-level access demonstrate the importance of removing vulnerable services, applying security updates, restricting unnecessary network exposure, and continuously monitoring systems.
The findings from this assessment will be incorporated into the final penetration testing report.
