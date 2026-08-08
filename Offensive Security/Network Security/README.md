# NETWORK SECURITY with Nmap

# Project Overview 
Server network security testing using the Nmap tool to detect vulnerabilities before they are misused by attackers.

# Testing
**1. View and identify active hosts**
![discover](Images/host_discover.png)

**2. Identify what ports and services are currently active
![port](Images/service.png)

Three port open: 21,22,80. FTP services are not secure because they provide unencrypted data and can be intercepted by hackers on the same network.

**3. Exploit ftp service**

![ftp](Images/ftp.png)

The login attempt failed, but if exploited further the attacker will get the login credentials, for example by brute force attack.

#Pentesting Report

Report ID : P080826-0001
Severity Level : Medium-High

**1. Summary**
| Parameter | Data |
| --- | --- |
| Description | Network and port scanning tests to view and find vulnerabilities in the network |
| Risk | Medium-High : If exploited, an attacker can obtain credentials | 
| Tools Used | Nmap |
| Reference | mmammm |

**2. Result**

* Port 21,22: ftp & ssh open ports and potentially exploitable by attackers on the same network/if the IP address is known.
* The login attempt failed, but if exploited further the attacker will get the login credentials, for example by brute force attack. Further exploitation is needed to obtain credentials by brute force.

**3. Remediation**

* Turn off unused services or change to an unusual port, for example 222, 223, etc.
* Don't use FTP because it's not secure. Use something more secure like SFTP, FTPS, or SSH.
