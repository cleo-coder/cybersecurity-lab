<<<<<<< HEAD
&#x20;**End-to-End Penetration Testing Lab**



&#x20; **Overview**



This project demonstrates a full penetration testing workflow conducted in a controlled virtual lab environment. The objective was to simulate a real-world attack scenario, identify vulnerabilities, exploit them, and gain unauthorized access to a target system.



&#x20;  **Lab Environment**



* &#x20;Virtualization: Oracle VM VirtualBox
* &#x20;Attacker Machine: Kali Linux
* &#x20;Target Machine: Metasploitable 2
* &#x20;Network: Host-only (isolated)



&#x20; **Methodology**



&#x20; **1. Reconnaissance**



* &#x20;Performed network discovery to identify active hosts
* &#x20;Conducted service enumeration using Nmap



Full scan results: `recon/nmap-full.txt`

Example output:

!\[Nmap Scan](screenshots/02-nmap.png)



\---



&#x20;  **2. Exploitation**



* &#x20;Identified vulnerable FTP service (vsftpd 2.3.4)
* &#x20;Used Metasploit Framework to exploit known backdoor vulnerability
* &#x20;Successfully established a Meterpreter session



Full exploit log: `exploitation/metasploit-exploit-session.txt`

Exploit success:

!\[Meterpreter Session](screenshots/03.1-exploit.png)



\---



&#x20;  **3. Post-Exploitation**



\* Gained root-level access to the system

\* Performed system enumeration and verification



Root access proof:

!\[Root Access](screenshots/04-whoami.png)



\---



&#x20;  **Key Outcomes**



* &#x20;Successfully compromised a vulnerable system
* &#x20;Demonstrated full attack lifecycle
* &#x20;Gained hands-on experience with industry-standard tools



&#x20;  **Skills Demonstrated**



* &#x20;Network scanning (Nmap)
* &#x20;Exploitation (Metasploit)
* &#x20;Linux system navigation
* &#x20;Vulnerability identification
* &#x20;Virtual lab setup and management



&#x20;***Disclaimer***



This project was conducted in a controlled lab environment for educational purposes only.



=======
# cybersecurity-lab
End-to-end penetration testing lab simulating real-world attack scenarios using Kali Linux and Metasploitable 2. Includes network reconnaissance, vulnerability exploitation using Metasploit, and post-exploitation analysis with documented evidence.
>>>>>>> 7f12b3f40c0ddd99bed4416d2c735bd651949cac
