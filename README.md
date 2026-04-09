# **End-to-End Penetration Testing Lab**

## 

## &#x20;**Overview**



This project demonstrates a full penetration testing workflow conducted in a controlled virtual lab environment. The objective was to simulate a real-world attack scenario, identify vulnerabilities, exploit them, and gain unauthorized access to a target system.



##### &#x20;**Lab Environment**



\* Virtualization: Oracle VM VirtualBox

\* Attacker Machine: Kali Linux

\* Target Machine: Metasploitable 2

\* Network: Host-only (isolated)

##### 

##### &#x20;**Methodology**

##### 

###### &#x20;1. Reconnaissance



\* Performed network discovery to identify active hosts

\* Conducted service enumeration using Nmap



Full scan results: `recon/nmap-full.txt`

Example output:

!\[Nmap Scan](screenshots/02-nmap.png)



\---



###### 2\. Exploitation



\* Identified vulnerable FTP service (vsftpd 2.3.4)

\* Used Metasploit Framework to exploit known backdoor vulnerability

\* Successfully established a Meterpreter session



Full exploit log: `exploitation/metasploit-exploit-session.txt`

Exploit success:

!\[Meterpreter Session](screenshots/03.1-exploit.png)



\---



###### 3\. Post-Exploitation



\* Gained root-level access to the system

\* Performed system enumeration and verification



Root access proof:

!\[Root Access](screenshots/04-whoami.png)



\---



##### &#x20;**Key Outcomes**



\* Successfully compromised a vulnerable system

\* Demonstrated full attack lifecycle

\* Gained hands-on experience with industry-standard tools



##### &#x20;**Skills Demonstrated**



\* Network scanning (Nmap)

\* Exploitation (Metasploit)

\* Linux system navigation

\* Vulnerability identification

\* Virtual lab setup and management



###### &#x20;**Disclaimer**



This project was conducted in a controlled lab environment for educational purposes only.



