# Penetration Testing Lab

## Project Overview
This project documents a controlled penetration testing exercise conducted in an isolated virtual lab. The assessment focused on identifying vulnerable services, evaluating security weaknesses, demonstrating exploitation techniques, and recommending defensive improvements.

## Lab Environment
- Kali Linux — penetration testing workstation
- Metasploitable 2 — intentionally vulnerable target machine
- Windows — additional lab target
- VirtualBox — virtualisation environment

## Tools and Technologies
- Nmap — network discovery and service enumeration
- Metasploit Framework — exploitation testing
- Meterpreter — post-exploitation session analysis
- Kali Linux — security testing environment

## Testing Methodology
1. **Reconnaissance:** Identified reachable lab systems and exposed network services using Nmap.
2. **Vulnerability Assessment:** Examined detected services and outdated software versions, including VSFTPD 2.3.4.
3. **Controlled Exploitation:** Used Metasploit in the authorised lab environment to evaluate exploitable weaknesses.
4. **Post-Exploitation Analysis:** Documented session establishment, process enumeration, session migration, and demonstrations of keylogging and screenshot capture.
5. **Reporting:** Summarised findings and proposed remediation measures.

## Key Security Lessons
- Outdated services increase exposure to known vulnerabilities.
- Unnecessary open ports expand the attack surface.
- Endpoint monitoring and least-privilege access reduce potential impact.
- Regular patching, segmentation, and security logging strengthen defensive resilience.

## Project Deliverables
- Penetration testing report with original lab screenshots (to be uploaded)
- Vulnerability assessment and exploitation findings
- Security remediation recommendations

## Scope and Disclaimer
All testing described in this project was conducted in a controlled educational lab using intentionally vulnerable or authorised virtual machines. The project does not involve unauthorised testing of live systems.

## Skills Demonstrated
Network reconnaissance | Vulnerability Assessment | Metasploit | Kali Linux | Security Reporting | Remediation Planning
